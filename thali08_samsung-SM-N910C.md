#### Test 64613803f00187f_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-30 14:13:48.059  3481  6076 D SSRM:n  : SIOP:: AP = 270, PST = 281 (W:14), CUR = 39, LCD = 0
,--------- beginning of main
03-30 14:13:49.029 11097 11097 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-30 14:13:49.039 11097 11097 D AndroidRuntime: CheckJNI is OFF
03-30 14:13:49.039 11097 11097 D AndroidRuntime: readGMSProperty: start
03-30 14:13:49.039 11097 11097 D AndroidRuntime: readGMSProperty: already setted!!
03-30 14:13:49.039 11097 11097 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-30 14:13:49.039 11097 11097 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-30 14:13:49.039 11097 11097 D AndroidRuntime: readGMSProperty: end
03-30 14:13:49.039 11097 11097 D AndroidRuntime: addProductProperty: start
03-30 14:13:49.244 11097 11097 E AffinityControl: AffinityControl: registerfunction enter
03-30 14:13:49.274 11097 11097 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-30 14:13:49.289  3481  4734 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-30 14:13:49.294  3481  4734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-30 14:13:49.324  3481  4734 W ActivityManager: mDVFSHelper.acquire()
03-30 14:13:49.329  3481  4734 V WindowManager: addAppToken: AppWindowToken{6c48059 token=Token{820fca0 ActivityRecord{90231a3 u0 com.test.thalitest/.MainActivity t42}}} to stack=1 task=42 at 0
03-30 14:13:49.334  3481  4734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:13:49.334  3481  4734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:13:49.334  3481  4734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:13:49.334  3481  4734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:13:49.339  3481  3582 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-30 14:13:49.339  3481  3582 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-30 14:13:49.344  3481  3582 D SecWifiDisplayUtil: Metadata value : none
03-30 14:13:49.344  3481  3582 V WindowManager: Adding window Window{b8dbfb8 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{5dd1ee u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-30 14:13:49.349 11115 11115 E Zygote  : MountEmulatedStorage()
03-30 14:13:49.349 11115 11115 E Zygote  : v2
03-30 14:13:49.349 11115 11115 I libpersona: KNOX_SDCARD checking this for 10011
03-30 14:13:49.349 11115 11115 I libpersona: KNOX_SDCARD not a persona
03-30 14:13:49.354  3481  4734 I ActivityManager: Start proc 11115:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-30 14:13:49.354  3481  4734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-30 14:13:49.354  3481  4734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-30 14:13:49.354  3481  4734 D InputDispatcher: Focused application set to: xxxx
03-30 14:13:49.354 11115 11115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-30 14:13:49.359  3481  4734 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-30 14:13:49.359  3481  4734 D InputDispatcher: Focus left window: 6574
03-30 14:13:49.359 11097 11097 D AndroidRuntime: Shutting down VM
03-30 14:13:49.359  3481  3582 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-30 14:13:49.359  3481  3582 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-30 14:13:49.359 11115 11115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-30 14:13:49.364 11115 11115 E Zygote  : accessInfo : 0
03-30 14:13:49.364  2860  2860 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-30 14:13:49.364 11115 11115 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-30 14:13:49.374  3481  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
03-30 14:13:49.374  3481  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
03-30 14:13:49.374  3481  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-30 14:13:49.379  3481  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-30 14:13:49.384 11115 11115 D TimaKeyStoreProvider: TimaSignature is unavailable
03-30 14:13:49.384 11115 11115 D ActivityThread: Added TimaKeyStore provider
03-30 14:13:49.389  3481  3743 D PowerManagerService: setKeyboardVisibility: false
03-30 14:13:49.394  3481  3580 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{b8dbfb8 u0 d0 Starting com.test.thalitest}
03-30 14:13:49.399  3481  3743 D ActivityManager:  Launching com.test.thalitest, updated priority
03-30 14:13:49.409  3481  3743 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{90231a3 u0 com.test.thalitest/.MainActivity t42}
03-30 14:13:49.424  2860  3007 I SurfaceFlinger: id=12 Removed YUIInstallC (7/9)
03-30 14:13:49.424  2860  3009 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-30 14:13:49.429  6574  6574 V ActivityThread: updateVisibility : ActivityRecord{83f17ad token=android.os.BinderProxy@207a0b7b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
03-30 14:13:49.564  3481  6076 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-30 14:13:49.604 11115 11115 D SecWifiDisplayUtil: Metadata value : none
,03-30 14:13:49.649 11115 11115 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-30 14:13:49.659 11115 11115 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7976-7978)
03-30 14:13:49.659 11115 11115 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-30 14:13:49.674 11115 11115 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6d51742}
,03-30 14:13:49.674 11115 11115 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-30 14:13:49.674 11115 11115 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-30 14:13:49.679 11115 11131 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-30 14:13:49.694 11115 11115 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-30 14:13:49.694 11115 11115 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-30 14:13:49.699 11115 11115 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-30 14:13:49.719 11115 11115 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-30 14:13:49.719 11115 11115 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-30 14:13:49.719 11115 11115 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-30 14:13:49.784 11115 11154 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-30 14:13:49.829 11115 11115 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-30 14:13:49.854 11115 11115 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-30 14:13:49.869 11115 11115 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-30 14:13:49.869 11115 11115 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-30 14:13:49.879 11115 11115 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-30 14:13:49.889 11115 11115 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-30 14:13:49.889 11115 11115 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-30 14:13:49.964 11115 11167 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-30 14:13:49.969  3481  3510 V WindowManager: Adding window Window{a351f39 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{b8dbfb8 u0 d0 Starting com.test.thalitest})
,03-30 14:13:49.969  3481  4021 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-30 14:13:49.969  3481  4021 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-30 14:13:49.969  3481  4021 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-30 14:13:49.969  3481  3481 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-30 14:13:49.969  3481  3481 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-30 14:13:49.974  3481  3481 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-30 14:13:49.974  3481  3481 D PersonaManagerService: getPersonasForUser(): returning null!
03-30 14:13:49.974  3481  3481 I EnterpriseSharedDevicePolicy: Get Result: -1
03-30 14:13:49.974  3481  3481 I EnterpriseSharedDevicePolicy: status: false
03-30 14:13:49.974  3481  3481 I KnoxTimeoutHandler: Shared devices show user statefalse
03-30 14:13:49.984 11115 11115 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-30 14:13:49.984 11115 11115 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-30 14:13:49.989 11115 11115 D SecWifiDisplayUtil: Metadata value : none
,03-30 14:13:49.999  2860  2860 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,03-30 14:13:50.004  3481  3961 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-30 14:13:50.009  3481  3961 D InputDispatcher: Focus entered window: 11115
,03-30 14:13:50.014  3481  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
03-30 14:13:50.014  3481  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
03-30 14:13:50.014  3481  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-30 14:13:50.014  3481  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-30 14:13:50.014 11115 11115 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-30 14:13:50.014 11115 11167 I OpenGLRenderer: Initialized EGL, version 1.4
,03-30 14:13:50.014 11115 11167 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae430c10 ,&mEglDisplay = 1 , &mEglConfig = -1266835184 
,03-30 14:13:50.019 11115 11167 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-30 14:13:50.019 11115 11167 D OpenGLRenderer: Enabling debug mode 0
,03-30 14:13:50.019 11115 11167 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-30 14:13:50.024 11115 11115 V ActivityThread: updateVisibility : ActivityRecord{27104a token=android.os.BinderProxy@210179ec {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-30 14:13:50.069  3481  3958 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-30 14:13:50.074  3723  3723 D PanelView: There is/are notification(s) 
,03-30 14:13:50.079  3481  3582 I ActivityManager: Displayed Component not be shown by security: +536ms (total +1m39s803ms)
,03-30 14:13:50.084  3481  3582 W ActivityManager: mDVFSHelper.release()
03-30 14:13:50.084  3481  3582 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{90231a3 u0 com.test.thalitest/.MainActivity t42} time:198402
,03-30 14:13:50.084  2860  4065 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
,03-30 14:13:50.084  2860  3009 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,03-30 14:13:50.109 11115 11115 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-30 14:13:50.109 11115 11115 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@210179ec time:198428
,03-30 14:13:50.139 11115 11115 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11115
,03-30 14:13:50.314 11115 11115 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-30 14:13:50.399 11115 11172 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1621989248
,03-30 14:13:50.404 11115 11172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-30 14:13:50.404 11115 11172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-30 14:13:50.404 11115 11172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-30 14:13:50.404 11115 11172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-30 14:13:50.404 11115 11172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-30 14:13:50.409 11115 11172 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a03f9ab added. We now have 1 listener(s)
,03-30 14:13:50.409 11115 11172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-30 14:13:50.414 11115 11172 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-30 14:13:50.414 11115 11172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-30 14:13:50.414 11115 11172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-30 14:13:50.414 11115 11131 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-30 14:13:50.419 11115 11172 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fac41c6 added. We now have 1 listener(s)
03-30 14:13:50.419 11115 11172 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-30 14:13:50.424 11115 11172 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-30 14:13:50.424 11115 11172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-30 14:13:50.424 11115 11172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-30 14:13:50.424 11115 11172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-30 14:13:50.424 11115 11172 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-30 14:13:50.429 11115 11172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:13:50.429 11115 11172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:13:50.434 11115 11172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-30 14:13:50.434 11115 11172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-30 14:13:50.434 11115 11172 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-30 14:13:50.439 11115 11172 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-30 14:13:50.439 11115 11115 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-30 14:13:50.439 11115 11115 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-30 14:13:50.464 11115 11115 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-30 14:13:50.859 11115 11178 W jxcore-log: Initializing JXcore engine
03-30 14:13:50.859 11115 11178 W jxcore-log: JXcore engine is ready
,03-30 14:13:50.894  4711  4711 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-30 14:13:50.894  4711  4711 E audit   : type=1400 msg=audit(1459340030.889:196): avc:  denied  { ioctl } for  pid=11178 comm="Thread-1529" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4244 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-30 14:13:50.894  3481  3578 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-30 14:13:50.894  4711  4711 E audit   :  SEPF_SM-N910C_5.1.1_0038
03-30 14:13:50.894  4711  4711 E audit   : type=1300 msg=audit(1459340030.889:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=967048d8 items=0 ppid=2902 ppcomm=main pid=11178 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1529" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-30 14:13:50.894  4711  4711 E audit   : type=1320 msg=audit(1459340030.889:196): 
03-30 14:13:50.894  3481  3578 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-30 14:13:50.894  3481  3578 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
03-30 14:13:50.899  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:13:50.899 11115 11178 W jxcore-log: Starting JXcore engine
03-30 14:13:50.899  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:13:50.899  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:13:50.899  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:13:50.909 11179 11179 E Zygote  : MountEmulatedStorage(),
03-30 14:13:50.909 11179 11179 E Zygote  : v2
03-30 14:13:50.909 11179 11179 I libpersona: KNOX_SDCARD checking this for 1000
03-30 14:13:50.909 11179 11179 I libpersona: KNOX_SDCARD not a persona
,03-30 14:13:50.909 11179 11179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:13:50.914  3481  3569 I ActivityManager: Start proc 11179:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-30 14:13:50.914 11179 11179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-30 14:13:50.914 11179 11179 E Zygote  : accessInfo : 0
03-30 14:13:50.914 11179 11179 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:13:50.929 11179 11179 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:13:50.934 11179 11179 D ActivityThread: Added TimaKeyStore provider
,03-30 14:13:50.939  3481  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{140d6ead u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{283f05e2 11179:com.samsung.android.securitylogagent/1000}
,03-30 14:13:50.949 11115 11178 W jxcore-log: Platform android
03-30 14:13:50.949 11115 11178 W jxcore-log: 
03-30 14:13:50.949 11115 11178 W jxcore-log: Process ARCH arm
03-30 14:13:50.949 11115 11178 W jxcore-log: 
,03-30 14:13:50.954 11179 11179 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-30 14:13:50.954 11179 11179 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-30 14:13:50.959  3481  4734 I ActivityManager: Killing 10090:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-30 14:13:51.044 11115 11178 I jxcore-log: JXcore Cordova bridge is ready!
03-30 14:13:51.044 11115 11178 I jxcore-log: 
03-30 14:13:51.044 11115 11178 W jxcore-log: JXcore engine is started
,03-30 14:13:51.049 11115 11172 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-30 14:13:51.049 11115 11115 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-30 14:13:52.339  3481  3689 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/42_task.xml.bak
,03-30 14:13:56.749 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:13:56.749 11115 11178 I jxcore-log: 
,03-30 14:13:56.754 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:13:56.754 11115 11178 I jxcore-log: 
,03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:13:56.754 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:13:56.754 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:13:56.759 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:13:56.759 11115 11178 I jxcore-log: 
,03-30 14:13:56.759 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:13:56.759 11115 11178 I jxcore-log: 
,03-30 14:13:56.949  3481  3960 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-30 14:13:56.949  3481  3960 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-30 14:13:56.949  3481  3960 D BatteryService: online:4, current avg:-67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-228
03-30 14:13:56.949  3481  3960 D BatteryService: stay LED for fully charged
03-30 14:13:56.949  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:13:56.954  3481  3481 I MotionRecognitionService: Plugged
03-30 14:13:56.954  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-30 14:13:56.954  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-30 14:13:56.954  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-30 14:13:56.954  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:13:56.954  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:13:56.954  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
03-30 14:13:56.959  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-30 14:13:56.959  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
03-30 14:13:56.959  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:13:56.959  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:13:56.959  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:13:56.959  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:13:57.084 11115 11178 I jxcore-log: Unit Test app is loaded
03-30 14:13:57.084 11115 11178 I jxcore-log: 
,03-30 14:13:57.089 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:13:57.089 11115 11178 I jxcore-log: 
,03-30 14:13:57.094 11115 11115 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-30 14:13:57.094 11115 11178 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-30 14:13:57.094 11115 11178 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-30 14:13:57.094 11115 11178 I jxcore-log: 
03-30 14:13:57.099 11115 11178 I jxcore-log: My device name is: samsung-SM-N910C
03-30 14:13:57.099 11115 11178 I jxcore-log: 
,03-30 14:13:57.724  3481  3584 I PowerManagerService: [PWL] Off : 140s ago
,03-30 14:13:58.074  3481  6076 D SSRM:n  : SIOP:: AP = 300, PST = 281 (W:10), CUR = -67, LCD = 0
,03-30 14:13:59.379  3481  3590 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-30 14:13:59.384  3481  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-30 14:13:59.464 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-30 14:13:59.464 11115 11178 I jxcore-log: 
,03-30 14:13:59.669 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-30 14:13:59.669 11115 11178 I jxcore-log: 
,03-30 14:13:59.679 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-30 14:13:59.679 11115 11178 I jxcore-log: 
,03-30 14:13:59.679 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-30 14:13:59.679 11115 11178 I jxcore-log: 
,03-30 14:13:59.699 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-30 14:13:59.699 11115 11178 I jxcore-log: 
,03-30 14:13:59.709 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-30 14:13:59.709 11115 11178 I jxcore-log: 
,03-30 14:13:59.709 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-30 14:13:59.709 11115 11178 I jxcore-log: 
,03-30 14:13:59.994  3481  3617 V AlarmManager: waitForAlarm result :8
,03-30 14:14:00.914 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-30 14:14:00.914 11115 11178 I jxcore-log: 
,03-30 14:14:00.924 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-30 14:14:00.924 11115 11178 I jxcore-log: 
,03-30 14:14:00.929 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-30 14:14:00.929 11115 11178 I jxcore-log: 
,03-30 14:14:01.079 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-30 14:14:01.079 11115 11178 I jxcore-log: 
,03-30 14:14:01.119 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-30 14:14:01.119 11115 11178 I jxcore-log: 
,03-30 14:14:01.149 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-30 14:14:01.149 11115 11178 I jxcore-log: 
,03-30 14:14:01.154 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-30 14:14:01.154 11115 11178 I jxcore-log: 
,03-30 14:14:01.159 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-30 14:14:01.159 11115 11178 I jxcore-log: 
,03-30 14:14:01.164 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-30 14:14:01.164 11115 11178 I jxcore-log: 
,03-30 14:14:01.164 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-30 14:14:01.164 11115 11178 I jxcore-log: 
,03-30 14:14:01.174 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-30 14:14:01.174 11115 11178 I jxcore-log: 
,03-30 14:14:01.184 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-30 14:14:01.184 11115 11178 I jxcore-log: 
,03-30 14:14:01.234 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-30 14:14:01.234 11115 11178 I jxcore-log: 
,03-30 14:14:01.234 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-30 14:14:01.234 11115 11178 I jxcore-log: 
,03-30 14:14:01.249 11115 11178 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-30 14:14:01.249 11115 11178 I jxcore-log: 
,03-30 14:14:01.494  3481  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-30 14:14:07.094  3481  3831 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-30 14:14:07.094  3481  3831 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-30 14:14:07.094  3481  3831 D BatteryService: online:4, current avg:-47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,03-30 14:14:07.099  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:14:07.104  3481  3481 I MotionRecognitionService: Plugged
03-30 14:14:07.104  3481  3481 D MotionRecognitionService:   cableConnection= 1,
03-30 14:14:07.104  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-30 14:14:07.104  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-30 14:14:07.109  3481  3831 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-30 14:14:07.109  3481  3831 D BatteryService: stay LED for fully charged,
,03-30 14:14:07.119  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-30 14:14:07.119  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-30 14:14:07.119  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-30 14:14:07.134  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:07.134  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-30 14:14:07.134  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
,03-30 14:14:07.149  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:07.149  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:07.149  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:08.099  3481  6076 D SSRM:n  : SIOP:: AP = 300, PST = 281 (W:10), CUR = -47, LCD = 0
,03-30 14:14:08.819 11115 11178 I jxcore-log: TAP version 13
03-30 14:14:08.819 11115 11178 I jxcore-log: 
,03-30 14:14:08.824 11115 11178 I jxcore-log: # setup
03-30 14:14:08.824 11115 11178 I jxcore-log: 
,03-30 14:14:09.074 11115 11178 I jxcore-log: # 1. calling createNativeListener directly rejects
03-30 14:14:09.074 11115 11178 I jxcore-log: 
,03-30 14:14:09.199 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:09.199 11115 11178 I jxcore-log: 
,03-30 14:14:09.209 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 60641
03-30 14:14:09.209 11115 11178 I jxcore-log: 
,03-30 14:14:09.219 11115 11178 I jxcore-log: ok 1 Should throw
03-30 14:14:09.219 11115 11178 I jxcore-log: 
,03-30 14:14:09.219 11115 11178 I jxcore-log: # teardown
03-30 14:14:09.219 11115 11178 I jxcore-log: 
,03-30 14:14:09.314 11115 11178 I jxcore-log: # setup
03-30 14:14:09.314 11115 11178 I jxcore-log: 
,03-30 14:14:09.489 11115 11178 I jxcore-log: # 2. emits incomingConnectionState
03-30 14:14:09.489 11115 11178 I jxcore-log: 
,03-30 14:14:09.609 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:09.609 11115 11178 I jxcore-log: 
,03-30 14:14:09.614 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 39592
03-30 14:14:09.614 11115 11178 I jxcore-log: 
,03-30 14:14:09.624 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:09.624 11115 11178 I jxcore-log: 
,03-30 14:14:09.629 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:09.629 11115 11178 I jxcore-log: 
,03-30 14:14:09.644 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:09.644 11115 11178 I jxcore-log: 
,03-30 14:14:09.649 11115 11178 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-30 14:14:09.649 11115 11178 I jxcore-log: 
,03-30 14:14:09.669 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:09.669 11115 11178 I jxcore-log: 
,03-30 14:14:09.669 11115 11178 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-30 14:14:09.669 11115 11178 I jxcore-log: 
,03-30 14:14:09.679 11115 11178 I jxcore-log: # teardown
03-30 14:14:09.679 11115 11178 I jxcore-log: 
,03-30 14:14:09.814 11115 11178 I jxcore-log: # setup
03-30 14:14:09.814 11115 11178 I jxcore-log: 
,03-30 14:14:09.969 11115 11178 I jxcore-log: # 3. emits routerPortConnectionFailed
03-30 14:14:09.969 11115 11178 I jxcore-log: 
,03-30 14:14:10.149 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:10.149 11115 11178 I jxcore-log: 
,03-30 14:14:10.149 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 48251
03-30 14:14:10.149 11115 11178 I jxcore-log: 
,03-30 14:14:10.159 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:10.159 11115 11178 I jxcore-log: 
,03-30 14:14:10.164 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:10.164 11115 11178 I jxcore-log: 
,03-30 14:14:10.164 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:10.164 11115 11178 I jxcore-log: 
,03-30 14:14:10.204 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:10.204 11115 11178 I jxcore-log: 
,03-30 14:14:10.209 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:10.209 11115 11178 I jxcore-log: 
,03-30 14:14:10.214 11115 11178 I jxcore-log: DEBUG createNativeListener: 
03-30 14:14:10.214 11115 11178 I jxcore-log: 
,03-30 14:14:10.219 11115 11178 I jxcore-log: ok 4 tried to connect to right port
03-30 14:14:10.219 11115 11178 I jxcore-log: 
,03-30 14:14:10.219 11115 11178 I jxcore-log: ok 5 failed due to refused connection
03-30 14:14:10.219 11115 11178 I jxcore-log: 
,03-30 14:14:10.219 11115 11178 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-30 14:14:10.219 11115 11178 I jxcore-log: 
,03-30 14:14:10.224 11115 11178 I jxcore-log: # teardown
03-30 14:14:10.224 11115 11178 I jxcore-log: 
,03-30 14:14:10.229 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:10.229 11115 11178 I jxcore-log: 
,03-30 14:14:10.369 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close,
03-30 14:14:10.369 11115 11178 I jxcore-log: 
,03-30 14:14:10.374 11115 11178 I jxcore-log: # setup
03-30 14:14:10.374 11115 11178 I jxcore-log: 
,03-30 14:14:10.379 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:10.379 11115 11178 I jxcore-log: 
,03-30 14:14:10.619 11115 11178 I jxcore-log: # 4. native server connections all up
03-30 14:14:10.619 11115 11178 I jxcore-log: 
,03-30 14:14:10.774 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:10.774 11115 11178 I jxcore-log: 
,03-30 14:14:10.794 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 36643
03-30 14:14:10.794 11115 11178 I jxcore-log: 
,03-30 14:14:10.804 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:10.804 11115 11178 I jxcore-log: 
,03-30 14:14:10.809 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:10.809 11115 11178 I jxcore-log: 
,03-30 14:14:10.814 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:10.814 11115 11178 I jxcore-log: 
,03-30 14:14:10.844 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:10.844 11115 11178 I jxcore-log: 
,03-30 14:14:10.849 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:10.849 11115 11178 I jxcore-log: 
,03-30 14:14:10.854 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:10.854 11115 11178 I jxcore-log: 
,03-30 14:14:10.859 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:10.859 11115 11178 I jxcore-log: 
,03-30 14:14:10.909 11115 11178 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-30 14:14:10.909 11115 11178 I jxcore-log: 
,03-30 14:14:10.909 11115 11178 I jxcore-log: ok 8 Send/recvd #1 should be same
03-30 14:14:10.909 11115 11178 I jxcore-log: 
,03-30 14:14:10.914 11115 11178 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-30 14:14:10.914 11115 11178 I jxcore-log: 
,03-30 14:14:10.914 11115 11178 I jxcore-log: ok 10 Send/recvd #2 should be same
03-30 14:14:10.914 11115 11178 I jxcore-log: 
,03-30 14:14:10.919 11115 11178 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-30 14:14:10.919 11115 11178 I jxcore-log: 
,03-30 14:14:10.929 11115 11178 I jxcore-log: # teardown
03-30 14:14:10.929 11115 11178 I jxcore-log: 
,03-30 14:14:11.044 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.044 11115 11178 I jxcore-log: 
,03-30 14:14:11.049 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.049 11115 11178 I jxcore-log: 
,03-30 14:14:11.059 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:11.059 11115 11178 I jxcore-log: 
,03-30 14:14:11.064 11115 11178 I jxcore-log: # setup
03-30 14:14:11.064 11115 11178 I jxcore-log: 
,03-30 14:14:11.064 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:11.064 11115 11178 I jxcore-log: 
,03-30 14:14:11.194 11115 11178 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-30 14:14:11.194 11115 11178 I jxcore-log: 
,03-30 14:14:11.324 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:11.324 11115 11178 I jxcore-log: 
,03-30 14:14:11.329 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 53240
03-30 14:14:11.329 11115 11178 I jxcore-log: 
,03-30 14:14:11.339 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:11.339 11115 11178 I jxcore-log: 
,03-30 14:14:11.344 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:11.344 11115 11178 I jxcore-log: 
,03-30 14:14:11.349 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:11.349 11115 11178 I jxcore-log: 
,03-30 14:14:11.369 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:11.369 11115 11178 I jxcore-log: 
,03-30 14:14:11.374 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:11.374 11115 11178 I jxcore-log: 
,03-30 14:14:11.389 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.389 11115 11178 I jxcore-log: 
,03-30 14:14:11.409 11115 11178 I jxcore-log: ok 12 socket shouldn't close until after stream
03-30 14:14:11.409 11115 11178 I jxcore-log: 
,03-30 14:14:11.409 11115 11178 I jxcore-log: ok 13 incoming remains open
03-30 14:14:11.409 11115 11178 I jxcore-log: 
,03-30 14:14:11.419 11115 11178 I jxcore-log: # teardown
03-30 14:14:11.419 11115 11178 I jxcore-log: 
,03-30 14:14:11.479 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:11.479 11115 11178 I jxcore-log: 
,03-30 14:14:11.484 11115 11178 I jxcore-log: # setup
03-30 14:14:11.484 11115 11178 I jxcore-log: 
,03-30 14:14:11.489 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:11.489 11115 11178 I jxcore-log: 
,03-30 14:14:11.669 11115 11178 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-30 14:14:11.669 11115 11178 I jxcore-log: 
,03-30 14:14:11.819 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:11.819 11115 11178 I jxcore-log: 
,03-30 14:14:11.824 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 59930
03-30 14:14:11.824 11115 11178 I jxcore-log: 
,03-30 14:14:11.834 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:11.834 11115 11178 I jxcore-log: 
,03-30 14:14:11.839 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:11.839 11115 11178 I jxcore-log: 
,03-30 14:14:11.839 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:11.839 11115 11178 I jxcore-log: 
,03-30 14:14:11.854 11115 11178 I jxcore-log: ok 14 we should not have gotten an error
03-30 14:14:11.854 11115 11178 I jxcore-log: 
,03-30 14:14:11.859 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:11.859 11115 11178 I jxcore-log: 
,03-30 14:14:11.869 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:11.869 11115 11178 I jxcore-log: 
,03-30 14:14:11.884 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:11.884 11115 11178 I jxcore-log: 
,03-30 14:14:11.884 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:11.884 11115 11178 I jxcore-log: 
,03-30 14:14:11.899 11115 11178 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-30 14:14:11.899 11115 11178 I jxcore-log: 
,03-30 14:14:11.899 11115 11178 I jxcore-log: ok 16 incoming is cleaned up
03-30 14:14:11.899 11115 11178 I jxcore-log: 
,03-30 14:14:11.909 11115 11178 I jxcore-log: # teardown
03-30 14:14:11.909 11115 11178 I jxcore-log: 
,03-30 14:14:11.984 11115 11178 I jxcore-log: # setup
03-30 14:14:11.984 11115 11178 I jxcore-log: 
,03-30 14:14:12.139 11115 11178 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-30 14:14:12.139 11115 11178 I jxcore-log: 
,03-30 14:14:12.289 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:12.289 11115 11178 I jxcore-log: 
,03-30 14:14:12.299 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 54280
03-30 14:14:12.299 11115 11178 I jxcore-log: 
,03-30 14:14:12.309 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:12.309 11115 11178 I jxcore-log: 
,03-30 14:14:12.314 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:12.314 11115 11178 I jxcore-log: 
,03-30 14:14:12.319 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:12.319 11115 11178 I jxcore-log: 
,03-30 14:14:12.334 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:12.334 11115 11178 I jxcore-log: 
,03-30 14:14:12.339 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:12.339 11115 11178 I jxcore-log: 
,03-30 14:14:12.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:12.354 11115 11178 I jxcore-log: 
,03-30 14:14:12.369 11115 11178 I jxcore-log: ok 17 stream was closed
03-30 14:14:12.369 11115 11178 I jxcore-log: 
,03-30 14:14:12.369 11115 11178 I jxcore-log: ok 18 incoming should survive
03-30 14:14:12.369 11115 11178 I jxcore-log: 
,03-30 14:14:12.369 11115 11178 I jxcore-log: ok 19 mux should have no streams
03-30 14:14:12.369 11115 11178 I jxcore-log: 
,03-30 14:14:12.379 11115 11178 I jxcore-log: # teardown
03-30 14:14:12.379 11115 11178 I jxcore-log: 
,03-30 14:14:12.559 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:12.559 11115 11178 I jxcore-log: 
,03-30 14:14:12.569 11115 11178 I jxcore-log: # setup
03-30 14:14:12.569 11115 11178 I jxcore-log: 
,03-30 14:14:12.574 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:12.574 11115 11178 I jxcore-log: 
,03-30 14:14:13.159 11115 11178 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-30 14:14:13.159 11115 11178 I jxcore-log: 
,03-30 14:14:13.299 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:13.299 11115 11178 I jxcore-log: 
,03-30 14:14:13.304 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 42745
03-30 14:14:13.304 11115 11178 I jxcore-log: 
,03-30 14:14:13.314 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.314 11115 11178 I jxcore-log: 
,03-30 14:14:13.319 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.319 11115 11178 I jxcore-log: 
,03-30 14:14:13.319 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.319 11115 11178 I jxcore-log: 
,03-30 14:14:13.334 11115 11178 I jxcore-log: ok 20 we should not have gotten an error
03-30 14:14:13.334 11115 11178 I jxcore-log: 
,03-30 14:14:13.339 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:13.339 11115 11178 I jxcore-log: 
,03-30 14:14:13.349 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:13.349 11115 11178 I jxcore-log: 
,03-30 14:14:13.359 11115 11178 I jxcore-log: ok 21 Buffers are identical
03-30 14:14:13.359 11115 11178 I jxcore-log: 
,03-30 14:14:13.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:13.359 11115 11178 I jxcore-log: 
,03-30 14:14:13.364 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:13.364 11115 11178 I jxcore-log: 
,03-30 14:14:13.369 11115 11178 I jxcore-log: ok 22 native server is nulled out
03-30 14:14:13.369 11115 11178 I jxcore-log: 
,03-30 14:14:13.374 11115 11178 I jxcore-log: ok 23 native server should be closed
03-30 14:14:13.374 11115 11178 I jxcore-log: 
,03-30 14:14:13.374 11115 11178 I jxcore-log: ok 24 incoming has been removed
03-30 14:14:13.374 11115 11178 I jxcore-log: 
,03-30 14:14:13.374 11115 11178 I jxcore-log: ok 25 Incoming should be done
03-30 14:14:13.374 11115 11178 I jxcore-log: 
03-30 14:14:13.374 11115 11178 I jxcore-log: ok 26 The mux object should be closed
03-30 14:14:13.374 11115 11178 I jxcore-log: 
,03-30 14:14:13.374 11115 11178 I jxcore-log: ok 27 The mux stream should be closed
03-30 14:14:13.374 11115 11178 I jxcore-log: 
,03-30 14:14:13.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:13.374 11115 11178 I jxcore-log: 
,03-30 14:14:13.394 11115 11178 I jxcore-log: # teardown
03-30 14:14:13.394 11115 11178 I jxcore-log: 
,03-30 14:14:13.489 11115 11178 I jxcore-log: # setup
03-30 14:14:13.489 11115 11178 I jxcore-log: 
,03-30 14:14:13.674 11115 11178 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-30 14:14:13.674 11115 11178 I jxcore-log: 
,03-30 14:14:13.874 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:13.874 11115 11178 I jxcore-log: 
,03-30 14:14:13.884 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 52833
03-30 14:14:13.884 11115 11178 I jxcore-log: 
,03-30 14:14:13.914 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.914 11115 11178 I jxcore-log: 
,03-30 14:14:13.914 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.914 11115 11178 I jxcore-log: 
,03-30 14:14:13.919 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.919 11115 11178 I jxcore-log: 
,03-30 14:14:13.924 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.924 11115 11178 I jxcore-log: 
,03-30 14:14:13.924 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.924 11115 11178 I jxcore-log: 
,03-30 14:14:13.929 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.929 11115 11178 I jxcore-log: 
,03-30 14:14:13.929 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.929 11115 11178 I jxcore-log: 
,03-30 14:14:13.934 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.934 11115 11178 I jxcore-log: 
,03-30 14:14:13.934 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.934 11115 11178 I jxcore-log: 
,03-30 14:14:13.939 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.939 11115 11178 I jxcore-log: 
,03-30 14:14:13.944 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.944 11115 11178 I jxcore-log: 
,03-30 14:14:13.944 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.944 11115 11178 I jxcore-log: 
,03-30 14:14:13.954 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.954 11115 11178 I jxcore-log: 
,03-30 14:14:13.959 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.959 11115 11178 I jxcore-log: 
,03-30 14:14:13.959 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.959 11115 11178 I jxcore-log: 
,03-30 14:14:13.964 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.964 11115 11178 I jxcore-log: 
,03-30 14:14:13.964 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.964 11115 11178 I jxcore-log: 
,03-30 14:14:13.969 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.969 11115 11178 I jxcore-log: 
,03-30 14:14:13.974 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.974 11115 11178 I jxcore-log: 
,03-30 14:14:13.974 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.974 11115 11178 I jxcore-log: 
,03-30 14:14:13.974 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.974 11115 11178 I jxcore-log: 
,03-30 14:14:13.984 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.984 11115 11178 I jxcore-log: 
,03-30 14:14:13.984 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.984 11115 11178 I jxcore-log: 
,03-30 14:14:13.984 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.984 11115 11178 I jxcore-log: 
,03-30 14:14:13.989 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.989 11115 11178 I jxcore-log: 
,03-30 14:14:13.989 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.989 11115 11178 I jxcore-log: 
,03-30 14:14:13.994 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.994 11115 11178 I jxcore-log: 
,03-30 14:14:13.994 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:13.994 11115 11178 I jxcore-log: 
,03-30 14:14:13.994 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:13.994 11115 11178 I jxcore-log: 
,03-30 14:14:13.999 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:13.999 11115 11178 I jxcore-log: 
,03-30 14:14:14.144 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.144 11115 11178 I jxcore-log: 
,03-30 14:14:14.144 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.144 11115 11178 I jxcore-log: 
,03-30 14:14:14.149 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.149 11115 11178 I jxcore-log: 
,03-30 14:14:14.149 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.149 11115 11178 I jxcore-log: 
,03-30 14:14:14.149 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.149 11115 11178 I jxcore-log: 
,03-30 14:14:14.154 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.154 11115 11178 I jxcore-log: 
,03-30 14:14:14.154 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.154 11115 11178 I jxcore-log: 
,03-30 14:14:14.154 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.154 11115 11178 I jxcore-log: 
,03-30 14:14:14.154 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.154 11115 11178 I jxcore-log: 
,03-30 14:14:14.159 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.159 11115 11178 I jxcore-log: 
,03-30 14:14:14.159 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.159 11115 11178 I jxcore-log: 
,03-30 14:14:14.159 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.159 11115 11178 I jxcore-log: 
,03-30 14:14:14.159 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-30 14:14:14.159 11115 11178 I jxcore-log: 
,03-30 14:14:14.164 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.164 11115 11178 I jxcore-log: 
,03-30 14:14:14.164 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.164 11115 11178 I jxcore-log: 
,03-30 14:14:14.169 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.169 11115 11178 I jxcore-log: 
,03-30 14:14:14.169 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.169 11115 11178 I jxcore-log: 
,03-30 14:14:14.174 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.174 11115 11178 I jxcore-log: 
,03-30 14:14:14.174 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.174 11115 11178 I jxcore-log: 
,03-30 14:14:14.174 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.174 11115 11178 I jxcore-log: 
,03-30 14:14:14.179 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.179 11115 11178 I jxcore-log: 
,03-30 14:14:14.179 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.179 11115 11178 I jxcore-log: 
,03-30 14:14:14.184 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.184 11115 11178 I jxcore-log: 
,03-30 14:14:14.184 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.184 11115 11178 I jxcore-log: 
,03-30 14:14:14.184 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.184 11115 11178 I jxcore-log: 
,03-30 14:14:14.189 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.189 11115 11178 I jxcore-log: 
,03-30 14:14:14.189 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.189 11115 11178 I jxcore-log: 
,03-30 14:14:14.189 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.189 11115 11178 I jxcore-log: 
,03-30 14:14:14.194 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.194 11115 11178 I jxcore-log: 
,03-30 14:14:14.194 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.194 11115 11178 I jxcore-log: 
,03-30 14:14:14.194 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.194 11115 11178 I jxcore-log: 
,03-30 14:14:14.199 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.199 11115 11178 I jxcore-log: 
,03-30 14:14:14.199 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.199 11115 11178 I jxcore-log: 
,03-30 14:14:14.199 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.199 11115 11178 I jxcore-log: 
,03-30 14:14:14.199 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.199 11115 11178 I jxcore-log: 
,03-30 14:14:14.204 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.204 11115 11178 I jxcore-log: 
,03-30 14:14:14.204 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.204 11115 11178 I jxcore-log: 
,03-30 14:14:14.204 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.204 11115 11178 I jxcore-log: 
,03-30 14:14:14.204 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.204 11115 11178 I jxcore-log: 
,03-30 14:14:14.209 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.209 11115 11178 I jxcore-log: 
,03-30 14:14:14.209 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.209 11115 11178 I jxcore-log: 
,03-30 14:14:14.209 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.209 11115 11178 I jxcore-log: 
,03-30 14:14:14.214 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-30 14:14:14.214 11115 11178 I jxcore-log: 
,03-30 14:14:14.214 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.214 11115 11178 I jxcore-log: 
,03-30 14:14:14.214 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.214 11115 11178 I jxcore-log: 
,03-30 14:14:14.219 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.219 11115 11178 I jxcore-log: 
,03-30 14:14:14.219 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.219 11115 11178 I jxcore-log: 
,03-30 14:14:14.219 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-30 14:14:14.219 11115 11178 I jxcore-log: 
,03-30 14:14:14.229 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.229 11115 11178 I jxcore-log: 
,03-30 14:14:14.229 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.229 11115 11178 I jxcore-log: 
,03-30 14:14:14.229 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.229 11115 11178 I jxcore-log: 
,03-30 14:14:14.234 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.234 11115 11178 I jxcore-log: 
,03-30 14:14:14.234 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.234 11115 11178 I jxcore-log: 
,03-30 14:14:14.234 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.234 11115 11178 I jxcore-log: 
,03-30 14:14:14.239 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.239 11115 11178 I jxcore-log: 
,03-30 14:14:14.239 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.239 11115 11178 I jxcore-log: 
,03-30 14:14:14.239 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.239 11115 11178 I jxcore-log: 
,03-30 14:14:14.244 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.244 11115 11178 I jxcore-log: 
,03-30 14:14:14.244 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.244 11115 11178 I jxcore-log: 
,03-30 14:14:14.244 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.244 11115 11178 I jxcore-log: 
,03-30 14:14:14.244 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.244 11115 11178 I jxcore-log: 
,03-30 14:14:14.249 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.249 11115 11178 I jxcore-log: 
,03-30 14:14:14.249 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.249 11115 11178 I jxcore-log: 
,03-30 14:14:14.249 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.249 11115 11178 I jxcore-log: 
,03-30 14:14:14.254 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.254 11115 11178 I jxcore-log: 
,03-30 14:14:14.254 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.254 11115 11178 I jxcore-log: 
,03-30 14:14:14.254 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.254 11115 11178 I jxcore-log: 
,03-30 14:14:14.254 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.254 11115 11178 I jxcore-log: 
,03-30 14:14:14.259 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.259 11115 11178 I jxcore-log: 
,03-30 14:14:14.259 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.259 11115 11178 I jxcore-log: 
,03-30 14:14:14.259 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.259 11115 11178 I jxcore-log: 
,03-30 14:14:14.264 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.264 11115 11178 I jxcore-log: 
,03-30 14:14:14.264 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.264 11115 11178 I jxcore-log: 
,03-30 14:14:14.264 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.264 11115 11178 I jxcore-log: 
,03-30 14:14:14.264 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.264 11115 11178 I jxcore-log: 
,03-30 14:14:14.269 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.269 11115 11178 I jxcore-log: 
,03-30 14:14:14.269 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.269 11115 11178 I jxcore-log: 
,03-30 14:14:14.269 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.269 11115 11178 I jxcore-log: 
,03-30 14:14:14.269 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.269 11115 11178 I jxcore-log: 
,03-30 14:14:14.274 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.274 11115 11178 I jxcore-log: 
,03-30 14:14:14.284  3481  3861 E Watchdog: !@Sync 7 [03-30 14:14:14.285]
,03-30 14:14:14.334 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.334 11115 11178 I jxcore-log: 
,03-30 14:14:14.334 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.334 11115 11178 I jxcore-log: 
,03-30 14:14:14.339 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.339 11115 11178 I jxcore-log: 
,03-30 14:14:14.339 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.339 11115 11178 I jxcore-log: 
,03-30 14:14:14.339 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.339 11115 11178 I jxcore-log: 
,03-30 14:14:14.339 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.339 11115 11178 I jxcore-log: 
,03-30 14:14:14.339 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.339 11115 11178 I jxcore-log: 
03-30 14:14:14.339 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.339 11115 11178 I jxcore-log: 
,03-30 14:14:14.344 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.344 11115 11178 I jxcore-log: 
,03-30 14:14:14.344 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.344 11115 11178 I jxcore-log: 
,03-30 14:14:14.344 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.344 11115 11178 I jxcore-log: 
,03-30 14:14:14.344 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.344 11115 11178 I jxcore-log: 
,03-30 14:14:14.344 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.344 11115 11178 I jxcore-log: 
03-30 14:14:14.349 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.349 11115 11178 I jxcore-log: 
,03-30 14:14:14.349 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.349 11115 11178 I jxcore-log: 
,03-30 14:14:14.349 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.349 11115 11178 I jxcore-log: 
,03-30 14:14:14.349 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.349 11115 11178 I jxcore-log: 
03-30 14:14:14.349 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.349 11115 11178 I jxcore-log: 
,03-30 14:14:14.349 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.349 11115 11178 I jxcore-log: 
,03-30 14:14:14.349 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.349 11115 11178 I jxcore-log: 
,03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.354 11115 11178 I jxcore-log: 
03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.354 11115 11178 I jxcore-log: 
,03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.354 11115 11178 I jxcore-log: 
03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.354 11115 11178 I jxcore-log: 
,03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.354 11115 11178 I jxcore-log: 
,03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.354 11115 11178 I jxcore-log: 
,03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.354 11115 11178 I jxcore-log: 
03-30 14:14:14.354 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.354 11115 11178 I jxcore-log: 
,03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.359 11115 11178 I jxcore-log: 
,03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.359 11115 11178 I jxcore-log: 
03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.359 11115 11178 I jxcore-log: 
,03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.359 11115 11178 I jxcore-log: 
,03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.359 11115 11178 I jxcore-log: 
03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.359 11115 11178 I jxcore-log: 
,03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.359 11115 11178 I jxcore-log: 
,03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.359 11115 11178 I jxcore-log: 
,03-30 14:14:14.359 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.359 11115 11178 I jxcore-log: 
03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.364 11115 11178 I jxcore-log: 
,03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.364 11115 11178 I jxcore-log: 
,03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.364 11115 11178 I jxcore-log: 
,03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.364 11115 11178 I jxcore-log: 
03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.364 11115 11178 I jxcore-log: 
,03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.364 11115 11178 I jxcore-log: 
,03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.364 11115 11178 I jxcore-log: 
,03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.364 11115 11178 I jxcore-log: 
03-30 14:14:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.364 11115 11178 I jxcore-log: 
,03-30 14:14:14.369 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.369 11115 11178 I jxcore-log: 
,03-30 14:14:14.369 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.369 11115 11178 I jxcore-log: 
03-30 14:14:14.369 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.369 11115 11178 I jxcore-log: 
,03-30 14:14:14.369 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.369 11115 11178 I jxcore-log: 
,03-30 14:14:14.369 11115 11178 I jxcore-log: ok 28 native server is nulled out
03-30 14:14:14.369 11115 11178 I jxcore-log: 
,03-30 14:14:14.369 11115 11178 I jxcore-log: ok 29 native server should be closed
03-30 14:14:14.369 11115 11178 I jxcore-log: 
03-30 14:14:14.374 11115 11178 I jxcore-log: ok 30 incoming has been removed
03-30 14:14:14.374 11115 11178 I jxcore-log: 
,03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
,03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
,03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
,03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
,03-30 14:14:14.374 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.374 11115 11178 I jxcore-log: 
,03-30 14:14:14.464 11115 11178 I jxcore-log: # teardown
03-30 14:14:14.464 11115 11178 I jxcore-log: 
,03-30 14:14:14.489 11115 11178 I jxcore-log: # setup
03-30 14:14:14.489 11115 11178 I jxcore-log: 
,03-30 14:14:14.669 11115 11178 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-30 14:14:14.669 11115 11178 I jxcore-log: 
,03-30 14:14:14.824 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:14.824 11115 11178 I jxcore-log: 
,03-30 14:14:14.834 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 40262
03-30 14:14:14.834 11115 11178 I jxcore-log: 
,03-30 14:14:14.844 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:14.844 11115 11178 I jxcore-log: 
,03-30 14:14:14.844 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:14.844 11115 11178 I jxcore-log: 
,03-30 14:14:14.849 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:14.849 11115 11178 I jxcore-log: 
,03-30 14:14:14.864 11115 11178 I jxcore-log: ok 31 we should not have gotten an error
03-30 14:14:14.864 11115 11178 I jxcore-log: 
,03-30 14:14:14.869 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:14.869 11115 11178 I jxcore-log: 
,03-30 14:14:14.869 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:14.869 11115 11178 I jxcore-log: 
,03-30 14:14:14.879 11115 11178 I jxcore-log: ok 32 Buffers are identical
03-30 14:14:14.879 11115 11178 I jxcore-log: 
,03-30 14:14:14.879 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:14.879 11115 11178 I jxcore-log: 
,03-30 14:14:14.884 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:14.884 11115 11178 I jxcore-log: 
,03-30 14:14:14.899 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:14.899 11115 11178 I jxcore-log: 
,03-30 14:14:14.899 11115 11178 I jxcore-log: ok 33 server should be fine
03-30 14:14:14.899 11115 11178 I jxcore-log: 
,03-30 14:14:14.899 11115 11178 I jxcore-log: ok 34 server should be open
03-30 14:14:14.899 11115 11178 I jxcore-log: 
,03-30 14:14:14.904 11115 11178 I jxcore-log: ok 35 incoming has been removed
03-30 14:14:14.904 11115 11178 I jxcore-log: 
,03-30 14:14:14.904 11115 11178 I jxcore-log: ok 36 The mux object should be closed
03-30 14:14:14.904 11115 11178 I jxcore-log: 
,03-30 14:14:14.904 11115 11178 I jxcore-log: ok 37 The mux stream should be closed
03-30 14:14:14.904 11115 11178 I jxcore-log: 
,03-30 14:14:14.909 11115 11178 I jxcore-log: # teardown
03-30 14:14:14.909 11115 11178 I jxcore-log: 
,03-30 14:14:15.089 11115 11178 I jxcore-log: # setup,
03-30 14:14:15.089 11115 11178 I jxcore-log: 
,03-30 14:14:15.249 11115 11178 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-30 14:14:15.249 11115 11178 I jxcore-log: 
,03-30 14:14:15.399 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:15.399 11115 11178 I jxcore-log: 
,03-30 14:14:15.409 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 33622
03-30 14:14:15.409 11115 11178 I jxcore-log: 
,03-30 14:14:15.424 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:14:15.424 11115 11178 I jxcore-log: 
,03-30 14:14:15.429 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:14:15.429 11115 11178 I jxcore-log: 
,03-30 14:14:15.429 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:14:15.429 11115 11178 I jxcore-log: 
,03-30 14:14:15.444 11115 11178 I jxcore-log: ok 38 we should not have gotten an error
03-30 14:14:15.444 11115 11178 I jxcore-log: 
,03-30 14:14:15.449 11115 11178 I jxcore-log: DEBUG createNativeListener: new stream: 
03-30 14:14:15.449 11115 11178 I jxcore-log: 
,03-30 14:14:15.454 11115 11178 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-30 14:14:15.454 11115 11178 I jxcore-log: 
,03-30 14:14:15.464 11115 11178 I jxcore-log: ok 39 Buffers are identical
03-30 14:14:15.464 11115 11178 I jxcore-log: 
,03-30 14:14:15.469 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-30 14:14:15.469 11115 11178 I jxcore-log: 
,03-30 14:14:15.469 11115 11178 I jxcore-log: DEBUG createNativeListener: stream close:
03-30 14:14:15.469 11115 11178 I jxcore-log: 
,03-30 14:14:15.474 11115 11178 I jxcore-log: DEBUG createNativeListener: mux close
03-30 14:14:15.474 11115 11178 I jxcore-log: 
,03-30 14:14:15.479 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:14:15.479 11115 11178 I jxcore-log: 
,03-30 14:14:15.484 11115 11178 I jxcore-log: ok 40 server should be fine
03-30 14:14:15.484 11115 11178 I jxcore-log: 
,03-30 14:14:15.484 11115 11178 I jxcore-log: ok 41 server should be open
03-30 14:14:15.484 11115 11178 I jxcore-log: 
,03-30 14:14:15.484 11115 11178 I jxcore-log: ok 42 incoming has been removed
03-30 14:14:15.484 11115 11178 I jxcore-log: 
,03-30 14:14:15.489 11115 11178 I jxcore-log: ok 43 The mux object should be closed
03-30 14:14:15.489 11115 11178 I jxcore-log: 
,03-30 14:14:15.489 11115 11178 I jxcore-log: ok 44 The mux stream should be closed
03-30 14:14:15.489 11115 11178 I jxcore-log: 
,03-30 14:14:15.499 11115 11178 I jxcore-log: # teardown
03-30 14:14:15.499 11115 11178 I jxcore-log: 
,03-30 14:14:15.574 11115 11178 I jxcore-log: # setup
03-30 14:14:15.574 11115 11178 I jxcore-log: 
,03-30 14:14:15.704 11115 11178 I jxcore-log: # 12. closeAll can close even when connections open
03-30 14:14:15.704 11115 11178 I jxcore-log: 
,03-30 14:14:15.889 11115 11178 I jxcore-log: ok 45 not possible to connect to the server anymore
03-30 14:14:15.889 11115 11178 I jxcore-log: 
,03-30 14:14:15.899 11115 11178 I jxcore-log: # teardown
03-30 14:14:15.899 11115 11178 I jxcore-log: 
,03-30 14:14:16.009 11115 11178 I jxcore-log: # setup
03-30 14:14:16.009 11115 11178 I jxcore-log: 
,03-30 14:14:16.154 11115 11178 I jxcore-log: # 13. closeAll with promise
03-30 14:14:16.154 11115 11178 I jxcore-log: 
,03-30 14:14:16.284 11115 11178 I jxcore-log: ok 46 not possible to connect to the server anymore
03-30 14:14:16.284 11115 11178 I jxcore-log: 
,03-30 14:14:16.294 11115 11178 I jxcore-log: # teardown
03-30 14:14:16.294 11115 11178 I jxcore-log: 
,03-30 14:14:16.439 11115 11178 I jxcore-log: # setup
03-30 14:14:16.439 11115 11178 I jxcore-log: 
,03-30 14:14:16.619 11115 11178 I jxcore-log: # 14. closeAll properly throws when closing a non open server with eatNotRunning set to false
03-30 14:14:16.619 11115 11178 I jxcore-log: 
,03-30 14:14:16.784 11115 11178 I jxcore-log: ok 47 Got the right error
03-30 14:14:16.784 11115 11178 I jxcore-log: 
,03-30 14:14:16.789 11115 11178 I jxcore-log: # teardown
03-30 14:14:16.789 11115 11178 I jxcore-log: 
,03-30 14:14:16.949 11115 11178 I jxcore-log: # setup
03-30 14:14:16.949 11115 11178 I jxcore-log: 
,03-30 14:14:17.089 11115 11178 I jxcore-log: # 15. closeAll works even with a server that is not listening yet witheatNotRunning set to true
03-30 14:14:17.089 11115 11178 I jxcore-log: 
,03-30 14:14:17.204  3481  3730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-30 14:14:17.204  3481  3730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-30 14:14:17.204  3481  3730 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
03-30 14:14:17.204  3481  3730 D BatteryService: stay LED for fully charged
03-30 14:14:17.204  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:14:17.209  3481  3481 I MotionRecognitionService: Plugged
03-30 14:14:17.209  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-30 14:14:17.209  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-30 14:14:17.209  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-30 14:14:17.214  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:17.214  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:14:17.214  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-30 14:14:17.219  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-30 14:14:17.219  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
,03-30 14:14:17.224 11115 11178 I jxcore-log: # teardown
03-30 14:14:17.224 11115 11178 I jxcore-log: 
,03-30 14:14:17.234  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:17.234  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:17.234  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:17.234  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:17.474 11115 11178 I jxcore-log: # setup
03-30 14:14:17.474 11115 11178 I jxcore-log: 
,03-30 14:14:17.574 11115 11178 I jxcore-log: # 16. multiplex can send data
03-30 14:14:17.574 11115 11178 I jxcore-log: 
,03-30 14:14:17.739 11115 11178 I jxcore-log: ok 48 String should be length:200
03-30 14:14:17.739 11115 11178 I jxcore-log: 
,03-30 14:14:17.749 11115 11178 I jxcore-log: # teardown
03-30 14:14:17.749 11115 11178 I jxcore-log: 
,03-30 14:14:17.904 11115 11178 I jxcore-log: # setup
03-30 14:14:17.904 11115 11178 I jxcore-log: 
,03-30 14:14:18.029 11115 11178 I jxcore-log: # 17. enqueue and run in order
03-30 14:14:18.029 11115 11178 I jxcore-log: 
,03-30 14:14:18.139  3481  6076 D SSRM:n  : SIOP:: AP = 290, PST = 282 (W:10), CUR = 10, LCD = 0
,03-30 14:14:18.244 11115 11178 I jxcore-log: ok 49 firstPromise setTimeout
03-30 14:14:18.244 11115 11178 I jxcore-log: 
,03-30 14:14:18.254 11115 11178 I jxcore-log: ok 50 firstPromise result
03-30 14:14:18.254 11115 11178 I jxcore-log: 
,03-30 14:14:18.259 11115 11178 I jxcore-log: ok 51 firstPromise testValue
03-30 14:14:18.259 11115 11178 I jxcore-log: 
,03-30 14:14:18.369 11115 11178 I jxcore-log: ok 52 secondPromise setTimeout
03-30 14:14:18.369 11115 11178 I jxcore-log: 
,03-30 14:14:18.379 11115 11178 I jxcore-log: ok 53 secondPromise result
03-30 14:14:18.379 11115 11178 I jxcore-log: 
,03-30 14:14:18.384 11115 11178 I jxcore-log: ok 54 secondPromise testValue
03-30 14:14:18.384 11115 11178 I jxcore-log: 
,03-30 14:14:18.389 11115 11178 I jxcore-log: ok 55 thirdPromise in promise
03-30 14:14:18.389 11115 11178 I jxcore-log: 
,03-30 14:14:18.394 11115 11178 I jxcore-log: ok 56 thirdPromise result
03-30 14:14:18.394 11115 11178 I jxcore-log: 
,03-30 14:14:18.394 11115 11178 I jxcore-log: ok 57 thirdPromise testValue
03-30 14:14:18.394 11115 11178 I jxcore-log: 
,03-30 14:14:18.404 11115 11178 I jxcore-log: # teardown
03-30 14:14:18.404 11115 11178 I jxcore-log: 
,03-30 14:14:18.749 11115 11178 I jxcore-log: # setup
03-30 14:14:18.749 11115 11178 I jxcore-log: 
,03-30 14:14:18.849 11115 11178 I jxcore-log: # 18. enqueueAtTop and run backwards
03-30 14:14:18.849 11115 11178 I jxcore-log: 
,03-30 14:14:19.389 11115 11178 I jxcore-log: ok 58 thirdPromise - first to run
03-30 14:14:19.389 11115 11178 I jxcore-log: 
,03-30 14:14:19.394 11115 11178 I jxcore-log: ok 59 thirdPromise - in resolve
03-30 14:14:19.394 11115 11178 I jxcore-log: 
,03-30 14:14:19.399 11115 11178 I jxcore-log: ok 60 secondPromise - second to run
03-30 14:14:19.399 11115 11178 I jxcore-log: 
,03-30 14:14:19.399 11115 11178 I jxcore-log: ok 61 secondPromise - in catch
03-30 14:14:19.399 11115 11178 I jxcore-log: 
,03-30 14:14:19.404 11115 11178 I jxcore-log: ok 62 firstPromise - third to run
03-30 14:14:19.404 11115 11178 I jxcore-log: 
,03-30 14:14:19.409 11115 11178 I jxcore-log: ok 63 firstPromise - in then
03-30 14:14:19.409 11115 11178 I jxcore-log: 
,03-30 14:14:19.409 11115 11178 I jxcore-log: ok 64 testing promises
03-30 14:14:19.409 11115 11178 I jxcore-log: 
,03-30 14:14:19.414 11115 11178 I jxcore-log: # teardown
03-30 14:14:19.414 11115 11178 I jxcore-log: 
,03-30 14:14:19.569 11115 11178 I jxcore-log: # setup
03-30 14:14:19.569 11115 11178 I jxcore-log: 
,03-30 14:14:19.664 11115 11178 I jxcore-log: # 19. mix enqueue and enqueueAtTop
03-30 14:14:19.664 11115 11178 I jxcore-log: 
,03-30 14:14:19.809 11115 11178 I jxcore-log: ok 65 fourth
03-30 14:14:19.809 11115 11178 I jxcore-log: 
,03-30 14:14:19.809 11115 11178 I jxcore-log: ok 66 fourth
03-30 14:14:19.809 11115 11178 I jxcore-log: 
,03-30 14:14:19.814 11115 11178 I jxcore-log: ok 67 second
03-30 14:14:19.814 11115 11178 I jxcore-log: 
,03-30 14:14:19.819 11115 11178 I jxcore-log: ok 68 secondPromise - in then
03-30 14:14:19.819 11115 11178 I jxcore-log: 
,03-30 14:14:19.924 11115 11178 I jxcore-log: ok 69 first,
03-30 14:14:19.924 11115 11178 I jxcore-log: 
,03-30 14:14:19.939 11115 11178 I jxcore-log: ok 70 firstPromise - in catch
03-30 14:14:19.939 11115 11178 I jxcore-log: 
,03-30 14:14:19.944 11115 11178 I jxcore-log: ok 71 third
03-30 14:14:19.944 11115 11178 I jxcore-log: 
,03-30 14:14:19.949 11115 11178 I jxcore-log: ok 72 thirdPromise - in then
03-30 14:14:19.949 11115 11178 I jxcore-log: 
,03-30 14:14:19.949 11115 11178 I jxcore-log: ok 73 testingPromises
03-30 14:14:19.949 11115 11178 I jxcore-log: 
,03-30 14:14:19.959 11115 11178 I jxcore-log: # teardown
03-30 14:14:19.959 11115 11178 I jxcore-log: 
,03-30 14:14:20.109 11115 11178 I jxcore-log: # setup
03-30 14:14:20.109 11115 11178 I jxcore-log: 
,03-30 14:14:20.274 11115 11178 I jxcore-log: # 20. queues handled independently
03-30 14:14:20.274 11115 11178 I jxcore-log: 
,03-30 14:14:20.539 11115 11178 I jxcore-log: ok 74 all short operations completed before the long resolves
03-30 14:14:20.539 11115 11178 I jxcore-log: 
,03-30 14:14:20.549 11115 11178 I jxcore-log: # teardown
03-30 14:14:20.549 11115 11178 I jxcore-log: 
,03-30 14:14:20.604 11115 11178 I jxcore-log: # setup
03-30 14:14:20.604 11115 11178 I jxcore-log: 
,03-30 14:14:20.834 11115 11178 I jxcore-log: # 21. basic
03-30 14:14:20.834 11115 11178 I jxcore-log: 
,03-30 14:14:21.029 11115 11178 I jxcore-log: ok 75 sane
03-30 14:14:21.029 11115 11178 I jxcore-log: 
,03-30 14:14:21.034 11115 11178 I jxcore-log: # teardown
03-30 14:14:21.034 11115 11178 I jxcore-log: 
,03-30 14:14:21.214 11115 11178 I jxcore-log: # setup
03-30 14:14:21.214 11115 11178 I jxcore-log: 
,03-30 14:14:21.394 11115 11178 I jxcore-log: # 22. another
03-30 14:14:21.394 11115 11178 I jxcore-log: 
,03-30 14:14:21.499  3481  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-30 14:14:21.554 11115 11178 I jxcore-log: ok 76 sane
03-30 14:14:21.554 11115 11178 I jxcore-log: 
,03-30 14:14:21.559 11115 11178 I jxcore-log: # teardown
03-30 14:14:21.559 11115 11178 I jxcore-log: 
,03-30 14:14:21.664 11115 11178 I jxcore-log: # setup
03-30 14:14:21.664 11115 11178 I jxcore-log: 
,03-30 14:14:21.794 11115 11178 I jxcore-log: # 23. can pass data in setup
03-30 14:14:21.794 11115 11178 I jxcore-log: 
,03-30 14:14:21.969 11115 11178 I jxcore-log: ok 77 test participant has uuid
03-30 14:14:21.969 11115 11178 I jxcore-log: 
,03-30 14:14:21.974 11115 11178 I jxcore-log: ok 78 participant data matches
03-30 14:14:21.974 11115 11178 I jxcore-log: 
,03-30 14:14:21.974 11115 11178 I jxcore-log: ok 79 test participant has uuid
03-30 14:14:21.974 11115 11178 I jxcore-log: 
,03-30 14:14:21.974 11115 11178 I jxcore-log: ok 80 participant data matches
03-30 14:14:21.974 11115 11178 I jxcore-log: 
,03-30 14:14:21.979 11115 11178 I jxcore-log: ok 81 test participant has uuid
03-30 14:14:21.979 11115 11178 I jxcore-log: 
,03-30 14:14:21.979 11115 11178 I jxcore-log: ok 82 participant data matches
03-30 14:14:21.979 11115 11178 I jxcore-log: 
,03-30 14:14:21.994 11115 11178 I jxcore-log: not ok 83 test participant has uuid
03-30 14:14:21.994 11115 11178 I jxcore-log: 
,03-30 14:14:21.994 11115 11178 I jxcore-log:   ---
03-30 14:14:21.994 11115 11178 I jxcore-log: 
,03-30 14:14:21.994 11115 11178 I jxcore-log:     operator: ok
03-30 14:14:21.994 11115 11178 I jxcore-log: 
,03-30 14:14:21.994 11115 11178 I jxcore-log:     expected: true
03-30 14:14:21.994 11115 11178 I jxcore-log: 
,03-30 14:14:21.994 11115 11178 I jxcore-log:     actual:   undefined
03-30 14:14:21.994 11115 11178 I jxcore-log: 
,03-30 14:14:21.994 11115 11178 I jxcore-log:   ...
03-30 14:14:21.994 11115 11178 I jxcore-log: 
,03-30 14:14:21.999 11115 11178 I jxcore-log: ok 84 participant data matches
03-30 14:14:21.999 11115 11178 I jxcore-log: 
,03-30 14:14:21.999 11115 11178 I jxcore-log: ok 85 own UUID is found from the participants list
03-30 14:14:21.999 11115 11178 I jxcore-log: 
,03-30 14:14:22.004 11115 11178 I jxcore-log: # teardown
03-30 14:14:22.004 11115 11178 I jxcore-log: 
,03-30 14:14:22.354 11115 11178 I jxcore-log: # setup
03-30 14:14:22.354 11115 11178 I jxcore-log: 
,03-30 14:14:22.559 11115 11178 I jxcore-log: # 24. #startListeningForAdvertisements should fail if start not called
03-30 14:14:22.559 11115 11178 I jxcore-log: 
,03-30 14:14:22.734 11115 11178 I jxcore-log: ok 86 specific error should be returned
03-30 14:14:22.734 11115 11178 I jxcore-log: 
,03-30 14:14:22.739 11115 11178 I jxcore-log: # teardown
03-30 14:14:22.739 11115 11178 I jxcore-log: 
,03-30 14:14:22.879 11115 11178 I jxcore-log: ok 87 error should be null
03-30 14:14:22.879 11115 11178 I jxcore-log: 
,03-30 14:14:22.884 11115 11178 I jxcore-log: ok 88 error should be null
03-30 14:14:22.884 11115 11178 I jxcore-log: 
,03-30 14:14:22.889 11115 11178 I jxcore-log: # setup
03-30 14:14:22.889 11115 11178 I jxcore-log: 
,03-30 14:14:23.014 11115 11178 I jxcore-log: # 25. #startUpdateAdvertisingAndListening should fail if start not called
03-30 14:14:23.014 11115 11178 I jxcore-log: 
,03-30 14:14:23.234 11115 11178 I jxcore-log: ok 89 specific error should be returned
03-30 14:14:23.234 11115 11178 I jxcore-log: 
,03-30 14:14:23.239 11115 11178 I jxcore-log: # teardown
03-30 14:14:23.239 11115 11178 I jxcore-log: 
,03-30 14:14:23.359 11115 11178 I jxcore-log: ok 90 error should be null
03-30 14:14:23.359 11115 11178 I jxcore-log: 
,03-30 14:14:23.364 11115 11178 I jxcore-log: ok 91 error should be null
03-30 14:14:23.364 11115 11178 I jxcore-log: 
,03-30 14:14:23.369 11115 11178 I jxcore-log: # setup
03-30 14:14:23.369 11115 11178 I jxcore-log: 
,03-30 14:14:23.534 11115 11178 I jxcore-log: # 26. should be able to call #stopListeningForAdvertisements many times
03-30 14:14:23.534 11115 11178 I jxcore-log: 
,03-30 14:14:23.859 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:23.859 11115 11178 I jxcore-log: 
,03-30 14:14:23.859 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 51471
03-30 14:14:23.859 11115 11178 I jxcore-log: 
,03-30 14:14:23.869 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:23.869 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:23.869 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:23.874 11115 11178 I jxcore-log: ok 92 error should be null
03-30 14:14:23.874 11115 11178 I jxcore-log: 
,03-30 14:14:23.874 11115 11178 I jxcore-log: ok 93 error should be null
03-30 14:14:23.874 11115 11178 I jxcore-log: 
,03-30 14:14:23.879 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:23.879 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:23.879 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:23.884 11115 11178 I jxcore-log: ok 94 error should be null
03-30 14:14:23.884 11115 11178 I jxcore-log: 
,03-30 14:14:23.884 11115 11178 I jxcore-log: ok 95 error should be null
03-30 14:14:23.884 11115 11178 I jxcore-log: 
,03-30 14:14:23.889 11115 11178 I jxcore-log: # teardown
03-30 14:14:23.889 11115 11178 I jxcore-log: 
,03-30 14:14:24.019 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:24.019 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:24.024 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:24.029 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:24.029 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:14:24.029 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:24.039 11115 11178 I jxcore-log: ok 96 error should be null
03-30 14:14:24.039 11115 11178 I jxcore-log: 
,03-30 14:14:24.039 11115 11178 I jxcore-log: ok 97 error should be null
03-30 14:14:24.039 11115 11178 I jxcore-log: 
,03-30 14:14:24.049 11115 11178 I jxcore-log: # setup
03-30 14:14:24.049 11115 11178 I jxcore-log: 
,03-30 14:14:24.124 11115 11178 I jxcore-log: # 27. should be able to call #startListeningForAdvertisements many times
03-30 14:14:24.124 11115 11178 I jxcore-log: 
,03-30 14:14:24.329 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:24.329 11115 11178 I jxcore-log: 
,03-30 14:14:24.334 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 37355
03-30 14:14:24.334 11115 11178 I jxcore-log: 
,03-30 14:14:24.344 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-30 14:14:24.344 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:24.344 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:14:24.349 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:14:24.349 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:24.349 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:24.354 11115 11178 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:24.364 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:24.374 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:24.374 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:24.374 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:14:24.374 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:24.379  5869  5880 D BtGatt.GattService: registerClient() - UUID=2168a60e-1f9f-453d-aa69-2c21d02110cc
,03-30 14:14:24.424  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=2168a60e-1f9f-453d-aa69-2c21d02110cc, clientIf=6
,03-30 14:14:24.424 11115 11171 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:24.429  5869  5883 D BtGatt.GattService: start scan with filters
,03-30 14:14:24.444  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 128
,03-30 14:14:24.449  5869  5883 D BtGatt.GattService: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 128
,03-30 14:14:24.459  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5cb9e2e u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY} DELIVERED for app ProcessRecord{36025fd3 5080:com.samsung.android.providers.context/u0a3}
,03-30 14:14:24.464  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:24.464  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:24.464  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:14:24.469 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-30 14:14:24.469 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-30 14:14:24.469 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:24.469  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:24.469 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-30 14:14:24.469  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:24.469 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:24.469 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:24.469 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:24.469  5869  5957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d51742,
,03-30 14:14:24.474 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:24.474 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:24.479 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:24.479 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:24.479 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:24.479 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:24.484  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-30 14:14:24.484  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:24.484  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:24.484  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-30 14:14:24.484  5869  5957 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-30 14:14:24.484  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-30 14:14:24.484  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:24.489  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:24.489  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:24.489  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-30 14:14:24.489  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:24.489 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:24.489 11115 11178 I jxcore-log: 
03-30 14:14:24.489  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:24.489  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:24.494 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:24.494 11115 11178 I jxcore-log: 
,03-30 14:14:24.494 11115 11178 I jxcore-log: ok 98 error should be null,
03-30 14:14:24.494 11115 11178 I jxcore-log: 
,03-30 14:14:24.494 11115 11178 I jxcore-log: ok 99 error should be null,
03-30 14:14:24.494 11115 11178 I jxcore-log: 
,03-30 14:14:24.499 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false,
03-30 14:14:24.499 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:24.499 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-30 14:14:24.499 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:24.499 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:24.504 11115 11178 I jxcore-log: ok 100 error should be null,
03-30 14:14:24.504 11115 11178 I jxcore-log: 
03-30 14:14:24.504 11115 11178 I jxcore-log: ok 101 error should be null
03-30 14:14:24.504 11115 11178 I jxcore-log: 
,03-30 14:14:24.509 11115 11178 I jxcore-log: # teardown
03-30 14:14:24.509 11115 11178 I jxcore-log: 
,03-30 14:14:24.664 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:24.664 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:24.664 11115 11178 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:14:24.664 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:24.664 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:24.664 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:14:24.664 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:24.669 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:24.669 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:24.669  5869  5883 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:24.669  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:24.669  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 3
03-30 14:14:24.669  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:14:24.674  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-30 14:14:24.674  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:24.674 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:24.674  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:24.674 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:24.674 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:24.674 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:14:24.674 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:14:24.674 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:24.674 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:24.674 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:24.674 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:24.674 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:14:24.679 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:24.679 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:24.679 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:24.679 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:24.679  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:24.679  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:24.679  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:24.679  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-30 14:14:24.679  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:24.684 11115 11178 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
03-30 14:14:24.684 11115 11178 I jxcore-log: 
03-30 14:14:24.684 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:24.694 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:24.694 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:24.694 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:24.694 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:24.694 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:24.694 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:24.694 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:24.699 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:24.699 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:24.699 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:24.699 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:24.699 11115 11178 I jxcore-log: 
,03-30 14:14:24.704 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:24.704 11115 11178 I jxcore-log: 
,03-30 14:14:24.709 11115 11178 I jxcore-log: ok 102 error should be null
03-30 14:14:24.709 11115 11178 I jxcore-log: 
,03-30 14:14:24.709 11115 11178 I jxcore-log: ok 103 error should be null
03-30 14:14:24.709 11115 11178 I jxcore-log: 
,03-30 14:14:24.724 11115 11178 I jxcore-log: # setup
03-30 14:14:24.724 11115 11178 I jxcore-log: 
,03-30 14:14:24.929 11115 11178 I jxcore-log: # 28. should be able to call #startUpdateAdvertisingAndListening many times
03-30 14:14:24.929 11115 11178 I jxcore-log: 
,03-30 14:14:25.099 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:25.099 11115 11178 I jxcore-log: 
,03-30 14:14:25.099 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 57838
03-30 14:14:25.099 11115 11178 I jxcore-log: 
,03-30 14:14:25.119 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 57838, start advertisements: true
,03-30 14:14:25.119 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:25.119 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:25.119 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:25.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:25.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:25.124 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:14:25.124 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:25.134  5869  5880 D BtGatt.GattService: registerClient() - UUID=d81b7d58-b722-43b4-a2e3-e24300b7710f
,03-30 14:14:25.174  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=d81b7d58-b722-43b4-a2e3-e24300b7710f, clientIf=6
,03-30 14:14:25.174 11115 11171 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:25.174  5869  5883 D BtGatt.GattService: start scan with filters
,03-30 14:14:25.189  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 1
,03-30 14:14:25.189 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:25.189 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:25.189 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:25.189  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:25.189  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:25.189 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:25.189  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:25.189 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:25.189 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:25.189 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:25.189 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:25.189 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:25.189 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:25.189 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:25.189 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:25.189  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:25.189  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:25.189  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:25.189  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:25.189  5869  5957 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-30 14:14:25.194  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:25.194  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:25.194  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:25.194  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:25.194  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:25.194  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:25.199  5869  5956 D BtGatt.GattService: registerClient() - UUID=05d7fdcb-f741-4f57-9a36-51f584a64523
03-30 14:14:25.199  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:25.199  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:25.239  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=05d7fdcb-f741-4f57-9a36-51f584a64523, clientIf=7
03-30 14:14:25.239 11115 11125 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:25.264  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 107
,03-30 14:14:25.279  5869  5880 D BtGatt.GattService: Write on CV = 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 107
,03-30 14:14:25.294  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{289a37eb u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY} DELIVERED for app ProcessRecord{36025fd3 5080:com.samsung.android.providers.context/u0a3}
,03-30 14:14:25.299  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:25.304  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:25.304  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:25.304  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:25.309  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:25.314  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:25.319  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
03-30 14:14:25.319  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:25.319  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:25.319  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-30 14:14:25.319 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:25.324 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:14:25.324 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:25.324 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:14:25.329 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 14:14:25.329 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:25.329 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-30 14:14:25.329 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 14:14:25.334 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-30 14:14:25.334 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 14:14:25.334 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:25.334 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:25.334 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:25.334 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:25.334 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:25.334 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:25.334 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:25.334 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:25.334 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:25.334 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:25.334 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:25.334 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:25.334 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:25.349 11115 11428 D BluetoothSocket: bindListen(): myUserId = 0
03-30 14:14:25.349 11115 11428 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:25.354 11115 11428 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
03-30 14:14:25.354 11115 11428 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:14:25.354 11115 11428 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-30 14:14:25.354 11115 11428 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1884ac3c
03-30 14:14:25.354 11115 11428 D BluetoothSocket: channel: 6
03-30 14:14:25.354 11115 11428 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:25.359 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:25.359 11115 11178 I jxcore-log: 
,03-30 14:14:25.359 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:25.359 11115 11178 I jxcore-log: 
,03-30 14:14:25.364 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:25.364 11115 11178 I jxcore-log: 
,03-30 14:14:25.364 11115 11178 I jxcore-log: ok 104 error should be null
03-30 14:14:25.364 11115 11178 I jxcore-log: 
,03-30 14:14:25.364 11115 11178 I jxcore-log: ok 105 error should be null
03-30 14:14:25.364 11115 11178 I jxcore-log: 
,03-30 14:14:25.374 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 57838, start advertisements: true
,03-30 14:14:25.374 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:25.374 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:25.374 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:25.374 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:25.384 11115 11178 I jxcore-log: ok 106 error should be null
03-30 14:14:25.384 11115 11178 I jxcore-log: 
,03-30 14:14:25.384 11115 11178 I jxcore-log: ok 107 error should be null
03-30 14:14:25.384 11115 11178 I jxcore-log: 
,03-30 14:14:25.394 11115 11178 I jxcore-log: # teardown
03-30 14:14:25.394 11115 11178 I jxcore-log: 
,03-30 14:14:25.544 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:25.544 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:25.544 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:25.544 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:25.544 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 14:14:25.544 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f5fcdc5, channel: 6, state: LISTENING
,03-30 14:14:25.549 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f5fcdc5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1884ac3c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27dad31amSocket: android.net.LocalSocket@499fe4b impl:android.net.LocalSocketImpl@1a0e5028 fd:FileDescriptor[117]
,03-30 14:14:25.549 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@499fe4b impl:android.net.LocalSocketImpl@1a0e5028 fd:FileDescriptor[117]
03-30 14:14:25.549 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:14:25.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:25.549 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:25.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:14:25.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:25.549 11115 11428 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:25.549 11115 11428 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:25.549 11115 11428 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:25.549 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:14:25.549 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:25.554  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:25.554  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:25.554  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 4
,03-30 14:14:25.554  5869  5883 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:14:25.559 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:25.559 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:25.559 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:25.559 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:25.559 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:25.559 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-30 14:14:25.559 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-30 14:14:25.559  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:25.559  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:25.559  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:25.559  5869  5954 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:25.559  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:25.559  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:14:25.564  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:14:25.564  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-30 14:14:25.564  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:25.564  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:25.564  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-30 14:14:25.564  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:14:25.564  5869  5883 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:14:25.569 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:25.569 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:25.569 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:14:25.569 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:25.569 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-30 14:14:25.569 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:25.569 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:25.569 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:14:25.569 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:25.569 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:25.569 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:25.569 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:25.569 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:25.574  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-30 14:14:25.574  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:25.574  5869  5942 D BtGatt.GattService: current time is 233892524776
03-30 14:14:25.574  5869  5942 D BtGatt.GattService: Batch record : [53, 49, 68, -62, 11, 79, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -58, 122, -80, -128, 112, 87, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-30 14:14:25.579 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-30 14:14:25.579  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:25.579  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:25.579  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:25.579  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:14:25.584 11115 11178 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:25.584 11115 11178 I jxcore-log: 
,03-30 14:14:25.589 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:25.589 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:25.589 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:25.594 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:14:25.594 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:25.594 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:25.594 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:25.594 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:25.594 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:25.594 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:25.594 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:14:25.594 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:25.594 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:25.594 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:25.599 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:25.599 11115 11178 I jxcore-log: 
,03-30 14:14:25.599 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:25.599 11115 11178 I jxcore-log: 
,03-30 14:14:25.599 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:25.599 11115 11178 I jxcore-log: 
,03-30 14:14:25.604 11115 11178 I jxcore-log: ok 108 error should be null
03-30 14:14:25.604 11115 11178 I jxcore-log: 
,03-30 14:14:25.609 11115 11178 I jxcore-log: ok 109 error should be null
03-30 14:14:25.609 11115 11178 I jxcore-log: 
,03-30 14:14:25.614 11115 11178 I jxcore-log: # setup
03-30 14:14:25.614 11115 11178 I jxcore-log: 
,03-30 14:14:25.759 11115 11178 I jxcore-log: # 29. should be able to call #stopAdvertisingAndListening many times
03-30 14:14:25.759 11115 11178 I jxcore-log: 
,03-30 14:14:25.934 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:25.934 11115 11178 I jxcore-log: 
,03-30 14:14:25.939 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 44581
03-30 14:14:25.939 11115 11178 I jxcore-log: 
,03-30 14:14:25.944 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:25.944 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:25.944 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:25.949 11115 11178 I jxcore-log: ok 110 error should be null
03-30 14:14:25.949 11115 11178 I jxcore-log: 
,03-30 14:14:25.954 11115 11178 I jxcore-log: ok 111 error should be null
03-30 14:14:25.954 11115 11178 I jxcore-log: 
,03-30 14:14:25.954 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:25.959 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:25.959 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:25.959 11115 11178 I jxcore-log: ok 112 error should be null
03-30 14:14:25.959 11115 11178 I jxcore-log: 
,03-30 14:14:25.964 11115 11178 I jxcore-log: ok 113 error should be null
03-30 14:14:25.964 11115 11178 I jxcore-log: 
,03-30 14:14:25.969 11115 11178 I jxcore-log: # teardown
03-30 14:14:25.969 11115 11178 I jxcore-log: 
,03-30 14:14:26.034 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:26.034 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:26.034 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:26.039 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:26.039 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:26.039 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:26.044 11115 11178 I jxcore-log: ok 114 error should be null
03-30 14:14:26.044 11115 11178 I jxcore-log: 
,03-30 14:14:26.044 11115 11178 I jxcore-log: ok 115 error should be null
03-30 14:14:26.044 11115 11178 I jxcore-log: 
,03-30 14:14:26.049 11115 11178 I jxcore-log: # setup
03-30 14:14:26.049 11115 11178 I jxcore-log: 
,03-30 14:14:26.169 11115 11178 I jxcore-log: # 30. #start should fail if called twice in a row
03-30 14:14:26.169 11115 11178 I jxcore-log: 
,03-30 14:14:26.334 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:26.334 11115 11178 I jxcore-log: 
,03-30 14:14:26.339 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 58854
03-30 14:14:26.339 11115 11178 I jxcore-log: 
,03-30 14:14:26.349 11115 11178 I jxcore-log: ok 116 first call should succeed
03-30 14:14:26.349 11115 11178 I jxcore-log: 
,03-30 14:14:26.349 11115 11178 I jxcore-log: ok 117 first call should succeed
03-30 14:14:26.349 11115 11178 I jxcore-log: 
,03-30 14:14:26.354 11115 11178 I jxcore-log: ok 118 specific error should be returned
03-30 14:14:26.354 11115 11178 I jxcore-log: 
,03-30 14:14:26.364 11115 11178 I jxcore-log: # teardown
03-30 14:14:26.364 11115 11178 I jxcore-log: 
,03-30 14:14:26.629 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:26.629 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:26.629 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:26.634 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:26.639 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:14:26.639 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:26.644 11115 11178 I jxcore-log: ok 119 error should be null
03-30 14:14:26.644 11115 11178 I jxcore-log: 
,03-30 14:14:26.649 11115 11178 I jxcore-log: ok 120 error should be null
03-30 14:14:26.649 11115 11178 I jxcore-log: 
,03-30 14:14:26.654 11115 11178 I jxcore-log: # setup
03-30 14:14:26.654 11115 11178 I jxcore-log: 
,03-30 14:14:27.344  3481  4679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-30 14:14:27.344  3481  4679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-30 14:14:27.344  3481  4679 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,03-30 14:14:27.349  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:14:27.354  3481  3481 I MotionRecognitionService: Plugged
03-30 14:14:27.354  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-30 14:14:27.354  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-30 14:14:27.354  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-30 14:14:27.359  3481  4679 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-30 14:14:27.359  3481  4679 D BatteryService: stay LED for fully charged
,03-30 14:14:27.369  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-30 14:14:27.369  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:27.369  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-30 14:14:27.384  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-30 14:14:27.384  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
,03-30 14:14:27.399  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:27.399  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:27.399  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:27.399  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:28.084 11115 11178 I jxcore-log: # 31. does not emit duplicate discoveryAdvertisingStateUpdate
03-30 14:14:28.084 11115 11178 I jxcore-log: 
,03-30 14:14:28.164  3481  6076 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:10), CUR = 32, LCD = 0
,03-30 14:14:28.339 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:14:28.339 11115 11178 I jxcore-log: 
,03-30 14:14:28.344 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 34975
03-30 14:14:28.344 11115 11178 I jxcore-log: 
,03-30 14:14:28.354 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 57838, start advertisements: false
03-30 14:14:28.354 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:28.354 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:28.354 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:14:28.359 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:28.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:28.359 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:28.364  5869  5956 D BtGatt.GattService: registerClient() - UUID=c46e62d6-d910-46ad-a68d-2f6d9346e39b
,03-30 14:14:28.404  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=c46e62d6-d910-46ad-a68d-2f6d9346e39b, clientIf=6
,03-30 14:14:28.404 11115 11127 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:28.404  5869  5880 D BtGatt.GattService: start scan with filters
,03-30 14:14:28.414  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 2,
03-30 14:14:28.414 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:28.414 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:28.414 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 14:14:28.414 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:28.414 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:28.414 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:28.414 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:28.414  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:28.414  5869  5957 D BtGatt.ScanManager: isFilteringSupported
,03-30 14:14:28.414  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:14:28.419 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 14:14:28.419 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:28.419 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:28.419 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:28.419 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:28.419 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:28.419  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-30 14:14:28.419  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:28.419  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:28.419  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:28.419  5869  5957 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-30 14:14:28.424  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-30 14:14:28.424  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:28.424  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:28.424  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:28.424 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:28.424 11115 11178 I jxcore-log: 
,03-30 14:14:28.429  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-30 14:14:28.429  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:28.429 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:28.429 11115 11178 I jxcore-log: 
,03-30 14:14:28.429  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:28.429  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:28.444 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 34975, start advertisements: true
,03-30 14:14:28.444 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:28.449 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:28.449 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:28.449 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:28.449 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-30 14:14:28.449 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:28.449 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:28.449 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-30 14:14:28.449 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:28.449 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:28.449 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:28.454  5869  5880 D BtGatt.GattService: registerClient() - UUID=5aaaca04-8499-42bf-8468-448e9e4fd3d9
,03-30 14:14:28.494  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=5aaaca04-8499-42bf-8468-448e9e4fd3d9, clientIf=7
,03-30 14:14:28.499 11115 11171 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:28.529  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 1
,03-30 14:14:28.529  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:28.529  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:28.534  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:28.539  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:28.539  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:28.549  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:28.554  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:28.559  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:28.559  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
03-30 14:14:28.559  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-30 14:14:28.559 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:28.559 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:28.559 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:28.559 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-30 14:14:28.559 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:28.559 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:28.559 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-30 14:14:28.579 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:28.579 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:14:28.579 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
,03-30 14:14:28.579 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-30 14:14:28.579 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-30 14:14:28.589 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-30 14:14:28.594 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:28.594 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
,03-30 14:14:28.594 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-30 14:14:28.594 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:28.594 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:28.594 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:28.594 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
,03-30 14:14:28.624 11115 11474 D BluetoothSocket: bindListen(): myUserId = 0,
03-30 14:14:28.624 11115 11474 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,03-30 14:14:28.629 11115 11474 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]},
03-30 14:14:28.629 11115 11474 D BluetoothSocket: bindListen(), new LocalSocket ,
,03-30 14:14:28.629 11115 11474 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-30 14:14:28.629 11115 11474 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c0c46d4,
03-30 14:14:28.634 11115 11474 D BluetoothSocket: channel: 6,
03-30 14:14:28.634 11115 11474 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-30 14:14:28.654 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:28.654 11115 11178 I jxcore-log: 
,03-30 14:14:28.659 11115 11178 I jxcore-log: ok 121 called only once
03-30 14:14:28.659 11115 11178 I jxcore-log: 
,03-30 14:14:28.664 11115 11178 I jxcore-log: ok 122 discovery state matches
03-30 14:14:28.664 11115 11178 I jxcore-log: 
,03-30 14:14:28.664 11115 11178 I jxcore-log: ok 123 advertising state matches
03-30 14:14:28.664 11115 11178 I jxcore-log: 
,03-30 14:14:28.674 11115 11178 I jxcore-log: # teardown
03-30 14:14:28.674 11115 11178 I jxcore-log: 
,03-30 14:14:29.429  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:29.454  5869  5869 D BtGatt.ScanManager: awakened up at time 237773
,03-30 14:14:29.459  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:29.469  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:29.469  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: current time is 237785908069
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: Batch record : [-19, 91, -12, -51, 106, 97, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -71, -88, 95, 111, 17, 93, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:29.469  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:29.469  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=5D:11:6F:5F:A8:B9, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-62, mTimestampNanos=237736128444}
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=61:6A:CD:F4:5B:ED, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=237686128444}
03-30 14:14:29.469  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:29.469 11115 11127 D ScanRecord: parseFromBytes
03-30 14:14:29.469 11115 11127 D ScanRecord: parseFromBytes
03-30 14:14:29.474 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
03-30 14:14:29.474 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-30 14:14:29.474 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-30 14:14:29.474 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 14:14:29.504  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
03-30 14:14:29.504  3723  3723 I PERF    : received broadcast android.intent.action.TIME_TICK
03-30 14:14:29.504  3723  3723 D KeyguardUpdateMonitor: handleTimeUpdate
,03-30 14:14:29.509  3723  3723 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,03-30 14:14:29.514 11115 11178 I jxcore-log: DEBUG createPeerListener: createPeerListener,
03-30 14:14:29.514 11115 11178 I jxcore-log: 
,03-30 14:14:29.524  3723  3723 D SecKeyguardClockView: HomeTimezone(): 1,
,03-30 14:14:29.534  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:14:29.534  3723  3723 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-30 14:14:29.544  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-30 14:14:29.549 11115 11178 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-30 14:14:29.549 11115 11178 I jxcore-log: 
,03-30 14:14:29.549 11115 11178 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-30 14:14:29.549 11115 11178 I jxcore-log: 
,03-30 14:14:29.554 11115 11178 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-30 14:14:29.554 11115 11178 I jxcore-log: 
,03-30 14:14:29.564  3481  3569 W ProcessCpuTracker: Skipping unknown process pid 11481
,03-30 14:14:29.579  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:14:29.579  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:14:29.584  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-30 14:14:29.584  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:14:29.589  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:14:29.589  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:14:29.609  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:14:29.839 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:29.839 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-30 14:14:29.844 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 14:14:29.844 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:29.844 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 14:14:29.844 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3539ebc3, channel: 6, state: LISTENING
,03-30 14:14:29.844 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3539ebc3, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c0c46d4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b50fc40mSocket: android.net.LocalSocket@37d71779 impl:android.net.LocalSocketImpl@30520cbe fd:FileDescriptor[117],
,03-30 14:14:29.844 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37d71779 impl:android.net.LocalSocketImpl@30520cbe fd:FileDescriptor[117]
,03-30 14:14:29.849 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-30 14:14:29.849 11115 11474 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:29.849 11115 11474 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-30 14:14:29.849 11115 11474 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:29.849 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:14:29.854 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:14:29.854 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:29.854 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:14:29.854 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:29.854 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:14:29.854 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:29.854 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:29.854 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:29.854  5869  5956 D BtGatt.GattService: stopScan() - queue size =1,
03-30 14:14:29.859  5869  5957 D BtGatt.ScanManager: filter size is 1
,03-30 14:14:29.859  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 5,
,03-30 14:14:29.859  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-30 14:14:29.859  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:29.859  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:29.864  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:29.864  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:29.864  5869  5880 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:29.864  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:29.864 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:29.864 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:29.869  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:29.869  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:29.869  5869  5942 D BtGatt.GattService: current time is 238186299694
,03-30 14:14:29.869  5869  5942 D BtGatt.GattService: Batch record : [-19, 91, -12, -51, 106, 97, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -71, -88, 95, 111, 17, 93, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-30 14:14:29.869  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:29.869  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:29.869  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:29.869  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:29.869 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:29.869 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:29.869 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:29.869 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:29.869 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-30 14:14:29.879  5869  5954 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:29.879  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:29.879  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:14:29.879  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:14:29.879  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-30 14:14:29.879  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:14:29.884  5869  5880 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:14:29.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:29.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:29.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-30 14:14:29.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:29.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:14:29.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:29.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:29.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:14:29.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:29.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 14:14:29.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:29.884 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:29.884 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:29.884 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:29.884 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:29.884 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:29.889 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:29.889 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:29.889 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:29.889 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:29.894 11115 11178 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-30 14:14:29.894 11115 11178 I jxcore-log: 
,03-30 14:14:29.894 11115 11178 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:29.894 11115 11178 I jxcore-log: 
,03-30 14:14:29.899 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:29.899 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:29.899 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:29.899 11115 11178 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:29.899 11115 11178 I jxcore-log: 
,03-30 14:14:29.899 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:29.899 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:29.899 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:29.904 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:29.904 11115 11178 I jxcore-log: 
,03-30 14:14:29.904 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:29.904 11115 11178 I jxcore-log: 
,03-30 14:14:29.904 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:29.904 11115 11178 I jxcore-log: 
,03-30 14:14:29.909 11115 11178 I jxcore-log: ok 124 error should be null
03-30 14:14:29.909 11115 11178 I jxcore-log: 
,03-30 14:14:29.914 11115 11178 I jxcore-log: ok 125 error should be null
03-30 14:14:29.914 11115 11178 I jxcore-log: 
,03-30 14:14:29.919 11115 11178 I jxcore-log: # setup
03-30 14:14:29.919 11115 11178 I jxcore-log: 
,03-30 14:14:30.244 11115 11178 I jxcore-log: # 32. does not send duplicate availability changes
03-30 14:14:30.244 11115 11178 I jxcore-log: 
,03-30 14:14:30.434 11115 11178 I jxcore-log: ok 126 should be called once
03-30 14:14:30.434 11115 11178 I jxcore-log: 
,03-30 14:14:30.439 11115 11178 I jxcore-log: ok 127 should not have been called more than once
03-30 14:14:30.439 11115 11178 I jxcore-log: 
,03-30 14:14:30.444 11115 11178 I jxcore-log: # teardown
03-30 14:14:30.444 11115 11178 I jxcore-log: 
,03-30 14:14:30.529 11115 11178 I jxcore-log: ok 128 error should be null
03-30 14:14:30.529 11115 11178 I jxcore-log: 
,03-30 14:14:30.534 11115 11178 I jxcore-log: ok 129 error should be null
03-30 14:14:30.534 11115 11178 I jxcore-log: 
,03-30 14:14:30.539 11115 11178 I jxcore-log: # setup
03-30 14:14:30.539 11115 11178 I jxcore-log: 
,03-30 14:14:30.644 11115 11178 I jxcore-log: # 33. can get the network status
03-30 14:14:30.644 11115 11178 I jxcore-log: 
,03-30 14:14:30.759 11115 11178 I jxcore-log: ok 130 network status should have certain non-empty properties
03-30 14:14:30.759 11115 11178 I jxcore-log: 
,03-30 14:14:30.764 11115 11178 I jxcore-log: # teardown
03-30 14:14:30.764 11115 11178 I jxcore-log: 
,03-30 14:14:30.859 11115 11178 I jxcore-log: ok 131 error should be null
03-30 14:14:30.859 11115 11178 I jxcore-log: 
,03-30 14:14:30.859 11115 11178 I jxcore-log: ok 132 error should be null
03-30 14:14:30.859 11115 11178 I jxcore-log: 
,03-30 14:14:30.869 11115 11178 I jxcore-log: # setup
03-30 14:14:30.869 11115 11178 I jxcore-log: 
,03-30 14:14:30.974 11115 11178 I jxcore-log: # 34. wifi peer is marked unavailable if announcements stop
03-30 14:14:30.974 11115 11178 I jxcore-log: 
,03-30 14:14:31.084 11115 11178 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-30 14:14:31.084 11115 11178 I jxcore-log: 
,03-30 14:14:31.114 11115 11178 I jxcore-log: ok 133 host address should match
03-30 14:14:31.114 11115 11178 I jxcore-log: 
,03-30 14:14:31.114 11115 11178 I jxcore-log: ok 134 port should match
03-30 14:14:31.114 11115 11178 I jxcore-log: 
,03-30 14:14:33.099 11115 11178 I jxcore-log: ok 135 host address should be null
03-30 14:14:33.099 11115 11178 I jxcore-log: 
,03-30 14:14:33.104 11115 11178 I jxcore-log: ok 136 port should should be null
03-30 14:14:33.104 11115 11178 I jxcore-log: 
,03-30 14:14:33.124 11115 11178 I jxcore-log: # teardown
03-30 14:14:33.124 11115 11178 I jxcore-log: 
,03-30 14:14:33.684 11115 11178 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-30 14:14:33.684 11115 11178 I jxcore-log: 
,03-30 14:14:33.689 11115 11178 I jxcore-log: ok 137 error should be null
03-30 14:14:33.689 11115 11178 I jxcore-log: 
,03-30 14:14:33.689 11115 11178 I jxcore-log: ok 138 error should be null
03-30 14:14:33.689 11115 11178 I jxcore-log: 
,03-30 14:14:33.694 11115 11178 I jxcore-log: # setup
03-30 14:14:33.694 11115 11178 I jxcore-log: 
,03-30 14:14:33.934 11115 11178 I jxcore-log: # 35. Can call start/stopListeningForAdvertisements
03-30 14:14:33.934 11115 11178 I jxcore-log: 
,03-30 14:14:34.124 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 34975, start advertisements: false
,03-30 14:14:34.124 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:34.124 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:14:34.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:14:34.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:34.129 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:14:34.134 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:34.139  5869  5880 D BtGatt.GattService: registerClient() - UUID=af83de2e-8df0-4988-9bd2-60c4e04c9548
,03-30 14:14:34.184  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=af83de2e-8df0-4988-9bd2-60c4e04c9548, clientIf=6
03-30 14:14:34.184 11115 11127 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:34.189  5869  5883 D BtGatt.GattService: start scan with filters
,03-30 14:14:34.209  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 3
,03-30 14:14:34.214 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:34.214 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:34.214  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:34.214  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:34.214  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:34.214 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:34.214 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:34.214 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:34.214 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:34.219 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:34.219 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:34.219 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:14:34.219 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK,
03-30 14:14:34.219 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
,03-30 14:14:34.219 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-30 14:14:34.219 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 14:14:34.224 11115 11178 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error,
03-30 14:14:34.224 11115 11178 I jxcore-log: 
03-30 14:14:34.229  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-30 14:14:34.229  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:34.229  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:34.229  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:34.229  5869  5957 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-30 14:14:34.229 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:34.229 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:34.229 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:34.229 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:34.229  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:34.229  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:34.229  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:34.229  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:34.234  5869  5883 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:34.234  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:34.234  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:34.234  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:34.234  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:34.234  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:34.234 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:34.234 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:34.234 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:34.239 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:14:34.239 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:14:34.239 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:34.239 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:34.244 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:34.244 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:34.244  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:34.244  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 6
03-30 14:14:34.244 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.244 11115 11178 I jxcore-log: 
03-30 14:14:34.244  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:34.244  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:34.244  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:34.249  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-30 14:14:34.249  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:34.249  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:34.249 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.249 11115 11178 I jxcore-log: 
,03-30 14:14:34.254  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-30 14:14:34.254  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:34.254 11115 11178 I jxcore-log: ok 140 Can call stopListeningForAdvertisements without error
03-30 14:14:34.254 11115 11178 I jxcore-log: 
,03-30 14:14:34.264 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:34.264 11115 11178 I jxcore-log: 
,03-30 14:14:34.264 11115 11178 I jxcore-log: # teardown
03-30 14:14:34.264 11115 11178 I jxcore-log: 
,03-30 14:14:34.384 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:34.384 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:34.384 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:34.389 11115 11178 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:34.389 11115 11178 I jxcore-log: 
,03-30 14:14:34.394 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:34.394 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:34.394 11115 11178 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:14:34.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:14:34.394 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:34.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:14:34.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-30 14:14:34.399 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:14:34.399 11115 11178 D BluetoothLeScanner: could not find callback wrapper
,03-30 14:14:34.399 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:34.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 14:14:34.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:34.404 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:34.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-30 14:14:34.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:34.409 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-30 14:14:34.409 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:34.409 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:34.414 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-30 14:14:34.424 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:34.424 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:34.424 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:34.429 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:34.429 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:34.429 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:34.434 11115 11178 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:34.434 11115 11178 I jxcore-log: 
,03-30 14:14:34.439 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:34.439 11115 11178 I jxcore-log: 
,03-30 14:14:34.444 11115 11178 I jxcore-log: # setup
03-30 14:14:34.444 11115 11178 I jxcore-log: 
,03-30 14:14:34.569 11115 11178 I jxcore-log: # 36. Calling startListeningForAdvertisements twice is NOT an error
03-30 14:14:34.569 11115 11178 I jxcore-log: 
,03-30 14:14:34.704 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 34975, start advertisements: false
,03-30 14:14:34.704 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:34.704 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:14:34.704 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:14:34.709 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:34.709 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:34.709 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:34.714  5869  5883 D BtGatt.GattService: registerClient() - UUID=59677858-9174-40d6-be0a-064d1c350f22
,03-30 14:14:34.759  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=59677858-9174-40d6-be0a-064d1c350f22, clientIf=6
03-30 14:14:34.764 11115 11125 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:34.769  5869  5956 D BtGatt.GattService: start scan with filters,
,03-30 14:14:34.789  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 4
,03-30 14:14:34.794  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:34.794  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:34.794  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:14:34.799  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:34.799  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:34.799  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:34.799  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:34.799  5869  5957 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-30 14:14:34.799  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:34.799  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:34.804  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:34.804  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:34.804  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:34.804  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:34.809  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:34.809  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:34.814 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-30 14:14:34.814 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:34.814 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-30 14:14:34.814 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:34.814 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:34.814 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:14:34.814 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:34.814 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-30 14:14:34.814 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:14:34.814 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:14:34.814 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:34.814 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:34.819 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:34.824 11115 11178 I jxcore-log: ok 143 Can call startListeningForAdvertisements without error
03-30 14:14:34.824 11115 11178 I jxcore-log: 
,03-30 14:14:34.829 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 34975, start advertisements: false
,03-30 14:14:34.829 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:34.829 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:14:34.829 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:34.829 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:34.834 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.834 11115 11178 I jxcore-log: 
,03-30 14:14:34.834 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:34.834 11115 11178 I jxcore-log: 
,03-30 14:14:34.839 11115 11178 I jxcore-log: ok 144 Can call startListeningForAdvertisements twice without error
03-30 14:14:34.839 11115 11178 I jxcore-log: 
,03-30 14:14:34.844 11115 11178 I jxcore-log: # teardown
03-30 14:14:34.844 11115 11178 I jxcore-log: 
,03-30 14:14:35.019 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:35.024 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:35.024 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:35.024 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:35.029  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:35.029  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:35.029  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 7
03-30 14:14:35.029  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:35.029  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:35.029  5869  5957 D BtGatt.ScanManager: stopping BLe Batch,
,03-30 14:14:35.034  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-30 14:14:35.034  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:35.034  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:35.034  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:35.034  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:35.039  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-30 14:14:35.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:35.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:35.044 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:35.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-30 14:14:35.044 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:14:35.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-30 14:14:35.044 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-30 14:14:35.049 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:14:35.049 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-30 14:14:35.049 11115 11178 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:35.049 11115 11178 I jxcore-log: 
,03-30 14:14:35.054 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:35.054 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:35.054 11115 11178 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:14:35.054 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:35.054 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:35.054 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:35.054 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-30 14:14:35.054 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:14:35.059 11115 11178 D BluetoothLeScanner: could not find callback wrapper
,03-30 14:14:35.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:35.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:14:35.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:35.059 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:35.064 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:35.064 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:35.064 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:35.064 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-30 14:14:35.064 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:35.069 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-30 14:14:35.079 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 14:14:35.079 11115 11178 I jxcore-log: 
,03-30 14:14:35.079 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-30 14:14:35.084 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-30 14:14:35.084 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:35.089 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:35.089 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:35.089 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:35.094 11115 11178 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:35.094 11115 11178 I jxcore-log: 
,03-30 14:14:35.099 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:35.099 11115 11178 I jxcore-log: 
,03-30 14:14:35.104 11115 11178 I jxcore-log: # setup
03-30 14:14:35.104 11115 11178 I jxcore-log: 
,03-30 14:14:35.224 11115 11178 I jxcore-log: # 37. Can call start/stopUpdateAdvertisingAndListening
03-30 14:14:35.224 11115 11178 I jxcore-log: 
,03-30 14:14:35.349 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-30 14:14:35.354 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:35.354 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:35.354 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:35.359 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:35.359 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:35.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:35.359 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:35.364  5869  5880 D BtGatt.GattService: registerClient() - UUID=3199351e-5525-4148-841f-0191975a5832
,03-30 14:14:35.409  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=3199351e-5525-4148-841f-0191975a5832, clientIf=6
03-30 14:14:35.409 11115 11171 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:35.409  5869  5956 D BtGatt.GattService: start scan with filters
,03-30 14:14:35.424  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 5
,03-30 14:14:35.429  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:35.429  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:35.429  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:14:35.434  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:35.434  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:35.434  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:35.434  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:35.434  5869  5957 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-30 14:14:35.439  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:35.439  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:35.439  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:35.439  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:35.444  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:35.444  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:35.444  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:35.444  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:35.444 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:35.444 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:35.444 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:35.444 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:35.444 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:35.444 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:35.444 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:35.444 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:35.444 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:35.444 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:35.444 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:35.444 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:35.454  5869  5883 D BtGatt.GattService: registerClient() - UUID=d044fb99-7768-48e1-a735-4e71842d15ee
,03-30 14:14:35.494  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=d044fb99-7768-48e1-a735-4e71842d15ee, clientIf=7
,03-30 14:14:35.494 11115 11125 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:35.509  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 2
,03-30 14:14:35.509  5869  5954 D BtGatt.AdvertiseManager: message : 0
03-30 14:14:35.509  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
,03-30 14:14:35.509  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:35.509  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:35.509  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:35.514  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:35.514  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:35.514  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:35.519  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:35.519  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-30 14:14:35.519 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:35.519 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:14:35.524 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:35.524 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:35.524 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:35.524 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:35.524 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:14:35.524 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:35.524 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:35.524 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:35.524 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:14:35.524 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:35.524 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-30 14:14:35.524 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:35.524 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:35.524 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:35.524 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:35.524 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:35.524 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:35.524 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:35.524 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:35.524 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:35.524 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:35.529 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:35.529 11115 11178 I jxcore-log: 
03-30 14:14:35.529 11115 11549 D BluetoothSocket: bindListen(): myUserId = 0
03-30 14:14:35.529 11115 11549 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:35.529 11115 11178 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-30 14:14:35.529 11115 11178 I jxcore-log: 
,03-30 14:14:35.534 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:35.534 11115 11549 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-30 14:14:35.534 11115 11549 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:14:35.534 11115 11549 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-30 14:14:35.534 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:35.534 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:35.534 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:35.534 11115 11549 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24390d04,
03-30 14:14:35.534 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 14:14:35.534 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:35.534 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:14:35.534 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:35.534 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:14:35.534 11115 11549 D BluetoothSocket: channel: 6
03-30 14:14:35.534 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:35.534 11115 11549 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2359f2ed, channel: 6, state: LISTENING
03-30 14:14:35.534 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:14:35.534 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:14:35.534 11115 11549 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2359f2ed, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24390d04, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@59ed522mSocket: android.net.LocalSocket@3dd4bb3 impl:android.net.LocalSocketImpl@11bbf570 fd:FileDescriptor[92]
03-30 14:14:35.534 11115 11549 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3dd4bb3 impl:android.net.LocalSocketImpl@11bbf570 fd:FileDescriptor[92]
03-30 14:14:35.534 11115 11549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:14:35.534 11115 11549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:35.534 11115 11549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:35.534  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:35.534  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:35.534  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 8
03-30 14:14:35.534  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:35.534 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:35.539 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:35.539 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:35.539 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:35.539 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 14:14:35.539  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:35.539  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:35.539 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:35.539 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:14:35.539  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:35.539  5869  5954 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:35.539  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:35.539  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-30 14:14:35.539  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:35.539  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:35.539  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:35.539  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-30 14:14:35.544  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:35.544  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:35.544  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-30 14:14:35.544  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:14:35.544  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:14:35.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:35.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:35.549 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
,03-30 14:14:35.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:35.549 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:14:35.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:35.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:35.549 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:35.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-30 14:14:35.549 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:35.549 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:35.549 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:35.549 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:14:35.549 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-30 14:14:35.549 11115 11178 I jxcore-log: ,
,03-30 14:14:35.554 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-30 14:14:35.554 11115 11178 I jxcore-log: 
03-30 14:14:35.559 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-30 14:14:35.569 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-30 14:14:35.569 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-30 14:14:35.569 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-30 14:14:35.569 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-30 14:14:35.569 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:35.569 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-30 14:14:35.569 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:35.569 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:35.574 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-30 14:14:35.574 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:35.574 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-30 14:14:35.574 11115 11178 I jxcore-log: ok 148 Can call stopAdvertisingAndListening without error,
03-30 14:14:35.574 11115 11178 I jxcore-log: 
,03-30 14:14:35.589 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:35.589 11115 11178 I jxcore-log: 
,03-30 14:14:35.589 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:35.589 11115 11178 I jxcore-log: 
,03-30 14:14:35.594 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:35.594 11115 11178 I jxcore-log: 
,03-30 14:14:35.594 11115 11178 I jxcore-log: # teardown
03-30 14:14:35.594 11115 11178 I jxcore-log: 
,03-30 14:14:35.669 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:35.669 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:14:35.669 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:35.674 11115 11178 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:35.674 11115 11178 I jxcore-log: 
,03-30 14:14:35.679 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:35.679 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:14:35.679 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:35.684 11115 11178 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:35.684 11115 11178 I jxcore-log: 
,03-30 14:14:35.694 11115 11178 I jxcore-log: # setup
03-30 14:14:35.694 11115 11178 I jxcore-log: 
,03-30 14:14:35.944 11115 11178 I jxcore-log: # 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-30 14:14:35.944 11115 11178 I jxcore-log: 
,03-30 14:14:36.089 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-30 14:14:36.094 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:36.094 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-30 14:14:36.094 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:36.099 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:36.099 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:36.099 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:14:36.099 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:36.109  5869  5956 D BtGatt.GattService: registerClient() - UUID=00251772-3e30-4f31-b351-9e5b492a2e7d
,03-30 14:14:36.149  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=00251772-3e30-4f31-b351-9e5b492a2e7d, clientIf=6
03-30 14:14:36.149 11115 11127 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:36.149  5869  5883 D BtGatt.GattService: start scan with filters
,03-30 14:14:36.164  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 6
,03-30 14:14:36.164  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:36.164  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:36.164  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:14:36.169  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:36.169  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:36.169 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:36.169 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:36.169 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:36.169 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:36.169 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:36.169 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:36.169 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:36.169 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:36.169 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:36.169 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:36.169 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:36.169 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:14:36.174  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:36.174  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:36.174  5869  5957 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-30 14:14:36.174  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:36.174  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:36.174  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan,
03-30 14:14:36.174  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:36.179  5869  5956 D BtGatt.GattService: registerClient() - UUID=15a79a17-d813-425a-b32d-60bedb8286ba
,03-30 14:14:36.179  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:36.179  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:36.179  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:36.179  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:36.219  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=15a79a17-d813-425a-b32d-60bedb8286ba, clientIf=7
,03-30 14:14:36.219 11115 11171 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:36.234  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 3
,03-30 14:14:36.234  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:36.234  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:36.234  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:36.234  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:36.234  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:36.239  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:36.239  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:36.239  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:36.239  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:36.239  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-30 14:14:36.244 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:36.244 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:14:36.244 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:36.244 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:36.244 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:36.244 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:36.244 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:14:36.249 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:36.249 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:36.249 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:36.249 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:36.249 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:36.249 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:36.249 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:36.249 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:36.249 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:36.249 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:36.249 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:36.249 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:36.249 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:36.249 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:36.249 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:36.249 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:36.249 11115 11558 D BluetoothSocket: bindListen(): myUserId = 0
,03-30 14:14:36.249 11115 11558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:36.254 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-30 14:14:36.254 11115 11178 I jxcore-log: 
03-30 14:14:36.254 11115 11558 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-30 14:14:36.254 11115 11558 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:14:36.254 11115 11558 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-30 14:14:36.254 11115 11558 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2342f89c
,03-30 14:14:36.254 11115 11558 D BluetoothSocket: channel: 6
03-30 14:14:36.254 11115 11558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 14:14:36.254 11115 11178 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListening without error
03-30 14:14:36.254 11115 11178 I jxcore-log: 
,03-30 14:14:36.259 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-30 14:14:36.259 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:36.259 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:36.259 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:36.259 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:36.264 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:36.264 11115 11178 I jxcore-log: 
,03-30 14:14:36.264 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:36.264 11115 11178 I jxcore-log: 
,03-30 14:14:36.269 11115 11178 I jxcore-log: ok 152 Can call startUpdateAdvertisingAndListening twice without error
03-30 14:14:36.269 11115 11178 I jxcore-log: 
,03-30 14:14:36.274 11115 11178 I jxcore-log: # teardown
03-30 14:14:36.274 11115 11178 I jxcore-log: 
,03-30 14:14:36.739 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:36.739 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-30 14:14:36.744 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:36.744 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:36.749  5869  5880 D BtGatt.GattService: stopScan() - queue size =1,
,03-30 14:14:36.749  5869  5957 D BtGatt.ScanManager: filter size is 1
,03-30 14:14:36.749  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 9
,03-30 14:14:36.754  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-30 14:14:36.754  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:36.754  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:36.759  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:36.759  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:36.759  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:36.759  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:36.759  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:36.759  5869  5942 D BtGatt.GattService: current time is 245079132486
03-30 14:14:36.759  5869  5942 D BtGatt.GattService: Batch record : [-40, 27, -3, -79, -5, 116, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 7, -13, 75, 38, 35, 87, 1, -128, -59, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-30 14:14:36.759  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:36.759  5869  5942 D ScanRecord: parseFromBytes,
,03-30 14:14:36.759  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
03-30 14:14:36.759  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:36.764  5869  5883 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:36.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:36.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:36.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:14:36.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:36.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-30 14:14:36.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:36.769 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:36.769 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:14:36.769 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:36.774 11115 11178 I jxcore-log: ok 153 Should be able to call stopListeningForAdvertisments in teardown,
03-30 14:14:36.774 11115 11178 I jxcore-log: 
03-30 14:14:36.774 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:14:36.774 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:36.774 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:14:36.774 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-30 14:14:36.774 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:14:36.774 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@feb92a5, channel: 6, state: LISTENING
03-30 14:14:36.774 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@feb92a5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2342f89c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e99e67amSocket: android.net.LocalSocket@281c7e2b impl:android.net.LocalSocketImpl@2d50288 fd:FileDescriptor[92]
03-30 14:14:36.774 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@281c7e2b impl:android.net.LocalSocketImpl@2d50288 fd:FileDescriptor[92]
,03-30 14:14:36.779 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-30 14:14:36.784 11115 11558 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-30 14:14:36.784 11115 11558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:36.784 11115 11558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 14:14:36.784 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 14:14:36.784 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:14:36.784 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-30 14:14:36.784 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-30 14:14:36.784 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-30 14:14:36.784 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-30 14:14:36.784 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-30 14:14:36.784 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:14:36.789 11115 11178 D BluetoothLeScanner: could not find callback wrapper
,03-30 14:14:36.789 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:36.789 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:14:36.789  5869  5954 D BtGatt.AdvertiseManager: message : 1,
,03-30 14:14:36.789  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-30 14:14:36.789  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:14:36.794  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-30 14:14:36.794  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-30 14:14:36.794  5869  5942 D BtGatt.GattService: Client app is not null!
03-30 14:14:36.794  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-30 14:14:36.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:36.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:36.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:14:36.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 14:14:36.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
,03-30 14:14:36.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:36.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:36.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:14:36.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:14:36.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:36.799 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:36.799 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:36.799 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:36.799 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:36.799 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:14:36.809 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:36.809 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:14:36.814 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:36.814 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:36.814 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:36.814 11115 11178 I jxcore-log: 
03-30 14:14:36.819 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:36.819 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:36.819 11115 11178 I jxcore-log: ok 154 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:36.819 11115 11178 I jxcore-log: 
,03-30 14:14:36.824 11115 11178 I jxcore-log: # setup
03-30 14:14:36.824 11115 11178 I jxcore-log: 
03-30 14:14:36.829 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:36.829 11115 11178 I jxcore-log: 
03-30 14:14:36.829 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:36.829 11115 11178 I jxcore-log: 
,03-30 14:14:37.044 11115 11178 I jxcore-log: # 39. peerAvailabilityChange is called
03-30 14:14:37.044 11115 11178 I jxcore-log: 
,03-30 14:14:37.199 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-30 14:14:37.199 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:37.199 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-30 14:14:37.199 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:37.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:37.209 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:37.209 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:37.209 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:37.214  5869  5956 D BtGatt.GattService: registerClient() - UUID=ac316468-cd28-4ea4-bf35-8bc343aeb6fd
,03-30 14:14:37.254  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=ac316468-cd28-4ea4-bf35-8bc343aeb6fd, clientIf=6
03-30 14:14:37.254 11115 11125 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:37.264  5869  5880 D BtGatt.GattService: start scan with filters,
,03-30 14:14:37.289  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 7
,03-30 14:14:37.289  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:37.289  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:37.289  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:14:37.294  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:37.294  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:37.294  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:37.294  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:37.294  5869  5957 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-30 14:14:37.299  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:37.299  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:37.299  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:37.299  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:37.304  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:37.304  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:37.304  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:37.304  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:37.309 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-30 14:14:37.309 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:37.309 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-30 14:14:37.309 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:37.309 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:37.309 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-30 14:14:37.309 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:37.309 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:37.309 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:14:37.309 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:37.309 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-30 14:14:37.309 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 14:14:37.319  5869  5956 D BtGatt.GattService: registerClient() - UUID=fdf2fa8a-d44c-4c8b-a635-103f983486a9
,03-30 14:14:37.359  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=fdf2fa8a-d44c-4c8b-a635-103f983486a9, clientIf=7
,03-30 14:14:37.359 11115 11127 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:37.379  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 4
,03-30 14:14:37.379  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:37.379  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:37.379  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:37.384  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:37.384  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-30 14:14:37.384  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:37.389  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising,
,03-30 14:14:37.394  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-30 14:14:37.394  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:37.394  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-30 14:14:37.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:37.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:14:37.399 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:14:37.399 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:37.399 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:37.399 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:37.399 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-30 14:14:37.399 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:37.399 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:37.399 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:37.399 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:37.399 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:37.399 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:37.399 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:37.399 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:37.399 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 14:14:37.399 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:37.399 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:37.399 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:37.399 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:37.399 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:37.399 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:37.399 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:37.404 11115 11579 D BluetoothSocket: bindListen(): myUserId = 0
03-30 14:14:37.404 11115 11579 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:37.404 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:37.404 11115 11178 I jxcore-log: 
,03-30 14:14:37.404 11115 11579 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-30 14:14:37.404 11115 11579 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:14:37.404 11115 11579 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-30 14:14:37.404 11115 11579 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31fbbf34
,03-30 14:14:37.404 11115 11579 D BluetoothSocket: channel: 6
03-30 14:14:37.404 11115 11579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:37.409 11115 11178 I jxcore-log: ok 155 Can call startUpdateAdvertisingAndListeningwithout error
03-30 14:14:37.409 11115 11178 I jxcore-log: 
,03-30 14:14:37.409 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-30 14:14:37.409 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:37.409 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-30 14:14:37.409 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:14:37.409 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:37.414 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:37.414 11115 11178 I jxcore-log: 
,03-30 14:14:37.414 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:37.414 11115 11178 I jxcore-log: 
,03-30 14:14:37.419 11115 11178 I jxcore-log: ok 156 Can call startListeningForAdvertisements without error
03-30 14:14:37.419 11115 11178 I jxcore-log: 
,03-30 14:14:37.479  3481  3509 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-30 14:14:37.479  3481  3509 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-30 14:14:37.479  3481  3509 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
03-30 14:14:37.479  3481  3509 D BatteryService: stay LED for fully charged
03-30 14:14:37.479  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:14:37.479  3481  3481 I MotionRecognitionService: Plugged
,03-30 14:14:37.479  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-30 14:14:37.479  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-30 14:14:37.479  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-30 14:14:37.484  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-30 14:14:37.484  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:14:37.484  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-30 14:14:37.489  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-30 14:14:37.489  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
,03-30 14:14:37.504  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:37.504  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:37.504  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:37.504  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:37.724  3481  3584 I PowerManagerService: [PWL] Off : 180s ago,
,03-30 14:14:37.724  3481  3584 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1,
,03-30 14:14:37.724  3481  3584 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1,
,03-30 14:14:37.724  3481  3584 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5869, ws=null) (elapsedTime=973),
,03-30 14:14:38.189  3481  6076 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:12), CUR = 39, LCD = 0
,03-30 14:14:38.314  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:38.324  5869  5869 D BtGatt.ScanManager: awakened up at time 246644,
,03-30 14:14:38.334  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:38.349  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:38.349  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-30 14:14:38.349  5869  5942 D BtGatt.GattService: current time is 246668243403,
,03-30 14:14:38.349  5869  5942 D BtGatt.GattService: Batch record : [52, -49, 29, -49, 53, 110, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 116, 40, 116, -111, 105, 89, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:14:38.349  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-30 14:14:38.349  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:38.349  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 14:14:38.349  5869  5942 D ScanRecord: parseFromBytes,
,03-30 14:14:38.349  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=6E:35:CF:1D:CF:34, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-62, mTimestampNanos=246618462236}
,03-30 14:14:38.349  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:38.349  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=59:69:91:74:28:74, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-78, mTimestampNanos=246668462236}
03-30 14:14:38.349  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-30 14:14:38.354 11115 11125 D ScanRecord: parseFromBytes
03-30 14:14:38.354 11115 11125 D ScanRecord: parseFromBytes
03-30 14:14:38.354 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 1
,03-30 14:14:38.354 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 2
03-30 14:14:38.354 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-30 14:14:38.354 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 14:14:38.379 11115 11178 I jxcore-log: ok 157 peers must be an array,
03-30 14:14:38.379 11115 11178 I jxcore-log: 
03-30 14:14:38.379 11115 11178 I jxcore-log: ok 158 peers must not be zero-length
03-30 14:14:38.379 11115 11178 I jxcore-log: 
,03-30 14:14:38.379 11115 11178 I jxcore-log: ok 159 peer must have peerIdentifier
03-30 14:14:38.379 11115 11178 I jxcore-log: 
03-30 14:14:38.379 11115 11178 I jxcore-log: ok 160 peerIdentifier must be a string
03-30 14:14:38.379 11115 11178 I jxcore-log: 
03-30 14:14:38.379 11115 11178 I jxcore-log: ok 161 peer must have peerAvailable
,03-30 14:14:38.379 11115 11178 I jxcore-log: 
03-30 14:14:38.379 11115 11178 I jxcore-log: ok 162 peer must have pleaseConnect
03-30 14:14:38.379 11115 11178 I jxcore-log: 
,03-30 14:14:38.389 11115 11178 I jxcore-log: # teardown
03-30 14:14:38.389 11115 11178 I jxcore-log: 
,03-30 14:14:39.069 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:14:39.074 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-30 14:14:39.074 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-30 14:14:39.074 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:14:39.079  5869  5956 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:39.079  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:39.079  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 10
,03-30 14:14:39.079  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-30 14:14:39.079  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:39.084  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:39.084  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:39.084  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:39.084  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-30 14:14:39.089  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
,03-30 14:14:39.089  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:39.089  5869  5942 D BtGatt.GattService: current time is 247406986861
,03-30 14:14:39.089  5869  5942 D BtGatt.GattService: Batch record : [52, -49, 29, -49, 53, 110, 1, -128, -62, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 116, 40, 116, -111, 105, 89, 1, -128, -77, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
,03-30 14:14:39.089  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:39.089  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:14:39.089  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-30 14:14:39.089  5869  5942 D ScanRecord: parseFromBytes,
03-30 14:14:39.094  5869  5883 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:39.099 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-30 14:14:39.099 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-30 14:14:39.099 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-30 14:14:39.099 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:39.099 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-30 14:14:39.099 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-30 14:14:39.104 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:39.104 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-30 14:14:39.104 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-30 14:14:39.114 11115 11178 I jxcore-log: ok 163 Should be able to call stopListeningForAdvertisments in teardown,
03-30 14:14:39.114 11115 11178 I jxcore-log: 
,03-30 14:14:39.114 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-30 14:14:39.114 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:39.119 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 14:14:39.119 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:39.119 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 14:14:39.119 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ad087a3, channel: 6, state: LISTENING
,03-30 14:14:39.119 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ad087a3, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31fbbf34, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f2f9aa0mSocket: android.net.LocalSocket@21c659 impl:android.net.LocalSocketImpl@1aa6c21e fd:FileDescriptor[92]
,03-30 14:14:39.119 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21c659 impl:android.net.LocalSocketImpl@1aa6c21e fd:FileDescriptor[92]
,03-30 14:14:39.119 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-30 14:14:39.119 11115 11579 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-30 14:14:39.119 11115 11579 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:39.119 11115 11579 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 14:14:39.124 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 14:14:39.124 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:14:39.124 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:14:39.124 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:14:39.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:14:39.124 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:39.124 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-30 14:14:39.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-30 14:14:39.129 11115 11178 D BluetoothLeScanner: could not find callback wrapper,
,03-30 14:14:39.129 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-30 14:14:39.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-30 14:14:39.129  5869  5954 D BtGatt.AdvertiseManager: message : 1,
03-30 14:14:39.134  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-30 14:14:39.134  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
,03-30 14:14:39.134  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:14:39.134  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-30 14:14:39.134  5869  5942 D BtGatt.GattService: Client app is not null!
03-30 14:14:39.134  5869  5880 D BtGatt.GattService: unregisterClient() - clientIf=7
03-30 14:14:39.139 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:39.139 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:39.139 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:14:39.139 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:39.139 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:14:39.139 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:39.139 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:39.139 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:14:39.139 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:39.139 11115 11178 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear,
03-30 14:14:39.139 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:39.144 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:39.144 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:39.144 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:39.144 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:39.144 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:39.149 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-30 14:14:39.154 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:14:39.159 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:39.159 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:39.159 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:39.159 11115 11178 I jxcore-log: 
03-30 14:14:39.159 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:14:39.159 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:14:39.159 11115 11178 I jxcore-log: ok 164 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:39.159 11115 11178 I jxcore-log: 
,03-30 14:14:39.169 11115 11178 I jxcore-log: # setup
03-30 14:14:39.169 11115 11178 I jxcore-log: 
,03-30 14:14:39.174 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:39.174 11115 11178 I jxcore-log: 
,03-30 14:14:39.179 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:39.179 11115 11178 I jxcore-log: 
,03-30 14:14:41.504  3481  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-30 14:14:41.699 11115 11178 I jxcore-log: # 40. Can connect to a remote peer
03-30 14:14:41.699 11115 11178 I jxcore-log: 
,03-30 14:14:41.784 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 43042, start advertisements: true
03-30 14:14:41.784 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:41.784 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:41.784 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:41.789 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-30 14:14:41.789 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:41.789 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:41.789 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:41.794  5869  5880 D BtGatt.GattService: registerClient() - UUID=214b0dab-a1cd-458d-8c8a-1c6889c7023d
,03-30 14:14:41.834  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=214b0dab-a1cd-458d-8c8a-1c6889c7023d, clientIf=6
,03-30 14:14:41.839 11115 11125 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:41.839  5869  5956 D BtGatt.GattService: start scan with filters
,03-30 14:14:41.859  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 8
,03-30 14:14:41.859  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:41.859  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:41.859  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:14:41.869  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:41.869  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:41.869  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:41.869  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:41.869  5869  5957 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
03-30 14:14:41.874  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:41.874  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:41.874  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:41.874  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:41.874  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:41.874  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:41.879  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:41.879  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:41.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-30 14:14:41.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:41.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 14:14:41.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:41.884 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:41.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:14:41.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:41.884 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:41.884 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:14:41.884 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:41.884 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:41.884 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:41.889  5869  5880 D BtGatt.GattService: registerClient() - UUID=aca6504c-3f2b-4d1a-8475-377eb6b70432,
,03-30 14:14:41.934  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=aca6504c-3f2b-4d1a-8475-377eb6b70432, clientIf=7,
,03-30 14:14:41.934 11115 11127 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-30 14:14:41.964  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 5
,03-30 14:14:41.964  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:41.964  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:41.964  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:41.969  5869  5954 D BtGatt.AdvertiseManager: starting advertising
03-30 14:14:41.969  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-30 14:14:41.974  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:41.974  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:41.979  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:41.979  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:41.979  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-30 14:14:41.979 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:41.979 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:14:41.984 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:41.984 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:14:41.984 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:14:41.984 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:41.984 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:14:41.984 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:14:41.984 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:14:41.984 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:14:41.984 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:41.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:41.984 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:41.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:41.984 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:14:41.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:41.984 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:41.984 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:41.984 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:14:41.984 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:41.984 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:14:41.984 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:14:41.984 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:41.989 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-30 14:14:41.989 11115 11178 I jxcore-log: 
,03-30 14:14:41.994 11115 11178 I jxcore-log: ok 165 Can call startUpdateAdvertisingAndListening without error,
03-30 14:14:41.994 11115 11178 I jxcore-log: 
,03-30 14:14:41.999 11115 11610 D BluetoothSocket: bindListen(): myUserId = 0,
03-30 14:14:41.999 11115 11610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:41.999 11115 11610 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
,03-30 14:14:41.999 11115 11610 D BluetoothSocket: bindListen(), new LocalSocket 
,03-30 14:14:42.004 11115 11610 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-30 14:14:42.004 11115 11610 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@678e22a
03-30 14:14:42.004 11115 11610 D BluetoothSocket: channel: 6,
03-30 14:14:42.004 11115 11610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:42.009 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 43042, start advertisements: false
,03-30 14:14:42.009 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:42.009 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-30 14:14:42.009 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:42.009 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:42.014 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:42.014 11115 11178 I jxcore-log: 
,03-30 14:14:42.014 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:42.014 11115 11178 I jxcore-log: 
,03-30 14:14:42.019 11115 11178 I jxcore-log: ok 166 Can call startListeningForAdvertisements without error
03-30 14:14:42.019 11115 11178 I jxcore-log: 
,03-30 14:14:42.879  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:42.894  5869  5869 D BtGatt.ScanManager: awakened up at time 251213
,03-30 14:14:42.899  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:42.904  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:42.904  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: current time is 251223489195
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: Batch record : [79, -94, -49, -106, 88, 74, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -79, 30, -59, -90, 8, 125, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:42.904  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:42.904  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=4A:58:96:CF:A2:4F, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=251123673320}
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=7D:08:A6:C5:1E:B1, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=251173673320}
03-30 14:14:42.904  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:42.909 11115 11171 D ScanRecord: parseFromBytes
03-30 14:14:42.909 11115 11171 D ScanRecord: parseFromBytes
03-30 14:14:42.909 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-30 14:14:42.909 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-30 14:14:42.909 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-30 14:14:42.909 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: ,
03-30 14:14:42.919 11115 11178 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-30 14:14:42.919 11115 11178 I jxcore-log: 
,03-30 14:14:42.929 11115 11178 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-30 14:14:42.929 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-30 14:14:42.934 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-30 14:14:42.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-30 14:14:42.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-30 14:14:42.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
,03-30 14:14:42.939 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-30 14:14:42.939 11115 11178 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-30 14:14:42.944 11115 11178 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true,"pleaseConnect":false}]
03-30 14:14:42.944 11115 11178 I jxcore-log: 
,03-30 14:14:42.944 11115 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1536)
,03-30 14:14:42.954 11115 11617 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-30 14:14:42.954 11115 11617 D BluetoothSocket: connect(): myUserId = 0
,03-30 14:14:42.954 11115 11617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:42.959  5869  5880 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-30 14:14:42.959  5869  6029 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:42.959  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-30 14:14:42.959  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-30 14:14:42.959  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-30 14:14:42.959  5869  6029 D IOP_DB_BT: db_query_execute: result 1
03-30 14:14:42.959  5869  6029 W bt-btif : bta_dm_acl_change(), event : 2
,03-30 14:14:42.964 11115 11617 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,03-30 14:14:43.924  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:43.939  5869  5869 D BtGatt.ScanManager: awakened up at time 252254
,03-30 14:14:43.944  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:43.949  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:43.949  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:43.949  5869  5942 D BtGatt.GattService: current time is 252265822820
03-30 14:14:43.949  5869  5942 D BtGatt.GattService: Batch record : [-79, 30, -59, -90, 8, 125, 1, -128, -55, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 79, -94, -49, -106, 88, 74, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
,03-30 14:14:43.949  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:43.949  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:14:43.949  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:43.949  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:43.949  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=4A:58:96:CF:A2:4F, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=252266002070}
,03-30 14:14:43.949  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:43.949  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=7D:08:A6:C5:1E:B1, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=252066002070}
,03-30 14:14:43.949  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-30 14:14:43.949 11115 11125 D ScanRecord: parseFromBytes
03-30 14:14:43.949 11115 11125 D ScanRecord: parseFromBytes
,03-30 14:14:43.949 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-30 14:14:43.949 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-30 14:14:44.284  3481  3861 E Watchdog: !@Sync 8 [03-30 14:14:44.287]
,03-30 14:14:44.964  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:44.979  5869  5869 D BtGatt.ScanManager: awakened up at time 253296
,03-30 14:14:44.984  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:44.989  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2,
03-30 14:14:44.989  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:44.989  5869  5942 D BtGatt.GattService: current time is 253309438945
03-30 14:14:44.989  5869  5942 D BtGatt.GattService: Batch record : [-79, 30, -59, -90, 8, 125, 1, -128, -54, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 79, -94, -49, -106, 88, 74, 1, -128, -73, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:14:44.989  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97],
,03-30 14:14:44.989  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:44.994  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:44.994  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:14:44.994  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=4A:58:96:CF:A2:4F, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=252909617279}
03-30 14:14:44.994  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:44.994  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=7D:08:A6:C5:1E:B1, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=252909617279},
,03-30 14:14:44.994  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:44.994 11115 11127 D ScanRecord: parseFromBytes
03-30 14:14:44.994 11115 11127 D ScanRecord: parseFromBytes
,03-30 14:14:44.994 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:14:44.994 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-30 14:14:45.354  5869  6029 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:45.354  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:45.354  5869  6029 W bt-btif : bta_dm_acl_change(), event : 2
,03-30 14:14:45.374  5869  6029 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:45.374  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-30 14:14:45.374  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-30 14:14:45.374  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-30 14:14:45.374  5869  6029 D IOP_DB_BT: db_query_execute: result 1
03-30 14:14:45.374  5869  6029 W bt-btif : bta_dm_acl_change(), event : 0
03-30 14:14:45.379  5869  6029 W bt-btif : info:x10
03-30 14:14:45.379  5869  5942 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-30 14:14:45.379  5869  5942 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-30 14:14:45.379  5869  6029 W bt-btif : bta_dm_acl_change(), event : 2
,03-30 14:14:45.394  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
,03-30 14:14:45.474  5869  6029 W bt-sdp  : process_service_search_attr_rsp
,03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_execute: result 1
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_create: id EnforceSlaveRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-30 14:14:45.599  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-30 14:14:45.604  5869  6029 D IOP_DB_BT: db_query_execute: result 1
,03-30 14:14:45.669  5869  6029 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
,03-30 14:14:45.669  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:45.684  5869  6029 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:45.684  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-30 14:14:45.684  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-30 14:14:45.684  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-30 14:14:45.684  5869  6029 D IOP_DB_BT: db_query_execute: result 1
03-30 14:14:45.684  5869  6029 W bt-btif : bta_dm_acl_change(), event : 0
03-30 14:14:45.684  5869  6029 W bt-btif : info:x10
03-30 14:14:45.684  5869  5942 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-30 14:14:45.684  5869  5942 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-30 14:14:45.684  5869  6029 W bt-btif : bta_dm_acl_change(), event : 2
,03-30 14:14:45.709  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-30 14:14:45.859  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb359329c rs_disc_pending=1
03-30 14:14:45.859  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:45.859  5869  6029 W bt-btif : bta_dm_check_av:0
03-30 14:14:45.864  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:46.009  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:46.024  5869  5869 D BtGatt.ScanManager: awakened up at time 254342
,03-30 14:14:46.029  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:46.034  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:46.034  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:46.209  5869  5942 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-30 14:14:46.219  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-30 14:14:46.239  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-30 14:14:46.239  5869  5942 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-30 14:14:46.244  3481  4763 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-30 14:14:46.249  5869  5942 E bt-btif : check_cod: remote_cod = 0x5a020c
03-30 14:14:46.249  5869  5942 W bt-btif : btif_dm_ssp_reply: accept=1
,03-30 14:14:46.264  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-30 14:14:46.264  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-30 14:14:46.269  5869  5953 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-30 14:14:46.274  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-30 14:14:46.274  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-30 14:14:46.279  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{acf5b45 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{11bf0353 10157:com.android.settings/1000}
03-30 14:14:46.274  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-30 14:14:46.274  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
03-30 14:14:46.279  3481  4734 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:46.279  5869  5953 D BtConfig.SecureMode: isSecureModeOn:false
03-30 14:14:46.279  5869  5953 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-30 14:14:46.284  3723  3723 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-30 14:14:46.284 10157 10157 D BluetoothNotiBroadcastReceiver: onReceive
,03-30 14:14:46.284  3723  4706 D BluetoothTile:  handleUpdatestate:false name:null
,03-30 14:14:46.289 10235 11643 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-30 14:14:46.289 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-30 14:14:46.289  3481  4733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{acf5b45 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102}
,03-30 14:14:46.289 10235 10235 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-30 14:14:46.294 10235 10235 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-30 14:14:46.299  3481  3958 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{acf5b45 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102}
,03-30 14:14:46.299  3481  4041 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:46.304 10235 11644 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-30 14:14:46.304 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-30 14:14:46.309  3481  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{acf5b45 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1402b35b 10419:com.samsung.android.app.watchmanagerstub/u0a121}
,03-30 14:14:46.324 10419 10419 E BluetoothHeadset: BTStateChangeCB is registed
,03-30 14:14:46.324 10419 10419 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-30 14:14:46.324 10419 10419 D GMHFPReceiver: jangil::setProperties()
,03-30 14:14:46.324 10419 10419 D GMHFPReceiver: jangil::printBTStatus()
,03-30 14:14:46.329  3481  3831 D SettingsProvider: name = Wearable0001
,03-30 14:14:46.329  3481  3831 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:46.329  3481  3831 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:46.329  3481  3831 D SettingsProvider: selectionArgs: false
03-30 14:14:46.329  3481  3831 D SettingsProvider: selectionArgs: 10121
03-30 14:14:46.329  3481  3831 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:46.329  3481  3831 D SettingsProvider: ret = -1
,03-30 14:14:46.334  3481  3831 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-30 14:14:46.339 10419 10419 D GMHFPReceiver: ::::::::Wearable0001::false
,03-30 14:14:46.339  3481  3961 D SettingsProvider: name = Wearable0002
03-30 14:14:46.339  3481  3961 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:46.339  3481  3961 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-30 14:14:46.339  3481  3961 D SettingsProvider: selectionArgs: false
03-30 14:14:46.339  3481  3961 D SettingsProvider: selectionArgs: 10121
03-30 14:14:46.339  3481  3961 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:46.339  3481  3961 D SettingsProvider: ret = -1
,03-30 14:14:46.349  3723  3723 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,03-30 14:14:46.349  5869  5942 W bt-btif : btif_dm_auth_cmpl_evt,
03-30 14:14:46.354  5869  5942 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-30 14:14:46.359  3481  3961 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-30 14:14:46.359 10419 10419 D GMHFPReceiver: ::::::::Wearable0002::false
,03-30 14:14:46.364  3481  3743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{acf5b45 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1cbe426a 4412:com.google.android.gms.persistent/u0a14}
,03-30 14:14:46.369  5869  5942 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-30 14:14:46.369  5869  5953 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-30 14:14:46.369  3481  3958 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-30 14:14:46.374  3723  3723 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-30 14:14:46.374  5869  5953 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-30 14:14:46.379  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-30 14:14:46.379  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-30 14:14:46.379  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
,03-30 14:14:46.379  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-30 14:14:46.379  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
,03-30 14:14:46.379  3723  3723 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-30 14:14:46.379  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-30 14:14:46.384  3723  4706 D BluetoothTile:  handleUpdatestate:false name:null
,03-30 14:14:46.384  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1f55a7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{11bf0353 10157:com.android.settings/1000}
,03-30 14:14:46.384  5869  5953 D BtConfig.SecureMode: isSecureModeOn:false
03-30 14:14:46.384 10157 10157 D BluetoothNotiBroadcastReceiver: onReceive
03-30 14:14:46.384  3481  4763 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:46.394 10235 11646 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-30 14:14:46.394  5869  5953 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@35c93cb9
,03-30 14:14:46.399  3481  4021 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-30 14:14:46.399  3481  4021 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:46.399  3481  4021 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:46.399  3481  4021 D SettingsProvider: selectionArgs: false
03-30 14:14:46.399  3481  4021 D SettingsProvider: selectionArgs: 1002
03-30 14:14:46.399  3481  4021 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-30 14:14:46.399  3481  3743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1f55a7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102}
03-30 14:14:46.399  3481  4021 D SettingsProvider: ret = -1
03-30 14:14:46.399 10235 10235 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-30 14:14:46.399  5869  5953 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-30 14:14:46.399  3481  4733 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-30 14:14:46.399  3481  4733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:46.399  3481  4733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-30 14:14:46.399  3481  4733 D SettingsProvider: selectionArgs: false
03-30 14:14:46.399  3481  4733 D SettingsProvider: selectionArgs: 1002
03-30 14:14:46.399  3481  4733 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:46.399  3481  4733 D SettingsProvider: ret = -1
,03-30 14:14:46.404  3481  3510 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
03-30 14:14:46.404  3481  3510 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-30 14:14:46.404  3481  3510 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:46.404  3481  3510 D SettingsProvider: selectionArgs: false
03-30 14:14:46.404  3481  3510 D SettingsProvider: selectionArgs: 1002
03-30 14:14:46.404  3481  3510 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:46.404  3481  3510 D SettingsProvider: ret = -1
03-30 14:14:46.404 10235 10235 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-30 14:14:46.404  5869  5953 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-30 14:14:46.409  3481  4041 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1f55a7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102}
,03-30 14:14:46.409  3481  4734 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:46.414 10235 11648 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-30 14:14:46.419  3481  4041 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1f55a7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1402b35b 10419:com.samsung.android.app.watchmanagerstub/u0a121}
,03-30 14:14:46.419 10419 10419 E BluetoothHeadset: BTStateChangeCB is registed
,03-30 14:14:46.419 10419 10419 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-30 14:14:46.419 10419 10419 D GMHFPReceiver: jangil::setProperties()
,03-30 14:14:46.424 10419 10419 D GMHFPReceiver: jangil::printBTStatus()
,03-30 14:14:46.424  3481  4733 D SettingsProvider: name = Wearable0001
03-30 14:14:46.424  3481  4733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:46.424  3481  4733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:46.424  3481  4733 D SettingsProvider: selectionArgs: false
03-30 14:14:46.424  3481  4733 D SettingsProvider: selectionArgs: 10121
03-30 14:14:46.424  3481  4733 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-30 14:14:46.424  3481  4733 D SettingsProvider: ret = -1
03-30 14:14:46.424 10419 10419 D GMHFPReceiver: ::::::::Wearable0001::false
,03-30 14:14:46.424  3481  4679 D SettingsProvider: name = Wearable0002
03-30 14:14:46.424  3481  4679 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:46.424  3481  4679 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:46.424  3481  4679 D SettingsProvider: selectionArgs: false
03-30 14:14:46.424  3481  4679 D SettingsProvider: selectionArgs: 10121
03-30 14:14:46.424  3481  4679 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-30 14:14:46.424  3481  4679 D SettingsProvider: ret = -1
03-30 14:14:46.429 10419 10419 D GMHFPReceiver: ::::::::Wearable0002::false
,03-30 14:14:46.429 10419 10419 D GMHFPReceiver: onServiceConnected() : 1
03-30 14:14:46.429 10419 10419 D GMHFPReceiver: mBluetoothHeadset = true
,03-30 14:14:46.429  3481  4046 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c1f55a7 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1cbe426a 4412:com.google.android.gms.persistent/u0a14},
,03-30 14:14:46.434  5869  6029 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link),
03-30 14:14:46.434  5869  6029 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-30 14:14:46.434  5869  6029 W bt-btif : bta_dm_acl_change(), event : 1
03-30 14:14:46.434  5869  6029 W bt-btif : HAL bt_hal_cbacks->acl_state_changed_cb
03-30 14:14:46.434  5869  5942 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
,03-30 14:14:46.439  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-30 14:14:46.439  3723  3723 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-30 14:14:46.444  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-30 14:14:46.444  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-30 14:14:46.444  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-30 14:14:46.449  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33392cf9 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2a1c8f9f 5869:com.android.bluetooth/1002}
,03-30 14:14:46.454  3481  3961 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:46.459  3723  3723 D KeyguardViewMediator: isGear1: device is not B1!
03-30 14:14:46.459  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d51742
03-30 14:14:46.459  5869  5869 D BtConfig.SecureMode: isSecureModeOn:false
,03-30 14:14:46.459  3481  3743 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-30 14:14:46.464 10235 11652 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-30 14:14:46.464 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-30 14:14:46.464 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-30 14:14:46.469  3481  4733 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-30 14:14:46.469 10235 10235 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-30 14:14:46.469 10235 10235 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-30 14:14:46.469  5869  5869 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-30 14:14:46.474  3481  3743 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:14:46.474  3481  3743 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:14:46.474  3481  3743 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:14:46.474  3481  3743 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:14:46.484 11656 11656 E Zygote  : MountEmulatedStorage()
03-30 14:14:46.489 11656 11656 E Zygote  : v2
03-30 14:14:46.489 11656 11656 I libpersona: KNOX_SDCARD checking this for 10036
03-30 14:14:46.489 11656 11656 I libpersona: KNOX_SDCARD not a persona
,03-30 14:14:46.489 11656 11656 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:14:46.489 11656 11656 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-30 14:14:46.494 11656 11656 E Zygote  : accessInfo : 0
03-30 14:14:46.494  3481  3743 I ActivityManager: Start proc 11656:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
03-30 14:14:46.494 11656 11656 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-30 14:14:46.509 11656 11656 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:14:46.509 11656 11656 D ActivityThread: Added TimaKeyStore provider
,03-30 14:14:46.519  3481  3730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33392cf9 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:46.524 10419 10419 D GMHFPReceiver: onServiceConnected() : 1
,03-30 14:14:46.524 10419 10419 D GMHFPReceiver: mBluetoothHeadset = true
,03-30 14:14:46.529 11656 11656 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-30 14:14:46.619 11656 11656 D HealthConsole: Service for HealthDataConsole is connected
,03-30 14:14:46.624  3481  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33392cf9 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:46.634  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb35930d8 rs_disc_pending=1
03-30 14:14:46.634  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:46.634  5869  6029 W bt-btif : bta_dm_check_av:0
03-30 14:14:46.634  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:46.644 11656 11656 D HealthConsole: Service for HealthDataConsole is connected
,03-30 14:14:46.649  3481  3743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33392cf9 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:46.664  3481  4763 I ActivityManager: Killing 10183:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-30 14:14:46.664  3481  4763 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{33392cf9 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{ae069c4 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-30 14:14:46.689  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=0, deviceClass=0]
,03-30 14:14:46.694  4129  4129 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-30 14:14:46.899  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb35930d8 rs_disc_pending=0
03-30 14:14:46.899  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:46.899  5869  6029 W bt-btif : bta_dm_check_av:0
,03-30 14:14:46.899  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:46.909  5869  6029 W bt-btif : new conn_srvc id:26, app_id:1
03-30 14:14:46.909  5869  6029 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-30 14:14:46.909  5869  6029 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-30 14:14:46.914  5869  5956 E BluetoothRemoteDevices: setRfcommConnected true
,03-30 14:14:46.919 11115 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1536)
03-30 14:14:46.919 11115 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1536)
,03-30 14:14:46.924 11115 11617 D BluetoothSocket: getInputStream(): myUserId = 0
,03-30 14:14:46.929 11115 11617 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-30 14:14:46.934  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:46.934  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:46.934  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:46.934  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:46.939 11115 11617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1537)
,03-30 14:14:46.939 11115 11617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1537)
03-30 14:14:46.939 11115 11617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1536)
,03-30 14:14:46.939 11115 11688 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1537)
,03-30 14:14:46.954  3481  3569 W ProcessCpuTracker: Skipping unknown process pid 11687
,03-30 14:14:46.974  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:46.974 11115 11688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1537)
03-30 14:14:46.974  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:46.974  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:46.974  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:46.974 11115 11688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-30 14:14:46.974 11115 11688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1536)
03-30 14:14:46.974 11115 11688 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1536)
,03-30 14:14:46.974 11115 11688 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1537)
,03-30 14:14:46.974 11115 11115 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-30 14:14:46.974 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-30 14:14:46.974 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:14:46.979 11115 11115 D BluetoothSocket: getInputStream(): myUserId = 0
,03-30 14:14:46.984 11115 11115 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-30 14:14:46.984 11115 11115 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-30 14:14:46.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-30 14:14:46.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:46.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:46.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:46.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:14:46.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:46.984 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:14:46.984  5869  5954 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:46.984  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:46.984  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:14:46.984  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:14:46.989  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-30 14:14:46.989  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:14:46.989  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:14:46.989 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:14:46.989 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:46.994 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:14:46.994 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:46.994 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-30 14:14:46.994 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:46.994 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:46.994 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:46.994 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:46.999  5869 11651 D BtGatt.GattService: registerClient() - UUID=8626afd0-2902-43e3-aa93-3aa323f2db42
,03-30 14:14:47.039  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=8626afd0-2902-43e3-aa93-3aa323f2db42, clientIf=7
,03-30 14:14:47.039 11115 11127 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:47.049  3481  3617 V AlarmManager: waitForAlarm result :4,
,03-30 14:14:47.059  5869  5869 D BtGatt.ScanManager: awakened up at time 255379
,03-30 14:14:47.064  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:47.069  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-30 14:14:47.069  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.079  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 6,
,03-30 14:14:47.079  5869  5954 D BtGatt.AdvertiseManager: message : 0
03-30 14:14:47.079  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:47.079  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:47.084  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:47.084  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:47.089  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:47.089  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:47.089  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-30 14:14:47.094  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:47.094  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-30 14:14:47.094 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:47.094  5869 11650 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:47.094  5869 11651 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-30 14:14:47.094  5869  5957 D BtGatt.ScanManager: filter size is 1
,03-30 14:14:47.094  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 11
,03-30 14:14:47.099  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:47.099  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.099 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:47.099 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:47.099 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:47.099 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:47.099 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:47.099 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:47.099  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:47.099  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:47.099  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.099  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:47.104  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:47.104  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.104  5869 11651 D BtGatt.GattService: registerClient() - UUID=51f2b087-6a1c-4f5a-9946-9b51812a78c7,
,03-30 14:14:47.149  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=51f2b087-6a1c-4f5a-9946-9b51812a78c7, clientIf=6,
03-30 14:14:47.149 11115 11171 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:47.149  5869  5883 D BtGatt.GattService: start scan with filters
,03-30 14:14:47.164  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 9
,03-30 14:14:47.164 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-30 14:14:47.164  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:47.164  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:47.164  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:47.164 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:47.164  5869  5954 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:47.164  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:47.164  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:14:47.169  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:47.169  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.169  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:47.169  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:47.169  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:14:47.169  5869  5957 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
,03-30 14:14:47.169  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-30 14:14:47.169  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:14:47.169  5869 11651 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:14:47.174 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-30 14:14:47.174  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:47.174  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.174 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 14:14:47.174  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:47.174 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:14:47.174  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:47.174 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:47.174 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:47.174 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-30 14:14:47.174 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.174 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.174 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:47.174  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:47.174  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.174  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:47.174  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.179  5869 11650 D BtGatt.GattService: registerClient() - UUID=c76027da-9f49-41e2-b5ca-155875f894f9
,03-30 14:14:47.219  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=c76027da-9f49-41e2-b5ca-155875f894f9, clientIf=7,
,03-30 14:14:47.219 11115 11125 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:47.249  5869 11651 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 7
,03-30 14:14:47.249  5869  5954 D BtGatt.AdvertiseManager: message : 0
03-30 14:14:47.249  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
,03-30 14:14:47.249  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:47.254  5869  5954 D BtGatt.AdvertiseManager: starting advertising
03-30 14:14:47.254  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:47.259  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
03-30 14:14:47.264  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:47.264  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:47.264  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:47.264  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-30 14:14:47.264 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:47.269  5869  5956 D BtGatt.GattService: stopScan() - queue size =1,
,03-30 14:14:47.269  5869  5957 D BtGatt.ScanManager: filter size is 1,
,03-30 14:14:47.269  5869  5880 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-30 14:14:47.269  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 12
03-30 14:14:47.274 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:47.274  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-30 14:14:47.274  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:47.274  5869  5957 D BtGatt.ScanManager: stopping BLe Batch,
03-30 14:14:47.274 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:47.274 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:47.274 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:47.274 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:14:47.274 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:47.274  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:47.274  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.274  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:47.279  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-30 14:14:47.279  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.279  5869  5942 D BtGatt.GattService: current time is 255598042404
03-30 14:14:47.279  5869  5942 D BtGatt.GattService: Batch record : [-122, -124, -58, 60, -95, 109, 1, -128, -67, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-30 14:14:47.279  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:47.279  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:47.284  5869  5956 D BtGatt.GattService: registerClient() - UUID=8f962e27-2c04-402e-8de9-38efa61e7655
,03-30 14:14:47.329  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=8f962e27-2c04-402e-8de9-38efa61e7655, clientIf=6,
03-30 14:14:47.329 11115 11125 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:14:47.329  5869  5880 D BtGatt.GattService: start scan with filters
,03-30 14:14:47.344  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 10
,03-30 14:14:47.344 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
,03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:14:47.344 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:14:47.344  5869  5957 D BtGatt.ScanManager: handling starting scan
,03-30 14:14:47.344  5869  5957 D BtGatt.ScanManager: isFilteringSupported
,03-30 14:14:47.344  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:47.344  5869  5954 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:47.344  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:47.344  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.344  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:47.349  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:14:47.349  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:47.349  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:47.349  5869  5957 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-30 14:14:47.349  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:47.349  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.349  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:14:47.349  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-30 14:14:47.349  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:47.349  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-30 14:14:47.349  5869  5942 D BtGatt.GattService: Client app is not null!
03-30 14:14:47.349  5869  5883 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:14:47.354 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:14:47.354 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 14:14:47.354 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-30 14:14:47.354 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:47.354 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:47.354  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-30 14:14:47.354  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.354 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:47.354 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.354 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:47.354 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:47.354  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:47.354  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.359  5869  5883 D BtGatt.GattService: registerClient() - UUID=c006dd1b-342e-4d07-bf37-ef0c2a9811f5
,03-30 14:14:47.399  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=c006dd1b-342e-4d07-bf37-ef0c2a9811f5, clientIf=7
,03-30 14:14:47.399 11115 11171 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:47.414  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 8
,03-30 14:14:47.414  5869  5954 D BtGatt.AdvertiseManager: message : 0
03-30 14:14:47.414  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:47.414  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:47.414  5869  5954 D BtGatt.AdvertiseManager: starting advertising
03-30 14:14:47.414  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:47.419  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:47.419  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:47.424  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-30 14:14:47.424  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:47.424  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-30 14:14:47.424 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:47.424  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:47.429  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:47.429  5869 11650 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:47.429  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 13
,03-30 14:14:47.429 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:47.429 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:47.429 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:47.429 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:47.429 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:47.429 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:47.429  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:47.429  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.429  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:47.434  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:47.434  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.434  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:47.434  5869  5880 D BtGatt.GattService: registerClient() - UUID=7d137cc7-2989-45f4-a24e-be26449cd837
,03-30 14:14:47.434  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:47.434  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.474  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=7d137cc7-2989-45f4-a24e-be26449cd837, clientIf=6
,03-30 14:14:47.474 11115 11127 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:47.479  5869 11650 D BtGatt.GattService: start scan with filters
,03-30 14:14:47.494  5869 11650 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 11
,03-30 14:14:47.494 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:47.494 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:47.494  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:47.494  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:47.494  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:47.494 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-30 14:14:47.494 11115 11115 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-30 14:14:47.494 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:47.494 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:47.494 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:47.494 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:47.494 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-30 14:14:47.494 11115 11703 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1538)
,03-30 14:14:47.499  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:47.499  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.499  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:47.499  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:47.499  5869  5957 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
,03-30 14:14:47.499  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
03-30 14:14:47.499  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:47.499 11115 11703 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43140
,03-30 14:14:47.499 11115 11703 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-30 14:14:47.499 11115 11703 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 43140 (peer ID: F8:95:C7:87:3C:51)
,03-30 14:14:47.499 11115 11703 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-30 14:14:47.504  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:47.504  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:47.504  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-30 14:14:47.504  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.504  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:47.504  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:47.509 11115 11178 I jxcore-log: INFO testThaliMobileNative: 
03-30 14:14:47.509 11115 11178 I jxcore-log: 
,03-30 14:14:47.509 11115 11178 I jxcore-log: ok 167 Must have listeningPort
03-30 14:14:47.509 11115 11178 I jxcore-log: 
03-30 14:14:47.509 11115 11178 I jxcore-log: ok 168 listeningPort must be a number
03-30 14:14:47.509 11115 11178 I jxcore-log: 
03-30 14:14:47.509 11115 11178 I jxcore-log: ok 169 Connection must have clientPort
03-30 14:14:47.509 11115 11178 I jxcore-log: 
,03-30 14:14:47.514 11115 11178 I jxcore-log: ok 170 clientPort must be a number,
03-30 14:14:47.514 11115 11178 I jxcore-log: 
,03-30 14:14:47.514 11115 11178 I jxcore-log: ok 171 Connection must have serverPort
03-30 14:14:47.514 11115 11178 I jxcore-log: 
,03-30 14:14:47.514 11115 11178 I jxcore-log: ok 172 serverPort must be a number
03-30 14:14:47.514 11115 11178 I jxcore-log: 
,03-30 14:14:47.519 11115 11178 I jxcore-log: ok 173 forward connection must have clientPort == 0,
03-30 14:14:47.519 11115 11178 I jxcore-log: 
03-30 14:14:47.519 11115 11178 I jxcore-log: ok 174 forward connection must have serverPort == 0
03-30 14:14:47.519 11115 11178 I jxcore-log: 
,03-30 14:14:47.529 11115 11178 I jxcore-log: # teardown
03-30 14:14:47.529 11115 11178 I jxcore-log: 
,03-30 14:14:47.619  3481  3730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-30 14:14:47.629  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:14:47.619  3481  3730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0,
,03-30 14:14:47.629  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-30 14:14:47.619  3481  3730 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
03-30 14:14:47.629  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-30 14:14:47.619  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-30 14:14:47.644  2893  4803 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-30 14:14:47.624  3481  3730 D BatteryService: stay LED for fully charged
03-30 14:14:47.624  3481  3481 I MotionRecognitionService: Plugged
,03-30 14:14:47.624  3481  3481 D MotionRecognitionService:   cableConnection= 1
,03-30 14:14:47.624  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-30 14:14:47.624  3481  3481 D MotionRecognitionService: skip setTransmitPower. ,
,03-30 14:14:47.659  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-30 14:14:47.659  5869  5977 D HeadsetStateMachine: Disconnected process message: 10,
,03-30 14:14:47.664  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-30 14:14:47.664  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:47.664  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:47.664  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:48.219  3481  6076 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:12), CUR = 39, LCD = 0
,03-30 14:14:48.509  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:48.524  5869  5869 D BtGatt.ScanManager: awakened up at time 256840
,03-30 14:14:48.529  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:48.534  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:48.534  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:48.534  5869  5942 D BtGatt.GattService: current time is 256851149029,
03-30 14:14:48.534  5869  5942 D BtGatt.GattService: Batch record : [104, 110, -90, 23, 41, 79, 1, -128, -87, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -37, -31, 9, 69, 1, 116, 1, -128, -67, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-30 14:14:48.534  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-30 14:14:48.534  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:14:48.534  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:48.534  5869  5942 D ScanRecord: parseFromBytes,
,03-30 14:14:48.534  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=74:01:45:09:E1:DB, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-67, mTimestampNanos=256601345779},
03-30 14:14:48.534  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:48.534  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=4F:29:17:A6:6E:68, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-87, mTimestampNanos=256451345779},
03-30 14:14:48.534  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:48.534 11115 11171 D ScanRecord: parseFromBytes
,03-30 14:14:48.534 11115 11171 D ScanRecord: parseFromBytes
03-30 14:14:48.534 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-30 14:14:48.534 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
,03-30 14:14:49.549  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:49.564  5869  5869 D BtGatt.ScanManager: awakened up at time 257880
,03-30 14:14:49.569  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:49.574  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-30 14:14:49.574  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:49.574  5869  5942 D BtGatt.GattService: current time is 257893247238
03-30 14:14:49.574  5869  5942 D BtGatt.GattService: Batch record : [104, 110, -90, 23, 41, 79, 1, -128, -84, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-30 14:14:49.574  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:49.574  5869  5942 D ScanRecord: parseFromBytes,
03-30 14:14:49.579  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=4F:29:17:A6:6E:68, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=257443597529},
,03-30 14:14:49.579  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:49.579 11115 11125 D ScanRecord: parseFromBytes,
03-30 14:14:49.579 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
,03-30 14:14:50.594  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:50.604  5869  5869 D BtGatt.ScanManager: awakened up at time 258924
03-30 14:14:50.609  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:50.614  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:50.614  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:50.824  5869  6029 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:50.824  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-30 14:14:50.824  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
03-30 14:14:50.824  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-30 14:14:50.829  5869  6029 D IOP_DB_BT: db_query_execute: result 1
03-30 14:14:50.829  5869  6029 D IOP_DB_BT: db_query_create: id EnforceSlaveRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:50.829  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
,03-30 14:14:50.829  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975,
,03-30 14:14:50.829  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *,
,03-30 14:14:50.829  5869  6029 D IOP_DB_BT: db_query_execute: result 1,
,03-30 14:14:51.004  5869  6029 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:51.004  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-30 14:14:51.004  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:8975
,03-30 14:14:51.004  5869  6029 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
,03-30 14:14:51.009  5869  6029 D IOP_DB_BT: db_query_execute: result 1
03-30 14:14:51.009  5869  6029 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:51.009  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:51.009  5869  6029 W bt-btif : bta_dm_acl_change(), event : 0
03-30 14:14:51.009  5869  6029 W bt-btif : info:x10
03-30 14:14:51.009  5869  5942 D         : remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
03-30 14:14:51.009  5869  5942 E BluetoothRemoteDevices: aclStateChangeCallback: State:Connected to Device:F8:CF:C5:D9:E5:XX
03-30 14:14:51.014  5869  6029 W bt-btif : bta_dm_acl_change(), event : 2
03-30 14:14:51.034  3723  3723 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_CONNECTED
03-30 14:14:51.034  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-30 14:14:51.054  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
,03-30 14:14:51.054  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_CONNECTED
,03-30 14:14:51.054  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_CONNECTED
,03-30 14:14:51.064  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{272fe025 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:51.069  3723  3723 D KeyguardViewMediator: isGear1: device is not B1!
03-30 14:14:51.064  3481  3958 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:51.074 10235 11728 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,03-30 14:14:51.079  3481  3743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{272fe025 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:51.084 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,03-30 14:14:51.089  3481  3831 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{272fe025 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:51.089 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
03-30 14:14:51.089 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage CONNECTION_COMPLETE
,03-30 14:14:51.104  3481  3958 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{272fe025 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{11bf0353 10157:com.android.settings/1000}
,03-30 14:14:51.104 10157 10157 D BluetoothNotiBroadcastReceiver: onReceive
,03-30 14:14:51.109  3481  3958 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{272fe025 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{ae069c4 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-30 14:14:51.119  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=0, deviceClass=0]
,03-30 14:14:51.124  4129  4129 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-30 14:14:51.199  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb359329c rs_disc_pending=0
03-30 14:14:51.199  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:51.199  5869  6029 W bt-btif : bta_dm_check_av:0
03-30 14:14:51.199  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:51.214  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-30 14:14:51.434  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb35930d8 rs_disc_pending=1
03-30 14:14:51.434  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:51.434  5869  6029 W bt-btif : bta_dm_check_av:0
,03-30 14:14:51.434  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14),
,03-30 14:14:51.594  5869  5942 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-30 14:14:51.599  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-30 14:14:51.599  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-30 14:14:51.604  5869  5942 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,03-30 14:14:51.609  3481  4046 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-30 14:14:51.614  5869  5942 E bt-btif : check_cod: remote_cod = 0x5a020c
03-30 14:14:51.614  5869  5942 W bt-btif : btif_dm_ssp_reply: accept=1
,03-30 14:14:51.624  3481  3617 V AlarmManager: waitForAlarm result :4
03-30 14:14:51.629  3723  3723 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
,03-30 14:14:51.629  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-30 14:14:51.629  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED,
03-30 14:14:51.629  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED,
03-30 14:14:51.629  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,03-30 14:14:51.629  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-30 14:14:51.629  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-30 14:14:51.644  5869  5953 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11,
03-30 14:14:51.649  5869  5953 D BtConfig.SecureMode: isSecureModeOn:false
03-30 14:14:51.649  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3689ce08 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{11bf0353 10157:com.android.settings/1000}
,03-30 14:14:51.649  5869  5953 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-30 14:14:51.659  3481  4733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3689ce08 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102},
03-30 14:14:51.649 10157 10157 D BluetoothNotiBroadcastReceiver: onReceive
,03-30 14:14:51.664  3481  3961 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-30 14:14:51.649  5869  5942 W bt-btif : btif_dm_auth_cmpl_evt
,03-30 14:14:51.649  5869  5942 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
03-30 14:14:51.669 10235 10235 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-30 14:14:51.674  3723  4706 D BluetoothTile:  handleUpdatestate:false name:null
,03-30 14:14:51.674 10235 10235 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 11
03-30 14:14:51.674  5869  5942 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
03-30 14:14:51.674  5869  5953 D BluetoothAdapterProperties: Failed to remove device: F8:CF:C5:D9:E5:61
,03-30 14:14:51.684  3481  4763 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3689ce08 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102}
,03-30 14:14:51.684  3481  4679 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-30 14:14:51.689 10235 11741 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-30 14:14:51.689  5869  5953 I BluetoothBondStateMachine: Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,03-30 14:14:51.689  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-30 14:14:51.689  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-30 14:14:51.689  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-30 14:14:51.689  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-30 14:14:51.689  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-30 14:14:51.689  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-30 14:14:51.694  3723  3723 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-30 14:14:51.694  3481  4733 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:51.694  3723  4706 D BluetoothTile:  handleUpdatestate:false name:null
,03-30 14:14:51.699  5869  5953 D BtConfig.SecureMode: isSecureModeOn:false
,03-30 14:14:51.699  5869  5953 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@35c93cb9
03-30 14:14:51.704 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
03-30 14:14:51.704  3481  4679 D SettingsProvider: name = bluetooth_input_device_priority_F8:CF:C5:D9:E5:61
03-30 14:14:51.704  3481  4679 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:51.704  3481  4679 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:51.704  3481  4679 D SettingsProvider: selectionArgs: false
03-30 14:14:51.704  3481  4679 D SettingsProvider: selectionArgs: 1002
03-30 14:14:51.704  3481  4679 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-30 14:14:51.704  3481  4679 D SettingsProvider: ret = -1
03-30 14:14:51.704  5869  5953 D HidService: Saved priority F8:CF:C5:D9:E5:61 = -1
,03-30 14:14:51.704  3481  3510 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:CF:C5:D9:E5:61
03-30 14:14:51.704  3481  3510 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:51.704  3481  3510 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:51.704  3481  3510 D SettingsProvider: selectionArgs: false
03-30 14:14:51.704  3481  3510 D SettingsProvider: selectionArgs: 1002
03-30 14:14:51.704  3481  3510 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-30 14:14:51.704  3481  3510 D SettingsProvider: ret = -1
,03-30 14:14:51.709  3481  4734 D SettingsProvider: name = bluetooth_headset_priority_F8:CF:C5:D9:E5:61,
03-30 14:14:51.709  3481  4734 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:51.709  3481  3743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3689ce08 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1402b35b 10419:com.samsung.android.app.watchmanagerstub/u0a121}
03-30 14:14:51.709  3481  4734 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-30 14:14:51.709  3481  3730 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-30 14:14:51.709  3481  4734 D SettingsProvider: selectionArgs: false
03-30 14:14:51.709  3481  4734 D SettingsProvider: selectionArgs: 1002
03-30 14:14:51.709  3481  4734 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-30 14:14:51.709  3481  4734 D SettingsProvider: ret = -1
03-30 14:14:51.709  5869  5953 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-30 14:14:51.709 10419 10419 E BluetoothHeadset: BTStateChangeCB is registed
,03-30 14:14:51.714 10419 10419 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-30 14:14:51.714 10419 10419 D GMHFPReceiver: jangil::setProperties()
,03-30 14:14:51.714 10235 11742 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-30 14:14:51.714 10419 10419 D GMHFPReceiver: jangil::printBTStatus()
03-30 14:14:51.719 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-30 14:14:51.719  3481  3831 D SettingsProvider: name = Wearable0001
03-30 14:14:51.719  3481  3831 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:51.719  3481  3831 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:51.719  3481  3831 D SettingsProvider: selectionArgs: false
03-30 14:14:51.719  3481  3831 D SettingsProvider: selectionArgs: 10121
03-30 14:14:51.719  3481  3831 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:51.719  3481  3831 D SettingsProvider: ret = -1
,03-30 14:14:51.719 10419 10419 D GMHFPReceiver: ::::::::Wearable0001::false
03-30 14:14:51.719 10235 11742 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-30 14:14:51.719  3481  4041 D SettingsProvider: name = Wearable0002
03-30 14:14:51.719  3481  4041 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:51.719  3481  4041 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-30 14:14:51.719  3481  4041 D SettingsProvider: selectionArgs: false
03-30 14:14:51.719  3481  4041 D SettingsProvider: selectionArgs: 10121
03-30 14:14:51.719  3481  4041 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:51.719  3481  4041 D SettingsProvider: ret = -1
,03-30 14:14:51.719 10419 10419 D GMHFPReceiver: ::::::::Wearable0002::false
,03-30 14:14:51.729  3481  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3689ce08 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1cbe426a 4412:com.google.android.gms.persistent/u0a14}
,03-30 14:14:51.734  5869  5869 D BtGatt.ScanManager: awakened up at time 260050
,03-30 14:14:51.734  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:51.734  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:51.734  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:51.739  3481  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16f1c2b4 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{11bf0353 10157:com.android.settings/1000}
,03-30 14:14:51.739 10157 10157 D BluetoothNotiBroadcastReceiver: onReceive
,03-30 14:14:51.744  3481  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16f1c2b4 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102},
,03-30 14:14:51.749 10235 10235 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-30 14:14:51.749 10235 10235 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 6 state is 10
,03-30 14:14:51.754  3481  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16f1c2b4 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{f086ea2 10235:com.sec.android.automotive.drivelink/u0a102}
,03-30 14:14:51.754  3481  4731 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:51.764 10235 11743 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-30 14:14:51.764  3481  4021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16f1c2b4 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1402b35b 10419:com.samsung.android.app.watchmanagerstub/u0a121}
,03-30 14:14:51.769 10419 10419 E BluetoothHeadset: BTStateChangeCB is registed
,03-30 14:14:51.769 10419 10419 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-30 14:14:51.769 10419 10419 D GMHFPReceiver: jangil::setProperties()
,03-30 14:14:51.769 10419 10419 D GMHFPReceiver: jangil::printBTStatus()
03-30 14:14:51.769  3481  4763 D SettingsProvider: name = Wearable0001
,03-30 14:14:51.769  3481  4763 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:51.769  3481  4763 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:51.769  3481  4763 D SettingsProvider: selectionArgs: false
03-30 14:14:51.769  3481  4763 D SettingsProvider: selectionArgs: 10121
03-30 14:14:51.769  3481  4763 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:51.774  3481  4763 D SettingsProvider: ret = -1
03-30 14:14:51.774 10419 10419 D GMHFPReceiver: ::::::::Wearable0001::false
,03-30 14:14:51.774  3481  4733 D SettingsProvider: name = Wearable0002
03-30 14:14:51.774  3481  4733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-30 14:14:51.774  3481  4733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-30 14:14:51.774  3481  4733 D SettingsProvider: selectionArgs: false
03-30 14:14:51.774  3481  4733 D SettingsProvider: selectionArgs: 10121
03-30 14:14:51.774  3481  4733 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-30 14:14:51.774  3481  4733 D SettingsProvider: ret = -1
,03-30 14:14:51.774 10419 10419 D GMHFPReceiver: ::::::::Wearable0002::false
,03-30 14:14:51.779  3481  3743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{16f1c2b4 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1cbe426a 4412:com.google.android.gms.persistent/u0a14}
,03-30 14:14:51.814 10419 10419 D GMHFPReceiver: onServiceConnected() : 1
,03-30 14:14:51.814 10419 10419 D GMHFPReceiver: mBluetoothHeadset = true
,03-30 14:14:51.849  5869  6029 W bt-btif : new conn_srvc id:26, app_id:255
03-30 14:14:51.849  5869  6029 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-30 14:14:51.849  5869  6029 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-30 14:14:51.849 11115 11610 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3bb3f7c9
,03-30 14:14:51.854  5869  5956 E BluetoothRemoteDevices: setRfcommConnected true
,03-30 14:14:51.854 11115 11610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-30 14:14:51.859 11115 11610 D BluetoothSocket: getInputStream(): myUserId = 0
,03-30 14:14:51.864 11115 11610 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-30 14:14:51.864 11115 11610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1539)
03-30 14:14:51.864 11115 11610 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f95eece, channel: 6, state: LISTENING
,03-30 14:14:51.864 11115 11610 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f95eece, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@678e22a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32eda1efmSocket: android.net.LocalSocket@45ef4fc impl:android.net.LocalSocketImpl@1fb4785 fd:FileDescriptor[93]
,03-30 14:14:51.864 11115 11610 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@45ef4fc impl:android.net.LocalSocketImpl@1fb4785 fd:FileDescriptor[93]
03-30 14:14:51.864 11115 11610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:14:51.864 11115 11745 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1539)
03-30 14:14:51.869 10419 10419 D GMHFPReceiver: onServiceConnected() : 1
,03-30 14:14:51.869 10419 10419 D GMHFPReceiver: mBluetoothHeadset = true
03-30 14:14:51.874 11115 11610 D BluetoothSocket: bindListen(): myUserId = 0
03-30 14:14:51.874 11115 11610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:51.879 11115 11610 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,03-30 14:14:51.879 11115 11610 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:14:51.879 11115 11610 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-30 14:14:51.879 11115 11610 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3da629da
03-30 14:14:51.879 11115 11610 D BluetoothSocket: channel: 6
,03-30 14:14:51.879 11115 11610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:51.939  5869  6029 W bt-btif : dm_pm_timer expires,
03-30 14:14:51.939  5869  6029 W bt-btif : dm_pm_timer expires 0
03-30 14:14:51.939  5869  6029 W bt-btif : proc dm_pm_timer expires
,03-30 14:14:52.124  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb359329c rs_disc_pending=1
03-30 14:14:52.124  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:52.124  5869  6029 W bt-btif : bta_dm_check_av:0
,03-30 14:14:52.124  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:52.134  3481  3569 W ProcessCpuTracker: Skipping unknown process pid 11746
,03-30 14:14:52.379  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb359329c rs_disc_pending=0
03-30 14:14:52.379  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:52.379  5869  6029 W bt-btif : bta_dm_check_av:0
,03-30 14:14:52.384  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14),
,03-30 14:14:52.449  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:52.449  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:52.449  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:52.449  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:52.454 11115 11745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1539),
,03-30 14:14:52.464 11115 11745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:CF:C5:D9:E5:61]
,03-30 14:14:52.464  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:52.469  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:52.469  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:cf:c5:d9:e5:61
03-30 14:14:52.469  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:52.469 11115 11745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1539)
,03-30 14:14:52.469 11115 11745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1539
,03-30 14:14:52.469 11115 11745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1539)
,03-30 14:14:52.474 11115 11745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:CF:C5:D9:E5:61]
,03-30 14:14:52.474 11115 11115 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:CF:C5:D9:E5:61]
03-30 14:14:52.474 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:CF:C5:D9:E5:61]
03-30 14:14:52.474 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-30 14:14:52.479 11115 11115 D BluetoothSocket: getInputStream(): myUserId = 0
,03-30 14:14:52.484 11115 11745 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1539)
,03-30 14:14:52.489 11115 11115 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-30 14:14:52.489 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:CF:C5:D9:E5:61], created successfully
,03-30 14:14:52.489 11115 11115 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-30 14:14:52.494 11115 11749 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1540)
,03-30 14:14:52.494  2873  3464 D EnterpriseController: netId is 0
03-30 14:14:52.494  2873  3464 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-30 14:14:52.504 11115 11749 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 43042
03-30 14:14:52.504 11115 11749 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-30 14:14:52.504 11115 11749 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 14:14:52.504 11115 11749 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 14:14:52.504 11115 11749 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1540)
03-30 14:14:52.504 11115 11749 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1540)
03-30 14:14:52.504 11115 11753 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1541, name: Sender)
03-30 14:14:52.504 11115 11754 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1542, name: Receiver)
,03-30 14:14:52.649 11115 11753 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1541, thread name: Sender)
03-30 14:14:52.649 11115 11753 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-30 14:14:52.649 11115 11753 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:CF:C5:D9:E5:61] disconnected: Input stream got -1 on read
03-30 14:14:52.649 11115 11753 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1540
03-30 14:14:52.649 11115 11753 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1540)
,03-30 14:14:52.649 11115 11753 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22464e8, channel: 6, state: CONNECTED
03-30 14:14:52.654 11115 11753 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22464e8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33add701, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@44d09a6mSocket: android.net.LocalSocket@2a21dfe7 impl:android.net.LocalSocketImpl@164ee794 fd:FileDescriptor[117],
03-30 14:14:52.654 11115 11753 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a21dfe7 impl:android.net.LocalSocketImpl@164ee794 fd:FileDescriptor[117]
,03-30 14:14:52.654 11115 11753 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22464e8, channel: 6, state: CLOSED,
03-30 14:14:52.654 11115 11753 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22464e8, channel: 6, state: CLOSED
,03-30 14:14:52.659 11115 11753 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
03-30 14:14:52.659 11115 11753 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-30 14:14:52.659 11115 11753 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1542
03-30 14:14:52.659 11115 11753 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-30 14:14:52.659 11115 11753 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1541
,03-30 14:14:52.659 11115 11753 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1540)
03-30 14:14:52.659 11115 11753 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1540)
03-30 14:14:52.659 11115 11753 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-30 14:14:52.664 11115 11754 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1542, thread name: Receiver): bt socket closed, read return: -1,
,03-30 14:14:52.664 11115 11754 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1542, name: Receiver),
03-30 14:14:52.664 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:14:52.664 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:14:52.664 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:14:52.664 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:14:52.669 11115 11753 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1541, name: Sender)
,03-30 14:14:52.674  5869  5883 D BtGatt.GattService: stopScan() - queue size =1,
,03-30 14:14:52.674  5869  5957 D BtGatt.ScanManager: filter size is 1,
03-30 14:14:52.674  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 14
03-30 14:14:52.674  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:52.674  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:52.674  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:52.674  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:52.674  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-30 14:14:52.674  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:52.679  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-30 14:14:52.679  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-30 14:14:52.684  5869 11650 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:52.684 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:52.684 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:52.684 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-30 14:14:52.684 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:14:52.684 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:14:52.684 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:52.684 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:14:52.684 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-30 14:14:52.684 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:14:52.694 11115 11178 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-30 14:14:52.694 11115 11178 I jxcore-log: 
,03-30 14:14:52.694 11115 11178 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-30 14:14:52.694 11115 11178 I jxcore-log: 
,03-30 14:14:52.699 11115 11178 I jxcore-log: ok 175 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:14:52.699 11115 11178 I jxcore-log: 
,03-30 14:14:52.699 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:14:52.699 11115 11178 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-30 14:14:52.699 11115 11178 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1538)
,03-30 14:14:52.699 11115 11178 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1538)
03-30 14:14:52.699 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a9fe23d, channel: 7, state: CONNECTED
,03-30 14:14:52.704 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a9fe23d, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25301a32, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32229383mSocket: android.net.LocalSocket@3bfce900 impl:android.net.LocalSocketImpl@fad6539 fd:FileDescriptor[115]
03-30 14:14:52.704 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3bfce900 impl:android.net.LocalSocketImpl@fad6539 fd:FileDescriptor[115]
,03-30 14:14:52.704 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a9fe23d, channel: 7, state: CLOSED
,03-30 14:14:52.704 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a9fe23d, channel: 7, state: CLOSED
03-30 14:14:52.704 11115 11178 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-30 14:14:52.704 11115 11178 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1538)
03-30 14:14:52.704 11115 11178 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1538)
,03-30 14:14:52.704 11115 11703 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1538)
,03-30 14:14:52.709 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 14:14:52.709 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 14:14:52.709 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:14:52.709 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:14:52.709 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4c1a77e, channel: 6, state: LISTENING
,03-30 14:14:52.709 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4c1a77e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3da629da, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@10f0e4dfmSocket: android.net.LocalSocket@3fc7952c impl:android.net.LocalSocketImpl@3761bf5 fd:FileDescriptor[118]
03-30 14:14:52.709 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fc7952c impl:android.net.LocalSocketImpl@3761bf5 fd:FileDescriptor[118]
,03-30 14:14:52.709 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 14:14:52.709 11115 11610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:14:52.709 11115 11610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:14:52.709 11115 11610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:14:52.714 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:14:52.714 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:14:52.714 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-30 14:14:52.714 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-30 14:14:52.714 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 14:14:52.714 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:14:52.714 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:14:52.714 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:14:52.714 11115 11178 D BluetoothLeScanner: could not find callback wrapper,
03-30 14:14:52.714 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:14:52.714 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-30 14:14:52.719  5869  5954 D BtGatt.AdvertiseManager: message : 1,
,03-30 14:14:52.719  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-30 14:14:52.719  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-30 14:14:52.719  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
,03-30 14:14:52.724  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-30 14:14:52.724  5869  5942 D BtGatt.GattService: Client app is not null!
03-30 14:14:52.724  5869  5883 D BtGatt.GattService: unregisterClient() - clientIf=7
03-30 14:14:52.729 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:52.729 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:52.734 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-30 14:14:52.734 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:14:52.734 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:14:52.734 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:52.734 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:14:52.734 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:14:52.734 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:14:52.734 11115 11178 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 14:14:52.734 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:52.734 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:14:52.734 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:14:52.734 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:14:52.734 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:14:52.734 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:14:52.734 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:14:52.734 11115 11178 I jxcore-log: 
,03-30 14:14:52.739 11115 11178 I jxcore-log: ok 176 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:14:52.739 11115 11178 I jxcore-log: 
,03-30 14:14:52.739 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:14:52.744 11115 11178 I jxcore-log: # setup
03-30 14:14:52.744 11115 11178 I jxcore-log: 
,03-30 14:14:52.744 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-30 14:14:52.749 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:52.749 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:14:52.749 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:14:52.749 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:14:52.754 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:52.754 11115 11178 I jxcore-log: 
,03-30 14:14:52.754 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:14:52.754 11115 11178 I jxcore-log: 
,03-30 14:14:53.179  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb359329c rs_disc_pending=1
03-30 14:14:53.179  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:53.179  5869  6029 W bt-btif : bta_dm_check_av:0
03-30 14:14:53.184  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:53.214  5869  6029 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
03-30 14:14:53.214  5869  6029 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-30 14:14:53.564  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb35930d8 rs_disc_pending=0
03-30 14:14:53.564  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:53.564  5869  6029 W bt-btif : bta_dm_check_av:0
,03-30 14:14:53.564  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:53.604  5869  6029 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-30 14:14:53.679 11115 11178 I jxcore-log: # 41. Can shift large amounts of data
03-30 14:14:53.679 11115 11178 I jxcore-log: 
,03-30 14:14:54.119 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 41629, start advertisements: true
,03-30 14:14:54.119 11115 11178 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-30 14:14:54.119 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-30 14:14:54.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:54.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:54.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:14:54.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:14:54.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:14:54.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:14:54.124 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:14:54.129 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:54.134 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:14:54.134 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:14:54.134 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:14:54.144 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:14:54.144 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:54.144 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:54.144 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:54.149  5869  5880 D BtGatt.GattService: registerClient() - UUID=61b719b8-557b-486f-8af3-926cedd1b098
,03-30 14:14:54.189  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=61b719b8-557b-486f-8af3-926cedd1b098, clientIf=6
,03-30 14:14:54.189 11115 11125 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:54.189  5869  5883 D BtGatt.GattService: start scan with filters
,03-30 14:14:54.204  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 12
,03-30 14:14:54.204 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:54.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:54.204 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:14:54.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:14:54.204 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:54.204  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:54.204  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:54.204  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:54.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:54.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:54.204 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:14:54.204 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:54.204 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:54.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:54.204 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:54.204  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:54.204  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:54.204  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:54.204  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:54.204  5869  5957 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
,03-30 14:14:54.209  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:54.209  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:54.209  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:54.209  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:54.209  5869  5880 D BtGatt.GattService: registerClient() - UUID=98b2858d-11de-47ca-81f5-59685da08e54
03-30 14:14:54.209  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:54.209  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:54.209  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:54.209  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:54.249  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=98b2858d-11de-47ca-81f5-59685da08e54, clientIf=7
,03-30 14:14:54.249 11115 11171 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:54.274  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 9
,03-30 14:14:54.274  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:54.279  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:54.284  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:54.289  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:54.294  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:54.309  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:54.319  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:54.329  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:54.329  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
,03-30 14:14:54.334  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0,
,03-30 14:14:54.339 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-30 14:14:54.339 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:14:54.354 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-30 14:14:54.364 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:14:54.364 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
,03-30 14:14:54.364 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:14:54.374 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-30 14:14:54.379 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-30 14:14:54.379 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
,03-30 14:14:54.379 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-30 14:14:54.384 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 14:14:54.384 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:54.384 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-30 14:14:54.384 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:14:54.384 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-30 14:14:54.384 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:14:54.384 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:54.384 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:14:54.384 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
,03-30 14:14:54.384 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-30 14:14:54.384 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-30 14:14:54.384 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:14:54.389 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK,
03-30 14:14:54.394 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:54.394 11115 11178 I jxcore-log: 
03-30 14:14:54.394 11115 11178 I jxcore-log: ok 177 Can call startUpdateAdvertisingAndListening without error
,03-30 14:14:54.394 11115 11178 I jxcore-log: 
,03-30 14:14:54.409 11115 11773 D BluetoothSocket: bindListen(): myUserId = 0,
03-30 14:14:54.409 11115 11773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:54.414 11115 11773 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
03-30 14:14:54.414 11115 11773 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:14:54.414 11115 11773 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-30 14:14:54.414 11115 11773 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16d98271
03-30 14:14:54.414 11115 11773 D BluetoothSocket: channel: 6
03-30 14:14:54.414 11115 11773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:14:54.419 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 41629, start advertisements: false
,03-30 14:14:54.424 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:14:54.424 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-30 14:14:54.424 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:14:54.424 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:14:54.429 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:14:54.429 11115 11178 I jxcore-log: 
,03-30 14:14:54.429 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:14:54.429 11115 11178 I jxcore-log: 
,03-30 14:14:54.429 11115 11178 I jxcore-log: ok 178 Can call startListeningForAdvertisements without error
03-30 14:14:54.429 11115 11178 I jxcore-log: 
,03-30 14:14:54.629  5869  6029 W bt-rfcomm: rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
03-30 14:14:54.629  5869  6029 W bt-rfcomm: RFCOMM_DisconnectInd LCID:0x44
,03-30 14:14:55.209  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:55.229  5869  5869 D BtGatt.ScanManager: awakened up at time 263545
,03-30 14:14:55.229  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-30 14:14:55.234  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:55.234  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:14:55.234  5869  5942 D BtGatt.GattService: current time is 263554587655
03-30 14:14:55.239  5869  5942 D BtGatt.GattService: Batch record : [72, 84, 87, -53, -86, 69, 1, -128, -55, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 22, 64, -99, -35, 23, 89, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
,03-30 14:14:55.239  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
,03-30 14:14:55.239  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:55.239  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-30 14:14:55.239  5869  5942 D ScanRecord: parseFromBytes,
03-30 14:14:55.239  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=59:17:DD:9D:40:16, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-72, mTimestampNanos=263555380072},
,03-30 14:14:55.239  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:55.239  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=45:AA:CB:57:54:48, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=263405380072}
03-30 14:14:55.239  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,03-30 14:14:55.244 11115 11125 D ScanRecord: parseFromBytes,
03-30 14:14:55.244 11115 11125 D ScanRecord: parseFromBytes
03-30 14:14:55.244 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-30 14:14:55.244 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61], added - the peer count is 2
03-30 14:14:55.244 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-30 14:14:55.244 11115 11115 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: 
03-30 14:14:55.269 11115 11178 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-30 14:14:55.269 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-30 14:14:55.274 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,03-30 14:14:55.274 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-30 14:14:55.274 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-30 14:14:55.274 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-30 14:14:55.274 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-30 14:14:55.274 11115 11178 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-30 14:14:55.274 11115 11776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1544)
,03-30 14:14:55.284 11115 11776 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-30 14:14:55.284 11115 11776 D BluetoothSocket: connect(): myUserId = 0
03-30 14:14:55.284 11115 11776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:14:55.284  5869 11650 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-30 14:14:55.284 11115 11776 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,03-30 14:14:55.674  5869  6029 W bt-sdp  : process_service_search_attr_rsp
,03-30 14:14:56.264  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:56.274  5869  5869 D BtGatt.ScanManager: awakened up at time 264590
,03-30 14:14:56.274  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-30 14:14:56.284  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:56.284  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:56.284  5869  5942 D BtGatt.GattService: current time is 264601474488
03-30 14:14:56.284  5869  5942 D BtGatt.GattService: Batch record : [72, 84, 87, -53, -86, 69, 1, -128, -55, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 22, 64, -99, -35, 23, 89, 1, -128, -73, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-30 14:14:56.284  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:56.284  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:56.284  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:56.284  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:56.289  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=59:17:DD:9D:40:16, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=264302064447}
03-30 14:14:56.289  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:56.289  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=45:AA:CB:57:54:48, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=264552064447}
,03-30 14:14:56.289  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:56.289 11115 11171 D ScanRecord: parseFromBytes
,03-30 14:14:56.289 11115 11171 D ScanRecord: parseFromBytes
03-30 14:14:56.289 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-30 14:14:56.289 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-30 14:14:56.799  5869  6029 W bt-btif : new conn_srvc id:26, app_id:1
,03-30 14:14:56.809  5869 11651 E BluetoothRemoteDevices: setRfcommConnected true
,03-30 14:14:56.824 11115 11776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1544),
03-30 14:14:56.824 11115 11776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1544)
,03-30 14:14:56.829 11115 11776 D BluetoothSocket: getInputStream(): myUserId = 0
,03-30 14:14:56.834 11115 11776 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-30 14:14:56.839 11115 11776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1545)
,03-30 14:14:56.839 11115 11776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1545)
03-30 14:14:56.839 11115 11776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1544)
,03-30 14:14:56.844 11115 11785 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1545)
,03-30 14:14:57.289  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:57.299  5869  5869 D BtGatt.ScanManager: awakened up at time 265615
,03-30 14:14:57.299  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:57.309  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:57.309  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.309  5869  5942 D BtGatt.GattService: current time is 265626492739
03-30 14:14:57.309  5869  5942 D BtGatt.GattService: Batch record : [72, 84, 87, -53, -86, 69, 1, -128, -54, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 22, 64, -99, -35, 23, 89, 1, -128, -73, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:14:57.309  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:57.309  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:14:57.309  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:57.309  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:57.314  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=59:17:DD:9D:40:16, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-73, mTimestampNanos=264827136822}
03-30 14:14:57.314  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:57.314  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=45:AA:CB:57:54:48, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=264877136822}
03-30 14:14:57.314  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:14:57.314 11115 11127 D ScanRecord: parseFromBytes
,03-30 14:14:57.314 11115 11127 D ScanRecord: parseFromBytes
03-30 14:14:57.314 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-30 14:14:57.314 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-30 14:14:57.384  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb35930d8 rs_disc_pending=1
03-30 14:14:57.384  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:14:57.384  5869  6029 W bt-btif : bta_dm_check_av:0
03-30 14:14:57.384  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:14:57.389  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:57.389  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:57.389  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:57.394  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:57.424  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:57.424 11115 11785 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1545)
03-30 14:14:57.424  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:57.424  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:57.429  5869  6029 D IOP_DB_BT: db_query: result 1,
03-30 14:14:57.429 11115 11785 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51],
03-30 14:14:57.429 11115 11785 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1544)
03-30 14:14:57.429 11115 11785 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1544),
03-30 14:14:57.434 11115 11115 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51],
,03-30 14:14:57.434 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51],
,03-30 14:14:57.434 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2,
03-30 14:14:57.439 11115 11785 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1545)
03-30 14:14:57.459 11115 11115 D BluetoothSocket: getInputStream(): myUserId = 0
03-30 14:14:57.489 11115 11115 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-30 14:14:57.489 11115 11115 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings,
03-30 14:14:57.489 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-30 14:14:57.499 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-30 14:14:57.499 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:57.499 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:57.499 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:14:57.499 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:57.499 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:14:57.504  5869  5954 D BtGatt.AdvertiseManager: message : 1
,03-30 14:14:57.504  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7,
,03-30 14:14:57.504  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
,03-30 14:14:57.504  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-30 14:14:57.509  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-30 14:14:57.509  5869  5942 D BtGatt.GattService: Client app is not null!
03-30 14:14:57.514  5869  5880 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-30 14:14:57.519 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:57.519 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:57.519 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:14:57.519 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:14:57.519 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:57.519 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:57.519 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:57.519 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:57.519 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-30 14:14:57.534  5869 11651 D BtGatt.GattService: registerClient() - UUID=7da0d1dc-d5a3-4a84-8a83-dce33dde595e,
,03-30 14:14:57.574  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=7da0d1dc-d5a3-4a84-8a83-dce33dde595e, clientIf=7
03-30 14:14:57.574 11115 11171 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:57.609  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 10
,03-30 14:14:57.609  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:57.614  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:57.614  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:57.619  5869  5954 D BtGatt.AdvertiseManager: starting advertising
03-30 14:14:57.619  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:57.629  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:57.634  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
03-30 14:14:57.639  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-30 14:14:57.639  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:57.639  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-30 14:14:57.639 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:57.644  5869 11650 D BtGatt.GattService: stopScan() - queue size =1,
03-30 14:14:57.644  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:57.644  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 15
,03-30 14:14:57.644  5869 11651 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:14:57.644  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:57.644  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:57.644  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:57.649 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:57.649 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-30 14:14:57.649 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:57.649 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:57.649 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:57.649 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:57.649  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:57.649  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:57.649  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:57.649  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:57.654  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:57.654  5869  5956 D BtGatt.GattService: registerClient() - UUID=9101c6fd-c6d1-411c-85fc-33c425f49c8b
,03-30 14:14:57.694  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=9101c6fd-c6d1-411c-85fc-33c425f49c8b, clientIf=6,
03-30 14:14:57.699 11115 11125 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:57.699  5869 11651 D BtGatt.GattService: start scan with filters
,03-30 14:14:57.719  5869 11651 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 13
,03-30 14:14:57.719 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:57.719  5869  5957 D BtGatt.ScanManager: handling starting scan
,03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-30 14:14:57.719  5869  5957 D BtGatt.ScanManager: isFilteringSupported
,03-30 14:14:57.719  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:14:57.719 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:14:57.724  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:14:57.724  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.724  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:57.724  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:57.724  5869  5957 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-30 14:14:57.724  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:57.724  5869  5954 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:57.724  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:57.724  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:57.724  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:57.724  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:57.724  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-30 14:14:57.724  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:14:57.724  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.729  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:57.729  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.729  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-30 14:14:57.734  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-30 14:14:57.734  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:14:57.734  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-30 14:14:57.739 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:14:57.739 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 14:14:57.739 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:14:57.739 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:57.739 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:57.739 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:14:57.739 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:57.739 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:14:57.739 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:57.744  5869 11650 D BtGatt.GattService: registerClient() - UUID=902d1d5b-fa8f-4b06-a778-5cc00ede92a3,
,03-30 14:14:57.759 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4c1a77e, channel: 6, state: CLOSED
,03-30 14:14:57.759 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22464e8, channel: 6, state: CLOSED
03-30 14:14:57.759 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a9fe23d, channel: 7, state: CLOSED
03-30 14:14:57.759 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f95eece, channel: 6, state: CLOSED
,03-30 14:14:57.759 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ad087a3, channel: 6, state: CLOSED
,03-30 14:14:57.764 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@feb92a5, channel: 6, state: CLOSED
,03-30 14:14:57.764 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f5fcdc5, channel: 6, state: CLOSED
,03-30 14:14:57.769 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2359f2ed, channel: 6, state: CLOSED
,03-30 14:14:57.769 11115 11124 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3539ebc3, channel: 6, state: CLOSED
,03-30 14:14:57.774  3481  3743 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-30 14:14:57.774  3481  3743 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-30 14:14:57.774  3481  3743 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
03-30 14:14:57.774  3481  3743 D BatteryService: stay LED for fully charged
03-30 14:14:57.774  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:14:57.774  3481  3481 I MotionRecognitionService: Plugged,
03-30 14:14:57.774  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-30 14:14:57.774  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-30 14:14:57.774  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-30 14:14:57.779  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:57.779  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:14:57.779  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-30 14:14:57.784  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=902d1d5b-fa8f-4b06-a778-5cc00ede92a3, clientIf=7,
03-30 14:14:57.784 11115 11127 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:57.789  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-30 14:14:57.789  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
,03-30 14:14:57.799  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:14:57.799  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:57.799  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:14:57.799  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:14:57.804  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 11
,03-30 14:14:57.804  5869  5954 D BtGatt.AdvertiseManager: message : 0
03-30 14:14:57.804  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:57.804  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:57.809  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:57.809  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-30 14:14:57.809  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:57.814  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
03-30 14:14:57.819  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:57.819  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:57.819  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-30 14:14:57.819 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:14:57.819  5869  5883 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:14:57.819  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:57.819  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 3
03-30 14:14:57.824  5869 11650 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:14:57.824  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:57.824  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.824  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:14:57.824 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:57.824 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:57.824 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:14:57.824 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:14:57.824 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,03-30 14:14:57.824 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
03-30 14:14:57.824  5869  6029 W bt-btif : new conn_srvc id:26, app_id:255
03-30 14:14:57.824 11115 11773 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@32550ea9
03-30 14:14:57.829  5869 11651 E BluetoothRemoteDevices: setRfcommConnected true
03-30 14:14:57.829 11115 11773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-30 14:14:57.829  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:14:57.829  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.829  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:57.829  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:14:57.829  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.834  5869 11651 D BtGatt.GattService: registerClient() - UUID=984263da-abd0-474e-adf5-1df38f644e6a
03-30 14:14:57.834 11115 11773 D BluetoothSocket: getInputStream(): myUserId = 0
03-30 14:14:57.839 11115 11773 D BluetoothSocket: getOutputStream(): myUserId = 0
03-30 14:14:57.839 11115 11773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1547)
,03-30 14:14:57.839 11115 11773 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1864ec2e, channel: 6, state: LISTENING
03-30 14:14:57.839 11115 11773 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1864ec2e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16d98271, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c82c3cfmSocket: android.net.LocalSocket@1c70a15c impl:android.net.LocalSocketImpl@1646ec65 fd:FileDescriptor[93]
03-30 14:14:57.839 11115 11773 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c70a15c impl:android.net.LocalSocketImpl@1646ec65 fd:FileDescriptor[93]
03-30 14:14:57.839 11115 11773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:14:57.844 11115 11773 D BluetoothSocket: bindListen(): myUserId = 0
03-30 14:14:57.844 11115 11773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:14:57.844 11115 11773 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
03-30 14:14:57.844 11115 11773 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:14:57.844 11115 11773 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-30 14:14:57.844 11115 11773 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13579d3a
03-30 14:14:57.844 11115 11773 D BluetoothSocket: channel: 6
03-30 14:14:57.844 11115 11773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-30 14:14:57.844 11115 11803 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1547)
,03-30 14:14:57.874  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=984263da-abd0-474e-adf5-1df38f644e6a, clientIf=6
,03-30 14:14:57.874 11115 11171 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:57.874  5869 11650 D BtGatt.GattService: start scan with filters
,03-30 14:14:57.889  5869 11650 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 14
,03-30 14:14:57.889 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-30 14:14:57.889  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:57.889  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:57.889  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:14:57.889 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:14:57.889  5869  5954 D BtGatt.AdvertiseManager: message : 1
03-30 14:14:57.889  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-30 14:14:57.889  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.889  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:14:57.889  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:57.889  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-30 14:14:57.889  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:57.889  5869  5957 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-30 14:14:57.894  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:57.894  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.894  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:57.894  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:14:57.894  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:14:57.894  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-30 14:14:57.894  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.894  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-30 14:14:57.894  5869  5942 D BtGatt.GattService: Client app is not null!
03-30 14:14:57.894  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=7
03-30 14:14:57.899 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:14:57.899 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-30 14:14:57.899 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:14:57.899 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:14:57.899 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:14:57.899 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-30 14:14:57.899 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:57.899  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:57.899  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.899 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:14:57.899 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:14:57.899  5869  5880 D BtGatt.GattService: registerClient() - UUID=6900fd61-fe6f-4eb5-92c5-5c72d8eb38f3
,03-30 14:14:57.944  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=6900fd61-fe6f-4eb5-92c5-5c72d8eb38f3, clientIf=7
,03-30 14:14:57.944 11115 11125 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:14:57.959  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 12
,03-30 14:14:57.959  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:14:57.959  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:14:57.959  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:14:57.964  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:14:57.964  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:14:57.969  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:14:57.974  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:14:57.974  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:14:57.974  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:14:57.974  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-30 14:14:57.974 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:14:57.979  5869 11650 D BtGatt.GattService: stopScan() - queue size =1
,03-30 14:14:57.979  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:14:57.979  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 4
03-30 14:14:57.979  5869  5883 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-30 14:14:57.979 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:14:57.979 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:14:57.979 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:14:57.979 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:14:57.979 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:14:57.979 11115 11115 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:57.979  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:14:57.979  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:57.979  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
,03-30 14:14:57.984  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-30 14:14:57.984  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.984  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:14:57.984  5869 11650 D BtGatt.GattService: registerClient() - UUID=4da4e6da-ea3c-4eb7-9c25-824907ddcb8f
,03-30 14:14:57.984  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-30 14:14:57.984  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:57.989  5869  5942 D BtGatt.GattService: current time is 266305085364
03-30 14:14:57.989  5869  5942 D BtGatt.GattService: Batch record : [72, 84, 87, -53, -86, 69, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-30 14:14:57.989  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:57.989  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:14:58.029  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=4da4e6da-ea3c-4eb7-9c25-824907ddcb8f, clientIf=6
,03-30 14:14:58.029 11115 11127 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:14:58.029  5869  5883 D BtGatt.GattService: start scan with filters
,03-30 14:14:58.044  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 15
,03-30 14:14:58.044 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:14:58.044 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:14:58.044  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:14:58.044  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:14:58.044  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:14:58.044 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-30 14:14:58.044 11115 11115 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-30 14:14:58.044 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:58.044 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:14:58.044 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-30 14:14:58.044 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:58.044 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:14:58.044 11115 11809 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1546)
03-30 14:14:58.049  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-30 14:14:58.049  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:58.049 11115 11809 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43434
03-30 14:14:58.049 11115 11809 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-30 14:14:58.049 11115 11809 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 43434 (peer ID: F8:95:C7:87:3C:51)
03-30 14:14:58.049  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:14:58.049  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:14:58.049 11115 11809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-30 14:14:58.049  5869  5957 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-30 14:14:58.049  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:14:58.049  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:58.049  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:14:58.049  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:14:58.054  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-30 14:14:58.054  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:14:58.054 11115 11178 I jxcore-log: INFO testThaliMobileNative: 
03-30 14:14:58.054 11115 11178 I jxcore-log: 
,03-30 14:14:58.059  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:14:58.059  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:58.059 11115 11178 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-30 14:14:58.059 11115 11178 I jxcore-log: 
,03-30 14:14:58.064 11115 11809 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 43434
,03-30 14:14:58.064 11115 11809 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-30 14:14:58.064 11115 11809 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-30 14:14:58.064 11115 11809 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-30 14:14:58.064 11115 11809 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1546)
03-30 14:14:58.064 11115 11809 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1546)
,03-30 14:14:58.064 11115 11811 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1548, name: Sender)
,03-30 14:14:58.069 11115 11812 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1549, name: Receiver)
03-30 14:14:58.069 11115 11178 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-30 14:14:58.069 11115 11178 I jxcore-log: 
,03-30 14:14:58.199  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.199  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.199  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.199  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.204 11115 11803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1547),
,03-30 14:14:58.214 11115 11803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-30 14:14:58.219  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-30 14:14:58.219  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.219  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.219  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.224 11115 11803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1547)
,03-30 14:14:58.229 11115 11803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1547,
03-30 14:14:58.229 11115 11803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1547)
,03-30 14:14:58.229 11115 11803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-30 14:14:58.229 11115 11115 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51],
03-30 14:14:58.229 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51],
,03-30 14:14:58.229 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-30 14:14:58.234 11115 11115 D BluetoothSocket: getInputStream(): myUserId = 0
,03-30 14:14:58.244 11115 11115 D BluetoothSocket: getOutputStream(): myUserId = 0
03-30 14:14:58.244 11115 11115 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-30 14:14:58.244 11115 11115 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-30 14:14:58.249 11115 11803 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1547),
,03-30 14:14:58.249 11115 11815 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1550),
,03-30 14:14:58.254  2873  3464 D EnterpriseController: netId is 0
03-30 14:14:58.254  2873  3464 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-30 14:14:58.259 11115 11815 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 41629
,03-30 14:14:58.264 11115 11815 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-30 14:14:58.264 11115 11815 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-30 14:14:58.264 11115 11815 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-30 14:14:58.269 11115 11817 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1551, name: Sender)
03-30 14:14:58.269  3481  6076 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:12), CUR = 37, LCD = 0
03-30 14:14:58.269 11115 11815 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1550)
03-30 14:14:58.269 11115 11815 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1550)
03-30 14:14:58.269 11115 11819 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1552, name: Receiver)
,03-30 14:14:58.274  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.274  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.274  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.274  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.279 11115 11178 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 14:14:58.279 11115 11178 I jxcore-log: 
,03-30 14:14:58.519  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.519  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.519  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.519  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.524  5869  6029 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-30 14:14:58.524  5869  6029 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-30 14:14:58.524  5869  6029 W bt-btif : bta_dm_acl_change(), event : 1
03-30 14:14:58.524  5869  5942 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:CF:C5:D9:E5:XX
03-30 14:14:58.529  5869  6029 W bt-btif : bta_dm_acl_change(), event : 2
03-30 14:14:58.539  3723  3723 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-30 14:14:58.539  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-30 14:14:58.549  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-30 14:14:58.549  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-30 14:14:58.549  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-30 14:14:58.559 11115 11178 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-30 14:14:58.559 11115 11178 I jxcore-log: 
,03-30 14:14:58.564  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a85719b u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2a1c8f9f 5869:com.android.bluetooth/1002},
,03-30 14:14:58.574  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d51742
03-30 14:14:58.579  3481  3730 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-30 14:14:58.574  5869  5869 D BtConfig.SecureMode: isSecureModeOn:false
03-30 14:14:58.574  3481  4021 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-30 14:14:58.584  5869  5869 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-30 14:14:58.584  3723  3723 D KeyguardViewMediator: isGear1: device is not B1!
,03-30 14:14:58.589  3481  4733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a85719b u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:58.609  3481  4041 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a85719b u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:58.614  3481  4679 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:14:58.624 10235 11828 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-30 14:14:58.624  3481  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a85719b u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:14:58.629 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-30 14:14:58.629 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-30 14:14:58.629 10235 10235 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-30 14:14:58.629 10235 10235 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-30 14:14:58.634  3481  4021 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3a85719b u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{ae069c4 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-30 14:14:58.644  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,03-30 14:14:58.644  4129  4129 I BluetoothClassifier: Bluetooth Device Name: Nexus 6
,03-30 14:14:58.649  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.649  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.649  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.649  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.649 11115 11178 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 14:14:58.649 11115 11178 I jxcore-log: 
,03-30 14:14:58.719  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.719  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.719  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.719  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.734 11115 11178 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 14:14:58.734 11115 11178 I jxcore-log: 
,03-30 14:14:58.779  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.779  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.779  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.784  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.789  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.789  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.789  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.789  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.804 11115 11178 I jxcore-log: INFO testThaliMobileNative: forwardData
03-30 14:14:58.804 11115 11178 I jxcore-log: 
,03-30 14:14:58.804 11115 11178 I jxcore-log: ok 179 received should match sent forward
03-30 14:14:58.804 11115 11178 I jxcore-log: 
,03-30 14:14:58.819  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.819  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.819  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:58.819  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.824 11115 11178 I jxcore-log: # teardown
03-30 14:14:58.824 11115 11178 I jxcore-log: 
,03-30 14:14:58.854  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.854  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.854  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:58.854  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:58.859  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:58.859  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:58.859  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:58.859  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:59.059  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:14:59.069  5869  5869 D BtGatt.ScanManager: awakened up at time 267389
,03-30 14:14:59.079  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:14:59.089  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:14:59.089  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:14:59.089  5869  5942 D BtGatt.GattService: current time is 267407387155
03-30 14:14:59.089  5869  5942 D BtGatt.GattService: Batch record : [72, 84, 87, -53, -86, 69, 1, -128, -65, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 1, 26, -111, 112, 55, 105, 1, -128, -84, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:14:59.089  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:14:59.089  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:59.089  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:14:59.089  5869  5942 D ScanRecord: parseFromBytes
03-30 14:14:59.094  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=45:AA:CB:57:54:48, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-65, mTimestampNanos=267157816530}
03-30 14:14:59.094  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:59.094  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=69:37:70:91:1A:01, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=266857816530}
03-30 14:14:59.094  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:14:59.094 11115 11125 D ScanRecord: parseFromBytes
03-30 14:14:59.094 11115 11125 D ScanRecord: parseFromBytes
03-30 14:14:59.094 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-30 14:14:59.094 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:14:59.109  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-30 14:14:59.109  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:59.109  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.109  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:59.139  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:59.139  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:59.139  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.139  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:59.179  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.179  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:59.179  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.179  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:59.179  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.184  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:59.184  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.184  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:14:59.244  5869  6029 D IOP_DB_BT: db_query: result 1
,03-30 14:14:59.289  3481  3498 I art     : Background partial concurrent mark sweep GC freed 51668(3MB) AllocSpace objects, 53(3MB) LOS objects, 33% free, 29MB/44MB, paused 2.849ms total 187.676ms
,03-30 14:14:59.999  3481  3617 V AlarmManager: waitForAlarm result :8
,03-30 14:15:00.129  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:15:00.154  5869  5869 D BtGatt.ScanManager: awakened up at time 268472
,03-30 14:15:00.164  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:15:00.169  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:15:00.169  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: current time is 268485668614
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: Batch record : [72, 84, 87, -53, -86, 69, 1, -128, -54, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0, 1, 26, -111, 112, 55, 105, 1, -128, -86, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:15:00.169  5869  5942 D ScanRecord: parseFromBytes
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:15:00.169  5869  5942 D ScanRecord: parseFromBytes
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=45:AA:CB:57:54:48, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=268435842531}
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=69:37:70:91:1A:01, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-86, mTimestampNanos=268335842531}
03-30 14:15:00.169  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:15:00.169 11115 11171 D ScanRecord: parseFromBytes
03-30 14:15:00.169 11115 11171 D ScanRecord: parseFromBytes
03-30 14:15:00.169 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
03-30 14:15:00.169 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-30 14:15:00.189  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
03-30 14:15:00.189  3723  3723 I PERF    : received broadcast android.intent.action.TIME_TICK
03-30 14:15:00.189  3723  3723 D KeyguardUpdateMonitor: handleTimeUpdate
03-30 14:15:00.194  3723  3723 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,03-30 14:15:00.204  3723  3723 D SecKeyguardClockView: HomeTimezone(): 1,
,03-30 14:15:00.219  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.219  3723  3723 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-30 14:15:00.229  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-30 14:15:00.269  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.274  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.274  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.279  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.284  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.284  3723  3723 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.299  3723  3723 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-30 14:15:00.689  5869  6029 E bt-btm  : tBTM_SEC_DEV:0xb35930d8 rs_disc_pending=0
,03-30 14:15:00.689  5869  6029 W bt-btif : bta_dm_acl_change(), event : 3
03-30 14:15:00.689  5869  6029 W bt-btif : bta_dm_check_av:0
03-30 14:15:00.694  5869  5942 W bt-btif : btif_dm_cback : unhandled event (14)
,03-30 14:15:01.179  3481  3617 V AlarmManager: waitForAlarm result :4
,03-30 14:15:01.194  5869  5869 D BtGatt.ScanManager: awakened up at time 269511
,03-30 14:15:01.199  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:15:01.204  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-30 14:15:01.204  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:01.204  5869  5942 D BtGatt.GattService: current time is 269523840906
03-30 14:15:01.204  5869  5942 D BtGatt.GattService: Batch record : [72, 84, 87, -53, -86, 69, 1, -128, -55, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0],
,03-30 14:15:01.204  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:15:01.204  5869  5942 D ScanRecord: parseFromBytes
03-30 14:15:01.209  5869  5942 D BtGatt.GattService: result: ScanResult{mDevice=45:AA:CB:57:54:48, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=268874174239}
,03-30 14:15:01.209  5869  5942 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-30 14:15:01.209 11115 11127 D ScanRecord: parseFromBytes
03-30 14:15:01.209 11115 11115 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61] updated - the peer count is 2
,03-30 14:15:01.509  3481  6107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-30 14:15:01.674 11115 11817 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1551, thread name: Sender)
03-30 14:15:01.674 11115 11817 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-30 14:15:01.674 11115 11817 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-30 14:15:01.674 11115 11817 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1550
03-30 14:15:01.674 11115 11817 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1550)
03-30 14:15:01.674 11115 11817 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@325f431d, channel: 6, state: CONNECTED
03-30 14:15:01.674 11115 11817 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@325f431d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e709992, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3da80f63mSocket: android.net.LocalSocket@3ed0e760 impl:android.net.LocalSocketImpl@39b1f419 fd:FileDescriptor[92]
03-30 14:15:01.674 11115 11817 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ed0e760 impl:android.net.LocalSocketImpl@39b1f419 fd:FileDescriptor[92]
,03-30 14:15:01.674 11115 11819 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1552, thread name: Receiver): bt socket closed, read return: -1,
03-30 14:15:01.674 11115 11819 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1552, name: Receiver)
03-30 14:15:01.674  5869  6029 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-30 14:15:01.674  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:15:01.674  5869  6029 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-30 14:15:01.674  5869  6029 D IOP_DB_BT: db_query: result 1
03-30 14:15:01.679 11115 11817 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@325f431d, channel: 6, state: CLOSED
03-30 14:15:01.679 11115 11817 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@325f431d, channel: 6, state: CLOSED
03-30 14:15:01.679 11115 11817 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-30 14:15:01.679 11115 11817 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-30 14:15:01.679 11115 11817 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1552
,03-30 14:15:01.679 11115 11817 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-30 14:15:01.679 11115 11817 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1551
03-30 14:15:01.679 11115 11817 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1550),
,03-30 14:15:01.679 11115 11817 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1550)
03-30 14:15:01.679 11115 11817 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-30 14:15:01.684 11115 11817 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1551, name: Sender)
03-30 14:15:01.689 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:01.689 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-30 14:15:01.689 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-30 14:15:01.689 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:15:01.694  5869 11650 D BtGatt.GattService: stopScan() - queue size =1,
03-30 14:15:01.694  5869  5957 D BtGatt.ScanManager: filter size is 1
,03-30 14:15:01.694  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 5,
03-30 14:15:01.694  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:15:01.694  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:01.699  5869  6029 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
03-30 14:15:01.699  5869  6029 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-30 14:15:01.699  5869  5957 D BtGatt.ScanManager: stopping BLe Batch,
03-30 14:15:01.699  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:15:01.699  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:01.699  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-30 14:15:01.699  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:15:01.699  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:01.704  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:01.704 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:01.704 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:01.704 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:01.704 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-30 14:15:01.704 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-30 14:15:01.704 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:01.709 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:01.709 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-30 14:15:01.709 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:15:01.714 11115 11178 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s,
03-30 14:15:01.714 11115 11178 I jxcore-log: 
03-30 14:15:01.714 11115 11178 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-30 14:15:01.714 11115 11178 I jxcore-log: 
,03-30 14:15:01.719 11115 11178 I jxcore-log: ok 180 Should be able to call stopListeningForAdvertisments in teardown
03-30 14:15:01.719 11115 11178 I jxcore-log: 
,03-30 14:15:01.719 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:01.719 11115 11178 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-30 14:15:01.719 11115 11178 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1546)
03-30 14:15:01.719 11115 11178 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1546)
,03-30 14:15:01.724 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d7abcde, channel: 7, state: CONNECTED
03-30 14:15:01.724 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d7abcde, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34823ebf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@114d198cmSocket: android.net.LocalSocket@29e4b8d5 impl:android.net.LocalSocketImpl@1071c8ea fd:FileDescriptor[115]
03-30 14:15:01.724 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29e4b8d5 impl:android.net.LocalSocketImpl@1071c8ea fd:FileDescriptor[115]
,03-30 14:15:01.724 11115 11812 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1549, thread name: Receiver): bt socket closed, read return: -1
03-30 14:15:01.724 11115 11812 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1549, name: Receiver)
,03-30 14:15:01.724 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d7abcde, channel: 7, state: CLOSED
03-30 14:15:01.724 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d7abcde, channel: 7, state: CLOSED
03-30 14:15:01.724 11115 11178 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-30 14:15:01.724 11115 11178 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
,03-30 14:15:01.724 11115 11178 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1549
03-30 14:15:01.724 11115 11178 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-30 14:15:01.729 11115 11178 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1548
03-30 14:15:01.729 11115 11178 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1546)
,03-30 14:15:01.729 11115 11811 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1548, thread name: Sender): Socket closed,
03-30 14:15:01.729 11115 11811 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1548, name: Sender)
03-30 14:15:01.729 11115 11178 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1546)
,03-30 14:15:01.729 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-30 14:15:01.729 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:15:01.729 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:15:01.729 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 14:15:01.729 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3aa607db, channel: 6, state: LISTENING
03-30 14:15:01.729 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3aa607db, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13579d3a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d784278mSocket: android.net.LocalSocket@31450d51 impl:android.net.LocalSocketImpl@221b89b6 fd:FileDescriptor[117]
,03-30 14:15:01.734 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31450d51 impl:android.net.LocalSocketImpl@221b89b6 fd:FileDescriptor[117]
,03-30 14:15:01.734 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-30 14:15:01.734 11115 11773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:15:01.734 11115 11773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-30 14:15:01.734 11115 11773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:15:01.734 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-30 14:15:01.734 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:01.734 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-30 14:15:01.734 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:15:01.739 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:01.739 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:01.739 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:01.739 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-30 14:15:01.739 11115 11178 D BluetoothLeScanner: could not find callback wrapper,
03-30 14:15:01.739 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:01.739 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-30 14:15:01.744  5869  5954 D BtGatt.AdvertiseManager: message : 1
,03-30 14:15:01.744  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:15:01.744  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:15:01.744  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:15:01.744  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-30 14:15:01.749  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:15:01.749  5869 11650 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:15:01.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:01.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:01.749 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:15:01.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 14:15:01.749 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:15:01.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:01.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:01.749 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:15:01.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:01.749 11115 11178 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-30 14:15:01.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:01.749 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:01.749 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:15:01.749 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:01.749 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:01.749 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:15:01.754 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-30 14:15:01.754 11115 11178 I jxcore-log: 
,03-30 14:15:01.754 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:01.759 11115 11178 I jxcore-log: ok 181 Should be able to call stopAdvertisingAndListening in teardown
03-30 14:15:01.759 11115 11178 I jxcore-log: 
,03-30 14:15:01.759 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-30 14:15:01.759 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:01.759 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:01.764 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:01.764 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:01.764 11115 11178 I jxcore-log: # setup
03-30 14:15:01.764 11115 11178 I jxcore-log: 
,03-30 14:15:01.769 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:01.769 11115 11178 I jxcore-log: 
,03-30 14:15:01.769 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:01.769 11115 11178 I jxcore-log: 
,03-30 14:15:02.064  5869  6029 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-30 14:15:02.694 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:02.694 11115 11178 I jxcore-log: 
,03-30 14:15:02.699 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:02.699 11115 11178 I jxcore-log: 
,03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:02.704 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:02.709 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:02.709 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:02.709 11115 11178 I jxcore-log: 
,03-30 14:15:02.714 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:02.714 11115 11178 I jxcore-log: 
,03-30 14:15:02.719 11115 11178 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
03-30 14:15:02.719 11115 11178 I jxcore-log: 
,03-30 14:15:02.724 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:02.724 11115 11178 I jxcore-log: 
,03-30 14:15:04.849 11115 11178 I jxcore-log: ok 182 specific error should be returned
03-30 14:15:04.849 11115 11178 I jxcore-log: 
,03-30 14:15:04.854 11115 11178 I jxcore-log: # teardown
03-30 14:15:04.854 11115 11178 I jxcore-log: 
,03-30 14:15:05.774 11115 11178 I jxcore-log: ok 183 must be stopped
03-30 14:15:05.774 11115 11178 I jxcore-log: 
,03-30 14:15:05.779 11115 11178 I jxcore-log: # setup
03-30 14:15:05.779 11115 11178 I jxcore-log: 
,03-30 14:15:06.689 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:06.689 11115 11178 I jxcore-log: 
,03-30 14:15:06.689 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:06.689 11115 11178 I jxcore-log: 
,03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:06.699 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:06.709 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:06.709 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:06.709 11115 11178 I jxcore-log: 
,03-30 14:15:06.714 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:06.714 11115 11178 I jxcore-log: 
,03-30 14:15:06.719 11115 11178 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
03-30 14:15:06.719 11115 11178 I jxcore-log: 
,03-30 14:15:06.719 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:06.719 11115 11178 I jxcore-log: 
,03-30 14:15:06.914 11115 11178 I jxcore-log: ok 184 specific error should be returned
03-30 14:15:06.914 11115 11178 I jxcore-log: 
,03-30 14:15:06.919 11115 11178 I jxcore-log: # teardown
03-30 14:15:06.919 11115 11178 I jxcore-log: 
,03-30 14:15:06.939  5869  6029 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-30 14:15:06.939  5869  6029 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-30 14:15:06.939  5869  6029 W bt-btif : bta_dm_acl_change(), event : 1
03-30 14:15:06.939  5869  6029 W bt-btif : bta_dm_acl_change(), event : 2
,03-30 14:15:06.939  5869  5942 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-30 14:15:06.944  3723  3723 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-30 14:15:06.944  5869  5942 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-30 14:15:06.949  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-30 14:15:06.949  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-30 14:15:06.949  3481  3481 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-30 14:15:06.964  3481  3569 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{278750 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{2a1c8f9f 5869:com.android.bluetooth/1002}
,03-30 14:15:06.964  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6d51742
03-30 14:15:06.969  3481  4046 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-30 14:15:06.964  5869  5869 D BtConfig.SecureMode: isSecureModeOn:false
03-30 14:15:06.964  3481  4731 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-30 14:15:06.974  5869  5869 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-30 14:15:06.974  3723  3723 D KeyguardViewMediator: isGear1: device is not B1!
,03-30 14:15:06.984  3481  3961 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{278750 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:15:06.989  3481  4733 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-30 14:15:06.999 10235 11897 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-30 14:15:06.999  3481  4046 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{278750 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:15:07.004 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-30 14:15:07.004 10235 10235 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-30 14:15:07.009  3481  4041 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{278750 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{22ef529f 11656:com.sec.android.app.shealth/u0a36}
,03-30 14:15:07.009 10235 10235 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-30 14:15:07.009 10235 10235 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-30 14:15:07.019  3481  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{278750 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{ae069c4 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-30 14:15:07.029  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-30 14:15:07.029  4129  4129 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-30 14:15:07.914 11115 11178 I jxcore-log: ok 185 must be stopped
03-30 14:15:07.914 11115 11178 I jxcore-log: 
,03-30 14:15:07.919  3481  4763 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-30 14:15:07.919  3481  4763 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-30 14:15:07.919  3481  4763 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
03-30 14:15:07.919  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:15:07.929  3481  3481 I MotionRecognitionService: Plugged
03-30 14:15:07.929  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-30 14:15:07.929  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-30 14:15:07.929  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
,03-30 14:15:07.929  3481  4763 D BatteryService: stay LED for fully charged,
,03-30 14:15:07.934  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:15:07.934  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:15:07.934  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-30 14:15:07.949  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-30 14:15:07.949  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
,03-30 14:15:07.954 11115 11178 I jxcore-log: # setup
03-30 14:15:07.954 11115 11178 I jxcore-log: 
,03-30 14:15:07.959  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:15:07.964  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:15:07.964  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:15:07.964  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:15:08.269 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:08.269 11115 11178 I jxcore-log: 
,03-30 14:15:08.274 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:08.274 11115 11178 I jxcore-log: 
,03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:08.289 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:08.289 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:08.294  3481  6076 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:12), CUR = 36, LCD = 0
,03-30 14:15:08.294 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:08.294 11115 11178 I jxcore-log: 
,03-30 14:15:08.299 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:08.299 11115 11178 I jxcore-log: 
,03-30 14:15:08.304 11115 11178 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
03-30 14:15:08.304 11115 11178 I jxcore-log: 
,03-30 14:15:08.309 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:08.309 11115 11178 I jxcore-log: 
,03-30 14:15:08.854 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:08.854 11115 11178 I jxcore-log: 
,03-30 14:15:08.859 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 41794
03-30 14:15:08.859 11115 11178 I jxcore-log: 
,03-30 14:15:08.864 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:08.864 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:08.864 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:08.869 11115 11178 I jxcore-log: ok 186 no errors
03-30 14:15:08.869 11115 11178 I jxcore-log: 
,03-30 14:15:08.869 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:08.869 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:08.869 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:08.874 11115 11178 I jxcore-log: ok 187 still no errors
03-30 14:15:08.874 11115 11178 I jxcore-log: 
,03-30 14:15:08.884 11115 11178 I jxcore-log: # teardown
03-30 14:15:08.884 11115 11178 I jxcore-log: 
,03-30 14:15:09.024 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:09.024 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:09.024 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:09.029 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:09.029 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:09.029 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:09.039 11115 11178 I jxcore-log: ok 188 must be stopped
03-30 14:15:09.039 11115 11178 I jxcore-log: 
,03-30 14:15:09.049 11115 11178 I jxcore-log: # setup
03-30 14:15:09.049 11115 11178 I jxcore-log: 
,03-30 14:15:09.554 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:09.554 11115 11178 I jxcore-log: 
,03-30 14:15:09.554 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:09.554 11115 11178 I jxcore-log: 
,03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:09.564 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:09.569 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:09.574 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:09.574 11115 11178 I jxcore-log: 
,03-30 14:15:09.574 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:09.574 11115 11178 I jxcore-log: 
,03-30 14:15:09.584 11115 11178 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
03-30 14:15:09.584 11115 11178 I jxcore-log: 
,03-30 14:15:09.584 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:09.584 11115 11178 I jxcore-log: 
,03-30 14:15:09.744 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:09.744 11115 11178 I jxcore-log: 
,03-30 14:15:09.749 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 42908
03-30 14:15:09.749 11115 11178 I jxcore-log: 
,03-30 14:15:09.754 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 41629, start advertisements: false
,03-30 14:15:09.754 11115 11178 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-30 14:15:09.754 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-30 14:15:09.759 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-30 14:15:09.764 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:09.769 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:15:09.769 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:09.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:15:09.774 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:15:09.779 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:09.779 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:09.784  5869  5956 D BtGatt.GattService: registerClient() - UUID=5ca4c76c-45ee-420e-ba2f-3811adc5c80f
,03-30 14:15:09.824  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=5ca4c76c-45ee-420e-ba2f-3811adc5c80f, clientIf=6
,03-30 14:15:09.824 11115 11127 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-30 14:15:09.824  5869 11650 D BtGatt.GattService: start scan with filters
,03-30 14:15:09.839  5869 11650 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 16
,03-30 14:15:09.839 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:09.839 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:09.839 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:15:09.839 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:09.839 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:09.839 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:15:09.839  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:15:09.839  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:15:09.839 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:09.839  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:15:09.839 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-30 14:15:09.839 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:09.839 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:09.844 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:09.844 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:09.844 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:09.844  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-30 14:15:09.844  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:09.844  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:15:09.844  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:15:09.844  5869  5957 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,03-30 14:15:09.844 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:09.844 11115 11178 I jxcore-log: 
03-30 14:15:09.844  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:15:09.844  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:09.844  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
,03-30 14:15:09.844  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-30 14:15:09.844 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:09.844 11115 11178 I jxcore-log: 
,03-30 14:15:09.849  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:15:09.849  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:09.849 11115 11178 I jxcore-log: ok 189 no errors
03-30 14:15:09.849 11115 11178 I jxcore-log: 
03-30 14:15:09.849  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:15:09.849  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:09.849 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 41629, start advertisements: false,
03-30 14:15:09.849 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:09.849 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:09.849 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-30 14:15:09.854 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:15:09.854 11115 11178 I jxcore-log: ok 190 still no errors
03-30 14:15:09.854 11115 11178 I jxcore-log: 
,03-30 14:15:09.859 11115 11178 I jxcore-log: # teardown
03-30 14:15:09.859 11115 11178 I jxcore-log: 
,03-30 14:15:10.234 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-30 14:15:10.234 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
03-30 14:15:10.239 11115 11178 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-30 14:15:10.239 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-30 14:15:10.239 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:10.239 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:15:10.239 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-30 14:15:10.239 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-30 14:15:10.239 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-30 14:15:10.244  5869  5883 D BtGatt.GattService: stopScan() - queue size =1,
03-30 14:15:10.244  5869  5957 D BtGatt.ScanManager: filter size is 1,
,03-30 14:15:10.244  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 6,
,03-30 14:15:10.249  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-30 14:15:10.249  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:10.249  5869  5957 D BtGatt.ScanManager: stopping BLe Batch,
,03-30 14:15:10.249  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-30 14:15:10.249  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-30 14:15:10.249  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-30 14:15:10.254  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:15:10.254  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-30 14:15:10.254  5869 11651 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:10.259 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:10.259 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-30 14:15:10.259 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:10.259 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:15:10.259 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,03-30 14:15:10.259 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:10.264 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-30 14:15:10.264 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-30 14:15:10.264 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-30 14:15:10.264 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-30 14:15:10.264 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:10.264 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-30 14:15:10.264 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-30 14:15:10.264 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:15:10.269 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-30 14:15:10.274 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-30 14:15:10.279 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:10.279 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-30 14:15:10.284 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-30 14:15:10.284 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:10.284 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-30 14:15:10.284 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-30 14:15:10.289 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:10.294 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:10.294 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-30 14:15:10.299 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-30 14:15:10.299 11115 11178 I jxcore-log: 
,03-30 14:15:10.299 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:10.299 11115 11178 I jxcore-log: 
,03-30 14:15:10.304 11115 11178 I jxcore-log: ok 191 must be stopped
03-30 14:15:10.304 11115 11178 I jxcore-log: 
,03-30 14:15:10.309 11115 11178 I jxcore-log: # setup
03-30 14:15:10.309 11115 11178 I jxcore-log: 
,03-30 14:15:10.544 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:10.544 11115 11178 I jxcore-log: 
,03-30 14:15:10.549 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:10.549 11115 11178 I jxcore-log: 
,03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:10.559 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:10.564 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:10.569 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:10.569 11115 11178 I jxcore-log: 
,03-30 14:15:10.569 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:10.569 11115 11178 I jxcore-log: 
,03-30 14:15:10.574 11115 11178 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
03-30 14:15:10.574 11115 11178 I jxcore-log: 
,03-30 14:15:10.579 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:10.579 11115 11178 I jxcore-log: 
,03-30 14:15:10.709 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:10.709 11115 11178 I jxcore-log: 
,03-30 14:15:10.719 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 34199
03-30 14:15:10.719 11115 11178 I jxcore-log: 
,03-30 14:15:10.724 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 34199, start advertisements: true
,03-30 14:15:10.729 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:15:10.729 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:15:10.729 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:15:10.734 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:15:10.734 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:15:10.734 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:15:10.734 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:10.739  5869  5956 D BtGatt.GattService: registerClient() - UUID=a6a42df3-3790-445f-83da-80e4235b0730
,03-30 14:15:10.779  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=a6a42df3-3790-445f-83da-80e4235b0730, clientIf=6
03-30 14:15:10.779 11115 11171 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:15:10.779  5869 11650 D BtGatt.GattService: start scan with filters
,03-30 14:15:10.799  5869 11650 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 17
,03-30 14:15:10.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-30 14:15:10.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:10.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:15:10.799  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:15:10.799  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:15:10.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:10.799  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:15:10.799 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:10.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:15:10.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:15:10.799 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:10.799 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-30 14:15:10.799 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:10.799 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:10.799 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:15:10.799  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:15:10.799  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:10.799  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:15:10.799  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:15:10.799  5869  5957 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-30 14:15:10.804  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:15:10.804  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:10.804  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:10.804  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:15:10.804  5869 11650 D BtGatt.GattService: registerClient() - UUID=3d52bf84-177a-442d-8de3-d334e54d20ac
,03-30 14:15:10.804  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:15:10.804  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:10.804  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:15:10.804  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:10.844  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=3d52bf84-177a-442d-8de3-d334e54d20ac, clientIf=7
,03-30 14:15:10.844 11115 11127 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:15:10.864  5869 11651 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 13
,03-30 14:15:10.864  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:15:10.869  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
,03-30 14:15:10.869  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:15:10.874  5869  5954 D BtGatt.AdvertiseManager: starting advertising
,03-30 14:15:10.874  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:15:10.894  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:15:10.899  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:10.909  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-30 14:15:10.909  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-30 14:15:10.909  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-30 14:15:10.909 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-30 14:15:10.909 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:15:10.924 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-30 14:15:10.929 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:15:10.939 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-30 14:15:10.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-30 14:15:10.949 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-30 14:15:10.954 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,03-30 14:15:10.959 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
,03-30 14:15:10.959 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-30 14:15:10.964 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
,03-30 14:15:10.964 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
,03-30 14:15:10.964 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
,03-30 14:15:10.969 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
,03-30 14:15:10.969 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING],
03-30 14:15:10.969 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING],
,03-30 14:15:10.969 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-30 14:15:10.969 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-30 14:15:10.969 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-30 14:15:10.969 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-30 14:15:10.969 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-30 14:15:10.969 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:10.974 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:10.994 11115 11948 D BluetoothSocket: bindListen(): myUserId = 0
,03-30 14:15:10.994 11115 11948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:15:10.999 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:10.999 11115 11178 I jxcore-log: 
,03-30 14:15:11.004 11115 11948 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
03-30 14:15:11.004 11115 11948 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:15:11.004 11115 11948 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-30 14:15:11.004 11115 11948 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b8b1589
03-30 14:15:11.004 11115 11948 D BluetoothSocket: channel: 6
03-30 14:15:11.004 11115 11948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:15:11.014 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-30 14:15:11.014 11115 11178 I jxcore-log: 
,03-30 14:15:11.014 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:15:11.014 11115 11178 I jxcore-log: 
,03-30 14:15:11.019 11115 11178 I jxcore-log: ok 192 no errors
03-30 14:15:11.019 11115 11178 I jxcore-log: 
,03-30 14:15:11.029 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 34199, start advertisements: true
,03-30 14:15:11.029 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:15:11.029 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:15:11.029 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:11.029 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:15:11.034 11115 11178 I jxcore-log: ok 193 still no errors
03-30 14:15:11.034 11115 11178 I jxcore-log: 
,03-30 14:15:11.044 11115 11178 I jxcore-log: # teardown
03-30 14:15:11.044 11115 11178 I jxcore-log: 
,03-30 14:15:11.359 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:11.359 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-30 14:15:11.364 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-30 14:15:11.364 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:15:11.364 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:15:11.364 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3bbe198e, channel: 6, state: LISTENING
,03-30 14:15:11.364 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3bbe198e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b8b1589, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d8e55afmSocket: android.net.LocalSocket@380ffdbc impl:android.net.LocalSocketImpl@39868145 fd:FileDescriptor[115],
03-30 14:15:11.364 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@380ffdbc impl:android.net.LocalSocketImpl@39868145 fd:FileDescriptor[115],
,03-30 14:15:11.369 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-30 14:15:11.369 11115 11948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-30 14:15:11.369 11115 11948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:15:11.369 11115 11948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 14:15:11.369 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:15:11.374 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-30 14:15:11.374 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:15:11.374 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-30 14:15:11.374 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:11.374 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-30 14:15:11.374 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,03-30 14:15:11.374 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-30 14:15:11.374 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:15:11.379  5869 11650 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:15:11.379  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:15:11.379  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 7
03-30 14:15:11.384  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:15:11.384  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:11.384  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:11.384  5869 11651 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:11.384  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:15:11.384  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:11.384  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:15:11.389  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
03-30 14:15:11.389  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:11.389  5869  5942 D BtGatt.GattService: current time is 279708979157
03-30 14:15:11.389  5869  5942 D BtGatt.GattService: Batch record : [57, 110, -41, 40, 16, 119, 1, -128, -75, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -125, 11, 107, 13, -94, 67, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
,03-30 14:15:11.389  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-30 14:15:11.389  5869  5942 D ScanRecord: parseFromBytes
03-30 14:15:11.389  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:15:11.389  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:15:11.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:15:11.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:11.394 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-30 14:15:11.394 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-30 14:15:11.399 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:15:11.399 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:11.399 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:15:11.399  5869  5954 D BtGatt.AdvertiseManager: message : 1
,03-30 14:15:11.399  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:15:11.399  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:15:11.399  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:15:11.404  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-30 14:15:11.404  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:15:11.404  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=7
03-30 14:15:11.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-30 14:15:11.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:11.404 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:15:11.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:15:11.404 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:15:11.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:11.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:11.404 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:15:11.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-30 14:15:11.404 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:11.404 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:11.404 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:11.404 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:11.404 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:11.404 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:15:11.409 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:11.409 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:11.409 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:11.409 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:11.414 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:11.414 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:11.414 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:11.419 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 14:15:11.419 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:11.419 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:11.419 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:15:11.419 11115 11178 I jxcore-log: 
,03-30 14:15:11.419 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:11.419 11115 11178 I jxcore-log: 
,03-30 14:15:11.424 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:11.424 11115 11178 I jxcore-log: 
,03-30 14:15:11.429 11115 11178 I jxcore-log: ok 194 must be stopped
03-30 14:15:11.429 11115 11178 I jxcore-log: 
,03-30 14:15:11.434 11115 11178 I jxcore-log: # setup
03-30 14:15:11.434 11115 11178 I jxcore-log: 
,03-30 14:15:11.879 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-30 14:15:11.879 11115 11178 I jxcore-log: 
03-30 14:15:11.879 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
03-30 14:15:11.879 11115 11178 I jxcore-log: 
,03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:11.894 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:11.894 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:11.899 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:11.899 11115 11178 I jxcore-log: 
,03-30 14:15:11.904 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:11.904 11115 11178 I jxcore-log: 
,03-30 14:15:11.904 11115 11178 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
03-30 14:15:11.904 11115 11178 I jxcore-log: 
,03-30 14:15:11.909 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:11.909 11115 11178 I jxcore-log: 
,03-30 14:15:12.439 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:12.439 11115 11178 I jxcore-log: 
,03-30 14:15:12.444 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 43255
03-30 14:15:12.444 11115 11178 I jxcore-log: 
,03-30 14:15:12.444 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:12.449 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:12.449 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.449 11115 11178 I jxcore-log: ok 195 no errors
03-30 14:15:12.449 11115 11178 I jxcore-log: 
,03-30 14:15:12.454 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:12.454 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:12.454 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.459 11115 11178 I jxcore-log: ok 196 still no errors
03-30 14:15:12.459 11115 11178 I jxcore-log: 
,03-30 14:15:12.464 11115 11178 I jxcore-log: # teardown
03-30 14:15:12.464 11115 11178 I jxcore-log: 
,03-30 14:15:12.679 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:12.679 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-30 14:15:12.679 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.684 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:12.684 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-30 14:15:12.689 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:12.694 11115 11178 I jxcore-log: ok 197 must be stopped
03-30 14:15:12.694 11115 11178 I jxcore-log: 
,03-30 14:15:12.704 11115 11178 I jxcore-log: # setup
03-30 14:15:12.704 11115 11178 I jxcore-log: 
,03-30 14:15:12.939 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:12.939 11115 11178 I jxcore-log: 
,03-30 14:15:12.944 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:12.944 11115 11178 I jxcore-log: 
,03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:12.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:12.954 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:12.959 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:12.959 11115 11178 I jxcore-log: 
,03-30 14:15:12.964 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:12.964 11115 11178 I jxcore-log: 
,03-30 14:15:12.969 11115 11178 I jxcore-log: # 48. can get the network status before starting
03-30 14:15:12.969 11115 11178 I jxcore-log: 
,03-30 14:15:12.974 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:12.974 11115 11178 I jxcore-log: 
,03-30 14:15:13.149 11115 11178 I jxcore-log: ok 198 network status should have certain non-empty properties
03-30 14:15:13.149 11115 11178 I jxcore-log: 
,03-30 14:15:13.159 11115 11178 I jxcore-log: # teardown
03-30 14:15:13.159 11115 11178 I jxcore-log: 
,03-30 14:15:13.244 11115 11178 I jxcore-log: ok 199 must be stopped
03-30 14:15:13.244 11115 11178 I jxcore-log: 
,03-30 14:15:13.249 11115 11178 I jxcore-log: # setup
03-30 14:15:13.249 11115 11178 I jxcore-log: 
,03-30 14:15:13.419 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:13.419 11115 11178 I jxcore-log: 
,03-30 14:15:13.424 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:13.424 11115 11178 I jxcore-log: 
,03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:13.434 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:13.439 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:13.439 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:13.439 11115 11178 I jxcore-log: 
,03-30 14:15:13.444 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:13.444 11115 11178 I jxcore-log: 
,03-30 14:15:13.449 11115 11178 I jxcore-log: # 49. error returned with bad router
03-30 14:15:13.449 11115 11178 I jxcore-log: 
,03-30 14:15:13.454 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:13.454 11115 11178 I jxcore-log: 
,03-30 14:15:13.564 11115 11178 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-30 14:15:13.564 11115 11178 I jxcore-log: 
,03-30 14:15:13.564 11115 11178 I jxcore-log: ok 200 specific error expected
03-30 14:15:13.564 11115 11178 I jxcore-log: 
,03-30 14:15:13.569 11115 11178 I jxcore-log: # teardown
03-30 14:15:13.569 11115 11178 I jxcore-log: 
,03-30 14:15:13.704 11115 11178 I jxcore-log: ok 201 must be stopped
03-30 14:15:13.704 11115 11178 I jxcore-log: 
,03-30 14:15:13.714 11115 11178 I jxcore-log: # setup
03-30 14:15:13.714 11115 11178 I jxcore-log: 
,03-30 14:15:13.859 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:13.859 11115 11178 I jxcore-log: 
,03-30 14:15:13.864 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:13.864 11115 11178 I jxcore-log: 
,03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:13.874 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:13.879 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:13.879 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:13.879 11115 11178 I jxcore-log: 
,03-30 14:15:13.884 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:13.884 11115 11178 I jxcore-log: 
,03-30 14:15:13.884 11115 11178 I jxcore-log: # 50. all services are stopped when we call stop
03-30 14:15:13.884 11115 11178 I jxcore-log: 
,03-30 14:15:13.889 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:13.889 11115 11178 I jxcore-log: 
,03-30 14:15:14.079 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:14.079 11115 11178 I jxcore-log: 
,03-30 14:15:14.084 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 59576
03-30 14:15:14.084 11115 11178 I jxcore-log: 
,03-30 14:15:14.089 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 34199, start advertisements: false
,03-30 14:15:14.094 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:14.094 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:15:14.094 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:15:14.094 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:15:14.099 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-30 14:15:14.099 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:14.104  5869 11651 D BtGatt.GattService: registerClient() - UUID=3db5ef79-f5d5-4c74-b389-36f06cbb90d9
,03-30 14:15:14.144  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=3db5ef79-f5d5-4c74-b389-36f06cbb90d9, clientIf=6
03-30 14:15:14.144 11115 11125 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:15:14.154  5869  5883 D BtGatt.GattService: start scan with filters,
,03-30 14:15:14.179  5869  5883 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 18
,03-30 14:15:14.179  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:15:14.179  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:15:14.179  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:15:14.189  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:15:14.189  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:14.189  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:15:14.189  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:15:14.189  5869  5957 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-30 14:15:14.189  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:15:14.189  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:14.194  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:14.194  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:15:14.194  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:15:14.194  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:14.199  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-30 14:15:14.199  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:14.204 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-30 14:15:14.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:14.204 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-30 14:15:14.204 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:14.204 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 14:15:14.204 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:15:14.204 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:14.209 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:14.209 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-30 14:15:14.209 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-30 14:15:14.209 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:14.209 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:14.209 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
,03-30 14:15:14.209 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:14.209 11115 11178 I jxcore-log: 
,03-30 14:15:14.214 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:14.214 11115 11178 I jxcore-log: 
,03-30 14:15:14.224 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 59576, start advertisements: true
,03-30 14:15:14.224 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-30 14:15:14.224 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-30 14:15:14.224 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:15:14.224 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:15:14.229 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-30 14:15:14.229 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-30 14:15:14.229 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:15:14.229 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-30 14:15:14.229 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-30 14:15:14.229 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:14.229 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-30 14:15:14.234  5869  5956 D BtGatt.GattService: registerClient() - UUID=905a33a9-5bbd-407c-b6ee-fc0a12f4e47b
,03-30 14:15:14.274  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=905a33a9-5bbd-407c-b6ee-fc0a12f4e47b, clientIf=7
,03-30 14:15:14.274 11115 11171 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:15:14.289  5869 11650 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 14
,03-30 14:15:14.289  5869  5954 D BtGatt.AdvertiseManager: message : 0
03-30 14:15:14.289  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:15:14.289  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:15:14.289  5869  5954 D BtGatt.AdvertiseManager: starting advertising
03-30 14:15:14.289  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-30 14:15:14.289  3481  3861 E Watchdog: !@Sync 9 [03-30 14:15:14.294]
,03-30 14:15:14.294  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:15:14.294  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:14.294  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-30 14:15:14.294  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-30 14:15:14.294  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-30 14:15:14.294 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:15:14.294 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:15:14.294 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:15:14.294 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:15:14.294 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:15:14.294 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:15:14.294 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-30 14:15:14.299 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:14.299 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:14.299 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:15:14.299 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:14.299 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:14.299 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:15:14.299 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:15:14.299 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:15:14.299 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:15:14.299 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:14.299 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-30 14:15:14.299 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:14.299 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-30 14:15:14.304 11115 12002 D BluetoothSocket: bindListen(): myUserId = 0
03-30 14:15:14.304 11115 12002 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-30 14:15:14.304 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:15:14.304 11115 11178 I jxcore-log: 
,03-30 14:15:14.304 11115 12002 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
03-30 14:15:14.304 11115 12002 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:15:14.304 11115 12002 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-30 14:15:14.304 11115 12002 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1012ecc1
03-30 14:15:14.304 11115 12002 D BluetoothSocket: channel: 6
03-30 14:15:14.304 11115 12002 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:15:14.309 11115 11178 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-30 14:15:14.309 11115 11178 I jxcore-log: 
,03-30 14:15:14.314 11115 11178 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-30 14:15:14.314 11115 11178 I jxcore-log: 
,03-30 14:15:14.314 11115 11178 I jxcore-log: DEBUG createNativeListener: new mux
03-30 14:15:14.314 11115 11178 I jxcore-log: 
,03-30 14:15:14.319 11115 11178 I jxcore-log: ok 202 connection to servers manager should succeed after starting
03-30 14:15:14.319 11115 11178 I jxcore-log: 
,03-30 14:15:14.344 11115 11178 I jxcore-log: ok 203 connection to router server should succeed after starting
03-30 14:15:14.344 11115 11178 I jxcore-log: 
,03-30 14:15:14.344 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:14.344 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:15:14.344 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:15:14.344 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:15:14.344 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-30 14:15:14.344 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a77cc66, channel: 6, state: LISTENING
,03-30 14:15:14.344 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a77cc66, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1012ecc1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@222d4ba7mSocket: android.net.LocalSocket@4804854 impl:android.net.LocalSocketImpl@5a093fd fd:FileDescriptor[115]
03-30 14:15:14.344 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4804854 impl:android.net.LocalSocketImpl@5a093fd fd:FileDescriptor[115]
03-30 14:15:14.344 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:15:14.344 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:14.344 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-30 14:15:14.344 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:14.344 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:14.344 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:15:14.344 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-30 14:15:14.344 11115 12002 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-30 14:15:14.344 11115 12002 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:15:14.344 11115 12002 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-30 14:15:14.349  5869 11651 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:15:14.349  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:15:14.349  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 8
03-30 14:15:14.349  5869  5880 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:14.349 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:15:14.349 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:14.349 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:14.349  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:15:14.349  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:14.349  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:14.349 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-30 14:15:14.349 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:15:14.349 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:14.349 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:15:14.349  5869  5954 D BtGatt.AdvertiseManager: message : 1
,03-30 14:15:14.349  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-30 14:15:14.349  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-30 14:15:14.354  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:15:14.354  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:14.354  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:15:14.354  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-30 14:15:14.354  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-30 14:15:14.354  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:15:14.354  5869 11650 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:15:14.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:14.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:14.359 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:15:14.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-30 14:15:14.359 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:15:14.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:14.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:14.359 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:15:14.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:14.359  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-30 14:15:14.359  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:14.359  5869  5942 D BtGatt.GattService: current time is 282677644574
03-30 14:15:14.359  5869  5942 D BtGatt.GattService: Batch record : [-68, 109, -125, 27, 79, 123, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97, 0]
03-30 14:15:14.359  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -49, -59, -39, -27, 97]
03-30 14:15:14.359  5869  5942 D ScanRecord: parseFromBytes
03-30 14:15:14.359 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:14.359 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:14.359 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:14.359 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:15:14.364 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:14.364 11115 11178 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-30 14:15:14.364 11115 11178 I jxcore-log: 
,03-30 14:15:14.369 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:14.369 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-30 14:15:14.369 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:14.374 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:15:14.374 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:15:14.374 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:14.374 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:14.374 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:14.374 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:14.374 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:14.374 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:15:14.379 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:14.379 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:14.379 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:14.384 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:15:14.384 11115 11178 I jxcore-log: 
,03-30 14:15:14.384 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:14.384 11115 11178 I jxcore-log: 
,03-30 14:15:14.384 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:14.384 11115 11178 I jxcore-log: 
,03-30 14:15:14.394 11115 11178 I jxcore-log: ok 204 is stopped after calling stop
03-30 14:15:14.394 11115 11178 I jxcore-log: 
,03-30 14:15:14.399 11115 11178 I jxcore-log: ok 205 connection to servers manager should fail after stopping
03-30 14:15:14.399 11115 11178 I jxcore-log: 
,03-30 14:15:14.404 11115 11178 I jxcore-log: ok 206 connection to router server should fail after stopping
03-30 14:15:14.404 11115 11178 I jxcore-log: 
,03-30 14:15:14.414 11115 11178 I jxcore-log: # teardown
03-30 14:15:14.414 11115 11178 I jxcore-log: 
,03-30 14:15:14.684 11115 11178 I jxcore-log: ok 207 must be stopped
03-30 14:15:14.684 11115 11178 I jxcore-log: 
,03-30 14:15:14.689 11115 11178 I jxcore-log: # setup
03-30 14:15:14.689 11115 11178 I jxcore-log: 
,03-30 14:15:14.934 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:14.934 11115 11178 I jxcore-log: 
,03-30 14:15:14.939 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:14.939 11115 11178 I jxcore-log: 
,03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:14.949 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:14.949 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:14.954 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:14.954 11115 11178 I jxcore-log: 
,03-30 14:15:14.954 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:14.954 11115 11178 I jxcore-log: 
,03-30 14:15:14.959 11115 11178 I jxcore-log: # 51. make sure terminateConnection is properly hooked up
03-30 14:15:14.959 11115 11178 I jxcore-log: 
,03-30 14:15:14.964 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:14.964 11115 11178 I jxcore-log: 
,03-30 14:15:15.319 11115 11178 I jxcore-log: ok 208 called with right arguments
03-30 14:15:15.319 11115 11178 I jxcore-log: 
,03-30 14:15:15.324 11115 11178 I jxcore-log: # teardown
03-30 14:15:15.324 11115 11178 I jxcore-log: 
,03-30 14:15:15.414 11115 11178 I jxcore-log: ok 209 must be stopped
03-30 14:15:15.414 11115 11178 I jxcore-log: 
,03-30 14:15:15.419 11115 11178 I jxcore-log: # setup
03-30 14:15:15.419 11115 11178 I jxcore-log: 
,03-30 14:15:15.589 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:15.589 11115 11178 I jxcore-log: 
,03-30 14:15:15.589 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:15.589 11115 11178 I jxcore-log: 
,03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:15.599 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:15.604 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:15.609 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:15.609 11115 11178 I jxcore-log: 
,03-30 14:15:15.609 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:15.609 11115 11178 I jxcore-log: 
,03-30 14:15:15.614 11115 11178 I jxcore-log: # 52. make sure terminateListener is properly hooked up
03-30 14:15:15.614 11115 11178 I jxcore-log: 
,03-30 14:15:15.619 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:15.619 11115 11178 I jxcore-log: 
,03-30 14:15:15.804 11115 11178 I jxcore-log: ok 210 called with right arguments
03-30 14:15:15.804 11115 11178 I jxcore-log: 
,03-30 14:15:15.809 11115 11178 I jxcore-log: # teardown
03-30 14:15:15.809 11115 11178 I jxcore-log: 
,03-30 14:15:15.914 11115 11178 I jxcore-log: ok 211 must be stopped
03-30 14:15:15.914 11115 11178 I jxcore-log: 
,03-30 14:15:15.919 11115 11178 I jxcore-log: # setup
03-30 14:15:15.919 11115 11178 I jxcore-log: 
,03-30 14:15:16.054 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:16.054 11115 11178 I jxcore-log: 
,03-30 14:15:16.059 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:16.059 11115 11178 I jxcore-log: 
,03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:16.069 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:16.074 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:16.079 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:16.079 11115 11178 I jxcore-log: 
,03-30 14:15:16.079 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:16.079 11115 11178 I jxcore-log: 
,03-30 14:15:16.084 11115 11178 I jxcore-log: # 53. make sure we actually call kill connections properly
03-30 14:15:16.084 11115 11178 I jxcore-log: 
,03-30 14:15:16.084 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:16.084 11115 11178 I jxcore-log: 
,03-30 14:15:16.224 11115 11178 I jxcore-log: ok 212 specific error expected
03-30 14:15:16.224 11115 11178 I jxcore-log: 
,03-30 14:15:16.229 11115 11178 I jxcore-log: # teardown
03-30 14:15:16.229 11115 11178 I jxcore-log: 
,03-30 14:15:16.394 11115 11178 I jxcore-log: ok 213 must be stopped
03-30 14:15:16.394 11115 11178 I jxcore-log: 
,03-30 14:15:16.399 11115 11178 I jxcore-log: # setup
03-30 14:15:16.399 11115 11178 I jxcore-log: 
,03-30 14:15:16.514 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:16.514 11115 11178 I jxcore-log: 
,03-30 14:15:16.519 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:16.519 11115 11178 I jxcore-log: 
,03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:16.529 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:16.529 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:16.534 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:16.534 11115 11178 I jxcore-log: 
,03-30 14:15:16.539 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:16.539 11115 11178 I jxcore-log: 
,03-30 14:15:16.544 11115 11178 I jxcore-log: # 54. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-30 14:15:16.544 11115 11178 I jxcore-log: 
,03-30 14:15:16.544 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:16.544 11115 11178 I jxcore-log: 
,03-30 14:15:16.709 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:16.709 11115 11178 I jxcore-log: 
,03-30 14:15:16.714 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 48259
03-30 14:15:16.714 11115 11178 I jxcore-log: 
,03-30 14:15:16.719 11115 11178 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":59458,"error":{}}
03-30 14:15:16.719 11115 11178 I jxcore-log: 
,03-30 14:15:16.724 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:16.724 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:16.724 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:16.729 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:16.729 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:16.729 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:16.744 11115 11178 I jxcore-log: ok 214 failure reason is as expected
03-30 14:15:16.744 11115 11178 I jxcore-log: 
,03-30 14:15:16.744 11115 11178 I jxcore-log: ok 215 error description is as expected
03-30 14:15:16.744 11115 11178 I jxcore-log: 
,03-30 14:15:16.749 11115 11178 I jxcore-log: ok 216 must be stopped
03-30 14:15:16.749 11115 11178 I jxcore-log: 
,03-30 14:15:16.754 11115 11178 I jxcore-log: # teardown
03-30 14:15:16.754 11115 11178 I jxcore-log: 
,03-30 14:15:16.844 11115 11178 I jxcore-log: ok 217 must be stopped
03-30 14:15:16.844 11115 11178 I jxcore-log: 
,03-30 14:15:16.849 11115 11178 I jxcore-log: # setup
03-30 14:15:16.849 11115 11178 I jxcore-log: 
,03-30 14:15:16.964 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:16.964 11115 11178 I jxcore-log: 
,03-30 14:15:16.964 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:16.964 11115 11178 I jxcore-log: 
,03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:16.969 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:16.974 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:16.974 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:16.974 11115 11178 I jxcore-log: 
,03-30 14:15:16.974 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:16.974 11115 11178 I jxcore-log: 
,03-30 14:15:16.979 11115 11178 I jxcore-log: # 55. We repeat failedConnection event when we get it from thaliTcpServersManager
03-30 14:15:16.979 11115 11178 I jxcore-log: 
,03-30 14:15:16.984 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:16.984 11115 11178 I jxcore-log: 
,03-30 14:15:17.184 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:17.184 11115 11178 I jxcore-log: 
,03-30 14:15:17.189 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 60884
03-30 14:15:17.189 11115 11178 I jxcore-log: 
,03-30 14:15:17.199 11115 11178 I jxcore-log: ok 218 peerIdentifier matches
03-30 14:15:17.199 11115 11178 I jxcore-log: 
,03-30 14:15:17.199 11115 11178 I jxcore-log: ok 219 error description matches
03-30 14:15:17.199 11115 11178 I jxcore-log: 
,03-30 14:15:17.204 11115 11178 I jxcore-log: # teardown
03-30 14:15:17.204 11115 11178 I jxcore-log: 
,03-30 14:15:17.329 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:15:17.329 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:17.329 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:17.329 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-30 14:15:17.329 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:17.329 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:17.339 11115 11178 I jxcore-log: ok 220 must be stopped
03-30 14:15:17.339 11115 11178 I jxcore-log: 
,03-30 14:15:17.349 11115 11178 I jxcore-log: # setup
03-30 14:15:17.349 11115 11178 I jxcore-log: 
,03-30 14:15:17.494 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-30 14:15:17.494 11115 11178 I jxcore-log: 
,03-30 14:15:17.499 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-30 14:15:17.499 11115 11178 I jxcore-log: 
,03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-30 14:15:17.509 11115 11178 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-30 14:15:17.514 11115 11178 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-30 14:15:17.514 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-30 14:15:17.514 11115 11178 I jxcore-log: 
,03-30 14:15:17.519 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-30 14:15:17.519 11115 11178 I jxcore-log: 
,03-30 14:15:17.529 11115 11178 I jxcore-log: # 56. we successfully receive and replay discoveryAdvertisingStateUpdate
03-30 14:15:17.529 11115 11178 I jxcore-log: 
,03-30 14:15:17.534 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-30 14:15:17.534 11115 11178 I jxcore-log: 
,03-30 14:15:17.649 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:17.649 11115 11178 I jxcore-log: 
,03-30 14:15:17.654 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 35675
03-30 14:15:17.654 11115 11178 I jxcore-log: 
,03-30 14:15:17.664 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 59576, start advertisements: false
,03-30 14:15:17.664 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:17.664 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:15:17.664 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-30 14:15:17.669 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-30 14:15:17.669 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:17.669 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:17.674  5869 11651 D BtGatt.GattService: registerClient() - UUID=3fdd4182-2246-4dad-8c63-4accc81f19dc
,03-30 14:15:17.714  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=3fdd4182-2246-4dad-8c63-4accc81f19dc, clientIf=6
03-30 14:15:17.714 11115 11127 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:15:17.714  5869  5880 D BtGatt.GattService: start scan with filters
,03-30 14:15:17.729  5869  5880 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 19
,03-30 14:15:17.729  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:15:17.729  5869  5957 D BtGatt.ScanManager: isFilteringSupported
03-30 14:15:17.729  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
,03-30 14:15:17.734  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-30 14:15:17.734  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:17.734  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:15:17.734  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:15:17.734  5869  5957 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
,03-30 14:15:17.739  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:15:17.739  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:17.739  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:17.739  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:15:17.739  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-30 14:15:17.739  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:17.744  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-30 14:15:17.744  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:17.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-30 14:15:17.749 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:17.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
03-30 14:15:17.749 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:17.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 14:15:17.749 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-30 14:15:17.749 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-30 14:15:17.754 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:17.754 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:17.754 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-30 14:15:17.754 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:17.754 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:17.754 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:17.754 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:17.754 11115 11178 I jxcore-log: 
03-30 14:15:17.754 11115 11178 I jxcore-log: ok 221 discoveryActive matches
03-30 14:15:17.754 11115 11178 I jxcore-log: 
03-30 14:15:17.759 11115 11178 I jxcore-log: ok 222 advertisingActive matches
03-30 14:15:17.759 11115 11178 I jxcore-log: 
03-30 14:15:17.759 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:17.759 11115 11178 I jxcore-log: 
03-30 14:15:17.764 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-30 14:15:17.764 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:17.764 11115 11178 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-30 14:15:17.764 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:17.764 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:17.764 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:17.764 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:17.764 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:15:17.764 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:15:17.764  5869 11650 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:15:17.764  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:15:17.764  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 9
,03-30 14:15:17.764  5869 11651 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:17.764 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-30 14:15:17.764 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:17.764 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:17.764 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-30 14:15:17.764 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-30 14:15:17.764 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:17.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:17.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-30 14:15:17.769 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-30 14:15:17.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:17.769 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:17.769 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:17.769 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:17.769 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-30 14:15:17.769  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-30 14:15:17.769  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:17.769  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:17.769  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:15:17.769  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:17.769  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-30 14:15:17.774  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-30 14:15:17.774  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:17.774  5869  5942 D BtGatt.GattService: current time is 286093033366
03-30 14:15:17.774  5869  5942 D BtGatt.GattService: Batch record : [-110, 69, -15, -121, 52, 73, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-30 14:15:17.774  5869  5942 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-30 14:15:17.774  5869  5942 D ScanRecord: parseFromBytes
,03-30 14:15:17.779 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:17.784 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:17.784 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:17.784 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-30 14:15:17.784 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-30 14:15:17.784 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:17.784 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:17.784 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:17.789 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-30 14:15:17.789 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:17.789 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:17.789 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:17.789 11115 11178 I jxcore-log: 
,03-30 14:15:17.789 11115 11178 I jxcore-log: ok 223 discoveryActive matches
03-30 14:15:17.789 11115 11178 I jxcore-log: 
,03-30 14:15:17.789 11115 11178 I jxcore-log: ok 224 advertisingActive matches
03-30 14:15:17.789 11115 11178 I jxcore-log: 
,03-30 14:15:17.794 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:17.794 11115 11178 I jxcore-log: 
,03-30 14:15:17.809 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:17.809 11115 11178 I jxcore-log: 
,03-30 14:15:17.809 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 55626
03-30 14:15:17.809 11115 11178 I jxcore-log: 
,03-30 14:15:17.814 11115 11178 I io.jxcore.node.ConnectionHelper: start: Port number: 55626, start advertisements: true
,03-30 14:15:17.814 11115 11178 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-30 14:15:17.814 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-30 14:15:17.814 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-30 14:15:17.819 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-30 14:15:17.819 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-30 14:15:17.819 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-30 14:15:17.819 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-30 14:15:17.819  5869  5883 D BtGatt.GattService: registerClient() - UUID=ea73b70f-cfa5-45fd-87af-3d3d7aac8fe6
,03-30 14:15:17.864  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=ea73b70f-cfa5-45fd-87af-3d3d7aac8fe6, clientIf=6
,03-30 14:15:17.864 11115 11171 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-30 14:15:17.864  5869  5956 D BtGatt.GattService: start scan with filters
,03-30 14:15:17.919  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 20,
,03-30 14:15:17.924  5869  5957 D BtGatt.ScanManager: handling starting scan
03-30 14:15:17.924  5869  5957 D BtGatt.ScanManager: isFilteringSupported,
03-30 14:15:17.924  5869  5957 D BluetoothAdapter: setting StandAloneBleMode
03-30 14:15:17.924  5869  5942 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-30 14:15:17.924  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:17.924  5869  5957 D BtGatt.ScanManager: allow scan with filters
03-30 14:15:17.929  5869  5957 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-30 14:15:17.929  5869  5957 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-30 14:15:17.929  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-30 14:15:17.929  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:17.929  5869  5957 D BtGatt.ScanManager: Starting BLE batch scan
03-30 14:15:17.929  5869  5957 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-30 14:15:17.934  5869  5942 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-30 14:15:17.934  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:17.934  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-30 14:15:17.934  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:17.934 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-30 14:15:17.934 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-30 14:15:17.939 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-30 14:15:17.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-30 14:15:17.939 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-30 14:15:17.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-30 14:15:17.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-30 14:15:17.939 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-30 14:15:17.939 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:17.939 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-30 14:15:17.939 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-30 14:15:17.939 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-30 14:15:17.944  5869  5883 D BtGatt.GattService: registerClient() - UUID=e2fa9b17-896e-41ac-bd1e-a79eb738c623
,03-30 14:15:17.984  5869  5942 D BtGatt.GattService: onClientRegistered() - UUID=e2fa9b17-896e-41ac-bd1e-a79eb738c623, clientIf=7
,03-30 14:15:17.984 11115 11127 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-30 14:15:17.999  5869  5956 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 15
,03-30 14:15:17.999  5869  5954 D BtGatt.AdvertiseManager: message : 0
,03-30 14:15:17.999  5869  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-30 14:15:17.999  5869  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-30 14:15:18.004  5869  5954 D BtGatt.AdvertiseManager: starting advertising,
03-30 14:15:18.004  5869  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-30 14:15:18.004  5869  5942 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-30 14:15:18.014  5869  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-30 14:15:18.014  5869  5942 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-30 14:15:18.014  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-30 14:15:18.014  5869  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-30 14:15:18.014 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-30 14:15:18.014 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-30 14:15:18.019 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:18.019 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-30 14:15:18.019 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-30 14:15:18.019 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-30 14:15:18.019 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-30 14:15:18.019 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-30 14:15:18.019 11115 11178 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-30 14:15:18.019 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-30 14:15:18.019 11115 11178 I io.jxcore.node.ConnectionHelper: start: OK
03-30 14:15:18.019 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-30 14:15:18.019 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-30 14:15:18.019 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-30 14:15:18.019 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-30 14:15:18.019 11115 11115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-30 14:15:18.019 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-30 14:15:18.019 11115 11115 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-30 14:15:18.019 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-30 14:15:18.019 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-30 14:15:18.019 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:18.019 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-30 14:15:18.019 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-30 14:15:18.019 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:18.019 11115 11178 I jxcore-log: 
,03-30 14:15:18.024 11115 12067 D BluetoothSocket: bindListen(): myUserId = 0
,03-30 14:15:18.024 11115 12067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-30 14:15:18.024 11115 12067 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,03-30 14:15:18.024 11115 12067 D BluetoothSocket: bindListen(), new LocalSocket 
03-30 14:15:18.024 11115 12067 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-30 14:15:18.024 11115 12067 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d2c4dec
03-30 14:15:18.024 11115 12067 D BluetoothSocket: channel: 6
03-30 14:15:18.024 11115 12067 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-30 14:15:18.024 11115 11178 I jxcore-log: not ok 225 discoveryActive matches
03-30 14:15:18.024 11115 11178 I jxcore-log: 
03-30 14:15:18.024 11115 11178 I jxcore-log:   ---
03-30 14:15:18.024 11115 11178 I jxcore-log: 
03-30 14:15:18.024 11115 11178 I jxcore-log:     operator: equal
03-30 14:15:18.024 11115 11178 I jxcore-log: 
03-30 14:15:18.029 11115 11178 I jxcore-log:     expected: false
03-30 14:15:18.029 11115 11178 I jxcore-log: 
03-30 14:15:18.029 11115 11178 I jxcore-log:     actual:   true
03-30 14:15:18.029 11115 11178 I jxcore-log: 
03-30 14:15:18.029 11115 11178 I jxcore-log:   ...
03-30 14:15:18.029 11115 11178 I jxcore-log: 
,03-30 14:15:18.029 11115 11178 I jxcore-log: not ok 226 advertisingActive matches
03-30 14:15:18.029 11115 11178 I jxcore-log: 
,03-30 14:15:18.029 11115 11178 I jxcore-log:   ---
03-30 14:15:18.029 11115 11178 I jxcore-log: 
03-30 14:15:18.029 11115 11178 I jxcore-log:     operator: equal
03-30 14:15:18.029 11115 11178 I jxcore-log: 
03-30 14:15:18.029 11115 11178 I jxcore-log:     expected: true
03-30 14:15:18.029 11115 11178 I jxcore-log: 
03-30 14:15:18.029 11115 11178 I jxcore-log:     actual:   false
03-30 14:15:18.029 11115 11178 I jxcore-log: 
03-30 14:15:18.029 11115 11178 I jxcore-log:   ...
03-30 14:15:18.029 11115 11178 I jxcore-log: 
,03-30 14:15:18.034 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-30 14:15:18.034 11115 11178 I jxcore-log: 
,03-30 14:15:18.034 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-30 14:15:18.034 11115 11178 I jxcore-log: 
,03-30 14:15:18.039 11115 11178 I jxcore-log: not ok 227 discoveryActive matches
03-30 14:15:18.039 11115 11178 I jxcore-log: 
,03-30 14:15:18.039 11115 11178 I jxcore-log:   ---
03-30 14:15:18.039 11115 11178 I jxcore-log: 
03-30 14:15:18.039 11115 11178 I jxcore-log:     operator: equal
03-30 14:15:18.039 11115 11178 I jxcore-log: 
03-30 14:15:18.039 11115 11178 I jxcore-log:     expected: false
03-30 14:15:18.039 11115 11178 I jxcore-log: 
03-30 14:15:18.039 11115 11178 I jxcore-log:     actual:   true
03-30 14:15:18.039 11115 11178 I jxcore-log: 
03-30 14:15:18.039 11115 11178 I jxcore-log:   ...
03-30 14:15:18.039 11115 11178 I jxcore-log: 
,03-30 14:15:18.044 11115 11178 I jxcore-log: not ok 228 advertisingActive matches
03-30 14:15:18.044 11115 11178 I jxcore-log: 
,03-30 14:15:18.044 11115 11178 I jxcore-log:   ---
03-30 14:15:18.044 11115 11178 I jxcore-log: 
03-30 14:15:18.044 11115 11178 I jxcore-log:     operator: equal
03-30 14:15:18.044 11115 11178 I jxcore-log: 
03-30 14:15:18.044 11115 11178 I jxcore-log:     expected: false
03-30 14:15:18.044 11115 11178 I jxcore-log: 
03-30 14:15:18.044 11115 11178 I jxcore-log:     actual:   true
03-30 14:15:18.044 11115 11178 I jxcore-log: 
03-30 14:15:18.044 11115 11178 I jxcore-log:   ...
03-30 14:15:18.044 11115 11178 I jxcore-log: 
,03-30 14:15:18.044 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-30 14:15:18.044 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-30 14:15:18.044 11115 11178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-30 14:15:18.044 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-30 14:15:18.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-30 14:15:18.044 11115 11178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c2345b5, channel: 6, state: LISTENING
03-30 14:15:18.044 11115 11178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c2345b5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d2c4dec, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3940044amSocket: android.net.LocalSocket@3ccc8fbb impl:android.net.LocalSocketImpl@1c865cd8 fd:FileDescriptor[115]
03-30 14:15:18.044 11115 11178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ccc8fbb impl:android.net.LocalSocketImpl@1c865cd8 fd:FileDescriptor[115]
03-30 14:15:18.044 11115 11178 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-30 14:15:18.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-30 14:15:18.044 11115 12067 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-30 14:15:18.044 11115 12067 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-30 14:15:18.044 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-30 14:15:18.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-30 14:15:18.044 11115 12067 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-30 14:15:18.044 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-30 14:15:18.044 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-30 14:15:18.044 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-30 14:15:18.044 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-30 14:15:18.044 11115 11115 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-30 14:15:18.049  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
03-30 14:15:18.049  5869  5957 D BtGatt.ScanManager: filter size is 1
03-30 14:15:18.049  5869  5957 D BtGatt.ScanManager: delete FilterIndex - 10
,03-30 14:15:18.049  5869 11650 D BtGatt.GattService: unregisterClient() - clientIf=6
03-30 14:15:18.049 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-30 14:15:18.049 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-30 14:15:18.049  5869  5942 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-30 14:15:18.049 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-30 14:15:18.049  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:18.049 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-30 14:15:18.049 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-30 14:15:18.049 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-30 14:15:18.049 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-30 14:15:18.049  5869  5957 D BtGatt.ScanManager: stopping BLe Batch
03-30 14:15:18.054  5869  5954 D BtGatt.AdvertiseManager: message : 1
03-30 14:15:18.054  5869  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-30 14:15:18.054  5869  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-30 14:15:18.054  5869  5942 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-30 14:15:18.054  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-30 14:15:18.054  5869  5957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-30 14:15:18.054  5869  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-30 14:15:18.054  5869  5942 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-30 14:15:18.054  5869  5942 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-30 14:15:18.054  5869  5942 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-30 14:15:18.054  5869  5942 D BtGatt.GattService: Client app is not null!
,03-30 14:15:18.059  5869  5956 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-30 14:15:18.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-30 14:15:18.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,03-30 14:15:18.059 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-30 14:15:18.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-30 14:15:18.059 11115 11178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-30 14:15:18.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:18.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-30 14:15:18.059 11115 11178 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-30 14:15:18.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-30 14:15:18.059 11115 11178 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-30 14:15:18.059 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-30 14:15:18.059 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-30 14:15:18.059 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-30 14:15:18.064 11115 11115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-30 14:15:18.069 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-30 14:15:18.069 11115 11115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-30 14:15:18.069 11115 11115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-30 14:15:18.074 11115 11115 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-30 14:15:18.074 11115 11115 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-30 14:15:18.074 11115 11115 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-30 14:15:18.074 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-30 14:15:18.074 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-30 14:15:18.074 11115 11115 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-30 14:15:18.074 11115 11178 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-30 14:15:18.074 11115 11178 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-30 14:15:18.074 11115 11178 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-30 14:15:18.074 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-30 14:15:18.074 11115 11178 I jxcore-log: 
,03-30 14:15:18.079 11115 11178 I jxcore-log: ok 229 discoveryActive matches
03-30 14:15:18.079 11115 11178 I jxcore-log: 
,03-30 14:15:18.084 11115 11178 I jxcore-log: not ok 230 advertisingActive matches
03-30 14:15:18.084 11115 11178 I jxcore-log: 
,03-30 14:15:18.084 11115 11178 I jxcore-log:   ---
03-30 14:15:18.084 11115 11178 I jxcore-log: 
03-30 14:15:18.084 11115 11178 I jxcore-log:     operator: equal
03-30 14:15:18.084 11115 11178 I jxcore-log: 
03-30 14:15:18.084 11115 11178 I jxcore-log:     expected: false
03-30 14:15:18.084 11115 11178 I jxcore-log: 
03-30 14:15:18.084 11115 11178 I jxcore-log:     actual:   true
03-30 14:15:18.084 11115 11178 I jxcore-log: 
03-30 14:15:18.084 11115 11178 I jxcore-log:   ...
03-30 14:15:18.084 11115 11178 I jxcore-log: 
,03-30 14:15:18.089 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:18.089 11115 11178 I jxcore-log: 
,03-30 14:15:18.089 11115 11178 I jxcore-log: ok 231 discoveryActive matches
03-30 14:15:18.089 11115 11178 I jxcore-log: 
,03-30 14:15:18.089  3481  4731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-30 14:15:18.089  3481  4731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-30 14:15:18.089 11115 11178 I jxcore-log: ok 232 advertisingActive matches
03-30 14:15:18.089 11115 11178 I jxcore-log: 
03-30 14:15:18.089  3481  4731 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
03-30 14:15:18.089  3481  4731 D BatteryService: stay LED for fully charged
,03-30 14:15:18.089  3481  3481 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-30 14:15:18.094  3481  3481 I MotionRecognitionService: Plugged
,03-30 14:15:18.094  3481  3481 D MotionRecognitionService:   cableConnection= 1
03-30 14:15:18.094  3481  3481 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-30 14:15:18.094  3481  3481 D MotionRecognitionService: skip setTransmitPower. 
03-30 14:15:18.094 11115 11178 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-30 14:15:18.094 11115 11178 I jxcore-log: 
,03-30 14:15:18.094  3723  3723 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:15:18.094  3723  3723 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-30 14:15:18.094  3723  3723 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-30 14:15:18.104  5869  5869 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-30 14:15:18.104  5869  5977 D HeadsetStateMachine: Disconnected process message: 10
,03-30 14:15:18.109 11115 11178 I jxcore-log: DEBUG createNativeListener: creating native server
03-30 14:15:18.109 11115 11178 I jxcore-log: 
,03-30 14:15:18.114 11115 11178 I jxcore-log: DEBUG createNativeListener: listening 41837
03-30 14:15:18.114 11115 11178 I jxcore-log: 
,03-30 14:15:18.124  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-30 14:15:18.124  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:15:18.124  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-30 14:15:18.124  3723  3723 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-30 14:15:18.124 11115 11178 I jxcore-log: Uncaught Promise Rejection: {}
03-30 14:15:18.124 11115 11178 I jxcore-log: 
,03-30 14:15:18.129 11115 11178 E jxcore-log: Trace: [Error: Call Stop!]
03-30 14:15:18.129 11115 11178 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-30 14:15:18.129 11115 11178 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-30 14:15:18.129 11115 11178 E jxcore-log:     at emit@events.js:98:1
03-30 14:15:18.129 11115 11178 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-30 14:15:18.129 11115 11178 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-30 14:15:18.129 11115 11178 E jxcore-log:     at $0a@node.js:917:1
03-30 14:15:18.129 11115 11178 E jxcore-log: 
,03-30 14:15:18.129 11115 11178 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-30 14:15:18.129 11115 11178 I jxcore-log: 
,03-30 14:15:18.129 11115 11178 I jxcore-log: # teardown
03-30 14:15:18.129 11115 11178 I jxcore-log: 
,03-30 14:15:18.309  3481  6076 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:14), CUR = 34, LCD = 0
,03-30 14:15:18.574 12073 12073 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-30 14:15:18.579 12073 12073 D AndroidRuntime: CheckJNI is OFF
,03-30 14:15:18.579 12073 12073 D AndroidRuntime: readGMSProperty: start
03-30 14:15:18.579 12073 12073 D AndroidRuntime: readGMSProperty: already setted!!
03-30 14:15:18.579 12073 12073 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-30 14:15:18.579 12073 12073 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-30 14:15:18.579 12073 12073 D AndroidRuntime: readGMSProperty: end
03-30 14:15:18.579 12073 12073 D AndroidRuntime: addProductProperty: start
,03-30 14:15:18.674 12073 12073 E AffinityControl: AffinityControl: registerfunction enter
,03-30 14:15:18.694 12073 12073 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-30 14:15:18.704  3481  4734 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,03-30 14:15:18.704  3481  4734 D PackageManager: START PACKAGE DELETE: observer{98630329}
03-30 14:15:18.704  3481  4734 D PackageManager: pkg{<packageName>}
03-30 14:15:18.704  3481  4734 D PackageManager: user{0}
03-30 14:15:18.704  3481  4734 D PackageManager: caller{2000}
03-30 14:15:18.704  3481  4734 D PackageManager: flags{2}
03-30 14:15:18.704  3481  4734 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-30 14:15:18.704  3481  4734 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,03-30 14:15:18.704  3481  3590 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-30 14:15:18.704  3481  4734 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-30 14:15:18.704  3481  4734 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-30 14:15:18.704  3481  3590 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,03-30 14:15:18.704  3481  3590 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-30 14:15:18.704  3481  3590 D ApplicationPolicy: getApplicationUninstallationEnabled
03-30 14:15:18.704  3481  3590 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-30 14:15:18.709  3481  3590 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-30 14:15:18.714  3481  3569 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-30 14:15:18.714  3481  3569 I ActivityManager: Killing 11115:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-30 14:15:18.724  3481  3569 I ActivityManager:   Force finishing activity 3 ActivityRecord{90231a3 u0 com.test.thalitest/.MainActivity t42}
,03-30 14:15:18.729  3481  3569 W ActivityManager: mDVFSHelper.acquire()
,03-30 14:15:18.829  3481  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-30 14:15:18.829  3481  3590 W PackageSettings: Skipping PackageSetting{1aca88bc com.example.hello/10691} due to missing metadata
,03-30 14:15:18.854  3481  3590 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-30 14:15:18.854  3481  3569 D PowerManagerService: setKeyboardVisibility: false
03-30 14:15:18.854  3481  3569 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{198e1870 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
,03-30 14:15:18.864  3481  3509 I WindowState: WIN DEATH: Window{a351f39 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
03-30 14:15:18.864  2860  4065 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
03-30 14:15:18.864  2860  3009 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-30 14:15:18.869  3481  3509 D InputDispatcher: Focus left window: 11115
,03-30 14:15:18.869  3481  3509 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-30 14:15:18.869  2860  3009 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-30 14:15:18.879  3481  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
03-30 14:15:18.879  3481  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
03-30 14:15:18.879  3481  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-30 14:15:18.879  3481  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-30 14:15:18.889  3481  3590 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
,03-30 14:15:18.894  3481  3590 I ActivityManager:   Force finishing activity 3 ActivityRecord{90231a3 u0 com.test.thalitest/.MainActivity t42 f}
03-30 14:15:18.894  3481  3590 W ActivityManager: Duplicate finish request for ActivityRecord{90231a3 u0 com.test.thalitest/.MainActivity t42 f}
,03-30 14:15:18.919  3481  3590 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-30 14:15:18.929  9065  9065 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 405us total 19.454ms
,03-30 14:15:18.934  3921  3921 I art     : Explicit concurrent mark sweep GC freed 1673(87KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 468us total 19.716ms
,03-30 14:15:18.944  6574  6574 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
,03-30 14:15:18.944  3481  3689 D TaskPersister: removeObsoleteFile: deleting file=42_task.xml
03-30 14:15:18.944  3481  3689 D TaskPersister: removeObsoleteFile: deleting file=42_task_thumbnail.png
03-30 14:15:18.949  3481  3569 D InputDispatcher: Focused application released
,03-30 14:15:18.959  4657  4657 I art     : Explicit concurrent mark sweep GC freed 3024(187KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 845us total 59.608ms
,03-30 14:15:18.964  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
03-30 14:15:18.964  4129  4129 I art     : Explicit concurrent mark sweep GC freed 17(12KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 580us total 69.313ms
,03-30 14:15:18.974  4030  4030 I art     : Explicit concurrent mark sweep GC freed 16016(920KB) AllocSpace objects, 10(1506KB) LOS objects, 12% free, 56MB/64MB, paused 560us total 47.491ms
,03-30 14:15:18.979  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-30 14:15:18.984  3481  3630 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-30 14:15:18.984  3723  3723 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-30 14:15:18.984  4494  4494 E SamsungIME: mOCRHelper is null
,03-30 14:15:18.989  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-30 14:15:18.989  4412  4840 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-30 14:15:18.989  6574  6574 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
,03-30 14:15:18.994 10615 10615 D LWLocationManager: getDeviceLocationId :  id = -100
,03-30 14:15:18.994 10615 10615 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-30 14:15:18.994  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-30 14:15:18.999  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:18.999  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:18.999  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:18.999  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.009 12097 12097 E Zygote  : MountEmulatedStorage()
03-30 14:15:19.009 12097 12097 E Zygote  : v2
03-30 14:15:19.009 12097 12097 I libpersona: KNOX_SDCARD checking this for 10063
03-30 14:15:19.009 12097 12097 I libpersona: KNOX_SDCARD not a persona
,03-30 14:15:19.014 12097 12097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.014  3481  3569 I ActivityManager: Start proc 12097:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
,03-30 14:15:19.019 12097 12097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-30 14:15:19.019 12097 12097 E Zygote  : accessInfo : 0
,03-30 14:15:19.019 12097 12097 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.019  5564  5583 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-30 14:15:19.019  5564  5583 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-30 14:15:19.024  6574  6574 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-30 14:15:19.024  6574  6574 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-30 14:15:19.034  3481  3650 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-30 14:15:19.034  3481  3650 D NtpTrustedTime: currentTimeMillis() cache hit
03-30 14:15:19.034  3481  3650 V NetworkStats: performPollLocked(flags=0x3)
,03-30 14:15:19.039  3998  3998 D RegisteredServicesCache: empty dynamic service
,03-30 14:15:19.039  3481  3650 V NetworkStats: performPollLocked() took 7ms
03-30 14:15:19.039  3481  3650 D NtpTrustedTime: currentTimeMillis() cache hit
,03-30 14:15:19.049 12097 12097 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:15:19.049 12097 12097 D ActivityThread: Added TimaKeyStore provider
,03-30 14:15:19.049  3998  3998 D RegisteredComponentCache: Collect Tech packages for Knox
,03-30 14:15:19.059  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-30 14:15:19.059  3481  4733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{338a48ac u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{350d8975 12097:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-30 14:15:19.079  3481  4733 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-30 14:15:19.079  3481  4733 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-30 14:15:19.084  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,03-30 14:15:19.089  3481  3481 I art     : Explicit concurrent mark sweep GC freed 34056(2MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 29MB/44MB, paused 2.304ms total 168.296ms
03-30 14:15:19.089  3481  3590 I art     : WaitForGcToComplete blocked for 65.327ms for cause Explicit
,03-30 14:15:19.089  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-30 14:15:19.099  6574  6574 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-30 14:15:19.099  3481  3651 D NtpTrustedTime: currentTimeMillis() cache hit
03-30 14:15:19.099  3481  3651 D NtpTrustedTime: currentTimeMillis() cache hit
,03-30 14:15:19.099  6574  6574 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-30 14:15:19.099  6574  6574 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
,03-30 14:15:19.104  6574  6574 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-30 14:15:19.104  3481  3831 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-30 14:15:19.104  3481  3831 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-30 14:15:19.104  3481  3831 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-30 14:15:19.104 12097 12097 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-30 14:15:19.104 12097 12097 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove,
03-30 14:15:19.104 12097 12097 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
03-30 14:15:19.104  2860  2860 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
03-30 14:15:19.109  3481  3743 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-30 14:15:19.109  3481  3580 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5dd1ee u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
,03-30 14:15:19.109  3481  4731 I ActivityManager: Killing 10008:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
03-30 14:15:19.109  3481  3743 D InputDispatcher: Focus entered window: 6574
,03-30 14:15:19.114  3481  3582 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3481 uid:1000
,03-30 14:15:19.114  3481  4731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{338a48ac u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1227dbd3 7152:com.samsung.klmsagent/u0a21},
03-30 14:15:19.114  3481  3582 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-30 14:15:19.114  3481  3831 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-30 14:15:19.114  3481  3582 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3481 uid:1000
03-30 14:15:19.114  3481  3582 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-30 14:15:19.114  6574  6574 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-30 14:15:19.114  6574  9084 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-30 14:15:19.114  7152  7152 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 30 14:15:19 GMT+02:00 2016
03-30 14:15:19.114  6574  6574 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
,03-30 14:15:19.124  7152  7152 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-30 14:15:19.124  3481  4046 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-30 14:15:19.124  7152  7152 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
,03-30 14:15:19.129  7152  7152 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-30 14:15:19.129  7152  7152 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-30 14:15:19.129  7152 12114 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
,03-30 14:15:19.129  7152 12114 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-30 14:15:19.129  7152 12114 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-30 14:15:19.129  7152 12114 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
,03-30 14:15:19.134  3481  3960 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
,03-30 14:15:19.134  7152 12114 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-30 14:15:19.134  7152 12114 I KLMS-2.5.262: : MDMBridge.getInstance()
03-30 14:15:19.134  3481  3730 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-30 14:15:19.134  7152 12114 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-30 14:15:19.134  3481  3960 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,03-30 14:15:19.139  7152 12114 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-30 14:15:19.139  3481  3730 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 11115 uid 10011
03-30 14:15:19.139  7152 12114 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-30 14:15:19.139  3481  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{338a48ac u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1e0fa69a 6814:com.samsung.aasaservice/1000}
,03-30 14:15:19.144  6814  6814 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,03-30 14:15:19.144  4494  4494 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-30 14:15:19.144  7152 12114 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-30 14:15:19.149  6814  6814 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-30 14:15:19.149  6814  6814 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-30 14:15:19.149  6814  6814 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
,03-30 14:15:19.149  6814  6814 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-30 14:15:19.149  7152 12114 E KLMS-2.5.262: : arr si null
03-30 14:15:19.149  6814  6814 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
,03-30 14:15:19.149  3481  3566 D EnterpriseDeviceManagerService: Package has changed for user 0
03-30 14:15:19.149  6814  6814 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-30 14:15:19.149  6814  6814 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.149  6814  6814 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.149  6814  6814 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-30 14:15:19.149  6814  6814 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.149  6814  6814 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.149  6814  6814 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.149  6814  6814 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-30 14:15:19.154  7152 12114 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-30 14:15:19.154  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.154  7152 12114 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-30 14:15:19.154  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.154  7152 12114 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-30 14:15:19.154  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.154  7152 12114 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
03-30 14:15:19.154  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.154  3481  3566 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-30 14:15:19.159  3481  3566 W TextServicesManagerService: no available spell checker services found
,03-30 14:15:19.164  6574  6574 V ActivityThread: updateVisibility : ActivityRecord{83f17ad token=android.os.BinderProxy@207a0b7b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,03-30 14:15:19.164  6574  6574 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@207a0b7b time:287484
,03-30 14:15:19.179  3481  3569 I ActivityManager: Start proc 12118:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,03-30 14:15:19.179 12118 12118 E Zygote  : MountEmulatedStorage()
,03-30 14:15:19.184 12118 12118 E Zygote  : v2
03-30 14:15:19.184 12118 12118 I libpersona: KNOX_SDCARD checking this for 10042
03-30 14:15:19.184 12118 12118 I libpersona: KNOX_SDCARD not a persona
,03-30 14:15:19.184 12118 12118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.184  3481  3569 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{880bf47 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{fab684b 10845:com.samsung.android.sm/1000}
03-30 14:15:19.184 12118 12118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-30 14:15:19.184 12118 12118 E Zygote  : accessInfo : 0
,03-30 14:15:19.184 12118 12118 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.189  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.189  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.189  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.189  3481  3569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.204 12132 12132 E Zygote  : MountEmulatedStorage()
03-30 14:15:19.204 12132 12132 E Zygote  : v2
03-30 14:15:19.204 12132 12132 I libpersona: KNOX_SDCARD checking this for 1000
03-30 14:15:19.204 12132 12132 I libpersona: KNOX_SDCARD not a persona
,03-30 14:15:19.204 12132 12132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.204 12118 12118 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:15:19.209 12118 12118 D ActivityThread: Added TimaKeyStore provider
,03-30 14:15:19.209 12132 12132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-30 14:15:19.209  3481  3569 I ActivityManager: Start proc 12132:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
03-30 14:15:19.209 12132 12132 E Zygote  : accessInfo : 0
03-30 14:15:19.209 12132 12132 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.214 10845 10845 I art     : Explicit concurrent mark sweep GC freed 1421(69KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 1784KB/3MB, paused 577us total 14.571ms
,03-30 14:15:19.224 12132 12132 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:15:19.224 12132 12132 D ActivityThread: Added TimaKeyStore provider
,03-30 14:15:19.229  3481  4679 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{11034374 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1ca9409d 12118:com.samsung.android.sdk.samsunglink/u0a42}
,03-30 14:15:19.229  7152 12114 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
,03-30 14:15:19.229  7152 12114 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-30 14:15:19.229  7152 12114 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-30 14:15:19.229  7152 12114 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-30 14:15:19.229  3481  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{338a48ac u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{8aec41c 3481:system/1000}
,03-30 14:15:19.229  3481  3590 I art     : Explicit concurrent mark sweep GC freed 9808(703KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 29MB/44MB, paused 6.069ms total 142.111ms
,03-30 14:15:19.234 12118 12118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-30 14:15:19.234  3481  3582 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{198e1870 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:287553
03-30 14:15:19.234  3481  3582 W ActivityManager: mDVFSHelper.release()
03-30 14:15:19.234 12118 12118 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-30 14:15:19.244  7152 12114 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-30 14:15:19.244  7152 12114 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-30 14:15:19.244  3481  3510 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1c2e8912 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{38008e3 12132:com.sec.android.app.popupuireceiver/1000}
03-30 14:15:19.244  7152 12114 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-30 14:15:19.244  7152 12114 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-30 14:15:19.249  7152  7152 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,03-30 14:15:19.259  3481  3960 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{880bf47 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{fab684b 10845:com.samsung.android.sm/1000}
,03-30 14:15:19.264 12132 12132 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-30 14:15:19.269  3481  3960 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{880bf47 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{fab684b 10845:com.samsung.android.sm/1000}
,03-30 14:15:19.269  3481  4731 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-30 14:15:19.274  3481  4021 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-30 14:15:19.274  3481  3960 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.274  3481  3960 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.274  3481  3960 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.274  3481  3960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.274 12132 12132 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,03-30 14:15:19.274  3481  4734 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
,03-30 14:15:19.279 12132 12132 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-30 14:15:19.279 12132 12132 D PopupuiReceiver: Action package removed
,03-30 14:15:19.284 12149 12149 E Zygote  : MountEmulatedStorage()
03-30 14:15:19.284 12149 12149 E Zygote  : v2
03-30 14:15:19.284 12149 12149 I libpersona: KNOX_SDCARD checking this for 1000
03-30 14:15:19.284 12149 12149 I libpersona: KNOX_SDCARD not a persona
,03-30 14:15:19.289 12149 12149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.289 10845 12148 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-30 14:15:19.294  3481  3960 I ActivityManager: Start proc 12149:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,03-30 14:15:19.294 12149 12149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-30 14:15:19.294 12149 12149 E Zygote  : accessInfo : 0
,03-30 14:15:19.294 12149 12149 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.299  3481  3730 I ActivityManager: Killing 10269:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-30 14:15:19.299  3481  3960 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1c2e8912 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{efd2b40 10543:com.samsung.android.snote/u0a160}
,03-30 14:15:19.304 10615 12105 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-30 14:15:19.309  3481  4763 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.309  3481  4763 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.309  3481  4763 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.309  3481  4763 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.309  4030  4030 D Launcher.Model: reloadBadges entered.
,03-30 14:15:19.309 10715 10724 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
03-30 14:15:19.309 10715 10724 D BadgeProvider: sendNotify, [notify] : null
03-30 14:15:19.309 10715 10724 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-30 14:15:19.309 10715 10724 D BadgeProvider: update, [uri.query] : null
03-30 14:15:19.309 10715 10724 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-30 14:15:19.309 10715 10724 D BadgeProvider: update, [UpdateCount] : 1
,03-30 14:15:19.314 12149 12149 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:15:19.314 12149 12149 D ActivityThread: Added TimaKeyStore provider
,03-30 14:15:19.319  3481  3590 D PackageManager: delete codoeFile: 
03-30 14:15:19.319  3481  3590 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
,03-30 14:15:19.324  3481  3590 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
,03-30 14:15:19.324 12165 12165 E Zygote  : MountEmulatedStorage()
,03-30 14:15:19.324 12165 12165 I libpersona: KNOX_SDCARD checking this for 10183
03-30 14:15:19.324 12165 12165 E Zygote  : v2
03-30 14:15:19.324 12165 12165 I libpersona: KNOX_SDCARD not a persona
03-30 14:15:19.324 12165 12165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.324  3481  3590 I AASA_removePackage: UID=10011 Target=com.test.thalitest
,03-30 14:15:19.324 12165 12165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-30 14:15:19.324  3481  3590 D PackageManager: result of delete: 1{98630329}
03-30 14:15:19.324 12165 12165 E Zygote  : accessInfo : 0
,03-30 14:15:19.324 12165 12165 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.329  3481  4763 I ActivityManager: Start proc 12165:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
03-30 14:15:19.329 12073 12073 I art     : System.exit called, status: 0
03-30 14:15:19.329 12073 12073 I AndroidRuntime: VM exiting with result code 0.
,03-30 14:15:19.334  3481  3590 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-30 14:15:19.334  3481  3590 D PackageManager: userId{-1}
03-30 14:15:19.334  3481  3590 D PackageManager: andCode{true}
,03-30 14:15:19.339 12165 12165 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:15:19.339 12165 12165 D ActivityThread: Added TimaKeyStore provider
03-30 14:15:19.339  3481  4046 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{880bf47 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2bec8879 12149:com.samsung.android.app.assistantmenu/1000}
,03-30 14:15:19.344  3481  3566 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-30 14:15:19.349 10715 10724 D BadgeProvider: query, [selection] : null
,03-30 14:15:19.354 12118 12118 I SL_DEBUG: isLoggable:: isProductShip = 1
,03-30 14:15:19.354 12118 12118 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,03-30 14:15:19.359  9750 12183 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,03-30 14:15:19.359  9750 12183 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
03-30 14:15:19.359  3481  3509 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1c2e8912 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{28736222 12165:com.samsung.android.provider.shootingmodeprovider/u0a183}
03-30 14:15:19.359  9750 12183 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-30 14:15:19.359  9750 12183 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
,03-30 14:15:19.359  9750 12183 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-30 14:15:19.359  9750 12183 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
,03-30 14:15:19.369 10615 12105 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-30 14:15:19.369 10615 12105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-30 14:15:19.369 10615 12105 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-30 14:15:19.369 10615 12105 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-30 14:15:19.374 12149 12149 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
,03-30 14:15:19.374 12165 12165 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-30 14:15:19.374  3481  3510 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-30 14:15:19.384  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.384  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.384  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.384  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.394  3481  3566 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-30 14:15:19.394  3481  3566 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-30 14:15:19.394  3481  3566 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-30 14:15:19.394  3481  3566 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-30 14:15:19.404 12188 12188 E Zygote  : MountEmulatedStorage()
,03-30 14:15:19.404 12188 12188 E Zygote  : v2
03-30 14:15:19.404 12188 12188 I libpersona: KNOX_SDCARD checking this for 1000
03-30 14:15:19.404 12188 12188 I libpersona: KNOX_SDCARD not a persona
,03-30 14:15:19.404 12188 12188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.404  3481  4733 I ActivityManager: Start proc 12188:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
,03-30 14:15:19.409  3481  3960 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,03-30 14:15:19.409 12188 12188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-30 14:15:19.414 12188 12188 E Zygote  : accessInfo : 0
,03-30 14:15:19.414 12188 12188 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.419  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.419  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.419  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.419  3481  4733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-30 14:15:19.429  2902  2902 I art     : Explicit concurrent mark sweep GC freed 8758(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 440us total 26.103ms
,03-30 14:15:19.434 12188 12188 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:15:19.434 12188 12188 D ActivityThread: Added TimaKeyStore provider
,03-30 14:15:19.444  3481  3481 D RCPManagerService: PackageReceiver onReceive()
03-30 14:15:19.444  3481  3481 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-30 14:15:19.444  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 302us total 13.194ms
,03-30 14:15:19.449  3481  3481 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-30 14:15:19.449  3481  3481 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-30 14:15:19.449  3481  3481 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-30 14:15:19.454  2902  2902 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 296us total 8.063ms
,03-30 14:15:19.459  3481  3481 I OTPFW   : ProvisionData::getAllEntries Enter
,03-30 14:15:19.459  3481  3481 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-30 14:15:19.464  3481  3481 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-30 14:15:19.464  3481  3481 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-30 14:15:19.469 12204 12204 E Zygote  : MountEmulatedStorage()
03-30 14:15:19.469 12204 12204 E Zygote  : v2
03-30 14:15:19.469 12204 12204 I libpersona: KNOX_SDCARD checking this for 10190
03-30 14:15:19.469 12204 12204 I libpersona: KNOX_SDCARD not a persona
,03-30 14:15:19.469 12204 12204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.469 12204 12204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-30 14:15:19.469  3481  4733 I ActivityManager: Start proc 12204:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
03-30 14:15:19.469 12204 12204 E Zygote  : accessInfo : 0
03-30 14:15:19.469 12204 12204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.474  3481  3566 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-30 14:15:19.474  3481  3566 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicy: uID is 10011
03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicy: Removed Packageuid is0
03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-30 14:15:19.474  4030  4030 E Launcher.Model: onPackageRemoved :com.test.thalitest
03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-30 14:15:19.474  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-30 14:15:19.479  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-30 14:15:19.479  3481  3481 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-30 14:15:19.479  3481  3481 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-30 14:15:19.479  3481  3481 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
,03-30 14:15:19.484  3481  3509 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{880bf47 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{16c1bfa9 12188:com.sec.knox.bridge/1000}
03-30 14:15:19.484  3481  3481 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,03-30 14:15:19.484  3481  3592 D EnterprisePartitionManager: RCV <-
03-30 14:15:19.484  3481  3481 D EnterprisePartitionManager: RMV <-
,03-30 14:15:19.489  3481  4733 I ActivityManager: Killing 10302:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
,03-30 14:15:19.489 12204 12204 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-30 14:15:19.494 12204 12204 D ActivityThread: Added TimaKeyStore provider
,03-30 14:15:19.494  3481  4733 I ActivityManager: Killing 10397:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-30 14:15:19.499 12188 12188 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-30 14:15:19.504  3481  3481 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-30 14:15:19.509  3481  6076 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-30 14:15:19.509  3481  3481 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-30 14:15:19.509  2858  3049 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
03-30 14:15:19.509  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:15:19.509  2858  3049 W Vold    : Returning OperationFailed - no handler for errno 0
03-30 14:15:19.509  3481  3481 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-30 14:15:19.509  3481  3481 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-30 14:15:19.509  3481  3481 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-30 14:15:19.509  3481  3481 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-30 14:15:19.509  3481  3481 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-30 14:15:19.509  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.509  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.509  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.509  3481  3481 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-30 14:15:19.509  3481  3481 W System.err: 	at libcore.io.Posix.open(Native Method)
03-30 14:15:19.509  3481  3481 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:15:19.509  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:15:19.509  3481  3481 W System.err: 	... 18 more
03-30 14:15:19.509  3481  3481 E SdpManagerService: failed to get engine list
03-30 14:15:19.509  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-30 14:15:19.509  3481  3481 V EnterpriseBillingPolicy: uID is 10011
03-30 14:15:19.509  3481  3481 V EnterpriseBillingPolicy: Removed Packageuid is0
03-30 14:15:19.509  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-30 14:15:19.514  3481  3481 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-30 14:15:19.514  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-30 14:15:19.514  3481  3481 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-30 14:15:19.514  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-30 14:15:19.514 12118 12118 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
03-30 14:15:19.514  3481  3481 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-30 14:15:19.519  3481  3960 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1c2e8912 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1e9a492e 12204:com.sec.android.widgetapp.tapandpay/u0a190}
03-30 14:15:19.519  3481  3934 E SQLiteLog: (28) failed to open "/data/system/slocation.db" with flag (131138) and mode_t (0) due to error (30)
03-30 14:15:19.519  3481  6076 E SQLiteLog: (28) failed to open "/data/system/powerManager" with flag (131138) and mode_t (0) due to error (30)
03-30 14:15:19.524 12118 12118 D SecWifiDisplayUtil: Metadata value : none
03-30 14:15:19.524  3481  3481 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-30 14:15:19.524  3481  3481 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-30 14:15:19.524  3481  3481 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-30 14:15:19.529  3481  3481 I EnterpriseSharedDevicePolicy: Get Result: -1
03-30 14:15:19.529  3481  3481 I EnterpriseSharedDevicePolicy: status: false
03-30 14:15:19.529  3481  3481 I KnoxTimeoutHandler: Shared devices show user statefalse
03-30 14:15:19.529  3481  3481 D PersonaManagerService: getPersonasForUser(): returning null!
03-30 14:15:19.529  3723  3723 D PanelView: There is/are notification(s) 
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: Failed to open database '/data/system/powerManager'.
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: #################################################################
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: #################################################################
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at com.android.internal.os.BatteryStatsDBHelper.deleteTableForApp(BatteryStatsDBHelper.java:779)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at com.android.internal.os.BatteryStatsDumper.deleteTableForApp(BatteryStatsDumper.java:444)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at com.android.server.ssrm.be.handleMessage(Unknown Source)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.529  3481  6076 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: SSRM Handler Thread
03-30 14:15:19.529  3481  6076 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.529  3481  6076 E AndroidRuntime: #################################################################
03-30 14:15:19.529  3481  6076 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.529  3481  6076 E AndroidRuntime: #################################################################
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at com.android.internal.os.BatteryStatsDBHelper.deleteTableForApp(BatteryStatsDBHelper.java:779)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at com.android.internal.os.BatteryStatsDumper.deleteTableForApp(BatteryStatsDumper.java:444)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at com.android.server.ssrm.be.handleMessage(Unknown Source)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.529  3481  6076 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 14:15:19.534  6143  6143 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive(),
03-30 14:15:19.534  3481  3481 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{338a48ac u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{399b7e88 6143:com.sec.android.service.health/u0a19}
03-30 14:15:19.534  6143  6143 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-30 14:15:19.534  3481  3481 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-30 14:15:19.534  6143  6143 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-30 14:15:19.539  3481  3960 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{338a48ac u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3ac8b31b 10615:com.sec.android.widgetapp.locationwidget/u0a22}
03-30 14:15:19.539 10615 10615 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: Failed to open database '/data/system/slocation.db'.
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: #################################################################
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: #################################################################
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:920)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:893)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:274)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at com.samsung.location.lib.SecureDBAdapter$DBAdapter.f(Unknown Source)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at com.samsung.location.lib.SecureDBAdapter$DBAdapter.b(Unknown Source)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at com.samsung.location.lib.SecureDBAdapter.a(Unknown Source)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at com.samsung.location.lib.p.a(Unknown Source)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at com.samsung.location.b.d.a(Unknown Source)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at com.samsung.location.lib.n.handleMessage(Unknown Source)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at com.samsung.location.SLocationService.run(Unknown Source)
03-30 14:15:19.549  3481  3934 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.549  3481  3934 E SLocation: getSGeofenceIdListForPackage got exceptionandroid.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.549  3481  3934 E SLocation: #################################################################
03-30 14:15:19.549  3481  3934 E SLocation: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.549  3481  3934 E SLocation: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.549  3481  3934 E SLocation: #################################################################
03-30 14:15:19.549  3481  3934 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.549  3481  3934 W System.err: #################################################################
03-30 14:15:19.549  3481  3934 W System.err: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.554  3481  3934 W System.err: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.554  3481  3934 W System.err: #################################################################
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:920)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:893)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:274)
03-30 14:15:19.554  3481  3934 W System.err: 	at com.samsung.location.lib.SecureDBAdapter$DBAdapter.f(Unknown Source)
03-30 14:15:19.554  3481  3934 W System.err: 	at com.samsung.location.lib.SecureDBAdapter$DBAdapter.b(Unknown Source)
03-30 14:15:19.554  3481  3934 W System.err: 	at com.samsung.location.lib.SecureDBAdapter.a(Unknown Source)
03-30 14:15:19.554  3481  3934 W System.err: 	at com.samsung.location.lib.p.a(Unknown Source)
03-30 14:15:19.554  3481  3934 W System.err: 	at com.samsung.location.b.d.a(Unknown Source)
03-30 14:15:19.554  3481  3934 W System.err: 	at com.samsung.location.lib.n.handleMessage(Unknown Source)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.554  3481  3934 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.554  3481  3934 W System.err: 	at com.samsung.location.SLocationService.run(Unknown Source)
03-30 14:15:19.554  3481  3934 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.564  3481  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-30 14:15:19.564  3481  3602 D UsbHostManager: displayNotification : [02h,02h,01h]
03-30 14:15:19.564  3481  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-30 14:15:19.564  3481  3602 D UsbHostManager: displayNotification : [0ah,00h,00h]
03-30 14:15:19.569  3481  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-30 14:15:19.569  3481  3602 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-30 14:15:19.569  3481  6076 E android.os.Debug: ro.product_ship = true
03-30 14:15:19.569  3481  6076 E android.os.Debug: ro.debug_level = 0x4f4c
03-30 14:15:19.574  3481  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-30 14:15:19.574  3481  3602 D UsbHostManager: displayNotification : [0ah,00h,01h]
03-30 14:15:19.574  3481  3481 W System.err: java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
03-30 14:15:19.574  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:15:19.574  3481  4041 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
03-30 14:15:19.574  3481  3481 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 14:15:19.574  3481  3481 W System.err: 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
03-30 14:15:19.574  3481  3481 W System.err: 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
03-30 14:15:19.574  3481  3481 W System.err: 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
03-30 14:15:19.574  3481  3481 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.574  3481  3481 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.574  3481  3481 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-30 14:15:19.579  3481  3602 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-30 14:15:19.574  3481  3481 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-30 14:15:19.579  3481  3602 D UsbHostManager: displayNotification : [09h,00h,00h]
03-30 14:15:19.574  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.579  3481  3691 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-30 14:15:19.574  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.579  3481  3691 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-30 14:15:19.574  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.579  3481  3691 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
03-30 14:15:19.574  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.574  3481  3481 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 14:15:19.574  3481  3481 W System.err: 	at libcore.io.Posix.open(Native Method)
03-30 14:15:19.574  3481  3481 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:15:19.574  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:15:19.574  3481  3481 W System.err: 	... 12 more
03-30 14:15:19.574  3481  3481 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/harmony_third_party_apps.xml.tmp
03-30 14:15:19.579  3481  3481 W System.err: java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
03-30 14:15:19.579  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:15:19.579  3481  3481 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 14:15:19.579  3481  3481 W System.err: 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
03-30 14:15:19.579  3481  3481 W System.err: 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
03-30 14:15:19.579  3481  3481 W System.err: 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
03-30 14:15:19.579  3481  3481 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.579  3481  3481 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.579  3481  3481 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-30 14:15:19.579  3481  3481 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-30 14:15:19.579  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.579  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.579  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.579  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.579  3481  3481 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 14:15:19.579  3481  3481 W System.err: 	at libcore.io.Posix.open(Native Method)
03-30 14:15:19.579  3481  3481 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:15:19.579  3481  3481 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:15:19.579  3481  3481 W System.err: 	... 12 more
03-30 14:15:19.579  3481  3481 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/harmony_third_party_apps.xml.tmp
03-30 14:15:19.579  3481  6076 W System.err: remove failed: EROFS (Read-only file system) : /data/system/dropbox/event_data@1459080688124.txt
03-30 14:15:19.584 12204 12204 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-30 14:15:19.584 12204 12204 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: Can't write: system_server_crash
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:16415)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:16003)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:15987)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-30 14:15:19.584  3481  6076 E DropBoxManagerService: 	... 11 more
03-30 14:15:19.584  3481  6076 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop183.tmp
,03-30 14:15:19.589  3481  4021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.589  3481  4021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.589  3481  4021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.589  3481  4021 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-30 14:15:19.589  3481  3481 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131074) and mode_t (0) due to error (30)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: #################################################################
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: #################################################################
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:674)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at com.android.server.LpnetManagerService$DBManager.dbOpen(LpnetManagerService.java:2118)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at com.android.server.LpnetManagerService$2$1.run(LpnetManagerService.java:710)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.594  3481  3481 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.594  3481  3481 E LpnetManagerService: Exception on handling DB : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.594  3481  3481 E LpnetManagerService: #################################################################
03-30 14:15:19.594  3481  3481 E LpnetManagerService: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.594  3481  3481 E LpnetManagerService: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.594  3481  3481 E LpnetManagerService: #################################################################
03-30 14:15:19.594  3481  3481 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.594  3481  3481 W System.err: #################################################################
03-30 14:15:19.594  3481  3481 W System.err: Error Code : 0 (SQLITE_OK)
03-30 14:15:19.594  3481  3481 W System.err: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-30 14:15:19.594  3481  3481 W System.err: #################################################################
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:674)
03-30 14:15:19.594  3481  3481 W System.err: 	at com.android.server.LpnetManagerService$DBManager.dbOpen(LpnetManagerService.java:2118)
03-30 14:15:19.594  3481  3481 W System.err: 	at com.android.server.LpnetManagerService$2$1.run(LpnetManagerService.java:710)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-30 14:15:19.594  3481  3481 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.594  3481  3481 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-30 14:15:19.594  3481  3481 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-30 14:15:19.594  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.594  3481  3481 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.594  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.594  3481  3481 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.599  3723  3723 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
03-30 14:15:19.599 12204 12204 I TapandpayWidget:Utils: Clear T&P info.
03-30 14:15:19.604  3723  3723 D PanelView: There is/are notification(s) 
03-30 14:15:19.604  3723  3723 D PanelView: kidsfalse mQsExpansionEnabled:true
03-30 14:15:19.604  2858  3049 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
03-30 14:15:19.604  2858  3049 W Vold    : Returning OperationFailed - no handler for errno 0
03-30 14:15:19.609 12118 12118 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
03-30 14:15:19.609  3481  3691 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-30 14:15:19.609  3723  3723 D PanelView: There is/are notification(s) 
03-30 14:15:19.609  3481  3691 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
03-30 14:15:19.609  3723  3723 D PanelView: kidsfalse mQsExpansionEnabled:true
03-30 14:15:19.609 12188 12188 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-30 14:15:19.614 12230 12230 E Zygote  : MountEmulatedStorage()
03-30 14:15:19.614 12230 12230 I libpersona: KNOX_SDCARD checking this for 1000
03-30 14:15:19.614 12230 12230 E Zygote  : v2
03-30 14:15:19.614 12230 12230 I libpersona: KNOX_SDCARD not a persona
,03-30 14:15:19.629 12230 12230 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-30 14:15:19.639  3481  4021 I ActivityManager: Start proc 12230:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
,03-30 14:15:19.649 12230 12230 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-30 14:15:19.654  3481  3961 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-30 14:15:19.654  3481  3961 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-30 14:15:19.659 12230 12230 E Zygote  : accessInfo : 0
,03-30 14:15:19.659 12230 12230 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-30 14:15:19.664  3481  6076 I Process : Sending signal. PID: 3481 SIG: 9
,03-30 14:15:19.674  3723  3723 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-30 14:15:19.814  2883  2883 E installd: eof
03-30 14:15:19.814  2883  2883 E installd: failed to read size
03-30 14:15:19.814  2883  2883 I installd: closing connection
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'telecom' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'vr' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'harmony_eas_service' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'rttmanager' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'lock_settings' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'sdp' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'device_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'log_manager_service' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'enterprise_license_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'application_policy' died
03-30 14:15:19.824  4412  4796 W Sensors : sensorservice died [0xb45f0600]
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'wifi_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'phone_restriction_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'remoteinjection' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'tima' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'cepproxyks' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'emailksproxy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'CustomFrequencyManagerService' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'samsung.smartfaceservice' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'consumer_ir' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'gfxinfo' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'dbinfo' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'cpuinfo' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'permission' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'hardware' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'battery' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'usagestats' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'webviewupdate' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'scheduling_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'telephony.registry' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'entropy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'user' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'activity' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'uimode' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'mum_container_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'enterprise_billing_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'otp_service' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'enterprise_shared_device_policy' died
03-30 14:15:19.824  2880  2880 W AudioFlinger: power manager service died !!!
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'knox_timakeystore_policy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'enterprise_policy' died
03-30 14:15:19.824  2880  2880 W AudioFlinger: power manager service died !!!
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'statusbar' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'clipboard' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'clipboardEx' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'network_management' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'notification' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'devicestoragemonitor' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'location' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'country_detector' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'sec_location' died
03-30 14:15:19.824  2857  2857 I ServiceManager: servi,ce 'search' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'dropbox' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'wallpaper' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'usb' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'serial' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'audio' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'DockObserver' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'jobscheduler' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'backup' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'appwidget' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'voiceinteraction' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'SecExternalDisplayService' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'diskstats' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'mDNIe' died,
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'spengestureservice' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'quickconnect' died,
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'samplingprofiler' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'commontime_management' died,
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'dreams' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'print' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'restrictions' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'media_session' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'media_router' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'trust' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'fingerprint' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'launcherapps' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'voip' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'media_projection' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'lpnet' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'imms' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'mobile_payment' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'wifi' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'wifihs20' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'wifiscanner' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'connectivity' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'sb_service' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'servicediscovery' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'updatelock' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'sec_analytics' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'edmnativehelper' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'sensorservice' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'package' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'procstats' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'meminfo' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'SEAMService' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'persona' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'account' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'content' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'DirEncryptService' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'ReactiveService' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'SatsService' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'vibrator' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'sedenial' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'mdm.remotedesktop' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'alarm' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'context_aware' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'scontext' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'barbeam' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'multiwindow_facade' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'window' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'input' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'tactileassist' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'bluetooth_manager' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'bluetooth_secure_mode_manager' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'rcp' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'input_method' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'accessibility' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'cover' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'mount' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'ABTPersistenceService' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'textservices' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'network_score' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'netstats' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'netpolicy' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'wifip2p' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'batterystats' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'appops' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'power' died
,03-30 14:15:19.824  2857  2857 I ServiceManager: service 'display' died
03-30 14:15:19.824  2857  2857 I ServiceManager: service 'persona_policy' died
03-30 14:15:19.829 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.829  2860  4065 I SurfaceFlinger: restart the boot-animation @ binderDied
03-30 14:15:19.829  2860  2860 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb449b000
03-30 14:15:19.829  2860  2860 I hwcomposer: int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(0)
,03-30 14:15:19.829 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.829 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.829 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.829 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.829 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.829 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.829 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.829 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.829 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.829 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.829 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.829 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.829 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.829 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.829 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.829 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.829 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.829 10615 12105 W System.err: 	... 11 more
,03-30 14:15:19.829  4030  4030 D AndroidRuntime: Shutting down VM
03-30 14:15:19.834  4412  4837 E WifiManager: Channel connection lost
03-30 14:15:19.834  5869  5869 D HeadsetStateMachine: Proxy object disconnected
03-30 14:15:19.834  3723  5368 W Sensors : sensorservice died [0xb47515c0]
03-30 14:15:19.834  4014  5067 W Sensors : sensorservice died [0xb45f1800]
03-30 14:15:19.834 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.834 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.834 10615 12105 W System.err: ,	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.834 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.834 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.834 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
,03-30 14:15:19.834 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.834 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.834 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.834 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.834 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.834  4014  4014 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
03-30 14:15:19.834 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.834 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
,03-30 14:15:19.834 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.834 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.834 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.834 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.834 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.834 10615 12105 W System.err: 	... 11 more
,03-30 14:15:19.839  3723  4465 E WifiManager: Channel connection lost
03-30 14:15:19.839  4030  4040 W Sensors : sensorservice died [0xae432040]
03-30 14:15:19.839  4030  4030 E AndroidRuntime: FATAL EXCEPTION: main
03-30 14:15:19.839  4030  4030 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 4030
03-30 14:15:19.839  4030  4030 E AndroidRuntime: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at com.android.launcher2.MenuAppModel.findActivitiesForPackage(MenuAppModel.java:697)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at com.android.launcher2.MenuAppModel.getDisabledAppList(MenuAppModel.java:740)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask$1.run(LauncherModel.java:2477)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at com.android.launcher2.DeferredHandler$Impl.handleMessage(DeferredHandler.java:48)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145),
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: Caused by: android.os.DeadObjectException
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.839  4030  4030 E AndroidRuntime: 	... 12 more
03-30 14:15:19.839 10235 10249 W Sensors : sensorservice died [0xb45f0fc0]
,03-30 14:15:19.839  6125  6137 W Sensors : sensorservice died [0x9d451600]
03-30 14:15:19.839  4722  4745 W Sensors : sensorservice died [0xb4613b80]
03-30 14:15:19.839  6143  6156 W Sensors : sensorservice died [0xb45f0e40]
,03-30 14:15:19.839 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.839 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.839 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.889 10845 10845 E ActivityThread: Failed to find provider info for com.sec.badge
03-30 14:15:19.844 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
,03-30 14:15:19.844 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.844 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.844 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.844 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,03-30 14:15:19.844 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.844 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.844 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.844 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.844  5259  5369 E WifiManager: Channel connection lost
03-30 14:15:19.844 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
,03-30 14:15:19.844 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.844 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.844 10108 10227 E WifiManager: Channel connection lost
03-30 14:15:19.844 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
,03-30 14:15:19.844 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.844 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.844 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.844 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.844 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
,03-30 14:15:19.844 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.844 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.844 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.849  4657  7974 E WifiManager: Channel connection lost
03-30 14:15:19.849 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
,03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.849 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.849 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.849 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.849 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,03-30 14:15:19.849 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.849 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.849 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.849 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
,03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.849 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.849 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.849 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
,03-30 14:15:19.849 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.849 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.849 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.849 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,03-30 14:15:19.849 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.849 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.849 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.849 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.849 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.849  4129  6847 E WifiManager: Channel connection lost
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=2 Removed GocusedStac (6/8)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/7)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=4 Removed EimLayer(An (0/6)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=5 Removed EimLayer(Di (0/5)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=6 Removed EimLayer(An (0/4)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=2 Removed GocusedStac (-2/4)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/4)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/4)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=9 Removed TtatusBar (2/3)
03-30 14:15:19.854  2860  3009 I SurfaceFlinger: id=16 Removed YUIInstallC (1/2)
03-30 14:15:19.854  2860  3009 I SurfaceFlinger: id=5 Removed EimLayer(Di (-2/2)
03-30 14:15:19.854  2860  3009 I SurfaceFlinger: id=6 Removed EimLayer(An (-2/2)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=7 Removed JmageWallpa (0/1)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/1)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=13 Removed DolorFade (0/0)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=13 Removed DolorFade (-2/0)
03-30 14:15:19.854  2860  3007 I SurfaceFlinger: id=9 Removed TtatusBar (-2/0)
03-30 14:15:19.854  5117  5151 E WifiManager: Channel connection lost
03-30 14:15:19.854 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.854 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.854 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.854 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.854 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.854 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.854 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.854 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.854 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.854 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.854 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.854 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.854 10615 12105 W System.err: 	at java.lang.Thread.run,(Thread.java:818)
03-30 14:15:19.854 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.859 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.859 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.859 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.859 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.859 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.859  2860  9083 I SurfaceFlinger: id=16 Removed YUIInstallC (-2/0)
03-30 14:15:19.864 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.864 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.864 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.864 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.864 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.864 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.864 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.864 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.864 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.864 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.864 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.864 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.864 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.864 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.864 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.864 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.864 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.864 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
,03-30 14:15:19.864 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.869 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.869 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.869 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.869 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.869 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.869 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.869 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.869 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
,03-30 14:15:19.869 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.869 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.869 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.869 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.869 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.869 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.869 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.869 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
,03-30 14:15:19.869 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.869 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.869 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.874  4030  4030 E AndroidRuntime: Error reporting crash
03-30 14:15:19.874  4030  4030 E AndroidRuntime: android.os.DeadObjectException
03-30 14:15:19.874  4030  4030 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.874  4030  4030 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.874  4030  4030 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4909)
03-30 14:15:19.874  4030  4030 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
03-30 14:15:19.874  4030  4030 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-30 14:15:19.874  4030  4030 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,03-30 14:15:19.874 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.874  4030  4030 I Process : Sending signal. PID: 4030 SIG: 9
03-30 14:15:19.874 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.874 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.874 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.874 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.874 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
,03-30 14:15:19.874 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.874 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.874 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.874 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.874 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.874 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,03-30 14:15:19.874 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.874 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.874 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.874 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.874 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.874 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.874 10615 12105 W System.err: 	... 11 more
,03-30 14:15:19.884 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.884 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.884 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.884 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.884 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.884 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.884 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.884 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
,03-30 14:15:19.884 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.884 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.884 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.884 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.884 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.884 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.884 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.884 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
,03-30 14:15:19.884 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.884 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.884 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.884 10845 10845 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-30 14:15:19.889 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.889 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.889 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.889 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
,03-30 14:15:19.889 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.889 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.889 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.889 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.889 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.889 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,03-30 14:15:19.889 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.889 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.889 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.889 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.889 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.889 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.889 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
,03-30 14:15:19.889 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.889 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.889 12204 12204 D AndroidRuntime: Shutting down VM
03-30 14:15:19.894 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.894 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.894 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.894 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
,03-30 14:15:19.894 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.894 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:19.894 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.894 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.894 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.894 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.894 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,03-30 14:15:19.894 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.894 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.894 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:19.894 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.894 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.894 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.894 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
,03-30 14:15:19.894 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.899 12204 12204 E AndroidRuntime: FATAL EXCEPTION: main
03-30 14:15:19.899 12204 12204 E AndroidRuntime: Process: com.sec.android.widgetapp.tapandpay, PID: 12204
03-30 14:15:19.899 12204 12204 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.tapandpay.TapandpayAppWidgetProvider: java.lang.RuntimeException: system server dead?
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3516)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: Caused by: java.lang.RuntimeException: system server dead?
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.appwidget.AppWidgetManager.getAppWidgetIds(AppWidgetManager.java:1106)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at com.sec.android.widgetapp.tapandpay.TapandpayAppWidgetProvider.onReceive(Unknown Source)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	,at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	... 9 more
03-30 14:15:19.899 12204 12204 E AndroidRuntime: Caused by: android.os.DeadObjectException
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at com.android.internal.appwidget.IAppWidgetService$Stub$Proxy.getAppWidgetIds(IAppWidgetService.java:961)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	at android.appwidget.AppWidgetManager.getAppWidgetIds(AppWidgetManager.java:1103)
03-30 14:15:19.899 12204 12204 E AndroidRuntime: 	... 11 more
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: Failed talking to License policy service 
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: android.os.DeadObjectException
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at android.app.enterprise.license.IEnterpriseLicense$Stub$Proxy.log(IEnterpriseLicense.java:818)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at android.app.enterprise.license.EnterpriseLicenseManager.log(EnterpriseLicenseManager.java:642)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at com.sec.enterprise.knox.keystore.TimaKeystore.isTimaKeystoreEnabledInDB(TimaKeystore.java:170)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at com.sec.tima.TimaKeyStoreProvider.addTimaSignatureService(TimaKeyStoreProvider.java:56)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at com.sec.tima.TimaKeyStoreProvider.<init>(TimaKeyStoreProvider.java:38)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at java.lang.reflect.Constructor.newInstance(Native Method)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	,at java.lang.Class.newInstance(Class.java:1690)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at android.app.ActivityThread.main(ActivityThread.java:6838)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.904 12230 12230 W EnterpriseLicenseManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.904 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:19.904 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:19.904 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:19.904 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:19.904 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:19.904 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
,03-30 14:15:19.904 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:19.904 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:19.904 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:19.904 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:19.904 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:19.904 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:19.904 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:19.904 10615 12105 W System.err: Caused by: android.os.DeadObjectException
,03-30 14:15:19.904 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.904 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.904 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:19.904 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:19.904 10615 12105 W System.err: 	... 11 more
03-30 14:15:19.904 12230 12230 W TimaKeystore: Failed at TimaKeystore API isTimaKeystoreEnabledInDB-Exception
03-30 14:15:19.904 12230 12230 W TimaKeystore: android.os.DeadObjectException
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at com.sec.enterprise.knox.keystore.ITimaKeystore$Stub$Proxy.isTimaKeystoreEnabledInDB(ITimaKeystore.java:178)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at com.sec.enterprise.knox.keystore.TimaKeystore.isTimaKeystoreEnabledInDB(TimaKeystore.java:172)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at com.sec.tima.TimaKeyStoreProvider.addTimaSignatureService(TimaKeyStoreProvider.java:56)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at com.sec.tima.TimaKeyStoreProvider.<init>(TimaKeyStoreProvider.java:38)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at java.lang.reflect.Constructor.newInstance(Native Method)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	,at java.lang.Class.newInstance(Class.java:1690)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at android.app.ActivityThread.main(ActivityThread.java:6838)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.904 12230 12230 W TimaKeystore: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.909 12230 12230 D TimaKeyStoreProvider: TimaSignature is unavailable
03-30 14:15:19.909 12230 12230 D ActivityThread: Added TimaKeyStore provider
03-30 14:15:19.914 12204 12204 E AndroidRuntime: Error reporting crash
03-30 14:15:19.914 12204 12204 E AndroidRuntime: android.os.DeadObjectException
03-30 14:15:19.914 12204 12204 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.914 12204 12204 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.914 12204 12204 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4909)
03-30 14:15:19.914 12204 12204 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
03-30 14:15:19.914 12204 12204 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-30 14:15:19.914 12204 12204 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,03-30 14:15:19.914 12204 12204 I Process : Sending signal. PID: 12204 SIG: 9
03-30 14:15:19.919 12230 12230 D AndroidRuntime: Shutting down VM
03-30 14:15:19.919 12230 12230 E AndroidRuntime: FATAL EXCEPTION: main
03-30 14:15:19.919 12230 12230 E AndroidRuntime: PID: 12230
03-30 14:15:19.919 12230 12230 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke interface method 'void android.app.IActivityManager.attachApplication(android.app.IApplicationThread)' on a null object reference
03-30 14:15:19.919 12230 12230 E AndroidRuntime: 	at android.app.ActivityThread.attach(ActivityThread.java:6505)
03-30 14:15:19.919 12230 12230 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6856)
03-30 14:15:19.919 12230 12230 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.919 12230 12230 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.919 12230 12230 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.919 12230 12230 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.924 12230 12230 E AndroidRuntime: Error reporting crash
03-30 14:15:19.924 12230 12230 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke interface method 'void android.app.IActivityManager.handleApplicationCrash(android.os.IBinder, android.app.ApplicationErrorReport$CrashInfo)' on a null object reference
03-30 14:15:19.924 12230 12230 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
03-30 14:15:19.924 12230 12230 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-30 14:15:19.924 12230 12230 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,03-30 14:15:19.924 12230 12230 I Process : Sending signal. PID: 12230 SIG: 9
,03-30 14:15:19.954 12118 12118 W System.err: java.lang.RuntimeException: Package manager has died
,03-30 14:15:19.954 12118 12118 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:164)
03-30 14:15:19.954 12118 12118 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:344)
03-30 14:15:19.954 12118 12118 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1021)
03-30 14:15:19.954 12118 12118 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5967)
,03-30 14:15:19.954 12118 12118 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-30 14:15:19.954 12118 12118 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
,03-30 14:15:19.954 12118 12118 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.954 12118 12118 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,03-30 14:15:19.954 12118 12118 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-30 14:15:19.954 12118 12118 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,03-30 14:15:19.954 12118 12118 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.954 12118 12118 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.954 12118 12118 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.954 12118 12118 W System.err: Caused by: android.os.DeadObjectException
,03-30 14:15:19.959 12118 12118 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.959 12118 12118 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.959 12118 12118 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.getPackageInfo(IPackageManager.java:2209)
03-30 14:15:19.959 12118 12118 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:159)
03-30 14:15:19.959 12118 12118 W System.err: 	... 12 more
,03-30 14:15:19.974 12118 12118 D AndroidRuntime: Shutting down VM
,03-30 14:15:19.974 12118 12118 E AndroidRuntime: FATAL EXCEPTION: main
03-30 14:15:19.974 12118 12118 E AndroidRuntime: Process: com.samsung.android.sdk.samsunglink, PID: 12118
,03-30 14:15:19.974 12118 12118 E AndroidRuntime: java.lang.RuntimeException: Unable to create service com.sec.pcw.analytics.AnalyticsUploaderService: java.lang.NullPointerException: Attempt to invoke interface method 'android.accounts.Account[] android.accounts.IAccountManager.getAccounts(java.lang.String)' on a null object reference
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3691)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.app.ActivityThread.access$2000(ActivityThread.java:197)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1764)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: Caused by: java.lang.NullPointerException: Attempt to invoke interface method 'android.accounts.Account[] android.accounts.IAccountManager.getAccounts(java.lang.String)' on a null object reference
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.accounts.AccountManager.getAccounts(AccountManager.java:411)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at com.sec.pcw.service.d.b.a(SourceFile:1914)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at com.sec.pcw.analytics.AnalyticsUploaderService.onCreate(SourceFile:64)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3681)
03-30 14:15:19.974 12118 12118 E AndroidRuntime: 	... 9 more
03-30 14:15:19.979 12118 12118 E AndroidRuntime: Error reporting crash
,03-30 14:15:19.979 12118 12118 E AndroidRuntime: android.os.DeadObjectException
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4909)
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at com.mfluent.asp.util.g.uncaughtException(SourceFile:44)
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at com.mfluent.asp.util.y.uncaughtException(SourceFile:90)
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-30 14:15:19.979 12118 12118 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
03-30 14:15:19.979 12118 12118 I Process : Sending signal. PID: 12118 SIG: 9
,03-30 14:15:20.009  9065  9080 E AndroidRuntime: FATAL EXCEPTION: AppProvider
03-30 14:15:20.009  9065  9080 E AndroidRuntime: Process: com.samsung.android.app.galaxyfinder:tagService, PID: 9065
03-30 14:15:20.009  9065  9080 E AndroidRuntime: java.lang.RuntimeException: Package manager has died
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider.b(SourceFile:461)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider.b(SourceFile:56)
,03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.applicationprovider.d.handleMessage(SourceFile:203)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: Caused by: android.os.DeadObjectException
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	... 7 more
,03-30 14:15:20.009  9065  9080 E AndroidRuntime: Error reporting crash
03-30 14:15:20.009  9065  9080 E AndroidRuntime: android.os.DeadObjectException
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4909)
,03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-30 14:15:20.009  9065  9080 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
03-30 14:15:20.009  9065  9080 I Process : Sending signal. PID: 9065 SIG: 9
,03-30 14:15:20.074 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:20.074 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:20.074 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:20.074 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:20.074 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:20.074 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:20.074 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:20.074 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:20.074 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:20.074 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:20.074 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:20.074 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:20.074 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:20.074 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:20.074 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:20.074 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:20.074 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:20.074 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:20.074 10615 12105 W System.err: 	... 11 more
,03-30 14:15:20.084 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:20.084 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:20.084 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:20.084 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:20.084 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:20.084 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:20.084 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:20.084 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:20.084 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:20.084 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:20.084 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:20.084 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:20.084 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:20.084 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:20.084 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:20.084 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:20.084 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:20.084 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:20.084 10615 12105 W System.err: 	... 11 more
,03-30 14:15:20.089 10615 12105 W System.err: java.lang.RuntimeException: Package manager has died
03-30 14:15:20.089 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:638)
03-30 14:15:20.089 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:620)
03-30 14:15:20.089 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.getLaunchIntentForPackage(ApplicationPackageManager.java:196)
03-30 14:15:20.089 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.pick.Lib.getApplicationsWithClass(Lib.java:107)
03-30 14:15:20.089 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:356)
03-30 14:15:20.089 10615 12105 W System.err: 	at com.sec.android.widgetapp.locationwidget.LocationWidgetApplication$LoadApplicationLists.doInBackground(LocationWidgetApplication.java:353)
03-30 14:15:20.089 10615 12105 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
03-30 14:15:20.089 10615 12105 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-30 14:15:20.089 10615 12105 W System.err: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-30 14:15:20.089 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-30 14:15:20.089 10615 12105 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-30 14:15:20.089 10615 12105 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-30 14:15:20.089 10615 12105 W System.err: Caused by: android.os.DeadObjectException
03-30 14:15:20.089 10615 12105 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
03-30 14:15:20.089 10615 12105 W System.err: 	at android.os.BinderProxy.transact(Binder.java:511)
03-30 14:15:20.089 10615 12105 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3275)
03-30 14:15:20.089 10615 12105 W System.err: 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:628)
03-30 14:15:20.089 10615 12105 W System.err: 	... 11 more

```
