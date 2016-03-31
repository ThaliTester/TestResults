#### Test 646138036c5f71d_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-31 15:14:04.382  3388  3585 I PowerManagerService: [PWL] Off : 5s ago
03-31 15:14:04.382  3388  3585 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-31 15:14:04.382  3388  3585 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-31 15:14:04.382  3388  3585 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService' (uid=10031, pid=10303, ws=null) (elapsedTime=3874)
,--------- beginning of main
03-31 15:14:05.347 10859 10859 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 15:14:05.357 10859 10859 D AndroidRuntime: CheckJNI is OFF
03-31 15:14:05.357 10859 10859 D AndroidRuntime: readGMSProperty: start
03-31 15:14:05.357 10859 10859 D AndroidRuntime: readGMSProperty: already setted!!
03-31 15:14:05.357 10859 10859 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 15:14:05.357 10859 10859 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 15:14:05.357 10859 10859 D AndroidRuntime: readGMSProperty: end
03-31 15:14:05.357 10859 10859 D AndroidRuntime: addProductProperty: start
03-31 15:14:05.547 10859 10859 E AffinityControl: AffinityControl: registerfunction enter
03-31 15:14:05.572 10859 10859 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-31 15:14:05.582  3388  3425 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-31 15:14:05.587  3388  3425 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 15:14:05.607  3388  3425 W ActivityManager: mDVFSHelper.acquire()
03-31 15:14:05.612  3388  3425 V WindowManager: addAppToken: AppWindowToken{1790f6bc token=Token{310392af ActivityRecord{cfe2a8e u0 com.test.thalitest/.MainActivity t41}}} to stack=1 task=41 at 0
03-31 15:14:05.612  3388  3425 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:05.612  3388  3425 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:05.612  3388  3425 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:05.612  3388  3425 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:05.622  3388  3580 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-31 15:14:05.622  3388  3580 D SecWifiDisplayUtil: Metadata value : none
03-31 15:14:05.622  3388  3580 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-31 15:14:05.622  3388  3580 V WindowManager: Adding window Window{1d6d28a7 u0 d0 Starting com.test.thalitest} at 3 of 7 (after Window{1039191b u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity})
03-31 15:14:05.632 10877 10877 E Zygote  : MountEmulatedStorage()
03-31 15:14:05.632 10877 10877 E Zygote  : v2
03-31 15:14:05.632 10877 10877 I libpersona: KNOX_SDCARD checking this for 10011
03-31 15:14:05.632 10877 10877 I libpersona: KNOX_SDCARD not a persona
03-31 15:14:05.637 10877 10877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:14:05.637  3388  3425 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 15:14:05.637  3388  3425 I ActivityManager: Start proc 10877:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-31 15:14:05.637  3388  3425 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 15:14:05.637  3388  3425 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 15:14:05.637  3388  3425 D InputDispatcher: Focused application set to: xxxx
03-31 15:14:05.637  3388  3425 D InputDispatcher: Focus left window: 6567
03-31 15:14:05.637  3388  3580 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 15:14:05.637  3388  3580 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-31 15:14:05.642 10859 10859 D AndroidRuntime: Shutting down VM
03-31 15:14:05.642  2860  2860 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-31 15:14:05.642 10877 10877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:14:05.642 10877 10877 E Zygote  : accessInfo : 0
03-31 15:14:05.647 10877 10877 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-31 15:14:05.652  3388  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3388 uid:1000
03-31 15:14:05.652  3388  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 15:14:05.652  3388  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3388 uid:1000
03-31 15:14:05.652  3388  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 15:14:05.667 10877 10877 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:14:05.667 10877 10877 D ActivityThread: Added TimaKeyStore provider
03-31 15:14:05.672  3388  4008 D PowerManagerService: setKeyboardVisibility: false
03-31 15:14:05.672  3388  3578 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1d6d28a7 u0 d0 Starting com.test.thalitest}
03-31 15:14:05.672  3388  4008 D ActivityManager:  Launching com.test.thalitest, updated priority
03-31 15:14:05.692  3388  4008 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{cfe2a8e u0 com.test.thalitest/.MainActivity t41}
03-31 15:14:05.702  2860  3019 I SurfaceFlinger: id=12 Removed YUIInstallC (7/9)
03-31 15:14:05.702  2860  3634 I SurfaceFlinger: id=12 Removed YUIInstallC (-2/9)
03-31 15:14:05.702  3388  3388 V ActivityManager: Display changed displayId=0
03-31 15:14:05.712  6567  6567 V ActivityThread: updateVisibility : ActivityRecord{289bef14 token=android.os.BinderProxy@6af5fda {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
03-31 15:14:05.862  3388  6061 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-31 15:14:05.897 10877 10877 D SecWifiDisplayUtil: Metadata value : none
,03-31 15:14:05.942 10877 10877 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-31 15:14:05.957 10877 10877 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2443-2445)
03-31 15:14:05.957 10877 10877 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 15:14:05.967 10877 10877 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14906d9d}
,03-31 15:14:05.972 10877 10877 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-31 15:14:05.972 10877 10877 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 15:14:05.972 10877 10893 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-31 15:14:05.992 10877 10877 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-31 15:14:05.992 10877 10877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 15:14:05.992 10877 10877 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-31 15:14:06.012 10877 10877 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-31 15:14:06.012 10877 10877 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-31 15:14:06.012 10877 10877 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-31 15:14:06.077 10877 10916 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-31 15:14:06.122 10877 10877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 15:14:06.147 10877 10877 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 15:14:06.167 10877 10877 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-31 15:14:06.167 10877 10877 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-31 15:14:06.177 10877 10877 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-31 15:14:06.187 10877 10877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 15:14:06.187 10877 10877 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-31 15:14:06.192  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:14:06.267 10877 10929 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 15:14:06.267  3388  3863 E Watchdog: !@Sync 2 [03-31 15:14:06.270]
03-31 15:14:06.267  3388  4008 V WindowManager: Adding window Window{146831c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 8 (before Window{1d6d28a7 u0 d0 Starting com.test.thalitest})
,03-31 15:14:06.272  3388  3855 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 15:14:06.272  3388  3855 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 15:14:06.272  3388  3855 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 15:14:06.272  3388  3388 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-31 15:14:06.272  3388  3388 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-31 15:14:06.272  3388  3388 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-31 15:14:06.277  3388  3388 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 15:14:06.277  3388  3388 I EnterpriseSharedDevicePolicy: status: false
03-31 15:14:06.277  3388  3388 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-31 15:14:06.277  3388  3388 D PersonaManagerService: getPersonasForUser(): returning null!
,03-31 15:14:06.287 10877 10877 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-31 15:14:06.287 10877 10877 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-31 15:14:06.292 10877 10877 D SecWifiDisplayUtil: Metadata value : none
03-31 15:14:06.302  2860  2860 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
03-31 15:14:06.302  3388  4731 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 15:14:06.317  3388  4731 D InputDispatcher: Focus entered window: 10877
,03-31 15:14:06.322  3388  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3388 uid:1000
03-31 15:14:06.322  3388  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 15:14:06.322  3388  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3388 uid:1000
03-31 15:14:06.322  3388  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 15:14:06.322 10877 10877 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 15:14:06.322 10877 10929 I OpenGLRenderer: Initialized EGL, version 1.4
,03-31 15:14:06.322 10877 10929 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae430c10 ,&mEglDisplay = 1 , &mEglConfig = -1266908912 
,03-31 15:14:06.327 10877 10929 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
,03-31 15:14:06.327 10877 10929 D OpenGLRenderer: Enabling debug mode 0
,03-31 15:14:06.327 10877 10929 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-31 15:14:06.332 10877 10877 V ActivityThread: updateVisibility : ActivityRecord{14961bc5 token=android.os.BinderProxy@20b4cc2f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-31 15:14:06.412  3388  4009 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 15:14:06.417  3388  3580 I ActivityManager: Displayed Component not be shown by security: +584ms (total +803ms)
,03-31 15:14:06.417  3726  3726 D PanelView: There is/are notification(s) 
,03-31 15:14:06.417  3388  3580 W ActivityManager: mDVFSHelper.release()
03-31 15:14:06.417  3388  3580 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{cfe2a8e u0 com.test.thalitest/.MainActivity t41} time:72909
,03-31 15:14:06.422  2860  3634 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
03-31 15:14:06.422  2860  4638 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
,03-31 15:14:06.452 10877 10877 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 15:14:06.452 10877 10877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20b4cc2f time:72941
,03-31 15:14:06.477 10877 10877 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10877
,03-31 15:14:06.587 10877 10877 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 15:14:06.682 10877 10933 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626296704
,03-31 15:14:06.687 10877 10933 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 15:14:06.687 10877 10933 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 15:14:06.687 10877 10933 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 15:14:06.687 10877 10933 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 15:14:06.687 10877 10933 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 15:14:06.687 10877 10933 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1abaecca added. We now have 1 listener(s)
,03-31 15:14:06.692 10877 10933 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-31 15:14:06.692 10877 10933 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-31 15:14:06.692 10877 10933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 15:14:06.692 10877 10933 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 15:14:06.697 10877 10893 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 15:14:06.697 10877 10933 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b3eab1 added. We now have 1 listener(s)
,03-31 15:14:06.697 10877 10933 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 15:14:06.702 10877 10933 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-31 15:14:06.702 10877 10933 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-31 15:14:06.702 10877 10933 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-31 15:14:06.702 10877 10933 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-31 15:14:06.702 10877 10933 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-31 15:14:06.707 10877 10933 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 15:14:06.707 10877 10933 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 15:14:06.712 10877 10933 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 15:14:06.712 10877 10933 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 15:14:06.712 10877 10933 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-31 15:14:06.712 10877 10933 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 15:14:06.717 10877 10877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 15:14:06.717 10877 10877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 15:14:06.762 10877 10877 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 15:14:07.142 10877 10940 W jxcore-log: Initializing JXcore engine
03-31 15:14:07.142 10877 10940 W jxcore-log: JXcore engine is ready
,03-31 15:14:07.177  4709  4709 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-31 15:14:07.177  4709  4709 E audit   : type=1400 msg=audit(1459430047.172:196): avc:  denied  { ioctl } for  pid=10940 comm="Thread-1519" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2338 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-31 15:14:07.177  3388  3576 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-31 15:14:07.177  4709  4709 E audit   :  SEPF_SM-N910C_5.1.1_0038
,03-31 15:14:07.177  4709  4709 E audit   : type=1300 msg=audit(1459430047.172:196): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=975008d8 items=0 ppid=2901 ppcomm=main pid=10940 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1519" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-31 15:14:07.177  4709  4709 E audit   : type=1320 msg=audit(1459430047.172:196): 
,03-31 15:14:07.177  3388  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,03-31 15:14:07.182  3388  3576 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
03-31 15:14:07.182  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:07.182  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:07.182  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:07.182 10877 10940 W jxcore-log: Starting JXcore engine
03-31 15:14:07.182  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 15:14:07.192 10941 10941 E Zygote  : MountEmulatedStorage()
,03-31 15:14:07.192 10941 10941 E Zygote  : v2
03-31 15:14:07.192 10941 10941 I libpersona: KNOX_SDCARD checking this for 1000
03-31 15:14:07.192 10941 10941 I libpersona: KNOX_SDCARD not a persona
03-31 15:14:07.197 10941 10941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 15:14:07.197  3388  3575 I ActivityManager: Start proc 10941:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-31 15:14:07.197 10941 10941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 15:14:07.197 10941 10941 E Zygote  : accessInfo : 0
,03-31 15:14:07.202 10941 10941 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 15:14:07.217 10941 10941 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 15:14:07.217 10941 10941 D ActivityThread: Added TimaKeyStore provider
,03-31 15:14:07.227  3388  3425 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1f551d20 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{2cdd56d9 10941:com.samsung.android.securitylogagent/1000}
,03-31 15:14:07.237 10877 10940 W jxcore-log: Platform android
03-31 15:14:07.237 10877 10940 W jxcore-log: 
03-31 15:14:07.237 10877 10940 W jxcore-log: Process ARCH arm
03-31 15:14:07.237 10877 10940 W jxcore-log: 
,03-31 15:14:07.247 10941 10941 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-31 15:14:07.247 10941 10941 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-31 15:14:07.307  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:14:07.307  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:14:07.307  3388  4397 D BatteryService: online:4, current avg:-40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-87
03-31 15:14:07.307  3388  4397 D BatteryService: stay LED for fully charged
03-31 15:14:07.307  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:14:07.307  3388  3388 I MotionRecognitionService: Plugged
03-31 15:14:07.307  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:14:07.307  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:14:07.307  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:14:07.312  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:07.312  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:07.312  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:14:07.317  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:14:07.317  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:14:07.317  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:14:07.327 10877 10940 I jxcore-log: JXcore Cordova bridge is ready!
03-31 15:14:07.327 10877 10940 I jxcore-log: 
03-31 15:14:07.327 10877 10940 W jxcore-log: JXcore engine is started
,03-31 15:14:07.332  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:07.332  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:07.332  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:07.332 10877 10933 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 15:14:07.337 10877 10877 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 15:14:08.302  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:14:08.497  3388  3843 I ActivityManager: Killing 9705:com.android.mms/u0a52 (adj 15): emptyCount ##31
,03-31 15:14:08.542  3388  3843 D CountryDetector: No listener is left
,03-31 15:14:08.622  3388  3692 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/41_task.xml.bak
,03-31 15:14:09.067  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:14:09.322  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:14:09.447  3388  6061 D SSRM:n  : SIOP:: AP = 310, PST = 332 (W:8), CUR = -40, LCD = 0
,03-31 15:14:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:14:11.807  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:14:11.812  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:14:11.812  3388  3618 V AlarmManager: No more alarm at this time.nowELAPSED=78303 batch.start=78811
,03-31 15:14:11.952 10303 10369 I Finsky  : [1425] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 15:14:11.952 10303 10303 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 15:14:12.322  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:14:12.322  3388  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14a20811 u0 null} DELIVERED for app ProcessRecord{4155ca5 4642:com.google.android.gms/u0a14}
,03-31 15:14:12.327  3388  4029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 15:14:12.332  3388  3388 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,03-31 15:14:12.337  3388  3388 I BackgroundCompactionService: onStart. jobID=801
,03-31 15:14:12.337  3388  3388 I BackgroundCompactionService: onStart done. jobID=801
,03-31 15:14:12.337  3388 10959 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,03-31 15:14:12.342  3388 10959 I BackgroundCompactionService: compact_memory command done
,03-31 15:14:12.352  4642 10958 I EventLogService: Aggregate from 1459428250438 (log), 1459428250438 (data)
,03-31 15:14:12.412  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:12.412  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:12.412  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:14:12.412  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-31 15:14:12.422 10960 10960 E Zygote  : MountEmulatedStorage()
03-31 15:14:12.422 10960 10960 I libpersona: KNOX_SDCARD checking this for 1000
03-31 15:14:12.422 10960 10960 E Zygote  : v2
03-31 15:14:12.422 10960 10960 I libpersona: KNOX_SDCARD not a persona
03-31 15:14:12.422 10960 10960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
,03-31 15:14:12.422 10960 10960 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
,03-31 15:14:12.422 10960 10960 E Zygote  : accessInfo : 0
03-31 15:14:12.422 10960 10960 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-31 15:14:12.427  3388  3575 I ActivityManager: Start proc 10960:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,03-31 15:14:12.437 10960 10960 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-31 15:14:12.437 10960 10960 D ActivityThread: Added TimaKeyStore provider
,03-31 15:14:12.447  3388  4029 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2b63066f u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{df9bf7c 10960:com.samsung.android.sm/1000}
,03-31 15:14:12.452 10960 10960 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 15:14:12.472  3388  4397 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{21968005 u0 android.intent.action.DROPBOX_ENTRY_ADDED} DELIVERED for app ProcessRecord{df9bf7c 10960:com.samsung.android.sm/1000}
,03-31 15:14:12.472  3388  4397 I ActivityManager: Killing 10080:com.sec.android.app.myfiles/u0a53 (adj 15): emptyCount ##31
,03-31 15:14:13.072 10877 10940 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 15:14:13.072 10877 10940 I jxcore-log: 
,03-31 15:14:13.077 10877 10940 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 15:14:13.077 10877 10940 I jxcore-log: 
,03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 15:14:13.077 10877 10940 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 15:14:13.077 10877 10940 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-31 15:14:13.082 10877 10940 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 15:14:13.082 10877 10940 I jxcore-log: 
,03-31 15:14:13.082 10877 10940 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 15:14:13.082 10877 10940 I jxcore-log: 
,03-31 15:14:13.302  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:14:13.402 10877 10940 I jxcore-log: Unit Test app is loaded
03-31 15:14:13.402 10877 10940 I jxcore-log: 
,03-31 15:14:13.407 10877 10940 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 15:14:13.407 10877 10940 I jxcore-log: 
,03-31 15:14:13.407 10877 10877 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-31 15:14:13.412 10877 10940 I jxcore-log: My device name is: samsung-SM-N910C
03-31 15:14:13.412 10877 10940 I jxcore-log: 
,03-31 15:14:13.412 10877 10940 I jxcore-log: WARN testUtils: myNameCallback not set!
03-31 15:14:13.412 10877 10940 I jxcore-log: 
,03-31 15:14:14.382  3388  3585 I PowerManagerService: [PWL] Off : 15s ago
,03-31 15:14:15.662  3388  3591 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-31 15:14:15.682  3388  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-31 15:14:15.757 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 15:14:15.757 10877 10940 I jxcore-log: 
,03-31 15:14:15.962 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 15:14:15.962 10877 10940 I jxcore-log: 
,03-31 15:14:15.967 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 15:14:15.967 10877 10940 I jxcore-log: 
,03-31 15:14:15.972 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 15:14:15.972 10877 10940 I jxcore-log: 
,03-31 15:14:15.992 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 15:14:15.992 10877 10940 I jxcore-log: 
,03-31 15:14:16.002 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 15:14:16.002 10877 10940 I jxcore-log: 
,03-31 15:14:16.002 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 15:14:16.002 10877 10940 I jxcore-log: 
,03-31 15:14:17.207 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 15:14:17.207 10877 10940 I jxcore-log: 
,03-31 15:14:17.217 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 15:14:17.217 10877 10940 I jxcore-log: 
,03-31 15:14:17.222 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 15:14:17.222 10877 10940 I jxcore-log: 
,03-31 15:14:17.372 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 15:14:17.372 10877 10940 I jxcore-log: 
,03-31 15:14:17.412 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 15:14:17.412 10877 10940 I jxcore-log: 
,03-31 15:14:17.427  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:14:17.427  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4354, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:14:17.427  3388  4397 D BatteryService: online:4, current avg:-173, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-212
03-31 15:14:17.427  3388  4397 D BatteryService: stay LED for fully charged
03-31 15:14:17.427  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:14:17.427  3388  3388 I MotionRecognitionService: Plugged
03-31 15:14:17.427  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:14:17.427  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:14:17.427  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:14:17.427  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:17.427  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:17.427  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:14:17.432  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:14:17.432  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:14:17.442 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 15:14:17.442 10877 10940 I jxcore-log: 
,03-31 15:14:17.447 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 15:14:17.447 10877 10940 I jxcore-log: 
,03-31 15:14:17.447  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:14:17.452  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:17.452  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:17.452  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:17.457 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 15:14:17.457 10877 10940 I jxcore-log: 
,03-31 15:14:17.457 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 15:14:17.457 10877 10940 I jxcore-log: 
,03-31 15:14:17.462 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 15:14:17.462 10877 10940 I jxcore-log: 
,03-31 15:14:17.467 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 15:14:17.467 10877 10940 I jxcore-log: 
,03-31 15:14:17.482 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 15:14:17.482 10877 10940 I jxcore-log: 
,03-31 15:14:17.527 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 15:14:17.527 10877 10940 I jxcore-log: 
,03-31 15:14:17.532 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 15:14:17.532 10877 10940 I jxcore-log: 
,03-31 15:14:17.547 10877 10940 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 15:14:17.547 10877 10940 I jxcore-log: 
,03-31 15:14:17.547 10877 10940 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-31 15:14:17.552 10877 10940 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-31 15:14:17.552 10877 10940 I jxcore-log: 
,03-31 15:14:18.302  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-31 15:14:19.472  3388  6061 D SSRM:n  : SIOP:: AP = 330, PST = 332 (W:9), CUR = -173, LCD = 0
,03-31 15:14:20.032 10101 10665 V xAnalytics: xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,03-31 15:14:23.307  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:14:26.127  3388  4397 I ActivityManager: Killing 10054:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-31 15:14:27.572  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:14:27.572  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:14:27.572  3388  4037 D BatteryService: online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:126
,03-31 15:14:27.577  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:14:27.582  3388  3388 I MotionRecognitionService: Plugged
03-31 15:14:27.582  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:14:27.582  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:14:27.582  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:14:27.587  3388  4037 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 15:14:27.587  3388  4037 D BatteryService: stay LED for fully charged
,03-31 15:14:27.597  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:14:27.597  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:14:27.597  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:14:27.617  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:14:27.622  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:14:27.632  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:14:27.632  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:27.632  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:27.632  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:29.382  3388  3585 I PowerManagerService: [PWL] Off : 30s ago
,03-31 15:14:29.447  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:14:29.492  3388  6061 D SSRM:n  : SIOP:: AP = 300, PST = 329 (W:10), CUR = 5, LCD = 0
,03-31 15:14:29.837  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:14:29.872  3388  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2ee15768 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE} DELIVERED for app ProcessRecord{1cdf222e 4392:com.google.android.gms.persistent/u0a14}
,03-31 15:14:29.922  3388  3843 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 15:14:29.997  3388  4397 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 15:14:30.012  3388  3651 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-31 15:14:30.052  3388  4236 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 15:14:30.082  4392  4392 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:30.097  4392 11011 I VacuumService: Vacuum at: now=1459430070097 tag=VacuumService
,03-31 15:14:30.127  3388  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3015ab80 u0 com.google.android.gms.gcm.ACTION_SCHEDULE} DELIVERED for app ProcessRecord{1cdf222e 4392:com.google.android.gms.persistent/u0a14}
,03-31 15:14:30.262  3388  4037 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 15:14:30.302  3388  3843 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-31 15:14:30.782  4392 11026 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 11174 seconds from now (1459430070785)
,03-31 15:14:30.817  3388  3575 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37343c7b u0 com.google.android.gms.gcm.ACTION_SCHEDULE} DELIVERED for app ProcessRecord{1cdf222e 4392:com.google.android.gms.persistent/u0a14}
,03-31 15:14:30.997  4392 11022 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-31 15:14:31.002  4392 11022 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 15:14:31.387  3388  4008 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-31 15:14:31.452  3388  4397 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-31 15:14:31.467  4392 11022 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-31 15:14:31.467  2873  3383 D EnterpriseController: netId is 0
03-31 15:14:31.467  2873  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,03-31 15:14:31.472  4392 11022 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-31 15:14:31.477  4392 11022 I qtaguid : Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 4392, getuid(): 10014
,03-31 15:14:31.627  4392 11022 I qtaguid : Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 4392, getuid(): 10014
,03-31 15:14:31.812  9046  9046 D FactoryTest: User mode
,03-31 15:14:31.817  9046  9046 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
03-31 15:14:31.817  9046  9046 D MTPRx   : still no open session command from host, so toast
,03-31 15:14:31.817  9046  9046 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1661 android.content.ContextWrapper.startActivity:338 android.content.ContextWrapper.startActivity:338 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
03-31 15:14:31.817  9046  9046 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1673 android.app.ContextImpl.startActivity:1662 android.content.ContextWrapper.startActivity:338 android.content.ContextWrapper.startActivity:338 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
03-31 15:14:31.817  9046  9046 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:98307
,03-31 15:14:31.817  3388  4460 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-31 15:14:31.822  3388  4460 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,03-31 15:14:31.822  3388  4460 W ActivityManager: mDVFSHelper.acquire()
,03-31 15:14:31.827  3388  4460 V WindowManager: addAppToken: AppWindowToken{c57262 token=Token{f2fbd2d ActivityRecord{187a9844 u0 com.android.settings/.SettingsReceiverActivity t42}}} to stack=1 task=42 at 0
,03-31 15:14:31.827  3388  4460 D PowerManagerService: setKeyboardVisibility: false,
03-31 15:14:31.832  3388  4460 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,03-31 15:14:31.842  3388  4460 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{187a9844 u0 com.android.settings/.SettingsReceiverActivity t42}
,03-31 15:14:31.842  3388  4460 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-31 15:14:31.842  3388  4460 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-31 15:14:31.842  3388  4460 D InputDispatcher: Focused application set to: xxxx
,03-31 15:14:31.842  3388  4460 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 15:14:31.842  3388  4460 D InputDispatcher: Focus left window: 10877
,03-31 15:14:31.847  9046  9046 E MTPRx   : started activity for popup
,03-31 15:14:31.847  3388  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3388 uid:1000
,03-31 15:14:31.847  3388  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-31 15:14:31.847  3388  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3388 uid:1000
03-31 15:14:31.847  3388  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-31 15:14:31.857  3388  6061 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-31 15:14:31.877  9046  9046 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-31 15:14:31.877  9046  9046 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-31 15:14:31.877  9046  9046 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
03-31 15:14:31.877  9046  9046 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 15:14:31.877  9046  9046 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 15:14:31.877  9046  9046 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-31 15:14:31.877  9046  9046 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-31 15:14:31.882  9046  9046 D SecWifiDisplayUtil: Metadata value : none
,03-31 15:14:31.897  9046  9046 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,03-31 15:14:31.897  3388  4236 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,03-31 15:14:31.897  3388  4236 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 15:14:31.897  3388  4236 D InputDispatcher: Focused application set to: xxxx
03-31 15:14:31.897  3388  4236 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-31 15:14:31.897  3388  4236 D InputDispatcher: Focus entered window: 10877
,03-31 15:14:31.902  3388  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3388 uid:1000
,03-31 15:14:31.902  3388  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 15:14:31.902  3388  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3388 uid:1000
03-31 15:14:31.902  3388  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 15:14:31.902  3388  4460 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-31 15:14:31.902  3388  4460 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@16b7bff3 attribute=null, token = android.os.BinderProxy@3ee0148f
,03-31 15:14:31.967  9046  9046 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,03-31 15:14:31.972  9046  9046 D PhoneWindow: *FMB* installDecor mIsFloating : true
03-31 15:14:31.972  9046  9046 D PhoneWindow: *FMB* installDecor flags : 8388610
,03-31 15:14:31.987  3388  3824 D ActivityManager:  Launching com.test.thalitest, updated priority
,03-31 15:14:31.992  3388  3824 D PowerManagerService: setKeyboardVisibility: false
,03-31 15:14:31.992  3388  3824 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{cfe2a8e u0 com.test.thalitest/.MainActivity t41}
,03-31 15:14:32.017 10877 10877 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
03-31 15:14:32.017 10877 10877 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
03-31 15:14:32.017 10877 10877 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
03-31 15:14:32.017 10877 10877 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,03-31 15:14:32.017  3388  3855 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 15:14:32.017  3388  3855 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 15:14:32.017  3388  3855 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 15:14:32.017  3388  3388 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-31 15:14:32.022  3388  3388 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-31 15:14:32.022  3388  3388 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-31 15:14:32.022  3388  3388 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 15:14:32.022  3388  3388 I EnterpriseSharedDevicePolicy: status: false
03-31 15:14:32.022  3388  3388 D PersonaManagerService: getPersonasForUser(): returning null!
03-31 15:14:32.022  3388  3388 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-31 15:14:32.027 10877 10877 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-31 15:14:32.027 10877 10877 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-31 15:14:32.032 10877 10877 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3da7c3c2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@24f4e1d, 16908290=android.view.AbsSavedState$1@24f4e1d}, android:focusedViewId=100}]}]
03-31 15:14:32.032 10877 10877 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
03-31 15:14:32.032 10877 10877 V ActivityThread: updateVisibility : ActivityRecord{14961bc5 token=android.os.BinderProxy@20b4cc2f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-31 15:14:32.032 10877 10877 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-31 15:14:32.032 10877 10877 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,03-31 15:14:32.032 10877 10877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20b4cc2f time:98521
,03-31 15:14:32.182  3388  3855 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-31 15:14:32.197  4392 11022 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-31 15:14:32.197  4392 11022 I qtaguid : Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 4392, getuid(): 10014
,03-31 15:14:32.367  3388  6061 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-31 15:14:32.387  3388  3843 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-31 15:14:32.402  4392 11022 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-31 15:14:32.407  4392 11022 I qtaguid : Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 4392, getuid(): 10014
,03-31 15:14:32.592  3388  4397 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-31 15:14:32.607  3388  4397 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-31 15:14:32.612  4392  4392 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:32.612  4392  4392 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 15:14:32.682  4392 11022 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-31 15:14:32.682  2873  3383 D EnterpriseController: netId is 0
03-31 15:14:32.682  2873  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,03-31 15:14:32.777  4392 11022 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
03-31 15:14:32.777  4392 11022 I qtaguid : Tagging socket 86 with tag 1000040100000000{268436481,0} uid 10014, pid: 4392, getuid(): 10014
,03-31 15:14:32.902  4392 11022 I qtaguid : Tagging socket 93 with tag 1000040100000000{268436481,0} uid 10014, pid: 4392, getuid(): 10014
,03-31 15:14:33.837  4392 11022 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-31 15:14:33.837  4392 11022 I qtaguid : Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 4392, getuid(): 10014
,03-31 15:14:34.027  3388  4029 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-31 15:14:34.052  4392 11022 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-31 15:14:34.057  4392 11022 I qtaguid : Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 4392, getuid(): 10014
,03-31 15:14:34.827  3388  3575 W ActivityManager: mDVFSHelper.release()
,03-31 15:14:36.272  3388  3863 E Watchdog: !@Sync 3 [03-31 15:14:36.271]
,03-31 15:14:37.712  3388  4236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:14:37.712  3388  4236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:14:37.712  3388  4236 D BatteryService: online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:93
,03-31 15:14:37.712  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:14:37.722  3388  4236 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-31 15:14:37.722  3388  4236 D BatteryService: stay LED for fully charged,
,03-31 15:14:37.727  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:14:37.727  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:14:37.727  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:14:37.727  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:14:37.737  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:14:37.737  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:37.737  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:14:37.747  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:14:37.747  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:14:37.762  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:14:37.762  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:37.762  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:37.762  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:39.522  3388  6061 D SSRM:n  : SIOP:: AP = 290, PST = 325 (W:11), CUR = 65, LCD = 0,
,03-31 15:14:43.312  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:14:47.847  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:14:47.847  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:14:47.847  3388  3651 D BatteryService: online:4, current avg:79, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:78
,03-31 15:14:47.852  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:14:47.852  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:14:47.862  3388  3388 I MotionRecognitionService: Plugged
03-31 15:14:47.862  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:14:47.862  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:14:47.862  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:14:47.867  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:47.867  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:47.867  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:14:47.882  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:14:47.882  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:14:47.892  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:14:47.897  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:47.897  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:47.897  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:49.387  3388  3585 I PowerManagerService: [PWL] Off : 50s ago
,03-31 15:14:49.557  3388  6061 D SSRM:n  : SIOP:: AP = 290, PST = 322 (W:12), CUR = 79, LCD = 0
,03-31 15:14:57.987  3388  4460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:14:57.987  3388  4460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:14:57.987  3388  4460 D BatteryService: online:4, current avg:77, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,03-31 15:14:57.987  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:14:57.997  3388  3388 I MotionRecognitionService: Plugged
03-31 15:14:57.997  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:14:57.997  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:14:57.997  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:14:58.002  3388  4460 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:14:58.002  3388  4460 D BatteryService: stay LED for fully charged
,03-31 15:14:58.012  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:14:58.012  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:58.012  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:14:58.032  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:14:58.032  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:14:58.042  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:14:58.042  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:58.042  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:14:58.042  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:14:59.582  3388  6061 D SSRM:n  : SIOP:: AP = 280, PST = 318 (W:12), CUR = 77, LCD = 0
,03-31 15:14:59.997  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:15:03.317  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:15:06.272  3388  3863 E Watchdog: !@Sync 4 [03-31 15:15:06.275]
,03-31 15:15:08.127  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:15:08.127  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:15:08.127  3388  3651 D BatteryService: online:4, current avg:71, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,03-31 15:15:08.127  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:15:08.137  3388  3388 I MotionRecognitionService: Plugged
03-31 15:15:08.137  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:15:08.137  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:15:08.137  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:15:08.142  3388  3651 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms
,03-31 15:15:08.142  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:15:08.152  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:15:08.152  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:15:08.152  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:15:08.167  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:15:08.167  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:15:08.177  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:08.177  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:08.182  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:15:08.182  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:15:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:15:09.612  3388  6061 D SSRM:n  : SIOP:: AP = 280, PST = 312 (W:12), CUR = 71, LCD = 0
,03-31 15:15:14.392  3388  3585 I PowerManagerService: [PWL] Off : 75s ago
,03-31 15:15:18.262  3388  4460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:15:18.267  3388  4460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:15:18.267  3388  4460 D BatteryService: online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,03-31 15:15:18.267  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:15:18.272  3388  4460 D BatteryService: stay LED for fully charged
03-31 15:15:18.277  3388  3388 I MotionRecognitionService: Plugged
03-31 15:15:18.277  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:15:18.277  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:15:18.277  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:15:18.282  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:15:18.287  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:15:18.287  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:15:18.297  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:15:18.297  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:15:18.307  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:18.307  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:18.307  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:18.312  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:15:19.647  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 306 (W:12), CUR = 67, LCD = 0
,03-31 15:15:23.322  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:15:27.107  4392  5729 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-31 15:15:27.927  4642  8669 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-31 15:15:28.402  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:15:28.407  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:15:28.407  3388  3843 D BatteryService: online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,03-31 15:15:28.407  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:15:28.407  3388  3843 D BatteryService: stay LED for fully charged
,03-31 15:15:28.417  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:15:28.417  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:15:28.417  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:15:28.417  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:15:28.422  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:15:28.422  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:28.427  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:15:28.442  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:15:28.442  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:15:28.452  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:15:28.452  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:28.452  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:28.452  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:15:29.677  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 299 (W:12), CUR = 61, LCD = 0
,03-31 15:15:36.282  3388  3863 E Watchdog: !@Sync 5 [03-31 15:15:36.282]
,03-31 15:15:38.542  3388  4009 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:15:38.542  3388  4009 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:15:38.542  3388  4009 D BatteryService: online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,03-31 15:15:38.547  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:15:38.552  3388  3388 I MotionRecognitionService: Plugged
03-31 15:15:38.552  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:15:38.552  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:15:38.552  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:15:38.557  3388  4009 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 15:15:38.557  3388  4009 D BatteryService: stay LED for fully charged
,03-31 15:15:38.567  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:15:38.567  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:15:38.567  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:15:38.582  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:15:38.582  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:15:38.597  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:15:38.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:38.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:38.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:15:39.707  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 294 (W:14), CUR = 57, LCD = 0
,03-31 15:15:43.327  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:15:44.397  3388  3585 I PowerManagerService: [PWL] Off : 105s ago
,03-31 15:15:48.677  3388  4731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:15:48.677  3388  4731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 15:15:48.682  3388  4731 D BatteryService: online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
03-31 15:15:48.682  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:15:48.692  3388  3388 I MotionRecognitionService: Plugged
03-31 15:15:48.692  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:15:48.692  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:15:48.692  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:15:48.692  3388  4731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-31 15:15:48.692  3388  4731 D BatteryService: stay LED for fully charged,
,03-31 15:15:48.702  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:48.702  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:48.702  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:15:48.727  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:15:48.727  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:15:48.737  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:48.737  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:48.737  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:48.737  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:15:49.727  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 287 (W:14), CUR = 52, LCD = 0
,03-31 15:15:50.507  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:15:50.537  3388  3388 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,03-31 15:15:50.542  3388  3388 V AlarmManagerEXT: <AppSync3 Whitelist>
03-31 15:15:50.542  3388  3388 V AlarmManagerEXT: (AppSync) ### 0 added ###
,03-31 15:15:50.547  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 15:15:50.547  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 15:15:50.547  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 15:15:50.562  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 15:15:50.567  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 15:15:50.577  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:50.577  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 15:15:50.582  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 15:15:50.617  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:50.622  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:50.622  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:50.627  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:50.632  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:50.632  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:50.647  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:15:58.822  3388  4236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:15:58.822  3388  4236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:15:58.822  3388  4236 D BatteryService: online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
03-31 15:15:58.822  3388  4236 D BatteryService: stay LED for fully charged
03-31 15:15:58.822  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:15:58.827  3388  3388 I MotionRecognitionService: Plugged
03-31 15:15:58.827  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:15:58.827  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:15:58.827  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:15:58.832  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:58.832  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:15:58.832  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:15:58.847  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:15:58.847  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:15:58.862  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:15:58.862  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:58.862  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:15:58.862  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:15:59.327  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:15:59.757  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 283 (W:14), CUR = 49, LCD = 0
,03-31 15:15:59.997  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:16:03.332  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:16:06.292  3388  3863 E Watchdog: !@Sync 6 [03-31 15:16:06.291]
,03-31 15:16:08.957  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:16:08.957  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:16:08.957  3388  4397 D BatteryService: online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,03-31 15:16:08.957  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:16:08.967  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 15:16:08.967  3388  4397 D BatteryService: stay LED for fully charged,
,03-31 15:16:08.972  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:16:08.972  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:16:08.972  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:16:08.972  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:16:08.982  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:16:08.982  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:16:08.982  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:16:08.997  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:16:08.997  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:16:09.007  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:16:09.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:09.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:09.012  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:16:09.792  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 280 (W:14), CUR = 46, LCD = 0
,03-31 15:16:19.097  3388  4236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:16:19.097  3388  4236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:16:19.097  3388  4236 D BatteryService: online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,03-31 15:16:19.097  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:16:19.107  3388  4236 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 15:16:19.107  3388  4236 D BatteryService: stay LED for fully charged,
,03-31 15:16:19.112  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:16:19.112  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:16:19.112  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:16:19.112  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:16:19.122  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:16:19.122  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:16:19.122  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:16:19.132  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:16:19.132  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:16:19.147  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:16:19.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:19.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:19.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:19.397  3388  3585 I PowerManagerService: [PWL] Off : 140s ago
,03-31 15:16:19.822  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 276 (W:16), CUR = 45, LCD = 0
,03-31 15:16:23.342  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:16:29.237  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:16:29.237  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:16:29.237  3388  4397 D BatteryService: online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-31 15:16:29.237  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:16:29.247  3388  3388 I MotionRecognitionService: Plugged
03-31 15:16:29.247  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:16:29.247  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:16:29.247  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:16:29.247  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms,
,03-31 15:16:29.247  3388  4397 D BatteryService: stay LED for fully charged,
03-31 15:16:29.257  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:16:29.257  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:16:29.257  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:16:29.277  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:16:29.277  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:16:29.287  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:16:29.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:29.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:29.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:29.852  3388  6061 D SSRM:n  : SIOP:: AP = 270, PST = 273 (W:16), CUR = 43, LCD = 0,
,03-31 15:16:36.297  3388  3863 E Watchdog: !@Sync 7 [03-31 15:16:36.298]
,03-31 15:16:39.377  3388  4236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:16:39.377  3388  4236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:16:39.377  3388  4236 D BatteryService: online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
03-31 15:16:39.377  3388  4236 D BatteryService: stay LED for fully charged
03-31 15:16:39.377  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:16:39.382  3388  3388 I MotionRecognitionService: Plugged,
,03-31 15:16:39.382  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:16:39.382  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:16:39.382  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:16:39.392  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:16:39.392  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:16:39.392  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:16:39.407  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:16:39.407  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:16:39.417  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:16:39.417  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:39.417  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:39.417  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:39.887  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 271 (W:16), CUR = 42, LCD = 0
,03-31 15:16:43.347  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:16:49.512  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:16:49.512  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:16:49.512  3388  3855 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,03-31 15:16:49.512  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:16:49.522  3388  3388 I MotionRecognitionService: Plugged
03-31 15:16:49.522  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:16:49.522  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:16:49.522  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:16:49.527  3388  3855 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:16:49.527  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:16:49.537  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:16:49.537  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:16:49.537  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:16:49.562  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:16:49.562  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:16:49.572  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:16:49.572  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:49.572  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:49.572  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:49.922  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 270 (W:16), CUR = 39, LCD = 0
,03-31 15:16:59.397  3388  3585 I PowerManagerService: [PWL] Off : 180s ago
,03-31 15:16:59.652  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:16:59.657  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:16:59.657  3388  3843 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:68
,03-31 15:16:59.657  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:16:59.662  3388  3388 I MotionRecognitionService: Plugged
03-31 15:16:59.662  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:16:59.662  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:16:59.662  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:16:59.667  3388  3843 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:16:59.667  3388  3843 D BatteryService: stay LED for fully charged
,03-31 15:16:59.677  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:16:59.677  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:16:59.677  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:16:59.692  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:16:59.692  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:16:59.707  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:16:59.707  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:59.707  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:16:59.707  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:16:59.952  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 268 (W:18), CUR = 38, LCD = 0
,03-31 15:17:03.357  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:17:06.307  3388  3863 E Watchdog: !@Sync 8 [03-31 15:17:06.305]
,03-31 15:17:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:17:09.782  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:17:09.782  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:17:09.782  3388  3855 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,03-31 15:17:09.782  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:17:09.787  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:17:09.792  3388  3388 I MotionRecognitionService: Plugged
03-31 15:17:09.792  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:17:09.792  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:17:09.792  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:17:09.802  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:17:09.802  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:09.802  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:17:09.817  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:17:09.822  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:17:09.832  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:09.832  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:09.832  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:09.832  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:17:10.002  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:18), CUR = 37, LCD = 0
,03-31 15:17:19.922  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:17:19.922  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:17:19.922  3388  3843 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,03-31 15:17:19.922  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:17:19.927  3388  3843 D BatteryService: stay LED for fully charged
,03-31 15:17:19.932  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:17:19.932  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:17:19.932  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:17:19.932  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:17:19.942  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:19.942  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:17:19.942  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:17:19.967  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:17:19.967  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:17:19.972  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:17:19.977  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:17:19.977  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:19.977  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:17:20.012  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 266 (W:18), CUR = 37, LCD = 0
,03-31 15:17:23.362  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:17:30.037  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:18), CUR = 36, LCD = 0
,03-31 15:17:30.062  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:17:30.067  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:17:30.067  3388  3855 D BatteryService: online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
03-31 15:17:30.067  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:17:30.067  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:17:30.072  3388  3388 I MotionRecognitionService: Plugged
03-31 15:17:30.072  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:17:30.072  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:17:30.072  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:17:30.077  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:30.077  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:17:30.077  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:17:30.092  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:17:30.092  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:17:30.102  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:30.102  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:30.102  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:30.102  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:17:36.312  3388  3863 E Watchdog: !@Sync 9 [03-31 15:17:36.313]
,03-31 15:17:40.067  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 265 (W:20), CUR = 36, LCD = 0
,03-31 15:17:40.182  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:17:40.187  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:17:40.187  3388  3843 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,03-31 15:17:40.187  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:17:40.187  3388  3843 D BatteryService: stay LED for fully charged
,03-31 15:17:40.192  3388  3388 I MotionRecognitionService: Plugged
03-31 15:17:40.192  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:17:40.192  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:17:40.192  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:17:40.202  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:17:40.202  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:40.202  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:17:40.222  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:17:40.222  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:17:40.232  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:40.232  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:40.232  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:40.232  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:17:43.367  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-31 15:17:44.402  3388  3585 I PowerManagerService: [PWL] Off : 225s ago
,03-31 15:17:50.092  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 264 (W:20), CUR = 34, LCD = 0
,03-31 15:17:50.322  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:17:50.327  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:17:50.327  3388  3855 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,03-31 15:17:50.327  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:17:50.327  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:17:50.337  3388  3388 I MotionRecognitionService: Plugged
03-31 15:17:50.337  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:17:50.337  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:17:50.337  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:17:50.342  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:17:50.342  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:50.342  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:17:50.362  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:17:50.362  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:17:50.372  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:17:50.372  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:50.372  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:17:50.372  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:18:00.122  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:20), CUR = 33, LCD = 0
,03-31 15:18:00.462  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:18:00.462  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:18:00.462  3388  3843 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,03-31 15:18:00.467  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:18:00.467  3388  3843 D BatteryService: stay LED for fully charged,
,03-31 15:18:00.472  3388  3388 I MotionRecognitionService: Plugged
03-31 15:18:00.472  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:18:00.472  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:18:00.472  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:18:00.487  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:18:00.487  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:00.487  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:18:00.507  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:18:00.507  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:18:00.517  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:00.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:00.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:00.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:18:03.377  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:18:03.947  3388  3607 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-31 15:18:03.957  3388  3606 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 15:18:03.962  3388  3607 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
,03-31 15:18:03.977  3388  3607 I TLC_TIMA_PKM_initialize: initializing...
,03-31 15:18:03.977  3388  3607 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
03-31 15:18:03.977  3388  3607 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
,03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: root = 0, root_len = 1
03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
,03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: device_id = 0x0
03-31 15:18:03.977  3388  3607 I TZ: mc_tlc_communication: tlc_open() was called
,03-31 15:18:03.982  3388  3607 I TZ: mc_tlc_communication: Opening MobiCore device
,03-31 15:18:03.982  3388  3607 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,03-31 15:18:03.987  3388  3607 I TZ: mc_tlc_communication: Opening the session
,03-31 15:18:04.002  3388  3607 I TZ: mc_tlc_communication: tlc_open() succeeded
,03-31 15:18:04.012  3388  3607 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-31 15:18:06.317  3388  3863 E Watchdog: !@Sync 10 [03-31 15:18:06.320]
,03-31 15:18:08.852  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 15:18:08.852  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 15:18:08.867  3388  3607 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
03-31 15:18:08.872  3388  3607 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 15:18:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:18:10.147  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 263 (W:20), CUR = 33, LCD = 0
,03-31 15:18:10.597  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:18:10.597  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:18:10.597  3388  3855 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-31 15:18:10.602  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:18:10.602  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:18:10.612  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:18:10.612  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:18:10.612  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:18:10.612  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:18:10.622  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:18:10.622  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:10.622  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:18:10.637  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:18:10.637  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:18:10.647  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:10.652  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:10.652  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:10.652  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:18:20.172  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 262 (W:22), CUR = 32, LCD = 0
,03-31 15:18:20.737  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:18:20.737  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:18:20.737  3388  3843 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 15:18:20.737  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:18:20.742  3388  3843 D BatteryService: stay LED for fully charged
,03-31 15:18:20.747  3388  3388 I MotionRecognitionService: Plugged
03-31 15:18:20.747  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:18:20.747  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:18:20.747  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:18:20.757  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:18:20.757  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:18:20.757  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:18:20.777  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:18:20.777  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:18:20.787  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:20.787  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:20.787  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:20.787  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:18:23.382  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:18:30.202  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:22), CUR = 30, LCD = 0
,03-31 15:18:30.872  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:18:30.877  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:18:30.877  3388  3855 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-31 15:18:30.877  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:18:30.877  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:18:30.887  3388  3388 I MotionRecognitionService: Plugged
03-31 15:18:30.887  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:18:30.887  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:18:30.887  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:18:30.897  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:18:30.897  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:30.897  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:18:30.917  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:18:30.917  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:18:30.927  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:30.927  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:30.927  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:30.927  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:18:34.402  3388  3585 I PowerManagerService: [PWL] Off : 275s ago
,03-31 15:18:36.332  3388  3863 E Watchdog: !@Sync 11 [03-31 15:18:36.332]
,03-31 15:18:40.232  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 261 (W:22), CUR = 32, LCD = 0
,03-31 15:18:41.007  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:18:41.012  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:18:41.012  3388  3843 D BatteryService: online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
03-31 15:18:41.012  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:18:41.022  3388  3388 I MotionRecognitionService: Plugged
03-31 15:18:41.022  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:18:41.022  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:18:41.022  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:18:41.027  3388  3843 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-31 15:18:41.027  3388  3843 D BatteryService: stay LED for fully charged,
,03-31 15:18:41.032  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:18:41.032  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:18:41.037  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:18:41.057  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:18:41.057  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:18:41.067  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:41.067  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:41.067  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:41.067  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:18:43.387  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:18:44.457  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:18:44.502  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 15:18:44.502  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 15:18:44.502  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 15:18:44.512  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 15:18:44.522  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 15:18:44.527  3388  3425 D ActivityManager: startService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager
,03-31 15:18:44.532  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.532  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 15:18:44.542  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 15:18:44.557 10420 11267 W appmanager(:<default>):aa: Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,03-31 15:18:44.557 10420 11267 W appmanager(:<default>):aa: Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,03-31 15:18:44.577  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.582  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.582 10420 11267 W appmanager(:<default>):m: No feature status reporters found; is this dead code?
,03-31 15:18:44.587  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.587  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.592  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.592  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.612  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:18:44.672  3388  4037 D ActivityManager: bindService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager, action: null
,03-31 15:18:44.682  3388  4008 D ActivityManager: startService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager
,03-31 15:18:44.722  3388  4029 D ActivityManager: bindService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager, action: null
,03-31 15:18:45.137 10420 11283 I System.out: Thread-1493(ApacheHTTPLog):isSBSettingEnabled false
03-31 15:18:45.137 10420 11283 I System.out: Thread-1493(ApacheHTTPLog):isShipBuild true
03-31 15:18:45.137 10420 11283 I System.out: Thread-1493(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-31 15:18:45.137 10420 11283 I System.out: Thread-1493(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-31 15:18:45.137  2873  3383 D EnterpriseController: netId is 0
03-31 15:18:45.137  2873  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10110
,03-31 15:18:46.042 10420 11283 I System.out: P[5]_NetworkDispatch5 calls detatch()
,03-31 15:18:46.082 10420 11298 I System.out: Thread-1497(ApacheHTTPLog):isSBSettingEnabled false
,03-31 15:18:46.082 10420 11298 I System.out: Thread-1497(ApacheHTTPLog):isShipBuild true
,03-31 15:18:46.082 10420 11298 I System.out: Thread-1497(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-31 15:18:46.082 10420 11298 I System.out: Thread-1497(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-31 15:18:46.212 10420 11298 I System.out: P[5]_NetworkDispatch6 calls detatch()
,03-31 15:18:47.562 10420 10657 W IdleConnectionHandler: Removing a connection that never existed!
,03-31 15:18:49.727  3388  4731 D ActivityManager: bindService callerProcessName:com.facebook.appmanager, calleePkgName: com.facebook.appmanager, action: null
,03-31 15:18:50.262  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:22), CUR = 32, LCD = 0
,03-31 15:18:51.152  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:18:51.152  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:18:51.152  3388  4037 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-31 15:18:51.152  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:18:51.162  3388  3388 I MotionRecognitionService: Plugged
03-31 15:18:51.162  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:18:51.162  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:18:51.162  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:18:51.162  3388  4037 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-31 15:18:51.162  3388  4037 D BatteryService: stay LED for fully charged
,03-31 15:18:51.172  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:18:51.172  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:18:51.172  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:18:51.192  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:18:51.192  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:18:51.202  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:18:51.202  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:51.202  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:18:51.202  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:18:59.997  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:19:00.292  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:24), CUR = 31, LCD = 0
,03-31 15:19:01.292  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:19:01.292  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:19:01.292  3388  4397 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-31 15:19:01.297  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:19:01.297  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:19:01.307  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:19:01.307  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:19:01.307  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:19:01.307  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:19:01.317  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:19:01.317  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:01.317  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:19:01.337  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:19:01.337  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:19:01.347  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:01.347  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:01.347  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:01.352  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:03.397  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:19:06.337  3388  3863 E Watchdog: !@Sync 12 [03-31 15:19:06.339]
,03-31 15:19:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:19:10.322  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:24), CUR = 31, LCD = 0
,03-31 15:19:11.417  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:19:11.417  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:19:11.417  3388  4037 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-31 15:19:11.417  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:19:11.417  3388  4037 D BatteryService: stay LED for fully charged
,03-31 15:19:11.427  3388  3388 I MotionRecognitionService: Plugged
03-31 15:19:11.427  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:19:11.427  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:19:11.427  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:19:11.437  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:11.437  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:11.437  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:19:11.447  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:19:11.447  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:19:11.462  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:19:11.462  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:11.462  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:11.462  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:20.337  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:24), CUR = 30, LCD = 0
,03-31 15:19:21.552  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:19:21.552  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:19:21.552  3388  3855 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-31 15:19:21.557  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:19:21.557  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:19:21.567  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:19:21.567  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:19:21.567  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:19:21.567  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:19:21.577  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:19:21.577  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:21.577  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:19:21.597  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:19:21.597  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:19:21.607  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:21.607  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:21.607  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:21.607  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:23.402  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:19:29.407  3388  3585 I PowerManagerService: [PWL] Off : 330s ago
,03-31 15:19:30.367  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:24), CUR = 30, LCD = 0
,03-31 15:19:31.692  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:19:31.692  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:19:31.692  3388  3843 D BatteryService: online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-31 15:19:31.697  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:19:31.697  3388  3843 D BatteryService: stay LED for fully charged
,03-31 15:19:31.702  3388  3388 I MotionRecognitionService: Plugged
03-31 15:19:31.702  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:19:31.702  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:19:31.702  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:19:31.712  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:19:31.712  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:31.712  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:19:31.737  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:19:31.737  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:19:31.742  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:31.742  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:31.747  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:31.747  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:36.347  3388  3863 E Watchdog: !@Sync 13 [03-31 15:19:36.347]
,03-31 15:19:40.402  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:26), CUR = 29, LCD = 0
,03-31 15:19:41.832  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:19:41.832  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:19:41.832  3388  3855 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-31 15:19:41.832  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:19:41.837  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:19:41.842  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:19:41.842  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:19:41.842  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:19:41.842  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:19:41.852  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:19:41.852  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:41.852  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:19:41.872  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:19:41.872  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:19:41.882  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:41.882  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:41.882  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:41.882  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:43.407  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:19:50.427  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:26), CUR = 28, LCD = 0
,03-31 15:19:51.972  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:19:51.972  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:19:51.972  3388  4029 D BatteryService: online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
03-31 15:19:51.972  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:19:51.977  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:19:51.982  3388  3388 I MotionRecognitionService: Plugged
03-31 15:19:51.982  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:19:51.982  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:19:51.982  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:19:51.992  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:19:51.992  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:19:51.992  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:19:52.017  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:19:52.017  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:19:52.022  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:19:52.027  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:19:52.027  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:19:52.027  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:20:00.462  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:26), CUR = 28, LCD = 0
,03-31 15:20:02.142  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:20:02.142  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:20:02.142  3388  3425 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,03-31 15:20:02.147  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:20:02.147  3388  3425 D BatteryService: stay LED for fully charged,
,03-31 15:20:02.152  3388  3388 I MotionRecognitionService: Plugged
03-31 15:20:02.152  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:20:02.152  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:20:02.152  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:20:02.167  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:20:02.167  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:20:02.167  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:20:02.182  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:20:02.182  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:20:02.192  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:02.192  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:02.192  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:02.197  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:20:03.412  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:20:06.352  3388  3863 E Watchdog: !@Sync 14 [03-31 15:20:06.355],
,03-31 15:20:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:20:10.492  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:26), CUR = 27, LCD = 0
,03-31 15:20:12.282  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:20:12.282  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:20:12.282  3388  4029 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-31 15:20:12.287  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:20:12.287  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:20:12.297  3388  3388 I MotionRecognitionService: Plugged
03-31 15:20:12.297  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:20:12.297  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:20:12.297  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:20:12.302  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:12.307  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:12.312  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:20:12.327  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:20:12.327  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:20:12.337  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:20:12.337  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:12.337  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:12.337  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:20:20.517  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), CUR = 27, LCD = 0
,03-31 15:20:22.417  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:20:22.422  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:20:22.422  3388  3425 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,03-31 15:20:22.422  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:20:22.432  3388  3388 I MotionRecognitionService: Plugged
03-31 15:20:22.432  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:20:22.432  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:20:22.432  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:20:22.432  3388  3425 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
03-31 15:20:22.432  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:20:22.442  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:20:22.442  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:20:22.442  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:20:22.462  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:20:22.467  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:20:22.477  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:20:22.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:22.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:22.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:20:23.417  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:20:29.407  3388  3585 I PowerManagerService: [PWL] Off : 390s ago
,03-31 15:20:30.547  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), CUR = 26, LCD = 0
,03-31 15:20:32.547  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:20:32.552  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:20:32.552  3388  4029 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-31 15:20:32.552  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:20:32.552  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:20:32.557  3388  3388 I MotionRecognitionService: Plugged
03-31 15:20:32.557  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:20:32.557  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:20:32.557  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:20:32.567  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:20:32.567  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:20:32.567  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:20:32.587  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:20:32.587  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:20:32.597  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:20:32.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:32.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:32.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:20:36.362  3388  3863 E Watchdog: !@Sync 15 [03-31 15:20:36.363]
,03-31 15:20:40.577  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), CUR = 26, LCD = 0
,03-31 15:20:42.682  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:20:42.682  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:20:42.682  3388  3425 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-31 15:20:42.682  3388  3425 D BatteryService: stay LED for fully charged
03-31 15:20:42.682  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:20:42.687  3388  3388 I MotionRecognitionService: Plugged
03-31 15:20:42.687  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:20:42.687  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:20:42.687  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:20:42.687  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:42.687  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:20:42.692  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:20:42.697  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:20:42.697  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:20:42.712  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:42.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:42.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:42.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:20:43.422  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:20:50.602  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:28), CUR = 26, LCD = 0
,03-31 15:20:52.827  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:20:52.827  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:20:52.827  3388  4029 D BatteryService: online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,03-31 15:20:52.827  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:20:52.827  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:20:52.842  3388  3388 I MotionRecognitionService: Plugged
03-31 15:20:52.842  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:20:52.842  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:20:52.842  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:20:52.857  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:52.857  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:52.862  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:20:52.867  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:20:52.872  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:20:52.872  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:52.872  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
03-31 15:20:52.872  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:20:52.872  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:20:57.647  2906  2906 I bootchecker: bootchecker wake up!!
,03-31 15:21:00.637  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 26, LCD = 0
,03-31 15:21:02.967  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:21:02.967  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:21:02.967  3388  3425 D BatteryService: online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,03-31 15:21:02.967  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:21:02.972  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:21:02.977  3388  3388 I MotionRecognitionService: Plugged
,03-31 15:21:02.977  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:21:02.977  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:21:02.977  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:21:02.987  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:02.987  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:02.987  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:21:02.997  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:21:02.997  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:21:03.012  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:21:03.012  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:03.012  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:03.012  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:03.432  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-31 15:21:06.367  3388  3863 E Watchdog: !@Sync 16 [03-31 15:21:06.370]
,03-31 15:21:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:21:10.667  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 27, LCD = 0
,03-31 15:21:13.107  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:21:13.107  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:21:13.107  3388  4029 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
03-31 15:21:13.107  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:21:13.107  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:21:13.112  3388  3388 I MotionRecognitionService: Plugged
03-31 15:21:13.112  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:21:13.112  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:21:13.112  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:21:13.117  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:21:13.117  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:13.122  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:21:13.132  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:21:13.132  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:21:13.147  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:21:13.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:13.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:13.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:20.702  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 25, LCD = 0
,03-31 15:21:23.242  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:21:23.242  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:21:23.242  3388  3425 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 15:21:23.242  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:21:23.252  3388  3388 I MotionRecognitionService: Plugged
03-31 15:21:23.252  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:21:23.252  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:21:23.252  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:21:23.252  3388  3425 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-31 15:21:23.252  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:21:23.262  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:21:23.262  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:23.262  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:21:23.277  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:21:23.277  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:21:23.292  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:21:23.292  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:23.292  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:23.292  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:23.432  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:21:30.732  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 24, LCD = 0
,03-31 15:21:33.382  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:21:33.382  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:21:33.382  3388  4029 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,03-31 15:21:33.382  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:21:33.382  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:21:33.392  3388  3388 I MotionRecognitionService: Plugged
03-31 15:21:33.392  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:21:33.392  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:21:33.392  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:21:33.402  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:21:33.402  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:33.402  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:21:33.422  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:21:33.422  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:21:33.432  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:33.432  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:33.432  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:33.432  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:34.412  3388  3585 I PowerManagerService: [PWL] Off : 455s ago
,03-31 15:21:36.377  3388  3863 E Watchdog: !@Sync 17 [03-31 15:21:36.378]
,03-31 15:21:40.762  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 25, LCD = 0
,03-31 15:21:43.432  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:21:43.517  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:21:43.517  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:21:43.517  3388  3425 D BatteryService: online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 15:21:43.522  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:21:43.522  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:21:43.532  3388  3388 I MotionRecognitionService: Plugged
03-31 15:21:43.532  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:21:43.532  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:21:43.532  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:21:43.537  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:21:43.537  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:43.537  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:21:43.562  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:21:43.562  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:21:43.572  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:21:43.572  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:43.572  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:43.572  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:50.787  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 25, LCD = 0
,03-31 15:21:53.657  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:21:53.657  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:21:53.657  3388  4029 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,03-31 15:21:53.662  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:21:53.662  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:21:53.667  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:21:53.667  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:21:53.667  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:21:53.667  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:21:53.677  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:21:53.677  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:21:53.677  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:21:53.697  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:21:53.697  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:21:53.707  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:21:53.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:53.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:21:53.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:21:59.057  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:21:59.087  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 15:21:59.087  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 15:21:59.092  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 15:21:59.102  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 15:21:59.107  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 15:21:59.117  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:21:59.122  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 15:21:59.127  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 15:21:59.172  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:21:59.172  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:21:59.177  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:21:59.182  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:21:59.182  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:21:59.187  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:21:59.202  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:22:00.067  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:22:00.817  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 24, LCD = 0
,03-31 15:22:03.437  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:22:03.797  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:22:03.797  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:22:03.797  3388  4037 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 15:22:03.797  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:22:03.807  3388  3388 I MotionRecognitionService: Plugged
03-31 15:22:03.807  3388  3388 D MotionRecognitionService:   cableConnection= 1,
,03-31 15:22:03.807  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:22:03.807  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
03-31 15:22:03.812  3388  4037 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:22:03.812  3388  4037 D BatteryService: stay LED for fully charged
,03-31 15:22:03.822  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:22:03.822  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:22:03.822  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:22:03.837  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:22:03.842  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:22:03.842  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:22:03.857  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:03.857  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:03.857  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:22:06.382  3388  3863 E Watchdog: !@Sync 18 [03-31 15:22:06.385]
,03-31 15:22:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:22:10.847  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 23, LCD = 0
,03-31 15:22:13.932  3388  4460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:22:13.932  3388  4460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:22:13.932  3388  4460 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 15:22:13.937  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:22:13.937  3388  4460 D BatteryService: stay LED for fully charged
,03-31 15:22:13.947  3388  3388 I MotionRecognitionService: Plugged,
,03-31 15:22:13.947  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:22:13.947  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:22:13.947  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:22:13.957  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:22:13.957  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:22:13.957  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:22:13.977  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:22:13.982  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:22:13.992  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:22:13.992  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:13.992  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:13.992  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:22:20.877  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 23, LCD = 0
,03-31 15:22:23.442  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:22:24.072  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:22:24.072  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:22:24.072  3388  4037 D BatteryService: online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,03-31 15:22:24.072  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:22:24.082  3388  4037 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 15:22:24.082  3388  4037 D BatteryService: stay LED for fully charged,
,03-31 15:22:24.082  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:22:24.082  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:22:24.082  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:22:24.082  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
03-31 15:22:24.097  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:22:24.097  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:22:24.097  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:22:24.117  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:22:24.117  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:22:24.127  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:22:24.127  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:24.127  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:24.127  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:22:30.912  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 23, LCD = 0
,03-31 15:22:34.212  3388  4460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:22:34.212  3388  4460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:22:34.212  3388  4460 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-31 15:22:34.212  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:22:34.222  3388  3388 I MotionRecognitionService: Plugged
03-31 15:22:34.222  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:22:34.222  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:22:34.222  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:22:34.222  3388  4460 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:22:34.222  3388  4460 D BatteryService: stay LED for fully charged
,03-31 15:22:34.232  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:22:34.232  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:22:34.232  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:22:34.247  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:22:34.247  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:22:34.262  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:22:34.262  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:22:34.262  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:34.262  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:22:36.392  3388  3863 E Watchdog: !@Sync 19 [03-31 15:22:36.395],
,03-31 15:22:40.942  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 22, LCD = 0
,03-31 15:22:43.447  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:22:44.347  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:22:44.347  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:22:44.347  3388  4037 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-31 15:22:44.352  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:22:44.357  3388  3388 I MotionRecognitionService: Plugged
03-31 15:22:44.357  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:22:44.357  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:22:44.357  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:22:44.362  3388  4037 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 15:22:44.362  3388  4037 D BatteryService: stay LED for fully charged
,03-31 15:22:44.372  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:22:44.372  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:22:44.372  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:22:44.392  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:22:44.392  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:22:44.402  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:22:44.402  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:44.402  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:44.402  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:22:44.412  3388  3585 I PowerManagerService: [PWL] Off : 525s ago
,03-31 15:22:50.952  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 22, LCD = 0
,03-31 15:22:54.487  3388  4460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:22:54.487  3388  4460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 15:22:54.492  3388  4460 D BatteryService: online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
03-31 15:22:54.492  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:22:54.492  3388  4460 D BatteryService: stay LED for fully charged
,03-31 15:22:54.502  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:22:54.502  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:22:54.502  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:22:54.502  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:22:54.512  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:22:54.512  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:22:54.512  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:22:54.532  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:22:54.532  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:22:54.542  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:22:54.542  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:54.542  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:22:54.542  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:23:00.982  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 22, LCD = 0
,03-31 15:23:03.452  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:23:03.947  3388  3607 D TimaService: TIMA: TimaService scheduler is intialized. 
03-31 15:23:03.947  3388  3607 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-31 15:23:03.952  3388  3606 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 15:23:04.627  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:23:04.632  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:23:04.632  3388  4037 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:23:04.632  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:23:04.632  3388  4037 D BatteryService: stay LED for fully charged
,03-31 15:23:04.637  3388  3388 I MotionRecognitionService: Plugged
,03-31 15:23:04.637  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:23:04.637  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:23:04.637  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:23:04.652  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:23:04.652  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:04.652  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:23:04.667  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:23:04.667  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:23:04.682  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:04.682  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:04.682  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:04.682  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:23:06.402  3388  3863 E Watchdog: !@Sync 20 [03-31 15:23:06.402]
,03-31 15:23:06.472  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 15:23:06.472  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 15:23:06.492  3388  3607 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,03-31 15:23:06.497  3388  3607 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 15:23:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:23:09.592  3388  3580 I ActivityManager: setMaxStartingBackgroundTimer onfinish
03-31 15:23:09.592  3388  3580 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,03-31 15:23:11.012  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 20, LCD = 0
,03-31 15:23:14.767  3388  4460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:23:14.767  3388  4460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:23:14.767  3388  4460 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,03-31 15:23:14.772  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:23:14.777  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:23:14.782  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:23:14.782  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:23:14.782  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:23:14.782  3388  4460 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 15:23:14.782  3388  4460 D BatteryService: stay LED for fully charged
,03-31 15:23:14.792  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:14.792  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:23:14.797  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:23:14.807  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:23:14.807  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:23:14.817  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:14.822  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:14.822  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:14.822  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:23:21.042  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 20, LCD = 0,
,03-31 15:23:23.457  3388  6092 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-31 15:23:24.837  3388  4037 I ActivityManager: Killing 10163:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-31 15:23:24.917  3388  4236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:23:24.917  3388  4236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:23:24.917  3388  4236 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
03-31 15:23:24.917  3388  4236 D BatteryService: stay LED for fully charged
03-31 15:23:24.917  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:23:24.917  3388  3388 I MotionRecognitionService: Plugged
03-31 15:23:24.917  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:23:24.917  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:23:24.917  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:23:24.922  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:24.922  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:23:24.922  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:23:24.927  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:23:24.927  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:23:24.942  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:24.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:24.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:24.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:23:31.072  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0
,03-31 15:23:35.042  3388  4009 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:23:35.042  3388  4009 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:23:35.042  3388  4009 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-31 15:23:35.042  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:23:35.047  3388  4009 D BatteryService: stay LED for fully charged
,03-31 15:23:35.052  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:23:35.052  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:23:35.052  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:23:35.052  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:23:35.062  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:23:35.062  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:23:35.062  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:23:35.082  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:23:35.082  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:23:35.092  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:23:35.092  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:35.092  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:35.092  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:23:36.412  3388  3863 E Watchdog: !@Sync 21 [03-31 15:23:36.414]
,03-31 15:23:41.097  3388  6061 D SSRM:n  : SIOP:: AP = 260, PST = 260 (W:30), CUR = 21, LCD = 0
,03-31 15:23:45.187  3388  4236 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:23:45.187  3388  4236 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:23:45.187  3388  4236 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 15:23:45.187  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-31 15:23:45.192  3388  4236 D BatteryService: stay LED for fully charged
03-31 15:23:45.197  3388  3388 I MotionRecognitionService: Plugged
03-31 15:23:45.197  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:23:45.197  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:23:45.197  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
03-31 15:23:45.202  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:45.202  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:23:45.202  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:23:45.222  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:23:45.222  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:23:45.237  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:23:45.237  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:45.237  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:45.237  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:23:51.122  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:30), CUR = 20, LCD = 0
,03-31 15:23:55.322  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:23:55.322  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:23:55.322  3388  3843 D BatteryService: online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 15:23:55.327  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:23:55.327  3388  3843 D BatteryService: stay LED for fully charged,
,03-31 15:23:55.337  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:23:55.337  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:23:55.337  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:23:55.337  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:23:55.347  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:55.347  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:23:55.347  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:23:55.372  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:23:55.372  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:23:55.382  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:23:55.382  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:55.382  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:23:55.382  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:23:59.417  3388  3585 I PowerManagerService: [PWL] Off : 600s ago
,03-31 15:24:01.152  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:30), CUR = 21, LCD = 0
,03-31 15:24:05.462  3388  4008 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:24:05.462  3388  4008 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:24:05.462  3388  4008 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-31 15:24:05.462  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:24:05.472  3388  3388 I MotionRecognitionService: Plugged
03-31 15:24:05.472  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:24:05.472  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:24:05.472  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:24:05.472  3388  4008 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms,
03-31 15:24:05.472  3388  4008 D BatteryService: stay LED for fully charged
,03-31 15:24:05.482  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:24:05.482  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:05.482  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:24:05.497  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:24:05.502  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:24:05.502  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:24:05.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:05.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:05.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:24:06.422  3388  3863 E Watchdog: !@Sync 22 [03-31 15:24:06.421]
,03-31 15:24:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:24:11.182  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 259 (W:30), CUR = 20, LCD = 0
,03-31 15:24:15.597  3388  3843 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:24:15.602  3388  3843 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:24:15.602  3388  3843 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
03-31 15:24:15.602  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:24:15.607  3388  3843 D BatteryService: stay LED for fully charged
,03-31 15:24:15.612  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:24:15.612  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:24:15.612  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:24:15.612  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:24:15.622  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:24:15.622  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:15.622  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:24:15.642  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:24:15.642  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:24:15.657  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:24:15.657  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:15.657  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:15.657  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:24:21.207  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:30), CUR = 20, LCD = 0,
,03-31 15:24:25.737  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:24:25.737  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:24:25.737  3388  3651 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-31 15:24:25.742  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:24:25.747  3388  3651 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 15:24:25.747  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:24:25.752  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:24:25.752  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:24:25.752  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:24:25.752  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:24:25.762  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:24:25.762  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:25.762  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:24:25.772  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:24:25.772  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:24:25.787  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:24:25.787  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:25.787  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:25.787  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:24:31.232  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:30), CUR = 19, LCD = 0
,03-31 15:24:35.902  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:24:35.907  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:24:35.907  3388  4029 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,03-31 15:24:35.907  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:24:35.917  3388  3388 I MotionRecognitionService: Plugged
03-31 15:24:35.917  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:24:35.917  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:24:35.917  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:24:35.917  3388  4029 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:24:35.917  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:24:35.927  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:24:35.927  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:35.927  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:24:35.942  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:24:35.942  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:24:35.957  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:35.957  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:35.957  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:35.957  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:24:36.427  3388  3863 E Watchdog: !@Sync 23 [03-31 15:24:36.429]
,03-31 15:24:41.257  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 258 (W:30), CUR = 19, LCD = 0
,03-31 15:24:46.047  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:24:46.047  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:24:46.047  3388  3651 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 15:24:46.052  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:24:46.052  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:24:46.057  3388  3388 I MotionRecognitionService: Plugged
03-31 15:24:46.057  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:24:46.057  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:24:46.057  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:24:46.067  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:24:46.067  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:46.067  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:24:46.087  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:24:46.087  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:24:46.097  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:46.097  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:46.097  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:46.097  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:24:51.287  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:30), CUR = 20, LCD = 0
,03-31 15:24:56.182  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:24:56.182  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:24:56.182  3388  4029 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,03-31 15:24:56.187  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:24:56.187  3388  4029 D BatteryService: stay LED for fully charged
,03-31 15:24:56.192  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:24:56.192  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:24:56.192  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:24:56.192  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:24:56.207  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:24:56.207  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:24:56.207  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:24:56.227  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:24:56.227  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:24:56.237  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:24:56.237  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:56.237  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:24:56.237  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:01.107  3388  3618 V AlarmManager: waitForAlarm result :4,
,03-31 15:25:01.137  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-31 15:25:01.137  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-31 15:25:01.137  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-31 15:25:01.147  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-31 15:25:01.167  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-31 15:25:01.177  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.177  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-31 15:25:01.182  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-31 15:25:01.217  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.217  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.222  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.222  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.227  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.232  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.247  3388  3572 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,03-31 15:25:01.247  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-31 15:25:01.247  3388  3572 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,03-31 15:25:01.262  3388  3572 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,03-31 15:25:01.277  3388  3572 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,03-31 15:25:01.297  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:30), CUR = 20, LCD = 0
,03-31 15:25:06.287  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:25:06.292  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:25:06.292  3388  4037 D BatteryService: online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
03-31 15:25:06.292  3388  4037 D BatteryService: stay LED for fully charged
03-31 15:25:06.292  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:25:06.292  3388  3388 I MotionRecognitionService: Plugged
03-31 15:25:06.292  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:25:06.292  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:25:06.292  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:25:06.297  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:06.297  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:06.297  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:25:06.297  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:25:06.302  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:25:06.302  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:25:06.317  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:06.317  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:06.317  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:06.437  3388  3863 E Watchdog: !@Sync 24 [03-31 15:25:06.436]
,03-31 15:25:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:25:11.327  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 257 (W:30), CUR = 20, LCD = 0
,03-31 15:25:16.427  3388  4731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:25:16.432  3388  4731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:25:16.432  3388  4731 D BatteryService: online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-31 15:25:16.432  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:25:16.432  3388  4731 D BatteryService: stay LED for fully charged
,03-31 15:25:16.442  3388  3388 I MotionRecognitionService: Plugged
03-31 15:25:16.442  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:25:16.442  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:25:16.442  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:25:16.447  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:25:16.447  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:16.447  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:25:16.472  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:25:16.472  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:25:16.482  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:16.482  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:16.482  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:16.482  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:19.417  3388  3585 I PowerManagerService: [PWL] Off : 680s ago
,03-31 15:25:21.352  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:30), CUR = 19, LCD = 0
,03-31 15:25:21.537  3388  3405 I art     : Background partial concurrent mark sweep GC freed 55166(5MB) AllocSpace objects, 200(5MB) LOS objects, 33% free, 29MB/44MB, paused 2.796ms total 180.306ms
,03-31 15:25:26.552  3388  4037 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:25:26.552  3388  4037 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:25:26.552  3388  4037 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-31 15:25:26.557  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:25:26.557  3388  4037 D BatteryService: stay LED for fully charged
,03-31 15:25:26.562  3388  3388 I MotionRecognitionService: Plugged
03-31 15:25:26.562  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:25:26.562  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:25:26.562  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:25:26.572  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:25:26.572  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:26.572  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:25:26.587  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:25:26.587  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:25:26.587  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:25:26.602  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:26.602  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:26.602  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:31.282  3388  3618 V AlarmManager: waitForAlarm result :4
,03-31 15:25:31.382  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:30), CUR = 17, LCD = 0
,03-31 15:25:36.447  3388  3863 E Watchdog: !@Sync 25 [03-31 15:25:36.445]
,03-31 15:25:36.672  3388  4731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:25:36.672  3388  4731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:25:36.672  3388  4731 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
03-31 15:25:36.672  3388  4731 D BatteryService: stay LED for fully charged
03-31 15:25:36.672  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:25:36.677  3388  3388 I MotionRecognitionService: Plugged
03-31 15:25:36.677  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:25:36.677  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:25:36.677  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:25:36.682  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:25:36.682  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:36.682  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:25:36.687  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-31 15:25:36.687  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:25:36.702  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:25:36.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:36.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:36.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:41.412  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 256 (W:30), CUR = 17, LCD = 0,
,03-31 15:25:46.817  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:25:46.817  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:25:46.817  3388  3651 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,03-31 15:25:46.822  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:25:46.832  3388  3388 I MotionRecognitionService: Plugged
03-31 15:25:46.832  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:25:46.832  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:25:46.832  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:25:46.832  3388  3651 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-31 15:25:46.832  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:25:46.842  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:25:46.842  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:46.842  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:25:46.867  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:25:46.867  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:25:46.872  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:46.872  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:46.872  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:46.872  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:51.442  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:30), CUR = 15, LCD = 0
,03-31 15:25:56.957  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:25:56.957  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:25:56.957  3388  4397 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
03-31 15:25:56.957  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:25:56.957  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:25:56.962  3388  3388 I MotionRecognitionService: Plugged
,03-31 15:25:56.962  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:25:56.962  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:25:56.962  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:25:56.972  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:25:56.972  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:25:56.972  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:25:56.987  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:25:56.987  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:25:57.002  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:25:57.002  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:57.002  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:25:57.002  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:25:59.997  3388  3618 V AlarmManager: waitForAlarm result :8,
,03-31 15:26:01.472  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:30), CUR = 15, LCD = 0
,03-31 15:26:06.452  3388  3863 E Watchdog: !@Sync 26 [03-31 15:26:06.455]
,03-31 15:26:07.097  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:26:07.097  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:26:07.097  3388  3651 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:26:07.097  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:26:07.107  3388  3388 I MotionRecognitionService: Plugged
03-31 15:26:07.107  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:26:07.107  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:26:07.107  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:26:07.107  3388  3651 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-31 15:26:07.107  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:26:07.122  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:26:07.122  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:07.122  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:26:07.142  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:26:07.142  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:26:07.152  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:07.152  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:07.152  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:07.152  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:09.077  3388  3618 V AlarmManager: waitForAlarm result :8
,03-31 15:26:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:26:11.502  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 255 (W:30), CUR = 16, LCD = 0
,03-31 15:26:17.232  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:26:17.237  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:26:17.237  3388  4397 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,03-31 15:26:17.237  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:26:17.247  3388  3388 I MotionRecognitionService: Plugged
03-31 15:26:17.247  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:26:17.247  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:26:17.247  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:26:17.247  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:26:17.247  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:26:17.257  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:26:17.257  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:17.257  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:26:17.272  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:26:17.272  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:26:17.287  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:17.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:17.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:17.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:21.537  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:30), CUR = 16, LCD = 0
,03-31 15:26:27.377  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:26:27.377  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:26:27.377  3388  3855 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 15:26:27.377  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:26:27.387  3388  3388 I MotionRecognitionService: Plugged
03-31 15:26:27.387  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:26:27.387  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:26:27.387  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:26:27.392  3388  3855 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms,
03-31 15:26:27.392  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:26:27.402  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:26:27.402  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:27.402  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:26:27.422  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:26:27.422  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:26:27.432  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:27.432  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:27.432  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:27.432  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:31.562  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:30), CUR = 18, LCD = 0
,03-31 15:26:36.462  3388  3863 E Watchdog: !@Sync 27 [03-31 15:26:36.462]
,03-31 15:26:37.517  3388  4009 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:26:37.517  3388  4009 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:26:37.517  3388  4009 D BatteryService: online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-31 15:26:37.517  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:26:37.522  3388  4009 D BatteryService: stay LED for fully charged
,03-31 15:26:37.527  3388  3388 I MotionRecognitionService: Plugged
03-31 15:26:37.527  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:26:37.527  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:26:37.527  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:26:37.537  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:26:37.537  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:37.537  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:26:37.552  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:26:37.552  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:26:37.567  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:26:37.567  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:37.567  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:37.567  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:41.592  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 254 (W:30), CUR = 17, LCD = 0
,03-31 15:26:44.417  3388  3585 I PowerManagerService: [PWL] Off : 765s ago
,03-31 15:26:47.657  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:26:47.657  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:26:47.657  3388  3855 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 15:26:47.662  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:26:47.667  3388  3855 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 15:26:47.667  3388  3855 D BatteryService: stay LED for fully charged,
,03-31 15:26:47.672  3388  3388 I MotionRecognitionService: Plugged
03-31 15:26:47.672  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:26:47.672  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:26:47.672  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:26:47.682  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:26:47.682  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:47.682  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:26:47.702  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:26:47.702  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:26:47.712  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:26:47.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:47.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:26:47.712  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:51.622  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:30), CUR = 16, LCD = 0
,03-31 15:26:57.797  3388  4009 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:26:57.797  3388  4009 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:26:57.797  3388  4009 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-31 15:26:57.797  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:26:57.797  3388  4009 D BatteryService: stay LED for fully charged
,03-31 15:26:57.807  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:26:57.807  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:26:57.807  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:26:57.807  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:26:57.817  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:26:57.817  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:26:57.817  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:26:57.842  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:26:57.842  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:26:57.852  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:26:57.852  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:57.852  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:26:57.852  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:27:01.652  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:30), CUR = 16, LCD = 0
,03-31 15:27:06.467  3388  3863 E Watchdog: !@Sync 28 [03-31 15:27:06.470]
,03-31 15:27:07.937  3388  3855 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:27:07.937  3388  3855 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:27:07.937  3388  3855 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,03-31 15:27:07.942  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:27:07.947  3388  3855 D BatteryService: stay LED for fully charged
,03-31 15:27:07.952  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:27:07.952  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:27:07.952  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:27:07.952  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:27:07.962  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:07.962  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:27:07.962  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:27:07.987  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:27:07.987  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:27:07.992  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:27:07.997  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:07.997  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:27:07.997  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:27:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:27:11.682  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 253 (W:30), CUR = 18, LCD = 0
,03-31 15:27:18.077  3388  4009 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:27:21.717  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:30), CUR = 18, LCD = 0
,03-31 15:27:28.217  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:27:28.217  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:27:28.217  3388  3651 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,03-31 15:27:28.222  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:27:28.222  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:27:28.232  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:27:28.232  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:27:28.232  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:27:28.232  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:27:28.242  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:27:28.242  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:28.242  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:27:28.257  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:27:28.257  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:27:28.272  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:27:28.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:28.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:28.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:27:31.742  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:30), CUR = 15, LCD = 0
,03-31 15:27:36.477  3388  3863 E Watchdog: !@Sync 29 [03-31 15:27:36.478]
,03-31 15:27:38.357  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:27:38.362  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:27:38.362  3388  4397 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:27:38.362  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:27:38.367  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:27:38.372  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:27:38.372  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:27:38.372  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:27:38.372  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:27:38.382  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:27:38.382  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:38.382  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:27:38.402  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:27:38.402  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:27:38.412  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:38.412  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:38.412  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:38.412  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:27:41.772  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 252 (W:30), CUR = 15, LCD = 0
,03-31 15:27:48.497  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:27:48.497  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:27:48.497  3388  3651 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-31 15:27:48.502  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:27:48.502  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:27:48.512  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:27:48.512  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:27:48.512  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:27:48.512  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:27:48.522  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:27:48.522  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:48.522  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:27:48.542  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:27:48.542  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:27:48.552  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:48.552  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:48.552  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:48.552  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:27:51.797  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:30), CUR = 15, LCD = 0
,03-31 15:27:58.642  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:27:58.642  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:27:58.642  3388  4397 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,03-31 15:27:58.647  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:27:58.652  3388  3388 I MotionRecognitionService: Plugged
03-31 15:27:58.652  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:27:58.652  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:27:58.652  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
03-31 15:27:58.652  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-31 15:27:58.652  3388  4397 D BatteryService: stay LED for fully charged,
,03-31 15:27:58.662  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:27:58.662  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:58.662  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:27:58.682  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:27:58.682  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:27:58.692  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:27:58.692  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:58.692  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:27:58.692  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:01.822  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:30), CUR = 14, LCD = 0
,03-31 15:28:03.947  3388  3607 D TimaService: TIMA: TimaService scheduler is intialized. 
03-31 15:28:03.947  3388  3607 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-31 15:28:03.952  3388  3606 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 15:28:06.482  3388  3863 E Watchdog: !@Sync 30 [03-31 15:28:06.485]
,03-31 15:28:08.792  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:28:08.792  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:28:08.792  3388  3651 D BatteryService: online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
03-31 15:28:08.792  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:28:08.792  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:28:08.797  3388  3388 I MotionRecognitionService: Plugged
03-31 15:28:08.797  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:28:08.797  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:28:08.797  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:28:08.802  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:28:08.802  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:08.802  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:28:08.822  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:28:08.822  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:28:08.832  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:08.832  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:08.832  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:08.837  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:08.857  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 15:28:08.857  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 15:28:08.872  3388  3607 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 15:28:08.872  3388  3607 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 15:28:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:28:11.847  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 251 (W:30), CUR = 15, LCD = 0
,03-31 15:28:14.417  3388  3585 I PowerManagerService: [PWL] Off : 855s ago
,03-31 15:28:18.932  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:28:18.937  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:28:18.937  3388  4397 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,03-31 15:28:18.937  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:28:18.937  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:28:18.942  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:28:18.942  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:28:18.947  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:28:18.947  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:28:18.957  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:28:18.957  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:18.957  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:28:18.982  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:28:18.982  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:28:18.987  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:18.987  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:18.987  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:18.987  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:21.877  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 15:28:29.072  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:28:29.072  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:28:29.072  3388  3651 D BatteryService: online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-31 15:28:29.072  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:28:29.077  3388  3651 D BatteryService: stay LED for fully charged,
,03-31 15:28:29.082  3388  3388 I MotionRecognitionService: Plugged
03-31 15:28:29.087  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:28:29.087  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:28:29.087  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:28:29.097  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:28:29.097  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:28:29.097  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:28:29.117  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:28:29.117  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:28:29.132  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:29.132  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:29.132  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:29.132  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:31.902  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 16, LCD = 0
,03-31 15:28:36.492  3388  3863 E Watchdog: !@Sync 31 [03-31 15:28:36.492]
,03-31 15:28:39.217  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:28:39.217  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:28:39.217  3388  4397 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 15:28:39.222  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:28:39.222  3388  4397 D BatteryService: stay LED for fully charged,
,03-31 15:28:39.232  3388  3388 I MotionRecognitionService: Plugged
03-31 15:28:39.232  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:28:39.232  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:28:39.232  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:28:39.242  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:28:39.242  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:28:39.242  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:28:39.257  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:28:39.257  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:28:39.272  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:39.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:39.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:39.272  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:41.932  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 15:28:49.357  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:28:49.362  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:28:49.362  3388  3651 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 15:28:49.362  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:28:49.362  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:28:49.372  3388  3388 I MotionRecognitionService: Plugged
,03-31 15:28:49.372  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:28:49.372  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:28:49.372  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:28:49.382  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:28:49.382  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:28:49.387  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:28:49.397  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:28:49.397  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:28:49.407  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:49.407  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:49.407  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:49.407  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:51.962  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0,
,03-31 15:28:59.462  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:28:59.462  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:28:59.462  3388  4397 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
03-31 15:28:59.462  3388  4397 D BatteryService: stay LED for fully charged
03-31 15:28:59.462  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:28:59.467  3388  3388 I MotionRecognitionService: Plugged
03-31 15:28:59.467  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:28:59.467  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:28:59.467  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:28:59.472  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:59.472  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:28:59.472  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:28:59.477  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:28:59.477  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:28:59.477  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:28:59.492  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:28:59.492  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:28:59.492  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:29:01.992  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 15:29:06.497  3388  3863 E Watchdog: !@Sync 32 [03-31 15:29:06.499]
,03-31 15:29:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:29:09.612  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:29:09.612  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:29:09.612  3388  3651 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,03-31 15:29:09.612  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:29:09.617  3388  3651 D BatteryService: stay LED for fully charged,
,03-31 15:29:09.622  3388  3388 I MotionRecognitionService: Plugged
03-31 15:29:09.622  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:29:09.622  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:29:09.622  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:29:09.637  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:29:09.637  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:29:09.637  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:29:09.652  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:29:09.652  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:29:09.662  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:29:09.662  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:09.662  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:09.662  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:29:12.027  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 15:29:19.752  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:29:19.752  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:29:19.752  3388  4397 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 15:29:19.757  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:29:19.757  3388  4397 D BatteryService: stay LED for fully charged,
,03-31 15:29:19.767  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:29:19.767  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:29:19.767  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:29:19.767  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:29:19.772  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:29:19.777  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:19.777  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:29:19.792  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:29:19.792  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:29:19.802  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:29:19.807  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:19.807  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:19.807  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:29:22.057  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 15:29:29.892  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:29:29.892  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:29:29.892  3388  3651 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,03-31 15:29:29.892  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:29:29.902  3388  3651 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-31 15:29:29.902  3388  3651 D BatteryService: stay LED for fully charged,
03-31 15:29:29.907  3388  3388 I MotionRecognitionService: Plugged
03-31 15:29:29.907  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:29:29.907  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:29:29.907  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:29:29.917  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:29.917  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:29.917  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:29:29.927  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:29:29.927  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:29:29.937  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:29:29.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:29.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:29.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:29:32.092  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 14, LCD = 0
,03-31 15:29:36.507  3388  3863 E Watchdog: !@Sync 33 [03-31 15:29:36.507]
,03-31 15:29:40.032  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:29:40.032  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:29:40.032  3388  4397 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 15:29:40.037  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:29:40.042  3388  3388 I MotionRecognitionService: Plugged
03-31 15:29:40.042  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:29:40.042  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:29:40.042  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:29:40.047  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms
03-31 15:29:40.047  3388  4397 D BatteryService: stay LED for fully charged,
,03-31 15:29:40.057  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:40.057  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:40.057  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:29:40.082  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:29:40.082  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:29:40.087  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:40.087  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:40.087  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:40.087  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:29:42.127  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 15:29:49.427  3388  3585 I PowerManagerService: [PWL] Off : 950s ago
,03-31 15:29:50.152  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:29:50.152  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:29:50.152  3388  3651 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 15:29:50.152  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:29:50.157  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:29:50.162  3388  3388 I MotionRecognitionService: Plugged
03-31 15:29:50.162  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:29:50.162  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:29:50.162  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:29:50.172  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:50.172  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:29:50.172  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:29:50.187  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:29:50.187  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:29:50.197  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:29:50.197  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:50.197  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:29:50.197  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:29:52.152  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:30:00.302  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:30:00.302  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:30:00.302  3388  4397 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
03-31 15:30:00.302  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:30:00.302  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:30:00.307  3388  3388 I MotionRecognitionService: Plugged
03-31 15:30:00.307  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:30:00.307  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:30:00.307  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:30:00.317  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:30:00.322  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:30:00.322  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:30:00.332  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:30:00.332  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:30:00.342  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:00.342  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:00.342  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:00.342  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:02.187  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:30:06.512  3388  3863 E Watchdog: !@Sync 34 [03-31 15:30:06.515]
,03-31 15:30:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:30:10.447  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:30:10.447  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:30:10.447  3388  3651 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,03-31 15:30:10.447  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:30:10.447  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:30:10.457  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:30:10.457  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:30:10.457  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:30:10.457  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:30:10.467  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:30:10.467  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:10.467  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:30:10.487  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:30:10.487  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:30:10.497  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:10.497  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:10.497  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:10.497  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:12.217  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:30:20.587  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:30:20.587  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:30:20.587  3388  4397 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,03-31 15:30:20.592  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:30:20.597  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 15:30:20.597  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:30:20.602  3388  3388 I MotionRecognitionService: Plugged
03-31 15:30:20.602  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:30:20.602  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:30:20.602  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:30:20.612  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:30:20.612  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:20.612  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:30:20.627  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:30:20.627  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:30:20.637  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:20.642  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:20.642  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:20.642  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:22.247  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:30:30.722  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:30:30.722  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:30:30.722  3388  3651 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,03-31 15:30:30.722  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:30:30.727  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:30:30.732  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:30:30.732  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:30:30.732  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:30:30.732  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:30:30.742  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:30:30.742  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:30.742  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:30:30.767  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:30:30.767  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:30:30.772  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:30.772  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:30.777  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:30.777  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:32.267  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 15:30:36.527  3388  3863 E Watchdog: !@Sync 35 [03-31 15:30:36.527]
,03-31 15:30:40.862  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:30:40.862  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:30:40.862  3388  4397 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 15:30:40.867  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:30:40.872  3388  3388 I MotionRecognitionService: Plugged
03-31 15:30:40.872  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:30:40.877  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:30:40.877  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:30:40.877  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 16ms,
03-31 15:30:40.877  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:30:40.887  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:40.887  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:40.887  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:30:40.912  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:30:40.912  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:30:40.917  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:30:40.922  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:40.922  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:40.922  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:42.297  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 15:30:51.002  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:30:51.007  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:30:51.007  3388  3651 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 15:30:51.007  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:30:51.007  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:30:51.017  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:30:51.017  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:30:51.017  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:30:51.017  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:30:51.027  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:30:51.027  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:30:51.027  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:30:51.052  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:30:51.052  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:30:51.057  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:30:51.057  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:51.057  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:30:51.057  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:30:52.327  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:31:01.147  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:31:01.147  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:31:01.147  3388  4397 D BatteryService: online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
03-31 15:31:01.147  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:31:01.147  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:31:01.157  3388  3388 I MotionRecognitionService: Plugged
03-31 15:31:01.157  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:31:01.157  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:31:01.157  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:31:01.167  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:01.167  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:01.167  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:31:01.187  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:31:01.187  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:31:01.197  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:01.197  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:01.197  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:01.197  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:02.357  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 13, LCD = 0
,03-31 15:31:06.537  3388  3863 E Watchdog: !@Sync 36 [03-31 15:31:06.535]
,03-31 15:31:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:31:11.287  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:31:11.287  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:31:11.287  3388  3651 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 15:31:11.287  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:31:11.292  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:31:11.297  3388  3388 I MotionRecognitionService: Plugged
03-31 15:31:11.297  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:31:11.297  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:31:11.297  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:31:11.307  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:31:11.307  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:11.307  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-31 15:31:11.332  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:31:11.332  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:31:11.337  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:11.337  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:11.342  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:11.342  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:12.382  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:31:21.427  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:31:21.427  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:31:21.427  3388  4397 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,03-31 15:31:21.427  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:31:21.432  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:31:21.437  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:31:21.437  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:31:21.437  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:31:21.437  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:31:21.447  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:31:21.447  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:21.447  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:31:21.467  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:31:21.467  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:31:21.477  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:21.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:21.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:21.477  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:22.412  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:31:29.432  3388  3585 I PowerManagerService: [PWL] Off : 1050s ago
,03-31 15:31:31.567  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:31:31.567  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:31:31.567  3388  3651 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-31 15:31:31.567  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:31:31.572  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:31:31.577  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:31:31.577  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:31:31.577  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:31:31.577  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:31:31.587  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:31.587  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:31:31.587  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:31:31.607  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:31:31.607  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:31:31.617  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:31:31.622  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:31.622  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:31.622  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:32.437  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:31:36.542  3388  3863 E Watchdog: !@Sync 37 [03-31 15:31:36.543]
,03-31 15:31:41.707  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:31:41.707  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:31:41.707  3388  4397 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:31:41.707  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:31:41.717  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 15:31:41.717  3388  4397 D BatteryService: stay LED for fully charged,
03-31 15:31:41.717  3388  3388 I MotionRecognitionService: Plugged
03-31 15:31:41.717  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:31:41.717  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:31:41.717  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:31:41.727  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:31:41.727  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:41.727  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:31:41.747  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:31:41.747  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:31:41.757  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:31:41.757  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:41.757  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:41.757  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:42.467  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 15:31:51.842  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:31:51.842  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:31:51.842  3388  3651 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,03-31 15:31:51.847  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:31:51.847  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:31:51.857  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:31:51.857  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:31:51.857  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:31:51.857  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:31:51.867  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:31:51.867  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:31:51.867  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:31:51.887  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:31:51.887  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:31:51.897  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:31:51.897  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:51.897  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:31:51.902  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:31:52.492  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:32:01.982  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:32:01.982  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:32:01.982  3388  4397 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-31 15:32:01.987  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:32:01.992  3388  3388 I MotionRecognitionService: Plugged
03-31 15:32:01.992  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:32:01.992  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:32:01.992  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:32:01.997  3388  4397 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:32:01.997  3388  4397 D BatteryService: stay LED for fully charged
,03-31 15:32:02.007  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:32:02.007  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:32:02.007  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:32:02.022  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:32:02.022  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:32:02.022  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:02.027  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:02.037  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:02.037  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:02.522  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:32:06.547  3388  3863 E Watchdog: !@Sync 38 [03-31 15:32:06.550]
,03-31 15:32:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:32:12.122  3388  3651 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:32:12.122  3388  3651 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:32:12.122  3388  3651 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,03-31 15:32:12.122  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:32:12.127  3388  3651 D BatteryService: stay LED for fully charged
,03-31 15:32:12.132  3388  3388 I MotionRecognitionService: Plugged
03-31 15:32:12.132  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:32:12.132  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:32:12.132  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:32:12.142  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:32:12.142  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:32:12.142  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:32:12.157  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:32:12.162  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:32:12.172  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:12.172  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:12.172  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:12.172  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:12.547  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:32:22.262  3388  4397 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:32:22.262  3388  4397 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:32:22.262  3388  4397 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,03-31 15:32:22.267  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:32:22.272  3388  4397 D BatteryService: stay LED for fully charged,
,03-31 15:32:22.277  3388  3388 I MotionRecognitionService: Plugged
03-31 15:32:22.277  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:32:22.277  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:32:22.277  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:32:22.292  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:32:22.292  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:32:22.292  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:32:22.302  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:32:22.302  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:32:22.317  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:22.317  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:22.317  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:22.317  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:22.577  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 15:32:32.402  3388  4460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:32:32.402  3388  4460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:32:32.402  3388  4460 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,03-31 15:32:32.407  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-31 15:32:32.407  3388  4460 D BatteryService: stay LED for fully charged
,03-31 15:32:32.417  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:32:32.417  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:32:32.417  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:32:32.417  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:32:32.422  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:32.422  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:32:32.422  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:32:32.437  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:32:32.437  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:32:32.447  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:32.447  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:32.447  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:32.447  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:32.602  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 15:32:36.557  3388  3863 E Watchdog: !@Sync 39 [03-31 15:32:36.558]
,03-31 15:32:42.542  3388  4009 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:32:42.547  3388  4009 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:32:42.547  3388  4009 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-31 15:32:42.547  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:32:42.547  3388  4009 D BatteryService: stay LED for fully charged
,03-31 15:32:42.557  3388  3388 I MotionRecognitionService: Plugged
03-31 15:32:42.557  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:32:42.557  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:32:42.557  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:32:42.567  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:32:42.567  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:32:42.567  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:32:42.587  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:32:42.587  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:32:42.597  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:42.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:42.597  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:42.607  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:42.617  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:32:52.642  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:32:52.687  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:32:52.687  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:32:52.687  3388  4029 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
03-31 15:32:52.687  3388  4029 D BatteryService: stay LED for fully charged
03-31 15:32:52.687  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:32:52.692  3388  3388 I MotionRecognitionService: Plugged
03-31 15:32:52.692  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:32:52.692  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:32:52.692  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:32:52.692  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:52.692  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:32:52.692  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:32:52.697  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:32:52.702  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:32:52.702  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:32:52.717  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:32:52.717  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:32:52.717  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:02.672  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:33:02.812  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:33:02.812  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:33:02.812  3388  3824 D BatteryService: online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,03-31 15:33:02.812  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:33:02.812  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:33:02.822  3388  3388 I MotionRecognitionService: Plugged
03-31 15:33:02.822  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:33:02.822  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:33:02.822  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:33:02.827  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:33:02.827  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:33:02.832  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:33:02.847  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:33:02.847  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:33:02.862  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:02.862  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:02.862  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:33:02.862  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:03.947  3388  3607 D TimaService: TIMA: TimaService scheduler is intialized. 
03-31 15:33:03.947  3388  3607 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-31 15:33:03.952  3388  3606 D TimaService: TimaServiceHandler.handleMessage what =1
,03-31 15:33:04.597  3388  3572 I UsageStatsService: User[0] Flushing usage stats to disk
,03-31 15:33:06.472  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-31 15:33:06.472  3388  3607 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-31 15:33:06.487  3388  3607 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
03-31 15:33:06.492  3388  3607 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-31 15:33:06.567  3388  3863 E Watchdog: !@Sync 40 [03-31 15:33:06.565]
,03-31 15:33:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:33:12.702  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 12, LCD = 0
,03-31 15:33:12.952  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:33:12.952  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:33:12.952  3388  3425 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,03-31 15:33:12.957  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:33:12.962  3388  3388 I MotionRecognitionService: Plugged
,03-31 15:33:12.962  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:33:12.962  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:33:12.962  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:33:12.967  3388  3425 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:33:12.967  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:33:12.977  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:33:12.977  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:33:12.977  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:33:12.992  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:33:12.992  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:33:13.002  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:13.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:13.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:33:13.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:14.432  3388  3585 I PowerManagerService: [PWL] Off : 1155s ago
,03-31 15:33:22.742  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 15:33:23.092  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:33:23.092  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:33:23.092  3388  3824 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,03-31 15:33:23.092  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:33:23.102  3388  3824 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms
03-31 15:33:23.102  3388  3824 D BatteryService: stay LED for fully charged,
03-31 15:33:23.102  3388  3388 I MotionRecognitionService: Plugged
,03-31 15:33:23.102  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:33:23.102  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:33:23.102  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:33:23.112  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:33:23.112  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:23.112  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:33:23.132  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:33:23.132  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:33:23.142  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:23.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:23.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:33:23.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:32.777  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 15:33:33.227  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:33:33.227  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:33:33.227  3388  3425 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 15:33:33.232  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:33:33.232  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:33:33.242  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:33:33.242  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:33:33.242  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:33:33.242  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:33:33.252  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:33.252  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:33:33.252  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:33:33.272  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:33:33.272  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:33:33.287  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:33.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:33.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:33.287  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:36.572  3388  3863 E Watchdog: !@Sync 41 [03-31 15:33:36.573]
,03-31 15:33:42.802  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 15:33:43.367  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:33:43.367  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:33:43.367  3388  3824 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 15:33:43.367  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:33:43.377  3388  3388 I MotionRecognitionService: Plugged
03-31 15:33:43.377  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:33:43.377  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:33:43.377  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:33:43.377  3388  3824 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms,
03-31 15:33:43.377  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:33:43.387  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:33:43.387  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:43.387  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:33:43.407  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:33:43.407  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:33:43.417  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:33:43.417  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:33:43.417  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:33:43.417  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:33:52.832  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0,
,03-31 15:33:53.507  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:33:53.507  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:33:53.507  3388  3425 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 15:33:53.507  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:33:53.507  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:33:53.517  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:33:53.517  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:33:53.517  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:33:53.517  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:33:53.527  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:33:53.527  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:53.527  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:33:53.547  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:33:53.547  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:33:53.562  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:33:53.562  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:33:53.562  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:33:53.562  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:34:02.867  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:34:03.647  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:34:03.647  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:34:03.647  3388  3824 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,03-31 15:34:03.647  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:34:03.657  3388  3824 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-31 15:34:03.657  3388  3824 D BatteryService: stay LED for fully charged,
,03-31 15:34:03.662  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:34:03.662  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:34:03.662  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:34:03.662  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:34:03.672  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:34:03.672  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:03.672  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:34:03.687  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:34:03.692  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:34:03.702  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:34:03.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:03.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:03.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:34:06.577  3388  3863 E Watchdog: !@Sync 42 [03-31 15:34:06.580]
,03-31 15:34:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:34:12.897  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0,
,03-31 15:34:13.817  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:34:13.817  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:34:13.817  3388  3425 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,03-31 15:34:13.817  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:34:13.817  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:34:13.827  3388  3388 I MotionRecognitionService: Plugged
03-31 15:34:13.827  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:34:13.827  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:34:13.827  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:34:13.837  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:34:13.837  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:13.837  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:34:13.857  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:34:13.857  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:34:13.867  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:13.867  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:13.867  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:13.867  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:34:22.937  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:34:23.952  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:34:23.952  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:34:23.952  3388  3824 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:34:23.957  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:34:23.957  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:34:23.967  3388  3388 I MotionRecognitionService: Plugged
03-31 15:34:23.967  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:34:23.967  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:34:23.967  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:34:23.977  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:34:23.977  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:23.977  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:34:23.997  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:34:23.997  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:34:24.007  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:24.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:24.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:24.007  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:34:32.962  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:34:34.092  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:34:34.092  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:34:34.092  3388  3425 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,03-31 15:34:34.097  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:34:34.097  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:34:34.107  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:34:34.107  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:34:34.107  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:34:34.107  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:34:34.117  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:34:34.117  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:34.117  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:34:34.132  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:34:34.132  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:34:34.147  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:34.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:34.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:34.147  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:34:36.587  3388  3863 E Watchdog: !@Sync 43 [03-31 15:34:36.588]
,03-31 15:34:42.997  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:34:44.227  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:34:44.227  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:34:44.227  3388  3824 D BatteryService: online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:34:44.232  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:34:44.242  3388  3388 I MotionRecognitionService: Plugged
03-31 15:34:44.242  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:34:44.242  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:34:44.242  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
03-31 15:34:44.242  3388  3824 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
03-31 15:34:44.242  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:34:44.247  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:34:44.247  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:44.252  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:34:44.272  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:34:44.272  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:34:44.282  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:44.282  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:44.282  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:44.282  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:34:53.022  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 11, LCD = 0
,03-31 15:34:54.367  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:34:54.367  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
,03-31 15:34:54.372  3388  3425 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
03-31 15:34:54.372  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:34:54.372  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:34:54.382  3388  3388 I MotionRecognitionService: Plugged
03-31 15:34:54.382  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:34:54.382  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:34:54.382  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:34:54.387  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:34:54.387  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:34:54.392  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:34:54.412  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:34:54.412  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:34:54.422  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:34:54.422  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:54.422  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:34:54.422  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:03.052  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:35:04.442  3388  3585 I PowerManagerService: [PWL] Off : 1265s ago
,03-31 15:35:04.507  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:35:04.507  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:35:04.507  3388  3824 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,03-31 15:35:04.512  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:35:04.517  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:35:04.522  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:35:04.522  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:35:04.522  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:35:04.522  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:35:04.532  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:35:04.532  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:04.532  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:35:04.547  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-31 15:35:04.547  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:35:04.567  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:35:04.567  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:04.567  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:04.567  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:06.597  3388  3863 E Watchdog: !@Sync 44 [03-31 15:35:06.596]
,03-31 15:35:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:35:13.082  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:35:14.652  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:35:14.652  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:35:14.652  3388  3425 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:35:14.652  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:35:14.652  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:35:14.662  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:35:14.662  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:35:14.662  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-31 15:35:14.662  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:35:14.672  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:35:14.672  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:14.672  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:35:14.697  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:35:14.697  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:35:14.702  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:35:14.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:14.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:14.702  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:23.112  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:35:24.792  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:35:24.792  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:35:24.792  3388  3824 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,03-31 15:35:24.792  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:35:24.792  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:35:24.802  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:35:24.802  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:35:24.802  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:35:24.802  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:35:24.817  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:35:24.817  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:24.817  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:35:24.837  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:35:24.837  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:35:24.847  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:24.847  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:24.847  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:24.847  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:33.137  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:35:34.932  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:35:34.932  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:35:34.932  3388  3425 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:35:34.937  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:35:34.937  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:35:34.942  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:35:34.942  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:35:34.942  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:35:34.942  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:35:34.957  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:35:34.957  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:34.957  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:35:34.977  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:35:34.977  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:35:34.987  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:34.987  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:34.987  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:34.987  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:36.602  3388  3863 E Watchdog: !@Sync 45 [03-31 15:35:36.604]
,03-31 15:35:43.162  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:35:45.072  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:35:45.072  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:35:45.072  3388  3824 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
03-31 15:35:45.072  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:35:45.072  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:35:45.082  3388  3388 I MotionRecognitionService: Plugged
03-31 15:35:45.082  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:35:45.082  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:35:45.082  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:35:45.087  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:35:45.087  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:45.087  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:35:45.107  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:35:45.107  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:35:45.122  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:35:45.122  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:45.122  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:45.122  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:35:53.192  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:35:55.187  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:35:55.187  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:35:55.187  3388  3425 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
03-31 15:35:55.187  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:35:55.187  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:35:55.192  3388  3388 I MotionRecognitionService: Plugged
03-31 15:35:55.192  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:35:55.192  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:35:55.192  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:35:55.197  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:55.197  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:35:55.197  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:35:55.207  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:35:55.207  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:35:55.222  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:35:55.222  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:55.222  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:35:55.222  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:03.217  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0,
,03-31 15:36:05.327  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:36:05.327  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:36:05.327  3388  3824 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 15:36:05.332  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:36:05.332  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:36:05.337  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:36:05.337  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:36:05.337  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
,03-31 15:36:05.337  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:36:05.352  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:05.352  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:05.352  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:36:05.362  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:36:05.362  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:36:05.377  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:36:05.377  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:05.377  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:05.377  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:06.612  3388  3863 E Watchdog: !@Sync 46 [03-31 15:36:06.611]
,03-31 15:36:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:36:13.247  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:36:15.472  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:36:15.472  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:36:15.472  3388  3425 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,03-31 15:36:15.472  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:36:15.482  3388  3388 I MotionRecognitionService: Plugged
03-31 15:36:15.482  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:36:15.482  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:36:15.482  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:36:15.482  3388  3425 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:36:15.482  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:36:15.492  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:36:15.492  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:15.492  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:36:15.502  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:36:15.502  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:36:15.517  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:36:15.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:15.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:15.517  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:23.282  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:36:25.612  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-31 15:36:25.612  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:36:25.612  3388  3824 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
03-31 15:36:25.612  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:36:25.612  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:36:25.617  3388  3388 I MotionRecognitionService: Plugged
03-31 15:36:25.617  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:36:25.617  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:36:25.617  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:36:25.627  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:36:25.627  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:25.627  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:36:25.642  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:36:25.642  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:36:25.652  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:36:25.652  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:25.652  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:25.652  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:33.307  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0,
,03-31 15:36:35.752  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:36:35.752  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:36:35.752  3388  3425 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 15:36:35.752  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:36:35.752  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:36:35.762  3388  3388 I MotionRecognitionService: Plugged
03-31 15:36:35.762  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:36:35.762  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:36:35.762  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:36:35.772  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:36:35.772  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:35.772  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:36:35.787  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:36:35.787  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:36:35.797  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:35.802  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:35.802  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:35.802  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:36.617  3388  3863 E Watchdog: !@Sync 47 [03-31 15:36:36.619]
,03-31 15:36:43.342  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 15:36:45.892  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:36:45.892  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:36:45.892  3388  3824 D BatteryService: online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,03-31 15:36:45.892  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:36:45.892  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:36:45.902  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:36:45.902  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:36:45.902  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:36:45.902  3388  3388 D MotionRecognitionService: skip setTransmitPower. ,
,03-31 15:36:45.912  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:36:45.912  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:45.912  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:36:45.927  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:36:45.927  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:36:45.937  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:45.937  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:45.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:45.942  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:53.367  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 8, LCD = 0
,03-31 15:36:56.027  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:36:56.027  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:36:56.027  3388  3425 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,03-31 15:36:56.032  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:36:56.032  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:36:56.042  3388  3388 I MotionRecognitionService: Plugged,
03-31 15:36:56.042  3388  3388 D MotionRecognitionService:   cableConnection= 1
,03-31 15:36:56.042  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
03-31 15:36:56.042  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
03-31 15:36:56.052  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:36:56.052  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:36:56.052  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:36:56.077  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:36:56.077  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:36:56.082  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:36:56.082  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:56.082  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:36:56.082  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:36:59.442  3388  3585 I PowerManagerService: [PWL] Off : 1380s ago
,03-31 15:37:03.397  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:37:06.192  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:37:06.192  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:37:06.192  3388  3824 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,03-31 15:37:06.197  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:37:06.197  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:37:06.207  3388  3388 I MotionRecognitionService: Plugged
,03-31 15:37:06.207  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:37:06.207  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:37:06.207  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:37:06.217  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:37:06.217  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:06.217  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:37:06.227  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:37:06.227  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:37:06.242  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-31 15:37:06.242  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:06.242  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:37:06.242  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:37:06.627  3388  3863 E Watchdog: !@Sync 48 [03-31 15:37:06.626]
,03-31 15:37:09.462  2894  4758 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-31 15:37:13.422  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,03-31 15:37:16.337  3388  3425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:37:16.337  3388  3425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:37:16.337  3388  3425 D BatteryService: online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,03-31 15:37:16.337  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-31 15:37:16.347  3388  3388 I MotionRecognitionService: Plugged
03-31 15:37:16.347  3388  3388 D MotionRecognitionService:   cableConnection= 1,
03-31 15:37:16.347  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:37:16.347  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:37:16.352  3388  3425 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 14ms,
03-31 15:37:16.352  3388  3425 D BatteryService: stay LED for fully charged
,03-31 15:37:16.362  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-31 15:37:16.362  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:16.362  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:37:16.387  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:37:16.387  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:37:16.392  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:16.392  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:16.392  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:16.392  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:37:23.447  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 10, LCD = 0
,03-31 15:37:26.477  3388  3824 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:37:26.477  3388  3824 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:37:26.477  3388  3824 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,03-31 15:37:26.477  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:37:26.477  3388  3824 D BatteryService: stay LED for fully charged
,03-31 15:37:26.487  3388  3388 I MotionRecognitionService: Plugged
03-31 15:37:26.487  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:37:26.487  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:37:26.487  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
,03-31 15:37:26.497  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-31 15:37:26.497  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:26.497  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-31 15:37:26.517  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-31 15:37:26.517  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
,03-31 15:37:26.527  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:26.527  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:26.527  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:26.527  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-31 15:37:33.482  3388  6061 D SSRM:n  : SIOP:: AP = 250, PST = 250 (W:30), CUR = 9, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms),03-31 15:37:36.257 12106 12106 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 15:37:36.262 12106 12106 D AndroidRuntime: CheckJNI is OFF
03-31 15:37:36.262 12106 12106 D AndroidRuntime: readGMSProperty: start
03-31 15:37:36.262 12106 12106 D AndroidRuntime: readGMSProperty: already setted!!
03-31 15:37:36.262 12106 12106 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-31 15:37:36.262 12106 12106 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-31 15:37:36.262 12106 12106 D AndroidRuntime: readGMSProperty: end
03-31 15:37:36.262 12106 12106 D AndroidRuntime: addProductProperty: start
03-31 15:37:36.357 12106 12106 E AffinityControl: AffinityControl: registerfunction enter
03-31 15:37:36.372 12106 12106 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-31 15:37:36.382  3388  4731 D PackageManager: START PACKAGE DELETE: observer{619752488}
03-31 15:37:36.382  3388  4731 D PackageManager: pkg{<packageName>}
03-31 15:37:36.382  3388  4731 D PackageManager: user{0}
03-31 15:37:36.382  3388  4731 D PackageManager: caller{2000}
03-31 15:37:36.382  3388  4731 D PackageManager: flags{2}
03-31 15:37:36.387  3388  4731 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-31 15:37:36.387  3388  4731 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-31 15:37:36.387  3388  4731 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-31 15:37:36.387  3388  3591 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-31 15:37:36.387  3388  4731 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 15:37:36.387  3388  4731 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-31 15:37:36.387  3388  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-31 15:37:36.387  3388  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-31 15:37:36.387  3388  3591 D ApplicationPolicy: getApplicationUninstallationEnabled
03-31 15:37:36.387  3388  3591 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-31 15:37:36.387  3388  3591 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
03-31 15:37:36.392  3388  3575 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
03-31 15:37:36.392  3388  3575 I ActivityManager: Killing 10877:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
03-31 15:37:36.407  3388  3575 I ActivityManager:   Force finishing activity 3 ActivityRecord{cfe2a8e u0 com.test.thalitest/.MainActivity t41}
03-31 15:37:36.407  3388  3575 W ActivityManager: mDVFSHelper.acquire()
03-31 15:37:36.502  3388  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
03-31 15:37:36.502  3388  3591 W PackageSettings: Skipping PackageSetting{20470d0c com.example.hello/10691} due to missing metadata
03-31 15:37:36.517  2860  3019 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
03-31 15:37:36.517  3388  3824 I WindowState: WIN DEATH: Window{146831c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
03-31 15:37:36.522  2860  4638 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
03-31 15:37:36.522  3388  3824 D InputDispatcher: Focus left window: 10877
03-31 15:37:36.522  3388  3824 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 15:37:36.522  2860  3021 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
03-31 15:37:36.527  3388  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
03-31 15:37:36.527  3388  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3388 uid:1000
03-31 15:37:36.532  3388  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 15:37:36.532  3388  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3388 uid:1000
03-31 15:37:36.532  3388  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 15:37:36.537  3388  3575 D PowerManagerService: setKeyboardVisibility: false
03-31 15:37:36.537  3388  3575 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{3c05f15a u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40}
03-31 15:37:36.547  3388  3591 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
03-31 15:37:36.552  3388  3591 I ActivityManager:   Force finishing activity 3 ActivityRecord{cfe2a8e u0 com.test.thalitest/.MainActivity t41 f}
03-31 15:37:36.552  3388  3591 W ActivityManager: Duplicate finish request for ActivityRecord{cfe2a8e u0 com.test.thalitest/.MainActivity t41 f}
03-31 15:37:36.592  3388  3591 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-31 15:37:36.597  3920  3920 I art     : Explicit concurrent mark sweep GC freed 1776(92KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 478us total 23.146ms
03-31 15:37:36.602  3388  3575 D InputDispatcher: Focused application released
03-31 15:37:36.602  3388  3692 D TaskPersister: removeObsoleteFile: deleting file=41_task.xml
03-31 15:37:36.602  3388  3692 D TaskPersister: removeObsoleteFile: deleting file=41_task_thumbnail.png
03-31 15:37:36.602  3388  4029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-31 15:37:36.602  3388  4029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-31 15:37:36.602  3388  4029 D BatteryService: online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
03-31 15:37:36.602  3388  4029 D BatteryService: stay LED for fully charged
03-31 15:37:36.607  6567  6567 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(433/onResume)] 
03-31 15:37:36.627  4130  4130 I art     : Explicit concurrent mark sweep GC freed 14207(923KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 699us total 73.083ms
03-31 15:37:36.632  3388  3863 E Watchdog: !@Sync 49 [03-31 15:37:36.633]
03-31 15:37:36.632  9213  9213 I art     : Explicit concurrent mark sweep GC freed 21176(1187KB) AllocSpace objects, 2(32KB) LOS objects, 69% free, 1812KB/5MB, paused 1.592ms total 64.865ms
03-31 15:37:36.632  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
03-31 15:37:36.637  4014  4014 I art     : Explicit concurrent mark sweep GC freed 16029(920KB) AllocSpace objects, 7(1074KB) LOS objects, 12% free, 56MB/64MB, paused 558us total 53.034ms
03-31 15:37:36.637  4642  4642 I art     : Explicit concurrent mark sweep GC freed 4766(321KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 9MB/12MB, paused 1.182ms total 80.006ms
03-31 15:37:36.652  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
03-31 15:37:36.657  4531  4531 E SamsungIME: mOCRHelper is null
03-31 15:37:36.657  3388  3631 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-31 15:37:36.657  4392  4792 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-31 15:37:36.657  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-31 15:37:36.667  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-31 15:37:36.672  6567  6567 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(443/onResume)] Postpone Count : 0
03-31 15:37:36.672 10583 10583 D LWLocationManager: getDeviceLocationId :  id = -100
03-31 15:37:36.672 10583 10583 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-31 15:37:36.677  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5475/llIlIIIIlllIlllllIll)] Download Postpone status : 0
03-31 15:37:36.687  3388  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 15:37:36.687  3388  3653 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-31 15:37:36.687  3388  3653 V NetworkStats: performPollLocked(flags=0x3)
03-31 15:37:36.692  4642  4653 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-31 15:37:36.692  3388  3653 V NetworkStats: performPollLocked() took 6ms
03-31 15:37:36.692  3388  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 15:37:36.697  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.697  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.697  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.697  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.702  5599  5617 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-31 15:37:36.702  5599  5617 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
03-31 15:37:36.712 12126 12126 E Zygote  : MountEmulatedStorage()
03-31 15:37:36.717 12126 12126 E Zygote  : v2
03-31 15:37:36.717 12126 12126 I libpersona: KNOX_SDCARD checking this for 10063
03-31 15:37:36.717 12126 12126 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:36.717 12126 12126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:36.717  3388  3575 I ActivityManager: Start proc 12126:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
03-31 15:37:36.722 12126 12126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:36.722 12126 12126 E Zygote  : accessInfo : 0
03-31 15:37:36.722  6567  6567 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-31 15:37:36.722  6567  6567 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(327/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
03-31 15:37:36.722 12126 12126 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 15:37:36.732  3981  3981 D RegisteredServicesCache: empty dynamic service
03-31 15:37:36.742  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5134/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-31 15:37:36.757  3388  3388 I art     : Explicit concurrent mark sweep GC freed 72284(9MB) AllocSpace objects, 373(5MB) LOS objects, 33% free, 30MB/45MB, paused 2.289ms total 165.551ms
03-31 15:37:36.757  3388  3388 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-31 15:37:36.757  3388  3591 I art     : WaitForGcToComplete blocked for 155.890ms for cause Explicit
03-31 15:37:36.757  3981  3981 D RegisteredComponentCache: Collect Tech packages for Knox
03-31 15:37:36.762 12126 12126 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:37:36.767 12126 12126 D ActivityThread: Added TimaKeyStore provider
03-31 15:37:36.767  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:36.767  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:36.767  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
03-31 15:37:36.777  5866  5866 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-31 15:37:36.777  5866  5944 D HeadsetStateMachine: Disconnected process message: 10
03-31 15:37:36.782  3388  3651 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-31 15:37:36.782  3388  3651 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-31 15:37:36.787  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-31 15:37:36.787  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:36.792  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:36.792  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-31 15:37:36.797  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5412/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
03-31 15:37:36.807  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5054/IIlllIlIIlIllIlllIll)] Get Force status : 0
03-31 15:37:36.812  3388  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 15:37:36.812  3388  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-31 15:37:36.817  3388  4460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{313d48be u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{24360d1f 12126:com.samsung.android.app.vrsetupwizardstub/u0a63}
03-31 15:37:36.822  6567  6567 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5434/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-31 15:37:36.827  6567  6567 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(537/llIIIIlllllIIllIIllI)] Check Force Install : false
03-31 15:37:36.827  6567  6567 I DBG_DM  : [llIIlIIlIllIllIlllII(337/IllIlIIIIlIIlIIIllIl)] 
03-31 15:37:36.832  6567  6567 I DBG_DM  : [llIIlIIlIllIllIlllII(343/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
03-31 15:37:36.832  3388  3651 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-31 15:37:36.832  3388  3651 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-31 15:37:36.832  3388  3651 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-31 15:37:36.832  6567  6567 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(425/onPause)] 
03-31 15:37:36.842  3388  3427 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-31 15:37:36.842  2860  2860 I SurfaceFlinger: id=16 createSurf (1440x2560),1 flag=404, YUIInstallC
03-31 15:37:36.847  3388  3425 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-31 15:37:36.847  3388  3578 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1039191b u0 d0 com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}
03-31 15:37:36.847  3388  3425 D InputDispatcher: Focus entered window: 6567
03-31 15:37:36.852  6567  6567 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-31 15:37:36.852  3388  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3388 uid:1000
03-31 15:37:36.852  3388  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-31 15:37:36.852  3388  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3388 uid:1000
03-31 15:37:36.852  3388  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-31 15:37:36.852  6567  9032 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
03-31 15:37:36.852 12126 12126 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-31 15:37:36.852  6567  6567 V ActivityThread: updateVisibility : ActivityRecord{289bef14 token=android.os.BinderProxy@6af5fda {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
03-31 15:37:36.852 12126 12126 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-31 15:37:36.852 12126 12126 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
03-31 15:37:36.857  3388  4008 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-31 15:37:36.862  3388  4236 I ActivityManager: Killing 9970:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
03-31 15:37:36.862  3388  4008 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 10877 uid 10011
03-31 15:37:36.862  3388  4236 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{313d48be u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2a028045 7143:com.samsung.klmsagent/u0a21}
03-31 15:37:36.877  7143  7143 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 31 15:37:36 GMT+02:00 2016
03-31 15:37:36.892  4531  4531 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-31 15:37:36.892  3388  3824 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-31 15:37:36.902  7143  7143 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
03-31 15:37:36.902  7143  7143 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
03-31 15:37:36.902  7143  7143 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-31 15:37:36.902  6567  6567 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6af5fda time:1483394
03-31 15:37:36.902  3388  4460 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-31 15:37:36.907  3388  4460 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
03-31 15:37:36.907  7143  7143 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-31 15:37:36.907  7143 12144 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-31 15:37:36.907  7143 12144 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-31 15:37:36.907  7143 12144 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-31 15:37:36.907  7143 12144 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-31 15:37:36.907  7143 12144 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-31 15:37:36.907  7143 12144 I KLMS-2.5.262: : MDMBridge.getInstance()
03-31 15:37:36.907  7143 12144 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-31 15:37:36.907  7143 12144 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-31 15:37:36.912  7143 12144 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-31 15:37:36.912  3388  4460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{313d48be u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1876f794 6799:com.samsung.aasaservice/1000}
03-31 15:37:36.912  6799  6799 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
03-31 15:37:36.912  7143 12144 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
03-31 15:37:36.912  6799  6799 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-31 15:37:36.912  6799  6799 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-31 15:37:36.912  6799  6799 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-31 15:37:36.912  6799  6799 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-31 15:37:36.912  6799  6799 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-31 15:37:36.912  6799  6799 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-31 15:37:36.912  6799  6799 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 15:37:36.912  6799  6799 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 15:37:36.912  6799  6799 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-31 15:37:36.912  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 15:37:36.912  6799  6799 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 15:37:36.912  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 15:37:36.912  6799  6799 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 15:37:36.912  7143 12144 E KLMS-2.5.262: : arr si null
03-31 15:37:36.912  3388  3580 W ActivityManager: mDVFSHelper.release()
03-31 15:37:36.917  3388  3580 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c05f15a u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t40} time:1483405
03-31 15:37:36.917  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.917  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.917  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.917  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.927  7143 12144 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-31 15:37:36.927  7143 12144 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-31 15:37:36.927  7143 12144 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-31 15:37:36.927  7143 12144 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
03-31 15:37:36.942 12146 12146 E Zygote  : MountEmulatedStorage()
03-31 15:37:36.947 12146 12146 E Zygote  : v2
03-31 15:37:36.947 12146 12146 I libpersona: KNOX_SDCARD checking this for 10042
03-31 15:37:36.947 12146 12146 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:36.947 12146 12146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:36.947 12146 12146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:36.952  3388  3575 I ActivityManager: Start proc 12146:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
03-31 15:37:36.957  3388  3575 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3afcdeed u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{df9bf7c 10960:com.samsung.android.sm/1000}
03-31 15:37:36.957 12146 12146 E Zygote  : accessInfo : 0
03-31 15:37:36.957 12146 12146 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-31 15:37:36.957  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.957  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.957  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.957  3388  3575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:36.972  3388  3591 I art     : Explicit concurrent mark sweep GC freed 13888(1158KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 29MB/44MB, paused 3.091ms total 214.527ms
03-31 15:37:36.977 12160 12160 E Zygote  : MountEmulatedStorage()
03-31 15:37:36.977 12160 12160 E Zygote  : v2
03-31 15:37:36.977 12160 12160 I libpersona: KNOX_SDCARD checking this for 1000
03-31 15:37:36.977 12160 12160 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:36.982 12160 12160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:36.982  3388  3575 I ActivityManager: Start proc 12160:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
03-31 15:37:36.987 12160 12160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:36.987 12160 12160 E Zygote  : accessInfo : 0
03-31 15:37:36.987 12160 12160 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 15:37:36.992 12146 12146 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:37:36.992 12146 12146 D ActivityThread: Added TimaKeyStore provider
03-31 15:37:36.997  7143 12144 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-31 15:37:36.997  7143 12144 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-31 15:37:36.997  7143 12144 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-31 15:37:36.997  7143 12144 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
03-31 15:37:37.002  3388  4460 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{313d48be u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1903f06c 3388:system/1000}
03-31 15:37:37.007  7143 12144 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-31 15:37:37.007  7143 12144 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-31 15:37:37.007  7143 12144 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-31 15:37:37.007  7143 12144 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
03-31 15:37:37.007 10960 10960 I art     : Explicit concurrent mark sweep GC freed 150(20KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1735KB/3MB, paused 485us total 16.649ms
03-31 15:37:37.012 10583 12133 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-31 15:37:37.012  3388  3824 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{2609de2a u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3260941b 12146:com.samsung.android.sdk.samsunglink/u0a42}
03-31 15:37:37.017  7143  7143 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
03-31 15:37:37.022 12160 12160 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:37:37.022 12160 12160 D ActivityThread: Added TimaKeyStore provider
03-31 15:37:37.027 12146 12146 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 15:37:37.027 12146 12146 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-31 15:37:37.032  3388  4008 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1e4dc7d0 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{34dfa3c9 12160:com.sec.android.app.popupuireceiver/1000}
03-31 15:37:37.037  3388  3824 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3afcdeed u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{df9bf7c 10960:com.samsung.android.sm/1000}
03-31 15:37:37.042  3388  3824 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3afcdeed u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{df9bf7c 10960:com.samsung.android.sm/1000}
03-31 15:37:37.047  3388  3591 D PackageManager: delete codoeFile: 
03-31 15:37:37.047  3388  3591 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-31 15:37:37.047  3388  4397 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.047  3388  4397 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.047  3388  4397 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.047  3388  4397 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.052 12160 12160 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
03-31 15:37:37.052  3388  3591 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-31 15:37:37.057  3388  3591 I AASA_removePackage: UID=10011 Target=com.test.thalitest
03-31 15:37:37.057 10960 12176 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-31 15:37:37.057  3388  3591 D PackageManager: result of delete: 1{619752488}
03-31 15:37:37.062 12106 12106 I art     : System.exit called, status: 0
03-31 15:37:37.062 12106 12106 I AndroidRuntime: VM exiting with result code 0.
03-31 15:37:37.067  3388  3591 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-31 15:37:37.067  3388  3591 D PackageManager: userId{-1}
03-31 15:37:37.067  3388  3591 D PackageManager: andCode{true}
03-31 15:37:37.067 12180 12180 E Zygote  : MountEmulatedStorage()
03-31 15:37:37.067 12180 12180 I libpersona: KNOX_SDCARD checking this for 1000
03-31 15:37:37.067 12180 12180 E Zygote  : v2
03-31 15:37:37.067 12180 12180 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:37.067 12180 12180 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:37.072 12180 12180 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:37.072  3388  4397 I ActivityManager: Start proc 12180:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
03-31 15:37:37.072 12180 12180 E Zygote  : accessInfo : 0
03-31 15:37:37.072 12180 12180 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 15:37:37.077  3388  4731 D SecContentProvider2: query(), uri = -1 selection = getSealedState
03-31 15:37:37.082  3388  4731 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
03-31 15:37:37.082 12160 12160 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
03-31 15:37:37.082  3388  4009 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
03-31 15:37:37.087  4014  4014 D Launcher.Model: reloadBadges entered.
03-31 15:37:37.087 10699 10711 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
03-31 15:37:37.087 10699 10711 D BadgeProvider: sendNotify, [notify] : null
03-31 15:37:37.087 10699 10711 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-31 15:37:37.087 10699 10711 D BadgeProvider: update, [uri.query] : null
03-31 15:37:37.087 10699 10711 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-31 15:37:37.087 10699 10711 D BadgeProvider: update, [UpdateCount] : 1
03-31 15:37:37.087  3388  3388 D RCPManagerService: PackageReceiver onReceive()
03-31 15:37:37.087 10583 12133 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-31 15:37:37.087  3388  3388 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-31 15:37:37.087 10583 12133 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 15:37:37.087 10583 12133 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 15:37:37.087 10583 12133 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-31 15:37:37.092 12160 12160 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-31 15:37:37.092 12160 12160 D PopupuiReceiver: Action package removed
03-31 15:37:37.092  3388  3388 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-31 15:37:37.092  3388  3388 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-31 15:37:37.092  3388  3388 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
03-31 15:37:37.097  3388  3388 I OTPFW   : ProvisionData::getAllEntries Enter
03-31 15:37:37.097  3388  3388 E OTPFW   : ProvisionData::getAllEntries Table is empty
03-31 15:37:37.097  9624 12195 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-31 15:37:37.097  9624 12195 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
03-31 15:37:37.097  9624 12195 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-31 15:37:37.097  9624 12195 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
03-31 15:37:37.102 12180 12180 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:37:37.102  9624 12195 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-31 15:37:37.102  9624 12195 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
03-31 15:37:37.102 12180 12180 D ActivityThread: Added TimaKeyStore provider
03-31 15:37:37.102  3388  3651 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1e4dc7d0 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{655f9a7 10515:com.samsung.android.snote/u0a160}
03-31 15:37:37.102  3388  3388 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-31 15:37:37.102  3388  3388 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 15:37:37.107  3388  3388 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-31 15:37:37.107  3388  3388 V EnterpriseBillingPolicy: uID is 10011
03-31 15:37:37.107  3388  3388 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 15:37:37.107  3388  3388 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 15:37:37.112  3388  3388 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 15:37:37.112  3388  3388 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 15:37:37.112  3388  3388 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 15:37:37.112  3388  3388 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-31 15:37:37.112  3388  3388 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 15:37:37.112  3388  3388 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-31 15:37:37.112  3388  3388 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-31 15:37:37.112  3388  3388 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
03-31 15:37:37.112 10699 10711 D BadgeProvider: query, [selection] : null
03-31 15:37:37.117  3388  3388 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-31 15:37:37.117  3388  4009 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3afcdeed u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{386c0f06 12180:com.samsung.android.app.assistantmenu/1000}
03-31 15:37:37.122  3388  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.122  3388  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.122  3388  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.122  3388  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.127  3388  3593 D EnterprisePartitionManager: RCV <-
03-31 15:37:37.127  3388  3388 D EnterprisePartitionManager: RMV <-
03-31 15:37:37.137 12146 12146 I SL_DEBUG: isLoggable:: isProductShip = 1
03-31 15:37:37.142  3388  3388 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-31 15:37:37.142 12146 12146 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
03-31 15:37:37.142  3388  3388 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-31 15:37:37.142  3388  3388 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 15:37:37.142  3388  3388 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-31 15:37:37.142  3388  3388 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-31 15:37:37.142  3388  3388 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 15:37:37.142  3388  3388 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 15:37:37.142  3388  3388 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-31 15:37:37.142 12201 12201 I libpersona: KNOX_SDCARD checking this for 10183
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-31 15:37:37.142 12201 12201 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:37.142  3388  3388 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 15:37:37.142  3388  3388 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-31 15:37:37.142  3388  3388 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-31 15:37:37.142  3388  3388 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-31 15:37:37.142  3388  3388 W System.err: 	at libcore.io.Posix.open(Native Method)
03-31 15:37:37.142  3388  3388 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 15:37:37.142  3388  3388 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 15:37:37.142  3388  3388 W System.err: 	... 18 more
03-31 15:37:37.142  3388  3388 E SdpManagerService: failed to get engine list
03-31 15:37:37.142 12201 12201 E Zygote  : MountEmulatedStorage()
03-31 15:37:37.142 12201 12201 E Zygote  : v2
03-31 15:37:37.142 12201 12201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicy: uID is 10011
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicy: Removed Packageuid is0
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-31 15:37:37.142  3388  6061 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-31 15:37:37.142  3388  3388 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-31 15:37:37.142  3388  3388 I MotionRecognitionService: Plugged
03-31 15:37:37.142  3388  3388 D MotionRecognitionService:   cableConnection= 1
03-31 15:37:37.142  3388  3388 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-31 15:37:37.142  3388  3388 D MotionRecognitionService: skip setTransmitPower. 
03-31 15:37:37.147 12201 12201 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:37.147  3388  3651 I ActivityManager: Start proc 12201:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
03-31 15:37:37.147 12201 12201 E Zygote  : accessInfo : 0
03-31 15:37:37.147 12201 12201 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 15:37:37.157  3388  3388 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-31 15:37:37.157  3388  3388 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-31 15:37:37.162  3388  3388 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
03-31 15:37:37.162  3388  3388 I EnterpriseSharedDevicePolicy: Get Result: -1
03-31 15:37:37.162  3388  3388 D PersonaManagerService: getPersonasForUser(): returning null!
03-31 15:37:37.162  3388  3388 I EnterpriseSharedDevicePolicy: status: false
03-31 15:37:37.162  3388  4029 I ActivityManager: Killing 10242:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
03-31 15:37:37.162  3388  3388 I KnoxTimeoutHandler: Shared devices show user statefalse
03-31 15:37:37.162  3388  3388 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-31 15:37:37.162  3726  3726 D PanelView: There is/are notification(s) 
03-31 15:37:37.167  3388  3388 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{313d48be u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{c174623 6126:com.sec.android.service.health/u0a19}
03-31 15:37:37.172  6126  6126 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
03-31 15:37:37.172  6126  6126 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-31 15:37:37.172  6126  6126 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-31 15:37:37.182  3388  3824 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{313d48be u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2eb2e4f0 10583:com.sec.android.widgetapp.locationwidget/u0a22}
03-31 15:37:37.187 10583 10583 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-31 15:37:37.187 12201 12201 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:37:37.187 12201 12201 D ActivityThread: Added TimaKeyStore provider
03-31 15:37:37.197  3388  3855 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1e4dc7d0 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{64ff8de 12201:com.samsung.android.provider.shootingmodeprovider/u0a183}
03-31 15:37:37.207 12180 12180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
03-31 15:37:37.207  3388  3427 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-31 15:37:37.217  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.217  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.217  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.217  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.227  3726  3726 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
03-31 15:37:37.232 12218 12218 E Zygote  : MountEmulatedStorage()
03-31 15:37:37.232 12218 12218 E Zygote  : v2
03-31 15:37:37.232 12218 12218 I libpersona: KNOX_SDCARD checking this for 1000
03-31 15:37:37.232 12218 12218 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:37.232 12218 12218 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:37.232  3726  3726 D PanelView: There is/are notification(s) 
03-31 15:37:37.232  3726  3726 D PanelView: kidsfalse mQsExpansionEnabled:true
03-31 15:37:37.237 12218 12218 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:37.237 12218 12218 E Zygote  : accessInfo : 0
03-31 15:37:37.237 12218 12218 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 15:37:37.237  3388  4460 I ActivityManager: Start proc 12218:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
03-31 15:37:37.237  3726  3726 D PanelView: There is/are notification(s) 
03-31 15:37:37.237  3726  3726 D PanelView: kidsfalse mQsExpansionEnabled:true
03-31 15:37:37.247  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.247  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.247  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.247  3388  4460 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.247 12201 12201 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-31 15:37:37.262 12233 12233 E Zygote  : MountEmulatedStorage()
03-31 15:37:37.262 12233 12233 E Zygote  : v2
03-31 15:37:37.262 12233 12233 I libpersona: KNOX_SDCARD checking this for 1000
03-31 15:37:37.262 12233 12233 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:37.262 12233 12233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:37.267 12218 12218 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:37:37.267  3388  4460 I ActivityManager: Start proc 12233:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
03-31 15:37:37.267 12218 12218 D ActivityThread: Added TimaKeyStore provider
03-31 15:37:37.267 12233 12233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:37.267 12233 12233 E Zygote  : accessInfo : 0
03-31 15:37:37.267 12233 12233 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 15:37:37.277  3388  4037 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3afcdeed u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{275ec4ea 12218:com.sec.knox.bridge/1000}
03-31 15:37:37.282  3388  4460 I ActivityManager: Killing 10285:com.facebook.system/u0a10 (adj 15): emptyCount ##31
03-31 15:37:37.282  3388  3843 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-31 15:37:37.297  3388  3855 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.297  3388  3855 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.297  3388  3855 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.297  3388  3855 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-31 15:37:37.297 10960 12177 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-31 15:37:37.297 10960 12177 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-31 15:37:37.302 12233 12233 D TimaKeyStoreProvider: TimaSignature is unavailable
03-31 15:37:37.302 12233 12233 D ActivityThread: Added TimaKeyStore provider
03-31 15:37:37.307  3726  3726 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-31 15:37:37.307 12218 12218 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: #################################################################
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	(disk I/O error (code 778))
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: #################################################################
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-31 15:37:37.307 10960 12177 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-31 15:37:37.312 12250 12250 E Zygote  : MountEmulatedStorage()
03-31 15:37:37.312 12250 12250 E Zygote  : v2
03-31 15:37:37.312 12250 12250 I libpersona: KNOX_SDCARD checking this for 10190
03-31 15:37:37.312 12250 12250 I libpersona: KNOX_SDCARD not a persona
03-31 15:37:37.317  3388  3855 I ActivityManager: Start proc 12250:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
03-31 15:37:37.327 12250 12250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.1.1 ver=38
03-31 15:37:37.332 12250 12250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.1.1_0038
03-31 15:37:37.332 12250 12250 E Zygote  : accessInfo : 0
03-31 15:37:37.332 12250 12250 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-31 15:37:37.337  2901  2901 I art     : Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 419us total 17.473ms
03-31 15:37:37.342  3388  4008 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{313d48be u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3bcb52b7 12233:com.sec.pcw.device/1000}
03-31 15:37:37.342 10960 12177 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-31 15:37:37.342  3388  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-31 15:37:37.342  3388  3603 D UsbHostManager: displayNotification : [02h,02h,01h]
03-31 15:37:37.342  3388  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-31 15:37:37.342  3388  3603 D UsbHostManager: displayNotification : [0ah,00h,00h]
03-31 15:37:37.342  3388  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-31 15:37:37.342  3388  3603 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-31 15:37:37.342 10960 12177 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-31 15:37:37.347  3388  3855 I ActivityManager: Killing 10204:com.sec.android.automotive.drivelink/u0a102 (adj 15): emptyCount ##31
03-31 15:37:37.347  3388  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-31 15:37:37.347  3388  3603 D UsbHostManager: displayNotification : [0ah,00h,01h]

```
