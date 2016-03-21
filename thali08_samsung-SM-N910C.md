#### Test 62548124e8057a0_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-21 14:21:43.117  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
03-21 14:21:43.727 11036 11036 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 14:21:43.732 11036 11036 D AndroidRuntime: CheckJNI is OFF
03-21 14:21:43.732 11036 11036 D AndroidRuntime: readGMSProperty: start
03-21 14:21:43.732 11036 11036 D AndroidRuntime: readGMSProperty: already setted!!
03-21 14:21:43.732 11036 11036 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 14:21:43.732 11036 11036 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 14:21:43.732 11036 11036 D AndroidRuntime: readGMSProperty: end
03-21 14:21:43.732 11036 11036 D AndroidRuntime: addProductProperty: start
03-21 14:21:43.827 11036 11036 E AffinityControl: AffinityControl: registerfunction enter
03-21 14:21:43.847 11036 11036 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 14:21:43.862  3410  3434 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 14:21:43.872  3410  3434 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 14:21:43.907  3410  3434 W ActivityManager: mDVFSHelper.acquire()
03-21 14:21:43.912  3410  3434 D FocusedStackFrame: Set to : 0
03-21 14:21:43.917  3410  3434 V WindowManager: addAppToken: AppWindowToken{d4c236e token=Token{3e859ae9 ActivityRecord{1cc2a770 u0 com.test.thalitest/.MainActivity t40}}} to stack=1 task=40 at 0
03-21 14:21:43.922  3410  3434 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:21:43.922  3410  3434 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:21:43.922  3410  3434 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:21:43.922  3410  3434 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:21:43.927  3410  3580 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 14:21:43.927  3410  3580 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 14:21:43.932  3410  3580 D SecWifiDisplayUtil: Metadata value : none
03-21 14:21:43.932  3410  3580 V WindowManager: Adding window Window{206cbe21 u0 d0 Starting com.test.thalitest} at 2 of 6 (after Window{1d99dc1f u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher})
03-21 14:21:43.937 11054 11054 E Zygote  : MountEmulatedStorage()
03-21 14:21:43.937 11054 11054 E Zygote  : v2
03-21 14:21:43.937 11054 11054 I libpersona: KNOX_SDCARD checking this for 10011
03-21 14:21:43.937 11054 11054 I libpersona: KNOX_SDCARD not a persona
03-21 14:21:43.942 11054 11054 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:21:43.942 11054 11054 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:21:43.942 11054 11054 E Zygote  : accessInfo : 0
03-21 14:21:43.942 11054 11054 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 14:21:43.942  3410  3434 I ActivityManager: Start proc 11054:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-21 14:21:43.942  3410  3434 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 14:21:43.942  3410  3434 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-21 14:21:43.942  3410  3434 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 14:21:43.942  3410  3434 D InputDispatcher: Focused application set to: xxxx
03-21 14:21:43.942  3410  3434 D InputDispatcher: Focus left window: 4031
03-21 14:21:43.947 11036 11036 D AndroidRuntime: Shutting down VM
03-21 14:21:43.947  3410  3580 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 14:21:43.952  3410  3580 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 14:21:43.952  2859  2859 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-21 14:21:43.962 11054 11054 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:21:43.962 11054 11054 D ActivityThread: Added TimaKeyStore provider
03-21 14:21:43.972  3410  4700 V WindowOrientationListener: setCurrentAppOrientation :-1
03-21 14:21:43.972  3410  4700 V WindowOrientationListener: setCurrentAppOrientation enable auto rotation
03-21 14:21:43.972  3410  4700 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false
03-21 14:21:43.972  3410  4700 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 14:21:43.972  3410  4700 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 14:21:43.972  3410  4700 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 14:21:43.972  3410  4700 D PowerManagerService: setKeyboardVisibility: false
03-21 14:21:43.972  3410  4700 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 14:21:43.972  3410  3578 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{206cbe21 u0 d0 Starting com.test.thalitest}
03-21 14:21:43.977  3410  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
03-21 14:21:43.977  3410  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 14:21:43.977  3410  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3410 uid:1000
03-21 14:21:43.977  3410  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 14:21:43.977  3410  3410 V ActivityManager: Display changed displayId=0
03-21 14:21:43.997  3410  4700 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{1cc2a770 u0 com.test.thalitest/.MainActivity t40}
03-21 14:21:44.012  2859  3009 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
03-21 14:21:44.012  2859  3588 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
03-21 14:21:44.017  4031  4031 V ActivityThread: updateVisibility : ActivityRecord{2bcc3a9c token=android.os.BinderProxy@2043f8c7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-21 14:21:44.017  4031  4031 D Launcher: onTrimMemory. Level: 20
03-21 14:21:44.172  3410  6093 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 14:21:44.207 11054 11054 D SecWifiDisplayUtil: Metadata value : none
,03-21 14:21:44.252 11054 11054 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-21 14:21:44.262 11054 11054 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1072-1074)
03-21 14:21:44.262 11054 11054 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 14:21:44.282 11054 11071 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-21 14:21:44.282 11054 11054 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fecc454}
03-21 14:21:44.282 11054 11054 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 14:21:44.282 11054 11054 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 14:21:44.302 11054 11054 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 14:21:44.302 11054 11054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 14:21:44.302 11054 11054 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 14:21:44.327 11054 11054 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-21 14:21:44.327 11054 11054 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-21 14:21:44.327 11054 11054 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-21 14:21:44.412 11054 11094 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-21 14:21:44.437 11054 11054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 14:21:44.452 11054 11054 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 14:21:44.457 11054 11054 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 14:21:44.457 11054 11054 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-21 14:21:44.462 11054 11054 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-21 14:21:44.467 11054 11054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 14:21:44.467 11054 11054 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 14:21:44.527 11054 11107 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 14:21:44.532  3410  3773 V WindowManager: Adding window Window{2211f0ce u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (before Window{206cbe21 u0 d0 Starting com.test.thalitest})
,03-21 14:21:44.532  3410  4781 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-21 14:21:44.532  3410  4781 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 14:21:44.532  3410  4781 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-21 14:21:44.532  3410  3410 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-21 14:21:44.537  3410  3410 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-21 14:21:44.537  3410  3410 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-21 14:21:44.537  3410  3410 I EnterpriseSharedDevicePolicy: Get Result: -1
03-21 14:21:44.537  3410  3410 I EnterpriseSharedDevicePolicy: status: false
03-21 14:21:44.537  3410  3410 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-21 14:21:44.542  3410  3410 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 14:21:44.552 11054 11054 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-21 14:21:44.552 11054 11054 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-21 14:21:44.557 11054 11054 D SecWifiDisplayUtil: Metadata value : none
,03-21 14:21:44.562  2859  2859 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,03-21 14:21:44.567  3410  4415 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 14:21:44.572  3410  4415 D InputDispatcher: Focus entered window: 11054,
,03-21 14:21:44.577  3410  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
03-21 14:21:44.577  3410  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 14:21:44.577  3410  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3410 uid:1000
03-21 14:21:44.577  3410  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 14:21:44.577 11054 11054 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-21 14:21:44.577 11054 11107 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 14:21:44.577 11054 11107 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae82fb50 ,&mEglDisplay = 1 , &mEglConfig = -1266872048 
,03-21 14:21:44.577 11054 11107 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-21 14:21:44.577 11054 11107 D OpenGLRenderer: Enabling debug mode 0
,03-21 14:21:44.582 11054 11107 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-21 14:21:44.582 11054 11054 V ActivityThread: updateVisibility : ActivityRecord{12cc061c token=android.os.BinderProxy@1e8112ee {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-21 14:21:44.582  3410  3582 I PowerManagerService: [PWL] Off : 15s ago
,03-21 14:21:44.652  3410  4781 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 14:21:44.657  3410  3580 I ActivityManager: Displayed Component not be shown by security: +518ms (total +740ms)
,03-21 14:21:44.657  3725  3725 D PanelView: There is/are notification(s) 
,03-21 14:21:44.662  3410  3580 W ActivityManager: mDVFSHelper.release()
,03-21 14:21:44.662  3410  3580 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cc2a770 u0 com.test.thalitest/.MainActivity t40} time:71471
03-21 14:21:44.662  2859 11069 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
03-21 14:21:44.662  2859  3588 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,03-21 14:21:44.692 11054 11054 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 14:21:44.692 11054 11054 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e8112ee time:71500
,03-21 14:21:44.717 11054 11054 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11054
,03-21 14:21:44.817 11054 11054 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 14:21:44.912 11054 11111 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626384256
,03-21 14:21:44.922 11054 11111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 14:21:44.922 11054 11111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 14:21:44.922 11054 11111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 14:21:44.922 11054 11111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 14:21:44.922 11054 11111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 14:21:44.922 11054 11111 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c60e95 added. We now have 1 listener(s)
,03-21 14:21:44.927 11054 11111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-21 14:21:44.932 11054 11111 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 14:21:44.932 11054 11111 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 14:21:44.932 11054 11111 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 14:21:44.932 11054 11071 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 14:21:44.942 11054 11111 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1982e338 added. We now have 1 listener(s)
03-21 14:21:44.942 11054 11111 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 14:21:44.952 11054 11111 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 14:21:44.952 11054 11111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-21 14:21:44.952 11054 11111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 14:21:44.952 11054 11111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 14:21:44.952 11054 11111 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 14:21:44.957 11054 11111 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 14:21:44.962 11054 11111 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 14:21:44.967 11054 11111 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 14:21:44.967 11054 11111 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 14:21:44.967 11054 11111 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-21 14:21:44.972 11054 11111 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 14:21:44.972 11054 11054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 14:21:44.972 11054 11054 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 14:21:45.002 11054 11054 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 14:21:45.387 11054 11118 W jxcore-log: Initializing JXcore engine
03-21 14:21:45.387 11054 11118 W jxcore-log: JXcore engine is ready
,03-21 14:21:45.412  4818  4818 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-21 14:21:45.412  4818  4818 E audit   : type=1400 msg=audit(1458566505.407:195): avc:  denied  { ioctl } for  pid=11118 comm="Thread-1544" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4120 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-21 14:21:45.412  3410  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-21 14:21:45.412  3410  3576 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-21 14:21:45.412  4818  4818 E audit   :  SEPF_SM-N910C_5.1.1_0035
03-21 14:21:45.412  4818  4818 E audit   : type=1300 msg=audit(1458566505.407:195): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=969048d8 items=0 ppid=2901 ppcomm=main pid=11118 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1544" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 14:21:45.412  4818  4818 E audit   : type=1320 msg=audit(1458566505.407:195): 
,03-21 14:21:45.412  3410  3576 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-21 14:21:45.412  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:21:45.412  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:21:45.417  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:21:45.417  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 14:21:45.417 11054 11118 W jxcore-log: Starting JXcore engine
,03-21 14:21:45.427 11119 11119 E Zygote  : MountEmulatedStorage()
03-21 14:21:45.427 11119 11119 E Zygote  : v2
03-21 14:21:45.427 11119 11119 I libpersona: KNOX_SDCARD checking this for 1000
03-21 14:21:45.427 11119 11119 I libpersona: KNOX_SDCARD not a persona
03-21 14:21:45.427 11119 11119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:21:45.427 11119 11119 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:21:45.427 11119 11119 E Zygote  : accessInfo : 0
03-21 14:21:45.432 11119 11119 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:21:45.432  3410  3575 I ActivityManager: Start proc 11119:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-21 14:21:45.447 11119 11119 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 14:21:45.447 11119 11119 D ActivityThread: Added TimaKeyStore provider
,03-21 14:21:45.457  3410  3435 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{354c7c32 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{144d83 11119:com.samsung.android.securitylogagent/1000}
,03-21 14:21:45.467 11054 11118 W jxcore-log: Platform android
03-21 14:21:45.467 11054 11118 W jxcore-log: 
03-21 14:21:45.467 11054 11118 W jxcore-log: Process ARCH arm
03-21 14:21:45.467 11054 11118 W jxcore-log: 
,03-21 14:21:45.477 11119 11119 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-21 14:21:45.477 11119 11119 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-21 14:21:45.477  3410  4046 I ActivityManager: Killing 10194:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-21 14:21:45.557 11054 11118 I jxcore-log: JXcore Cordova bridge is ready!
03-21 14:21:45.557 11054 11118 I jxcore-log: 
03-21 14:21:45.557 11054 11118 W jxcore-log: JXcore engine is started
,03-21 14:21:45.562 11054 11111 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 14:21:45.567 11054 11054 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 14:21:45.692  3410  3619 V AlarmManager: waitForAlarm result :8
,03-21 14:21:45.767  3410  3864 E Watchdog: !@Sync 2 [03-21 14:21:45.769]
,03-21 14:21:46.177  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:21:46.177  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:21:46.177  3410  4783 D BatteryService: online:4, current avg:-35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-192
03-21 14:21:46.177  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:21:46.177  3410  4783 D BatteryService: stay LED for fully charged
,03-21 14:21:46.177  3410  3410 I MotionRecognitionService: Plugged
03-21 14:21:46.177  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:21:46.177  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:21:46.177  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:21:46.177  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:21:46.177  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:21:46.182  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:21:46.182  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:21:46.182  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:21:46.197  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:21:46.197  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:21:46.197  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:21:46.197  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:21:46.932  3410  3691 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/40_task.xml.bak
,03-21 14:21:48.127  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:21:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:21:49.632  3410  6093 D SSRM:n  : SIOP:: AP = 320, PST = 351 (W:8), CUR = -35, LCD = 0
,03-21 14:21:50.657  3410  3619 V AlarmManager: waitForAlarm result :4
,03-21 14:21:50.672  3410  3410 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,03-21 14:21:50.677  3410  3410 I BackgroundCompactionService: onStart. jobID=801
,03-21 14:21:50.682  3410  3410 I BackgroundCompactionService: onStart done. jobID=801
,03-21 14:21:50.682  3410 11136 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,03-21 14:21:50.682  3410 11136 I BackgroundCompactionService: compact_memory command done
,03-21 14:21:50.867 10544 10615 I Finsky  : [1485] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-21 14:21:50.867 10544 10544 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-21 14:21:51.547 11054 11118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 14:21:51.547 11054 11118 I jxcore-log: 
,03-21 14:21:51.552 11054 11118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 14:21:51.552 11054 11118 I jxcore-log: 
,03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 14:21:51.552 11054 11118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 14:21:51.552 11054 11118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 14:21:51.557 11054 11118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 14:21:51.557 11054 11118 I jxcore-log: 
,03-21 14:21:51.557 11054 11118 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 14:21:51.557 11054 11118 I jxcore-log: 
,03-21 14:21:51.882 11054 11118 I jxcore-log: Unit Test app is loaded
03-21 14:21:51.882 11054 11118 I jxcore-log: 
,03-21 14:21:51.887 11054 11118 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 14:21:51.887 11054 11118 I jxcore-log: 
,03-21 14:21:51.892 11054 11054 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 14:21:51.892 11054 11118 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-21 14:21:51.892 11054 11118 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-21 14:21:51.892 11054 11118 I jxcore-log: 
,03-21 14:21:51.892 11054 11118 I jxcore-log: My device name is: samsung-SM-N910C
03-21 14:21:51.892 11054 11118 I jxcore-log: 
,03-21 14:21:53.127  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:21:53.967  3410  3589 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-21 14:21:53.997  3410  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-21 14:21:54.247 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 14:21:54.247 11054 11118 I jxcore-log: 
,03-21 14:21:54.457 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-21 14:21:54.457 11054 11118 I jxcore-log: 
,03-21 14:21:54.462 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-21 14:21:54.462 11054 11118 I jxcore-log: 
,03-21 14:21:54.462 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-21 14:21:54.462 11054 11118 I jxcore-log: 
,03-21 14:21:54.487 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-21 14:21:54.487 11054 11118 I jxcore-log: 
,03-21 14:21:54.492 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-21 14:21:54.492 11054 11118 I jxcore-log: 
,03-21 14:21:54.497 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-21 14:21:54.497 11054 11118 I jxcore-log: 
,03-21 14:21:54.527 10338 10495 V xAnalytics: xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,03-21 14:21:55.712 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 14:21:55.712 11054 11118 I jxcore-log: 
,03-21 14:21:55.722 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-21 14:21:55.722 11054 11118 I jxcore-log: 
,03-21 14:21:55.727 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-21 14:21:55.727 11054 11118 I jxcore-log: 
,03-21 14:21:55.802 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-21 14:21:55.802 11054 11118 I jxcore-log: 
,03-21 14:21:55.832 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-21 14:21:55.832 11054 11118 I jxcore-log: 
,03-21 14:21:55.912 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-21 14:21:55.912 11054 11118 I jxcore-log: 
,03-21 14:21:55.917 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-21 14:21:55.917 11054 11118 I jxcore-log: 
,03-21 14:21:55.917 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-21 14:21:55.917 11054 11118 I jxcore-log: 
,03-21 14:21:55.932 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-21 14:21:55.932 11054 11118 I jxcore-log: 
,03-21 14:21:55.942 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-21 14:21:55.942 11054 11118 I jxcore-log: 
,03-21 14:21:56.002 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-21 14:21:56.002 11054 11118 I jxcore-log: 
,03-21 14:21:56.007 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-21 14:21:56.007 11054 11118 I jxcore-log: 
,03-21 14:21:56.017 11054 11118 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-21 14:21:56.017 11054 11118 I jxcore-log: 
,03-21 14:21:56.307  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:21:56.307  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:21:56.307  3410  3434 D BatteryService: online:4, current avg:-159, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-237
03-21 14:21:56.307  3410  3434 D BatteryService: stay LED for fully charged
03-21 14:21:56.307  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:21:56.312  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:21:56.312  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:21:56.312  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:21:56.312  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:21:56.317  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:21:56.317  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:21:56.317  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:21:56.327  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 14:21:56.327  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:21:56.342  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:21:56.342  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:21:56.342  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:21:56.342  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:21:58.127  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:21:59.562  3410  3619 V AlarmManager: waitForAlarm result :4
,03-21 14:21:59.587  3410  3582 I PowerManagerService: [PWL] Off : 30s ago
,03-21 14:21:59.642  3410  6093 D SSRM:n  : SIOP:: AP = 330, PST = 348 (W:9), CUR = -159, LCD = 0
,03-21 14:21:59.997  3410  3619 V AlarmManager: waitForAlarm result :8
,03-21 14:22:03.132  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:22:06.452  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:22:06.452  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:22:06.452  3410  4029 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:104
,03-21 14:22:06.452  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:22:06.462  3410  3410 I MotionRecognitionService: Plugged
03-21 14:22:06.462  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:22:06.462  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:22:06.462  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
03-21 14:22:06.462  3410  4029 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,03-21 14:22:06.462  3410  4029 D BatteryService: stay LED for fully charged,
,03-21 14:22:06.477  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:22:06.477  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:22:06.477  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:22:06.497  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:22:06.497  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:22:06.507  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:22:06.507  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:06.507  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:06.507  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:22:09.437  3410  3619 V AlarmManager: waitForAlarm result :4
,03-21 14:22:09.452  3410  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{21609dcf u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE} DELIVERED for app ProcessRecord{337c5ce0 4332:com.google.android.gms.persistent/u0a14}
,03-21 14:22:09.472  3410  3410 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,03-21 14:22:09.472  3410  3410 V AlarmManagerEXT: <AppSync3 Whitelist>
03-21 14:22:09.472  3410  3410 V AlarmManagerEXT: (AppSync) ### 0 added ###
,03-21 14:22:09.482  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-21 14:22:09.482  3725  3725 I PERF    : received broadcast android.intent.action.TIME_TICK
03-21 14:22:09.482  3725  3725 D KeyguardUpdateMonitor: handleTimeUpdate
,03-21 14:22:09.507  3725  3725 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-21 14:22:09.517  3725  3725 D SecKeyguardClockView: HomeTimezone(): 1
,03-21 14:22:09.527  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.527  3725  3725 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 14:22:09.532  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 14:22:09.547  3410  4749 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 14:22:09.577  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.577  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.582  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.587  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.587  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.592  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.612  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:22:09.622  3410  4749 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 14:22:09.642  3410  4700 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-21 14:22:09.647  3410  6093 D SSRM:n  : SIOP:: AP = 310, PST = 345 (W:10), CUR = 11, LCD = 0
,03-21 14:22:09.662  3410  3966 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 14:22:09.677  4332  4332 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:09.682  4332 11193 I VacuumService: Vacuum at: now=1458566529687 tag=VacuumService
,03-21 14:22:09.702  3410  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{20bc77c7 u0 com.google.android.gms.gcm.ACTION_SCHEDULE} DELIVERED for app ProcessRecord{337c5ce0 4332:com.google.android.gms.persistent/u0a14}
,03-21 14:22:09.837  3410  4783 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 14:22:09.902  3410  3966 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 14:22:10.252  4332  4343 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@293f62e0)
,03-21 14:22:10.522  4332 11212 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 10769 seconds from now (1458566530527)
,03-21 14:22:10.562  3410  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6643ede u0 com.google.android.gms.gcm.ACTION_SCHEDULE} DELIVERED for app ProcessRecord{337c5ce0 4332:com.google.android.gms.persistent/u0a14}
,03-21 14:22:10.732  4332 11200 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-21 14:22:10.737  4332 11200 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 14:22:11.042  3410  3852 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 14:22:11.172  3410  4131 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-21 14:22:11.217  9227  9227 D FactoryTest: User mode
,03-21 14:22:11.222  9227  9227 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,03-21 14:22:11.222  9227  9227 D MTPRx   : still no open session command from host, so toast
,03-21 14:22:11.222  9227  9227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1661 android.content.ContextWrapper.startActivity:338 android.content.ContextWrapper.startActivity:338 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,03-21 14:22:11.222  9227  9227 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1673 android.app.ContextImpl.startActivity:1662 android.content.ContextWrapper.startActivity:338 android.content.ContextWrapper.startActivity:338 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,03-21 14:22:11.232  9227  9227 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:98043
,03-21 14:22:11.232  3410  3734 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-21 14:22:11.242  3410  3734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,03-21 14:22:11.247  3410  3734 W ActivityManager: mDVFSHelper.acquire()
,03-21 14:22:11.252  3410  3734 V WindowManager: addAppToken: AppWindowToken{cfa9751 token=Token{bc5b478 ActivityRecord{18da01db u0 com.android.settings/.SettingsReceiverActivity t41}}} to stack=1 task=41 at 0
,03-21 14:22:11.252  3410  3734 D PowerManagerService: setKeyboardVisibility: false
,03-21 14:22:11.257  3410  3734 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,03-21 14:22:11.272  3410  3734 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{18da01db u0 com.android.settings/.SettingsReceiverActivity t41}
,03-21 14:22:11.277  3410  3734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 14:22:11.277  3410  3734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 14:22:11.277  3410  3734 D InputDispatcher: Focused application set to: xxxx
03-21 14:22:11.277  3410  3734 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 14:22:11.277  3410  3734 D InputDispatcher: Focus left window: 11054
,03-21 14:22:11.277  9227  9227 E MTPRx   : started activity for popup
03-21 14:22:11.282  4332 11200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-21 14:22:11.282  4332 11200 I System.out: (HTTPLog)-Static: isShipBuild true
03-21 14:22:11.282  4332 11200 I System.out: (HTTPLog)-Thread-263-733858772: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-21 14:22:11.282  4332 11200 I System.out: (HTTPLog)-Thread-263-733858772: SMARTBONDING_FEATURE_ENABLED is true
03-21 14:22:11.282  4332 11200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-21 14:22:11.287  2872  3385 D EnterpriseController: netId is 0
03-21 14:22:11.287  2872  3385 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,03-21 14:22:11.302  3410  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
03-21 14:22:11.302  3410  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 14:22:11.302  3410  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3410 uid:1000
03-21 14:22:11.302  3410  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-21 14:22:11.317  4332 11200 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-21 14:22:11.317  4332 11200 I qtaguid : Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4332, getuid(): 10014
,03-21 14:22:11.322  3410  6093 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 14:22:11.342  9227  9227 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-21 14:22:11.342  9227  9227 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-21 14:22:11.342  9227  9227 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
03-21 14:22:11.342  9227  9227 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 14:22:11.347  9227  9227 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 14:22:11.347  9227  9227 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 14:22:11.347  9227  9227 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-21 14:22:11.357  9227  9227 D SecWifiDisplayUtil: Metadata value : none
,03-21 14:22:11.367  9227  9227 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,03-21 14:22:11.367  3410  4783 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 14:22:11.367  3410  4783 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 14:22:11.367  3410  4783 D InputDispatcher: Focused application set to: xxxx
03-21 14:22:11.367  3410  4783 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 14:22:11.367  3410  4783 D InputDispatcher: Focus entered window: 11054
,03-21 14:22:11.372  3410  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
03-21 14:22:11.372  3410  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 14:22:11.372  3410  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3410 uid:1000
03-21 14:22:11.372  3410  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-21 14:22:11.372  3410  4131 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-21 14:22:11.372  3410  4131 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@8ece0b7 attribute=null, token = android.os.BinderProxy@2e76c1c9
,03-21 14:22:11.407  4332 11200 I qtaguid : Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4332, getuid(): 10014
,03-21 14:22:11.437  9227  9227 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,03-21 14:22:11.442  9227  9227 D PhoneWindow: *FMB* installDecor mIsFloating : true
03-21 14:22:11.442  9227  9227 D PhoneWindow: *FMB* installDecor flags : 8388610
,03-21 14:22:11.462  3410  4030 D ActivityManager:  Launching com.test.thalitest, updated priority
,03-21 14:22:11.462  3410  4030 D PowerManagerService: setKeyboardVisibility: false
,03-21 14:22:11.462  3410  4030 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{1cc2a770 u0 com.test.thalitest/.MainActivity t40}
,03-21 14:22:11.492 11054 11054 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
03-21 14:22:11.492 11054 11054 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
03-21 14:22:11.492 11054 11054 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
03-21 14:22:11.492 11054 11054 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,03-21 14:22:11.497  3410  4749 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-21 14:22:11.497  3410  4749 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 14:22:11.497  3410  4749 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-21 14:22:11.497  3410  3410 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-21 14:22:11.497  3410  3410 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-21 14:22:11.502  3410  3410 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-21 14:22:11.502  3410  3410 I EnterpriseSharedDevicePolicy: Get Result: -1
03-21 14:22:11.502  3410  3410 I EnterpriseSharedDevicePolicy: status: false
03-21 14:22:11.502  3410  3410 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 14:22:11.502  3410  3410 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-21 14:22:11.502 11054 11054 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-21 14:22:11.502 11054 11054 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-21 14:22:11.512 11054 11054 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3867426d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f36ab95, 16908290=android.view.AbsSavedState$1@f36ab95}, android:focusedViewId=100}]}]
03-21 14:22:11.512 11054 11054 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
03-21 14:22:11.512 11054 11054 V ActivityThread: updateVisibility : ActivityRecord{12cc061c token=android.os.BinderProxy@1e8112ee {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-21 14:22:11.512 11054 11054 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-21 14:22:11.512 11054 11054 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
03-21 14:22:11.512 11054 11054 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e8112ee time:98321
,03-21 14:22:11.797  3410  3852 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 14:22:11.822  4332 11200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 14:22:11.822  4332 11200 I qtaguid : Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4332, getuid(): 10014
,03-21 14:22:11.827  3410  6093 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 14:22:11.962  3410  3434 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 14:22:11.972  4332 11200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 14:22:11.972  4332 11200 I qtaguid : Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4332, getuid(): 10014
,03-21 14:22:12.062  3410  4131 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 14:22:12.092  4332 11200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 14:22:12.092  4332 11200 I qtaguid : Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4332, getuid(): 10014
,03-21 14:22:12.212  3410  4415 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 14:22:12.222  3410  4749 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-21 14:22:12.227  4332  4332 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:12.232  4332  4332 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 14:22:12.317  4332 11200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 14:22:12.317  2872  3385 D EnterpriseController: netId is 0
03-21 14:22:12.317  2872  3385 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,03-21 14:22:12.322  4332 11200 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
03-21 14:22:12.322  4332 11200 I qtaguid : Tagging socket 77 with tag 1000040100000000{268436481,0} uid 10014, pid: 4332, getuid(): 10014
,03-21 14:22:12.377  4332 11200 I qtaguid : Tagging socket 89 with tag 1000040100000000{268436481,0} uid 10014, pid: 4332, getuid(): 10014
,03-21 14:22:12.812  4332 11200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 14:22:12.812  4332 11200 I qtaguid : Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 4332, getuid(): 10014
,03-21 14:22:14.252  3410  3575 W ActivityManager: mDVFSHelper.release()
,03-21 14:22:15.767  3410  3864 E Watchdog: !@Sync 3 [03-21 14:22:15.770]
,03-21 14:22:16.592  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:22:16.592  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:22:16.592  3410  4030 D BatteryService: online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:106
,03-21 14:22:16.592  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:22:16.592  3410  4030 D BatteryService: stay LED for fully charged
,03-21 14:22:16.602  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:22:16.602  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:22:16.602  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:22:16.602  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:22:16.612  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:22:16.612  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:22:16.612  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:22:16.632  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:22:16.632  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:22:16.642  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:22:16.642  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:16.642  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:16.642  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:22:19.587  3410  3582 I PowerManagerService: [PWL] Off : 50s ago
,03-21 14:22:19.662  3410  6093 D SSRM:n  : SIOP:: AP = 300, PST = 340 (W:11), CUR = 67, LCD = 0
,03-21 14:22:23.137  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:22:26.717  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:22:26.722  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:22:26.722  3410  3966 D BatteryService: online:4, current avg:79, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:82
,03-21 14:22:26.722  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:22:26.722  3410  3966 D BatteryService: stay LED for fully charged
,03-21 14:22:26.732  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:22:26.732  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:22:26.732  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:22:26.732  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:22:26.742  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:22:26.742  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:22:26.742  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:22:26.762  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:22:26.762  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:22:26.772  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:22:26.772  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:26.772  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:26.772  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:22:29.692  3410  6093 D SSRM:n  : SIOP:: AP = 290, PST = 336 (W:12), CUR = 79, LCD = 0
,03-21 14:22:36.857  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:22:36.857  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:22:36.857  3410  3773 D BatteryService: online:4, current avg:77, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:68
,03-21 14:22:36.862  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:22:36.867  3410  3410 I MotionRecognitionService: Plugged
03-21 14:22:36.867  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:22:36.872  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:22:36.872  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:22:36.872  3410  3773 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
,03-21 14:22:36.872  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:22:36.882  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:22:36.882  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:22:36.882  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:22:36.902  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:22:36.902  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:22:36.912  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:22:36.912  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:36.912  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:36.912  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:22:39.717  3410  6093 D SSRM:n  : SIOP:: AP = 290, PST = 332 (W:12), CUR = 77, LCD = 0
,03-21 14:22:43.142  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:22:44.592  3410  3582 I PowerManagerService: [PWL] Off : 75s ago
,03-21 14:22:45.772  3410  3864 E Watchdog: !@Sync 4 [03-21 14:22:45.774]
,03-21 14:22:46.997  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:22:46.997  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:22:46.997  3410  3852 D BatteryService: online:4, current avg:71, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
03-21 14:22:46.997  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:22:46.997  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:22:47.007  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:22:47.007  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:22:47.007  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:22:47.007  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:22:47.022  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:22:47.022  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:22:47.022  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:22:47.042  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:22:47.042  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:22:47.052  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:22:47.052  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:47.052  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:47.052  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:22:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:22:49.747  3410  6093 D SSRM:n  : SIOP:: AP = 280, PST = 325 (W:12), CUR = 71, LCD = 0
,03-21 14:22:57.132  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:22:57.137  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:22:57.137  3410  4749 D BatteryService: online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,03-21 14:22:57.137  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:22:57.137  3410  4749 D BatteryService: stay LED for fully charged
,03-21 14:22:57.147  3410  3410 I MotionRecognitionService: Plugged
03-21 14:22:57.147  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:22:57.147  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:22:57.147  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:22:57.152  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:22:57.152  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:22:57.152  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:22:57.172  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:22:57.172  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:22:57.182  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:22:57.182  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:57.182  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:22:57.182  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:22:59.777  3410  6093 D SSRM:n  : SIOP:: AP = 280, PST = 320 (W:12), CUR = 66, LCD = 0
,03-21 14:22:59.997  3410  3619 V AlarmManager: waitForAlarm result :8
,03-21 14:23:03.152  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:23:06.107  4332  4908 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-21 14:23:07.272  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:23:07.272  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:23:07.272  3410  3434 D BatteryService: online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,03-21 14:23:07.277  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:23:07.277  3410  3434 D BatteryService: stay LED for fully charged
,03-21 14:23:07.287  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:23:07.287  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:23:07.287  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:23:07.287  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:23:07.302  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:07.302  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:07.302  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:23:07.322  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:23:07.322  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:23:07.332  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:23:07.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:07.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:07.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:09.807  3410  6093 D SSRM:n  : SIOP:: AP = 280, PST = 312 (W:12), CUR = 60, LCD = 0
,03-21 14:23:14.592  3410  3582 I PowerManagerService: [PWL] Off : 105s ago
,03-21 14:23:15.782  3410  3864 E Watchdog: !@Sync 5 [03-21 14:23:15.783]
,03-21 14:23:17.412  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:23:17.412  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:23:17.412  3410  4749 D BatteryService: online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
,03-21 14:23:17.412  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:23:17.412  3410  4749 D BatteryService: stay LED for fully charged
,03-21 14:23:17.422  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:23:17.422  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:23:17.422  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:23:17.422  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:23:17.432  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:23:17.432  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:17.432  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:23:17.452  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 14:23:17.457  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:23:17.462  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:23:17.462  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:17.467  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:17.467  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:19.832  3410  6093 D SSRM:n  : SIOP:: AP = 280, PST = 305 (W:14), CUR = 56, LCD = 0
,03-21 14:23:23.157  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:23:27.547  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:23:27.547  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:23:27.547  3410  3434 D BatteryService: online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,03-21 14:23:27.552  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:23:27.557  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:23:27.557  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:23:27.557  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:23:27.557  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:23:27.562  3410  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,03-21 14:23:27.562  3410  3434 D BatteryService: stay LED for fully charged
,03-21 14:23:27.577  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:27.577  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:27.577  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:23:27.592  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:23:27.592  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:23:27.607  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:23:27.607  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:27.607  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:27.607  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:29.367  3410  3619 V AlarmManager: waitForAlarm result :4
,03-21 14:23:29.397  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 14:23:29.402  3725  3725 I PERF    : received broadcast android.intent.action.TIME_TICK
,03-21 14:23:29.402  3725  3725 D KeyguardUpdateMonitor: handleTimeUpdate
,03-21 14:23:29.417  3725  3725 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-21 14:23:29.422  3725  3725 D SecKeyguardClockView: HomeTimezone(): 1
,03-21 14:23:29.427  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.432  3725  3725 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 14:23:29.437  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
,03-21 14:23:29.467  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.472  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.472  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.477  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.477  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.482  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.497  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:23:29.857  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 294 (W:14), CUR = 51, LCD = 0
,03-21 14:23:37.687  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:23:37.687  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:23:37.687  3410  4700 D BatteryService: online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-21 14:23:37.692  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:23:37.692  3410  4700 D BatteryService: stay LED for fully charged
,03-21 14:23:37.702  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:23:37.702  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:23:37.702  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:23:37.702  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:23:37.707  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:23:37.707  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:23:37.707  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:23:37.727  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:23:37.727  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:23:37.737  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:23:37.742  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:37.742  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:37.742  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:39.887  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 290 (W:14), CUR = 48, LCD = 0
,03-21 14:23:43.162  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:23:45.787  3410  3864 E Watchdog: !@Sync 6 [03-21 14:23:45.790]
,03-21 14:23:47.827  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:23:47.827  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:23:47.827  3410  4781 D BatteryService: online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,03-21 14:23:47.827  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:23:47.837  3410  4781 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-21 14:23:47.837  3410  4781 D BatteryService: stay LED for fully charged,
,03-21 14:23:47.842  3410  3410 I MotionRecognitionService: Plugged
03-21 14:23:47.842  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:23:47.842  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:23:47.842  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:23:47.852  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:47.852  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:47.852  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:23:47.872  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:23:47.872  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:23:47.882  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:23:47.882  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:47.882  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:47.887  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:23:49.592  3410  3582 I PowerManagerService: [PWL] Off : 140s ago
,03-21 14:23:49.922  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 286 (W:14), CUR = 47, LCD = 0
,03-21 14:23:57.967  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:23:57.967  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:23:57.967  3410  4029 D BatteryService: online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,03-21 14:23:57.967  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:23:57.967  3410  4029 D BatteryService: stay LED for fully charged
,03-21 14:23:57.977  3410  3410 I MotionRecognitionService: Plugged
03-21 14:23:57.977  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:23:57.977  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:23:57.977  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:23:57.987  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:23:57.987  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:23:57.987  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:23:58.007  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:23:58.007  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:23:58.022  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:23:58.022  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:58.022  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:23:58.022  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:23:59.952  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:16), CUR = 46, LCD = 0
,03-21 14:23:59.997  3410  3619 V AlarmManager: waitForAlarm result :8
,03-21 14:24:03.167  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:24:08.102  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:24:08.102  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:24:08.102  3410  3435 D BatteryService: online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,03-21 14:24:08.107  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:24:08.112  3410  3435 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-21 14:24:08.112  3410  3435 D BatteryService: stay LED for fully charged,
,03-21 14:24:08.117  3410  3410 I MotionRecognitionService: Plugged
03-21 14:24:08.117  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:24:08.117  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:24:08.117  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:24:08.127  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:24:08.127  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:24:08.127  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:24:08.147  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:24:08.147  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:24:08.157  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:08.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:08.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:08.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:24:09.977  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 278 (W:16), CUR = 42, LCD = 0
,03-21 14:24:15.797  3410  3864 E Watchdog: !@Sync 7 [03-21 14:24:15.797]
,03-21 14:24:18.242  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:24:18.242  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:24:18.242  3410  3852 D BatteryService: online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,03-21 14:24:18.242  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:24:18.252  3410  3852 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-21 14:24:18.252  3410  3852 D BatteryService: stay LED for fully charged,
03-21 14:24:18.252  3410  3410 I MotionRecognitionService: Plugged
03-21 14:24:18.252  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:24:18.252  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:24:18.252  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:24:18.267  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:24:18.267  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:18.267  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:24:18.287  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:24:18.287  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:24:18.297  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:18.297  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:18.297  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:18.297  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:24:20.012  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:16), CUR = 41, LCD = 0
,03-21 14:24:23.172  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:24:28.377  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:24:28.377  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:24:28.377  3410  3773 D BatteryService: online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,03-21 14:24:28.382  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:24:28.382  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:24:28.392  3410  3410 I MotionRecognitionService: Plugged
03-21 14:24:28.392  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:24:28.392  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:24:28.392  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:24:28.402  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:24:28.402  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:28.402  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:24:28.422  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:24:28.422  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:24:28.432  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:28.432  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:28.432  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:28.432  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:24:29.592  3410  3582 I PowerManagerService: [PWL] Off : 180s ago
,03-21 14:24:30.042  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 275 (W:16), CUR = 40, LCD = 0
,03-21 14:24:38.517  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:24:38.517  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:24:38.517  3410  4030 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,03-21 14:24:38.522  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:24:38.522  3410  4030 D BatteryService: stay LED for fully charged
,03-21 14:24:38.532  3410  3410 I MotionRecognitionService: Plugged
03-21 14:24:38.532  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:24:38.532  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:24:38.532  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:24:38.542  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:24:38.542  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:38.542  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:24:38.562  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:24:38.562  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:24:38.572  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:38.572  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:38.572  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:38.572  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:24:40.072  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:18), CUR = 39, LCD = 0
,03-21 14:24:43.177  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:24:45.802  3410  3864 E Watchdog: !@Sync 8 [03-21 14:24:45.806]
,03-21 14:24:48.652  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:24:48.657  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:24:48.657  3410  4415 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-21 14:24:48.657  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:24:48.662  3410  3410 I MotionRecognitionService: Plugged
03-21 14:24:48.662  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:24:48.667  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:24:48.667  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:24:48.667  3410  4415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-21 14:24:48.667  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:24:48.677  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:24:48.677  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:48.677  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:24:48.697  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:24:48.697  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:24:48.707  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:48.707  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:48.707  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:48.707  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:24:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:24:50.102  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:18), CUR = 37, LCD = 0
,03-21 14:24:58.792  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:24:58.792  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:24:58.792  3410  4046 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-21 14:24:58.797  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:24:58.797  3410  4046 D BatteryService: stay LED for fully charged
,03-21 14:24:58.802  3410  3410 I MotionRecognitionService: Plugged
03-21 14:24:58.807  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:24:58.807  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:24:58.807  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:24:58.817  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:24:58.817  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:24:58.817  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:24:58.837  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:24:58.837  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:24:58.847  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:24:58.847  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:24:58.847  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:24:58.847  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:25:00.137  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 272 (W:18), CUR = 37, LCD = 0
,03-21 14:25:03.182  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:25:08.932  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:25:08.932  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:25:08.932  3410  4783 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,03-21 14:25:08.932  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:25:08.937  3410  4783 D BatteryService: stay LED for fully charged
,03-21 14:25:08.942  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:25:08.942  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:25:08.942  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:25:08.942  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:25:08.952  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:25:08.952  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:08.952  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:25:08.972  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:25:08.972  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:25:08.982  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:08.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:08.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:08.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:25:10.167  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:18), CUR = 37, LCD = 0
,03-21 14:25:14.597  3410  3582 I PowerManagerService: [PWL] Off : 225s ago
,03-21 14:25:15.812  3410  3864 E Watchdog: !@Sync 9 [03-21 14:25:15.812]
,03-21 14:25:19.067  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:25:19.072  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:25:19.072  3410  3966 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
03-21 14:25:19.072  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:25:19.077  3410  3966 D BatteryService: stay LED for fully charged
,03-21 14:25:19.082  3410  3410 I MotionRecognitionService: Plugged
03-21 14:25:19.082  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:25:19.082  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:25:19.082  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:25:19.092  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:25:19.092  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:19.092  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:25:19.112  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:25:19.112  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:25:19.122  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:19.122  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:19.122  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:19.122  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:25:20.202  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 271 (W:20), CUR = 36, LCD = 0
,03-21 14:25:23.187  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:25:29.207  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:25:29.207  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:25:29.207  3410  3734 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,03-21 14:25:29.212  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:25:29.217  3410  3734 D BatteryService: stay LED for fully charged
03-21 14:25:29.222  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:25:29.222  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:25:29.222  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:25:29.222  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:25:29.232  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:25:29.232  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:29.232  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:25:29.247  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:25:29.247  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:25:29.262  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:25:29.262  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:25:29.262  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:29.262  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:25:30.232  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:20), CUR = 35, LCD = 0
,03-21 14:25:39.347  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:25:39.347  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:25:39.347  3410  3434 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
03-21 14:25:39.352  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:25:39.352  3410  3434 D BatteryService: stay LED for fully charged
,03-21 14:25:39.362  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:25:39.362  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:25:39.362  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:25:39.362  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:25:39.372  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:25:39.372  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:25:39.372  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:25:39.397  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:25:39.397  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:25:39.407  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:25:39.407  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:39.407  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:39.407  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:25:40.247  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:20), CUR = 34, LCD = 0
,03-21 14:25:43.197  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:25:43.442  3410  3608 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-21 14:25:43.447  3410  3608 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
03-21 14:25:43.452  3410  3607 D TimaService: TimaServiceHandler.handleMessage what =1,
,03-21 14:25:43.467  3410  3608 I TLC_TIMA_PKM_initialize: initializing...
,03-21 14:25:43.467  3410  3608 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
03-21 14:25:43.467  3410  3608 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
,03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: root = 0, root_len = 1
03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
,03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: device_id = 0x0
03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: tlc_open() was called
,03-21 14:25:43.472  3410  3608 I TZ: mc_tlc_communication: Opening MobiCore device
,03-21 14:25:43.477  3410  3608 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,03-21 14:25:43.482  3410  3608 I TZ: mc_tlc_communication: Opening the session
,03-21 14:25:43.497  3410  3608 I TZ: mc_tlc_communication: tlc_open() succeeded
,03-21 14:25:43.507  3410  3608 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-21 14:25:45.817  3410  3864 E Watchdog: !@Sync 10 [03-21 14:25:45.820]
,03-21 14:25:48.357  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-21 14:25:48.357  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-21 14:25:48.372  3410  3608 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
03-21 14:25:48.372  3410  3608 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 14:25:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:25:49.482  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:25:49.482  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:25:49.482  3410  4749 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-21 14:25:49.487  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:25:49.492  3410  4749 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-21 14:25:49.492  3410  4749 D BatteryService: stay LED for fully charged,
,03-21 14:25:49.497  3410  3410 I MotionRecognitionService: Plugged
03-21 14:25:49.497  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:25:49.497  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:25:49.497  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:25:49.507  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:25:49.507  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:25:49.507  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:25:49.527  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:25:49.527  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:25:49.537  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:49.537  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:49.537  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:49.537  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:25:50.287  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:20), CUR = 33, LCD = 0
,03-21 14:25:50.387  3410  3423 I art     : Background sticky concurrent mark sweep GC freed 71750(5MB) AllocSpace objects, 139(2MB) LOS objects, 20% free, 30MB/37MB, paused 2.577ms total 119.933ms
,03-21 14:25:59.617  3410  4131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:25:59.617  3410  4131 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:25:59.617  3410  4131 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-21 14:25:59.617  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:25:59.627  3410  4131 D BatteryService: stay LED for fully charged
03-21 14:25:59.627  3410  3410 I MotionRecognitionService: Plugged
03-21 14:25:59.627  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:25:59.627  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:25:59.627  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:25:59.632  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:59.632  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:25:59.632  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:25:59.647  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:25:59.647  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:25:59.657  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:25:59.662  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:59.662  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:25:59.662  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:00.327  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), CUR = 32, LCD = 0
,03-21 14:26:03.202  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:26:04.597  3410  3582 I PowerManagerService: [PWL] Off : 275s ago
,03-21 14:26:04.697  3410  3852 I ActivityManager: Killing 10250:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-21 14:26:09.757  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:26:09.757  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:26:09.757  3410  3773 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,03-21 14:26:09.757  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:26:09.767  3410  3773 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-21 14:26:09.767  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:26:09.772  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:26:09.772  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:26:09.772  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:26:09.772  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:26:09.782  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:09.782  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:26:09.782  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:26:09.792  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:26:09.792  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:26:09.807  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:09.807  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:09.807  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:09.807  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:10.362  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), CUR = 33, LCD = 0
,03-21 14:26:15.827  3410  3864 E Watchdog: !@Sync 11 [03-21 14:26:15.832]
,03-21 14:26:19.897  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:26:19.897  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:26:19.897  3410  4030 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
03-21 14:26:19.897  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:26:19.897  3410  4030 D BatteryService: stay LED for fully charged
,03-21 14:26:19.907  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:26:19.907  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:26:19.907  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:26:19.907  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:26:19.912  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:19.912  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:26:19.912  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:26:19.927  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:26:19.927  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:26:19.937  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:19.937  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:19.942  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:19.942  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:20.392  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), CUR = 31, LCD = 0
,03-21 14:26:23.207  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:26:30.032  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:26:30.032  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:26:30.032  3410  4415 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,03-21 14:26:30.037  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:26:30.042  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:26:30.042  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:26:30.042  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:26:30.042  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
03-21 14:26:30.047  3410  4415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
,03-21 14:26:30.047  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:26:30.057  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:30.057  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:26:30.062  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:26:30.072  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:26:30.072  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:26:30.082  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:30.087  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:30.087  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:30.087  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:30.422  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:22), CUR = 30, LCD = 0,
,03-21 14:26:40.172  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:26:40.172  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:26:40.172  3410  4030 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,03-21 14:26:40.172  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:26:40.182  3410  4030 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-21 14:26:40.182  3410  4030 D BatteryService: stay LED for fully charged,
,03-21 14:26:40.187  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:26:40.187  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:26:40.187  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:26:40.187  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:26:40.197  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:26:40.197  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:26:40.197  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:26:40.207  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:26:40.207  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:26:40.217  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:40.222  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:40.222  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:40.222  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:40.457  3410  6093 D SSRM:n  : SIOP:: AP = 270, PST = 270 (W:24), CUR = 30, LCD = 0,
,03-21 14:26:43.212  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:26:45.832  3410  3864 E Watchdog: !@Sync 12 [03-21 14:26:45.833]
,03-21 14:26:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:26:50.312  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:26:50.312  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:26:50.312  3410  4415 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-21 14:26:50.317  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:26:50.317  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:26:50.322  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:26:50.322  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:26:50.322  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:26:50.322  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:26:50.332  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:50.332  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:26:50.332  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:26:50.342  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:26:50.347  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:26:50.357  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:26:50.357  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:50.357  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:26:50.357  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:26:50.487  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:24), CUR = 29, LCD = 0
,03-21 14:26:59.607  3410  3582 I PowerManagerService: [PWL] Off : 330s ago
,03-21 14:26:59.997  3410  3619 V AlarmManager: waitForAlarm result :8
03-21 14:26:59.997  3410  3619 V AlarmManager: No more alarm at this time.nowELAPSED=386806 batch.start=1041570
,03-21 14:27:00.017  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-21 14:27:00.017  3725  3725 I PERF    : received broadcast android.intent.action.TIME_TICK
03-21 14:27:00.017  3725  3725 D KeyguardUpdateMonitor: handleTimeUpdate
,03-21 14:27:00.042  3725  3725 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-21 14:27:00.042  3410  3619 V AlarmManager: waitForAlarm result :8
,03-21 14:27:00.042  3410  3619 V AlarmManager: No more alarm at this time.nowELAPSED=386854 batch.start=446806
,03-21 14:27:00.052  3725  3725 D SecKeyguardClockView: HomeTimezone(): 1
,03-21 14:27:00.062  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.062  3725  3725 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 14:27:00.072  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 14:27:00.107  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.112  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.112  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.117  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.122  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.122  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.137  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:27:00.447  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:27:00.447  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:27:00.447  3410  4030 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,03-21 14:27:00.452  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:27:00.462  3410  3410 I MotionRecognitionService: Plugged
03-21 14:27:00.462  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:27:00.462  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:27:00.462  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
03-21 14:27:00.462  3410  4030 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
03-21 14:27:00.462  3410  4030 D BatteryService: stay LED for fully charged
,03-21 14:27:00.472  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:27:00.472  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:27:00.472  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:27:00.502  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:27:00.502  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:27:00.507  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:27:00.507  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:00.507  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:00.507  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:00.512  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 269 (W:24), CUR = 29, LCD = 0
,03-21 14:27:03.217  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:27:10.537  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:24), CUR = 28, LCD = 0
,03-21 14:27:10.587  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:27:10.587  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:27:10.587  3410  4415 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
03-21 14:27:10.587  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:27:10.587  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:27:10.592  3410  3410 I MotionRecognitionService: Plugged
03-21 14:27:10.592  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:27:10.592  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:27:10.592  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:27:10.597  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:27:10.597  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:27:10.597  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:27:10.612  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:27:10.612  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:10.612  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:10.612  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:27:10.612  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:27:10.627  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:15.837  3410  3864 E Watchdog: !@Sync 13 [03-21 14:27:15.841]
,03-21 14:27:20.572  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:26), CUR = 28, LCD = 0
,03-21 14:27:20.707  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:27:20.707  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:27:20.707  3410  3966 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,03-21 14:27:20.707  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:27:20.712  3410  3966 D BatteryService: stay LED for fully charged
,03-21 14:27:20.717  3410  3410 I MotionRecognitionService: Plugged
03-21 14:27:20.717  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:27:20.717  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:27:20.717  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:27:20.727  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:27:20.727  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:27:20.727  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:27:20.747  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:27:20.747  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:27:20.757  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:27:20.757  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:20.757  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:20.757  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:23.227  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:27:30.602  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 267 (W:26), CUR = 28, LCD = 0
,03-21 14:27:30.842  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:27:30.842  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:27:30.842  3410  4783 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-21 14:27:30.847  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:27:30.857  3410  3410 I MotionRecognitionService: Plugged
03-21 14:27:30.857  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:27:30.857  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:27:30.857  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:27:30.857  3410  4783 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,03-21 14:27:30.857  3410  4783 D BatteryService: stay LED for fully charged
03-21 14:27:30.867  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:27:30.867  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:27:30.867  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:27:30.892  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:27:30.892  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:27:30.902  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:27:30.902  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:30.902  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:30.902  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:40.637  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:26), CUR = 27, LCD = 0
,03-21 14:27:40.982  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:27:40.982  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-21 14:27:40.982  3410  4030 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
03-21 14:27:40.982  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:27:40.987  3410  4030 D BatteryService: stay LED for fully charged
,03-21 14:27:40.992  3410  3410 I MotionRecognitionService: Plugged
03-21 14:27:40.992  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:27:40.992  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:27:40.992  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:27:40.997  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:27:40.997  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:27:40.997  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:27:41.017  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:27:41.017  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:27:41.032  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:27:41.032  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:41.032  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:41.032  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:43.232  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:27:45.847  3410  3864 E Watchdog: !@Sync 14 [03-21 14:27:45.852]
,03-21 14:27:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:27:50.667  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:26), CUR = 27, LCD = 0
,03-21 14:27:51.122  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:27:51.122  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:27:51.122  3410  4029 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,03-21 14:27:51.122  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:27:51.132  3410  3410 I MotionRecognitionService: Plugged
03-21 14:27:51.132  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:27:51.132  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:27:51.132  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:27:51.132  3410  4029 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-21 14:27:51.132  3410  4029 D BatteryService: stay LED for fully charged
,03-21 14:27:51.142  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:27:51.142  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:27:51.142  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:27:51.157  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,03-21 14:27:51.157  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:27:51.172  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:27:51.172  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:51.172  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:27:51.172  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:27:59.607  3410  3582 I PowerManagerService: [PWL] Off : 390s ago
,03-21 14:27:59.997  3410  3619 V AlarmManager: waitForAlarm result :8
,03-21 14:28:00.697  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:28), CUR = 27, LCD = 0
,03-21 14:28:01.262  3410  4131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:28:01.262  3410  4131 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:28:01.262  3410  4131 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,03-21 14:28:01.262  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:28:01.272  3410  4131 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-21 14:28:01.272  3410  4131 D BatteryService: stay LED for fully charged
,03-21 14:28:01.277  3410  3410 I MotionRecognitionService: Plugged,
,03-21 14:28:01.277  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:28:01.277  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:28:01.277  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:28:01.287  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:28:01.292  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:28:01.287  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:28:01.292  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:28:01.287  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:28:01.297  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:28:01.297  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:28:01.312  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:01.312  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:03.237  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:28:10.727  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:28), CUR = 27, LCD = 0
,03-21 14:28:11.397  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:28:11.397  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:28:11.397  3410  4749 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-21 14:28:11.402  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:28:11.402  3410  4749 D BatteryService: stay LED for fully charged
,03-21 14:28:11.412  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:28:11.412  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:28:11.412  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:28:11.412  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:28:11.422  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:28:11.422  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:28:11.422  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:28:11.432  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:28:11.432  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:28:11.447  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:28:11.447  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:28:11.447  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:11.447  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:15.857  3410  3864 E Watchdog: !@Sync 15 [03-21 14:28:15.860]
,03-21 14:28:20.762  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:28), CUR = 27, LCD = 0
,03-21 14:28:21.542  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:28:21.542  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:28:21.542  3410  4030 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
03-21 14:28:21.542  3410  4030 D BatteryService: stay LED for fully charged
03-21 14:28:21.542  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:28:21.547  3410  3410 I MotionRecognitionService: Plugged
03-21 14:28:21.552  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:28:21.552  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:28:21.552  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:28:21.557  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:28:21.557  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:28:21.557  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:28:21.567  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:28:21.567  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:28:21.582  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:28:21.582  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:28:21.582  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:21.582  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:23.242  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:28:30.792  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:28), CUR = 26, LCD = 0
,03-21 14:28:31.677  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:28:31.677  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:28:31.677  3410  4029 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-21 14:28:31.682  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:28:31.682  3410  4029 D BatteryService: stay LED for fully charged
,03-21 14:28:31.687  3410  3410 I MotionRecognitionService: Plugged
03-21 14:28:31.687  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:28:31.687  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:28:31.687  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:28:31.697  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:28:31.697  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:28:31.702  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:28:31.722  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:28:31.722  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:28:31.732  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:28:31.732  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:31.732  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:31.732  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:37.212  2906  2906 I bootchecker: bootchecker wake up!!
,03-21 14:28:40.827  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:30), CUR = 25, LCD = 0
,03-21 14:28:41.817  3410  4131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:28:41.817  3410  4131 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-21 14:28:41.817  3410  4131 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
03-21 14:28:41.817  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:28:41.822  3410  4131 D BatteryService: stay LED for fully charged
,03-21 14:28:41.827  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:28:41.827  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:28:41.827  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:28:41.827  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:28:41.842  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:28:41.842  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:28:41.842  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:28:41.862  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:28:41.862  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:28:41.872  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:28:41.872  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:28:41.872  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:28:41.872  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:28:43.247  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:28:45.862  3410  3864 E Watchdog: !@Sync 16 [03-21 14:28:45.867]
,03-21 14:28:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:28:50.852  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), CUR = 26, LCD = 0
,03-21 14:28:51.957  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:28:51.957  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:28:51.957  3410  4749 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-21 14:28:51.957  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:28:51.957  3410  4749 D BatteryService: stay LED for fully charged
,03-21 14:28:51.967  3410  3410 I MotionRecognitionService: Plugged,
,03-21 14:28:51.967  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:28:51.967  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:28:51.967  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:28:51.977  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:28:51.977  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:28:51.977  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:28:51.997  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:28:51.997  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:28:52.012  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:28:52.012  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:28:52.012  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:28:52.012  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:29:00.882  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), CUR = 24, LCD = 0
,03-21 14:29:02.092  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:29:02.092  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:29:02.092  3410  4781 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-21 14:29:02.097  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:29:02.097  3410  4781 D BatteryService: stay LED for fully charged,
,03-21 14:29:02.107  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:29:02.107  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:29:02.107  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:29:02.107  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
03-21 14:29:02.117  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:29:02.117  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:29:02.117  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:29:02.137  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:29:02.137  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:29:02.147  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:29:02.147  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:02.147  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:02.147  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:29:03.252  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:29:04.607  3410  3582 I PowerManagerService: [PWL] Off : 455s ago
,03-21 14:29:10.907  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:30), CUR = 25, LCD = 0
,03-21 14:29:12.232  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:29:12.232  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:29:12.232  3410  4700 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-21 14:29:12.232  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:29:12.242  3410  3410 I MotionRecognitionService: Plugged
03-21 14:29:12.242  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:29:12.242  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:29:12.242  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:29:12.247  3410  4700 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-21 14:29:12.247  3410  4700 D BatteryService: stay LED for fully charged
,03-21 14:29:12.252  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:29:12.252  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:29:12.257  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:29:12.277  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 14:29:12.277  5913  6008 D HeadsetStateMachine: Disconnected process message: 10,
,03-21 14:29:12.287  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:29:12.287  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:12.287  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:12.287  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:29:15.872  3410  3864 E Watchdog: !@Sync 17 [03-21 14:29:15.874]
,03-21 14:29:20.937  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), CUR = 24, LCD = 0
,03-21 14:29:22.367  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:29:22.372  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:29:22.372  3410  3773 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-21 14:29:22.372  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:29:22.382  3410  3410 I MotionRecognitionService: Plugged
03-21 14:29:22.382  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:29:22.382  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:29:22.382  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:29:22.382  3410  3773 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-21 14:29:22.382  3410  3773 D BatteryService: stay LED for fully charged
,03-21 14:29:22.392  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:29:22.392  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:29:22.392  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:29:22.407  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 14:29:22.407  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:29:22.422  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:29:22.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:22.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:22.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:29:23.257  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:29:30.952  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), CUR = 23, LCD = 0
,03-21 14:29:32.507  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:29:32.507  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:29:32.507  3410  4700 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-21 14:29:32.507  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:29:32.517  3410  3410 I MotionRecognitionService: Plugged
03-21 14:29:32.517  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:29:32.517  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:29:32.517  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:29:32.517  3410  4700 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms,
,03-21 14:29:32.517  3410  4700 D BatteryService: stay LED for fully charged,
03-21 14:29:32.532  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:29:32.532  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:29:32.532  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:29:32.547  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:29:32.552  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:29:32.562  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:29:32.562  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:32.562  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:32.562  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:29:40.977  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:30), CUR = 23, LCD = 0
,03-21 14:29:42.642  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:29:42.642  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:29:42.642  3410  3773 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-21 14:29:42.647  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:29:42.647  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:29:42.652  3410  3410 I MotionRecognitionService: Plugged
03-21 14:29:42.652  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:29:42.652  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:29:42.652  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:29:42.667  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:29:42.667  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:29:42.667  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:29:42.677  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:29:42.677  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:29:42.692  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:29:42.692  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:42.692  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:42.692  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:29:43.262  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:29:45.877  3410  3864 E Watchdog: !@Sync 18 [03-21 14:29:45.882]
,03-21 14:29:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:29:51.007  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), CUR = 23, LCD = 0
,03-21 14:29:52.787  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:29:52.787  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:29:52.787  3410  3434 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-21 14:29:52.787  3410  3434 D BatteryService: stay LED for fully charged
03-21 14:29:52.787  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:29:52.797  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:29:52.797  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:29:52.797  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:29:52.797  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:29:52.802  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:29:52.802  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:29:52.802  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:29:52.817  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:29:52.817  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:29:52.827  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:29:52.827  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:29:52.827  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:29:52.832  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:01.042  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), CUR = 22, LCD = 0
,03-21 14:30:02.922  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:30:02.922  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:30:02.922  3410  3773 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,03-21 14:30:02.927  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:30:02.927  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:30:02.937  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:30:02.937  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:30:02.937  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:30:02.937  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:30:02.947  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:30:02.947  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:02.947  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:30:02.967  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:30:02.967  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:30:02.982  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:30:02.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:02.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:02.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:03.267  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:30:11.072  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:30), CUR = 23, LCD = 0
,03-21 14:30:13.062  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:30:13.062  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:30:13.062  3410  3434 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-21 14:30:13.067  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:30:13.072  3410  3410 I MotionRecognitionService: Plugged
03-21 14:30:13.072  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:30:13.072  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:30:13.072  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:30:13.077  3410  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-21 14:30:13.077  3410  3434 D BatteryService: stay LED for fully charged
,03-21 14:30:13.087  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:30:13.087  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:13.087  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:30:13.102  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:30:13.102  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:30:13.112  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:13.112  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:13.112  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:13.117  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:14.612  3410  3582 I PowerManagerService: [PWL] Off : 525s ago
,03-21 14:30:15.887  3410  3864 E Watchdog: !@Sync 19 [03-21 14:30:15.889]
,03-21 14:30:21.097  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0
,03-21 14:30:23.197  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:30:23.197  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:30:23.202  3410  3435 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-21 14:30:23.202  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:30:23.212  3410  3410 I MotionRecognitionService: Plugged
03-21 14:30:23.212  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:30:23.212  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:30:23.212  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
03-21 14:30:23.212  3410  3435 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
03-21 14:30:23.212  3410  3435 D BatteryService: stay LED for fully charged,
,03-21 14:30:23.227  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:30:23.227  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:30:23.227  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:30:23.247  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:30:23.247  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:30:23.257  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:23.257  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:23.257  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:23.257  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:23.272  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:30:31.127  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0
,03-21 14:30:33.337  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:30:33.337  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-21 14:30:33.342  3410  3734 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
03-21 14:30:33.342  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:30:33.342  3410  3734 D BatteryService: stay LED for fully charged
,03-21 14:30:33.352  3410  3410 I MotionRecognitionService: Plugged
03-21 14:30:33.352  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:30:33.352  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:30:33.352  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:30:33.357  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:30:33.357  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:33.357  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:30:33.377  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:30:33.377  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:30:33.387  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:33.387  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:33.387  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:33.387  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:41.152  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0
,03-21 14:30:43.277  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:30:43.442  3410  3608 D TimaService: TIMA: TimaService scheduler is intialized. 
03-21 14:30:43.442  3410  3608 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-21 14:30:43.442  3410  3607 D TimaService: TimaServiceHandler.handleMessage what =1
,03-21 14:30:43.497  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:30:43.497  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:30:43.497  3410  4046 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-21 14:30:43.497  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:30:43.497  3410  4046 D BatteryService: stay LED for fully charged
,03-21 14:30:43.507  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:30:43.507  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:30:43.507  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:30:43.507  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:30:43.517  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:30:43.517  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:43.517  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:30:43.532  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:30:43.537  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:30:43.547  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:30:43.547  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:43.547  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:43.547  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:45.892  3410  3864 E Watchdog: !@Sync 20 [03-21 14:30:45.896],
,03-21 14:30:45.982  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-21 14:30:45.982  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-21 14:30:45.997  3410  3608 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
03-21 14:30:45.997  3410  3608 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 14:30:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:30:49.377  3410  3580 I ActivityManager: setMaxStartingBackgroundTimer onfinish
03-21 14:30:49.377  3410  3580 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,03-21 14:30:51.182  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 20, LCD = 0
,03-21 14:30:53.632  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:30:53.632  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:30:53.632  3410  3852 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-21 14:30:53.637  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:30:53.642  3410  3410 I MotionRecognitionService: Plugged
03-21 14:30:53.642  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:30:53.642  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:30:53.642  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
03-21 14:30:53.647  3410  3852 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
,03-21 14:30:53.647  3410  3852 D BatteryService: stay LED for fully charged,
,03-21 14:30:53.652  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:30:53.652  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:30:53.657  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:30:53.672  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:30:53.672  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:30:53.687  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:30:53.687  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:30:53.687  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:30:53.687  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:31:01.212  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0
,03-21 14:31:03.282  3410  6124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 14:31:03.772  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:31:03.772  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:31:03.772  3410  4415 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-21 14:31:03.772  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:31:03.782  3410  3410 I MotionRecognitionService: Plugged
03-21 14:31:03.782  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:31:03.782  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:31:03.782  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
03-21 14:31:03.787  3410  4415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
03-21 14:31:03.787  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:31:03.792  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:31:03.792  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:31:03.792  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:31:03.817  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:31:03.817  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:31:03.827  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:31:03.827  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:03.827  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:03.827  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:31:11.237  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 22, LCD = 0
,03-21 14:31:13.907  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:31:13.912  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:31:13.912  3410  3966 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-21 14:31:13.912  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:31:13.917  3410  3966 D BatteryService: stay LED for fully charged
,03-21 14:31:13.922  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:31:13.922  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:31:13.922  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:31:13.922  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:31:13.932  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:31:13.932  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:31:13.932  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:31:13.947  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:31:13.947  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:31:13.957  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:31:13.957  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:31:13.962  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:13.962  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:31:15.907  3410  3864 E Watchdog: !@Sync 21 [03-21 14:31:15.909]
,03-21 14:31:21.267  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 22, LCD = 0
,03-21 14:31:24.047  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:31:24.047  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:31:24.047  3410  4783 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,03-21 14:31:24.052  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:31:24.052  3410  4783 D BatteryService: stay LED for fully charged,
,03-21 14:31:24.062  3410  3410 I MotionRecognitionService: Plugged
03-21 14:31:24.062  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:31:24.062  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:31:24.062  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:31:24.072  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:31:24.072  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:31:24.072  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:31:24.097  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:31:24.097  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:31:24.102  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:31:24.102  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:24.102  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:24.102  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:31:29.617  3410  3582 I PowerManagerService: [PWL] Off : 600s ago
,03-21 14:31:31.292  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0,
,03-21 14:31:34.187  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:31:34.187  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:31:34.187  3410  3734 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,03-21 14:31:34.192  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:31:34.197  3410  3734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms,
03-21 14:31:34.197  3410  3734 D BatteryService: stay LED for fully charged
03-21 14:31:34.197  3410  3410 I MotionRecognitionService: Plugged
03-21 14:31:34.197  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:31:34.197  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:31:34.197  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:31:34.212  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:31:34.212  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:31:34.212  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:31:34.232  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:31:34.232  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:31:34.242  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:31:34.242  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:34.242  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:34.242  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:31:41.327  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 19, LCD = 0
,03-21 14:31:44.327  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:31:44.327  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:31:44.327  3410  4046 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-21 14:31:44.327  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:31:44.332  3410  4046 D BatteryService: stay LED for fully charged
,03-21 14:31:44.342  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:31:44.342  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:31:44.342  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:31:44.342  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:31:44.352  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:31:44.352  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:31:44.352  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:31:44.372  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:31:44.372  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:31:44.382  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:31:44.382  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:44.382  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:44.382  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:31:45.912  3410  3864 E Watchdog: !@Sync 22 [03-21 14:31:45.916]
,03-21 14:31:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:31:51.362  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 17, LCD = 0
,03-21 14:31:54.467  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:31:54.472  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:31:54.472  3410  3852 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-21 14:31:54.472  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:31:54.472  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:31:54.482  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:31:54.482  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:31:54.482  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:31:54.482  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:31:54.492  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:31:54.492  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:31:54.492  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:31:54.507  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:31:54.512  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:31:54.522  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:31:54.522  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:54.522  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:31:54.522  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:32:01.392  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 18, LCD = 0
,03-21 14:32:04.607  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:32:04.607  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-21 14:32:04.607  3410  4415 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
03-21 14:32:04.612  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:32:04.612  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:32:04.622  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:32:04.622  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:32:04.622  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:32:04.622  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:32:04.632  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:32:04.632  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:04.632  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:32:04.647  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:32:04.647  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:32:04.662  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:32:04.662  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:04.662  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:04.662  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:32:11.417  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 19, LCD = 0
,03-21 14:32:14.752  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:32:14.752  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:32:14.752  3410  3852 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-21 14:32:14.752  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:32:14.757  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:32:14.762  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:32:14.762  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:32:14.762  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:32:14.762  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:32:14.772  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:14.772  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:14.772  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:32:14.782  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:32:14.782  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:32:14.797  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:32:14.797  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:14.797  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:14.797  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:32:15.922  3410  3864 E Watchdog: !@Sync 23 [03-21 14:32:15.924]
,03-21 14:32:21.462  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0
,03-21 14:32:21.632  3410  3423 I art     : Background partial concurrent mark sweep GC freed 45572(5MB) AllocSpace objects, 196(5MB) LOS objects, 33% free, 27MB/41MB, paused 2.803ms total 183.479ms
,03-21 14:32:24.892  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:32:24.892  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:32:24.892  3410  4415 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-21 14:32:24.897  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:32:24.902  3410  3410 I MotionRecognitionService: Plugged
03-21 14:32:24.907  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:32:24.907  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:32:24.907  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:32:24.907  3410  4415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-21 14:32:24.907  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:32:24.917  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:32:24.917  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:24.917  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:32:24.932  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:32:24.932  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:32:24.947  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:24.947  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:24.947  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:24.947  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:32:31.487  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 18, LCD = 0
,03-21 14:32:35.027  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:32:35.032  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:32:35.032  3410  3966 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-21 14:32:35.032  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:32:35.032  3410  3966 D BatteryService: stay LED for fully charged
,03-21 14:32:35.042  3410  3410 I MotionRecognitionService: Plugged
03-21 14:32:35.042  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:32:35.042  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:32:35.042  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:32:35.052  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:32:35.052  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:35.052  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:32:35.072  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:32:35.072  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:32:35.082  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:35.082  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:35.082  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:35.082  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:32:41.517  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 18, LCD = 0
,03-21 14:32:45.157  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:32:45.157  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:32:45.157  3410  4783 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
03-21 14:32:45.157  3410  4783 D BatteryService: stay LED for fully charged
03-21 14:32:45.157  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:32:45.162  3410  3410 I MotionRecognitionService: Plugged
03-21 14:32:45.162  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:32:45.162  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:32:45.162  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:32:45.162  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:32:45.162  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:45.162  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:32:45.167  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:32:45.172  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:32:45.172  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:32:45.187  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:45.187  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:45.187  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:32:45.927  3410  3864 E Watchdog: !@Sync 24 [03-21 14:32:45.932]
,03-21 14:32:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:32:49.622  3410  3582 I PowerManagerService: [PWL] Off : 680s ago
,03-21 14:32:51.542  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 19, LCD = 0
,03-21 14:32:55.297  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:32:55.302  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:32:55.302  3410  4030 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-21 14:32:55.302  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:32:55.302  3410  4030 D BatteryService: stay LED for fully charged,
,03-21 14:32:55.312  3410  3410 I MotionRecognitionService: Plugged
03-21 14:32:55.312  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:32:55.312  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:32:55.312  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:32:55.327  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:55.327  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:32:55.327  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:32:55.352  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:32:55.352  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:32:55.357  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:32:55.357  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:55.357  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:32:55.357  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:33:01.572  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 19, LCD = 0
,03-21 14:33:05.437  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:33:05.437  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:33:05.437  3410  4029 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-21 14:33:05.442  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:33:05.447  3410  4029 D BatteryService: stay LED for fully charged
,03-21 14:33:05.452  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:33:05.452  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:33:05.452  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:33:05.452  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:33:05.462  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:33:05.462  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:05.467  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:33:05.482  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:33:05.482  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:33:05.492  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:33:05.492  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:05.492  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:05.497  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:33:11.602  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 20, LCD = 0
,03-21 14:33:15.577  3410  4131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:33:15.577  3410  4131 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:33:15.577  3410  4131 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-21 14:33:15.582  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:33:15.587  3410  4131 D BatteryService: stay LED for fully charged
,03-21 14:33:15.592  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:33:15.592  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:33:15.592  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:33:15.592  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:33:15.602  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:33:15.602  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:33:15.612  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:33:15.612  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 14:33:15.612  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:33:15.612  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:15.617  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:33:15.617  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:33:15.632  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:33:15.937  3410  3864 E Watchdog: !@Sync 25 [03-21 14:33:15.940]
,03-21 14:33:21.632  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 18, LCD = 0
,03-21 14:33:25.717  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:33:25.717  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:33:25.717  3410  4749 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,03-21 14:33:25.717  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:33:25.722  3410  4749 D BatteryService: stay LED for fully charged
,03-21 14:33:25.727  3410  3410 I MotionRecognitionService: Plugged
03-21 14:33:25.732  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:33:25.732  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:33:25.732  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:33:25.737  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:25.737  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:25.737  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:33:25.752  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:33:25.752  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:33:25.767  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:33:25.767  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:25.767  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:25.767  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:33:31.662  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 18, LCD = 0
,03-21 14:33:35.857  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:33:35.857  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:33:35.857  3410  4781 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,03-21 14:33:35.857  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:33:35.862  3410  4781 D BatteryService: stay LED for fully charged
,03-21 14:33:35.867  3410  3410 I MotionRecognitionService: Plugged
03-21 14:33:35.867  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:33:35.867  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:33:35.867  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:33:35.877  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:33:35.877  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:35.877  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:33:35.897  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:33:35.897  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:33:35.907  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:35.907  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:35.907  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:35.907  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:33:41.692  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 18, LCD = 0
,03-21 14:33:45.942  3410  3864 E Watchdog: !@Sync 26 [03-21 14:33:45.947]
,03-21 14:33:45.997  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:33:45.997  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:33:45.997  3410  4700 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-21 14:33:45.997  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:33:46.002  3410  4700 D BatteryService: stay LED for fully charged
,03-21 14:33:46.007  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:33:46.007  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:33:46.007  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:33:46.007  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:33:46.017  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:33:46.017  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:46.017  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:33:46.037  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:33:46.037  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:33:46.047  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:46.047  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:46.047  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:46.047  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:33:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:33:51.717  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 17, LCD = 0
,03-21 14:33:56.137  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:33:56.137  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:33:56.137  3410  3773 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-21 14:33:56.142  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:33:56.147  3410  3410 I MotionRecognitionService: Plugged
03-21 14:33:56.147  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:33:56.152  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:33:56.152  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
03-21 14:33:56.152  3410  3773 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
,03-21 14:33:56.152  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:33:56.162  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:33:56.162  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:33:56.162  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:33:56.182  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:33:56.182  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:33:56.192  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:33:56.192  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:56.192  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:33:56.192  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:34:01.742  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 18, LCD = 0
,03-21 14:34:06.277  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:34:06.277  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:34:06.277  3410  3434 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-21 14:34:06.277  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:34:06.282  3410  3434 D BatteryService: stay LED for fully charged
,03-21 14:34:06.287  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:34:06.287  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:34:06.287  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:34:06.287  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:34:06.297  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:34:06.297  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:34:06.297  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:34:06.317  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:34:06.317  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:34:06.332  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:06.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:06.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:06.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:34:11.772  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 16, LCD = 0
,03-21 14:34:14.627  3410  3582 I PowerManagerService: [PWL] Off : 765s ago
,03-21 14:34:15.947  3410  3864 E Watchdog: !@Sync 27 [03-21 14:34:15.949]
,03-21 14:34:16.412  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:34:16.417  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:34:16.417  3410  3435 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
03-21 14:34:16.417  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:34:16.417  3410  3435 D BatteryService: stay LED for fully charged
,03-21 14:34:16.427  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:34:16.427  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:34:16.427  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:34:16.427  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:34:16.437  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:34:16.437  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:34:16.437  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:34:16.457  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:34:16.457  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:34:16.467  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:16.467  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:16.467  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:16.467  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:34:21.807  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:34:26.552  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:34:26.552  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:34:26.552  3410  3734 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,03-21 14:34:26.552  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:34:26.562  3410  3410 I MotionRecognitionService: Plugged
03-21 14:34:26.562  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:34:26.562  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:34:26.562  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:34:26.562  3410  3734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-21 14:34:26.562  3410  3734 D BatteryService: stay LED for fully charged
,03-21 14:34:26.572  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:34:26.572  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:34:26.572  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:34:26.587  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:34:26.592  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:34:26.602  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:26.602  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:26.602  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:26.602  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:34:31.842  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 16, LCD = 0
,03-21 14:34:36.687  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:34:36.687  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:34:36.687  3410  4046 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,03-21 14:34:36.692  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:34:36.692  3410  4046 D BatteryService: stay LED for fully charged
,03-21 14:34:36.697  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:34:36.697  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:34:36.702  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:34:36.702  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:34:36.707  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:36.707  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:34:36.712  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:34:36.727  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:34:36.727  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:34:36.737  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:36.737  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:36.742  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:34:36.742  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:34:41.872  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:34:45.952  3410  3864 E Watchdog: !@Sync 28 [03-21 14:34:45.956]
,03-21 14:34:46.827  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:34:46.827  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:34:46.827  3410  3852 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-21 14:34:46.827  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:34:46.837  3410  3852 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-21 14:34:46.837  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:34:46.842  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:34:46.842  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:34:46.842  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:34:46.842  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:34:46.852  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:34:46.852  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:34:46.852  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:34:46.862  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:34:46.862  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:34:46.872  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:46.877  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:46.877  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:46.877  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:34:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:34:51.907  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:34:56.972  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:34:56.972  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:34:56.972  3410  3435 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-21 14:34:56.972  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:34:56.972  3410  3435 D BatteryService: stay LED for fully charged
,03-21 14:34:56.982  3410  3410 I MotionRecognitionService: Plugged
03-21 14:34:56.982  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:34:56.982  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:34:56.982  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:34:56.987  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:56.987  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:34:56.987  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:34:57.002  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:34:57.002  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:34:57.012  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:34:57.012  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:57.012  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:34:57.012  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:01.937  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 17, LCD = 0
,03-21 14:35:07.107  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:35:07.107  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:35:07.107  3410  3734 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-21 14:35:07.107  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:35:07.107  3410  3734 D BatteryService: stay LED for fully charged
,03-21 14:35:07.117  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:35:07.117  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:35:07.117  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:35:07.117  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:35:07.127  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:35:07.127  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:35:07.132  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:35:07.142  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:35:07.147  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:35:07.157  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:35:07.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:07.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:07.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:11.972  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 16, LCD = 0
,03-21 14:35:15.962  3410  3864 E Watchdog: !@Sync 29 [03-21 14:35:15.967]
,03-21 14:35:17.242  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:35:17.247  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:35:17.247  3410  4046 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,03-21 14:35:17.247  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:35:17.247  3410  4046 D BatteryService: stay LED for fully charged
,03-21 14:35:17.257  3410  3410 I MotionRecognitionService: Plugged
03-21 14:35:17.257  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:35:17.257  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:35:17.257  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:35:17.262  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:35:17.262  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:35:17.262  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:35:17.282  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:35:17.282  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:35:17.292  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:35:17.292  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:17.292  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:17.297  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:21.997  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 17, LCD = 0
,03-21 14:35:27.382  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:35:27.387  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:35:27.387  3410  3852 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-21 14:35:27.387  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:35:27.397  3410  3410 I MotionRecognitionService: Plugged
03-21 14:35:27.397  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:35:27.397  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:35:27.397  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:35:27.397  3410  3852 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,03-21 14:35:27.397  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:35:27.412  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:35:27.412  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:35:27.412  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:35:27.427  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:35:27.427  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:35:27.442  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:35:27.442  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:27.442  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:27.442  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:32.027  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:35:37.522  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:35:37.527  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:35:37.527  3410  4415 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-21 14:35:37.527  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:35:37.537  3410  3410 I MotionRecognitionService: Plugged
03-21 14:35:37.537  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:35:37.537  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:35:37.537  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:35:37.537  3410  4415 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-21 14:35:37.537  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:35:37.547  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:35:37.547  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:35:37.547  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:35:37.562  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:35:37.567  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:35:37.577  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:35:37.577  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:37.577  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:37.577  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:42.052  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:35:43.442  3410  3608 D TimaService: TIMA: TimaService scheduler is intialized. 
03-21 14:35:43.442  3410  3608 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-21 14:35:43.447  3410  3607 D TimaService: TimaServiceHandler.handleMessage what =1
,03-21 14:35:44.627  3410  3582 I PowerManagerService: [PWL] Off : 855s ago
03-21 14:35:44.627  3410  3582 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-21 14:35:44.627  3410  3582 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-21 14:35:44.627  3410  3582 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=3410, ws=null) (elapsedTime=1184)
,03-21 14:35:45.972  3410  3864 E Watchdog: !@Sync 30 [03-21 14:35:45.974],
,03-21 14:35:47.647  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:35:47.647  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:35:47.647  3410  3852 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
03-21 14:35:47.647  3410  3852 D BatteryService: stay LED for fully charged
03-21 14:35:47.647  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:35:47.652  3410  3410 I MotionRecognitionService: Plugged
03-21 14:35:47.652  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:35:47.652  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:35:47.652  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:35:47.652  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:35:47.652  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:35:47.652  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:35:47.657  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:35:47.657  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:35:47.672  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:35:47.672  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:47.672  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:47.677  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:35:48.387  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-21 14:35:48.387  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-21 14:35:48.612  3410  3608 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 14:35:48.612  3410  3608 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 14:35:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:35:52.087  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:35:57.787  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:35:57.787  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:35:57.787  3410  4415 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-21 14:35:57.792  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:35:57.792  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:35:57.802  3410  3410 I MotionRecognitionService: Plugged
03-21 14:35:57.802  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:35:57.802  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:35:57.802  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:35:57.812  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:35:57.812  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:35:57.812  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:35:57.832  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:35:57.832  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:35:57.842  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:35:57.842  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:57.842  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:35:57.842  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:36:02.117  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:36:07.927  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:36:07.927  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:36:07.927  3410  3966 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,03-21 14:36:07.932  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:36:07.937  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:36:07.937  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:36:07.937  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:36:07.937  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:36:07.937  3410  3966 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-21 14:36:07.937  3410  3966 D BatteryService: stay LED for fully charged
,03-21 14:36:07.952  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:36:07.952  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:36:07.952  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:36:07.972  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:36:07.972  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:36:07.982  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:07.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:07.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:07.982  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:36:12.147  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:36:15.987  3410  3864 E Watchdog: !@Sync 31 [03-21 14:36:15.990]
,03-21 14:36:18.062  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:36:18.067  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:36:18.067  3410  4783 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-21 14:36:18.067  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:36:18.067  3410  4783 D BatteryService: stay LED for fully charged
,03-21 14:36:18.077  3410  3410 I MotionRecognitionService: Plugged
03-21 14:36:18.077  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:36:18.077  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:36:18.077  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:36:18.082  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:36:18.082  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:18.082  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:36:18.102  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:36:18.102  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:36:18.112  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:18.112  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:18.112  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:18.112  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:36:22.177  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:36:28.202  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:36:28.202  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:36:28.202  3410  4030 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,03-21 14:36:28.207  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:36:28.212  3410  3410 I MotionRecognitionService: Plugged
03-21 14:36:28.212  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:36:28.212  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:36:28.212  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:36:28.217  3410  4030 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
03-21 14:36:28.217  3410  4030 D BatteryService: stay LED for fully charged,
,03-21 14:36:28.227  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:28.227  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:36:28.227  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:36:28.247  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:36:28.247  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:36:28.257  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:28.257  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:28.257  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:28.257  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:36:32.202  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:36:38.337  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:36:38.337  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:36:38.337  3410  4029 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-21 14:36:38.342  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:36:38.342  3410  4029 D BatteryService: stay LED for fully charged
,03-21 14:36:38.352  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:36:38.352  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:36:38.352  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:36:38.352  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:36:38.362  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:36:38.362  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:38.362  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:36:38.387  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:36:38.387  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:36:38.392  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:36:38.392  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:38.397  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:36:38.397  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:36:42.232  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:36:45.997  3410  3864 E Watchdog: !@Sync 32 [03-21 14:36:45.997]
,03-21 14:36:48.482  3410  4131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:36:48.482  3410  4131 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:36:48.482  3410  4131 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
03-21 14:36:48.482  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:36:48.482  3410  4131 D BatteryService: stay LED for fully charged
,03-21 14:36:48.492  3410  3410 I MotionRecognitionService: Plugged
03-21 14:36:48.492  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:36:48.492  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:36:48.492  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:36:48.497  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:36:48.497  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:48.497  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:36:48.517  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:36:48.517  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:36:48.532  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:36:48.532  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:48.532  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:48.532  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:36:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:36:52.257  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:36:58.617  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:36:58.617  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:36:58.617  3410  4749 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,03-21 14:36:58.622  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:36:58.622  3410  4749 D BatteryService: stay LED for fully charged
,03-21 14:36:58.632  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:36:58.632  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:36:58.632  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:36:58.632  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:36:58.642  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:36:58.642  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:58.642  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:36:58.662  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:36:58.662  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:36:58.672  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:36:58.672  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:58.672  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:36:58.672  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:02.287  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:37:08.757  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:37:08.757  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:37:08.757  3410  4781 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
03-21 14:37:08.757  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:37:08.757  3410  4781 D BatteryService: stay LED for fully charged
,03-21 14:37:08.767  3410  3410 I MotionRecognitionService: Plugged
03-21 14:37:08.767  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:37:08.767  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:37:08.767  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:37:08.772  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:08.772  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:08.772  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:37:08.787  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:37:08.787  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:37:08.797  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:37:08.797  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:08.797  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:08.797  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:12.317  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:37:16.002  3410  3864 E Watchdog: !@Sync 33 [03-21 14:37:16.006]
,03-21 14:37:18.892  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:37:18.892  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:37:18.892  3410  4700 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-21 14:37:18.897  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:37:18.897  3410  4700 D BatteryService: stay LED for fully charged
,03-21 14:37:18.902  3410  3410 I MotionRecognitionService: Plugged
03-21 14:37:18.907  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:37:18.907  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:37:18.907  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:37:18.917  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:37:18.917  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:18.917  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:37:18.937  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:37:18.937  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:37:18.947  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:37:18.947  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:18.947  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:18.947  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:19.632  3410  3582 I PowerManagerService: [PWL] Off : 950s ago
,03-21 14:37:22.347  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-21 14:37:29.032  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:37:29.032  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:37:29.032  3410  3773 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-21 14:37:29.037  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:37:29.037  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:37:29.047  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:37:29.047  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:37:29.047  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:37:29.047  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:37:29.057  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:37:29.057  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:29.057  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:37:29.077  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:37:29.077  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:37:29.087  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:29.087  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:29.087  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:29.087  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:32.372  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:37:39.172  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:37:39.172  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:37:39.172  3410  3434 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,03-21 14:37:39.172  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:37:39.172  3410  3434 D BatteryService: stay LED for fully charged
,03-21 14:37:39.182  3410  3410 I MotionRecognitionService: Plugged
03-21 14:37:39.182  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:37:39.182  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:37:39.182  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:37:39.192  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:37:39.192  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:39.192  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:37:39.212  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:37:39.212  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:37:39.222  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:39.222  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:39.222  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:39.222  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:42.402  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:37:46.012  3410  3864 E Watchdog: !@Sync 34 [03-21 14:37:46.013]
,03-21 14:37:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:37:49.307  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:37:49.307  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:37:49.307  3410  4046 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,03-21 14:37:49.312  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:37:49.317  3410  3410 I MotionRecognitionService: Plugged
03-21 14:37:49.317  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:37:49.322  3410  4046 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-21 14:37:49.322  3410  4046 D BatteryService: stay LED for fully charged
03-21 14:37:49.322  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:37:49.322  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:37:49.332  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:37:49.332  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:49.332  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:37:49.352  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:37:49.352  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:37:49.362  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:49.362  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:49.362  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:49.362  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:52.432  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-21 14:37:54.762  3410  3619 V AlarmManager: waitForAlarm result :4
,03-21 14:37:54.802  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-21 14:37:54.802  3725  3725 I PERF    : received broadcast android.intent.action.TIME_TICK
03-21 14:37:54.802  3725  3725 D KeyguardUpdateMonitor: handleTimeUpdate
,03-21 14:37:54.817  3725  3725 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-21 14:37:54.817  3410  3410 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,03-21 14:37:54.822  3725  3725 D SecKeyguardClockView: HomeTimezone(): 1
,03-21 14:37:54.822  3410  3410 I Sensors : Light old sensor_state 0, new sensor_state : 512 en : 1
,03-21 14:37:54.832  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:54.832  3725  3725 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 14:37:54.837  3410  3410 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,03-21 14:37:54.837  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 14:37:54.852  3410  3410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f4165a7 u0 null} DELIVERED for app ProcessRecord{caadd61 4596:com.google.android.gms/u0a14}
,03-21 14:37:54.857  3410  3966 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 14:37:54.882  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:54.887  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:54.897  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:54.897  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:54.907  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:54.907  3725  3725 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:54.917  4596 11954 I EventLogService: Aggregate from 1458565674708 (log), 1458565674708 (data)
,03-21 14:37:54.937  3725  3725 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 14:37:55.027  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:37:55.027  3410  3574 I Sensors : #>LightSensor r=0 g=1 b=2 c=3 atime=238 again=64 lux=0.000000
03-21 14:37:55.027  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:37:55.027  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:37:55.027  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:37:55.027  3410  3599 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,03-21 14:37:55.027  3410  3599 I Sensors : Light old sensor_state 512, new sensor_state : 0 en : 0
,03-21 14:37:55.027  3410  3599 D SensorManager: unregisterListener ::   
03-21 14:37:55.027  3410  3599 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,03-21 14:37:55.042 11959 11959 E Zygote  : MountEmulatedStorage()
03-21 14:37:55.042 11959 11959 E Zygote  : v2
03-21 14:37:55.042 11959 11959 I libpersona: KNOX_SDCARD checking this for 1000
03-21 14:37:55.042 11959 11959 I libpersona: KNOX_SDCARD not a persona
,03-21 14:37:55.047 11959 11959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 14:37:55.047 11959 11959 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:37:55.047 11959 11959 E Zygote  : accessInfo : 0
03-21 14:37:55.047  3410  3575 I ActivityManager: Start proc 11959:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,03-21 14:37:55.047 11959 11959 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 14:37:55.072 11959 11959 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 14:37:55.077 11959 11959 D ActivityThread: Added TimaKeyStore provider
,03-21 14:37:55.082  3410  4749 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2fddc7c0 u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{32cabcf9 11959:com.samsung.android.sm/1000}
,03-21 14:37:55.092 11959 11959 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 14:37:55.132  3410  4131 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{77c843e u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{32cabcf9 11959:com.samsung.android.sm/1000}
,03-21 14:37:55.137  3410  4131 I ActivityManager: Killing 10223:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-21 14:37:59.447  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:37:59.447  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-21 14:37:59.452  3410  4781 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
03-21 14:37:59.452  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:37:59.452  3410  4781 D BatteryService: stay LED for fully charged
,03-21 14:37:59.462  3410  3410 I MotionRecognitionService: Plugged
03-21 14:37:59.462  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:37:59.462  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:37:59.462  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:37:59.472  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:37:59.472  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:37:59.472  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:37:59.487  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:37:59.492  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:37:59.502  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:37:59.502  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:59.502  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:37:59.502  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:37:59.997  3410  3619 V AlarmManager: waitForAlarm result :8,
,03-21 14:38:02.457  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:38:09.587  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:38:09.587  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:38:09.587  3410  3852 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-21 14:38:09.587  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:38:09.592  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:38:09.597  3410  3410 I MotionRecognitionService: Plugged
03-21 14:38:09.597  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:38:09.597  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:38:09.597  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:38:09.607  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:38:09.607  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:38:09.607  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:38:09.622  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:38:09.627  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:38:09.637  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:38:09.637  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:09.637  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:09.637  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:38:12.487  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-21 14:38:16.017  3410  3864 E Watchdog: !@Sync 35 [03-21 14:38:16.020]
,03-21 14:38:19.722  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:38:19.722  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:38:19.722  3410  3435 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
03-21 14:38:19.727  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:38:19.727  3410  3435 D BatteryService: stay LED for fully charged
,03-21 14:38:19.737  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:38:19.737  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:38:19.737  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:38:19.737  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:38:19.747  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:38:19.747  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:38:19.747  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:38:19.762  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:38:19.767  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:38:19.767  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:38:19.777  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:19.777  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:19.777  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:38:22.507  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-21 14:38:29.862  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:38:29.862  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:38:29.862  3410  3734 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-21 14:38:29.862  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:38:29.872  3410  3734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-21 14:38:29.872  3410  3734 D BatteryService: stay LED for fully charged,
,03-21 14:38:29.872  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:38:29.872  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:38:29.872  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:38:29.872  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:38:29.887  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:38:29.887  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:38:29.887  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:38:29.897  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:38:29.897  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:38:29.912  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:38:29.912  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:29.912  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:29.912  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:38:32.532  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 15, LCD = 0
,03-21 14:38:39.992  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:38:39.997  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:38:39.997  3410  4783 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-21 14:38:39.997  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:38:39.997  3410  4783 D BatteryService: stay LED for fully charged
,03-21 14:38:40.007  3410  3410 I MotionRecognitionService: Plugged
03-21 14:38:40.007  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:38:40.007  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:38:40.007  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:38:40.017  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:38:40.017  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:38:40.017  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:38:40.027  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:38:40.027  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:38:40.042  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:38:40.042  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:40.042  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:40.042  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:38:42.562  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 14, LCD = 0
,03-21 14:38:46.027  3410  3864 E Watchdog: !@Sync 36 [03-21 14:38:46.027]
,03-21 14:38:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:38:50.132  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:38:50.132  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:38:50.132  3410  3734 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-21 14:38:50.137  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:38:50.142  3410  3410 I MotionRecognitionService: Plugged
03-21 14:38:50.142  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:38:50.142  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:38:50.142  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:38:50.147  3410  3734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-21 14:38:50.147  3410  3734 D BatteryService: stay LED for fully charged
,03-21 14:38:50.157  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:38:50.157  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:38:50.157  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:38:50.172  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:38:50.172  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:38:50.182  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:38:50.182  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:38:50.187  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:38:50.187  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:38:52.587  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-21 14:38:59.637  3410  3582 I PowerManagerService: [PWL] Off : 1050s ago
,03-21 14:39:00.267  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:39:00.272  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:39:00.272  3410  4783 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
03-21 14:39:00.272  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:39:00.277  3410  4783 D BatteryService: stay LED for fully charged
,03-21 14:39:00.282  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:39:00.282  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:39:00.282  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:39:00.282  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:39:00.292  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:00.292  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:39:00.292  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:39:00.317  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:39:00.317  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:39:00.322  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:39:00.327  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:00.327  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:00.327  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:02.617  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-21 14:39:10.412  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:39:10.412  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:39:10.412  3410  3434 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-21 14:39:10.412  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:39:10.417  3410  3434 D BatteryService: stay LED for fully charged
,03-21 14:39:10.422  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:39:10.422  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:39:10.422  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:39:10.422  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:39:10.432  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:39:10.432  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:10.432  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:39:10.452  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:39:10.452  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:39:10.462  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:10.462  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:10.462  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:10.462  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:12.647  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:39:16.032  3410  3864 E Watchdog: !@Sync 37 [03-21 14:39:16.035]
,03-21 14:39:20.547  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:39:20.547  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:39:20.547  3410  4781 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,03-21 14:39:20.547  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:39:20.547  3410  4781 D BatteryService: stay LED for fully charged
,03-21 14:39:20.557  3410  3410 I MotionRecognitionService: Plugged
03-21 14:39:20.557  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:39:20.557  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:39:20.557  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:39:20.567  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:39:20.567  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:20.567  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:39:20.587  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:39:20.592  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:39:20.597  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:20.597  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:20.597  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:20.597  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:22.677  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-21 14:39:30.687  3410  4131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:39:30.687  3410  4131 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:39:30.687  3410  4131 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-21 14:39:30.692  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:39:30.692  3410  4131 D BatteryService: stay LED for fully charged
,03-21 14:39:30.697  3410  3410 I MotionRecognitionService: Plugged
03-21 14:39:30.697  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:39:30.697  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:39:30.697  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:39:30.707  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:39:30.707  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:39:30.707  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:39:30.727  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:39:30.727  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:39:30.737  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:30.737  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:30.737  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:30.742  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:32.702  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-21 14:39:40.822  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:39:40.822  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:39:40.822  3410  4700 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-21 14:39:40.827  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:39:40.827  3410  4700 D BatteryService: stay LED for fully charged,
,03-21 14:39:40.837  3410  3410 I MotionRecognitionService: Plugged
03-21 14:39:40.837  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:39:40.837  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:39:40.837  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:39:40.847  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:39:40.847  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:40.847  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:39:40.867  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:39:40.867  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:39:40.882  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:39:40.882  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:40.882  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:40.882  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:42.732  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:39:46.037  3410  3864 E Watchdog: !@Sync 38 [03-21 14:39:46.042]
,03-21 14:39:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:39:50.962  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:39:50.962  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-21 14:39:50.967  3410  4030 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
03-21 14:39:50.967  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:39:50.967  3410  4030 D BatteryService: stay LED for fully charged
,03-21 14:39:50.977  3410  3410 I MotionRecognitionService: Plugged
03-21 14:39:50.977  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:39:50.977  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:39:50.977  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:39:50.982  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:39:50.982  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:39:50.982  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:39:51.002  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:39:51.002  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:39:51.012  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:39:51.017  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:51.017  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:39:51.017  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:39:52.762  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:40:01.102  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:40:01.102  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:40:01.102  3410  4415 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,03-21 14:40:01.102  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:40:01.107  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:40:01.112  3410  3410 I MotionRecognitionService: Plugged
03-21 14:40:01.112  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:40:01.112  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:40:01.112  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:40:01.122  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:40:01.122  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:01.122  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:40:01.142  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:40:01.142  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:40:01.157  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:40:01.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:01.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:01.157  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:02.797  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:40:11.237  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:40:11.237  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:40:11.237  3410  3773 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-21 14:40:11.237  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:40:11.242  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:40:11.252  3410  3410 I MotionRecognitionService: Plugged
03-21 14:40:11.252  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:40:11.252  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:40:11.252  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:40:11.262  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:11.262  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:11.262  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:40:11.277  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:40:11.277  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:40:11.287  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:40:11.287  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:11.292  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:11.292  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:12.827  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-21 14:40:16.047  3410  3864 E Watchdog: !@Sync 39 [03-21 14:40:16.050]
,03-21 14:40:21.382  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:40:21.382  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:40:21.382  3410  4749 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-21 14:40:21.382  3410  4749 D BatteryService: stay LED for fully charged,
03-21 14:40:21.382  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:40:21.387  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:40:21.387  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:40:21.387  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:40:21.387  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:40:21.392  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:40:21.392  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:21.392  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:40:21.407  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:40:21.407  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:40:21.417  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:40:21.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:21.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:21.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:22.862  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 13, LCD = 0
,03-21 14:40:31.512  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:40:31.517  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:40:31.517  3410  3966 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-21 14:40:31.517  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:40:31.522  3410  3410 I MotionRecognitionService: Plugged
03-21 14:40:31.522  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:40:31.522  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:40:31.522  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:40:31.527  3410  3966 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-21 14:40:31.527  3410  3966 D BatteryService: stay LED for fully charged
,03-21 14:40:31.537  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:40:31.537  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:31.537  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:40:31.552  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:40:31.552  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:40:31.562  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:40:31.567  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:31.567  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:31.567  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:32.892  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:40:41.652  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:40:41.652  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:40:41.652  3410  4029 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-21 14:40:41.657  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:40:41.662  3410  4029 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-21 14:40:41.662  3410  4029 D BatteryService: stay LED for fully charged
,03-21 14:40:41.667  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:40:41.667  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:40:41.667  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:40:41.667  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:40:41.677  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:40:41.677  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:41.677  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:40:41.697  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:40:41.697  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:40:41.707  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:41.707  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:41.707  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:41.707  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:42.922  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:40:43.442  3410  3608 D TimaService: TIMA: TimaService scheduler is intialized. 
03-21 14:40:43.442  3410  3608 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-21 14:40:43.447  3410  3607 D TimaService: TimaServiceHandler.handleMessage what =1
,03-21 14:40:44.102  3410  3572 I UsageStatsService: User[0] Flushing usage stats to disk
,03-21 14:40:44.637  3410  3582 I PowerManagerService: [PWL] Off : 1155s ago
03-21 14:40:44.637  3410  3582 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-21 14:40:44.637  3410  3582 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-21 14:40:44.637  3410  3582 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=3410, ws=null) (elapsedTime=1187)
,03-21 14:40:45.977  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-21 14:40:45.977  3410  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-21 14:40:45.997  3410  3608 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,03-21 14:40:46.002  3410  3608 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 14:40:46.052  3410  3864 E Watchdog: !@Sync 40 [03-21 14:40:46.057]
,03-21 14:40:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:40:51.792  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:40:51.792  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:40:51.792  3410  4046 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
03-21 14:40:51.792  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:40:51.797  3410  4046 D BatteryService: stay LED for fully charged,
03-21 14:40:51.797  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:40:51.797  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:40:51.797  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:40:51.797  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:40:51.807  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:40:51.807  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:40:51.807  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:40:51.822  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:40:51.822  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:40:51.832  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:40:51.832  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:51.832  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:40:51.832  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:40:52.952  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:41:01.927  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:41:01.927  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:41:01.927  3410  3852 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-21 14:41:01.932  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:41:01.932  3410  3852 D BatteryService: stay LED for fully charged,
,03-21 14:41:01.942  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:41:01.942  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:41:01.942  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:41:01.942  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:41:01.952  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:41:01.952  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:41:01.952  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:41:01.972  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:41:01.972  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:41:01.982  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:41:01.987  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:01.987  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:01.987  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:02.977  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:41:12.067  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:41:12.067  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:41:12.067  3410  3435 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-21 14:41:12.067  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:41:12.077  3410  3435 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-21 14:41:12.077  3410  3435 D BatteryService: stay LED for fully charged,
,03-21 14:41:12.082  3410  3410 I MotionRecognitionService: Plugged
03-21 14:41:12.082  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:41:12.082  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:41:12.082  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:41:12.087  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:41:12.087  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:41:12.092  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:41:12.107  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:41:12.107  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:41:12.117  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:41:12.117  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:12.117  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:12.117  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:13.002  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:41:16.062  3410  3864 E Watchdog: !@Sync 41 [03-21 14:41:16.065]
,03-21 14:41:22.202  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:41:22.202  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:41:22.202  3410  3734 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,03-21 14:41:22.212  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:41:22.212  3410  3734 D BatteryService: stay LED for fully charged,
,03-21 14:41:22.217  3410  3410 I MotionRecognitionService: Plugged
03-21 14:41:22.217  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:41:22.217  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:41:22.217  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:41:22.232  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:41:22.232  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:41:22.232  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:41:22.252  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:41:22.252  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:41:22.262  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:41:22.262  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:22.262  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:22.262  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:23.032  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:41:32.347  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:41:32.347  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:41:32.347  3410  4046 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-21 14:41:32.347  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:41:32.357  3410  3410 I MotionRecognitionService: Plugged
03-21 14:41:32.357  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:41:32.357  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:41:32.357  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:41:32.357  3410  4046 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-21 14:41:32.357  3410  4046 D BatteryService: stay LED for fully charged
,03-21 14:41:32.367  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:41:32.367  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:41:32.367  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:41:32.387  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:41:32.387  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:41:32.397  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:41:32.397  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:32.397  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:32.397  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:33.057  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:41:42.472  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:41:42.472  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:41:42.472  3410  3852 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
03-21 14:41:42.472  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:41:42.477  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:41:42.482  3410  3410 I MotionRecognitionService: Plugged
03-21 14:41:42.482  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:41:42.482  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:41:42.482  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:41:42.487  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:41:42.487  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:41:42.492  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:41:42.507  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:41:42.512  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:41:42.522  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:41:42.522  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:42.522  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:42.522  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:43.082  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:41:46.072  3410  3864 E Watchdog: !@Sync 42 [03-21 14:41:46.074]
,03-21 14:41:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:41:52.612  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:41:52.612  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:41:52.612  3410  3435 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-21 14:41:52.612  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:41:52.622  3410  3410 I MotionRecognitionService: Plugged
03-21 14:41:52.622  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:41:52.622  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:41:52.622  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:41:52.627  3410  3435 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-21 14:41:52.627  3410  3435 D BatteryService: stay LED for fully charged
,03-21 14:41:52.637  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:41:52.637  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:41:52.637  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:41:52.657  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:41:52.657  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:41:52.667  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:41:52.667  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:52.667  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:41:52.667  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:41:53.107  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-21 14:42:02.747  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:42:02.747  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:42:02.747  3410  3734 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-21 14:42:02.752  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:42:02.757  3410  3734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-21 14:42:02.757  3410  3734 D BatteryService: stay LED for fully charged,
03-21 14:42:02.757  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:42:02.757  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:42:02.757  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:42:02.757  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:42:02.772  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:42:02.772  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:02.772  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:42:02.787  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:42:02.787  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:42:02.797  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:42:02.802  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:02.802  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:42:02.802  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:42:03.132  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:42:12.882  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:42:12.882  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:42:12.882  3410  4783 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-21 14:42:12.887  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:42:12.887  3410  4783 D BatteryService: stay LED for fully charged
,03-21 14:42:12.892  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:42:12.897  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:42:12.897  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:42:12.897  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:42:12.907  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:42:12.907  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:42:12.917  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 14:42:12.917  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:12.917  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
03-21 14:42:12.917  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-21 14:42:12.917  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 14:42:12.917  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:12.922  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:42:13.162  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0,
,03-21 14:42:16.077  3410  3864 E Watchdog: !@Sync 43 [03-21 14:42:16.082]
,03-21 14:42:23.022  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:42:23.022  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:42:23.022  3410  3434 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-21 14:42:23.027  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:42:23.027  3410  3434 D BatteryService: stay LED for fully charged,
,03-21 14:42:23.037  3410  3410 I MotionRecognitionService: Plugged
03-21 14:42:23.037  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:42:23.037  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-21 14:42:23.037  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:42:23.047  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:23.047  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:23.047  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:42:23.062  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:42:23.062  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:42:23.072  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:42:23.072  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:23.072  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:42:23.072  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:42:23.197  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:42:33.162  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:42:33.162  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:42:33.162  3410  4781 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
03-21 14:42:33.162  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:42:33.167  3410  4781 D BatteryService: stay LED for fully charged,
,03-21 14:42:33.172  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:42:33.172  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:42:33.172  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:42:33.172  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:42:33.177  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:33.177  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:42:33.177  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:42:33.192  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:42:33.192  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:42:33.202  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:42:33.207  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:33.207  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:33.207  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:42:33.207  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:42:34.642  3410  3582 I PowerManagerService: [PWL] Off : 1265s ago
,03-21 14:42:43.222  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 9, LCD = 0
,03-21 14:42:43.292  3410  4131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:42:43.292  3410  4131 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:42:43.292  3410  4131 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
03-21 14:42:43.292  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:42:43.292  3410  4131 D BatteryService: stay LED for fully charged
,03-21 14:42:43.302  3410  3410 I MotionRecognitionService: Plugged
03-21 14:42:43.302  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:42:43.302  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:42:43.302  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:42:43.307  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:42:43.307  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:43.307  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:42:43.322  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:42:43.322  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:42:43.332  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:43.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:43.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:43.332  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:42:46.087  3410  3864 E Watchdog: !@Sync 44 [03-21 14:42:46.090]
,03-21 14:42:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:42:53.252  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 9, LCD = 0
,03-21 14:42:53.412  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:42:53.412  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:42:53.412  3410  4700 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
03-21 14:42:53.412  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:42:53.412  3410  4700 D BatteryService: stay LED for fully charged
,03-21 14:42:53.417  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:42:53.417  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:42:53.417  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:42:53.417  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:42:53.427  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:42:53.427  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:53.427  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:42:53.442  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:42:53.442  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:42:53.452  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:42:53.452  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:53.452  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:42:53.452  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:43:03.287  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 12, LCD = 0
,03-21 14:43:03.532  3410  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:43:03.532  3410  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:43:03.532  3410  4030 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
03-21 14:43:03.532  3410  4030 D BatteryService: stay LED for fully charged
03-21 14:43:03.532  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:43:03.537  3410  3410 I MotionRecognitionService: Plugged
03-21 14:43:03.537  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:43:03.537  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:43:03.537  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:43:03.547  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:43:03.547  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:03.547  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:43:03.552  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:43:03.552  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:43:03.552  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:43:03.567  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:43:03.567  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:03.567  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:43:13.312  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 11, LCD = 0
,03-21 14:43:13.672  3410  4415 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:43:13.672  3410  4415 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:43:13.672  3410  4415 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,03-21 14:43:13.677  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:43:13.677  3410  4415 D BatteryService: stay LED for fully charged
,03-21 14:43:13.687  3410  3410 I MotionRecognitionService: Plugged
03-21 14:43:13.687  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:43:13.687  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:43:13.687  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:43:13.697  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:13.697  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:13.697  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:43:13.717  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:43:13.717  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:43:13.727  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:13.727  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:13.727  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:13.727  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:43:16.097  3410  3864 E Watchdog: !@Sync 45 [03-21 14:43:16.098]
,03-21 14:43:23.337  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:43:23.812  3410  3773 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:43:23.812  3410  3773 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:43:23.812  3410  3773 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-21 14:43:23.817  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:43:23.817  3410  3773 D BatteryService: stay LED for fully charged,
,03-21 14:43:23.827  3410  3410 I MotionRecognitionService: Plugged
03-21 14:43:23.827  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:43:23.827  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:43:23.827  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:43:23.837  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:43:23.837  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:43:23.842  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:43:23.852  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:43:23.852  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,03-21 14:43:23.852  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:43:23.867  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:43:23.867  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:23.867  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:43:33.367  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:43:33.952  3410  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:43:33.952  3410  4749 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:43:33.952  3410  4749 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-21 14:43:33.957  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:43:33.957  3410  4749 D BatteryService: stay LED for fully charged
,03-21 14:43:33.967  3410  3410 I MotionRecognitionService: Plugged
03-21 14:43:33.967  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:43:33.967  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:43:33.967  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:43:33.977  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:43:33.977  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:33.977  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:43:33.987  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:43:33.992  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:43:34.002  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:43:34.002  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:34.002  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:34.002  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:43:43.402  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 9, LCD = 0
,03-21 14:43:44.097  3410  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:43:44.097  3410  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:43:44.097  3410  3966 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
03-21 14:43:44.097  3410  3966 D BatteryService: stay LED for fully charged
03-21 14:43:44.097  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:43:44.102  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:43:44.102  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:43:44.102  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:43:44.102  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:43:44.107  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:44.107  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:44.107  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:43:44.122  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:43:44.122  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:43:44.132  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:43:44.137  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:44.137  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:44.137  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,03-21 14:43:46.102  3410  3864 E Watchdog: !@Sync 46 [03-21 14:43:46.105]
,03-21 14:43:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:43:53.432  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:43:54.227  3410  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:43:54.227  3410  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:43:54.232  3410  4029 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,03-21 14:43:54.232  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:43:54.232  3410  4029 D BatteryService: stay LED for fully charged
,03-21 14:43:54.242  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:43:54.242  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:43:54.242  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:43:54.242  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:43:54.252  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:43:54.257  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:43:54.257  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:43:54.272  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:43:54.272  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:43:54.282  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:43:54.282  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:54.282  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:43:54.282  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:44:03.462  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 10, LCD = 0
,03-21 14:44:04.367  3410  4046 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 14:44:04.367  3410  4046 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:44:04.367  3410  4046 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-21 14:44:04.372  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:44:04.382  3410  3410 I MotionRecognitionService: Plugged
03-21 14:44:04.382  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:44:04.382  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:44:04.382  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
03-21 14:44:04.382  3410  4046 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
03-21 14:44:04.382  3410  4046 D BatteryService: stay LED for fully charged
,03-21 14:44:04.392  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:44:04.392  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:44:04.392  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:44:04.412  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:44:04.417  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:44:04.422  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:44:04.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:04.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:04.422  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:44:13.497  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 8, LCD = 0
,03-21 14:44:14.507  3410  3852 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:44:14.507  3410  3852 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:44:14.507  3410  3852 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-21 14:44:14.512  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:44:14.512  3410  3852 D BatteryService: stay LED for fully charged
,03-21 14:44:14.517  3410  3410 I MotionRecognitionService: Plugged,
03-21 14:44:14.517  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:44:14.517  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 14:44:14.522  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:44:14.532  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:44:14.532  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:44:14.532  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:44:14.547  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:44:14.547  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:44:14.562  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:44:14.562  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:44:14.562  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:14.567  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:44:16.112  3410  3864 E Watchdog: !@Sync 47 [03-21 14:44:16.112]
,03-21 14:44:23.537  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 8, LCD = 0
,03-21 14:44:24.647  3410  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:44:24.647  3410  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:44:24.647  3410  3435 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-21 14:44:24.647  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:44:24.652  3410  3435 D BatteryService: stay LED for fully charged,
,03-21 14:44:24.657  3410  3410 I MotionRecognitionService: Plugged
,03-21 14:44:24.657  3410  3410 D MotionRecognitionService:   cableConnection= 1
,03-21 14:44:24.657  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:44:24.657  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:44:24.667  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:44:24.667  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:44:24.667  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:44:24.687  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:44:24.687  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:44:24.697  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:44:24.697  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:24.697  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:24.697  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:44:29.642  3410  3582 I PowerManagerService: [PWL] Off : 1380s ago
,03-21 14:44:33.562  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 8, LCD = 0
,03-21 14:44:34.787  3410  3734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:44:34.787  3410  3734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:44:34.787  3410  3734 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,03-21 14:44:34.787  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:44:34.797  3410  3410 I MotionRecognitionService: Plugged
03-21 14:44:34.797  3410  3410 D MotionRecognitionService:   cableConnection= 1,
,03-21 14:44:34.797  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:44:34.797  3410  3410 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 14:44:34.802  3410  3734 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-21 14:44:34.807  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:44:34.802  3410  3734 D BatteryService: stay LED for fully charged
03-21 14:44:34.807  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:44:34.807  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:44:34.827  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:44:34.832  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:44:34.842  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:44:34.842  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:34.842  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:34.842  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:44:43.592  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 8, LCD = 0
,03-21 14:44:44.922  3410  4783 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:44:44.922  3410  4783 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:44:44.922  3410  4783 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,03-21 14:44:44.927  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:44:44.937  3410  3410 I MotionRecognitionService: Plugged
03-21 14:44:44.937  3410  3410 D MotionRecognitionService:   cableConnection= 1,
03-21 14:44:44.937  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-21 14:44:44.937  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:44:44.937  3410  4783 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
,03-21 14:44:44.937  3410  4783 D BatteryService: stay LED for fully charged
,03-21 14:44:44.947  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:44:44.947  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:44:44.947  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 14:44:44.967  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:44:44.967  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:44:44.977  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:44:44.977  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:44.977  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:44.977  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:44:46.117  3410  3864 E Watchdog: !@Sync 48 [03-21 14:44:46.120]
,03-21 14:44:49.047  2894  4774 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 14:44:53.622  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 8, LCD = 0
,03-21 14:44:55.062  3410  3434 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:44:55.062  3410  3434 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:44:55.062  3410  3434 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-21 14:44:55.062  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:44:55.072  3410  3410 I MotionRecognitionService: Plugged
03-21 14:44:55.072  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:44:55.072  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:44:55.072  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:44:55.077  3410  3434 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
,03-21 14:44:55.077  3410  3434 D BatteryService: stay LED for fully charged,
,03-21 14:44:55.087  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:44:55.087  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 14:44:55.087  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:44:55.107  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 14:44:55.107  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:44:55.117  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:44:55.117  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:55.117  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:44:55.117  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:45:03.652  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 8, LCD = 0
,03-21 14:45:05.227  3410  4781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:45:05.227  3410  4781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:45:05.227  3410  4781 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,03-21 14:45:05.227  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 14:45:05.242  3410  3410 I MotionRecognitionService: Plugged
03-21 14:45:05.242  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:45:05.242  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:45:05.242  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
,03-21 14:45:05.242  3410  4781 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-21 14:45:05.242  3410  4781 D BatteryService: stay LED for fully charged
,03-21 14:45:05.252  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 14:45:05.252  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:45:05.252  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 14:45:05.267  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 14:45:05.267  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
,03-21 14:45:05.277  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 14:45:05.277  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:45:05.277  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:45:05.282  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 14:45:13.682  3410  6093 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 8, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms),03-21 14:45:14.632 12265 12265 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 14:45:14.642 12265 12265 D AndroidRuntime: CheckJNI is OFF
03-21 14:45:14.642 12265 12265 D AndroidRuntime: readGMSProperty: start
03-21 14:45:14.642 12265 12265 D AndroidRuntime: readGMSProperty: already setted!!
03-21 14:45:14.642 12265 12265 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 14:45:14.642 12265 12265 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 14:45:14.642 12265 12265 D AndroidRuntime: readGMSProperty: end
03-21 14:45:14.642 12265 12265 D AndroidRuntime: addProductProperty: start
03-21 14:45:14.847 12265 12265 E AffinityControl: AffinityControl: registerfunction enter
03-21 14:45:14.877 12265 12265 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-21 14:45:14.887  3410  3734 D PackageManager: START PACKAGE DELETE: observer{641950367}
03-21 14:45:14.887  3410  3734 D PackageManager: pkg{<packageName>}
03-21 14:45:14.887  3410  3734 D PackageManager: user{0}
03-21 14:45:14.887  3410  3734 D PackageManager: caller{2000}
03-21 14:45:14.887  3410  3734 D PackageManager: flags{2}
03-21 14:45:14.887  3410  3734 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 14:45:14.887  3410  3734 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 14:45:14.887  3410  3734 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 14:45:14.887  3410  3734 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 14:45:14.887  3410  3589 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-21 14:45:14.887  3410  3734 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 14:45:14.887  3410  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 14:45:14.887  3410  3589 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-21 14:45:14.887  3410  3589 D ApplicationPolicy: getApplicationUninstallationEnabled
03-21 14:45:14.887  3410  3589 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-21 14:45:14.892  3410  3589 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
03-21 14:45:14.892  3410  3575 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
03-21 14:45:14.892  3410  3575 I ActivityManager: Killing 11054:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
03-21 14:45:14.917  3410  3575 I ActivityManager:   Force finishing activity 3 ActivityRecord{1cc2a770 u0 com.test.thalitest/.MainActivity t40}
03-21 14:45:14.922  3410  3575 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-21 14:45:14.922  3410  3575 D InputDispatcher: Focus left window: 11054
03-21 14:45:14.927  2859 11069 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
03-21 14:45:14.927  2859  3007 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
03-21 14:45:14.932  3410  3575 D InputDispatcher: Focused application released
03-21 14:45:14.932  3410  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3410 uid:1000
03-21 14:45:14.932  3410  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 14:45:14.932  3410  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3410 uid:1000
03-21 14:45:14.932  3410  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 14:45:15.022  3410  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
03-21 14:45:15.027  3410  3589 W PackageSettings: Skipping PackageSetting{a41f397 com.example.hello/10691} due to missing metadata
03-21 14:45:15.057  3410  3589 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
03-21 14:45:15.067  3410  3589 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
03-21 14:45:15.107  3923  3923 I art     : Explicit concurrent mark sweep GC freed 1406(76KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 3.131ms total 21.770ms
03-21 14:45:15.117  9179  9179 I art     : Explicit concurrent mark sweep GC freed 20370(1153KB) AllocSpace objects, 2(32KB) LOS objects, 69% free, 1812KB/5MB, paused 886us total 27.118ms
03-21 14:45:15.122  3410  3589 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 14:45:15.137  4031  4031 I art     : Explicit concurrent mark sweep GC freed 2323(126KB) AllocSpace objects, 10(1489KB) LOS objects, 12% free, 56MB/64MB, paused 538us total 51.771ms
03-21 14:45:15.142  4596  4596 I art     : Explicit concurrent mark sweep GC freed 4593(315KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 8MB/11MB, paused 1.134ms total 71.145ms
03-21 14:45:15.152  4128  4128 I art     : Explicit concurrent mark sweep GC freed 3025(189KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 653us total 48.239ms
03-21 14:45:15.152  3410  3632 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-21 14:45:15.152  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
03-21 14:45:15.157  4507  4507 E SamsungIME: mOCRHelper is null
03-21 14:45:15.162  4332  4728 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-21 14:45:15.167  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.167  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.167  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.167  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.172 10701 10701 D LWLocationManager: getDeviceLocationId :  id = -100
03-21 14:45:15.172 10701 10701 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-21 14:45:15.182 12284 12284 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.182 12284 12284 E Zygote  : v2
03-21 14:45:15.182 12284 12284 I libpersona: KNOX_SDCARD checking this for 10063
03-21 14:45:15.182 12284 12284 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.187 12284 12284 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.187 12284 12284 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.187 12284 12284 E Zygote  : accessInfo : 0
03-21 14:45:15.187 12284 12284 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:45:15.192  3410  3575 I ActivityManager: Start proc 12284:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
03-21 14:45:15.202  3410  3691 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
03-21 14:45:15.202  3410  3691 D TaskPersister: removeObsoleteFile: deleting file=40_task_thumbnail.png
03-21 14:45:15.212  3410  3652 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-21 14:45:15.212  3410  3652 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 14:45:15.212  3410  3652 V NetworkStats: performPollLocked(flags=0x3)
03-21 14:45:15.217 12284 12284 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.217  5659  5677 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-21 14:45:15.217  5659  5677 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
03-21 14:45:15.217  3410  3652 V NetworkStats: performPollLocked() took 7ms
03-21 14:45:15.217  3410  3652 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 14:45:15.217 12284 12284 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.227  3999  3999 D RegisteredServicesCache: empty dynamic service
03-21 14:45:15.237  3410  3434 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18b8a64a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{308589bb 12284:com.samsung.android.app.vrsetupwizardstub/u0a63}
03-21 14:45:15.247  3999  3999 D RegisteredComponentCache: Collect Tech packages for Knox
03-21 14:45:15.262  3410  3410 I art     : Explicit concurrent mark sweep GC freed 27132(2MB) AllocSpace objects, 31(496KB) LOS objects, 33% free, 27MB/41MB, paused 3.533ms total 161.151ms
03-21 14:45:15.262  3410  3589 I art     : WaitForGcToComplete blocked for 64.362ms for cause Explicit
03-21 14:45:15.272 12284 12284 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-21 14:45:15.272 12284 12284 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-21 14:45:15.272 12284 12284 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
03-21 14:45:15.277  3410  4781 I ActivityManager: Killing 10079:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
03-21 14:45:15.277  3410  4781 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18b8a64a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3643092c 7207:com.samsung.klmsagent/u0a21}
03-21 14:45:15.282  7207  7207 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 21 14:45:15 GMT+01:00 2016
03-21 14:45:15.282  3410  4749 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-21 14:45:15.292  7207  7207 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
03-21 14:45:15.292  3410  4415 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-21 14:45:15.297  3410  4415 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-21 14:45:15.297  3410  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18b8a64a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2b7a5a4e 6858:com.samsung.aasaservice/1000}
03-21 14:45:15.302  3410  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 14:45:15.302  3410  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 14:45:15.302  6858  6858 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
03-21 14:45:15.302  7207  7207 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
03-21 14:45:15.302  7207  7207 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-21 14:45:15.302  6858  6858 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-21 14:45:15.302  6858  6858 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-21 14:45:15.302  6858  6858 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-21 14:45:15.302  6858  6858 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-21 14:45:15.302  6858  6858 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-21 14:45:15.302  6858  6858 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-21 14:45:15.302  6858  6858 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 14:45:15.302  6858  6858 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 14:45:15.302  6858  6858 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 14:45:15.302  6858  6858 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 14:45:15.302  6858  6858 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 14:45:15.302  6858  6858 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 14:45:15.302  6858  6858 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 14:45:15.307  7207  7207 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-21 14:45:15.307  7207 12300 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-21 14:45:15.307  7207 12300 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-21 14:45:15.307  7207 12300 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-21 14:45:15.307  7207 12300 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-21 14:45:15.307  7207 12300 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-21 14:45:15.307  3410  4046 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-21 14:45:15.312  3410  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18b8a64a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{b333477 3410:system/1000}
03-21 14:45:15.312  7207 12300 I KLMS-2.5.262: : MDMBridge.getInstance()
03-21 14:45:15.312  7207 12300 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-21 14:45:15.317  7207 12300 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-21 14:45:15.317  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.317  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.317  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.317  7207 12300 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-21 14:45:15.317  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.322  7207 12300 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-21 14:45:15.322  7207 12300 E KLMS-2.5.262: : arr si null
03-21 14:45:15.327  7207 12300 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-21 14:45:15.327  7207 12300 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-21 14:45:15.327  7207 12300 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-21 14:45:15.327  7207 12300 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
03-21 14:45:15.347 12302 12302 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.347 12302 12302 E Zygote  : v2
03-21 14:45:15.347 12302 12302 I libpersona: KNOX_SDCARD checking this for 10042
03-21 14:45:15.347 12302 12302 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.347 12302 12302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.347 12302 12302 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.347  3410  3575 I ActivityManager: Start proc 12302:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
03-21 14:45:15.347 12302 12302 E Zygote  : accessInfo : 0
03-21 14:45:15.347 12302 12302 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-21 14:45:15.352  3410  4700 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 14:45:15.352  3410  4700 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 14:45:15.352  3410  4700 D BatteryService: online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
03-21 14:45:15.352  3410  4700 D BatteryService: stay LED for fully charged
03-21 14:45:15.352  3410  3575 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{21dae9a1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{32cabcf9 11959:com.samsung.android.sm/1000}
03-21 14:45:15.357  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.357  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.357  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.357  3410  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.367 12318 12318 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.367 12318 12318 E Zygote  : v2
03-21 14:45:15.367 12318 12318 I libpersona: KNOX_SDCARD checking this for 1000
03-21 14:45:15.367 12318 12318 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.372 12318 12318 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.372 12318 12318 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.372  3410  3575 I ActivityManager: Start proc 12318:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
03-21 14:45:15.372 12302 12302 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.372 12302 12302 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.372 12318 12318 E Zygote  : accessInfo : 0
03-21 14:45:15.372 12318 12318 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:45:15.382  2901  2901 I art     : Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 404us total 13.650ms
03-21 14:45:15.387 11959 11959 I art     : Explicit concurrent mark sweep GC freed 150(20KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1735KB/3MB, paused 460us total 14.318ms
03-21 14:45:15.392  2901  2901 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 189us total 5.943ms
03-21 14:45:15.392 12318 12318 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.392  7207 12300 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-21 14:45:15.392  7207 12300 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-21 14:45:15.392  7207 12300 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-21 14:45:15.392 12318 12318 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.392  7207 12300 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
03-21 14:45:15.397  3410  4781 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{29ca8a52 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{ece1123 12302:com.samsung.android.sdk.samsunglink/u0a42}
03-21 14:45:15.397  2901  2901 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 326us total 5.869ms
03-21 14:45:15.397  7207 12300 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-21 14:45:15.397  7207 12300 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-21 14:45:15.397  7207 12300 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-21 14:45:15.397  7207 12300 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
03-21 14:45:15.397  3410  3589 I art     : Explicit concurrent mark sweep GC freed 9807(966KB) AllocSpace objects, 2(2MB) LOS objects, 33% free, 25MB/37MB, paused 3.659ms total 133.603ms
03-21 14:45:15.402  3410  3435 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3d0cbd49 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{f8f064e 12318:com.sec.android.app.popupuireceiver/1000}
03-21 14:45:15.402  7207  7207 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
03-21 14:45:15.407 12302 12302 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 14:45:15.407 12302 12302 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-21 14:45:15.412  3410  4030 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{21dae9a1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{32cabcf9 11959:com.samsung.android.sm/1000}
03-21 14:45:15.417 12318 12318 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
03-21 14:45:15.422  3410  4030 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{21dae9a1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{32cabcf9 11959:com.samsung.android.sm/1000}
03-21 14:45:15.422  3410  4046 D SecContentProvider2: query(), uri = -1 selection = getSealedState
03-21 14:45:15.427  3410  3435 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
03-21 14:45:15.427 12318 12318 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
03-21 14:45:15.427  3410  3773 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
03-21 14:45:15.427  3410  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.427  3410  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.427  3410  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.427  3410  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.432 12318 12318 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-21 14:45:15.432 12318 12318 D PopupuiReceiver: Action package removed
03-21 14:45:15.437 12336 12336 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.437 12336 12336 I libpersona: KNOX_SDCARD checking this for 1000
03-21 14:45:15.437 12336 12336 E Zygote  : v2
03-21 14:45:15.437 12336 12336 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.437 12336 12336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.437 12336 12336 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.437 12336 12336 E Zygote  : accessInfo : 0
03-21 14:45:15.437 12336 12336 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:45:15.442  3410  4030 I ActivityManager: Start proc 12336:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
03-21 14:45:15.442  3410  3589 D PackageManager: delete codoeFile: 
03-21 14:45:15.442  3410  3589 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-21 14:45:15.442  3410  4030 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3d0cbd49 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a7cae7 10630:com.samsung.android.snote/u0a160}
03-21 14:45:15.447  3410  4415 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.452  3410  4415 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.452  3410  4415 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.452  3410  4415 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.452  3410  3589 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-21 14:45:15.452  3410  3589 I AASA_removePackage: UID=10011 Target=com.test.thalitest
03-21 14:45:15.452 11959 12333 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-21 14:45:15.457 12351 12351 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.457 12351 12351 I libpersona: KNOX_SDCARD checking this for 10183
03-21 14:45:15.457 12351 12351 E Zygote  : v2
03-21 14:45:15.457 12351 12351 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.457 12351 12351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.457 12351 12351 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.457 12351 12351 E Zygote  : accessInfo : 0
03-21 14:45:15.457  3410  3589 D PackageManager: result of delete: 1{641950367}
03-21 14:45:15.457  3410  3410 D RCPManagerService: PackageReceiver onReceive()
03-21 14:45:15.457  3410  3410 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-21 14:45:15.457 12351 12351 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:45:15.462 12336 12336 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.462  3410  4415 I ActivityManager: Start proc 12351:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
03-21 14:45:15.462  3410  3410 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-21 14:45:15.462 12336 12336 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.462  3410  3410 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-21 14:45:15.462  3410  3410 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
03-21 14:45:15.462  3410  3410 I OTPFW   : ProvisionData::getAllEntries Enter
03-21 14:45:15.462  3410  3410 E OTPFW   : ProvisionData::getAllEntries Table is empty
03-21 14:45:15.462  3410  3410 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 14:45:15.462  3410  3410 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 14:45:15.467 12265 12265 I art     : System.exit called, status: 0
03-21 14:45:15.467 12265 12265 I AndroidRuntime: VM exiting with result code 0.
03-21 14:45:15.467  3410  4415 I ActivityManager: Killing 10363:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
03-21 14:45:15.467  3410  3589 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 14:45:15.467  3410  3589 D PackageManager: userId{-1}
03-21 14:45:15.467  3410  3589 D PackageManager: andCode{true}
03-21 14:45:15.472 12351 12351 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.472 12351 12351 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.477  3410  3966 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{21dae9a1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{25737655 12336:com.samsung.android.app.assistantmenu/1000}
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicy: uID is 10011
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 14:45:15.477  3410  3410 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-21 14:45:15.477  3410  3410 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 14:45:15.477  3410  3410 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-21 14:45:15.477  3410  3410 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
03-21 14:45:15.482  3410  3410 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-21 14:45:15.482  3410  3594 D EnterprisePartitionManager: RCV <-
03-21 14:45:15.482  3410  3410 D EnterprisePartitionManager: RMV <-
03-21 14:45:15.487  3410  3435 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3d0cbd49 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3130c15b 12351:com.samsung.android.provider.shootingmodeprovider/u0a183}
03-21 14:45:15.487  9764 12368 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-21 14:45:15.487  9764 12368 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
03-21 14:45:15.487  9764 12368 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-21 14:45:15.492  3410  3410 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-21 14:45:15.492  3410  3410 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-21 14:45:15.492  3410  3410 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 14:45:15.492  3410  3410 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-21 14:45:15.492  3410  3410 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-21 14:45:15.492  3410  3410 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 14:45:15.492  3410  3410 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 14:45:15.492  3410  3410 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 14:45:15.492  3410  3410 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 14:45:15.492  3410  3410 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 14:45:15.492  3410  3410 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 14:45:15.492  3410  3410 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-21 14:45:15.492  3410  3410 W System.err: 	at libcore.io.Posix.open(Native Method)
03-21 14:45:15.492  3410  3410 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 14:45:15.492  3410  3410 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 14:45:15.492  3410  3410 W System.err: 	... 18 more
03-21 14:45:15.492  3410  3410 E SdpManagerService: failed to get engine list
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicy: uID is 10011
03-21 14:45:15.492  3410  6093 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 14:45:15.492  9764 12368 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
03-21 14:45:15.492  3410  3410 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-21 14:45:15.497  9764 12368 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-21 14:45:15.497  3410  3410 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18b8a64a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1353df73 6158:com.sec.android.service.health/u0a19}
03-21 14:45:15.497 12336 12336 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
03-21 14:45:15.497  3410  3410 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 14:45:15.497  6158  6158 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
03-21 14:45:15.497  3410  3966 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-21 14:45:15.497  3410  3410 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-21 14:45:15.497  6158  6158 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-21 14:45:15.497  6158  6158 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-21 14:45:15.502  9764 12368 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
03-21 14:45:15.502  4031  4031 D Launcher.Model: reloadBadges entered.
03-21 14:45:15.502 10837 10850 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
03-21 14:45:15.502 10837 10850 D BadgeProvider: sendNotify, [notify] : null
03-21 14:45:15.502 10837 10850 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-21 14:45:15.502 10837 10850 D BadgeProvider: update, [uri.query] : null
03-21 14:45:15.502 10837 10850 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 14:45:15.502 10837 10850 D BadgeProvider: update, [UpdateCount] : 1
03-21 14:45:15.507  3725  3725 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:45:15.507  3725  3725 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:45:15.507  3725  3725 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 14:45:15.512 12351 12351 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-21 14:45:15.512 12302 12302 I SL_DEBUG: isLoggable:: isProductShip = 1
03-21 14:45:15.517  5913  5913 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 14:45:15.517  5913  6008 D HeadsetStateMachine: Disconnected process message: 10
03-21 14:45:15.517 12302 12302 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
03-21 14:45:15.522 10837 10850 D BadgeProvider: query, [selection] : null
03-21 14:45:15.522 10701 12295 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-21 14:45:15.527  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.527  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.527  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.527  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.532  3725  3725 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 14:45:15.532  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:45:15.532  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:45:15.532  3725  3725 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 14:45:15.537 12374 12374 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.537 12374 12374 E Zygote  : v2
03-21 14:45:15.537 12374 12374 I libpersona: KNOX_SDCARD checking this for 1000
03-21 14:45:15.537 12374 12374 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.542 12374 12374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.542 12374 12374 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.542 12374 12374 E Zygote  : accessInfo : 0
03-21 14:45:15.542 12374 12374 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:45:15.542  3410  4046 I ActivityManager: Start proc 12374:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
03-21 14:45:15.547  3410  4415 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-21 14:45:15.557 12374 12374 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.557 12374 12374 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.562 10701 10701 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-21 14:45:15.562  3410  4046 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18b8a64a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1bc62cc4 10701:com.sec.android.widgetapp.locationwidget/u0a22}
03-21 14:45:15.567 10701 12295 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 14:45:15.567 10701 12295 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 14:45:15.567 10701 12295 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 14:45:15.567 10701 12295 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-21 14:45:15.572  3410  3410 I MotionRecognitionService: Plugged
03-21 14:45:15.572  3410  3410 D MotionRecognitionService:   cableConnection= 1
03-21 14:45:15.572  3410  3410 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 14:45:15.572  3410  3410 D MotionRecognitionService: skip setTransmitPower. 
03-21 14:45:15.572  3410  4749 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{21dae9a1 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1563d72f 12374:com.sec.knox.bridge/1000}
03-21 14:45:15.587  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.587  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.587  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.587  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.602 11959 12334 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 14:45:15.602 11959 12334 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 14:45:15.602 12391 12391 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.602 12391 12391 E Zygote  : v2
03-21 14:45:15.602 12391 12391 I libpersona: KNOX_SDCARD checking this for 10190
03-21 14:45:15.602 12391 12391 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.607 12391 12391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.607 12391 12391 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.607 12391 12391 E Zygote  : accessInfo : 0
03-21 14:45:15.607 12391 12391 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:45:15.607  3410  4046 I ActivityManager: Start proc 12391:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
03-21 14:45:15.617  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.617  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.617  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.617  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.617 12374 12374 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 14:45:15.632 12391 12391 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.637 12406 12406 E Zygote  : MountEmulatedStorage()
03-21 14:45:15.637 12406 12406 I libpersona: KNOX_SDCARD checking this for 1000
03-21 14:45:15.637 12406 12406 E Zygote  : v2
03-21 14:45:15.637 12406 12406 I libpersona: KNOX_SDCARD not a persona
03-21 14:45:15.637 12391 12391 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.637 12406 12406 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 14:45:15.637 12406 12406 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 14:45:15.637 12406 12406 E Zygote  : accessInfo : 0
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: Error inserting name=DBVersion value=2003
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 14:45:15.637 11959 12334 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 14:45:15.637 12406 12406 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 14:45:15.642 11959 12334 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 14:45:15.642 11959 12334 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 14:45:15.647 11959 12334 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 14:45:15.647  3410  4046 I ActivityManager: Start proc 12406:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
03-21 14:45:15.657  3410  4131 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{3d0cbd49 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{6e0b74b 12391:com.sec.android.widgetapp.tapandpay/u0a190}
03-21 14:45:15.657 11959 12334 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 14:45:15.657 11959 12334 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 14:45:15.657  3410  4700 I ActivityManager: Killing 10307:com.sec.android.automotive.drivelink/u0a102 (adj 15): emptyCount ##31
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: Error inserting name=UT enabled value=false
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 14:45:15.662 11959 12334 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 14:45:15.662 12374 12374 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-21 14:45:15.667 12406 12406 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 14:45:15.667  3410  4046 I ActivityManager: Killing 10449:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
03-21 14:45:15.667 12406 12406 D ActivityThread: Added TimaKeyStore provider
03-21 14:45:15.667  3410  4749 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-21 14:45:15.667  3410  4749 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
03-21 14:45:15.672  3410  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-21 14:45:15.672  3410  3604 D UsbHostManager: displayNotification : [02h,02h,01h]
03-21 14:45:15.672  3410  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-21 14:45:15.672  3410  3604 D UsbHostManager: displayNotification : [0ah,00h,00h]
03-21 14:45:15.672  3410  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-21 14:45:15.672  3410  3604 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-21 14:45:15.672  3410  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-21 14:45:15.672  3410  3604 D UsbHostManager: displayNotification : [0ah,00h,01h]
03-21 14:45:15.672  3410  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-21 14:45:15.672  3410  3604 D UsbHostManager: displayNotification : [09h,00h,00h]
03-21 14:45:15.672  3410  3693 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-21 14:45:15.672  3410  3693 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-21 14:45:15.672  3410  3693 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
03-21 14:45:15.677  2857  3075 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
03-21 14:45:15.677  2857  3075 W Vold    : Returning OperationFailed - no handler for errno 0
03-21 14:45:15.677 12302 12302 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
03-21 14:45:15.677 12302 12302 D SecWifiDisplayUtil: Metadata value : none
03-21 14:45:15.682  3410  3435 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{18b8a64a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{34891528 12406:com.sec.pcw.device/1000}
03-21 14:45:15.687  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.687  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.687  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.687  3410  4046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 14:45:15.692 11959 12334 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 14:45:15.692 11959 12334 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: #################################################################
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 14:45:15.697 11959 12334 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
