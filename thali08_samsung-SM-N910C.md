#### Test 625481240f1d9b8_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,03-21 16:45:54.055  3390  3422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:45:54.055  3390  3422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:45:54.055  3390  3422 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
03-21 16:45:54.055  3390  3422 D BatteryService: stay LED for fully charged
03-21 16:45:54.055  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 16:45:54.060  3390  3390 I MotionRecognitionService: Plugged
03-21 16:45:54.060  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:45:54.060  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:45:54.060  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
03-21 16:45:54.070  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:45:54.070  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:45:54.070  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 16:45:54.080  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 16:45:54.085  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
03-21 16:45:54.095  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:45:54.095  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:45:54.095  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:45:54.095  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:45:54.365  3390  3619 V AlarmManager: waitForAlarm result :4
03-21 16:45:54.570 10956 10956 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 16:45:54.580 10956 10956 D AndroidRuntime: CheckJNI is OFF
03-21 16:45:54.580 10956 10956 D AndroidRuntime: readGMSProperty: start
03-21 16:45:54.580 10956 10956 D AndroidRuntime: readGMSProperty: already setted!!
03-21 16:45:54.580 10956 10956 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 16:45:54.580 10956 10956 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 16:45:54.580 10956 10956 D AndroidRuntime: readGMSProperty: end
03-21 16:45:54.580 10956 10956 D AndroidRuntime: addProductProperty: start
03-21 16:45:54.685 10956 10956 E AffinityControl: AffinityControl: registerfunction enter
03-21 16:45:54.705 10956 10956 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 16:45:54.715  3390  3981 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 16:45:54.720  3390  3981 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 16:45:54.745  3390  3981 W ActivityManager: mDVFSHelper.acquire()
03-21 16:45:54.750  3390  3981 D FocusedStackFrame: Set to : 0
03-21 16:45:54.750  3390  3981 V WindowManager: addAppToken: AppWindowToken{214b64f2 token=Token{3c29ffd ActivityRecord{34f30454 u0 com.test.thalitest/.MainActivity t41}}} to stack=1 task=41 at 0
03-21 16:45:54.755  3390  3981 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:45:54.755  3390  3981 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:45:54.755  3390  3981 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:45:54.755  3390  3981 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:45:54.760  3390  3581 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 16:45:54.760  3390  3581 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 16:45:54.760  3390  3581 D SecWifiDisplayUtil: Metadata value : none
03-21 16:45:54.765  3390  3581 V WindowManager: Adding window Window{2fad1b5 u0 d0 Starting com.test.thalitest} at 2 of 6 (after Window{2bfbf406 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher})
03-21 16:45:54.770 10976 10976 E Zygote  : MountEmulatedStorage()
03-21 16:45:54.770 10976 10976 E Zygote  : v2
03-21 16:45:54.770 10976 10976 I libpersona: KNOX_SDCARD checking this for 10011
03-21 16:45:54.770 10976 10976 I libpersona: KNOX_SDCARD not a persona
03-21 16:45:54.775 10976 10976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:45:54.775  3390  3981 I ActivityManager: Start proc 10976:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-21 16:45:54.775 10976 10976 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 16:45:54.775  3390  3981 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 16:45:54.775  3390  3981 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 16:45:54.775  3390  3981 D InputDispatcher: Focused application set to: xxxx
03-21 16:45:54.775  3390  3981 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-21 16:45:54.775 10976 10976 E Zygote  : accessInfo : 0
03-21 16:45:54.775  3390  3981 D InputDispatcher: Focus left window: 4014
03-21 16:45:54.780 10976 10976 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 16:45:54.780 10956 10956 D AndroidRuntime: Shutting down VM
03-21 16:45:54.780  3390  3581 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 16:45:54.780  3390  3581 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 16:45:54.785  2862  2862 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-21 16:45:54.800 10976 10976 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 16:45:54.805 10976 10976 D ActivityThread: Added TimaKeyStore provider
03-21 16:45:54.805  3390  6044 D SSRM:n  : SIOP:: AP = 270, PST = 284 (W:14), CUR = 38, LCD = 0
03-21 16:45:54.810  3390  4030 V WindowOrientationListener: setCurrentAppOrientation :-1
03-21 16:45:54.810  3390  4030 V WindowOrientationListener: setCurrentAppOrientation enable auto rotation
03-21 16:45:54.810  3390  4030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false
03-21 16:45:54.810  3390  4030 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 16:45:54.810  3390  4030 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 16:45:54.810  3390  4030 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 16:45:54.810  3390  4030 D PowerManagerService: setKeyboardVisibility: false
03-21 16:45:54.810  3390  4030 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 16:45:54.810  3390  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3390 uid:1000
03-21 16:45:54.810  3390  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 16:45:54.810  3390  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3390 uid:1000
03-21 16:45:54.810  3390  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 16:45:54.810  3390  3579 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2fad1b5 u0 d0 Starting com.test.thalitest}
03-21 16:45:54.830  3390  4030 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{34f30454 u0 com.test.thalitest/.MainActivity t41}
03-21 16:45:54.840  2862  4527 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
03-21 16:45:54.840  2862  3019 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
03-21 16:45:54.850  4014  4014 V ActivityThread: updateVisibility : ActivityRecord{3b93b61c token=android.os.BinderProxy@b3f8c7b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-21 16:45:54.850  4014  4014 D Launcher: onTrimMemory. Level: 20
,03-21 16:45:54.995  3390  6044 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 16:45:55.045 10976 10976 D SecWifiDisplayUtil: Metadata value : none
,03-21 16:45:55.090 10976 10976 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-21 16:45:55.100 10976 10976 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6077-6079)
03-21 16:45:55.100 10976 10976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 16:45:55.115 10976 10976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a47f10c}
,03-21 16:45:55.120 10976 10976 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 16:45:55.120 10976 10992 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
03-21 16:45:55.120 10976 10976 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 16:45:55.140 10976 10976 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 16:45:55.140 10976 10976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:45:55.140 10976 10976 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 16:45:55.165 10976 10976 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-21 16:45:55.165 10976 10976 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-21 16:45:55.165 10976 10976 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-21 16:45:55.240 10976 11015 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-21 16:45:55.275 10976 10976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:45:55.285 10976 10976 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 16:45:55.295 10976 10976 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-21 16:45:55.295 10976 10976 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-21 16:45:55.300 10976 10976 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-21 16:45:55.305 10976 10976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:45:55.305 10976 10976 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:45:55.360 10976 11028 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 16:45:55.365  3390  3832 V WindowManager: Adding window Window{18884452 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (before Window{2fad1b5 u0 d0 Starting com.test.thalitest}),
,03-21 16:45:55.370  3390  3980 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-21 16:45:55.370  3390  3980 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 16:45:55.370  3390  3980 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-21 16:45:55.375  3390  3390 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-21 16:45:55.375  3390  3390 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-21 16:45:55.375  3390  3390 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service,
,03-21 16:45:55.380  3390  3390 I EnterpriseSharedDevicePolicy: Get Result: -1
03-21 16:45:55.380  3390  3390 I EnterpriseSharedDevicePolicy: status: false,
03-21 16:45:55.380  3390  3390 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-21 16:45:55.390  3390  3390 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 16:45:55.395 10976 10976 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 16:45:55.395 10976 10976 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-21 16:45:55.400 10976 10976 D SecWifiDisplayUtil: Metadata value : none
,03-21 16:45:55.410  2862  2862 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,03-21 16:45:55.410  3390  4727 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 16:45:55.420  3390  4727 D InputDispatcher: Focus entered window: 10976
,03-21 16:45:55.425  3390  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3390 uid:1000
03-21 16:45:55.425  3390  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 16:45:55.425  3390  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3390 uid:1000
03-21 16:45:55.425  3390  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 16:45:55.425 10976 10976 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-21 16:45:55.430 10976 11028 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 16:45:55.430 10976 11028 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae47ce50 ,&mEglDisplay = 1 , &mEglConfig = -1267293936 
,03-21 16:45:55.430 10976 11028 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-21 16:45:55.430 10976 11028 D OpenGLRenderer: Enabling debug mode 0
,03-21 16:45:55.430 10976 11028 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-21 16:45:55.435 10976 10976 V ActivityThread: updateVisibility : ActivityRecord{11ef6fd4 token=android.os.BinderProxy@39adc7e6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-21 16:45:55.510  3390  3832 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 16:45:55.515  3726  3726 D PanelView: There is/are notification(s) 
03-21 16:45:55.515  3390  3581 I ActivityManager: Displayed Component not be shown by security: +544ms (total +1m28s873ms)
,03-21 16:45:55.515  3390  3581 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34f30454 u0 com.test.thalitest/.MainActivity t41} time:186494
03-21 16:45:55.515  3390  3581 W ActivityManager: mDVFSHelper.release()
03-21 16:45:55.520  2862  4023 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
03-21 16:45:55.520  2862  3023 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,03-21 16:45:55.550 10976 10976 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 16:45:55.550 10976 10976 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39adc7e6 time:186526
,03-21 16:45:55.575 10976 10976 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10976
,03-21 16:45:55.720 10976 10976 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 16:45:55.800 10976 11032 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626651136
,03-21 16:45:55.810 10976 11032 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 16:45:55.810 10976 11032 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 16:45:55.810 10976 11032 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 16:45:55.810 10976 11032 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 16:45:55.810 10976 11032 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 16:45:55.810 10976 11032 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a97a7ed added. We now have 1 listener(s)
,03-21 16:45:55.820 10976 11032 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-21 16:45:55.820 10976 11032 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 16:45:55.820 10976 11032 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 16:45:55.820 10976 11032 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 16:45:55.825 10976 10992 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
,03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 16:45:55.830 10976 11032 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1248ee70 added. We now have 1 listener(s)
03-21 16:45:55.830 10976 11032 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 16:45:55.835 10976 11032 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 16:45:55.840 10976 11032 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-21 16:45:55.840 10976 11032 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 16:45:55.840 10976 11032 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 16:45:55.840 10976 11032 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 16:45:55.845 10976 11032 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:45:55.845 10976 11032 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:45:55.855 10976 11032 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 16:45:55.855 10976 11032 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 16:45:55.855 10976 11032 D io.jxcore.node.ConnectivityMonitor: start: OK,
,03-21 16:45:55.860 10976 11032 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 16:45:55.860 10976 10976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 16:45:55.860 10976 10976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 16:45:55.890 10976 10976 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 16:45:56.290 10976 11040 W jxcore-log: Initializing JXcore engine
03-21 16:45:56.290 10976 11040 W jxcore-log: JXcore engine is ready
,03-21 16:45:56.330  4745  4745 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-21 16:45:56.330  4745  4745 E audit   : type=1400 msg=audit(1458575156.325:195): avc:  denied  { ioctl } for  pid=11040 comm="Thread-1520" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2199 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-21 16:45:56.330  3390  3577 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,03-21 16:45:56.330  4745  4745 E audit   :  SEPF_SM-N910C_5.1.1_0035
03-21 16:45:56.330  3390  3577 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-21 16:45:56.330  4745  4745 E audit   : type=1300 msg=audit(1458575156.325:195): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=95f008d8 items=0 ppid=2903 ppcomm=main pid=11040 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1520" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 16:45:56.330  4745  4745 E audit   : type=1320 msg=audit(1458575156.325:195): 
,03-21 16:45:56.330  3390  3577 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-21 16:45:56.330  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:45:56.330  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:45:56.330  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:45:56.330  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:45:56.335 10976 11040 W jxcore-log: Starting JXcore engine
,03-21 16:45:56.345 11041 11041 E Zygote  : MountEmulatedStorage()
03-21 16:45:56.345 11041 11041 E Zygote  : v2
03-21 16:45:56.345 11041 11041 I libpersona: KNOX_SDCARD checking this for 1000
03-21 16:45:56.345 11041 11041 I libpersona: KNOX_SDCARD not a persona
,03-21 16:45:56.345 11041 11041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 16:45:56.345 11041 11041 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:45:56.350 11041 11041 E Zygote  : accessInfo : 0
,03-21 16:45:56.350 11041 11041 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:45:56.350  3390  3576 I ActivityManager: Start proc 11041:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-21 16:45:56.370 11041 11041 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:45:56.370 11041 11041 D ActivityThread: Added TimaKeyStore provider
,03-21 16:45:56.380  3390  4007 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{14e73876 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{3aeb2e77 11041:com.samsung.android.securitylogagent/1000}
,03-21 16:45:56.390 10976 11040 W jxcore-log: Platform android
03-21 16:45:56.390 10976 11040 W jxcore-log: 
03-21 16:45:56.390 10976 11040 W jxcore-log: Process ARCH arm
03-21 16:45:56.390 10976 11040 W jxcore-log: 
,03-21 16:45:56.400 11041 11041 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-21 16:45:56.400 11041 11041 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-21 16:45:56.405  3390  3981 I ActivityManager: Killing 10075:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-21 16:45:56.490 10976 11040 I jxcore-log: JXcore Cordova bridge is ready!
03-21 16:45:56.490 10976 11040 I jxcore-log: 
03-21 16:45:56.490 10976 11040 W jxcore-log: JXcore engine is started
,03-21 16:45:56.495 10976 11032 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 16:45:56.495 10976 10976 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 16:45:57.765  3390  3692 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/41_task.xml.bak
,03-21 16:45:58.650  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:45:59.995  3390  3619 V AlarmManager: waitForAlarm result :8
,03-21 16:46:01.530  3390  3864 E Watchdog: !@Sync 6 [03-21 16:46:01.534]
,03-21 16:46:02.350 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:02.350 10976 11040 I jxcore-log: 
,03-21 16:46:02.350 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:02.350 10976 11040 I jxcore-log: 
,03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:02.355 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:02.355 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:02.360 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:02.360 10976 11040 I jxcore-log: 
,03-21 16:46:02.360 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:02.360 10976 11040 I jxcore-log: 
,03-21 16:46:02.685 10976 11040 I jxcore-log: Unit Test app is loaded
03-21 16:46:02.685 10976 11040 I jxcore-log: 
,03-21 16:46:02.690 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:02.690 10976 11040 I jxcore-log: 
,03-21 16:46:02.690 10976 10976 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 16:46:02.695 10976 11040 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-21 16:46:02.695 10976 11040 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-21 16:46:02.695 10976 11040 I jxcore-log: 
,03-21 16:46:02.695 10976 11040 I jxcore-log: My device name is: samsung-SM-N910C
03-21 16:46:02.695 10976 11040 I jxcore-log: 
,03-21 16:46:04.165  3390  3744 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 16:46:04.165  3390  3744 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:46:04.165  3390  3744 D BatteryService: online:4, current avg:-82, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-175
03-21 16:46:04.165  3390  3744 D BatteryService: stay LED for fully charged
03-21 16:46:04.165  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:46:04.165  3390  3390 I MotionRecognitionService: Plugged
,03-21 16:46:04.165  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:46:04.165  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:46:04.165  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:46:04.170  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:04.170  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:46:04.170  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:46:04.170  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 16:46:04.170  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:46:04.190  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:04.190  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:04.190  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:04.190  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:04.780  2896  4798 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 16:46:04.800  3390  3592 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-21 16:46:04.815  3390  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-21 16:46:04.980  3390  6044 D SSRM:n  : SIOP:: AP = 310, PST = 284 (W:10), CUR = -82, LCD = 0
,03-21 16:46:05.030 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 16:46:05.030 10976 11040 I jxcore-log: 
,03-21 16:46:05.240 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-21 16:46:05.240 10976 11040 I jxcore-log: 
,03-21 16:46:05.245 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-21 16:46:05.245 10976 11040 I jxcore-log: 
,03-21 16:46:05.250 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-21 16:46:05.250 10976 11040 I jxcore-log: 
,03-21 16:46:05.270 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-21 16:46:05.270 10976 11040 I jxcore-log: 
,03-21 16:46:05.280 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-21 16:46:05.280 10976 11040 I jxcore-log: 
,03-21 16:46:05.280 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-21 16:46:05.280 10976 11040 I jxcore-log: 
,03-21 16:46:06.505 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 16:46:06.505 10976 11040 I jxcore-log: 
,03-21 16:46:06.515 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-21 16:46:06.515 10976 11040 I jxcore-log: 
03-21 16:46:06.520 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-21 16:46:06.520 10976 11040 I jxcore-log: 
,03-21 16:46:06.595 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-21 16:46:06.595 10976 11040 I jxcore-log: 
,03-21 16:46:06.625 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-21 16:46:06.625 10976 11040 I jxcore-log: 
,03-21 16:46:06.705 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-21 16:46:06.705 10976 11040 I jxcore-log: 
,03-21 16:46:06.710 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-21 16:46:06.710 10976 11040 I jxcore-log: 
,03-21 16:46:06.715 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-21 16:46:06.715 10976 11040 I jxcore-log: 
,03-21 16:46:06.725 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-21 16:46:06.725 10976 11040 I jxcore-log: 
,03-21 16:46:06.735 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-21 16:46:06.735 10976 11040 I jxcore-log: 
,03-21 16:46:06.795 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-21 16:46:06.795 10976 11040 I jxcore-log: 
,03-21 16:46:06.800 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-21 16:46:06.800 10976 11040 I jxcore-log: 
,03-21 16:46:06.810 10976 11040 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-21 16:46:06.810 10976 11040 I jxcore-log: 
,03-21 16:46:07.920 10976 11040 I jxcore-log: TAP version 13
03-21 16:46:07.920 10976 11040 I jxcore-log: 
,03-21 16:46:07.920 10976 11040 I jxcore-log: # setup
03-21 16:46:07.920 10976 11040 I jxcore-log: 
,03-21 16:46:07.925 10976 11040 I jxcore-log: # 1. calling createNativeListener directly rejects
03-21 16:46:07.925 10976 11040 I jxcore-log: 
,03-21 16:46:08.075 10976 11040 I jxcore-log: # teardown
03-21 16:46:08.075 10976 11040 I jxcore-log: 
,03-21 16:46:08.190 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:08.190 10976 11040 I jxcore-log: 
,03-21 16:46:08.200 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 56255
03-21 16:46:08.200 10976 11040 I jxcore-log: 
,03-21 16:46:08.205 10976 11040 I jxcore-log: ok 1 Should throw
03-21 16:46:08.205 10976 11040 I jxcore-log: 
,03-21 16:46:08.210 10976 11040 I jxcore-log: # setup
03-21 16:46:08.210 10976 11040 I jxcore-log: 
,03-21 16:46:08.320 10976 11040 I jxcore-log: # 2. emits incomingConnectionState
03-21 16:46:08.320 10976 11040 I jxcore-log: 
,03-21 16:46:08.440 10976 11040 I jxcore-log: # teardown
03-21 16:46:08.440 10976 11040 I jxcore-log: 
,03-21 16:46:08.545 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:08.545 10976 11040 I jxcore-log: 
,03-21 16:46:08.550 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 56456
03-21 16:46:08.550 10976 11040 I jxcore-log: 
,03-21 16:46:08.565 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:08.565 10976 11040 I jxcore-log: 
,03-21 16:46:08.570 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:08.570 10976 11040 I jxcore-log: 
,03-21 16:46:08.585 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:08.585 10976 11040 I jxcore-log: 
,03-21 16:46:08.590 10976 11040 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-21 16:46:08.590 10976 11040 I jxcore-log: 
,03-21 16:46:08.615 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:08.615 10976 11040 I jxcore-log: 
,03-21 16:46:08.620 10976 11040 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-21 16:46:08.620 10976 11040 I jxcore-log: 
,03-21 16:46:08.630 10976 11040 I jxcore-log: # setup
03-21 16:46:08.630 10976 11040 I jxcore-log: 
,03-21 16:46:08.710 10976 11040 I jxcore-log: # 3. emits routerPortConnectionFailed
03-21 16:46:08.710 10976 11040 I jxcore-log: 
,03-21 16:46:08.810 10976 11040 I jxcore-log: # teardown
03-21 16:46:08.810 10976 11040 I jxcore-log: 
,03-21 16:46:08.900 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:08.900 10976 11040 I jxcore-log: 
,03-21 16:46:08.905 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 57876
03-21 16:46:08.905 10976 11040 I jxcore-log: 
,03-21 16:46:08.910 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:08.910 10976 11040 I jxcore-log: 
,03-21 16:46:08.910 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:08.910 10976 11040 I jxcore-log: 
,03-21 16:46:08.915 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:08.915 10976 11040 I jxcore-log: 
,03-21 16:46:08.945 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:08.945 10976 11040 I jxcore-log: 
,03-21 16:46:08.950 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:08.950 10976 11040 I jxcore-log: 
,03-21 16:46:08.955 10976 11040 I jxcore-log: DEBUG createNativeListener: 
03-21 16:46:08.955 10976 11040 I jxcore-log: 
,03-21 16:46:08.955 10976 11040 I jxcore-log: ok 4 tried to connect to right port
03-21 16:46:08.955 10976 11040 I jxcore-log: 
,03-21 16:46:08.955 10976 11040 I jxcore-log: ok 5 failed due to refused connection
03-21 16:46:08.955 10976 11040 I jxcore-log: 
,03-21 16:46:08.955 10976 11040 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-21 16:46:08.955 10976 11040 I jxcore-log: 
,03-21 16:46:08.965 10976 11040 I jxcore-log: # setup
03-21 16:46:08.965 10976 11040 I jxcore-log: 
,03-21 16:46:08.965 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:08.965 10976 11040 I jxcore-log: 
,03-21 16:46:09.140 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:09.140 10976 11040 I jxcore-log: 
,03-21 16:46:09.150 10976 11040 I jxcore-log: # 4. native server connections all up
03-21 16:46:09.150 10976 11040 I jxcore-log: 
,03-21 16:46:09.155 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:09.155 10976 11040 I jxcore-log: 
,03-21 16:46:09.240 10976 11040 I jxcore-log: # teardown
03-21 16:46:09.240 10976 11040 I jxcore-log: 
,03-21 16:46:09.370 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:09.370 10976 11040 I jxcore-log: 
,03-21 16:46:09.375 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 54072
03-21 16:46:09.375 10976 11040 I jxcore-log: 
,03-21 16:46:09.390 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:09.390 10976 11040 I jxcore-log: 
,03-21 16:46:09.395 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:09.395 10976 11040 I jxcore-log: 
,03-21 16:46:09.395 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:09.395 10976 11040 I jxcore-log: 
,03-21 16:46:09.435 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:09.435 10976 11040 I jxcore-log: 
,03-21 16:46:09.440 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:09.440 10976 11040 I jxcore-log: 
,03-21 16:46:09.445 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:09.445 10976 11040 I jxcore-log: 
,03-21 16:46:09.450 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:09.450 10976 11040 I jxcore-log: 
,03-21 16:46:09.480 10976 11040 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-21 16:46:09.480 10976 11040 I jxcore-log: 
,03-21 16:46:09.480 10976 11040 I jxcore-log: ok 8 Send/recvd #1 should be same
03-21 16:46:09.480 10976 11040 I jxcore-log: 
,03-21 16:46:09.485 10976 11040 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-21 16:46:09.485 10976 11040 I jxcore-log: 
,03-21 16:46:09.485 10976 11040 I jxcore-log: ok 10 Send/recvd #2 should be same
03-21 16:46:09.485 10976 11040 I jxcore-log: 
,03-21 16:46:09.490 10976 11040 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-21 16:46:09.490 10976 11040 I jxcore-log: 
,03-21 16:46:09.500 10976 11040 I jxcore-log: # setup
03-21 16:46:09.500 10976 11040 I jxcore-log: 
,03-21 16:46:09.595 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:09.595 10976 11040 I jxcore-log: 
,03-21 16:46:09.615 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:09.615 10976 11040 I jxcore-log: 
,03-21 16:46:09.620 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:09.620 10976 11040 I jxcore-log: 
,03-21 16:46:09.625 10976 11040 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-21 16:46:09.625 10976 11040 I jxcore-log: 
,03-21 16:46:09.630 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:09.630 10976 11040 I jxcore-log: 
,03-21 16:46:09.750 10976 11040 I jxcore-log: # teardown
03-21 16:46:09.750 10976 11040 I jxcore-log: 
,03-21 16:46:09.870 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:09.870 10976 11040 I jxcore-log: 
,03-21 16:46:09.875 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 44377
03-21 16:46:09.875 10976 11040 I jxcore-log: 
,03-21 16:46:09.885 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:09.885 10976 11040 I jxcore-log: 
,03-21 16:46:09.890 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:09.890 10976 11040 I jxcore-log: 
,03-21 16:46:09.895 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:09.895 10976 11040 I jxcore-log: 
,03-21 16:46:09.910 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:09.910 10976 11040 I jxcore-log: 
,03-21 16:46:09.915 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:09.915 10976 11040 I jxcore-log: 
,03-21 16:46:09.930 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:09.930 10976 11040 I jxcore-log: 
,03-21 16:46:09.950 10976 11040 I jxcore-log: ok 12 socket shouldn't close until after stream
03-21 16:46:09.950 10976 11040 I jxcore-log: 
,03-21 16:46:09.950 10976 11040 I jxcore-log: ok 13 incoming remains open
03-21 16:46:09.950 10976 11040 I jxcore-log: 
,03-21 16:46:09.960 10976 11040 I jxcore-log: # setup
03-21 16:46:09.960 10976 11040 I jxcore-log: 
,03-21 16:46:10.015 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:10.015 10976 11040 I jxcore-log: 
,03-21 16:46:10.020 10976 11040 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-21 16:46:10.020 10976 11040 I jxcore-log: 
,03-21 16:46:10.020 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:10.020 10976 11040 I jxcore-log: 
,03-21 16:46:10.200 10976 11040 I jxcore-log: # teardown
03-21 16:46:10.200 10976 11040 I jxcore-log: 
,03-21 16:46:10.335 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:10.335 10976 11040 I jxcore-log: 
,03-21 16:46:10.345 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 55421
03-21 16:46:10.345 10976 11040 I jxcore-log: 
,03-21 16:46:10.355 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:10.355 10976 11040 I jxcore-log: 
,03-21 16:46:10.355 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:10.355 10976 11040 I jxcore-log: 
,03-21 16:46:10.360 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:10.360 10976 11040 I jxcore-log: 
,03-21 16:46:10.375 10976 11040 I jxcore-log: ok 14 we should not have gotten an error
03-21 16:46:10.375 10976 11040 I jxcore-log: 
,03-21 16:46:10.380 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:10.380 10976 11040 I jxcore-log: 
,03-21 16:46:10.390 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:10.390 10976 11040 I jxcore-log: 
,03-21 16:46:10.400 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:10.400 10976 11040 I jxcore-log: 
,03-21 16:46:10.405 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:10.405 10976 11040 I jxcore-log: 
,03-21 16:46:10.420 10976 11040 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-21 16:46:10.420 10976 11040 I jxcore-log: 
,03-21 16:46:10.420 10976 11040 I jxcore-log: ok 16 incoming is cleaned up
03-21 16:46:10.420 10976 11040 I jxcore-log: 
,03-21 16:46:10.425 10976 11040 I jxcore-log: # setup
03-21 16:46:10.425 10976 11040 I jxcore-log: 
,03-21 16:46:10.500 10976 11040 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-21 16:46:10.500 10976 11040 I jxcore-log: 
,03-21 16:46:10.610 10976 11040 I jxcore-log: # teardown
03-21 16:46:10.610 10976 11040 I jxcore-log: 
,03-21 16:46:10.700 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:10.700 10976 11040 I jxcore-log: 
,03-21 16:46:10.710 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 40759
03-21 16:46:10.710 10976 11040 I jxcore-log: 
,03-21 16:46:10.720 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:10.720 10976 11040 I jxcore-log: 
,03-21 16:46:10.725 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:10.725 10976 11040 I jxcore-log: 
,03-21 16:46:10.730 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:10.730 10976 11040 I jxcore-log: 
,03-21 16:46:10.745 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:10.745 10976 11040 I jxcore-log: 
,03-21 16:46:10.750 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:10.750 10976 11040 I jxcore-log: 
,03-21 16:46:10.765 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:10.765 10976 11040 I jxcore-log: 
,03-21 16:46:10.780 10976 11040 I jxcore-log: ok 17 stream was closed
03-21 16:46:10.780 10976 11040 I jxcore-log: 
,03-21 16:46:10.780 10976 11040 I jxcore-log: ok 18 incoming should survive
03-21 16:46:10.780 10976 11040 I jxcore-log: 
,03-21 16:46:10.785 10976 11040 I jxcore-log: ok 19 mux should have no streams
03-21 16:46:10.785 10976 11040 I jxcore-log: 
,03-21 16:46:10.790 10976 11040 I jxcore-log: # setup
03-21 16:46:10.790 10976 11040 I jxcore-log: 
,03-21 16:46:10.895 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:10.895 10976 11040 I jxcore-log: 
,03-21 16:46:10.905 10976 11040 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-21 16:46:10.905 10976 11040 I jxcore-log: 
,03-21 16:46:10.910 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:10.910 10976 11040 I jxcore-log: 
,03-21 16:46:10.985 10976 11040 I jxcore-log: # teardown
03-21 16:46:10.985 10976 11040 I jxcore-log: 
,03-21 16:46:11.075 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:11.075 10976 11040 I jxcore-log: 
,03-21 16:46:11.080 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 56726
03-21 16:46:11.080 10976 11040 I jxcore-log: 
,03-21 16:46:11.085 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.085 10976 11040 I jxcore-log: 
,03-21 16:46:11.090 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.090 10976 11040 I jxcore-log: 
,03-21 16:46:11.090 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.090 10976 11040 I jxcore-log: 
,03-21 16:46:11.105 10976 11040 I jxcore-log: ok 20 we should not have gotten an error
03-21 16:46:11.105 10976 11040 I jxcore-log: 
,03-21 16:46:11.115 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.115 10976 11040 I jxcore-log: 
,03-21 16:46:11.115 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.115 10976 11040 I jxcore-log: 
,03-21 16:46:11.130 10976 11040 I jxcore-log: ok 21 Buffers are identical
03-21 16:46:11.130 10976 11040 I jxcore-log: 
,03-21 16:46:11.130 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:11.130 10976 11040 I jxcore-log: 
,03-21 16:46:11.135 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:11.135 10976 11040 I jxcore-log: 
,03-21 16:46:11.140 10976 11040 I jxcore-log: ok 22 native server is nulled out
03-21 16:46:11.140 10976 11040 I jxcore-log: 
,03-21 16:46:11.140 10976 11040 I jxcore-log: ok 23 native server should be closed
03-21 16:46:11.140 10976 11040 I jxcore-log: 
,03-21 16:46:11.145 10976 11040 I jxcore-log: ok 24 incoming has been removed
03-21 16:46:11.145 10976 11040 I jxcore-log: 
,03-21 16:46:11.145 10976 11040 I jxcore-log: ok 25 Incoming should be done
03-21 16:46:11.145 10976 11040 I jxcore-log: 
,03-21 16:46:11.145 10976 11040 I jxcore-log: ok 26 The mux object should be closed
03-21 16:46:11.145 10976 11040 I jxcore-log: 
,03-21 16:46:11.145 10976 11040 I jxcore-log: ok 27 The mux stream should be closed
03-21 16:46:11.145 10976 11040 I jxcore-log: 
,03-21 16:46:11.145 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:11.145 10976 11040 I jxcore-log: 
,03-21 16:46:11.165 10976 11040 I jxcore-log: # setup
03-21 16:46:11.165 10976 11040 I jxcore-log: 
,03-21 16:46:11.310 10976 11040 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-21 16:46:11.310 10976 11040 I jxcore-log: 
,03-21 16:46:11.435 10976 11040 I jxcore-log: # teardown
03-21 16:46:11.435 10976 11040 I jxcore-log: 
,03-21 16:46:11.550 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:11.550 10976 11040 I jxcore-log: 
,03-21 16:46:11.555 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 37775
03-21 16:46:11.555 10976 11040 I jxcore-log: 
,03-21 16:46:11.590 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.590 10976 11040 I jxcore-log: 
,03-21 16:46:11.590 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.590 10976 11040 I jxcore-log: 
,03-21 16:46:11.595 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.595 10976 11040 I jxcore-log: 
,03-21 16:46:11.600 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.600 10976 11040 I jxcore-log: 
,03-21 16:46:11.600 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.600 10976 11040 I jxcore-log: 
,03-21 16:46:11.605 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.605 10976 11040 I jxcore-log: 
,03-21 16:46:11.605 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.605 10976 11040 I jxcore-log: 
,03-21 16:46:11.610 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.610 10976 11040 I jxcore-log: 
,03-21 16:46:11.610 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.610 10976 11040 I jxcore-log: 
,03-21 16:46:11.615 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.615 10976 11040 I jxcore-log: 
,03-21 16:46:11.615 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.615 10976 11040 I jxcore-log: 
,03-21 16:46:11.615 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.615 10976 11040 I jxcore-log: 
,03-21 16:46:11.620 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.620 10976 11040 I jxcore-log: 
,03-21 16:46:11.620 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.620 10976 11040 I jxcore-log: 
,03-21 16:46:11.625 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.625 10976 11040 I jxcore-log: 
,03-21 16:46:11.625 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.625 10976 11040 I jxcore-log: 
,03-21 16:46:11.630 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.630 10976 11040 I jxcore-log: 
,03-21 16:46:11.630 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.630 10976 11040 I jxcore-log: 
,03-21 16:46:11.635 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.635 10976 11040 I jxcore-log: 
,03-21 16:46:11.635 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.635 10976 11040 I jxcore-log: 
,03-21 16:46:11.635 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.635 10976 11040 I jxcore-log: 
,03-21 16:46:11.640 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.640 10976 11040 I jxcore-log: 
,03-21 16:46:11.640 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.640 10976 11040 I jxcore-log: 
,03-21 16:46:11.640 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.640 10976 11040 I jxcore-log: 
,03-21 16:46:11.645 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.645 10976 11040 I jxcore-log: 
,03-21 16:46:11.645 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.645 10976 11040 I jxcore-log: 
,03-21 16:46:11.650 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.650 10976 11040 I jxcore-log: 
,03-21 16:46:11.650 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:11.650 10976 11040 I jxcore-log: 
,03-21 16:46:11.650 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:11.650 10976 11040 I jxcore-log: 
,03-21 16:46:11.655 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:11.655 10976 11040 I jxcore-log: 
,03-21 16:46:11.790 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.790 10976 11040 I jxcore-log: 
,03-21 16:46:11.795 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.795 10976 11040 I jxcore-log: 
,03-21 16:46:11.795 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.795 10976 11040 I jxcore-log: 
,03-21 16:46:11.800 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.800 10976 11040 I jxcore-log: 
,03-21 16:46:11.800 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.800 10976 11040 I jxcore-log: 
,03-21 16:46:11.800 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.800 10976 11040 I jxcore-log: 
,03-21 16:46:11.805 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.805 10976 11040 I jxcore-log: 
,03-21 16:46:11.805 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.805 10976 11040 I jxcore-log: 
,03-21 16:46:11.810 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.810 10976 11040 I jxcore-log: 
,03-21 16:46:11.810 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.810 10976 11040 I jxcore-log: 
,03-21 16:46:11.810 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.810 10976 11040 I jxcore-log: 
,03-21 16:46:11.815 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.815 10976 11040 I jxcore-log: 
,03-21 16:46:11.815 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.815 10976 11040 I jxcore-log: 
,03-21 16:46:11.815 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.815 10976 11040 I jxcore-log: 
,03-21 16:46:11.815 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.815 10976 11040 I jxcore-log: 
,03-21 16:46:11.820 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.820 10976 11040 I jxcore-log: 
,03-21 16:46:11.820 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.820 10976 11040 I jxcore-log: 
,03-21 16:46:11.825 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.825 10976 11040 I jxcore-log: 
,03-21 16:46:11.825 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.825 10976 11040 I jxcore-log: 
,03-21 16:46:11.825 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.825 10976 11040 I jxcore-log: 
,03-21 16:46:11.825 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.825 10976 11040 I jxcore-log: 
,03-21 16:46:11.830 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.830 10976 11040 I jxcore-log: 
,03-21 16:46:11.835 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.835 10976 11040 I jxcore-log: 
,03-21 16:46:11.835 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.835 10976 11040 I jxcore-log: 
,03-21 16:46:11.835 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.835 10976 11040 I jxcore-log: 
,03-21 16:46:11.840 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.840 10976 11040 I jxcore-log: 
,03-21 16:46:11.840 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.840 10976 11040 I jxcore-log: 
,03-21 16:46:11.845 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.845 10976 11040 I jxcore-log: 
,03-21 16:46:11.845 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.845 10976 11040 I jxcore-log: 
,03-21 16:46:11.845 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.845 10976 11040 I jxcore-log: 
,03-21 16:46:11.850 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.850 10976 11040 I jxcore-log: 
,03-21 16:46:11.850 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.850 10976 11040 I jxcore-log: 
,03-21 16:46:11.850 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.850 10976 11040 I jxcore-log: 
,03-21 16:46:11.855 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.855 10976 11040 I jxcore-log: 
,03-21 16:46:11.855 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.855 10976 11040 I jxcore-log: 
,03-21 16:46:11.855 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.855 10976 11040 I jxcore-log: 
,03-21 16:46:11.855 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.855 10976 11040 I jxcore-log: 
,03-21 16:46:11.860 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.860 10976 11040 I jxcore-log: 
,03-21 16:46:11.860 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.860 10976 11040 I jxcore-log: 
,03-21 16:46:11.860 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.860 10976 11040 I jxcore-log: 
,03-21 16:46:11.865 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.865 10976 11040 I jxcore-log: 
,03-21 16:46:11.865 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.865 10976 11040 I jxcore-log: 
,03-21 16:46:11.865 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.865 10976 11040 I jxcore-log: 
,03-21 16:46:11.865 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.865 10976 11040 I jxcore-log: 
,03-21 16:46:11.870 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.870 10976 11040 I jxcore-log: 
,03-21 16:46:11.870 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.870 10976 11040 I jxcore-log: 
,03-21 16:46:11.870 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.870 10976 11040 I jxcore-log: 
,03-21 16:46:11.870 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.870 10976 11040 I jxcore-log: 
,03-21 16:46:11.880 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.880 10976 11040 I jxcore-log: 
,03-21 16:46:11.885 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.885 10976 11040 I jxcore-log: 
,03-21 16:46:11.885 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.885 10976 11040 I jxcore-log: 
,03-21 16:46:11.885 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.885 10976 11040 I jxcore-log: 
,03-21 16:46:11.885 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.885 10976 11040 I jxcore-log: 
,03-21 16:46:11.890 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.890 10976 11040 I jxcore-log: 
,03-21 16:46:11.890 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.890 10976 11040 I jxcore-log: 
,03-21 16:46:11.890 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.890 10976 11040 I jxcore-log: 
,03-21 16:46:11.895 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.895 10976 11040 I jxcore-log: 
,03-21 16:46:11.895 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.895 10976 11040 I jxcore-log: 
,03-21 16:46:11.900 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.900 10976 11040 I jxcore-log: 
,03-21 16:46:11.900 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.900 10976 11040 I jxcore-log: 
,03-21 16:46:11.900 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-21 16:46:11.900 10976 11040 I jxcore-log: 
,03-21 16:46:11.900 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.900 10976 11040 I jxcore-log: 
,03-21 16:46:11.905 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.905 10976 11040 I jxcore-log: 
,03-21 16:46:11.905 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.905 10976 11040 I jxcore-log: 
,03-21 16:46:11.905 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.905 10976 11040 I jxcore-log: 
,03-21 16:46:11.910 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.910 10976 11040 I jxcore-log: 
03-21 16:46:11.910 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.910 10976 11040 I jxcore-log: 
,03-21 16:46:11.910 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.910 10976 11040 I jxcore-log: 
,03-21 16:46:11.910 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.910 10976 11040 I jxcore-log: 
,03-21 16:46:11.915 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.915 10976 11040 I jxcore-log: 
,03-21 16:46:11.915 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.915 10976 11040 I jxcore-log: 
,03-21 16:46:11.915 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.915 10976 11040 I jxcore-log: 
,03-21 16:46:11.915 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.915 10976 11040 I jxcore-log: 
,03-21 16:46:11.920 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.920 10976 11040 I jxcore-log: 
,03-21 16:46:11.920 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.920 10976 11040 I jxcore-log: 
,03-21 16:46:11.920 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.920 10976 11040 I jxcore-log: 
03-21 16:46:11.920 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.920 10976 11040 I jxcore-log: 
,03-21 16:46:11.925 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.925 10976 11040 I jxcore-log: 
,03-21 16:46:11.925 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:11.925 10976 11040 I jxcore-log: 
,03-21 16:46:11.930 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:11.930 10976 11040 I jxcore-log: 
,03-21 16:46:11.990 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:11.990 10976 11040 I jxcore-log: 
,03-21 16:46:11.995 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:11.995 10976 11040 I jxcore-log: 
,03-21 16:46:11.995 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:11.995 10976 11040 I jxcore-log: 
,03-21 16:46:11.995 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:11.995 10976 11040 I jxcore-log: 
,03-21 16:46:11.995 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:11.995 10976 11040 I jxcore-log: 
,03-21 16:46:11.995 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:11.995 10976 11040 I jxcore-log: 
03-21 16:46:11.995 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:11.995 10976 11040 I jxcore-log: 
,03-21 16:46:12.000 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.000 10976 11040 I jxcore-log: 
03-21 16:46:12.000 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.000 10976 11040 I jxcore-log: 
,03-21 16:46:12.000 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.000 10976 11040 I jxcore-log: 
,03-21 16:46:12.000 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.000 10976 11040 I jxcore-log: 
,03-21 16:46:12.000 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.000 10976 11040 I jxcore-log: 
,03-21 16:46:12.005 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.005 10976 11040 I jxcore-log: 
03-21 16:46:12.005 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.005 10976 11040 I jxcore-log: 
,03-21 16:46:12.005 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.005 10976 11040 I jxcore-log: 
,03-21 16:46:12.005 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.005 10976 11040 I jxcore-log: 
,03-21 16:46:12.005 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.005 10976 11040 I jxcore-log: 
,03-21 16:46:12.005 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.005 10976 11040 I jxcore-log: 
,03-21 16:46:12.005 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.005 10976 11040 I jxcore-log: 
03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
,03-21 16:46:12.010 10976 11040 I jxcore-log: 
03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.010 10976 11040 I jxcore-log: 
,03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.010 10976 11040 I jxcore-log: 
03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.010 10976 11040 I jxcore-log: 
,03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.010 10976 11040 I jxcore-log: 
,03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.010 10976 11040 I jxcore-log: 
,03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.010 10976 11040 I jxcore-log: 
,03-21 16:46:12.010 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.010 10976 11040 I jxcore-log: 
03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.015 10976 11040 I jxcore-log: 
,03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.015 10976 11040 I jxcore-log: 
,03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.015 10976 11040 I jxcore-log: 
,03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.015 10976 11040 I jxcore-log: 
03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.015 10976 11040 I jxcore-log: 
,03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.015 10976 11040 I jxcore-log: 
,03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.015 10976 11040 I jxcore-log: 
03-21 16:46:12.015 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.015 10976 11040 I jxcore-log: 
,03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
,03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
,03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
,03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.020 10976 11040 I jxcore-log: 
03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
,03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
,03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
03-21 16:46:12.020 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.020 10976 11040 I jxcore-log: 
,03-21 16:46:12.025 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.025 10976 11040 I jxcore-log: 
03-21 16:46:12.025 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.025 10976 11040 I jxcore-log: 
,03-21 16:46:12.025 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.025 10976 11040 I jxcore-log: 
,03-21 16:46:12.025 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.025 10976 11040 I jxcore-log: 
03-21 16:46:12.025 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.025 10976 11040 I jxcore-log: 
,03-21 16:46:12.025 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.025 10976 11040 I jxcore-log: 
,03-21 16:46:12.030 10976 11040 I jxcore-log: ok 28 native server is nulled out
03-21 16:46:12.030 10976 11040 I jxcore-log: 
,03-21 16:46:12.030 10976 11040 I jxcore-log: ok 29 native server should be closed
03-21 16:46:12.030 10976 11040 I jxcore-log: 
03-21 16:46:12.030 10976 11040 I jxcore-log: ok 30 incoming has been removed
03-21 16:46:12.030 10976 11040 I jxcore-log: 
,03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
,03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
,03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
,03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
03-21 16:46:12.030 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.030 10976 11040 I jxcore-log: 
,03-21 16:46:12.120 10976 11040 I jxcore-log: # setup
03-21 16:46:12.120 10976 11040 I jxcore-log: 
,03-21 16:46:12.185 10976 11040 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-21 16:46:12.185 10976 11040 I jxcore-log: 
,03-21 16:46:12.305 10976 11040 I jxcore-log: # teardown
03-21 16:46:12.305 10976 11040 I jxcore-log: 
,03-21 16:46:12.415 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:12.415 10976 11040 I jxcore-log: 
,03-21 16:46:12.425 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 33120
03-21 16:46:12.425 10976 11040 I jxcore-log: 
,03-21 16:46:12.435 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:12.435 10976 11040 I jxcore-log: 
,03-21 16:46:12.440 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:12.440 10976 11040 I jxcore-log: 
,03-21 16:46:12.445 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:12.445 10976 11040 I jxcore-log: 
,03-21 16:46:12.455 10976 11040 I jxcore-log: ok 31 we should not have gotten an error
03-21 16:46:12.455 10976 11040 I jxcore-log: 
,03-21 16:46:12.460 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:12.460 10976 11040 I jxcore-log: 
,03-21 16:46:12.460 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:12.460 10976 11040 I jxcore-log: 
,03-21 16:46:12.475 10976 11040 I jxcore-log: ok 32 Buffers are identical
03-21 16:46:12.475 10976 11040 I jxcore-log: 
,03-21 16:46:12.475 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.475 10976 11040 I jxcore-log: 
,03-21 16:46:12.480 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.480 10976 11040 I jxcore-log: 
,03-21 16:46:12.490 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.490 10976 11040 I jxcore-log: 
,03-21 16:46:12.495 10976 11040 I jxcore-log: ok 33 server should be fine
03-21 16:46:12.495 10976 11040 I jxcore-log: 
,03-21 16:46:12.495 10976 11040 I jxcore-log: ok 34 server should be open
03-21 16:46:12.495 10976 11040 I jxcore-log: 
,03-21 16:46:12.495 10976 11040 I jxcore-log: ok 35 incoming has been removed
03-21 16:46:12.495 10976 11040 I jxcore-log: 
,03-21 16:46:12.500 10976 11040 I jxcore-log: ok 36 The mux object should be closed
03-21 16:46:12.500 10976 11040 I jxcore-log: 
,03-21 16:46:12.500 10976 11040 I jxcore-log: ok 37 The mux stream should be closed
03-21 16:46:12.500 10976 11040 I jxcore-log: 
,03-21 16:46:12.510 10976 11040 I jxcore-log: # setup
03-21 16:46:12.510 10976 11040 I jxcore-log: 
,03-21 16:46:12.590 10976 11040 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-21 16:46:12.590 10976 11040 I jxcore-log: 
,03-21 16:46:12.690 10976 11040 I jxcore-log: # teardown
03-21 16:46:12.690 10976 11040 I jxcore-log: 
,03-21 16:46:12.790 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:12.790 10976 11040 I jxcore-log: 
,03-21 16:46:12.795 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 54630
03-21 16:46:12.795 10976 11040 I jxcore-log: 
,03-21 16:46:12.800 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:12.800 10976 11040 I jxcore-log: 
,03-21 16:46:12.800 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:12.800 10976 11040 I jxcore-log: 
03-21 16:46:12.805 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:12.805 10976 11040 I jxcore-log: 
,03-21 16:46:12.810 10976 11040 I jxcore-log: ok 38 we should not have gotten an error
03-21 16:46:12.810 10976 11040 I jxcore-log: 
,03-21 16:46:12.815 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:46:12.815 10976 11040 I jxcore-log: 
,03-21 16:46:12.820 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:46:12.820 10976 11040 I jxcore-log: 
,03-21 16:46:12.825 10976 11040 I jxcore-log: ok 39 Buffers are identical
03-21 16:46:12.825 10976 11040 I jxcore-log: 
,03-21 16:46:12.830 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-21 16:46:12.830 10976 11040 I jxcore-log: 
,03-21 16:46:12.830 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:46:12.830 10976 11040 I jxcore-log: 
,03-21 16:46:12.835 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:46:12.835 10976 11040 I jxcore-log: 
,03-21 16:46:12.840 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:12.840 10976 11040 I jxcore-log: 
,03-21 16:46:12.840 10976 11040 I jxcore-log: ok 40 server should be fine
03-21 16:46:12.840 10976 11040 I jxcore-log: 
,03-21 16:46:12.840 10976 11040 I jxcore-log: ok 41 server should be open
03-21 16:46:12.840 10976 11040 I jxcore-log: 
,03-21 16:46:12.845 10976 11040 I jxcore-log: ok 42 incoming has been removed
03-21 16:46:12.845 10976 11040 I jxcore-log: 
03-21 16:46:12.845 10976 11040 I jxcore-log: ok 43 The mux object should be closed
03-21 16:46:12.845 10976 11040 I jxcore-log: 
,03-21 16:46:12.845 10976 11040 I jxcore-log: ok 44 The mux stream should be closed
03-21 16:46:12.845 10976 11040 I jxcore-log: 
,03-21 16:46:12.850 10976 11040 I jxcore-log: # setup
03-21 16:46:12.850 10976 11040 I jxcore-log: 
,03-21 16:46:13.030 10976 11040 I jxcore-log: # 12. closeAll can close even when connections open
03-21 16:46:13.030 10976 11040 I jxcore-log: 
,03-21 16:46:13.190 10976 11040 I jxcore-log: # teardown
03-21 16:46:13.190 10976 11040 I jxcore-log: 
,03-21 16:46:13.350 10976 11040 I jxcore-log: ok 45 not possible to connect to the server anymore
03-21 16:46:13.350 10976 11040 I jxcore-log: 
,03-21 16:46:13.360 10976 11040 I jxcore-log: # setup
03-21 16:46:13.360 10976 11040 I jxcore-log: 
,03-21 16:46:13.450 10976 11040 I jxcore-log: # 13. closeAll with promise
03-21 16:46:13.450 10976 11040 I jxcore-log: 
,03-21 16:46:13.595 10976 11040 I jxcore-log: # teardown
03-21 16:46:13.595 10976 11040 I jxcore-log: 
,03-21 16:46:13.720 10976 11040 I jxcore-log: ok 46 not possible to connect to the server anymore
03-21 16:46:13.720 10976 11040 I jxcore-log: 
,03-21 16:46:13.725 10976 11040 I jxcore-log: # setup
03-21 16:46:13.725 10976 11040 I jxcore-log: 
,03-21 16:46:13.840 10976 11040 I jxcore-log: # 14. multiplex can send data
03-21 16:46:13.840 10976 11040 I jxcore-log: 
,03-21 16:46:13.975 10976 11040 I jxcore-log: # teardown
03-21 16:46:13.975 10976 11040 I jxcore-log: 
,03-21 16:46:14.205 10976 11040 I jxcore-log: ok 47 String should be length:200
03-21 16:46:14.205 10976 11040 I jxcore-log: 
,03-21 16:46:14.230 10976 11040 I jxcore-log: # setup
03-21 16:46:14.230 10976 11040 I jxcore-log: 
,03-21 16:46:14.275  3390  3422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 16:46:14.275  3390  3422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:46:14.275  3390  3422 D BatteryService: online:4, current avg:-31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
03-21 16:46:14.275  3390  3422 D BatteryService: stay LED for fully charged
03-21 16:46:14.275  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:46:14.275  3390  3390 I MotionRecognitionService: Plugged
03-21 16:46:14.275  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:46:14.275  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:46:14.275  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:46:14.280  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:14.280  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:14.280  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:46:14.285  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 16:46:14.285  5849  5950 D HeadsetStateMachine: Disconnected process message: 10,
,03-21 16:46:14.300  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:46:14.300  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:14.300  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:14.300  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:14.355 10976 11040 I jxcore-log: # 15. enqueue and run in order
03-21 16:46:14.355 10976 11040 I jxcore-log: 
,03-21 16:46:14.470  3390  3583 I PowerManagerService: [PWL] Off : 140s ago
,03-21 16:46:14.550 10976 11040 I jxcore-log: # teardown
03-21 16:46:14.550 10976 11040 I jxcore-log: 
,03-21 16:46:14.835 10976 11040 I jxcore-log: ok 48 firstPromise setTimeout
03-21 16:46:14.835 10976 11040 I jxcore-log: 
,03-21 16:46:14.845 10976 11040 I jxcore-log: ok 49 firstPromise result
03-21 16:46:14.845 10976 11040 I jxcore-log: 
,03-21 16:46:14.850 10976 11040 I jxcore-log: ok 50 firstPromise testValue
03-21 16:46:14.850 10976 11040 I jxcore-log: 
,03-21 16:46:14.965 10976 11040 I jxcore-log: ok 51 secondPromise setTimeout
03-21 16:46:14.965 10976 11040 I jxcore-log: 
,03-21 16:46:14.975 10976 11040 I jxcore-log: ok 52 secondPromise result
03-21 16:46:14.975 10976 11040 I jxcore-log: 
,03-21 16:46:14.985 10976 11040 I jxcore-log: ok 53 secondPromise testValue
03-21 16:46:14.985 10976 11040 I jxcore-log: 
,03-21 16:46:14.990 10976 11040 I jxcore-log: ok 54 thirdPromise in promise
03-21 16:46:14.990 10976 11040 I jxcore-log: 
,03-21 16:46:14.990 10976 11040 I jxcore-log: ok 55 thirdPromise result
03-21 16:46:14.990 10976 11040 I jxcore-log: 
,03-21 16:46:14.995 10976 11040 I jxcore-log: ok 56 thirdPromise testValue
03-21 16:46:14.995 10976 11040 I jxcore-log: 
,03-21 16:46:15.005  3390  6044 D SSRM:n  : SIOP:: AP = 300, PST = 283 (W:10), CUR = -31, LCD = 0
,03-21 16:46:15.015 10976 11040 I jxcore-log: # setup
03-21 16:46:15.015 10976 11040 I jxcore-log: 
,03-21 16:46:15.135 10976 11040 I jxcore-log: # 16. enqueueAtTop and run backwards
03-21 16:46:15.135 10976 11040 I jxcore-log: 
,03-21 16:46:15.420 10976 11040 I jxcore-log: # teardown
03-21 16:46:15.420 10976 11040 I jxcore-log: 
,03-21 16:46:15.585 10976 11040 I jxcore-log: ok 57 thirdPromise - first to run
03-21 16:46:15.585 10976 11040 I jxcore-log: 
,03-21 16:46:15.585 10976 11040 I jxcore-log: ok 58 thirdPromise - in resolve
03-21 16:46:15.585 10976 11040 I jxcore-log: 
,03-21 16:46:15.590 10976 11040 I jxcore-log: ok 59 secondPromise - second to run
03-21 16:46:15.590 10976 11040 I jxcore-log: 
,03-21 16:46:15.595 10976 11040 I jxcore-log: ok 60 secondPromise - in catch
03-21 16:46:15.595 10976 11040 I jxcore-log: 
,03-21 16:46:15.595 10976 11040 I jxcore-log: ok 61 firstPromise - third to run
03-21 16:46:15.595 10976 11040 I jxcore-log: 
,03-21 16:46:15.600 10976 11040 I jxcore-log: ok 62 firstPromise - in then
03-21 16:46:15.600 10976 11040 I jxcore-log: 
,03-21 16:46:15.600 10976 11040 I jxcore-log: ok 63 testing promises
03-21 16:46:15.600 10976 11040 I jxcore-log: 
,03-21 16:46:15.605 10976 11040 I jxcore-log: # setup
03-21 16:46:15.605 10976 11040 I jxcore-log: 
,03-21 16:46:15.740 10976 11040 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-21 16:46:15.740 10976 11040 I jxcore-log: 
,03-21 16:46:15.840 10976 11040 I jxcore-log: # teardown
03-21 16:46:15.840 10976 11040 I jxcore-log: 
,03-21 16:46:16.000 10976 11040 I jxcore-log: ok 64 fourth
03-21 16:46:16.000 10976 11040 I jxcore-log: 
,03-21 16:46:16.000 10976 11040 I jxcore-log: ok 65 fourth
03-21 16:46:16.000 10976 11040 I jxcore-log: 
,03-21 16:46:16.005 10976 11040 I jxcore-log: ok 66 second
03-21 16:46:16.005 10976 11040 I jxcore-log: 
,03-21 16:46:16.010 10976 11040 I jxcore-log: ok 67 secondPromise - in then
03-21 16:46:16.010 10976 11040 I jxcore-log: 
,03-21 16:46:16.120 10976 11040 I jxcore-log: ok 68 first
03-21 16:46:16.120 10976 11040 I jxcore-log: 
,03-21 16:46:16.125 10976 11040 I jxcore-log: ok 69 firstPromise - in catch
03-21 16:46:16.125 10976 11040 I jxcore-log: 
,03-21 16:46:16.130 10976 11040 I jxcore-log: ok 70 third
03-21 16:46:16.130 10976 11040 I jxcore-log: 
,03-21 16:46:16.130 10976 11040 I jxcore-log: ok 71 thirdPromise - in then
03-21 16:46:16.130 10976 11040 I jxcore-log: 
,03-21 16:46:16.135 10976 11040 I jxcore-log: ok 72 testingPromises
03-21 16:46:16.135 10976 11040 I jxcore-log: 
,03-21 16:46:16.145 10976 11040 I jxcore-log: # setup
03-21 16:46:16.145 10976 11040 I jxcore-log: 
,03-21 16:46:16.220 10976 11040 I jxcore-log: # 18. queues handled independently
03-21 16:46:16.220 10976 11040 I jxcore-log: 
,03-21 16:46:16.345 10976 11040 I jxcore-log: # teardown
03-21 16:46:16.345 10976 11040 I jxcore-log: 
,03-21 16:46:16.445 10976 11040 I jxcore-log: ok 73 all short operations completed before the long resolves
03-21 16:46:16.445 10976 11040 I jxcore-log: 
,03-21 16:46:16.450 10976 11040 I jxcore-log: # setup
03-21 16:46:16.450 10976 11040 I jxcore-log: 
,03-21 16:46:16.555 10976 11040 I jxcore-log: # 19. basic
03-21 16:46:16.555 10976 11040 I jxcore-log: 
,03-21 16:46:16.630 10976 11040 I jxcore-log: # teardown
03-21 16:46:16.630 10976 11040 I jxcore-log: 
,03-21 16:46:16.720 10976 11040 I jxcore-log: ok 74 sane
03-21 16:46:16.720 10976 11040 I jxcore-log: 
,03-21 16:46:16.730 10976 11040 I jxcore-log: # setup
03-21 16:46:16.730 10976 11040 I jxcore-log: 
,03-21 16:46:16.830 10976 11040 I jxcore-log: # 20. another
03-21 16:46:16.830 10976 11040 I jxcore-log: 
,03-21 16:46:16.920 10976 11040 I jxcore-log: # teardown
03-21 16:46:16.920 10976 11040 I jxcore-log: 
,03-21 16:46:17.010 10976 11040 I jxcore-log: ok 75 sane
03-21 16:46:17.010 10976 11040 I jxcore-log: 
,03-21 16:46:17.015 10976 11040 I jxcore-log: # setup
03-21 16:46:17.015 10976 11040 I jxcore-log: 
,03-21 16:46:17.105 10976 11040 I jxcore-log: # 21. #startListeningForAdvertisements should fail if start not called
03-21 16:46:17.105 10976 11040 I jxcore-log: 
,03-21 16:46:17.255 10976 11040 I jxcore-log: # teardown
03-21 16:46:17.255 10976 11040 I jxcore-log: 
,03-21 16:46:17.340 10976 11040 I jxcore-log: ok 76 specific error should be returned
03-21 16:46:17.340 10976 11040 I jxcore-log: 
,03-21 16:46:17.340 10976 11040 I jxcore-log: # setup
03-21 16:46:17.340 10976 11040 I jxcore-log: 
,03-21 16:46:17.505 10976 11040 I jxcore-log: ok 77 error should be null
03-21 16:46:17.505 10976 11040 I jxcore-log: 
,03-21 16:46:17.510 10976 11040 I jxcore-log: ok 78 error should be null
03-21 16:46:17.510 10976 11040 I jxcore-log: 
,03-21 16:46:17.515 10976 11040 I jxcore-log: # 22. #startUpdateAdvertisingAndListening should fail if start not called
03-21 16:46:17.515 10976 11040 I jxcore-log: 
,03-21 16:46:17.880 10976 11040 I jxcore-log: # teardown
03-21 16:46:17.880 10976 11040 I jxcore-log: 
,03-21 16:46:18.655  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:46:20.560 10976 11040 I jxcore-log: ok 79 specific error should be returned
03-21 16:46:20.560 10976 11040 I jxcore-log: 
,03-21 16:46:20.565 10976 11040 I jxcore-log: # setup
03-21 16:46:20.565 10976 11040 I jxcore-log: 
,03-21 16:46:20.710 10976 11040 I jxcore-log: ok 80 error should be null
03-21 16:46:20.710 10976 11040 I jxcore-log: 
,03-21 16:46:20.710 10976 11040 I jxcore-log: ok 81 error should be null
03-21 16:46:20.710 10976 11040 I jxcore-log: 
,03-21 16:46:20.720 10976 11040 I jxcore-log: # 23. should be able to call #stopListeningForAdvertisements many times
03-21 16:46:20.720 10976 11040 I jxcore-log: 
,03-21 16:46:21.045 10976 11040 I jxcore-log: # teardown
03-21 16:46:21.045 10976 11040 I jxcore-log: 
,03-21 16:46:21.220 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:21.220 10976 11040 I jxcore-log: 
,03-21 16:46:21.220 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 42802
03-21 16:46:21.220 10976 11040 I jxcore-log: 
,03-21 16:46:21.230 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:21.230 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:21.230 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:21.235 10976 11040 I jxcore-log: ok 82 error should be null
03-21 16:46:21.235 10976 11040 I jxcore-log: 
,03-21 16:46:21.235 10976 11040 I jxcore-log: ok 83 error should be null
03-21 16:46:21.235 10976 11040 I jxcore-log: 
,03-21 16:46:21.240 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:21.240 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:21.240 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:21.240 10976 11040 I jxcore-log: ok 84 error should be null
03-21 16:46:21.240 10976 11040 I jxcore-log: 
,03-21 16:46:21.245 10976 11040 I jxcore-log: ok 85 error should be null
03-21 16:46:21.245 10976 11040 I jxcore-log: 
,03-21 16:46:21.250 10976 11040 I jxcore-log: # setup
03-21 16:46:21.250 10976 11040 I jxcore-log: 
,03-21 16:46:21.415 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:21.415 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:21.420 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:21.425 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:21.425 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:21.430 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:21.440 10976 11040 I jxcore-log: ok 86 error should be null
03-21 16:46:21.440 10976 11040 I jxcore-log: 
03-21 16:46:21.440 10976 11040 I jxcore-log: ok 87 error should be null
03-21 16:46:21.440 10976 11040 I jxcore-log: 
,03-21 16:46:21.445 10976 11040 I jxcore-log: # 24. should be able to call #startListeningForAdvertisements many times
03-21 16:46:21.445 10976 11040 I jxcore-log: 
,03-21 16:46:21.645 10976 11040 I jxcore-log: # teardown
03-21 16:46:21.645 10976 11040 I jxcore-log: 
,03-21 16:46:21.895 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server,
03-21 16:46:21.895 10976 11040 I jxcore-log: 
,03-21 16:46:21.905 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 37712
03-21 16:46:21.905 10976 11040 I jxcore-log: 
,03-21 16:46:21.915 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-21 16:46:21.915 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:21.915 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 16:46:21.915 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-21 16:46:21.915 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:46:21.915 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:46:21.925 10976 11040 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:21.935 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:21.940 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 16:46:21.945 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:21.945 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:21.945 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:21.955  5849  5857 D BtGatt.GattService: registerClient() - UUID=d47d1c7a-13fb-4b73-b3ef-543b1373caae
,03-21 16:46:22.000  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=d47d1c7a-13fb-4b73-b3ef-543b1373caae, clientIf=6
,03-21 16:46:22.000 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:22.000  5849  5861 D BtGatt.GattService: start scan with filters
,03-21 16:46:22.020  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 44
,03-21 16:46:22.025 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:22.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:22.025  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:22.025  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:22.025 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:22.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:22.025  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:22.025 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:22.025 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 16:46:22.025 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:22.025  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:22.025  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:22.030  5849  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a47f10c
,03-21 16:46:22.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:22.030 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 16:46:22.030 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:22.030 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:22.030 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:22.030 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:22.040  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 16:46:22.040  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:22.040  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:22.040  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 16:46:22.040  5849  5949 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6,
03-21 16:46:22.040 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:22.040 10976 11040 I jxcore-log: 
,03-21 16:46:22.045  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-21 16:46:22.045  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:22.045  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 16:46:22.045  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:22.045 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:22.045 10976 11040 I jxcore-log: 
,03-21 16:46:22.045  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 16:46:22.045  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:22.050 10976 11040 I jxcore-log: ok 88 error should be null
03-21 16:46:22.050 10976 11040 I jxcore-log: 
,03-21 16:46:22.050  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:22.050  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:22.050 10976 11040 I jxcore-log: ok 89 error should be null
03-21 16:46:22.050 10976 11040 I jxcore-log: 
,03-21 16:46:22.055 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-21 16:46:22.055 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:22.055 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:22.055 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:22.055 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:22.060 10976 11040 I jxcore-log: ok 90 error should be null
03-21 16:46:22.060 10976 11040 I jxcore-log: 
,03-21 16:46:22.060 10976 11040 I jxcore-log: ok 91 error should be null
03-21 16:46:22.060 10976 11040 I jxcore-log: 
,03-21 16:46:22.070 10976 11040 I jxcore-log: # setup
03-21 16:46:22.070 10976 11040 I jxcore-log: 
,03-21 16:46:22.220 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:22.225 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:22.225 10976 11040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 16:46:22.225 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 16:46:22.225 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 16:46:22.230 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-21 16:46:22.230 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 16:46:22.230 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 16:46:22.230 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:22.235  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
03-21 16:46:22.235  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:22.235  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 3
03-21 16:46:22.235  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:22.235  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:22.240  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:22.240  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:22.240  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:22.240  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:22.240  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:22.245  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:22.245  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:22.245 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 16:46:22.250 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 16:46:22.250 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 16:46:22.250 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-21 16:46:22.250 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 16:46:22.250 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 16:46:22.250 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 16:46:22.250 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-21 16:46:22.250 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 16:46:22.255 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-21 16:46:22.255 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:22.255 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-21 16:46:22.255 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:22.255 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-21 16:46:22.260 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:22.270 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-21 16:46:22.275 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-21 16:46:22.275 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:22.280 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-21 16:46:22.280 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:22.280 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:22.280 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:22.285 10976 11040 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 16:46:22.285 10976 11040 I jxcore-log: 
,03-21 16:46:22.285 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:22.285 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:22.285 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:22.290 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:22.290 10976 11040 I jxcore-log: 
,03-21 16:46:22.290 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:22.290 10976 11040 I jxcore-log: 
,03-21 16:46:22.295 10976 11040 I jxcore-log: ok 92 error should be null
03-21 16:46:22.295 10976 11040 I jxcore-log: 
,03-21 16:46:22.300 10976 11040 I jxcore-log: ok 93 error should be null
03-21 16:46:22.300 10976 11040 I jxcore-log: 
,03-21 16:46:22.310 10976 11040 I jxcore-log: # 25. should be able to call #startUpdateAdvertisingAndListening many times
03-21 16:46:22.310 10976 11040 I jxcore-log: 
,03-21 16:46:22.885 10976 11040 I jxcore-log: # teardown
03-21 16:46:22.885 10976 11040 I jxcore-log: 
,03-21 16:46:23.760 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:23.760 10976 11040 I jxcore-log: 
,03-21 16:46:23.765 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 40611
03-21 16:46:23.765 10976 11040 I jxcore-log: 
,03-21 16:46:23.780 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 40611, start advertisements: true
,03-21 16:46:23.780 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:23.780 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:23.780 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:23.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:46:23.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:23.785 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:23.785 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:23.790  5849  5861 D BtGatt.GattService: registerClient() - UUID=f2e44a39-fac6-46d3-a6de-aba9946073c1
,03-21 16:46:23.835  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=f2e44a39-fac6-46d3-a6de-aba9946073c1, clientIf=6
03-21 16:46:23.835 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:23.835  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:46:23.865  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 45
,03-21 16:46:23.865  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:23.865  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:23.865  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:23.875  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:23.875  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:23.875  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:23.875  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:23.875  5849  5949 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-21 16:46:23.875  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:23.875  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:23.880  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 16:46:23.880  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:23.880  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:23.880  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:23.885  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:23.885  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:23.890 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 16:46:23.890 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 16:46:23.890 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:23.890 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:23.890 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:23.890 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:23.890 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:23.890 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 16:46:23.890 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:23.890 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-21 16:46:23.890 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-21 16:46:23.890 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:23.900  5849  5861 D BtGatt.GattService: registerClient() - UUID=9dacd2ae-b7ef-496c-9905-3465a1a17e86,
,03-21 16:46:23.940  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=9dacd2ae-b7ef-496c-9905-3465a1a17e86, clientIf=7,
,03-21 16:46:23.940 10976 10988 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-21 16:46:23.980  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 36
,03-21 16:46:23.985  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:23.985  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:23.985  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:23.990  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:23.990  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:23.995  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:24.000  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:24.000  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:24.000  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 16:46:24.005  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 16:46:24.005 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:24.005 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:46:24.005 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:24.005 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:24.005 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-21 16:46:24.010 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:46:24.010 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-21 16:46:24.010 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-21 16:46:24.015 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 16:46:24.015 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-21 16:46:24.015 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:24.015 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:24.015 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:24.015 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:24.015 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:46:24.015 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:46:24.015 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:24.015 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:24.015 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:24.015 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:24.015 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 16:46:24.015 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 16:46:24.015 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:24.030 10976 11272 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:24.035 10976 11272 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 16:46:24.040 10976 11272 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
03-21 16:46:24.040 10976 11272 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:24.040 10976 11272 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:46:24.040 10976 11272 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c67d20f
03-21 16:46:24.040 10976 11272 D BluetoothSocket: channel: 6
03-21 16:46:24.040 10976 11272 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 16:46:24.045 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:24.045 10976 11040 I jxcore-log: 
03-21 16:46:24.045 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:24.045 10976 11040 I jxcore-log: 
03-21 16:46:24.050 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:24.050 10976 11040 I jxcore-log: 
03-21 16:46:24.050 10976 11040 I jxcore-log: ok 94 error should be null
03-21 16:46:24.050 10976 11040 I jxcore-log: 
03-21 16:46:24.050 10976 11040 I jxcore-log: ok 95 error should be null
03-21 16:46:24.050 10976 11040 I jxcore-log: 
,03-21 16:46:24.060 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 40611, start advertisements: true
,03-21 16:46:24.060 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:24.060 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:24.060 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:24.060 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:24.070 10976 11040 I jxcore-log: ok 96 error should be null
03-21 16:46:24.070 10976 11040 I jxcore-log: 
,03-21 16:46:24.070 10976 11040 I jxcore-log: ok 97 error should be null
03-21 16:46:24.070 10976 11040 I jxcore-log: 
,03-21 16:46:24.075 10976 11040 I jxcore-log: # setup
03-21 16:46:24.075 10976 11040 I jxcore-log: 
,03-21 16:46:24.190 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:24.190 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 16:46:24.190 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:24.190 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 16:46:24.190 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 16:46:24.195 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20cf329c, channel: 6, state: LISTENING
,03-21 16:46:24.195 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20cf329c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c67d20f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a4c44a5mSocket: android.net.LocalSocket@2c01b07a impl:android.net.LocalSocketImpl@38d9802b fd:FileDescriptor[117]
03-21 16:46:24.195 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c01b07a impl:android.net.LocalSocketImpl@38d9802b fd:FileDescriptor[117]
03-21 16:46:24.195 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:24.195 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 16:46:24.195 10976 11272 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 16:46:24.195 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:24.195 10976 11272 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:24.195 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:24.195 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:24.195 10976 11272 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-21 16:46:24.195 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:46:24.195 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 16:46:24.200  5849  6155 D BtGatt.GattService: stopScan() - queue size =1
03-21 16:46:24.200  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:24.200  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 4
03-21 16:46:24.200  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:24.200 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:24.205 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:24.205 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:24.205 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:46:24.205  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:24.205 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:46:24.205  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:24.205 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:24.205  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:24.205 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 16:46:24.205  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:46:24.205  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:24.205  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:24.205  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:24.205  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:24.205  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:24.210  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:46:24.210  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:24.210  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:24.210  5849  5920 D BtGatt.GattService: current time is 215187158149
03-21 16:46:24.210  5849  5920 D BtGatt.GattService: Batch record : [44, 94, 57, -57, -79, 126, 1, -128, -84, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:24.215  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:24.215  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:24.215  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:46:24.215  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:24.215  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:46:24.215 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:24.215 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:24.215 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:46:24.215 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 16:46:24.215 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:24.215 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:24.215 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:24.215 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:46:24.220 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:24.220 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:24.220 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:24.220 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:24.220 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 16:46:24.225 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 16:46:24.225 10976 11040 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 16:46:24.225 10976 11040 I jxcore-log: 
03-21 16:46:24.230 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:46:24.230 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:24.230 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:24.235 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 16:46:24.235 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:46:24.235 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:24.235 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:24.235 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:24.235 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:24.235 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:24.235 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 16:46:24.235 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:24.235 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:24.235 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:24.235 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:46:24.235 10976 11040 I jxcore-log: 
03-21 16:46:24.240 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:24.240 10976 11040 I jxcore-log: 
03-21 16:46:24.240 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:24.240 10976 11040 I jxcore-log: 
03-21 16:46:24.245 10976 11040 I jxcore-log: ok 98 error should be null
03-21 16:46:24.245 10976 11040 I jxcore-log: 
03-21 16:46:24.245 10976 11040 I jxcore-log: ok 99 error should be null
03-21 16:46:24.245 10976 11040 I jxcore-log: 
03-21 16:46:24.250 10976 11040 I jxcore-log: # 26. should be able to call #stopAdvertisingAndListening many times
03-21 16:46:24.250 10976 11040 I jxcore-log: 
,03-21 16:46:24.405  3390  4657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:46:24.405  3390  4657 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:46:24.405  3390  4657 D BatteryService: online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
03-21 16:46:24.405  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 16:46:24.410  3390  4657 D BatteryService: stay LED for fully charged
03-21 16:46:24.410  3390  3390 I MotionRecognitionService: Plugged
03-21 16:46:24.410  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:46:24.410  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:46:24.410  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
03-21 16:46:24.420  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:24.420  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:24.420  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:46:24.445  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:46:24.445  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:46:24.450  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:24.450  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:24.450  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:24.450  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:24.455 10976 11040 I jxcore-log: # teardown
03-21 16:46:24.455 10976 11040 I jxcore-log: 
,03-21 16:46:24.780 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:24.780 10976 11040 I jxcore-log: 
,03-21 16:46:24.790 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 37988
03-21 16:46:24.790 10976 11040 I jxcore-log: 
,03-21 16:46:24.795 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:24.795 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:24.795 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:24.800 10976 11040 I jxcore-log: ok 100 error should be null
03-21 16:46:24.800 10976 11040 I jxcore-log: 
,03-21 16:46:24.800 10976 11040 I jxcore-log: ok 101 error should be null
03-21 16:46:24.800 10976 11040 I jxcore-log: 
,03-21 16:46:24.805 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:24.805 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:24.805 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:24.810 10976 11040 I jxcore-log: ok 102 error should be null
03-21 16:46:24.810 10976 11040 I jxcore-log: 
,03-21 16:46:24.815 10976 11040 I jxcore-log: ok 103 error should be null
03-21 16:46:24.815 10976 11040 I jxcore-log: 
,03-21 16:46:24.820 10976 11040 I jxcore-log: # setup
03-21 16:46:24.820 10976 11040 I jxcore-log: 
,03-21 16:46:24.965 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:24.965 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:24.965 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:24.970 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:24.970 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:24.975 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:24.980 10976 11040 I jxcore-log: ok 104 error should be null
03-21 16:46:24.980 10976 11040 I jxcore-log: 
,03-21 16:46:24.985 10976 11040 I jxcore-log: ok 105 error should be null
03-21 16:46:24.985 10976 11040 I jxcore-log: 
,03-21 16:46:24.990 10976 11040 I jxcore-log: # 27. #start should fail if called twice in a row
03-21 16:46:24.990 10976 11040 I jxcore-log: 
,03-21 16:46:25.015  3390  6044 D SSRM:n  : SIOP:: AP = 290, PST = 284 (W:10), CUR = 18, LCD = 0
,03-21 16:46:25.085 10976 11040 I jxcore-log: # teardown
03-21 16:46:25.085 10976 11040 I jxcore-log: 
,03-21 16:46:25.260 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:25.260 10976 11040 I jxcore-log: 
,03-21 16:46:25.265 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 40261
03-21 16:46:25.265 10976 11040 I jxcore-log: 
,03-21 16:46:25.270 10976 11040 I jxcore-log: ok 106 first call should succeed
03-21 16:46:25.270 10976 11040 I jxcore-log: 
,03-21 16:46:25.275 10976 11040 I jxcore-log: ok 107 first call should succeed
03-21 16:46:25.275 10976 11040 I jxcore-log: 
,03-21 16:46:25.275 10976 11040 I jxcore-log: ok 108 specific error should be returned
03-21 16:46:25.275 10976 11040 I jxcore-log: 
,03-21 16:46:25.280 10976 11040 I jxcore-log: # setup
03-21 16:46:25.280 10976 11040 I jxcore-log: 
,03-21 16:46:25.485 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:25.485 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:25.485 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:25.490 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:25.495 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:25.495 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:25.505 10976 11040 I jxcore-log: ok 109 error should be null
03-21 16:46:25.505 10976 11040 I jxcore-log: 
,03-21 16:46:25.505 10976 11040 I jxcore-log: ok 110 error should be null
03-21 16:46:25.505 10976 11040 I jxcore-log: 
,03-21 16:46:25.515 10976 11040 I jxcore-log: # 28. does not emit duplicate discoveryAdvertisingStateUpdate
03-21 16:46:25.515 10976 11040 I jxcore-log: 
,03-21 16:46:25.740 10976 11040 I jxcore-log: # teardown
03-21 16:46:25.740 10976 11040 I jxcore-log: 
,03-21 16:46:26.070 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:26.070 10976 11040 I jxcore-log: 
,03-21 16:46:26.075 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 35225
03-21 16:46:26.075 10976 11040 I jxcore-log: 
,03-21 16:46:26.085 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 40611, start advertisements: false
,03-21 16:46:26.085 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:26.085 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:26.085 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 16:46:26.090 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:26.090 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:26.090 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:26.095  5849  5861 D BtGatt.GattService: registerClient() - UUID=67aed51c-4470-4532-b89e-da933a6980b7
,03-21 16:46:26.135  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=67aed51c-4470-4532-b89e-da933a6980b7, clientIf=6
,03-21 16:46:26.135 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:26.135  5849  6155 D BtGatt.GattService: start scan with filters
,03-21 16:46:26.150  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 46
,03-21 16:46:26.150 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:26.150 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:26.150 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:26.150 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:26.150 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:26.150 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:46:26.150  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:26.150  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:26.150  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:26.150 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:26.150 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-21 16:46:26.155 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:26.155 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:26.155 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:26.155 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:26.155 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:26.155  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:26.155  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:26.155  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:26.155  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 16:46:26.155  5849  5949 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-21 16:46:26.155  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:26.155  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:26.155  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 16:46:26.155  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:26.160  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 16:46:26.160  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:26.160  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:26.160  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:26.160 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:26.160 10976 11040 I jxcore-log: 
,03-21 16:46:26.165 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:26.165 10976 11040 I jxcore-log: 
,03-21 16:46:26.175 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 35225, start advertisements: true
,03-21 16:46:26.175 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:26.175 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:26.175 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:26.175 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:46:26.175 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-21 16:46:26.175 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:26.175 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 16:46:26.175 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:26.175 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:26.180 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:26.180 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:46:26.180  5849  5861 D BtGatt.GattService: registerClient() - UUID=0b7b0823-00af-4fea-bcf0-4387f8eb9977
,03-21 16:46:26.220  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=0b7b0823-00af-4fea-bcf0-4387f8eb9977, clientIf=7
03-21 16:46:26.225 10976 10986 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:26.240  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 37
,03-21 16:46:26.240  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:26.240  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:26.240  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:26.240  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:26.245  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:26.245  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:26.245  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:26.250  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:26.250  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:26.250  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:46:26.250 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-21 16:46:26.250 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:26.250 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:46:26.250 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:26.250 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:26.250 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:46:26.250 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 16:46:26.255 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:26.255 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 16:46:26.255 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:46:26.255 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:26.255 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:26.255 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 16:46:26.255 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:26.255 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 16:46:26.255 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 16:46:26.255 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:26.255 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 16:46:26.255 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:26.255 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 16:46:26.260 10976 11320 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 16:46:26.260 10976 11320 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:26.265 10976 11320 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,03-21 16:46:26.265 10976 11320 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:26.265 10976 11320 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:46:26.265 10976 11320 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e6df407
03-21 16:46:26.265 10976 11320 D BluetoothSocket: channel: 6
,03-21 16:46:26.265 10976 11320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:46:26.275 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:26.275 10976 11040 I jxcore-log: 
,03-21 16:46:26.285 10976 11040 I jxcore-log: ok 111 called only once
03-21 16:46:26.285 10976 11040 I jxcore-log: 
,03-21 16:46:26.285 10976 11040 I jxcore-log: ok 112 discovery state matches
03-21 16:46:26.285 10976 11040 I jxcore-log: 
,03-21 16:46:26.285 10976 11040 I jxcore-log: ok 113 advertising state matches
03-21 16:46:26.285 10976 11040 I jxcore-log: 
,03-21 16:46:26.295 10976 11040 I jxcore-log: # setup
03-21 16:46:26.295 10976 11040 I jxcore-log: 
,03-21 16:46:26.810 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:26.815 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-21 16:46:26.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 16:46:26.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 16:46:26.815 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 16:46:26.815 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19953934, channel: 6, state: LISTENING
,03-21 16:46:26.815 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19953934, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e6df407, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e2f635dmSocket: android.net.LocalSocket@3161d4d2 impl:android.net.LocalSocketImpl@1ebc9a3 fd:FileDescriptor[115]
,03-21 16:46:26.815 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3161d4d2 impl:android.net.LocalSocketImpl@1ebc9a3 fd:FileDescriptor[115]
,03-21 16:46:26.820 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 16:46:26.820 10976 11320 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-21 16:46:26.820 10976 11320 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
03-21 16:46:26.820 10976 11320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-21 16:46:26.820 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 16:46:26.825 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 16:46:26.825 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:46:26.825 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-21 16:46:26.825 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:26.825 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-21 16:46:26.825 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,03-21 16:46:26.825 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-21 16:46:26.825 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-21 16:46:26.830  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:26.830  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:26.835  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 5,
03-21 16:46:26.835  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-21 16:46:26.835  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 16:46:26.835  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:26.835  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:26.835  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:26.835  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:26.835  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:26.840 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:26.840 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:26.840 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:26.840 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:46:26.840 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:46:26.840 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:26.840  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:26.840  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:26.840  5849  5920 D BtGatt.GattService: current time is 217819225900
03-21 16:46:26.840  5849  5920 D BtGatt.GattService: Batch record : [-75, 110, 82, -13, -1, 124, 1, -128, -82, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:26.840  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:26.840  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:26.845 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 16:46:26.850  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:46:26.850  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:26.850  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:26.850  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:46:26.850  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:46:26.850  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:26.850  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:46:26.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:26.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:26.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:46:26.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 16:46:26.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:26.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:26.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:26.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:46:26.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:26.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:26.860 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:26.860 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:26.860 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:26.860 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:26.860 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 16:46:26.865 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:26.865 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:26.865 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:26.865 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 16:46:26.870 10976 11040 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-21 16:46:26.870 10976 11040 I jxcore-log: 
03-21 16:46:26.870 10976 11040 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 16:46:26.870 10976 11040 I jxcore-log: 
03-21 16:46:26.875 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:26.875 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-21 16:46:26.875 10976 11040 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 16:46:26.875 10976 11040 I jxcore-log: 
03-21 16:46:26.875 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:26.880 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 16:46:26.880 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:26.880 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:26.880 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:46:26.880 10976 11040 I jxcore-log: 
,03-21 16:46:26.885 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:26.885 10976 11040 I jxcore-log: 
,03-21 16:46:26.885 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:26.885 10976 11040 I jxcore-log: 
,03-21 16:46:26.890 10976 11040 I jxcore-log: ok 114 error should be null
03-21 16:46:26.890 10976 11040 I jxcore-log: 
,03-21 16:46:26.890 10976 11040 I jxcore-log: ok 115 error should be null
03-21 16:46:26.890 10976 11040 I jxcore-log: 
,03-21 16:46:26.895 10976 11040 I jxcore-log: # 29. does not send duplicate availability changes
03-21 16:46:26.895 10976 11040 I jxcore-log: 
,03-21 16:46:27.105 10976 11040 I jxcore-log: # teardown
03-21 16:46:27.105 10976 11040 I jxcore-log: 
,03-21 16:46:29.075 10976 11040 I jxcore-log: ok 116 should be called once
03-21 16:46:29.075 10976 11040 I jxcore-log: 
,03-21 16:46:29.080 10976 11040 I jxcore-log: ok 117 should not have been called more than once
03-21 16:46:29.080 10976 11040 I jxcore-log: 
,03-21 16:46:29.085 10976 11040 I jxcore-log: # setup
03-21 16:46:29.085 10976 11040 I jxcore-log: 
,03-21 16:46:29.320 10976 11040 I jxcore-log: ok 118 error should be null
03-21 16:46:29.320 10976 11040 I jxcore-log: 
,03-21 16:46:29.325 10976 11040 I jxcore-log: ok 119 error should be null
03-21 16:46:29.325 10976 11040 I jxcore-log: 
,03-21 16:46:29.330 10976 11040 I jxcore-log: # 30. can get the network status
03-21 16:46:29.330 10976 11040 I jxcore-log: 
,03-21 16:46:31.330 10976 11040 I jxcore-log: # teardown
03-21 16:46:31.330 10976 11040 I jxcore-log: 
,03-21 16:46:31.450 10976 11040 I jxcore-log: ok 120 network status should have certain non-empty properties
03-21 16:46:31.450 10976 11040 I jxcore-log: 
,03-21 16:46:31.455 10976 11040 I jxcore-log: # setup
03-21 16:46:31.455 10976 11040 I jxcore-log: 
,03-21 16:46:31.530  3390  3864 E Watchdog: !@Sync 7 [03-21 16:46:31.535]
,03-21 16:46:31.605 10976 11040 I jxcore-log: ok 121 error should be null
03-21 16:46:31.605 10976 11040 I jxcore-log: 
,03-21 16:46:31.610 10976 11040 I jxcore-log: ok 122 error should be null
03-21 16:46:31.610 10976 11040 I jxcore-log: 
,03-21 16:46:31.615 10976 11040 I jxcore-log: # 31. wifi peer is marked unavailable if announcements stop
03-21 16:46:31.615 10976 11040 I jxcore-log: 
,03-21 16:46:31.695 10976 11040 I jxcore-log: # teardown
03-21 16:46:31.695 10976 11040 I jxcore-log: 
,03-21 16:46:31.810 10976 11040 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-21 16:46:31.810 10976 11040 I jxcore-log: 
,03-21 16:46:31.840 10976 11040 I jxcore-log: ok 123 host address should match
03-21 16:46:31.840 10976 11040 I jxcore-log: 
,03-21 16:46:31.845 10976 11040 I jxcore-log: ok 124 port should match
03-21 16:46:31.845 10976 11040 I jxcore-log: 
,03-21 16:46:32.815 10976 11040 I jxcore-log: ok 125 host address should be null
03-21 16:46:32.815 10976 11040 I jxcore-log: 
,03-21 16:46:32.825 10976 11040 I jxcore-log: ok 126 port should should be null
03-21 16:46:32.825 10976 11040 I jxcore-log: 
,03-21 16:46:32.845 10976 11040 I jxcore-log: # setup
03-21 16:46:32.845 10976 11040 I jxcore-log: 
,03-21 16:46:32.895 10976 11040 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 16:46:32.895 10976 11040 I jxcore-log: 
,03-21 16:46:32.900 10976 11040 I jxcore-log: ok 127 error should be null
03-21 16:46:32.900 10976 11040 I jxcore-log: 
,03-21 16:46:32.900 10976 11040 I jxcore-log: ok 128 error should be null
03-21 16:46:32.900 10976 11040 I jxcore-log: 
,03-21 16:46:32.905 10976 11040 I jxcore-log: # 32. Can call start/stopListeningForAdvertisements
03-21 16:46:32.905 10976 11040 I jxcore-log: 
,03-21 16:46:32.970 10976 11040 I jxcore-log: # teardown
03-21 16:46:32.970 10976 11040 I jxcore-log: 
,03-21 16:46:33.055 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 35225, start advertisements: false
,03-21 16:46:33.055 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:33.055 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 16:46:33.055 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 16:46:33.060 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:33.060 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:33.065 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:33.065  5849  6155 D BtGatt.GattService: registerClient() - UUID=6610b652-d049-4c2c-9c24-4aec704ce060
,03-21 16:46:33.110  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=6610b652-d049-4c2c-9c24-4aec704ce060, clientIf=6
03-21 16:46:33.110 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:33.115  5849  5861 D BtGatt.GattService: start scan with filters,
,03-21 16:46:33.155  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 47
,03-21 16:46:33.160 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 16:46:33.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:33.160 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-21 16:46:33.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-21 16:46:33.160  5849  5949 D BtGatt.ScanManager: handling starting scan
,03-21 16:46:33.160 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:33.160  5849  5949 D BtGatt.ScanManager: isFilteringSupported,
,03-21 16:46:33.160  5849  5949 D BluetoothAdapter: setting StandAloneBleMode,
,03-21 16:46:33.165 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
,03-21 16:46:33.165 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,03-21 16:46:33.180 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-21 16:46:33.180 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-21 16:46:33.180 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:33.180 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:33.180 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-21 16:46:33.180 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:33.185 10976 11040 I jxcore-log: ok 129 Can call startListeningForAdvertisements without error,
03-21 16:46:33.185 10976 11040 I jxcore-log: 
03-21 16:46:33.190  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:33.190  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:33.190  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:33.190  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:33.190  5849  5949 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-21 16:46:33.190 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:33.190 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:33.190 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 16:46:33.190 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:33.190  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:33.190  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:33.190  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 16:46:33.190  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:33.195  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:33.195  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 16:46:33.195  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:33.195  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 16:46:33.195 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:33.195 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:33.195 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 16:46:33.195 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 16:46:33.195 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 16:46:33.195 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:33.195 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:33.195 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:33.195 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:33.200 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:33.200 10976 11040 I jxcore-log: 
03-21 16:46:33.200  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:33.200  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:33.200 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:33.200 10976 11040 I jxcore-log: 
,03-21 16:46:33.205 10976 11040 I jxcore-log: ok 130 Can call stopListeningForAdvertisements without error
03-21 16:46:33.205 10976 11040 I jxcore-log: 
,03-21 16:46:33.205  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:33.210  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 6
,03-21 16:46:33.210  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:33.210  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:33.210  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:33.210 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:33.210 10976 11040 I jxcore-log: 
,03-21 16:46:33.210  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:33.210  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 16:46:33.210  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:33.215 10976 11040 I jxcore-log: # setup
03-21 16:46:33.215 10976 11040 I jxcore-log: 
03-21 16:46:33.215  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:33.215  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:33.355 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:33.355 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:33.355 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:33.360 10976 11040 I jxcore-log: ok 131 Should be able to call stopListeningForAdvertisments in teardown
03-21 16:46:33.360 10976 11040 I jxcore-log: 
,03-21 16:46:33.365 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 16:46:33.365 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:33.365 10976 11040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-21 16:46:33.365 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:46:33.365 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:33.365 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:33.365 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:33.365 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 16:46:33.365 10976 11040 D BluetoothLeScanner: could not find callback wrapper
03-21 16:46:33.365 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:33.370 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,03-21 16:46:33.370 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:33.370 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 16:46:33.370 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:33.370 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:33.375 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-21 16:46:33.375 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:33.375 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-21 16:46:33.380 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:33.395 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-21 16:46:33.395 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-21 16:46:33.395 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:33.405 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-21 16:46:33.405 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:33.405 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:33.410 10976 11040 I jxcore-log: ok 132 Should be able to call stopAdvertisingAndListening in teardown,
03-21 16:46:33.410 10976 11040 I jxcore-log: 
,03-21 16:46:33.415 10976 11040 I jxcore-log: # 33. Calling startListeningForAdvertisements twice is NOT an error
03-21 16:46:33.415 10976 11040 I jxcore-log: 
,03-21 16:46:33.420 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:33.420 10976 11040 I jxcore-log: 
,03-21 16:46:33.525 10976 11040 I jxcore-log: # teardown
03-21 16:46:33.525 10976 11040 I jxcore-log: 
,03-21 16:46:33.760 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 35225, start advertisements: false
,03-21 16:46:33.760 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:33.760 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 16:46:33.760 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 16:46:33.765 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:33.765 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:33.765 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:33.775  5849  5861 D BtGatt.GattService: registerClient() - UUID=52b1b052-992b-40cc-81ab-9f975979ab34
,03-21 16:46:33.815  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=52b1b052-992b-40cc-81ab-9f975979ab34, clientIf=6
,03-21 16:46:33.815 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:33.815  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:46:33.825  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 48
,03-21 16:46:33.825 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:33.825 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:33.825 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:33.825  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:33.825  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:33.825 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:33.825  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:33.825 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:33.825 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:46:33.825 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:33.825  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 16:46:33.825  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:33.825  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:33.825  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:33.825  5849  5949 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-21 16:46:33.830  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:33.830  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:33.830  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 16:46:33.830  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:33.830 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:33.830 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:33.830 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:33.830 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:33.830 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:33.830 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:33.830  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:33.830  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:33.830  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 16:46:33.830  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:33.835 10976 11040 I jxcore-log: ok 133 Can call startListeningForAdvertisements without error
03-21 16:46:33.835 10976 11040 I jxcore-log: 
,03-21 16:46:33.840 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 35225, start advertisements: false
,03-21 16:46:33.840 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:33.840 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:33.840 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:33.840 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:33.840 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:33.840 10976 11040 I jxcore-log: 
,03-21 16:46:33.840 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:33.840 10976 11040 I jxcore-log: 
,03-21 16:46:33.845 10976 11040 I jxcore-log: ok 134 Can call startListeningForAdvertisements twice without error
03-21 16:46:33.845 10976 11040 I jxcore-log: 
,03-21 16:46:33.850 10976 11040 I jxcore-log: # setup
03-21 16:46:33.850 10976 11040 I jxcore-log: 
,03-21 16:46:34.025 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:34.025 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:34.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-21 16:46:34.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:34.035  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:34.035  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:34.035  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 7
,03-21 16:46:34.040  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:34.040  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 16:46:34.040  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.040  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:34.045 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:34.045 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 16:46:34.045 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:34.045 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 16:46:34.045 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 16:46:34.045 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 16:46:34.045 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:34.045 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:34.045 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:34.045  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:34.045  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.050  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:34.050  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 16:46:34.055  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:34.065 10976 11040 I jxcore-log: ok 135 Should be able to call stopListeningForAdvertisments in teardown,
03-21 16:46:34.065 10976 11040 I jxcore-log: 
,03-21 16:46:34.065 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
,03-21 16:46:34.065 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-21 16:46:34.065 10976 11040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-21 16:46:34.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:46:34.065 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:34.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:34.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 16:46:34.070 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:46:34.080 10976 11040 D BluetoothLeScanner: could not find callback wrapper
03-21 16:46:34.080 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:34.080 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 16:46:34.080 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:34.080 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 16:46:34.085 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:34.085 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:34.085 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:34.085 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:34.085 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 16:46:34.095 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:34.095 10976 11040 I jxcore-log: 
,03-21 16:46:34.120 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:34.155 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:34.165 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-21 16:46:34.170 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:34.190 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:34.190 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:34.195 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:34.195 10976 11040 I jxcore-log: ok 136 Should be able to call stopAdvertisingAndListening in teardown
03-21 16:46:34.195 10976 11040 I jxcore-log: 
,03-21 16:46:34.215 10976 11040 I jxcore-log: # 34. Can call start/stopUpdateAdvertisingAndListening
03-21 16:46:34.215 10976 11040 I jxcore-log: 
,03-21 16:46:34.220 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:34.220 10976 11040 I jxcore-log: 
,03-21 16:46:34.310 10976 11040 I jxcore-log: # teardown
03-21 16:46:34.310 10976 11040 I jxcore-log: 
,03-21 16:46:34.510 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-21 16:46:34.510 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:34.515 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 16:46:34.515 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:34.520 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:46:34.520 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:34.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:34.525 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:34.530  5849  6155 D BtGatt.GattService: registerClient() - UUID=0829b02e-390a-47c0-87d3-c5e775c74119
,03-21 16:46:34.550  3390  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:46:34.550  3390  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:46:34.550  3390  3981 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
03-21 16:46:34.555  3390  3981 D BatteryService: stay LED for fully charged
,03-21 16:46:34.555  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:46:34.560  3390  3390 I MotionRecognitionService: Plugged
03-21 16:46:34.560  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:46:34.560  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:46:34.560  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:46:34.565  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:34.565  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:34.565  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 16:46:34.575  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=0829b02e-390a-47c0-87d3-c5e775c74119, clientIf=6,
03-21 16:46:34.575 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
03-21 16:46:34.575  5849  5861 D BtGatt.GattService: start scan with filters,
,03-21 16:46:34.580  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 16:46:34.580  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:46:34.590  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:46:34.590  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:34.590  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:34.590  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:34.605  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 49
,03-21 16:46:34.605 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:34.605 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:34.605 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:34.605 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:34.605 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:34.605 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:34.605 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:34.605 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:34.605 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:34.605 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:34.605 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:46:34.605 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:34.605  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:34.605  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:34.605  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:34.615  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:34.615  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.615  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:34.615  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:34.615  5849  5949 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-21 16:46:34.615  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:34.615  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.615  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:34.615  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:34.620  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:34.620  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.620  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:34.620  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.625  5849  6155 D BtGatt.GattService: registerClient() - UUID=d4bd26c5-ef39-48be-beee-9bda9269944c
,03-21 16:46:34.665  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=d4bd26c5-ef39-48be-beee-9bda9269944c, clientIf=7
,03-21 16:46:34.665 10976 10986 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:34.680  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 38
,03-21 16:46:34.680  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:34.680  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:34.680  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:34.680  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:34.680  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:34.685  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:34.685  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:34.685  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:34.685  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:34.685  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:46:34.690 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:34.690 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 16:46:34.690 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:34.690 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:34.690 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:46:34.690 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:34.690 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 16:46:34.690 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:34.690 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 16:46:34.690 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 16:46:34.690 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK,
03-21 16:46:34.690 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:34.690 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:34.690 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:34.690 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:34.690 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:46:34.690 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:46:34.690 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 16:46:34.690 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:34.690 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:34.690 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:34.695 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 16:46:34.695 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:34.695 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:34.695 10976 11040 I jxcore-log: 
03-21 16:46:34.695 10976 11406 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:34.695 10976 11406 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:34.695 10976 11040 I jxcore-log: ok 137 Can call startUpdateAdvertisingAndListening without error,
03-21 16:46:34.695 10976 11040 I jxcore-log: 
03-21 16:46:34.695 10976 11406 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[91]}
03-21 16:46:34.695 10976 11406 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 16:46:34.695 10976 11406 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:46:34.695 10976 11406 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36e73991
03-21 16:46:34.695 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 16:46:34.695 10976 11406 D BluetoothSocket: channel: 6
03-21 16:46:34.695 10976 11406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 16:46:34.695 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 16:46:34.695 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:34.695 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 16:46:34.695 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 16:46:34.695 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b23e0f6, channel: 6, state: LISTENING
03-21 16:46:34.695 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b23e0f6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36e73991, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@115ecf7mSocket: android.net.LocalSocket@22935764 impl:android.net.LocalSocketImpl@18b4ddcd fd:FileDescriptor[91]
03-21 16:46:34.695 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22935764 impl:android.net.LocalSocketImpl@18b4ddcd fd:FileDescriptor[91]
03-21 16:46:34.695 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:34.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:46:34.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 16:46:34.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:34.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:34.700 10976 11406 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 16:46:34.700 10976 11406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:34.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:46:34.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 16:46:34.700 10976 11406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 16:46:34.700  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:34.700  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:34.700  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 8
,03-21 16:46:34.700  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:34.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:34.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:34.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:34.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:46:34.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:46:34.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:34.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 16:46:34.700  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:34.700  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.700  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:34.705  5849  5948 D BtGatt.AdvertiseManager: message : 1
,03-21 16:46:34.705  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:34.705  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 16:46:34.705  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:34.705  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.705  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:34.705  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:34.705  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:46:34.705  5849  5920 D BtGatt.GattService: Client app is not null!
,03-21 16:46:34.705  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:46:34.710 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 16:46:34.710 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:34.710 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:46:34.710  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:34.710  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:34.710 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 16:46:34.710 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:34.710 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:34.710 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:34.710 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 16:46:34.710 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:34.710 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:34.710 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:34.710 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:34.710 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:46:34.710 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:34.710 10976 11040 I jxcore-log: 
,03-21 16:46:34.715 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-21 16:46:34.715 10976 11040 I jxcore-log: 
,03-21 16:46:34.715 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:34.720 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:34.720 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:34.720 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:34.725 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 16:46:34.725 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:46:34.725 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:34.725 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:34.725 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:34.725 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:34.725 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:34.725 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 16:46:34.725 10976 11040 I jxcore-log: ok 138 Can call stopAdvertisingAndListening without error
03-21 16:46:34.725 10976 11040 I jxcore-log: 
,03-21 16:46:34.730 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:46:34.730 10976 11040 I jxcore-log: 
,03-21 16:46:34.730 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:34.730 10976 11040 I jxcore-log: 
,03-21 16:46:34.735 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:34.735 10976 11040 I jxcore-log: 
,03-21 16:46:34.735 10976 11040 I jxcore-log: # setup
03-21 16:46:34.735 10976 11040 I jxcore-log: 
,03-21 16:46:34.875 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:34.880 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:34.880 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-21 16:46:34.890 10976 11040 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-21 16:46:34.890 10976 11040 I jxcore-log: 
,03-21 16:46:34.890 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:34.890 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:34.895 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:34.895 10976 11040 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-21 16:46:34.895 10976 11040 I jxcore-log: 
,03-21 16:46:34.905 10976 11040 I jxcore-log: # 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-21 16:46:34.905 10976 11040 I jxcore-log: 
,03-21 16:46:35.030 10976 11040 I jxcore-log: # teardown
03-21 16:46:35.030 10976 11040 I jxcore-log: 
,03-21 16:46:35.045  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:10), CUR = 33, LCD = 0
,03-21 16:46:35.140 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-21 16:46:35.140 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:35.140 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:35.140 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:35.145 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-21 16:46:35.145 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:35.145 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:35.145 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:35.150  5849  6155 D BtGatt.GattService: registerClient() - UUID=fbce9caf-8f58-48d6-85f8-aabbff6ad03a
,03-21 16:46:35.190  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=fbce9caf-8f58-48d6-85f8-aabbff6ad03a, clientIf=6
,03-21 16:46:35.190 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:35.195  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:46:35.210  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 50
,03-21 16:46:35.210  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:35.210  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:35.210  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:35.215  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:35.215  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:35.215  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:35.215  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:35.215  5849  5949 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-21 16:46:35.220  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:35.220  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:35.220  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:35.220  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:35.225  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:35.225  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:35.225  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 16:46:35.225  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:35.230 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:35.230 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:35.230 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:35.230 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:35.230 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:35.230 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:35.235 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:35.235 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:35.235 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 16:46:35.235 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:35.235 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:46:35.235 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false,
03-21 16:46:35.235  5849  6155 D BtGatt.GattService: registerClient() - UUID=4da67d45-2ef8-43e9-802c-ab3e95675b3c
,03-21 16:46:35.280  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=4da67d45-2ef8-43e9-802c-ab3e95675b3c, clientIf=7,
03-21 16:46:35.280 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-21 16:46:35.295  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 39
,03-21 16:46:35.295  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:46:35.295  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:35.295  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:35.295  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:35.295  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:35.300  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:35.300  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:35.300  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:35.300  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:35.300  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:46:35.300 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:35.300 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 16:46:35.305 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:35.305 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:35.305 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:46:35.305 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:35.305 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 16:46:35.305 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:35.305 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 16:46:35.305 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-21 16:46:35.305 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:35.305 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:35.305 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-21 16:46:35.305 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:35.305 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-21 16:46:35.305 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:46:35.305 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:46:35.305 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:35.305 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:35.305 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:35.305 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:35.305 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 16:46:35.305 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:35.310 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:35.310 10976 11040 I jxcore-log: 
03-21 16:46:35.310 10976 11421 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:35.310 10976 11421 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:35.310 10976 11040 I jxcore-log: ok 141 Can call startUpdateAdvertisingAndListening without error
03-21 16:46:35.310 10976 11040 I jxcore-log: 
,03-21 16:46:35.310 10976 11421 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[91]}
03-21 16:46:35.310 10976 11421 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:35.310 10976 11421 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:46:35.310 10976 11421 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d3e89c9
03-21 16:46:35.310 10976 11421 D BluetoothSocket: channel: 6
03-21 16:46:35.310 10976 11421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:46:35.315 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-21 16:46:35.315 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:35.315 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:35.315 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:35.315 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:35.315 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:35.315 10976 11040 I jxcore-log: 
,03-21 16:46:35.315 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:35.315 10976 11040 I jxcore-log: 
,03-21 16:46:35.320 10976 11040 I jxcore-log: ok 142 Can call startUpdateAdvertisingAndListening twice without error
03-21 16:46:35.320 10976 11040 I jxcore-log: 
,03-21 16:46:35.325 10976 11040 I jxcore-log: # setup
03-21 16:46:35.325 10976 11040 I jxcore-log: 
,03-21 16:46:35.515 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:35.515 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 16:46:35.515 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 16:46:35.515 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:35.525  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:35.525  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:35.530  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 9,
,03-21 16:46:35.530  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:35.530  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 16:46:35.535  5849  5949 D BtGatt.ScanManager: stopping BLe Batch,
,03-21 16:46:35.540  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-21 16:46:35.540  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:35.540  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 16:46:35.550 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:35.550 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:35.550 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:35.550  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:35.550 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-21 16:46:35.550 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-21 16:46:35.550 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:35.550 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 16:46:35.550 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-21 16:46:35.550 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:35.555  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-21 16:46:35.555  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 16:46:35.555  5849  5920 D BtGatt.GattService: current time is 226532343734,
03-21 16:46:35.555  5849  5920 D BtGatt.GattService: Batch record : [71, 3, -72, 48, -99, 93, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
,03-21 16:46:35.555  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:35.555  5849  5920 D ScanRecord: parseFromBytes
,03-21 16:46:35.560 10976 11040 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown,
03-21 16:46:35.560 10976 11040 I jxcore-log: 
03-21 16:46:35.565 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-21 16:46:35.565 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
03-21 16:46:35.565 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:35.565 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
,03-21 16:46:35.565 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
03-21 16:46:35.570 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c1218ce, channel: 6, state: LISTENING
03-21 16:46:35.570 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c1218ce, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d3e89c9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@149783efmSocket: android.net.LocalSocket@28902efc impl:android.net.LocalSocketImpl@69cf985 fd:FileDescriptor[91],
,03-21 16:46:35.570 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28902efc impl:android.net.LocalSocketImpl@69cf985 fd:FileDescriptor[91]
03-21 16:46:35.570 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 16:46:35.570 10976 11421 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-21 16:46:35.570 10976 11421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:35.570 10976 11421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 16:46:35.580 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-21 16:46:35.580 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-21 16:46:35.580 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-21 16:46:35.580 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-21 16:46:35.580 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:35.580 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-21 16:46:35.580 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-21 16:46:35.580 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:46:35.590 10976 11040 D BluetoothLeScanner: could not find callback wrapper,
03-21 16:46:35.590 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 16:46:35.590 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 16:46:35.595  5849  5948 D BtGatt.AdvertiseManager: message : 1,
03-21 16:46:35.600  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-21 16:46:35.600  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:35.605  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
03-21 16:46:35.605  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 16:46:35.605  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:35.610  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-21 16:46:35.625 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 16:46:35.625 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:35.625 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-21 16:46:35.625 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
03-21 16:46:35.625 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:35.625 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-21 16:46:35.625 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-21 16:46:35.625 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:46:35.625 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-21 16:46:35.625 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-21 16:46:35.630 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:35.630 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-21 16:46:35.630 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-21 16:46:35.630 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:35.630 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-21 16:46:35.635 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-21 16:46:35.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:46:35.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-21 16:46:35.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:35.650 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:35.650 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:35.655 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-21 16:46:35.655 10976 11040 I jxcore-log: 
03-21 16:46:35.665 10976 11040 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-21 16:46:35.665 10976 11040 I jxcore-log: 
,03-21 16:46:35.685 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:35.685 10976 11040 I jxcore-log: 
,03-21 16:46:35.685 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-21 16:46:35.685 10976 11040 I jxcore-log: 
,03-21 16:46:35.685 10976 11040 I jxcore-log: # 36. peerAvailabilityChange is called
03-21 16:46:35.685 10976 11040 I jxcore-log: 
,03-21 16:46:35.825 10976 11040 I jxcore-log: # teardown,
03-21 16:46:35.825 10976 11040 I jxcore-log: 
,03-21 16:46:35.930 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-21 16:46:35.935 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:35.935 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 16:46:35.935 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:35.940 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:46:35.940 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:35.940 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:35.940 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:35.945  5849  6155 D BtGatt.GattService: registerClient() - UUID=24313797-84dd-4523-b974-2d807b9be5ad
,03-21 16:46:35.990  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=24313797-84dd-4523-b974-2d807b9be5ad, clientIf=6
03-21 16:46:35.990 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:35.990  5849  5861 D BtGatt.GattService: start scan with filters
,03-21 16:46:36.005  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 51
,03-21 16:46:36.005  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:36.005  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:36.005  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:36.010  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:36.010  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:36.010  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:36.010  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:36.010  5849  5949 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-21 16:46:36.015  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:36.015  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:36.015  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:36.015  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:36.020  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:36.020  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:36.025 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 16:46:36.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:36.025  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:36.025  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:36.025 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:36.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:36.025 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:36.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:36.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:36.025 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:36.025 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:36.025 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:36.025 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:46:36.025 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:36.030  5849  6155 D BtGatt.GattService: registerClient() - UUID=64e10243-1815-48da-9752-ec19733f2bde,
,03-21 16:46:36.075  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=64e10243-1815-48da-9752-ec19733f2bde, clientIf=7
,03-21 16:46:36.075 10976 10988 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:36.085  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 40
,03-21 16:46:36.085  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:46:36.085  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
,03-21 16:46:36.085  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:36.085  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:46:36.085  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:36.090  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:36.090  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising,
,03-21 16:46:36.090  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 16:46:36.090  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:36.090  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 16:46:36.090 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:36.090 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 16:46:36.095 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:36.095 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:36.095 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:46:36.095 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:46:36.100 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 16:46:36.100 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:36.100 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 16:46:36.100 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-21 16:46:36.100 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:36.100 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:36.100 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
03-21 16:46:36.100 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 16:46:36.100 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:36.100 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-21 16:46:36.100 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:46:36.100 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 16:46:36.100 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:36.100 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:36.100 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:36.100 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 16:46:36.100 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:36.100 10976 11435 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:36.100 10976 11435 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 16:46:36.100 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:36.100 10976 11040 I jxcore-log: 
03-21 16:46:36.105 10976 11040 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListeningwithout error
03-21 16:46:36.105 10976 11040 I jxcore-log: 
,03-21 16:46:36.105 10976 11435 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[91]}
03-21 16:46:36.105 10976 11435 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:36.105 10976 11435 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:46:36.105 10976 11435 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25b8a901
03-21 16:46:36.105 10976 11435 D BluetoothSocket: channel: 6
03-21 16:46:36.105 10976 11435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:46:36.110 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
03-21 16:46:36.110 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:36.110 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-21 16:46:36.110 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:36.110 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:36.110 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:36.110 10976 11040 I jxcore-log: 
,03-21 16:46:36.110 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:36.110 10976 11040 I jxcore-log: 
,03-21 16:46:36.115 10976 11040 I jxcore-log: ok 146 Can call startListeningForAdvertisements without error
03-21 16:46:36.115 10976 11040 I jxcore-log: 
,03-21 16:46:37.025  3390  3619 V AlarmManager: waitForAlarm result :4,
,03-21 16:46:37.060  5849  5849 D BtGatt.ScanManager: awakened up at time 228038
03-21 16:46:37.065  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:37.080  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:37.080  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:37.080  5849  5920 D BtGatt.GattService: current time is 228059242484
03-21 16:46:37.080  5849  5920 D BtGatt.GattService: Batch record : [-32, 52, -29, -128, 64, 88, 1, -128, -85, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:37.080  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:37.080  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:37.085  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=58:40:80:E3:34:E0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-85, mTimestampNanos=228059380109}
03-21 16:46:37.085  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:46:37.085 10976 10986 D ScanRecord: parseFromBytes
,03-21 16:46:37.090 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1,
03-21 16:46:37.090 10976 10976 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-21 16:46:37.090  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-21 16:46:37.090  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
,03-21 16:46:37.090  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
03-21 16:46:37.095 10976 11040 I jxcore-log: ok 147 peers must be an array
03-21 16:46:37.095 10976 11040 I jxcore-log: 
,03-21 16:46:37.100 10976 11040 I jxcore-log: ok 148 peers must not be zero-length,
03-21 16:46:37.100 10976 11040 I jxcore-log: 
,03-21 16:46:37.100 10976 11040 I jxcore-log: ok 149 peer must have peerIdentifier
03-21 16:46:37.100 10976 11040 I jxcore-log: 
03-21 16:46:37.105  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-21 16:46:37.110  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1
,03-21 16:46:37.115 10976 11040 I jxcore-log: ok 150 peerIdentifier must be a string
03-21 16:46:37.115 10976 11040 I jxcore-log: 
,03-21 16:46:37.120 10976 11040 I jxcore-log: ok 151 peer must have peerAvailable
03-21 16:46:37.120 10976 11040 I jxcore-log: 
,03-21 16:46:37.120 10976 11040 I jxcore-log: ok 152 peer must have pleaseConnect
03-21 16:46:37.120 10976 11040 I jxcore-log: 
,03-21 16:46:37.120  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:46:37.125  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 16:46:37.130 10976 11040 I jxcore-log: # setup
03-21 16:46:37.130 10976 11040 I jxcore-log: 
,03-21 16:46:37.135  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 16:46:37.170  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:46:37.175  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:46:37.180  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:46:37.180  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:46:37.185  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-21 16:46:37.185  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-21 16:46:37.210  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:46:37.260 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:37.265 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 16:46:37.265 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 16:46:37.265 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:37.265  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:37.265  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:37.265  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:37.265  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 10
,03-21 16:46:37.265 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:37.265 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:37.265  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:37.265  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:37.265  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:37.270 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 16:46:37.270 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:46:37.270 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:46:37.270 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:37.270 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 16:46:37.270 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 16:46:37.270 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:37.270  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:37.270  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:37.270  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:37.270 10976 11040 I jxcore-log: ok 153 Should be able to call stopListeningForAdvertisments in teardown
03-21 16:46:37.270 10976 11040 I jxcore-log: 
,03-21 16:46:37.270 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 16:46:37.270  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-21 16:46:37.270  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:37.270  5849  5920 D BtGatt.GattService: current time is 228249594901
03-21 16:46:37.270  5849  5920 D BtGatt.GattService: Batch record : [-32, 52, -29, -128, 64, 88, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:37.275  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:37.275  5849  5920 D ScanRecord: parseFromBytes
,03-21 16:46:37.275 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-21 16:46:37.275 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:37.275 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 16:46:37.275 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 16:46:37.275 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16e601e7, channel: 6, state: LISTENING
03-21 16:46:37.275 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16e601e7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25b8a901, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@342d6194mSocket: android.net.LocalSocket@1785d43d impl:android.net.LocalSocketImpl@2ed42432 fd:FileDescriptor[91]
03-21 16:46:37.275 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1785d43d impl:android.net.LocalSocketImpl@2ed42432 fd:FileDescriptor[91]
03-21 16:46:37.275 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:37.275 10976 11435 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-21 16:46:37.275 10976 11435 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:37.275 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:46:37.275 10976 11435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 16:46:37.275 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:37.275 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:37.275 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:37.275 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:46:37.275 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 16:46:37.275 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:46:37.275 10976 11040 D BluetoothLeScanner: could not find callback wrapper
03-21 16:46:37.275 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:37.275 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 16:46:37.275  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:46:37.275  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:37.275  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 16:46:37.275  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:37.280  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 16:46:37.280  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:37.280  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:46:37.280 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:37.280 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:37.280 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:46:37.280 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 16:46:37.280 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-21 16:46:37.280 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:37.280 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:37.280 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:46:37.280 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:37.280 10976 11040 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 16:46:37.280 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:37.280 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:37.280 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:37.280 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:46:37.285 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-21 16:46:37.285 10976 11040 I jxcore-log: 
,03-21 16:46:37.285 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:37.290 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:37.290 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:37.290 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:37.295 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 16:46:37.295 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:37.295 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:37.295 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:37.295 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:37.295 10976 11040 I jxcore-log: ok 154 Should be able to call stopAdvertisingAndListening in teardown
03-21 16:46:37.295 10976 11040 I jxcore-log: 
,03-21 16:46:37.300 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:37.300 10976 11040 I jxcore-log: 
,03-21 16:46:37.300 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:37.300 10976 11040 I jxcore-log: 
,03-21 16:46:37.305 10976 11040 I jxcore-log: # 37. Can connect to a remote peer
03-21 16:46:37.305 10976 11040 I jxcore-log: 
,03-21 16:46:37.505 10976 11040 I jxcore-log: # teardown
03-21 16:46:37.505 10976 11040 I jxcore-log: 
,03-21 16:46:37.610 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 60733, start advertisements: true
,03-21 16:46:37.610 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:37.610 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 16:46:37.615 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:37.620 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:46:37.620 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:37.620 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:37.620 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:37.625  5849  5861 D BtGatt.GattService: registerClient() - UUID=fd6b4910-9fc0-4166-9a8a-2758a27f28e5
,03-21 16:46:37.665  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=fd6b4910-9fc0-4166-9a8a-2758a27f28e5, clientIf=6
,03-21 16:46:37.670 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,03-21 16:46:37.675  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:46:37.695  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 52
,03-21 16:46:37.700  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:37.700  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:37.700  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:37.705  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:37.705  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:37.705  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:37.705  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:37.705  5849  5949 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
03-21 16:46:37.705  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:37.705  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:37.710  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:37.710  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:37.710  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:37.710  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:37.715  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:37.715  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:37.715 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 16:46:37.715 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 16:46:37.715 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,03-21 16:46:37.715 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,03-21 16:46:37.715 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:37.715 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:37.715 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 16:46:37.715 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:37.715 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:37.715 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:37.715 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-21 16:46:37.715 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:37.735  5849  6155 D BtGatt.GattService: registerClient() - UUID=d41393f0-836a-4352-aff0-067bcc37ebb4
,03-21 16:46:37.765 10976 10985 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20cf329c, channel: 6, state: CLOSED
,03-21 16:46:37.765 10976 10985 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19953934, channel: 6, state: CLOSED
,03-21 16:46:37.770 10976 10985 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b23e0f6, channel: 6, state: CLOSED
,03-21 16:46:37.770 10976 10985 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c1218ce, channel: 6, state: CLOSED
,03-21 16:46:37.775 10976 10985 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16e601e7, channel: 6, state: CLOSED
,03-21 16:46:37.775  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=d41393f0-836a-4352-aff0-067bcc37ebb4, clientIf=7
,03-21 16:46:37.775 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:37.790  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 41
,03-21 16:46:37.790  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:37.790  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:37.790  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:37.790  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:46:37.790  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:37.795  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:37.795  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:37.795  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:37.795  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:37.795  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:46:37.795 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:46:37.795 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 16:46:37.800 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:46:37.800 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:37.800 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:46:37.800 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:46:37.800 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 16:46:37.800 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:37.800 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 16:46:37.800 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 16:46:37.800 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:37.800 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:37.800 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:37.800 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:37.800 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:37.800 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:46:37.800 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:46:37.800 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:37.800 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:37.800 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:37.800 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:37.800 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 16:46:37.800 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 16:46:37.805 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:37.805 10976 11040 I jxcore-log: 
,03-21 16:46:37.805 10976 11040 I jxcore-log: ok 155 Can call startUpdateAdvertisingAndListening without error
03-21 16:46:37.805 10976 11040 I jxcore-log: 
03-21 16:46:37.805 10976 11467 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:37.805 10976 11467 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:37.805 10976 11467 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
03-21 16:46:37.810 10976 11467 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:37.810 10976 11467 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:46:37.810 10976 11467 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@59c517e
03-21 16:46:37.810 10976 11467 D BluetoothSocket: channel: 6
03-21 16:46:37.810 10976 11467 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 16:46:37.810 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 60733, start advertisements: false
03-21 16:46:37.810 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:37.810 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-21 16:46:37.810 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:46:37.810 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:37.810 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:37.810 10976 11040 I jxcore-log: 
,03-21 16:46:37.815 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:37.815 10976 11040 I jxcore-log: 
,03-21 16:46:37.820 10976 11040 I jxcore-log: ok 156 Can call startListeningForAdvertisements without error
03-21 16:46:37.820 10976 11040 I jxcore-log: 
,03-21 16:46:38.660  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:46:38.725  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:38.735  5849  5849 D BtGatt.ScanManager: awakened up at time 229713
,03-21 16:46:38.740  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:38.750  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:38.750  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:38.750  5849  5920 D BtGatt.GattService: current time is 229728265776
03-21 16:46:38.750  5849  5920 D BtGatt.GattService: Batch record : [-33, 63, 24, 113, -15, 91, 1, -128, -67, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:38.750  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:38.750  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:38.750  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=5B:F1:71:18:3F:DF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-67, mTimestampNanos=229728404068}
03-21 16:46:38.750  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:46:38.755 10976 10988 D ScanRecord: parseFromBytes
03-21 16:46:38.755 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 16:46:38.755 10976 10976 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 16:46:38.770 10976 11040 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-21 16:46:38.770 10976 11040 I jxcore-log: 
,03-21 16:46:38.780 10976 11040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-21 16:46:38.780 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:46:38.780 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-21 16:46:38.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-21 16:46:38.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-21 16:46:38.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-21 16:46:38.785 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-21 16:46:38.785 10976 11040 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-21 16:46:38.790 10976 11472 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1527)
,03-21 16:46:38.795 10976 11472 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-21 16:46:38.795 10976 11472 D BluetoothSocket: connect(): myUserId = 0
03-21 16:46:38.795 10976 11472 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:38.800  5849  6155 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 16:46:38.800  5849  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:38.800  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 16:46:38.800  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 16:46:38.800  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-21 16:46:38.800 10976 11472 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
03-21 16:46:38.800  5849  5999 D IOP_DB_BT: db_query_execute: result 1
,03-21 16:46:38.800  5849  5999 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 16:46:39.365  5849  5999 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:39.365  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:39.365  5849  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-21 16:46:39.390  5849  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:39.390  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 16:46:39.390  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 16:46:39.390  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-21 16:46:39.390  5849  5999 D IOP_DB_BT: db_query_execute: result 1
03-21 16:46:39.390  5849  5999 W bt-btif : bta_dm_acl_change(), event : 0
03-21 16:46:39.390  5849  5999 W bt-btif : info:x10
03-21 16:46:39.390  5849  5920 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-21 16:46:39.390  5849  5920 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-21 16:46:39.390  5849  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-21 16:46:39.395  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 16:46:39.415  5849  5999 W bt-sdp  : process_service_search_attr_rsp,
,03-21 16:46:39.765  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:39.785  5849  5849 D BtGatt.ScanManager: awakened up at time 230760
,03-21 16:46:39.790  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:39.795  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:39.795  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:40.340  5849  5920 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-21 16:46:40.350  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 16:46:40.360  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 16:46:40.360  5849  5920 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-21 16:46:40.370  3390  4657 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
03-21 16:46:40.375  5849  5920 E bt-btif : check_cod: remote_cod = 0x5a020c
03-21 16:46:40.375  5849  5920 W bt-btif : btif_dm_ssp_reply: accept=1
,03-21 16:46:40.390  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 16:46:40.390  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 16:46:40.390  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED,
03-21 16:46:40.390  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,03-21 16:46:40.390  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11,
03-21 16:46:40.390  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 16:46:40.395  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 16:46:40.395  5849  5946 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-21 16:46:40.400  5849  5946 D BtConfig.SecureMode: isSecureModeOn:false,
03-21 16:46:40.400  3390  3576 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d14e42d u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3599bc7c 10051:com.android.settings/1000}
,03-21 16:46:40.400  5849  5946 I BluetoothBondStateMachine: Entering PendingCommandState State,
03-21 16:46:40.405  3390  3423 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:46:40.405 10051 10051 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 16:46:40.410  3726  4754 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 16:46:40.415  3390  4727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d14e42d u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:46:40.420 10183 10183 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 16:46:40.420 10183 11492 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 16:46:40.420 10183 10183 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-21 16:46:40.425 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 16:46:40.425  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d14e42d u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:46:40.430  3390  4007 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:46:40.435 10183 11493 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 16:46:40.435 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 16:46:40.440  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d14e42d u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{e43a094 10330:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 16:46:40.450 10330 10330 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 16:46:40.450 10330 10330 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 16:46:40.450 10330 10330 D GMHFPReceiver: jangil::setProperties()
,03-21 16:46:40.455 10330 10330 D GMHFPReceiver: jangil::printBTStatus()
,03-21 16:46:40.455  3390  4657 D SettingsProvider: name = Wearable0001
03-21 16:46:40.455  3390  4657 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:46:40.455  3390  4657 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:46:40.455  3390  4657 D SettingsProvider: selectionArgs: false
03-21 16:46:40.455  3390  4657 D SettingsProvider: selectionArgs: 10121
03-21 16:46:40.455  3390  4657 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:46:40.455  3390  4657 D SettingsProvider: ret = -1
,03-21 16:46:40.460  3390  4657 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
03-21 16:46:40.465 10330 10330 D GMHFPReceiver: ::::::::Wearable0001::false
03-21 16:46:40.465  3390  3981 D SettingsProvider: name = Wearable0002
03-21 16:46:40.465  3390  3981 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:46:40.465  3390  3981 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:46:40.465  3390  3981 D SettingsProvider: selectionArgs: false
03-21 16:46:40.465  3390  3981 D SettingsProvider: selectionArgs: 10121
03-21 16:46:40.465  3390  3981 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 16:46:40.465  3390  3981 D SettingsProvider: ret = -1
03-21 16:46:40.470  3390  3981 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
03-21 16:46:40.475  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 16:46:40.475 10330 10330 D GMHFPReceiver: ::::::::Wearable0002::false
03-21 16:46:40.480  3390  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d14e42d u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{963a9dd 4454:com.google.android.gms.persistent/u0a14}
03-21 16:46:40.490  3726  3726 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 16:46:40.550 10330 10330 D GMHFPReceiver: onServiceConnected() : 1
03-21 16:46:40.550 10330 10330 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 16:46:40.680  5849  5920 W bt-btif : btif_dm_auth_cmpl_evt
,03-21 16:46:40.690  5849  5920 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-21 16:46:40.725  5849  5920 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-21 16:46:40.730  5849  5946 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-21 16:46:40.735  3390  3980 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 16:46:40.745  5849  5946 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-21 16:46:40.745  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 16:46:40.745  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 16:46:40.745  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-21 16:46:40.745  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-21 16:46:40.745  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-21 16:46:40.745  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 16:46:40.750  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 16:46:40.755  3726  4754 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 16:46:40.755  3390  3576 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32616edc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3599bc7c 10051:com.android.settings/1000}
03-21 16:46:40.755  3390  4727 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-21 16:46:40.760 10051 10051 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 16:46:40.765  5849  5946 D BtConfig.SecureMode: isSecureModeOn:false
,03-21 16:46:40.770 10183 11504 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 16:46:40.770  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32616edc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:46:40.775 10183 10183 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 16:46:40.775 10183 10183 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-21 16:46:40.785  3390  4729 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32616edc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:46:40.785  3390  4242 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:46:40.790  5849  5946 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@3a6037f7
,03-21 16:46:40.790  3390  3423 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-21 16:46:40.790  3390  3423 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:46:40.790  3390  3423 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:46:40.790  3390  3423 D SettingsProvider: selectionArgs: false
03-21 16:46:40.790  3390  3423 D SettingsProvider: selectionArgs: 1002
03-21 16:46:40.790  3390  3423 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:46:40.795  3390  3423 D SettingsProvider: ret = -1,
03-21 16:46:40.795  5849  5946 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-21 16:46:40.800  3390  4415 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51,
03-21 16:46:40.800  3390  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32616edc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{e43a094 10330:com.samsung.android.app.watchmanagerstub/u0a121}
03-21 16:46:40.800  3390  4415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:46:40.800  3390  4415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:46:40.800  3390  4415 D SettingsProvider: selectionArgs: false
03-21 16:46:40.800  3390  4415 D SettingsProvider: selectionArgs: 1002
03-21 16:46:40.800  3390  4415 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 16:46:40.800  3390  4415 D SettingsProvider: ret = -1
,03-21 16:46:40.800  3390  4657 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
,03-21 16:46:40.800  3390  4657 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:46:40.800  3390  4657 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:46:40.800  3390  4657 D SettingsProvider: selectionArgs: false
03-21 16:46:40.800  3390  4657 D SettingsProvider: selectionArgs: 1002
03-21 16:46:40.800  3390  4657 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:46:40.805 10330 10330 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 16:46:40.805  3390  4657 D SettingsProvider: ret = -1
,03-21 16:46:40.805  3390  3619 V AlarmManager: waitForAlarm result :4
03-21 16:46:40.805  5849  5946 I BluetoothBondStateMachine: StableState(): Entering Off State
03-21 16:46:40.805 10330 10330 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 16:46:40.805 10330 10330 D GMHFPReceiver: jangil::setProperties()
,03-21 16:46:40.805 10183 11507 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 16:46:40.810 10330 10330 D GMHFPReceiver: jangil::printBTStatus()
03-21 16:46:40.810  3390  3422 D SettingsProvider: name = Wearable0001
03-21 16:46:40.810  3390  3422 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:46:40.810  3390  3422 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:46:40.810  3390  3422 D SettingsProvider: selectionArgs: false
03-21 16:46:40.810  3390  3422 D SettingsProvider: selectionArgs: 10121
03-21 16:46:40.810  3390  3422 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:46:40.810  3390  3422 D SettingsProvider: ret = -1
,03-21 16:46:40.810 10330 10330 D GMHFPReceiver: ::::::::Wearable0001::false
03-21 16:46:40.810  3390  4415 D SettingsProvider: name = Wearable0002
03-21 16:46:40.810  3390  4415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:46:40.810  3390  4415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:46:40.810  3390  4415 D SettingsProvider: selectionArgs: false
03-21 16:46:40.810  3390  4415 D SettingsProvider: selectionArgs: 10121
03-21 16:46:40.810  3390  4415 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:46:40.815  3390  4415 D SettingsProvider: ret = -1
03-21 16:46:40.815 10330 10330 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 16:46:40.820  3390  4007 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{32616edc u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{963a9dd 4454:com.google.android.gms.persistent/u0a14}
,03-21 16:46:40.825  5849  5849 D BtGatt.ScanManager: awakened up at time 231803,
03-21 16:46:40.825  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:40.830  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-21 16:46:40.830  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:40.905 10330 10330 D GMHFPReceiver: onServiceConnected() : 1
03-21 16:46:40.905 10330 10330 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 16:46:41.830  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:41.845  5849  5849 D BtGatt.ScanManager: awakened up at time 232820
03-21 16:46:41.845  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:41.850  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:41.850  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:42.860  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:42.875  5849  5849 D BtGatt.ScanManager: awakened up at time 233850
,03-21 16:46:42.880  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:42.880  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:42.880  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:43.890  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:43.895  5849  5849 D BtGatt.ScanManager: awakened up at time 234870
,03-21 16:46:43.895  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:43.895  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:43.895  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:43.895  5849  5920 D BtGatt.GattService: current time is 234873951985
03-21 16:46:43.895  5849  5920 D BtGatt.GattService: Batch record : [-33, 63, 24, 113, -15, 91, 1, -128, -67, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-21 16:46:43.895  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:43.895  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:43.895  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=5B:F1:71:18:3F:DF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-67, mTimestampNanos=234774111527}
03-21 16:46:43.895  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:43.900 10976 10986 D ScanRecord: parseFromBytes
03-21 16:46:43.900 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:46:44.695  3390  4111 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:46:44.695  3390  4111 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:46:44.695  3390  4111 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,03-21 16:46:44.695  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:46:44.700  3390  4111 D BatteryService: stay LED for fully charged
,03-21 16:46:44.705  3390  3390 I MotionRecognitionService: Plugged
03-21 16:46:44.705  3390  3390 D MotionRecognitionService:   cableConnection= 1,
03-21 16:46:44.705  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:46:44.705  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:46:44.715  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 16:46:44.715  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:44.715  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:46:44.735  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:46:44.735  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:46:44.750  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:46:44.750  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:44.750  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:44.750  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:44.820  5849  5999 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 66 RCID: 67
,03-21 16:46:44.900  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:44.910  5849  5849 D BtGatt.ScanManager: awakened up at time 235888
,03-21 16:46:44.915  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:44.920  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:44.920  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:44.920  5849  5920 D BtGatt.GattService: current time is 235898262485
03-21 16:46:44.920  5849  5920 D BtGatt.GattService: Batch record : [-33, 63, 24, 113, -15, 91, 1, -128, -68, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:44.920  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:44.920  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:44.920  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=5B:F1:71:18:3F:DF, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=235898502402}
03-21 16:46:44.920  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:46:44.925 10976 10988 D ScanRecord: parseFromBytes
03-21 16:46:44.925 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:46:45.075  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:12), CUR = 38, LCD = 0
,03-21 16:46:45.295  5849  5999 W bt-btif : new conn_srvc id:26, app_id:255
03-21 16:46:45.295  5849  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 16:46:45.295  5849  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-21 16:46:45.300 10976 11467 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@f28078a,
,03-21 16:46:45.300  5849  5999 W bt-btif : new conn_srvc id:26, app_id:1,
,03-21 16:46:45.300  5849  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255,
03-21 16:46:45.300  5849  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1,
,03-21 16:46:45.305  5849  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200,
03-21 16:46:45.315  5849  5857 E BluetoothRemoteDevices: setRfcommConnected true
,03-21 16:46:45.315  5849  5861 E BluetoothRemoteDevices: setRfcommConnected true
03-21 16:46:45.320 10976 11472 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1527)
03-21 16:46:45.320 10976 11472 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1527)
03-21 16:46:45.325 10976 11467 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
03-21 16:46:45.335 10976 11467 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 16:46:45.335 10976 11467 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 16:46:45.340 10976 11467 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1529)
03-21 16:46:45.340 10976 11467 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@51371fb, channel: 6, state: LISTENING
,03-21 16:46:45.340 10976 11467 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@51371fb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@59c517e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39243218mSocket: android.net.LocalSocket@323cd471 impl:android.net.LocalSocketImpl@2d071256 fd:FileDescriptor[93],
,03-21 16:46:45.340 10976 11467 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@323cd471 impl:android.net.LocalSocketImpl@2d071256 fd:FileDescriptor[93]
,03-21 16:46:45.340 10976 11472 D BluetoothSocket: getInputStream(): myUserId = 0,
03-21 16:46:45.340 10976 11467 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:45.345 10976 11542 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1529)
,03-21 16:46:45.345 10976 11472 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 16:46:45.350 10976 11472 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1528)
03-21 16:46:45.350 10976 11472 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1528)
,03-21 16:46:45.350 10976 11472 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1527)
03-21 16:46:45.350 10976 11467 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:45.350 10976 11467 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:45.355 10976 11467 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]},
,03-21 16:46:45.355 10976 11467 D BluetoothSocket: bindListen(), new LocalSocket ,
,03-21 16:46:45.355 10976 11467 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 16:46:45.355 10976 11467 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@181d32d7,
03-21 16:46:45.355 10976 11467 D BluetoothSocket: channel: 6
03-21 16:46:45.355 10976 11467 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
03-21 16:46:45.360 10976 11543 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1528)
,03-21 16:46:45.500  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:45.505  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:45.505  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 16:46:45.505  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:45.505  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 16:46:45.505  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:46:45.505  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 16:46:45.505  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:46:45.510 10976 11542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1529),
,03-21 16:46:45.510 10976 11542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51],
,03-21 16:46:45.510 10976 11542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1529),
,03-21 16:46:45.515 10976 11543 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1528),
,03-21 16:46:45.515 10976 11543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51],
,03-21 16:46:45.515  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 16:46:45.520  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:46:45.520  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 16:46:45.520  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:46:45.520 10976 11543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1527),
,03-21 16:46:45.520 10976 11543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1527),
,03-21 16:46:45.540 10976 11542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1529,
03-21 16:46:45.540 10976 11542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1529)
,03-21 16:46:45.540 10976 11542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51],
03-21 16:46:45.545 10976 10976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51],
,03-21 16:46:45.550 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51],
,03-21 16:46:45.550 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:46:45.560 10976 11543 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1528)
03-21 16:46:45.560 10976 11542 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1529)
03-21 16:46:45.585 10976 10976 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 16:46:45.600 10976 10976 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 16:46:45.600 10976 10976 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-21 16:46:45.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-21 16:46:45.610 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
,03-21 16:46:45.610 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE,
,03-21 16:46:45.610 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0,
03-21 16:46:45.610 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:46:45.610 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:46:45.610 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:46:45.620  5849  5948 D BtGatt.AdvertiseManager: message : 1,
,03-21 16:46:45.620  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-21 16:46:45.620  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
03-21 16:46:45.620  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:45.625  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-21 16:46:45.625  5849  5920 D BtGatt.GattService: Client app is not null!
,03-21 16:46:45.625  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:46:45.625 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:45.625 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:45.625 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:46:45.625 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:45.625 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:45.625 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:45.625 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:45.625 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:45.625 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:46:45.640  5849  5861 D BtGatt.GattService: registerClient() - UUID=9efc3151-4cec-4fdd-b931-85880a1d0f46
,03-21 16:46:45.680  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=9efc3151-4cec-4fdd-b931-85880a1d0f46, clientIf=7
,03-21 16:46:45.680 10976 10986 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:45.690  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 42
,03-21 16:46:45.690  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:45.690  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:45.690  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:45.690  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:46:45.690  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:45.695  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:45.695  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:45.695  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:45.700  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:45.700  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:46:45.700 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:46:45.700  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:45.700  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:45.700  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 11
,03-21 16:46:45.700  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:45.700 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:45.700 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:45.700  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:45.700 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 16:46:45.700  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:45.700 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:45.700 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:45.700 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:46:45.700  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:45.705  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:45.705  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:45.705  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:45.705  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-21 16:46:45.705  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:45.705  5849  5920 D BtGatt.GattService: current time is 236683172652
03-21 16:46:45.705  5849  5920 D BtGatt.GattService: Batch record : [-33, 63, 24, 113, -15, 91, 1, -128, -67, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-21 16:46:45.705  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:45.705  5849  5857 D BtGatt.GattService: registerClient() - UUID=6a2bd757-2c77-4b7a-b987-46267ca5914b
03-21 16:46:45.705  5849  5920 D ScanRecord: parseFromBytes
,03-21 16:46:45.745  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=6a2bd757-2c77-4b7a-b987-46267ca5914b, clientIf=6
,03-21 16:46:45.745 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:45.750  5849  5861 D BtGatt.GattService: start scan with filters
,03-21 16:46:45.760  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 53
,03-21 16:46:45.760 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-21 16:46:45.760  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:45.760  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:45.760  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
,03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:46:45.760 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:46:45.760  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:46:45.760  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:45.760  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:45.760  5849  5949 D BtGatt.ScanManager: allow scan with filters
,03-21 16:46:45.760  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:45.760  5849  5949 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-21 16:46:45.765  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:45.765  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:45.765  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:45.765  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:45.765  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 16:46:45.765  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:45.765  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:45.765  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 16:46:45.765  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.770  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-21 16:46:45.770  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:45.770  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:46:45.770 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 16:46:45.770 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 16:46:45.770 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:46:45.770 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 16:46:45.770 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:45.770 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:45.770 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:45.770 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:45.770 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:46:45.770  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 16:46:45.770  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.775  5849  5857 D BtGatt.GattService: registerClient() - UUID=7f07f391-347b-4f29-9d4c-db44222db831
,03-21 16:46:45.815  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=7f07f391-347b-4f29-9d4c-db44222db831, clientIf=7
,03-21 16:46:45.815 10976 10988 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:45.845  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 43
,03-21 16:46:45.845  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:45.850  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
,03-21 16:46:45.850  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:45.855  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:46:45.860  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:45.870  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:45.870  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:45.875  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 16:46:45.875  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:45.875  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-21 16:46:45.875 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:46:45.880  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:45.880  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:45.880  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 12
,03-21 16:46:45.880  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:45.885  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:45.885  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.885  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:45.885 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:45.885 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-21 16:46:45.885 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:45.885 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
,03-21 16:46:45.885 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:45.885 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
03-21 16:46:45.890  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 16:46:45.890  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.890  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-21 16:46:45.890  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-21 16:46:45.890  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.895  5849  6155 D BtGatt.GattService: registerClient() - UUID=56a9a914-13b0-4144-8b2d-5d1110571eff
,03-21 16:46:45.935  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=56a9a914-13b0-4144-8b2d-5d1110571eff, clientIf=6
03-21 16:46:45.935 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:45.940  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:46:45.960  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 54
,03-21 16:46:45.960  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:45.960  5849  5949 D BtGatt.ScanManager: isFilteringSupported
,03-21 16:46:45.965  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:45.970  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:45.970  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.970  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:45.970  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:45.970  5849  5949 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-21 16:46:45.975  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:45.975  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.975  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:45.975  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:45.975  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:45.975  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.980  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 16:46:45.980  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:45.985 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:46:45.985 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:46:45.990  5849  5948 D BtGatt.AdvertiseManager: message : 1,
03-21 16:46:45.990  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-21 16:46:45.990  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:45.990  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:46:45.990  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:46:45.990  5849  5920 D BtGatt.GattService: Client app is not null!,
,03-21 16:46:45.995  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:46:45.995 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:45.995 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 16:46:45.995 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:46:45.995 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:45.995 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:45.995 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:45.995 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:45.995 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:45.995 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:46:46.000  5849  5861 D BtGatt.GattService: registerClient() - UUID=444f3188-9aca-471d-8641-748ede64f708
,03-21 16:46:46.040  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=444f3188-9aca-471d-8641-748ede64f708, clientIf=7,
03-21 16:46:46.045 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:46.055  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 44
,03-21 16:46:46.055  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:46:46.055  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:46.055  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:46.055  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:46.055  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:46.060  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:46.060  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:46.060  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:46.060  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:46.060  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 16:46:46.060 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:46:46.065  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:46.065  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:46.065  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 13
03-21 16:46:46.065  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:46.065 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:46.065 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:46.065 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:46.065 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:46.065 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:46.065 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:46.065  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:46.065  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:46.065  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:46.070  5849  5857 D BtGatt.GattService: registerClient() - UUID=2f575102-a672-4f9a-bf4d-646b4d6201e0
,03-21 16:46:46.070  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:46.070  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:46.070  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:46.070  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:46.070  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:46.110  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=2f575102-a672-4f9a-bf4d-646b4d6201e0, clientIf=6
,03-21 16:46:46.110 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:46.110  5849  5861 D BtGatt.GattService: start scan with filters
,03-21 16:46:46.130  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 55
,03-21 16:46:46.135  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:46.135  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:46.135  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:46.140  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:46.140  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:46.145  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:46.145  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:46.145  5849  5949 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
03-21 16:46:46.145  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:46.145  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:46.150  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:46.150  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:46.150  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:46.150  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:46.155  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 16:46:46.155  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:46.155 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:46.155 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:46.155 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 16:46:46.155 10976 10976 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-21 16:46:46.155 10976 10976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:46:46.155 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:46.155 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:46.155 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:46.155 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:46.155 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:46.155 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51],
03-21 16:46:46.155 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 16:46:46.160 10976 10976 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 16:46:46.175 10976 10976 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-21 16:46:46.175 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 16:46:46.175 10976 10976 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-21 16:46:46.175 10976 11575 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1530)
,03-21 16:46:46.180 10976 11576 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1531),
,03-21 16:46:46.185 10976 11575 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50780,
03-21 16:46:46.185 10976 11575 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-21 16:46:46.185 10976 11575 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 50780 (peer ID: F8:95:C7:87:3C:51)
,03-21 16:46:46.190 10976 11040 I jxcore-log: INFO testThaliMobileNative: ,
03-21 16:46:46.190 10976 11040 I jxcore-log: 
03-21 16:46:46.190 10976 11040 I jxcore-log: ok 157 Must have listeningPort
03-21 16:46:46.190 10976 11040 I jxcore-log: 
,03-21 16:46:46.195 10976 11575 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-21 16:46:46.195  2876  3383 D EnterpriseController: netId is 0,
03-21 16:46:46.195  2876  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 16:46:46.195 10976 11040 I jxcore-log: ok 158 listeningPort must be a number,
03-21 16:46:46.195 10976 11040 I jxcore-log: 
,03-21 16:46:46.200 10976 11040 I jxcore-log: ok 159 Connection must have clientPort
03-21 16:46:46.200 10976 11040 I jxcore-log: 
,03-21 16:46:46.200 10976 11576 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 60733,
03-21 16:46:46.200 10976 11576 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-21 16:46:46.200 10976 11576 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 16:46:46.200 10976 11576 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 16:46:46.200 10976 11576 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1531)
03-21 16:46:46.200 10976 11576 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1531)
,03-21 16:46:46.205 10976 11040 I jxcore-log: ok 160 clientPort must be a number,
03-21 16:46:46.205 10976 11040 I jxcore-log: 
,03-21 16:46:46.210 10976 11040 I jxcore-log: ok 161 Connection must have serverPort
03-21 16:46:46.210 10976 11040 I jxcore-log: 
,03-21 16:46:46.210 10976 11040 I jxcore-log: ok 162 serverPort must be a number
03-21 16:46:46.210 10976 11040 I jxcore-log: 
,03-21 16:46:46.210 10976 11579 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1533, name: Receiver)
,03-21 16:46:46.210 10976 11578 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1532, name: Sender)
,03-21 16:46:46.215 10976 11040 I jxcore-log: ok 163 forward connection must have clientPort == 0
03-21 16:46:46.215 10976 11040 I jxcore-log: 
,03-21 16:46:46.215 10976 11040 I jxcore-log: ok 164 forward connection must have serverPort == 0
03-21 16:46:46.215 10976 11040 I jxcore-log: 
,03-21 16:46:46.230 10976 11040 I jxcore-log: # setup
03-21 16:46:46.230 10976 11040 I jxcore-log: 
,03-21 16:46:46.340 10976 11578 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1532, thread name: Sender)
03-21 16:46:46.340 10976 11578 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 16:46:46.340 10976 11578 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 16:46:46.340 10976 11578 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1531
03-21 16:46:46.340 10976 11578 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1531)
03-21 16:46:46.340 10976 11578 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@37f9fde2, channel: 6, state: CONNECTED
03-21 16:46:46.340 10976 11578 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@37f9fde2, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f982573, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19232c30mSocket: android.net.LocalSocket@890a0a9 impl:android.net.LocalSocketImpl@223e162e fd:FileDescriptor[91]
03-21 16:46:46.340 10976 11578 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@890a0a9 impl:android.net.LocalSocketImpl@223e162e fd:FileDescriptor[91]
,03-21 16:46:46.340  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:46.345  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:46.345  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:46.345 10976 11578 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@37f9fde2, channel: 6, state: CLOSED
03-21 16:46:46.345  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:46.345 10976 11578 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@37f9fde2, channel: 6, state: CLOSED
03-21 16:46:46.345 10976 11578 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-21 16:46:46.345 10976 11579 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1533, thread name: Receiver): bt socket closed, read return: -1
03-21 16:46:46.345 10976 11578 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-21 16:46:46.345 10976 11578 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1533
03-21 16:46:46.345 10976 11579 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1533, name: Receiver)
03-21 16:46:46.345 10976 11578 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
,03-21 16:46:46.345 10976 11578 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1532,
,03-21 16:46:46.350 10976 11578 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1531),
,03-21 16:46:46.360 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:46.360 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-21 16:46:46.360 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 16:46:46.360 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 16:46:46.360 10976 11578 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1531)
,03-21 16:46:46.360 10976 11578 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-21 16:46:46.360 10976 11578 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1532, name: Sender)
03-21 16:46:46.365  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:46.365  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:46.370  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 14
,03-21 16:46:46.370  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 16:46:46.370  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 16:46:46.370  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:46.370 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:46.370 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:46.370  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:46.370 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:46.375 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:46:46.375 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-21 16:46:46.375 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:46.375 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:46.375 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-21 16:46:46.375 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:46.375  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:46.375  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:46.375  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:46.380  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-21 16:46:46.380  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:46.385 10976 11040 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 16:46:46.385 10976 11040 I jxcore-log: 
,03-21 16:46:46.385 10976 11040 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 16:46:46.385 10976 11040 I jxcore-log: 
,03-21 16:46:46.390 10976 11040 I jxcore-log: ok 165 Should be able to call stopListeningForAdvertisments in teardown,
03-21 16:46:46.390 10976 11040 I jxcore-log: 
03-21 16:46:46.390 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:46.390 10976 11040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-21 16:46:46.390 10976 11040 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1530)
03-21 16:46:46.390 10976 11040 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1530)
03-21 16:46:46.390 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14c5a5cf, channel: 7, state: CONNECTED
03-21 16:46:46.390 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14c5a5cf, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dc6db5c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9a99e65mSocket: android.net.LocalSocket@3299673a impl:android.net.LocalSocketImpl@19a0cfeb fd:FileDescriptor[112]
03-21 16:46:46.390 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3299673a impl:android.net.LocalSocketImpl@19a0cfeb fd:FileDescriptor[112]
,03-21 16:46:46.390 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14c5a5cf, channel: 7, state: CLOSED
03-21 16:46:46.390 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14c5a5cf, channel: 7, state: CLOSED
03-21 16:46:46.390 10976 11040 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 16:46:46.390 10976 11040 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1530)
03-21 16:46:46.390 10976 11040 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1530)
03-21 16:46:46.390 10976 11575 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1530)
,03-21 16:46:46.390 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-21 16:46:46.390 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:46.390 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 16:46:46.390 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 16:46:46.390 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23945148, channel: 6, state: LISTENING
03-21 16:46:46.390 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23945148, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@181d32d7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c9abbe1mSocket: android.net.LocalSocket@2426bd06 impl:android.net.LocalSocketImpl@2aba7fc7 fd:FileDescriptor[113]
03-21 16:46:46.390 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2426bd06 impl:android.net.LocalSocketImpl@2aba7fc7 fd:FileDescriptor[113]
,03-21 16:46:46.390 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:46.390 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:46:46.390 10976 11467 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 16:46:46.390 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:46.390 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:46.390 10976 11467 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:46.390 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:46.390 10976 11467 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 16:46:46.395 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 16:46:46.395 10976 11040 D BluetoothLeScanner: could not find callback wrapper
,03-21 16:46:46.395 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:46.395 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 16:46:46.395  5849  5948 D BtGatt.AdvertiseManager: message : 1
,03-21 16:46:46.395  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:46.395  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:46.395  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:46.400  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 16:46:46.400  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:46.400  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-21 16:46:46.400 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:46.400 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:46.400 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-21 16:46:46.400 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-21 16:46:46.400 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:46.400 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:46.400 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:46.400 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 16:46:46.400 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:46.400 10976 11040 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 16:46:46.400 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:46.400 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:46.400 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:46.400 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:46:46.405 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:46:46.405 10976 11040 I jxcore-log: 
,03-21 16:46:46.405 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:46.410 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 16:46:46.415 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:46.415 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 16:46:46.415 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:46:46.415 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:46.415 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 16:46:46.415 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:46.415 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:46.415 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:46.415 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 16:46:46.415 10976 11040 I jxcore-log: ok 166 Should be able to call stopAdvertisingAndListening in teardown
03-21 16:46:46.415 10976 11040 I jxcore-log: 
,03-21 16:46:46.425 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:46.425 10976 11040 I jxcore-log: 
,03-21 16:46:46.425 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:46.425 10976 11040 I jxcore-log: 
,03-21 16:46:46.425 10976 11040 I jxcore-log: # 38. Can shift large amounts of data
03-21 16:46:46.425 10976 11040 I jxcore-log: 
,03-21 16:46:46.430  5849  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-21 16:46:46.430  5849  5999 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-21 16:46:46.900  5849  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-21 16:46:47.280 10976 11040 I jxcore-log: # teardown
03-21 16:46:47.280 10976 11040 I jxcore-log: 
,03-21 16:46:47.475 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 32849, start advertisements: true
,03-21 16:46:47.475 10976 11040 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 16:46:47.475 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-21 16:46:47.480 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:47.480 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:47.480 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:46:47.480 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:46:47.480 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:46:47.480 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:46:47.480 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
,03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:46:47.485 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
,03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 16:46:47.490 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:47.490 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:47.490 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:47.500 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-21 16:46:47.500 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:47.500 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:47.500 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:47.505  5849  5861 D BtGatt.GattService: registerClient() - UUID=b4920add-9735-4462-a342-a20b8d5d522a
,03-21 16:46:47.545  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=b4920add-9735-4462-a342-a20b8d5d522a, clientIf=6
,03-21 16:46:47.545 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:47.545  5849  6155 D BtGatt.GattService: start scan with filters
,03-21 16:46:47.560  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 56
,03-21 16:46:47.560 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:47.560 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:47.560 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:47.560 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:47.560 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:47.560 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:47.560  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:47.560  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:47.560 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:47.560  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:47.560 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:47.560 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:47.560 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:47.560 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:46:47.560 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:46:47.565  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-21 16:46:47.565  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:47.565  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:47.565  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 16:46:47.565  5849  5949 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
03-21 16:46:47.565  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:47.565  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:47.565  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:47.565  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:47.570  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:47.570  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:47.570  5849  5857 D BtGatt.GattService: registerClient() - UUID=57c907d7-1037-4ce4-a824-119a3c1ad2ba
,03-21 16:46:47.570  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:47.570  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:47.615  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=57c907d7-1037-4ce4-a824-119a3c1ad2ba, clientIf=7
,03-21 16:46:47.615 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:47.630  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 45
,03-21 16:46:47.630  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:47.630  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:47.630  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:47.635  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:47.635  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:47.640  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:47.640  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:47.645  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:47.645  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 16:46:47.645  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 16:46:47.645 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:47.645 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:46:47.650 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:47.650 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:47.650 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:46:47.650 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:47.650 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 16:46:47.655 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:47.655 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 16:46:47.655 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-21 16:46:47.655 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-21 16:46:47.655 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:47.655 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 16:46:47.655 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:47.655 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:46:47.655 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:46:47.655 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:47.655 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-21 16:46:47.655 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:47.655 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:47.655 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 16:46:47.655 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:47.655 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:47.655 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:47.655 10976 11040 I jxcore-log: 
,03-21 16:46:47.665 10976 11040 I jxcore-log: ok 167 Can call startUpdateAdvertisingAndListening without error,
03-21 16:46:47.665 10976 11040 I jxcore-log: 
,03-21 16:46:47.665 10976 11600 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:47.665 10976 11600 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:47.670 10976 11600 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
03-21 16:46:47.670 10976 11600 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:47.670 10976 11600 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 16:46:47.670 10976 11600 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32d55163
03-21 16:46:47.670 10976 11600 D BluetoothSocket: channel: 6
03-21 16:46:47.670 10976 11600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:46:47.675 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 32849, start advertisements: false
,03-21 16:46:47.675 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:47.675 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-21 16:46:47.675 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:47.675 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:47.680 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:47.680 10976 11040 I jxcore-log: 
,03-21 16:46:47.680 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:47.680 10976 11040 I jxcore-log: 
,03-21 16:46:47.685 10976 11040 I jxcore-log: ok 168 Can call startListeningForAdvertisements without error
03-21 16:46:47.685 10976 11040 I jxcore-log: 
,03-21 16:46:48.575  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:48.585  5849  5849 D BtGatt.ScanManager: awakened up at time 239562
,03-21 16:46:48.590  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:48.595  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:48.595  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 16:46:48.595  5849  5920 D BtGatt.GattService: current time is 239574340485
03-21 16:46:48.595  5849  5920 D BtGatt.GattService: Batch record : [76, -4, -76, -71, -27, 87, 1, -128, -67, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-21 16:46:48.600  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:48.600  5849  5920 D ScanRecord: parseFromBytes,
,03-21 16:46:48.600  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=57:E5:B9:B4:FC:4C, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-67, mTimestampNanos=239524697069}
03-21 16:46:48.600  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:48.600 10976 10988 D ScanRecord: parseFromBytes
03-21 16:46:48.605 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-21 16:46:48.605 10976 10976 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: ,
,03-21 16:46:48.630 10976 11040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51,
,03-21 16:46:48.630 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:46:48.635 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51,
03-21 16:46:48.635 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-21 16:46:48.635 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-21 16:46:48.635 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-21 16:46:48.635 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,03-21 16:46:48.635 10976 11040 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-21 16:46:48.640 10976 11607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1535)
,03-21 16:46:48.645 10976 11607 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-21 16:46:48.645 10976 11607 D BluetoothSocket: connect(): myUserId = 0
,03-21 16:46:48.650 10976 11607 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:48.655  5849  5857 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 16:46:48.655 10976 11607 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-21 16:46:49.065  5849  5999 W bt-sdp  : process_service_search_attr_rsp
,03-21 16:46:49.625  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:46:49.640  5849  5849 D BtGatt.ScanManager: awakened up at time 240614
,03-21 16:46:49.645  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:49.650  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:49.650  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 16:46:49.650  5849  5920 D BtGatt.GattService: current time is 240626930236
,03-21 16:46:49.650  5849  5920 D BtGatt.GattService: Batch record : [76, -4, -76, -71, -27, 87, 1, -128, -68, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-21 16:46:49.650  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-21 16:46:49.650  5849  5920 D ScanRecord: parseFromBytes
,03-21 16:46:49.650  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=57:E5:B9:B4:FC:4C, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=240527258902}
,03-21 16:46:49.650  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-21 16:46:49.655 10976 11033 D ScanRecord: parseFromBytes
03-21 16:46:49.655 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:46:49.880  5849  5999 W bt-btif : new conn_srvc id:26, app_id:1
,03-21 16:46:49.890  5849  6155 E BluetoothRemoteDevices: setRfcommConnected true
,03-21 16:46:49.910 10976 11607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1535),
,03-21 16:46:49.915 10976 11607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1535)
,03-21 16:46:49.920 10976 11607 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 16:46:49.925 10976 11607 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 16:46:49.930 10976 11607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1536)
,03-21 16:46:49.930 10976 11607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1536)
,03-21 16:46:49.930 10976 11607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1535)
,03-21 16:46:49.935 10976 11626 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1536)
,03-21 16:46:50.015  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:50.015  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:50.015  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:50.015  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:50.150  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:50.155  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:50.155  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:50.155  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:50.155 10976 11626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1536)
,03-21 16:46:50.165 10976 11626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:46:50.165 10976 11626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1535)
,03-21 16:46:50.170 10976 11626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1535),
,03-21 16:46:50.170 10976 10976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 16:46:50.175 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51],
03-21 16:46:50.175 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1,
,03-21 16:46:50.185 10976 11626 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1536),
,03-21 16:46:50.190 10976 10976 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-21 16:46:50.195 10976 10976 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-21 16:46:50.200 10976 10976 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-21 16:46:50.200 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-21 16:46:50.205 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-21 16:46:50.205 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:50.205 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:46:50.205 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:46:50.205 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:46:50.205 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:46:50.210  5849  5948 D BtGatt.AdvertiseManager: message : 1,
03-21 16:46:50.210  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-21 16:46:50.210  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:50.210  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:50.215  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:46:50.215  5849  5920 D BtGatt.GattService: Client app is not null!
,03-21 16:46:50.215  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-21 16:46:50.220 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 16:46:50.220 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-21 16:46:50.220 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false,
03-21 16:46:50.220 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:50.225 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0",
,03-21 16:46:50.225 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:50.225 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 16:46:50.225 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-21 16:46:50.225 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-21 16:46:50.235  5849  5861 D BtGatt.GattService: registerClient() - UUID=89aa7399-2228-4baa-8ee0-d2d218bed76e,
,03-21 16:46:50.275  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=89aa7399-2228-4baa-8ee0-d2d218bed76e, clientIf=7
,03-21 16:46:50.275 10976 10988 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:50.290  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 46
,03-21 16:46:50.290  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:46:50.290  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:50.290  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:50.290  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:50.290  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:50.295  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:50.295  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:50.295  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:50.295  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:50.295  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:46:50.295 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:46:50.300  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:50.300  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:50.300  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 15
,03-21 16:46:50.300  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:50.300  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:50.300  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.300 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:50.300  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:50.300 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:50.300 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:50.300 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:50.300 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:50.300 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:50.305  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:50.305  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.305  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:50.305  5849  5857 D BtGatt.GattService: registerClient() - UUID=fe93461a-179c-4f3f-8a05-a2860b0ace88
,03-21 16:46:50.305  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
03-21 16:46:50.305  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.305  5849  5920 D BtGatt.GattService: current time is 241283377819
03-21 16:46:50.305  5849  5920 D BtGatt.GattService: Batch record : [76, -4, -76, -71, -27, 87, 1, -128, -68, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 118, -4, -93, 17, -34, 85, 1, -128, -68, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 4, 36, 116, -18, 41, 121, 1, -128, -79, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 104, -51, 12, -79, -44, 122, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:50.305  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:50.305  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:50.305  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:50.305  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:50.305  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-21 16:46:50.305  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:50.305  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:46:50.305  5849  5920 D ScanRecord: parseFromBytes
,03-21 16:46:50.345  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=fe93461a-179c-4f3f-8a05-a2860b0ace88, clientIf=6
,03-21 16:46:50.350 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:50.350  5849  5861 D BtGatt.GattService: start scan with filters
,03-21 16:46:50.380  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 57
,03-21 16:46:50.385 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:46:50.385 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:46:50.390  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:50.390  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:50.390  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:50.395  5849  5948 D BtGatt.AdvertiseManager: message : 1
,03-21 16:46:50.395  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:50.395  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:50.400  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:50.405  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,03-21 16:46:50.405  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 16:46:50.405  5849  5949 D BtGatt.ScanManager: allow scan with filters,
03-21 16:46:50.410  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
,03-21 16:46:50.410  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:46:50.410  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:50.410  5849  5949 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-21 16:46:50.415  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:50.415  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.415  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:50.415  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:50.420  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:50.420  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.420  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:46:50.425  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:50.425  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:50.465 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:50.465 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 16:46:50.465 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:46:50.465 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:50.465 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:50.465 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:50.465 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:50.465 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:50.465 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:46:50.490  5849  5857 D BtGatt.GattService: registerClient() - UUID=dfbb7720-b8c5-4545-8048-bece3a06b976,
,03-21 16:46:50.530  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=dfbb7720-b8c5-4545-8048-bece3a06b976, clientIf=7
,03-21 16:46:50.530 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:50.555  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 47
,03-21 16:46:50.555  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:50.560  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:50.560  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:50.565  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:46:50.565  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:50.570  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:50.575  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:50.580  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:50.580  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 16:46:50.580  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 16:46:50.585 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:46:50.585  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
03-21 16:46:50.585  5849  5999 W bt-btif : new conn_srvc id:26, app_id:255
03-21 16:46:50.585  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:50.585  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 3
03-21 16:46:50.585 10976 11600 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3c41a0bf
03-21 16:46:50.585  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:50.585  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.585  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:50.590  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 16:46:50.590 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:50.590 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:50.590 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-21 16:46:50.590 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:46:50.590  5849  5861 E BluetoothRemoteDevices: setRfcommConnected true
03-21 16:46:50.590 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:50.590 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:46:50.590 10976 11600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
03-21 16:46:50.590  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:50.590  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.590  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:50.595  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 16:46:50.595  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.595 10976 11600 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 16:46:50.595  5849  6155 D BtGatt.GattService: registerClient() - UUID=3c937655-ec03-4f22-ba8f-004fd79c3444
03-21 16:46:50.600 10976 11600 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 16:46:50.600 10976 11600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1538)
03-21 16:46:50.600 10976 11600 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@39a5d38c, channel: 6, state: LISTENING
03-21 16:46:50.600 10976 11600 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@39a5d38c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32d55163, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c57ead5mSocket: android.net.LocalSocket@30ba12ea impl:android.net.LocalSocketImpl@3bf989db fd:FileDescriptor[93]
,03-21 16:46:50.600 10976 11600 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@30ba12ea impl:android.net.LocalSocketImpl@3bf989db fd:FileDescriptor[93]
03-21 16:46:50.600 10976 11600 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:50.600 10976 11646 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1538)
,03-21 16:46:50.600 10976 11600 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:46:50.600 10976 11600 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:50.605 10976 11600 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,03-21 16:46:50.605 10976 11600 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:50.605 10976 11600 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:46:50.605 10976 11600 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ba29c78
03-21 16:46:50.605 10976 11600 D BluetoothSocket: channel: 6
03-21 16:46:50.605 10976 11600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:46:50.640  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=3c937655-ec03-4f22-ba8f-004fd79c3444, clientIf=6
,03-21 16:46:50.640 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:50.640  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:46:50.650  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 58
,03-21 16:46:50.650  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:50.650  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:50.650 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 16:46:50.650  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:46:50.650 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:46:50.650  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:46:50.655  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:50.655  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 16:46:50.655  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:50.655  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-21 16:46:50.655  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:50.655  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:50.655  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:50.655  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:46:50.655  5849  5920 D BtGatt.GattService: Client app is not null!
,03-21 16:46:50.655  5849  5949 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-21 16:46:50.660  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:46:50.660  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:50.660  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.660  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:50.660  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:50.660  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
,03-21 16:46:50.660 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:50.660  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:50.665 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 16:46:50.665 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:46:50.665 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 16:46:50.665 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:50.665 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:50.665 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:50.665 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:50.665 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:46:50.665  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:50.665  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:50.675  5849  5857 D BtGatt.GattService: registerClient() - UUID=1532dc50-0365-4f1b-a75e-743d39ad397a
,03-21 16:46:50.715  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=1532dc50-0365-4f1b-a75e-743d39ad397a, clientIf=7
,03-21 16:46:50.715 10976 10986 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:50.730  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 48
,03-21 16:46:50.730  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:50.730  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:50.730  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:50.730  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:50.730  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:50.735  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:50.735  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:50.735  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:50.735  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:46:50.735  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 16:46:50.735 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:46:50.740  5849  6155 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:50.740  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:50.740  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 4
,03-21 16:46:50.740  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:50.740 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:50.740 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:50.740 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:50.740 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:50.740 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:50.740 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:46:50.740  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:50.740  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.740  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:50.745  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 16:46:50.745  5849  5857 D BtGatt.GattService: registerClient() - UUID=16e86a58-f331-4522-87d4-1e16f1d33661
03-21 16:46:50.745  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.745  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:50.745  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:50.745  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:50.785  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=16e86a58-f331-4522-87d4-1e16f1d33661, clientIf=6
,03-21 16:46:50.790 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:50.790  5849  5861 D BtGatt.GattService: start scan with filters
,03-21 16:46:50.825  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 59
03-21 16:46:50.835 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:50.835 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:50.835 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 16:46:50.835 10976 10976 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-21 16:46:50.835 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:50.835 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:50.835 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:46:50.835 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:50.835 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:50.835  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:50.835  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:50.835  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:50.855  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 16:46:50.860  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:50.860  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:50.860  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:50.860 10976 11646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1538),
,03-21 16:46:50.870  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,03-21 16:46:50.870  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.870 10976 11646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:46:50.875  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 16:46:50.875  5849  5999 D IOP_DB_BT: db_query: result 1,
03-21 16:46:50.875  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:50.875  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:50.875  5849  5949 D BtGatt.ScanManager: allow scan with filters
,03-21 16:46:50.875  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:50.875  5849  5949 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,03-21 16:46:50.880  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
03-21 16:46:50.880  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:50.885  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:50.885  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:46:50.890  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:50.890  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:50.895  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:50.895  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:50.895 10976 11657 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1537)
03-21 16:46:50.895 10976 11657 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44766
03-21 16:46:50.895 10976 11657 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-21 16:46:50.895 10976 11657 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 44766 (peer ID: F8:95:C7:87:3C:51)
,03-21 16:46:50.905 10976 11646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1538)
03-21 16:46:50.905 10976 11646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1538
03-21 16:46:50.905 10976 11646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1538)
03-21 16:46:50.905 10976 11646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:46:50.910 10976 11646 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1538)
03-21 16:46:50.910 10976 10976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 16:46:50.910 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 16:46:50.910 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1,
03-21 16:46:50.915 10976 10976 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 16:46:50.920 10976 10976 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 16:46:50.920 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-21 16:46:50.920 10976 10976 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-21 16:46:50.920 10976 11657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-21 16:46:50.925 10976 11040 I jxcore-log: INFO testThaliMobileNative: 
03-21 16:46:50.925 10976 11040 I jxcore-log: 
,03-21 16:46:50.925 10976 11040 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-21 16:46:50.925 10976 11040 I jxcore-log: 
03-21 16:46:50.930 10976 11658 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1539)
03-21 16:46:50.935  2876  3383 D EnterpriseController: netId is 0
03-21 16:46:50.935  2876  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 16:46:50.935 10976 11657 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 44766,
03-21 16:46:50.935 10976 11657 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-21 16:46:50.940 10976 11657 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes,
03-21 16:46:50.940 10976 11657 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 16:46:50.940 10976 11657 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1537)
03-21 16:46:50.940 10976 11657 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1537)
03-21 16:46:50.940 10976 11040 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-21 16:46:50.940 10976 11040 I jxcore-log: 
,03-21 16:46:50.945 10976 11658 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 32849
03-21 16:46:50.945 10976 11658 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,03-21 16:46:50.945 10976 11658 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 16:46:50.945 10976 11658 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 16:46:50.945 10976 11658 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1539)
03-21 16:46:50.945 10976 11658 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1539)
,03-21 16:46:50.950 10976 11660 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1540, name: Sender),
,03-21 16:46:50.950  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:50.950  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:46:50.950  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 16:46:50.950  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:50.955 10976 11661 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1541, name: Receiver)
03-21 16:46:50.960 10976 11663 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1543, name: Receiver)
,03-21 16:46:50.960 10976 11662 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1542, name: Sender)
,03-21 16:46:51.000  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.000  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.000  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.000  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.005  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.005  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.005  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.005  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.070  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.070  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.070  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.070  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.070  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.070  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.070  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.075  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.140  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.140  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.140  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.140  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.145  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.145  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.145  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.145  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.210  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.210  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.210  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.210  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.220  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.225  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.225  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.225  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.270  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.270  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.270  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.280  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.280  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.285  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.285  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.285  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.300  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.300  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.300  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.300  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.310 10976 11040 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 16:46:51.310 10976 11040 I jxcore-log: 
,03-21 16:46:51.350  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.350  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.350  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.350  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.360 10976 11040 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 16:46:51.360 10976 11040 I jxcore-log: 
,03-21 16:46:51.530  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.535  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.535  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.535  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:46:51.555 10976 11040 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 16:46:51.555 10976 11040 I jxcore-log: 
,03-21 16:46:51.670  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.670  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.670  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.670  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.670  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.675  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:46:51.680  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 16:46:51.680  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:46:51.700 10976 11040 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 16:46:51.700 10976 11040 I jxcore-log: 
,03-21 16:46:51.705 10976 11040 I jxcore-log: ok 169 received should match sent forward
03-21 16:46:51.705 10976 11040 I jxcore-log: 
,03-21 16:46:51.715 10976 11040 I jxcore-log: # setup
03-21 16:46:51.715 10976 11040 I jxcore-log: 
,03-21 16:46:51.805 10976 11662 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1542, thread name: Sender)
03-21 16:46:51.805 10976 11662 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 16:46:51.805 10976 11662 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 16:46:51.805 10976 11662 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1539
03-21 16:46:51.805 10976 11662 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1539)
03-21 16:46:51.805 10976 11662 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f9e73b6, channel: 6, state: CONNECTED
03-21 16:46:51.805 10976 11662 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1f9e73b6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@327ce8b7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a10824mSocket: android.net.LocalSocket@1ee39f8d impl:android.net.LocalSocketImpl@35961542 fd:FileDescriptor[91]
03-21 16:46:51.805 10976 11662 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ee39f8d impl:android.net.LocalSocketImpl@35961542 fd:FileDescriptor[91]
03-21 16:46:51.805 10976 11662 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f9e73b6, channel: 6, state: CLOSED
03-21 16:46:51.805 10976 11662 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f9e73b6, channel: 6, state: CLOSED
03-21 16:46:51.805 10976 11662 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 16:46:51.805 10976 11662 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-21 16:46:51.805 10976 11662 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1543
03-21 16:46:51.805 10976 11662 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-21 16:46:51.805 10976 11662 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1542
03-21 16:46:51.805 10976 11662 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1539)
03-21 16:46:51.805 10976 11662 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1539)
03-21 16:46:51.805 10976 11662 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-21 16:46:51.805 10976 11663 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1543, thread name: Receiver): bt socket closed, read return: -1,
03-21 16:46:51.805 10976 11663 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1543, name: Receiver)
,03-21 16:46:51.810  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:46:51.810  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:46:51.810  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:46:51.810  5849  5999 D IOP_DB_BT: db_query: result 1,
03-21 16:46:51.815 10976 11662 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1542, name: Sender)
,03-21 16:46:51.815 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:51.815 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 16:46:51.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 16:46:51.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:51.825  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
03-21 16:46:51.825  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:51.825  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 5
03-21 16:46:51.825  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:46:51.825  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:51.825  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:46:51.825  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:51.825  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:51.830  5849 11643 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:51.830  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:51.830  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:51.830  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:51.835 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 16:46:51.835 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 16:46:51.835 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:51.835 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-21 16:46:51.835 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:46:51.835 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 16:46:51.835 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 16:46:51.835 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 16:46:51.835 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:51.840 10976 11040 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 16:46:51.840 10976 11040 I jxcore-log: 
,03-21 16:46:51.840 10976 11040 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 16:46:51.840 10976 11040 I jxcore-log: 
,03-21 16:46:51.845 10976 11040 I jxcore-log: ok 170 Should be able to call stopListeningForAdvertisments in teardown
03-21 16:46:51.845 10976 11040 I jxcore-log: 
,03-21 16:46:51.845 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:51.845 10976 11040 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-21 16:46:51.845 10976 11040 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1537)
,03-21 16:46:51.845 10976 11040 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1537)
,03-21 16:46:51.850 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e6d5953, channel: 7, state: CONNECTED
03-21 16:46:51.850 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e6d5953, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ef88290, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22f7a789mSocket: android.net.LocalSocket@3574438e impl:android.net.LocalSocketImpl@3cea37af fd:FileDescriptor[112]
,03-21 16:46:51.850 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3574438e impl:android.net.LocalSocketImpl@3cea37af fd:FileDescriptor[112]
,03-21 16:46:51.850 10976 11661 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1541, thread name: Receiver): bt socket closed, read return: -1
03-21 16:46:51.850 10976 11661 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1541, name: Receiver)
,03-21 16:46:51.850 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e6d5953, channel: 7, state: CLOSED
,03-21 16:46:51.850 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e6d5953, channel: 7, state: CLOSED
03-21 16:46:51.850 10976 11040 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-21 16:46:51.855 10976 11040 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-21 16:46:51.855 10976 11040 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1541
,03-21 16:46:51.855 10976 11040 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-21 16:46:51.855 10976 11040 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1540
03-21 16:46:51.855 10976 11040 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1537)
,03-21 16:46:51.855 10976 11660 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1540, thread name: Sender): Socket closed,
03-21 16:46:51.855 10976 11660 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1540, name: Sender)
,03-21 16:46:51.855 10976 11040 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1537)
,03-21 16:46:51.855 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-21 16:46:51.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:51.860 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 16:46:51.860 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 16:46:51.860 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d0b37bc, channel: 6, state: LISTENING
,03-21 16:46:51.860 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d0b37bc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ba29c78, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@102a3345mSocket: android.net.LocalSocket@29f50a9a impl:android.net.LocalSocketImpl@13ac9fcb fd:FileDescriptor[113]
,03-21 16:46:51.860 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29f50a9a impl:android.net.LocalSocketImpl@13ac9fcb fd:FileDescriptor[113]
,03-21 16:46:51.860 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-21 16:46:51.860 10976 11600 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 16:46:51.860 10976 11600 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:51.860 10976 11600 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-21 16:46:51.860 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 16:46:51.865 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 16:46:51.865 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-21 16:46:51.865 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 16:46:51.865 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-21 16:46:51.865 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:51.865 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:51.865 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 16:46:51.865 10976 11040 D BluetoothLeScanner: could not find callback wrapper,
03-21 16:46:51.865 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 16:46:51.865 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
,03-21 16:46:51.870  5849  5948 D BtGatt.AdvertiseManager: message : 1,
,03-21 16:46:51.870  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-21 16:46:51.870  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:51.870  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:51.875  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-21 16:46:51.875  5849  5920 D BtGatt.GattService: Client app is not null!,
03-21 16:46:51.875  5849 11643 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-21 16:46:51.880 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 16:46:51.880 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:51.880 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:46:51.880 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-21 16:46:51.880 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:51.880 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:51.880 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:51.880 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,03-21 16:46:51.880 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-21 16:46:51.880 10976 11040 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 16:46:51.880 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:51.880 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:51.880 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:51.880 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:51.880 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:51.880 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-21 16:46:51.890 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:51.895 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:46:51.895 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:51.895 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:51.900 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:46:51.900 10976 11040 I jxcore-log: 
03-21 16:46:51.910 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:51.910 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:51.910 10976 11040 I jxcore-log: ok 171 Should be able to call stopAdvertisingAndListening in teardown
03-21 16:46:51.910 10976 11040 I jxcore-log: 
,03-21 16:46:51.915 10976 11040 I jxcore-log: # 39. #startListeningForAdvertisements should fail if start not called
03-21 16:46:51.915 10976 11040 I jxcore-log: 
,03-21 16:46:51.920 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:51.920 10976 11040 I jxcore-log: 
,03-21 16:46:51.925 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:51.925 10976 11040 I jxcore-log: 
,03-21 16:46:52.000 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:52.000 10976 11040 I jxcore-log: 
,03-21 16:46:52.005 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:52.005 10976 11040 I jxcore-log: 
,03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:52.015 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:52.020 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:52.020 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:52.020 10976 11040 I jxcore-log: 
,03-21 16:46:52.030 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:52.030 10976 11040 I jxcore-log: 
,03-21 16:46:52.040 10976 11040 I jxcore-log: # teardown
03-21 16:46:52.040 10976 11040 I jxcore-log: 
,03-21 16:46:52.040 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:52.040 10976 11040 I jxcore-log: 
,03-21 16:46:52.155 10976 11040 I jxcore-log: ok 172 specific error should be returned
03-21 16:46:52.155 10976 11040 I jxcore-log: 
,03-21 16:46:52.160 10976 11040 I jxcore-log: # setup
03-21 16:46:52.160 10976 11040 I jxcore-log: 
,03-21 16:46:52.260 10976 11040 I jxcore-log: # 40. #startUpdateAdvertisingAndListening should fail if start not called
03-21 16:46:52.260 10976 11040 I jxcore-log: 
,03-21 16:46:52.350 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:52.350 10976 11040 I jxcore-log: 
,03-21 16:46:52.355 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:52.355 10976 11040 I jxcore-log: 
,03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:52.365 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:52.370 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:52.370 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:52.370 10976 11040 I jxcore-log: 
,03-21 16:46:52.375 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:52.375 10976 11040 I jxcore-log: 
,03-21 16:46:52.380 10976 11040 I jxcore-log: # teardown
03-21 16:46:52.380 10976 11040 I jxcore-log: 
,03-21 16:46:52.380  5849  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
03-21 16:46:52.380  5849  5999 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-21 16:46:52.380  5849  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-21 16:46:52.385 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:52.385 10976 11040 I jxcore-log: 
,03-21 16:46:52.440 10976 11040 I jxcore-log: ok 173 specific error should be returned
03-21 16:46:52.440 10976 11040 I jxcore-log: 
,03-21 16:46:52.445 10976 11040 I jxcore-log: # setup
03-21 16:46:52.445 10976 11040 I jxcore-log: 
,03-21 16:46:52.585 10976 11040 I jxcore-log: # 41. should be able to call #stopListeningForAdvertisements many times
03-21 16:46:52.585 10976 11040 I jxcore-log: 
,03-21 16:46:52.680 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:52.680 10976 11040 I jxcore-log: 
,03-21 16:46:52.685 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:52.685 10976 11040 I jxcore-log: 
,03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:52.695 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:52.700 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:52.700 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:52.700 10976 11040 I jxcore-log: 
,03-21 16:46:52.705 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:52.705 10976 11040 I jxcore-log: 
,03-21 16:46:52.710 10976 11040 I jxcore-log: # teardown
03-21 16:46:52.710 10976 11040 I jxcore-log: 
,03-21 16:46:52.715 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:52.715 10976 11040 I jxcore-log: 
,03-21 16:46:52.830 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:52.830 10976 11040 I jxcore-log: 
,03-21 16:46:52.835 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 45756
03-21 16:46:52.835 10976 11040 I jxcore-log: 
,03-21 16:46:52.840 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:52.840 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:52.840 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:52.845 10976 11040 I jxcore-log: ok 174 no errors
03-21 16:46:52.845 10976 11040 I jxcore-log: 
,03-21 16:46:52.845 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:52.845 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:52.845 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:52.850 10976 11040 I jxcore-log: ok 175 still no errors
03-21 16:46:52.850 10976 11040 I jxcore-log: 
,03-21 16:46:52.860 10976 11040 I jxcore-log: # setup
03-21 16:46:52.860 10976 11040 I jxcore-log: 
,03-21 16:46:52.925 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 16:46:52.925 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:52.925 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:52.930 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:52.930 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:52.930 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:52.940 10976 11040 I jxcore-log: # 42. should be able to call #startListeningForAdvertisements many times
03-21 16:46:52.940 10976 11040 I jxcore-log: 
,03-21 16:46:53.060 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:53.060 10976 11040 I jxcore-log: 
,03-21 16:46:53.065 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:53.065 10976 11040 I jxcore-log: 
,03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:53.070 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:53.075 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:53.080 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:53.080 10976 11040 I jxcore-log: 
,03-21 16:46:53.085 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:53.085 10976 11040 I jxcore-log: 
,03-21 16:46:53.090 10976 11040 I jxcore-log: # teardown
03-21 16:46:53.090 10976 11040 I jxcore-log: 
,03-21 16:46:53.090 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:53.090 10976 11040 I jxcore-log: 
,03-21 16:46:53.155 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:53.155 10976 11040 I jxcore-log: 
,03-21 16:46:53.155 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 50677
03-21 16:46:53.155 10976 11040 I jxcore-log: 
,03-21 16:46:53.160 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 32849, start advertisements: false
03-21 16:46:53.160 10976 11040 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectab,le: false
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:53.160 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:53.160 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:53.160 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 16:46:53.165 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:53.165 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 16:46:53.165 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:53.170  5849 11643 D BtGatt.GattService: registerClient() - UUID=c48584f6-d206-4081-806a-fa6975614150
,03-21 16:46:53.210  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=c48584f6-d206-4081-806a-fa6975614150, clientIf=6
,03-21 16:46:53.210 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:53.210  5849  6155 D BtGatt.GattService: start scan with filters
,03-21 16:46:53.265  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 60
,03-21 16:46:53.270  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:53.275  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:53.275  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:53.275  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:53.275  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:53.280  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:53.280  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:53.280  5849  5949 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-21 16:46:53.280  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:53.280  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:53.280  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:53.280  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:53.285  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:53.285  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:53.285  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
,03-21 16:46:53.285  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 16:46:53.295 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 16:46:53.295 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:53.295 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:53.295 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
03-21 16:46:53.295 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:53.295 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 16:46:53.295 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:53.295 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:53.295 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:53.295 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 16:46:53.295 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:53.295 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:53.295 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:53.300 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:53.300 10976 11040 I jxcore-log: 
03-21 16:46:53.300 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:53.300 10976 11040 I jxcore-log: 
,03-21 16:46:53.305 10976 11040 I jxcore-log: ok 176 no errors
03-21 16:46:53.305 10976 11040 I jxcore-log: 
,03-21 16:46:53.310 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 32849, start advertisements: false
,03-21 16:46:53.315 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:53.315 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:53.315 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:53.315 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:53.315 10976 11040 I jxcore-log: ok 177 still no errors
03-21 16:46:53.315 10976 11040 I jxcore-log: 
,03-21 16:46:53.325 10976 11040 I jxcore-log: # setup
03-21 16:46:53.325 10976 11040 I jxcore-log: 
,03-21 16:46:53.495 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:53.495 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:53.495 10976 11040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 16:46:53.500 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 16:46:53.500 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:53.500 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-21 16:46:53.500 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 16:46:53.500 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-21 16:46:53.500 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:53.505  5849  5861 D BtGatt.GattService: stopScan() - queue size =1,
03-21 16:46:53.505  5849  5949 D BtGatt.ScanManager: filter size is 1
,03-21 16:46:53.505  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 6,
,03-21 16:46:53.505  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 16:46:53.505  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:53.505  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:53.510  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 16:46:53.515  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:53.515  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:46:53.515  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:53.515  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 16:46:53.520  5849 11643 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:53.525 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 16:46:53.525 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:53.525 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-21 16:46:53.525 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:53.530 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:53.530 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:53.530 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 16:46:53.535 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 16:46:53.540 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:46:53.540 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:53.540 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,03-21 16:46:53.550 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-21 16:46:53.550 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:53.550 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:46:53.550 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:53.550 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:53.550 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:53.550 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:53.550 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:53.550 10976 11040 I jxcore-log: 
,03-21 16:46:53.555 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:53.555 10976 11040 I jxcore-log: 
,03-21 16:46:53.570 10976 11040 I jxcore-log: # 43. should be able to call #startUpdateAdvertisingAndListening many times
03-21 16:46:53.570 10976 11040 I jxcore-log: 
,03-21 16:46:53.640 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:53.640 10976 11040 I jxcore-log: 
,03-21 16:46:53.640 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:53.640 10976 11040 I jxcore-log: 
,03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:53.645 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:53.650 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:53.650 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:53.650 10976 11040 I jxcore-log: 
,03-21 16:46:53.650 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:53.650 10976 11040 I jxcore-log: 
,03-21 16:46:53.655 10976 11040 I jxcore-log: # teardown
03-21 16:46:53.655 10976 11040 I jxcore-log: 
,03-21 16:46:53.660 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:53.660 10976 11040 I jxcore-log: 
,03-21 16:46:53.790 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:53.790 10976 11040 I jxcore-log: 
,03-21 16:46:53.800 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 58769
03-21 16:46:53.800 10976 11040 I jxcore-log: 
,03-21 16:46:53.810 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 58769, start advertisements: true
03-21 16:46:53.810 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:53.810 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:53.810 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:53.810 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-21 16:46:53.810 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:53.810 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:53.810 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:53.815  5849 11643 D BtGatt.GattService: registerClient() - UUID=7d700704-06ea-4ee6-bf67-7e7b6f0300ac
,03-21 16:46:53.855  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=7d700704-06ea-4ee6-bf67-7e7b6f0300ac, clientIf=6
,03-21 16:46:53.855 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:46:53.855  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:46:53.870  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 61
,03-21 16:46:53.870 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:46:53.870 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:46:53.870 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-21 16:46:53.870 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:46:53.870  5849  5949 D BtGatt.ScanManager: handling starting scan
,03-21 16:46:53.870 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:53.870  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:53.870  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:53.870 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:53.870 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:53.870 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:53.870 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 16:46:53.870 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 16:46:53.870 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:53.870 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:46:53.875  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:53.875  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:53.875  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:53.875  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 16:46:53.875  5849  5949 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-21 16:46:53.880  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:53.880  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:53.880  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:46:53.880  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:46:53.880  5849  5857 D BtGatt.GattService: registerClient() - UUID=61225574-7f64-4d27-a53a-c3d8d4203fa4
03-21 16:46:53.880  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:53.880  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:53.885  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:53.885  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:53.920  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=61225574-7f64-4d27-a53a-c3d8d4203fa4, clientIf=7
,03-21 16:46:53.920 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:53.940  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 49
,03-21 16:46:53.940  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:53.940  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:53.940  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:53.945  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:53.945  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:53.950  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:53.955  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:53.955  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:53.960  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 16:46:53.960  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 16:46:53.960 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:53.960 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:46:53.960 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:53.960 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:53.960 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:46:53.960 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:46:53.965 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-21 16:46:53.965 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:53.965 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-21 16:46:53.965 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 16:46:53.965 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:53.965 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:46:53.965 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:46:53.965 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-21 16:46:53.965 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:46:53.965 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:46:53.965 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:53.965 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:53.965 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 16:46:53.965 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:53.965 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 16:46:53.965 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:46:53.965 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:46:53.970 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:53.970 10976 11040 I jxcore-log: 
,03-21 16:46:53.970 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:53.970 10976 11040 I jxcore-log: 
03-21 16:46:53.970 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:53.970 10976 11040 I jxcore-log: 
,03-21 16:46:53.980 10976 11715 D BluetoothSocket: bindListen(): myUserId = 0,
03-21 16:46:53.980 10976 11715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:53.985 10976 11715 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]},
03-21 16:46:53.985 10976 11715 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:53.985 10976 11715 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 16:46:53.985 10976 11715 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16e252f2
03-21 16:46:53.985 10976 11715 D BluetoothSocket: channel: 6
03-21 16:46:53.985 10976 11715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:46:53.985 10976 11040 I jxcore-log: ok 178 no errors
03-21 16:46:53.985 10976 11040 I jxcore-log: 
,03-21 16:46:53.990 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 58769, start advertisements: true
,03-21 16:46:53.990 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 16:46:53.995 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:53.995 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:53.995 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:54.000 10976 11040 I jxcore-log: ok 179 still no errors
03-21 16:46:54.000 10976 11040 I jxcore-log: 
,03-21 16:46:54.005 10976 11040 I jxcore-log: # setup
03-21 16:46:54.005 10976 11040 I jxcore-log: 
,03-21 16:46:54.050 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 16:46:54.050 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 16:46:54.050 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:54.050 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 16:46:54.050 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 16:46:54.050 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@ccf3d43, channel: 6, state: LISTENING
03-21 16:46:54.050 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@ccf3d43, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16e252f2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3db9afc0mSocket: android.net.LocalSocket@a1c84f9 impl:android.net.LocalSocketImpl@103eac3e fd:FileDescriptor[112]
03-21 16:46:54.050 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a1c84f9 impl:android.net.LocalSocketImpl@103eac3e fd:FileDescriptor[112]
03-21 16:46:54.050 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:54.050 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:46:54.050 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:54.050 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:54.050 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:54.050 10976 11715 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 16:46:54.050 10976 11715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:54.050 10976 11715 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 16:46:54.050 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:46:54.050 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:54.055  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:46:54.055  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:54.055  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 7
,03-21 16:46:54.055  5849 11643 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:54.055  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 16:46:54.055  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:54.055  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:54.055 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:54.055 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 16:46:54.055 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:46:54.055 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:46:54.055 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:46:54.055 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:54.055 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 16:46:54.060  5849  5948 D BtGatt.AdvertiseManager: message : 1
,03-21 16:46:54.060  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:54.060  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:46:54.060  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:54.060  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:54.060  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:54.060  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 16:46:54.060  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 16:46:54.060  5849  5920 D BtGatt.GattService: Client app is not null!
,03-21 16:46:54.060  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:46:54.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:54.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:54.065 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:46:54.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-21 16:46:54.065 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:54.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:54.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:54.065  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:46:54.065  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:54.065  5849  5920 D BtGatt.GattService: current time is 245042012028
03-21 16:46:54.065  5849  5920 D BtGatt.GattService: Batch record : [12, -79, -12, 77, 90, 77, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:46:54.065  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-21 16:46:54.065  5849  5920 D ScanRecord: parseFromBytes
03-21 16:46:54.065 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 16:46:54.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:54.065 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:54.065 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:54.065 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:54.065 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:46:54.070 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:54.075 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:54.075 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:54.075 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:54.075 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 16:46:54.080 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:46:54.080 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:54.080 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:54.080 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:54.080 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:54.080 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:54.080 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 16:46:54.080 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:54.080 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:54.080 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:54.080 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:46:54.080 10976 11040 I jxcore-log: 
,03-21 16:46:54.080 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:54.080 10976 11040 I jxcore-log: 
,03-21 16:46:54.085 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:54.085 10976 11040 I jxcore-log: 
,03-21 16:46:54.095 10976 11040 I jxcore-log: # 44. should be able to call #stopAdvertisingAndListening many times
03-21 16:46:54.095 10976 11040 I jxcore-log: 
,03-21 16:46:54.230 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:54.230 10976 11040 I jxcore-log: 
,03-21 16:46:54.230 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:54.230 10976 11040 I jxcore-log: 
,03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:54.240 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:54.245 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:54.250 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:54.250 10976 11040 I jxcore-log: 
,03-21 16:46:54.260 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:54.260 10976 11040 I jxcore-log: 
,03-21 16:46:54.265 10976 11040 I jxcore-log: # teardown
03-21 16:46:54.265 10976 11040 I jxcore-log: 
,03-21 16:46:54.270 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:54.270 10976 11040 I jxcore-log: 
,03-21 16:46:54.370 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:54.370 10976 11040 I jxcore-log: 
,03-21 16:46:54.375 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 51124
03-21 16:46:54.375 10976 11040 I jxcore-log: 
,03-21 16:46:54.380 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:54.380 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:54.380 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:54.385 10976 11040 I jxcore-log: ok 180 no errors
03-21 16:46:54.385 10976 11040 I jxcore-log: 
,03-21 16:46:54.385 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:54.390 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:54.390 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:54.395 10976 11040 I jxcore-log: ok 181 still no errors
03-21 16:46:54.395 10976 11040 I jxcore-log: 
,03-21 16:46:54.400 10976 11040 I jxcore-log: # setup
03-21 16:46:54.400 10976 11040 I jxcore-log: 
,03-21 16:46:54.475  3390  3583 I PowerManagerService: [PWL] Off : 180s ago
03-21 16:46:54.475  3390  3583 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-21 16:46:54.475  3390  3583 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-21 16:46:54.475  3390  3583 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5849, ws=null) (elapsedTime=3823)
,03-21 16:46:54.480 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:54.480 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:46:54.480 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:54.485 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:54.485 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 16:46:54.490 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:54.500 10976 11040 I jxcore-log: # 45. can get the network status before starting
03-21 16:46:54.500 10976 11040 I jxcore-log: 
,03-21 16:46:54.645 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:54.645 10976 11040 I jxcore-log: 
,03-21 16:46:54.650 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:54.650 10976 11040 I jxcore-log: 
,03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:54.660 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:54.660 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:54.665 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:54.665 10976 11040 I jxcore-log: 
,03-21 16:46:54.670 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:54.670 10976 11040 I jxcore-log: 
,03-21 16:46:54.680 10976 11040 I jxcore-log: # teardown
03-21 16:46:54.680 10976 11040 I jxcore-log: 
,03-21 16:46:54.700 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:54.700 10976 11040 I jxcore-log: 
,03-21 16:46:54.805  3390  4007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 16:46:54.805  3390  4007 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:46:54.805  3390  4007 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
03-21 16:46:54.805  3390  4007 D BatteryService: stay LED for fully charged
03-21 16:46:54.805  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:46:54.810  3390  3390 I MotionRecognitionService: Plugged
03-21 16:46:54.810  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:46:54.810  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:46:54.810  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:46:54.815  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:46:54.815  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:46:54.815  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:46:54.820  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:46:54.820  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:46:54.835  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:46:54.835  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:54.835  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:46:54.835  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:46:54.845 10976 11040 I jxcore-log: ok 182 network status should have certain non-empty properties
03-21 16:46:54.845 10976 11040 I jxcore-log: 
,03-21 16:46:54.850 10976 11040 I jxcore-log: # setup
03-21 16:46:54.850 10976 11040 I jxcore-log: 
,03-21 16:46:54.950 10976 11040 I jxcore-log: # 46. error returned with bad router
03-21 16:46:54.950 10976 11040 I jxcore-log: 
,03-21 16:46:55.025 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:55.025 10976 11040 I jxcore-log: 
,03-21 16:46:55.030 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:55.030 10976 11040 I jxcore-log: 
,03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:55.035 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:55.040 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:55.045 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:55.045 10976 11040 I jxcore-log: 
,03-21 16:46:55.050 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:55.050 10976 11040 I jxcore-log: 
,03-21 16:46:55.055 10976 11040 I jxcore-log: # teardown
03-21 16:46:55.055 10976 11040 I jxcore-log: 
,03-21 16:46:55.055 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:55.055 10976 11040 I jxcore-log: 
,03-21 16:46:55.085  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:12), CUR = 37, LCD = 0
,03-21 16:46:55.225 10976 11040 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-21 16:46:55.225 10976 11040 I jxcore-log: 
,03-21 16:46:55.230 10976 11040 I jxcore-log: ok 183 specific error expected
03-21 16:46:55.230 10976 11040 I jxcore-log: 
,03-21 16:46:55.235 10976 11040 I jxcore-log: # setup
03-21 16:46:55.235 10976 11040 I jxcore-log: 
,03-21 16:46:55.325 10976 11040 I jxcore-log: # 47. all services are stopped when we call stop
03-21 16:46:55.325 10976 11040 I jxcore-log: 
,03-21 16:46:55.460 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:55.460 10976 11040 I jxcore-log: 
,03-21 16:46:55.460 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:55.460 10976 11040 I jxcore-log: 
,03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:55.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:55.475 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:55.480 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:55.480 10976 11040 I jxcore-log: 
,03-21 16:46:55.480 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:55.480 10976 11040 I jxcore-log: 
,03-21 16:46:55.485 10976 11040 I jxcore-log: # teardown
03-21 16:46:55.485 10976 11040 I jxcore-log: 
,03-21 16:46:55.490 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:55.490 10976 11040 I jxcore-log: 
,03-21 16:46:55.600 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:55.600 10976 11040 I jxcore-log: 
,03-21 16:46:55.605 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 46781
03-21 16:46:55.605 10976 11040 I jxcore-log: 
,03-21 16:46:55.615 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 58769, start advertisements: false
,03-21 16:46:55.615 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:55.615 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:55.615 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 16:46:55.620 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:46:55.620 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:46:55.620 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:46:55.630  5849 11643 D BtGatt.GattService: registerClient() - UUID=9841e58e-0708-405d-bdf5-f01adb6d8431
,03-21 16:46:55.670  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=9841e58e-0708-405d-bdf5-f01adb6d8431, clientIf=6
03-21 16:46:55.670 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:46:55.675  5849  5857 D BtGatt.GattService: start scan with filters,
,03-21 16:46:55.705  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 62
,03-21 16:46:55.710  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:46:55.710  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:46:55.710  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:46:55.710  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:46:55.715  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:55.715  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:46:55.715  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:46:55.715  5849  5949 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-21 16:46:55.715  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:46:55.715  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:55.720  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 16:46:55.720  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
03-21 16:46:55.720  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:46:55.720  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:55.725  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:46:55.725  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:46:55.730 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-21 16:46:55.730 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-21 16:46:55.730 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:46:55.730 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-21 16:46:55.730 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:55.730 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:46:55.730 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:46:55.735 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:55.735 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:46:55.735 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:55.735 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:46:55.735 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:55.735 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:46:55.740 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:55.740 10976 11040 I jxcore-log: 
03-21 16:46:55.740 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:46:55.740 10976 11040 I jxcore-log: 
,03-21 16:46:55.745 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 46781, start advertisements: true
,03-21 16:46:55.745 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:46:55.745 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:46:55.750 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:46:55.750 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:46:55.750 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-21 16:46:55.750 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:46:55.750 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:46:55.750 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:46:55.750 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:55.755 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:46:55.755 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:46:55.755  5849  6155 D BtGatt.GattService: registerClient() - UUID=7a983e13-32a7-4f51-b6f7-ae04c248b8ea
,03-21 16:46:55.800  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=7a983e13-32a7-4f51-b6f7-ae04c248b8ea, clientIf=7
,03-21 16:46:55.800 10976 10988 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:46:55.835  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 50
,03-21 16:46:55.835  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:46:55.840  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:46:55.840  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:46:55.855  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:46:55.855  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:46:55.860  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:46:55.865  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:46:55.880  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:46:55.880  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 16:46:55.885  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 16:46:55.890 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
,03-21 16:46:55.890 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:46:55.890 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,03-21 16:46:55.895 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING,
03-21 16:46:55.895 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-21 16:46:55.895 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-21 16:46:55.895 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 16:46:55.925 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 16:46:55.925 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,03-21 16:46:55.930 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
,03-21 16:46:55.930 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
,03-21 16:46:55.930 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
03-21 16:46:55.935 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-21 16:46:55.940 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:46:55.945 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 16:46:55.945 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 16:46:55.945 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:46:55.945 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:55.945 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 16:46:55.945 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:46:55.960 10976 11754 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 16:46:55.960 10976 11754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:46:55.965 10976 11754 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-21 16:46:55.965 10976 11754 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:46:55.965 10976 11754 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 16:46:55.970 10976 11754 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f754e4a
,03-21 16:46:55.970 10976 11754 D BluetoothSocket: channel: 6
03-21 16:46:55.970 10976 11754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:46:55.970 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:46:55.970 10976 11040 I jxcore-log: 
,03-21 16:46:55.980 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:46:55.980 10976 11040 I jxcore-log: 
,03-21 16:46:55.985 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:46:55.985 10976 11040 I jxcore-log: 
,03-21 16:46:55.990 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:46:55.990 10976 11040 I jxcore-log: 
,03-21 16:46:55.995 10976 11040 I jxcore-log: ok 184 connection to servers manager should succeed after starting
03-21 16:46:55.995 10976 11040 I jxcore-log: 
,03-21 16:46:56.005 10976 11040 I jxcore-log: ok 185 connection to router server should succeed after starting
03-21 16:46:56.005 10976 11040 I jxcore-log: 
,03-21 16:46:56.010 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:56.010 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 16:46:56.010 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:46:56.010 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 16:46:56.010 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 16:46:56.010 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a0911bb, channel: 6, state: LISTENING
03-21 16:46:56.010 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a0911bb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f754e4a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3ae5b6d8mSocket: android.net.LocalSocket@1494da31 impl:android.net.LocalSocketImpl@10c20516 fd:FileDescriptor[112]
03-21 16:46:56.010 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1494da31 impl:android.net.LocalSocketImpl@10c20516 fd:FileDescriptor[112]
,03-21 16:46:56.015 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:46:56.015 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:46:56.015 10976 11754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 16:46:56.015 10976 11754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:46:56.015 10976 11754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 16:46:56.015 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:46:56.015 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:46:56.015 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 16:46:56.015 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:46:56.015 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 16:46:56.015 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:46:56.015 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:46:56.015 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:46:56.020  5849 11643 D BtGatt.GattService: stopScan() - queue size =1
03-21 16:46:56.020  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:46:56.020  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 8
,03-21 16:46:56.020  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:46:56.020  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 16:46:56.020  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:56.020 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:46:56.020 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:56.020 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 16:46:56.020 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:46:56.020 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:46:56.020  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:46:56.020 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:46:56.020 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 16:46:56.025  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:46:56.025  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:46:56.025  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 16:46:56.025  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:46:56.025  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:46:56.025  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:56.025  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:46:56.030  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 16:46:56.030  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:46:56.030  5849 11643 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:46:56.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:46:56.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:46:56.030 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:46:56.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 16:46:56.030 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:46:56.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:56.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:46:56.030 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:46:56.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:46:56.030 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:46:56.030  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:46:56.030  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:46:56.030 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:56.030 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:46:56.030 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:46:56.030 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:46:56.030 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:46:56.035 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:46:56.035 10976 11040 I jxcore-log: 
,03-21 16:46:56.035 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:46:56.035 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:46:56.035 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:56.035 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:56.040 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:46:56.040 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:46:56.040 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:46:56.045 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 16:46:56.045 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:46:56.045 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:46:56.045 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:46:56.045 10976 11040 I jxcore-log: 
,03-21 16:46:56.045 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:56.045 10976 11040 I jxcore-log: 
,03-21 16:46:56.050 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:46:56.050 10976 11040 I jxcore-log: 
,03-21 16:46:56.055 10976 11040 I jxcore-log: ok 186 is stopped after calling stop
03-21 16:46:56.055 10976 11040 I jxcore-log: 
,03-21 16:46:56.060 10976 11040 I jxcore-log: ok 187 connection to servers manager should fail after stopping
03-21 16:46:56.060 10976 11040 I jxcore-log: 
,03-21 16:46:56.065 10976 11040 I jxcore-log: ok 188 connection to router server should fail after stopping
03-21 16:46:56.065 10976 11040 I jxcore-log: 
,03-21 16:46:56.075 10976 11040 I jxcore-log: # setup
03-21 16:46:56.075 10976 11040 I jxcore-log: 
,03-21 16:46:56.175 10976 11040 I jxcore-log: # 48. make sure terminateConnection is properly hooked up
03-21 16:46:56.175 10976 11040 I jxcore-log: 
,03-21 16:46:57.015 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:57.015 10976 11040 I jxcore-log: 
,03-21 16:46:57.015 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:57.015 10976 11040 I jxcore-log: 
,03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:57.025 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:57.030 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:57.035 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:57.035 10976 11040 I jxcore-log: 
,03-21 16:46:57.035 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:57.035 10976 11040 I jxcore-log: 
,03-21 16:46:57.040 10976 11040 I jxcore-log: # teardown
03-21 16:46:57.040 10976 11040 I jxcore-log: 
,03-21 16:46:57.045 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:57.045 10976 11040 I jxcore-log: 
,03-21 16:46:57.195 10976 11040 I jxcore-log: ok 189 called with right arguments
03-21 16:46:57.195 10976 11040 I jxcore-log: 
,03-21 16:46:57.205 10976 11040 I jxcore-log: # setup
03-21 16:46:57.205 10976 11040 I jxcore-log: 
,03-21 16:46:57.930  5849  5999 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-21 16:46:57.930  5849  5999 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-21 16:46:57.930  5849  5999 W bt-btif : bta_dm_acl_change(), event : 1
03-21 16:46:57.930  5849  5999 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 16:46:57.930  5849  5920 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-21 16:46:57.955  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 16:46:57.960  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-21 16:46:57.970  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-21 16:46:57.970  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-21 16:46:57.970  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-21 16:46:57.990  3390  3576 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e7c9e10 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{140cc3b3 5849:com.android.bluetooth/1002}
03-21 16:46:57.990  3390  4730 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-21 16:46:57.995  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
,03-21 16:46:57.995  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a47f10c
03-21 16:46:57.995  5849  5849 D BtConfig.SecureMode: isSecureModeOn:false
,03-21 16:46:57.995  3390  4111 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-21 16:46:58.000  3390  4242 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-21 16:46:58.005 10183 11770 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-21 16:46:58.005  5849  5849 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-21 16:46:58.005 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-21 16:46:58.005 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-21 16:46:58.010  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:46:58.010  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:46:58.010  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:46:58.010  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:46:58.010 10183 10183 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-21 16:46:58.010 10183 10183 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-21 16:46:58.020 11771 11771 E Zygote  : MountEmulatedStorage()
03-21 16:46:58.020 11771 11771 E Zygote  : v2
03-21 16:46:58.020 11771 11771 I libpersona: KNOX_SDCARD checking this for 10036
03-21 16:46:58.020 11771 11771 I libpersona: KNOX_SDCARD not a persona
,03-21 16:46:58.025 11771 11771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:46:58.025 11771 11771 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:46:58.025 11771 11771 E Zygote  : accessInfo : 0
,03-21 16:46:58.025 11771 11771 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-21 16:46:58.025  3390  4730 I ActivityManager: Start proc 11771:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
,03-21 16:46:58.050 11771 11771 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:46:58.050 11771 11771 D ActivityThread: Added TimaKeyStore provider
,03-21 16:46:58.055  3390  3980 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e7c9e10 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:46:58.070 11771 11771 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 16:46:58.160 11771 11771 D HealthConsole: Service for HealthDataConsole is connected
,03-21 16:46:58.165  3390  4727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e7c9e10 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:46:58.185 11771 11771 D HealthConsole: Service for HealthDataConsole is connected
,03-21 16:46:58.190  3390  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e7c9e10 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:46:58.205  3390  4030 I ActivityManager: Killing 10094:com.facebook.system/u0a10 (adj 15): emptyCount ##31
,03-21 16:46:58.210  3390  4030 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1e7c9e10 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{c7a662d 4113:com.google.android.googlequicksearchbox:search/u0a64}
,03-21 16:46:58.225 10976 11040 I jxcore-log: # 49. make sure terminateListener is properly hooked up
03-21 16:46:58.225 10976 11040 I jxcore-log: 
,03-21 16:46:58.235  4113  4113 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-21 16:46:58.240  4113  4113 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-21 16:46:58.360 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:58.360 10976 11040 I jxcore-log: 
,03-21 16:46:58.365 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:58.365 10976 11040 I jxcore-log: 
,03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:58.375 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:58.380 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:58.380 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:58.380 10976 11040 I jxcore-log: 
,03-21 16:46:58.385 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:58.385 10976 11040 I jxcore-log: 
,03-21 16:46:58.390 10976 11040 I jxcore-log: # teardown
03-21 16:46:58.390 10976 11040 I jxcore-log: 
,03-21 16:46:58.390 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:58.390 10976 11040 I jxcore-log: 
,03-21 16:46:58.585 10976 11040 I jxcore-log: ok 190 called with right arguments
03-21 16:46:58.585 10976 11040 I jxcore-log: 
,03-21 16:46:58.590 10976 11040 I jxcore-log: # setup
03-21 16:46:58.590 10976 11040 I jxcore-log: 
,03-21 16:46:58.660  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:46:58.735 10976 11040 I jxcore-log: # 50. make sure we actually call kill connections properly
03-21 16:46:58.735 10976 11040 I jxcore-log: 
,03-21 16:46:58.905 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:58.905 10976 11040 I jxcore-log: 
,03-21 16:46:58.910 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:58.910 10976 11040 I jxcore-log: 
,03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:58.920 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:58.925 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:58.930 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:58.930 10976 11040 I jxcore-log: 
,03-21 16:46:58.930 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:58.930 10976 11040 I jxcore-log: 
,03-21 16:46:58.940 10976 11040 I jxcore-log: # teardown
03-21 16:46:58.940 10976 11040 I jxcore-log: 
,03-21 16:46:58.945 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:58.945 10976 11040 I jxcore-log: 
,03-21 16:46:59.170 10976 11040 I jxcore-log: ok 191 specific error expected
03-21 16:46:59.170 10976 11040 I jxcore-log: 
,03-21 16:46:59.175 10976 11040 I jxcore-log: # setup
03-21 16:46:59.175 10976 11040 I jxcore-log: 
,03-21 16:46:59.350 10976 11040 I jxcore-log: # 51. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-21 16:46:59.350 10976 11040 I jxcore-log: 
,03-21 16:46:59.545 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:59.545 10976 11040 I jxcore-log: 
,03-21 16:46:59.550 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:59.550 10976 11040 I jxcore-log: 
,03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:59.555 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:59.560 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:59.565 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:59.565 10976 11040 I jxcore-log: 
,03-21 16:46:59.565 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:59.565 10976 11040 I jxcore-log: 
,03-21 16:46:59.570 10976 11040 I jxcore-log: # teardown
03-21 16:46:59.570 10976 11040 I jxcore-log: 
,03-21 16:46:59.575 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:59.575 10976 11040 I jxcore-log: 
,03-21 16:46:59.680 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:46:59.680 10976 11040 I jxcore-log: 
,03-21 16:46:59.685 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 32801
03-21 16:46:59.685 10976 11040 I jxcore-log: 
,03-21 16:46:59.695 10976 11040 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":60920,"error":{}}
03-21 16:46:59.695 10976 11040 I jxcore-log: 
,03-21 16:46:59.700 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:46:59.700 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:46:59.700 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:59.705 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:46:59.705 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:46:59.705 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:46:59.710 10976 11040 I jxcore-log: ok 192 failure reason is as expected
03-21 16:46:59.710 10976 11040 I jxcore-log: 
,03-21 16:46:59.715 10976 11040 I jxcore-log: ok 193 error description is as expected
03-21 16:46:59.715 10976 11040 I jxcore-log: 
,03-21 16:46:59.715 10976 11040 I jxcore-log: ok 194 must be stopped
03-21 16:46:59.715 10976 11040 I jxcore-log: 
,03-21 16:46:59.725 10976 11040 I jxcore-log: # setup
03-21 16:46:59.725 10976 11040 I jxcore-log: 
,03-21 16:46:59.825 10976 11040 I jxcore-log: # 52. We repeat failedConnection event when we get it from thaliTcpServersManager
03-21 16:46:59.825 10976 11040 I jxcore-log: 
,03-21 16:46:59.950 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:46:59.950 10976 11040 I jxcore-log: 
,03-21 16:46:59.955 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:46:59.955 10976 11040 I jxcore-log: 
,03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:46:59.960 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:46:59.965 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:46:59.970 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:46:59.970 10976 11040 I jxcore-log: 
,03-21 16:46:59.970 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:46:59.970 10976 11040 I jxcore-log: 
,03-21 16:46:59.975 10976 11040 I jxcore-log: # teardown
03-21 16:46:59.975 10976 11040 I jxcore-log: 
,03-21 16:46:59.980 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:46:59.980 10976 11040 I jxcore-log: 
,03-21 16:46:59.995  3390  3619 V AlarmManager: waitForAlarm result :8
,03-21 16:47:00.120 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:47:00.120 10976 11040 I jxcore-log: 
,03-21 16:47:00.125 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 43445
03-21 16:47:00.125 10976 11040 I jxcore-log: 
,03-21 16:47:00.130 10976 11040 I jxcore-log: ok 195 peerIdentifier matches
03-21 16:47:00.130 10976 11040 I jxcore-log: 
,03-21 16:47:00.135 10976 11040 I jxcore-log: ok 196 error description matches
03-21 16:47:00.135 10976 11040 I jxcore-log: 
,03-21 16:47:00.140 10976 11040 I jxcore-log: # setup
03-21 16:47:00.140 10976 11040 I jxcore-log: 
,03-21 16:47:00.300 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:47:00.300 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:47:00.300 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:47:00.305 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:47:00.305 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:47:00.305 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:47:00.320 10976 11040 I jxcore-log: # 53. we successfully receive and replay discoveryAdvertisingStateUpdate
03-21 16:47:00.320 10976 11040 I jxcore-log: 
,03-21 16:47:00.455 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:47:00.455 10976 11040 I jxcore-log: 
,03-21 16:47:00.460 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:47:00.460 10976 11040 I jxcore-log: 
,03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:47:00.470 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:47:00.475 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:47:00.480 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:47:00.480 10976 11040 I jxcore-log: 
,03-21 16:47:00.480 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:47:00.480 10976 11040 I jxcore-log: 
,03-21 16:47:00.485 10976 11040 I jxcore-log: # teardown
03-21 16:47:00.485 10976 11040 I jxcore-log: 
,03-21 16:47:00.490 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:47:00.490 10976 11040 I jxcore-log: 
,03-21 16:47:00.565 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:47:00.565 10976 11040 I jxcore-log: 
,03-21 16:47:00.570 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 54350
03-21 16:47:00.570 10976 11040 I jxcore-log: 
,03-21 16:47:00.580 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 46781, start advertisements: false
,03-21 16:47:00.580 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:47:00.580 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:47:00.580 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 16:47:00.580 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:47:00.585 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:47:00.585 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:47:00.590  5849  6155 D BtGatt.GattService: registerClient() - UUID=1b4781d6-9b22-47dc-8adc-7d01b552de3d
,03-21 16:47:00.630  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=1b4781d6-9b22-47dc-8adc-7d01b552de3d, clientIf=6
03-21 16:47:00.630 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:47:00.630  5849 11643 D BtGatt.GattService: start scan with filters
,03-21 16:47:00.645  5849 11643 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 63
,03-21 16:47:00.650  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:47:00.650  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:47:00.650  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:47:00.655  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:47:00.655  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.660  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:47:00.660  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:47:00.660  5849  5949 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-21 16:47:00.660  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:47:00.660  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.660  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:47:00.660  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:47:00.665  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:47:00.665  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.665 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:47:00.665 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:47:00.665 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 16:47:00.665 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:47:00.665 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:47:00.665 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:47:00.665 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:47:00.670 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:47:00.670 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:47:00.670 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:47:00.670 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:47:00.670 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:47:00.670 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:47:00.670 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:47:00.670 10976 11040 I jxcore-log: 
03-21 16:47:00.675  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:47:00.675  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.680 10976 11040 I jxcore-log: ok 197 discoveryActive matches
03-21 16:47:00.680 10976 11040 I jxcore-log: 
,03-21 16:47:00.680 10976 11040 I jxcore-log: ok 198 advertisingActive matches
03-21 16:47:00.680 10976 11040 I jxcore-log: 
,03-21 16:47:00.685 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:47:00.685 10976 11040 I jxcore-log: 
,03-21 16:47:00.695 10976 11040 I jxcore-log: not ok 199 discoveryActive matches
03-21 16:47:00.695 10976 11040 I jxcore-log: 
03-21 16:47:00.695 10976 11040 I jxcore-log:   ---
03-21 16:47:00.695 10976 11040 I jxcore-log: 
03-21 16:47:00.695 10976 11040 I jxcore-log:     operator: equal
03-21 16:47:00.695 10976 11040 I jxcore-log: 
03-21 16:47:00.695 10976 11040 I jxcore-log:     expected: false
03-21 16:47:00.695 10976 11040 I jxcore-log: 
03-21 16:47:00.695 10976 11040 I jxcore-log:     actual:   true
03-21 16:47:00.695 10976 11040 I jxcore-log: 
03-21 16:47:00.695 10976 11040 I jxcore-log:   ...
03-21 16:47:00.695 10976 11040 I jxcore-log: 
03-21 16:47:00.695 10976 11040 I jxcore-log: ok 200 advertisingActive matches
03-21 16:47:00.695 10976 11040 I jxcore-log: 
,03-21 16:47:00.700 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-21 16:47:00.700 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-21 16:47:00.700 10976 11040 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-21 16:47:00.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:47:00.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:47:00.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:47:00.700 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 16:47:00.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:47:00.700 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 16:47:00.700  5849  6155 D BtGatt.GattService: stopScan() - queue size =1
03-21 16:47:00.700  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:47:00.700  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 9
,03-21 16:47:00.700  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 16:47:00.705 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 16:47:00.705  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:47:00.705  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:00.705 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:47:00.705  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-21 16:47:00.705 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:47:00.705 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:47:00.705 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:47:00.705 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:47:00.705 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:47:00.705  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:47:00.705  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:00.705  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:47:00.710  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
03-21 16:47:00.710  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:00.710  5849  5920 D BtGatt.GattService: current time is 251686740070
03-21 16:47:00.710  5849  5920 D BtGatt.GattService: Batch record : [62, 1, -85, 43, 99, 64, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-21 16:47:00.710  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:47:00.710  5849  5920 D ScanRecord: parseFromBytes
,03-21 16:47:00.710 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:47:00.715 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:47:00.715 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:47:00.715 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:47:00.720 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 16:47:00.720 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:47:00.720 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:47:00.720 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:47:00.720 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:47:00.720 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:47:00.720 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:47:00.720 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:47:00.720 10976 11040 I jxcore-log: 
,03-21 16:47:00.725 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:47:00.725 10976 11040 I jxcore-log: 
,03-21 16:47:00.735 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:47:00.735 10976 11040 I jxcore-log: 
,03-21 16:47:00.740 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 52805
03-21 16:47:00.740 10976 11040 I jxcore-log: 
,03-21 16:47:00.740 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 52805, start advertisements: true
,03-21 16:47:00.740 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:47:00.740 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 16:47:00.740 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:47:00.745 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:47:00.745 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:47:00.745 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:47:00.745 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:47:00.745  5849  5857 D BtGatt.GattService: registerClient() - UUID=a406f90d-b21f-4759-9855-780fa940d964
,03-21 16:47:00.790  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=a406f90d-b21f-4759-9855-780fa940d964, clientIf=6
,03-21 16:47:00.790 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 16:47:00.790  5849  6155 D BtGatt.GattService: start scan with filters
,03-21 16:47:00.810  5849  6155 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 64,
03-21 16:47:00.815  5849  5949 D BtGatt.ScanManager: handling starting scan,
03-21 16:47:00.815  5849  5949 D BtGatt.ScanManager: isFilteringSupported
,03-21 16:47:00.815  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:47:00.815 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-21 16:47:00.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 16:47:00.815 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-21 16:47:00.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:47:00.815 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
,03-21 16:47:00.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 16:47:00.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0",
,03-21 16:47:00.815 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 16:47:00.815 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:47:00.815 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 16:47:00.815 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:47:00.815 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 16:47:00.825  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:47:00.825  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.825  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:47:00.825  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 16:47:00.825  5849  5949 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
,03-21 16:47:00.825  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
03-21 16:47:00.825  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:00.830  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan,
03-21 16:47:00.830  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:47:00.830  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 16:47:00.830  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.835  5849  5861 D BtGatt.GattService: registerClient() - UUID=3165190a-f992-42d2-9f95-73c9775ef4ff
03-21 16:47:00.835  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 16:47:00.835  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.875  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=3165190a-f992-42d2-9f95-73c9775ef4ff, clientIf=7,
03-21 16:47:00.875 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-21 16:47:00.900  5849 11643 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 51
,03-21 16:47:00.900  5849  5948 D BtGatt.AdvertiseManager: message : 0
,03-21 16:47:00.905  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:47:00.905  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:47:00.910  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:47:00.910  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:47:00.915  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:47:00.920  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:47:00.920  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:47:00.920  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 16:47:00.920  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 16:47:00.925 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:47:00.925 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:47:00.930 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:47:00.930 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:47:00.930 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:47:00.930 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:47:00.935 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
03-21 16:47:00.935 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:47:00.935 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 16:47:00.935 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-21 16:47:00.935 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-21 16:47:00.935 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:47:00.935 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:47:00.935 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-21 16:47:00.935 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:47:00.935 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 16:47:00.935 10976 10976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:47:00.935 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 16:47:00.935 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:47:00.935 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:47:00.935 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 16:47:00.935 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:47:00.935 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK,
,03-21 16:47:00.940 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:47:00.940 10976 11040 I jxcore-log: 
,03-21 16:47:00.950 10976 11040 I jxcore-log: not ok 201 discoveryActive matches
03-21 16:47:00.950 10976 11040 I jxcore-log: 
03-21 16:47:00.950 10976 11040 I jxcore-log:   ---
03-21 16:47:00.950 10976 11040 I jxcore-log: 
03-21 16:47:00.950 10976 11040 I jxcore-log:     operator: equal
03-21 16:47:00.950 10976 11040 I jxcore-log: 
,03-21 16:47:00.950 10976 11040 I jxcore-log:     expected: false
03-21 16:47:00.950 10976 11040 I jxcore-log: 
03-21 16:47:00.950 10976 11040 I jxcore-log:     actual:   true
03-21 16:47:00.950 10976 11040 I jxcore-log: 
03-21 16:47:00.950 10976 11040 I jxcore-log:   ...
03-21 16:47:00.950 10976 11040 I jxcore-log: 
,03-21 16:47:00.950 10976 11851 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 16:47:00.950 10976 11851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:47:00.955 10976 11040 I jxcore-log: not ok 202 advertisingActive matches
03-21 16:47:00.955 10976 11040 I jxcore-log: 
,03-21 16:47:00.955 10976 11040 I jxcore-log:   ---
03-21 16:47:00.955 10976 11040 I jxcore-log: 
03-21 16:47:00.955 10976 11040 I jxcore-log:     operator: equal
03-21 16:47:00.955 10976 11040 I jxcore-log: 
03-21 16:47:00.955 10976 11851 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
03-21 16:47:00.955 10976 11851 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:47:00.955 10976 11851 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:47:00.955 10976 11040 I jxcore-log:     expected: true
03-21 16:47:00.955 10976 11040 I jxcore-log: 
,03-21 16:47:00.955 10976 11851 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19ab9e69
03-21 16:47:00.955 10976 11040 I jxcore-log:     actual:   false
03-21 16:47:00.955 10976 11040 I jxcore-log: 
03-21 16:47:00.955 10976 11851 D BluetoothSocket: channel: 6
03-21 16:47:00.955 10976 11851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 16:47:00.955 10976 11040 I jxcore-log:   ...
03-21 16:47:00.955 10976 11040 I jxcore-log: 
,03-21 16:47:00.960 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:47:00.960 10976 11040 I jxcore-log: 
,03-21 16:47:00.960 10976 11040 I jxcore-log: not ok 203 discoveryActive matches
03-21 16:47:00.960 10976 11040 I jxcore-log: 
,03-21 16:47:00.960 10976 11040 I jxcore-log:   ---
03-21 16:47:00.960 10976 11040 I jxcore-log: 
03-21 16:47:00.960 10976 11040 I jxcore-log:     operator: equal
03-21 16:47:00.960 10976 11040 I jxcore-log: 
03-21 16:47:00.960 10976 11040 I jxcore-log:     expected: false
03-21 16:47:00.960 10976 11040 I jxcore-log: 
03-21 16:47:00.960 10976 11040 I jxcore-log:     actual:   true
03-21 16:47:00.960 10976 11040 I jxcore-log: 
03-21 16:47:00.960 10976 11040 I jxcore-log:   ...
03-21 16:47:00.960 10976 11040 I jxcore-log: 
,03-21 16:47:00.965 10976 11040 I jxcore-log: ok 204 advertisingActive matches
03-21 16:47:00.965 10976 11040 I jxcore-log: 
,03-21 16:47:00.965 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:47:00.965 10976 11040 I jxcore-log: 
,03-21 16:47:00.965 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:47:00.965 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 16:47:00.965 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:47:00.965 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 16:47:00.965 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 16:47:00.965 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@268ca0ee, channel: 6, state: LISTENING
03-21 16:47:00.965 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@268ca0ee, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19ab9e69, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28fd398fmSocket: android.net.LocalSocket@2ef5441c impl:android.net.LocalSocketImpl@2d6b825 fd:FileDescriptor[112]
03-21 16:47:00.970 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ef5441c impl:android.net.LocalSocketImpl@2d6b825 fd:FileDescriptor[112]
03-21 16:47:00.970 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:47:00.970 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:47:00.970 10976 11851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 16:47:00.970 10976 11851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 16:47:00.970 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 16:47:00.970 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:47:00.970 10976 11851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 16:47:00.970 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:47:00.970 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:47:00.970 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 16:47:00.970  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:47:00.970  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:47:00.970  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 10
03-21 16:47:00.970  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 16:47:00.970 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:47:00.970 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:47:00.970 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:47:00.970 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:47:00.970 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 16:47:00.970 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:47:00.970 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 16:47:00.970  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:47:00.970  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:00.970  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:47:00.975  5849  5948 D BtGatt.AdvertiseManager: message : 1
,03-21 16:47:00.975  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:47:00.975  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 16:47:00.975  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:47:00.975  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:00.975  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:47:00.975  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:47:00.975  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:47:00.975  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:00.980  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 16:47:00.980  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:47:00.980  5849  5857 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:47:00.980 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 16:47:00.980 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:47:00.980 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:47:00.980 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 16:47:00.980 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:47:00.980 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:47:00.980 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-21 16:47:00.980 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:47:00.980 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 16:47:00.980 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:47:00.980 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:47:00.980 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:47:00.980 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 16:47:00.985 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 16:47:00.990 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 16:47:00.990 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:47:00.990 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 16:47:00.995 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 16:47:00.995 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:47:00.995 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:47:00.995 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:47:00.995 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 16:47:00.995 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:47:00.995 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 16:47:00.995 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 16:47:00.995 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 16:47:00.995 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:47:00.995 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:47:00.995 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:47:00.995 10976 11040 I jxcore-log: 
,03-21 16:47:00.995 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:47:00.995 10976 11040 I jxcore-log: 
,03-21 16:47:01.000 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:47:01.000 10976 11040 I jxcore-log: 
,03-21 16:47:01.010 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:47:01.010 10976 11040 I jxcore-log: 
,03-21 16:47:01.010 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 57211
03-21 16:47:01.010 10976 11040 I jxcore-log: 
,03-21 16:47:01.025 10976 11040 I jxcore-log: # setup
03-21 16:47:01.025 10976 11040 I jxcore-log: 
,03-21 16:47:01.160 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 16:47:01.160 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 16:47:01.160 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:47:01.165 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:47:01.165 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 16:47:01.165 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 16:47:01.190 10976 11040 I jxcore-log: # 54. can do HTTP requests between peers
03-21 16:47:01.190 10976 11040 I jxcore-log: 
,03-21 16:47:01.505 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:47:01.505 10976 11040 I jxcore-log: 
,03-21 16:47:01.510 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:47:01.510 10976 11040 I jxcore-log: 
,03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:47:01.520 10976 11040 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:47:01.525 10976 11040 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:47:01.525 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:47:01.525 10976 11040 I jxcore-log: 
,03-21 16:47:01.530 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:47:01.530 10976 11040 I jxcore-log: 
,03-21 16:47:01.530  3390  3864 E Watchdog: !@Sync 8 [03-21 16:47:01.535]
,03-21 16:47:01.535 10976 11040 I jxcore-log: # teardown
03-21 16:47:01.535 10976 11040 I jxcore-log: 
,03-21 16:47:01.540 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:47:01.540 10976 11040 I jxcore-log: 
,03-21 16:47:01.630 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:47:01.630 10976 11040 I jxcore-log: 
,03-21 16:47:01.635 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 48825
03-21 16:47:01.635 10976 11040 I jxcore-log: 
,03-21 16:47:01.640 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 52805, start advertisements: false
03-21 16:47:01.640 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:47:01.640 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:47:01.640 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 16:47:01.640 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:47:01.645 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:47:01.645 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:47:01.645  5849  6155 D BtGatt.GattService: registerClient() - UUID=879f166d-e6ee-4899-8015-152a70032f87
,03-21 16:47:01.685  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=879f166d-e6ee-4899-8015-152a70032f87, clientIf=6
,03-21 16:47:01.690 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:47:01.690  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:47:01.730  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 65
,03-21 16:47:01.735  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:47:01.735  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:47:01.735  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:47:01.745  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:47:01.745  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:01.745  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:47:01.745  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:47:01.745  5849  5949 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
03-21 16:47:01.745  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:47:01.750  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:01.750  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:47:01.750  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 16:47:01.750  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 16:47:01.750  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:01.755  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 16:47:01.755  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:01.755 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 16:47:01.755 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:47:01.755 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-21 16:47:01.755 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 16:47:01.755 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:47:01.755 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:47:01.755 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 16:47:01.760 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:47:01.760 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:47:01.760 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 16:47:01.760 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:47:01.760 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 16:47:01.760 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 16:47:01.770 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-21 16:47:01.770 10976 11040 I jxcore-log: 
,03-21 16:47:01.775 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 16:47:01.775 10976 11040 I jxcore-log: 
,03-21 16:47:01.780 10976 11040 I io.jxcore.node.ConnectionHelper: start: Port number: 48825, start advertisements: true
,03-21 16:47:01.780 10976 11040 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 16:47:01.780 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 16:47:01.780 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 16:47:01.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 16:47:01.785 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-21 16:47:01.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:47:01.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 16:47:01.785 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:47:01.785 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:47:01.785 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 16:47:01.785 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:47:01.790  5849  5861 D BtGatt.GattService: registerClient() - UUID=4428530f-1f65-43f1-b9ca-410081b80381
,03-21 16:47:01.830  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=4428530f-1f65-43f1-b9ca-410081b80381, clientIf=7
,03-21 16:47:01.830 10976 10988 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:47:01.845  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 52
,03-21 16:47:01.845  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:47:01.845  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:47:01.845  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:47:01.845  5849  5948 D BtGatt.AdvertiseManager: starting advertising
03-21 16:47:01.845  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:47:01.850  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:47:01.850  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:47:01.850  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:47:01.850  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:47:01.850  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:47:01.850 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:47:01.850 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 16:47:01.850 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 16:47:01.850 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:47:01.850 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 16:47:01.850 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 16:47:01.850 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 16:47:01.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 16:47:01.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 16:47:01.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 16:47:01.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 16:47:01.855 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 16:47:01.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 16:47:01.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 16:47:01.855 10976 11040 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 16:47:01.855 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 16:47:01.855 10976 11040 I io.jxcore.node.ConnectionHelper: start: OK
03-21 16:47:01.855 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 16:47:01.855 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 16:47:01.855 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 16:47:01.860 10976 11876 D BluetoothSocket: bindListen(): myUserId = 0
03-21 16:47:01.860 10976 11876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 16:47:01.860 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 16:47:01.860 10976 11040 I jxcore-log: 
,03-21 16:47:01.860 10976 11876 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-21 16:47:01.860 10976 11876 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 16:47:01.860 10976 11876 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:47:01.860 10976 11876 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2dfb1a1
03-21 16:47:01.860 10976 11876 D BluetoothSocket: channel: 6
03-21 16:47:01.860 10976 11876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:47:02.765  3390  3619 V AlarmManager: waitForAlarm result :4,
,03-21 16:47:02.790  5849  5849 D BtGatt.ScanManager: awakened up at time 253768
,03-21 16:47:02.795  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:02.800  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:47:02.800  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:02.800  5849  5920 D BtGatt.GattService: current time is 253778981820
03-21 16:47:02.800  5849  5920 D BtGatt.GattService: Batch record : [90, -105, -58, -25, -124, 123, 1, -128, -84, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:47:02.800  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:47:02.800  5849  5920 D ScanRecord: parseFromBytes
03-21 16:47:02.800  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=7B:84:E7:C6:97:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=253729122029}
03-21 16:47:02.800  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:02.805 10976 10986 D ScanRecord: parseFromBytes
03-21 16:47:02.805 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 16:47:02.805 10976 10976 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 16:47:02.820  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
03-21 16:47:02.820  3726  3726 I PERF    : received broadcast android.intent.action.TIME_TICK
03-21 16:47:02.820  3726  3726 D KeyguardUpdateMonitor: handleTimeUpdate
,03-21 16:47:02.830  3726  3726 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,03-21 16:47:02.835  3726  3726 D SecKeyguardClockView: HomeTimezone(): 1,
,03-21 16:47:02.845 10976 11040 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-21 16:47:02.845 10976 11040 I jxcore-log: 
,03-21 16:47:02.850 10976 11040 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-21 16:47:02.850 10976 11040 I jxcore-log: 
,03-21 16:47:02.855  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:47:02.855  3726  3726 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 16:47:02.860  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 16:47:02.865 10976 11040 I jxcore-log: ok 205 found a peer! {"peerIdentifier":"F8:95:C7:87:3C:51","portNumber":56899,"hostAddress":"127.0.0.1"}
03-21 16:47:02.865 10976 11040 I jxcore-log: 
,03-21 16:47:02.880 10976 11040 I jxcore-log: DEBUG createPeerListener: first connection
03-21 16:47:02.880 10976 11040 I jxcore-log: 
,03-21 16:47:02.880 10976 11040 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-21 16:47:02.880 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:47:02.885 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-21 16:47:02.885 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-21 16:47:02.885 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-21 16:47:02.885 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-21 16:47:02.885 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-21 16:47:02.885 10976 11040 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-21 16:47:02.885 10976 11884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1548)
,03-21 16:47:02.895 10976 11884 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-21 16:47:02.895 10976 11884 D BluetoothSocket: connect(): myUserId = 0
03-21 16:47:02.895 10976 11884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:47:02.895  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
03-21 16:47:02.895  5849 11643 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 16:47:02.895  5849  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:02.895  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
,03-21 16:47:02.895  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 16:47:02.895  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-21 16:47:02.900 10976 11884 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
03-21 16:47:02.900  5849  5999 D IOP_DB_BT: db_query_execute: result 1
03-21 16:47:02.900  5849  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-21 16:47:02.900  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:47:02.905  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:47:02.905  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:47:02.910  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:47:02.910  3726  3726 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:47:02.925  3726  3726 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 16:47:03.815  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:47:03.830  5849  5849 D BtGatt.ScanManager: awakened up at time 254805
,03-21 16:47:03.835  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:03.840  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:47:03.840  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:03.840  5849  5920 D BtGatt.GattService: current time is 254818045196
03-21 16:47:03.840  5849  5920 D BtGatt.GattService: Batch record : [90, -105, -58, -25, -124, 123, 1, -128, -68, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:47:03.840  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-21 16:47:03.840  5849  5920 D ScanRecord: parseFromBytes
03-21 16:47:03.845  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=7B:84:E7:C6:97:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=254718380821}
03-21 16:47:03.845  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:03.845 10976 10988 D ScanRecord: parseFromBytes,
,03-21 16:47:03.845 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:47:04.780  2896  4798 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 16:47:04.860  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:47:04.865  5849  5849 D BtGatt.ScanManager: awakened up at time 255842
03-21 16:47:04.870  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:47:04.875  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:47:04.875  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:04.875  5849  5920 D BtGatt.GattService: current time is 255850626279
03-21 16:47:04.875  5849  5920 D BtGatt.GattService: Batch record : [90, -105, -58, -25, -124, 123, 1, -128, -67, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:47:04.875  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-21 16:47:04.875  5849  5920 D ScanRecord: parseFromBytes
03-21 16:47:04.875  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=7B:84:E7:C6:97:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-67, mTimestampNanos=255850798529},
03-21 16:47:04.875  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-21 16:47:04.875 10976 11033 D ScanRecord: parseFromBytes
03-21 16:47:04.875 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:47:04.965  3390  4727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:47:04.965  3390  4727 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:47:04.965  3390  4727 D BatteryService: online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
03-21 16:47:04.965  3390  4727 D BatteryService: stay LED for fully charged
03-21 16:47:04.965  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:47:04.965  3390  3390 I MotionRecognitionService: Plugged
03-21 16:47:04.965  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:47:04.970  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:47:04.970  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:47:04.970  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:04.970  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:04.970  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:47:04.975  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 16:47:04.975  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:47:04.990  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:47:04.990  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:04.990  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:04.995  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:05.110  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:12), CUR = 38, LCD = 0
,03-21 16:47:05.855  5849  5999 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:05.855  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 16:47:05.855  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 16:47:05.855  5849  5999 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
,03-21 16:47:05.860  5849  5999 D IOP_DB_BT: db_query_execute: result 1
03-21 16:47:05.885  3390  3619 V AlarmManager: waitForAlarm result :4
03-21 16:47:05.860  5849  5999 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:05.860  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:05.860  5849  5999 W bt-btif : bta_dm_acl_change(), event : 0
03-21 16:47:05.860  5849  5999 W bt-btif : info:x10
,03-21 16:47:05.860  5849  5920 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-21 16:47:05.860  5849  5920 E BluetoothRemoteDevices: aclStateChangeCallback: State:Connected to Device:F8:95:C7:87:3C:XX,
,03-21 16:47:05.860  5849  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-21 16:47:05.880  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 16:47:05.880  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_CONNECTED
03-21 16:47:05.900  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 16:47:05.900  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_CONNECTED,
,03-21 16:47:05.900  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_CONNECTED
,03-21 16:47:05.915  3390  3576 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2eaa9c96 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:47:05.920  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
,03-21 16:47:05.920  3390  3980 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:47:05.950  3390  4729 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2eaa9c96 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:47:05.955  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 16:47:05.965 10183 11901 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,03-21 16:47:05.965  3390  3980 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2eaa9c96 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:47:05.970 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,03-21 16:47:05.970 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
,03-21 16:47:05.975 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage CONNECTION_COMPLETE
,03-21 16:47:05.975  3390  4730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2eaa9c96 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{3599bc7c 10051:com.android.settings/1000}
,03-21 16:47:05.980 10051 10051 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 16:47:05.990  3390  4730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2eaa9c96 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{c7a662d 4113:com.google.android.googlequicksearchbox:search/u0a64}
,03-21 16:47:06.005  4113  4113 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-21 16:47:06.005  4113  4113 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-21 16:47:06.010  5849  5849 D BtGatt.ScanManager: awakened up at time 256986
,03-21 16:47:06.010  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:47:06.010  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:47:06.010  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:06.010  5849  5920 D BtGatt.GattService: current time is 256989458113
03-21 16:47:06.010  5849  5920 D BtGatt.GattService: Batch record : [90, -105, -58, -25, -124, 123, 1, -128, -68, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:47:06.010  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:47:06.010  5849  5920 D ScanRecord: parseFromBytes
,03-21 16:47:06.015  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=7B:84:E7:C6:97:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=256189598904}
03-21 16:47:06.015  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:06.015 10976 10986 D ScanRecord: parseFromBytes
,03-21 16:47:06.015 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:47:06.145  5849  5999 W bt-sdp  : process_service_search_attr_rsp
,03-21 16:47:07.015  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:47:07.025  5849  5849 D BtGatt.ScanManager: awakened up at time 258003
03-21 16:47:07.030  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:07.035  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:47:07.035  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:07.105  5849  5920 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-21 16:47:07.110  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 16:47:07.110  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 16:47:07.110  5849  5920 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-21 16:47:07.115  3390  4727 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 16:47:07.115  5849  5920 E bt-btif : check_cod: remote_cod = 0x5a020c
03-21 16:47:07.115  5849  5920 W bt-btif : btif_dm_ssp_reply: accept=1
,03-21 16:47:07.120  5849  5946 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-21 16:47:07.120  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 16:47:07.120  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 16:47:07.120  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
,03-21 16:47:07.120  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-21 16:47:07.120  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-21 16:47:07.120  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
03-21 16:47:07.125  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 16:47:07.125  3726  4754 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 16:47:07.125  3390  3576 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25e105ed u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3599bc7c 10051:com.android.settings/1000},
03-21 16:47:07.130  3390  3651 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-21 16:47:07.130 10051 10051 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 16:47:07.130  5849  5946 D BtConfig.SecureMode: isSecureModeOn:false
,03-21 16:47:07.130  5849  5946 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-21 16:47:07.135 10183 11911 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
03-21 16:47:07.135 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 16:47:07.140  3390  3981 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25e105ed u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:47:07.140 10183 10183 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 16:47:07.145 10183 10183 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-21 16:47:07.145  3390  4729 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25e105ed u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:47:07.150  3390  4030 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:47:07.155 10183 11912 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 16:47:07.155 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 16:47:07.160  3390  4729 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25e105ed u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{e43a094 10330:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 16:47:07.160 10330 10330 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 16:47:07.160 10330 10330 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 16:47:07.160 10330 10330 D GMHFPReceiver: jangil::setProperties()
,03-21 16:47:07.165 10330 10330 D GMHFPReceiver: jangil::printBTStatus()
,03-21 16:47:07.165  3390  3651 D SettingsProvider: name = Wearable0001
03-21 16:47:07.165  3390  3651 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:47:07.165  3390  3651 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:47:07.165  3390  3651 D SettingsProvider: selectionArgs: false
03-21 16:47:07.165  3390  3651 D SettingsProvider: selectionArgs: 10121
03-21 16:47:07.165  3390  3651 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 16:47:07.165  3390  3651 D SettingsProvider: ret = -1
,03-21 16:47:07.165 10330 10330 D GMHFPReceiver: ::::::::Wearable0001::false
03-21 16:47:07.165  3390  3422 D SettingsProvider: name = Wearable0002
03-21 16:47:07.165  3390  3422 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:47:07.165  3390  3422 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:47:07.165  3390  3422 D SettingsProvider: selectionArgs: false
03-21 16:47:07.165  3390  3422 D SettingsProvider: selectionArgs: 10121
03-21 16:47:07.170  3390  3422 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:47:07.170  3390  3422 D SettingsProvider: ret = -1
03-21 16:47:07.170 10330 10330 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 16:47:07.175  3390  4111 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{25e105ed u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{963a9dd 4454:com.google.android.gms.persistent/u0a14}
,03-21 16:47:07.265 10330 10330 D GMHFPReceiver: onServiceConnected() : 1
,03-21 16:47:07.265 10330 10330 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 16:47:07.655  5849  5920 W bt-btif : btif_dm_auth_cmpl_evt
03-21 16:47:07.655  5849  5920 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-21 16:47:07.685  5849  5920 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-21 16:47:07.690  5849  5946 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-21 16:47:07.695  3390  4242 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 16:47:07.705  3726  3726 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 16:47:07.705  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 16:47:07.705  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 16:47:07.705  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-21 16:47:07.705  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-21 16:47:07.705  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-21 16:47:07.705  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 16:47:07.705  5849  5946 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-21 16:47:07.720  3390  3576 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2700a86e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3599bc7c 10051:com.android.settings/1000}
,03-21 16:47:07.720  5849  5946 D BtConfig.SecureMode: isSecureModeOn:false
,03-21 16:47:07.725  5849  5946 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@3a6037f7
,03-21 16:47:07.730  3390  4415 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-21 16:47:07.730  3390  4415 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:47:07.730  3390  4415 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:47:07.730  3390  4415 D SettingsProvider: selectionArgs: false
03-21 16:47:07.730  3390  4415 D SettingsProvider: selectionArgs: 1002
03-21 16:47:07.730  3390  4415 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:47:07.730  3390  4415 D SettingsProvider: ret = -1
,03-21 16:47:07.730  5849  5946 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-21 16:47:07.735  3390  4729 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-21 16:47:07.735  3390  4729 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:47:07.735  3390  4729 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:47:07.735  3390  4729 D SettingsProvider: selectionArgs: false
03-21 16:47:07.735  3390  4729 D SettingsProvider: selectionArgs: 1002
03-21 16:47:07.735  3390  4729 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 16:47:07.735  3390  4729 D SettingsProvider: ret = -1
,03-21 16:47:07.735 10051 10051 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 16:47:07.735  3390  3744 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
03-21 16:47:07.735  3390  3744 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:47:07.735  3390  3744 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:47:07.735  3390  3744 D SettingsProvider: selectionArgs: false
03-21 16:47:07.735  3390  3744 D SettingsProvider: selectionArgs: 1002
03-21 16:47:07.735  3390  3744 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:47:07.740  3390  3744 D SettingsProvider: ret = -1
03-21 16:47:07.740  5849  5946 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-21 16:47:07.740  3726  4754 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 16:47:07.740  3390  4730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2700a86e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:47:07.745  3390  3423 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:47:07.750 10183 10183 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 16:47:07.750 10183 10183 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-21 16:47:07.755 10183 11919 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 16:47:07.755  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2700a86e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{3e61ed99 10183:com.sec.android.automotive.drivelink/u0a102}
,03-21 16:47:07.755  3390  3980 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:47:07.765 10183 11920 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 16:47:07.765  3390  3832 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2700a86e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{e43a094 10330:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 16:47:07.770 10330 10330 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 16:47:07.770 10330 10330 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 16:47:07.770 10330 10330 D GMHFPReceiver: jangil::setProperties()
,03-21 16:47:07.770 10330 10330 D GMHFPReceiver: jangil::printBTStatus()
,03-21 16:47:07.770  3390  3744 D SettingsProvider: name = Wearable0001
03-21 16:47:07.770  3390  3744 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:47:07.770  3390  3744 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:47:07.770  3390  3744 D SettingsProvider: selectionArgs: false
03-21 16:47:07.775  3390  3744 D SettingsProvider: selectionArgs: 10121
03-21 16:47:07.775  3390  3744 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:47:07.775  3390  3744 D SettingsProvider: ret = -1
03-21 16:47:07.775 10330 10330 D GMHFPReceiver: ::::::::Wearable0001::false
03-21 16:47:07.775  3390  4111 D SettingsProvider: name = Wearable0002
03-21 16:47:07.775  3390  4111 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 16:47:07.775  3390  4111 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 16:47:07.775  3390  4111 D SettingsProvider: selectionArgs: false
03-21 16:47:07.775  3390  4111 D SettingsProvider: selectionArgs: 10121
03-21 16:47:07.775  3390  4111 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 16:47:07.775  3390  4111 D SettingsProvider: ret = -1
03-21 16:47:07.775 10330 10330 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 16:47:07.780  3390  4730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2700a86e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{963a9dd 4454:com.google.android.gms.persistent/u0a14}
,03-21 16:47:07.875 10330 10330 D GMHFPReceiver: onServiceConnected() : 1,
,03-21 16:47:07.885 10330 10330 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 16:47:08.050  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:47:08.065  5849  5849 D BtGatt.ScanManager: awakened up at time 259044
,03-21 16:47:08.070  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:08.075  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:47:08.075  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:09.090  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:47:09.100  5849  5849 D BtGatt.ScanManager: awakened up at time 260079
,03-21 16:47:09.110  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:09.115  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:47:09.115  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:09.115  5849  5920 D BtGatt.GattService: current time is 260093438780
03-21 16:47:09.115  5849  5920 D BtGatt.GattService: Batch record : [90, -105, -58, -25, -124, 123, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:47:09.115  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:47:09.115  5849  5920 D ScanRecord: parseFromBytes
03-21 16:47:09.115  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=7B:84:E7:C6:97:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=260043572071}
03-21 16:47:09.115  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:09.115 10976 10986 D ScanRecord: parseFromBytes
03-21 16:47:09.120 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:47:10.130  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:47:10.145  5849  5849 D BtGatt.ScanManager: awakened up at time 261122
03-21 16:47:10.145  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:10.150  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:47:10.150  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:10.150  5849  5920 D BtGatt.GattService: current time is 261128269280
03-21 16:47:10.150  5849  5920 D BtGatt.GattService: Batch record : [90, -105, -58, -25, -124, 123, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:47:10.150  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:47:10.150  5849  5920 D ScanRecord: parseFromBytes
03-21 16:47:10.150  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=7B:84:E7:C6:97:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=261128453571}
03-21 16:47:10.150  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:10.155 10976 10988 D ScanRecord: parseFromBytes
03-21 16:47:10.155 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:47:11.165  3390  3619 V AlarmManager: waitForAlarm result :4
,03-21 16:47:11.175  5849  5849 D BtGatt.ScanManager: awakened up at time 262154
,03-21 16:47:11.185  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:11.190  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 16:47:11.190  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:11.190  5849  5920 D BtGatt.GattService: current time is 262166297988
03-21 16:47:11.190  5849  5920 D BtGatt.GattService: Batch record : [90, -105, -58, -25, -124, 123, 1, -128, -66, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 16:47:11.190  5849  5920 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 16:47:11.190  5849  5920 D ScanRecord: parseFromBytes
03-21 16:47:11.190  5849  5920 D BtGatt.GattService: result: ScanResult{mDevice=7B:84:E7:C6:97:5A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=261216436655}
03-21 16:47:11.190  5849  5920 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:11.190 10976 11033 D ScanRecord: parseFromBytes
03-21 16:47:11.190 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:47:11.910  5849  5999 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 73 RCID: 74
,03-21 16:47:12.185  5849  5999 W bt-btif : new conn_srvc id:26, app_id:255
03-21 16:47:12.190  5849  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 16:47:12.190  5849  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-21 16:47:12.190 10976 11876 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@eabf3d9
03-21 16:47:12.195  5849  6155 E BluetoothRemoteDevices: setRfcommConnected true
,03-21 16:47:12.200  3390  3619 V AlarmManager: waitForAlarm result :4
03-21 16:47:12.205  5849  5849 D BtGatt.ScanManager: awakened up at time 263184
03-21 16:47:12.215  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:12.215  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:47:12.215  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:12.220 10976 11876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
03-21 16:47:12.220 10976 11876 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 16:47:12.235 10976 11876 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-21 16:47:12.235 10976 11876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1549)
03-21 16:47:12.235 10976 11876 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1659219e, channel: 6, state: LISTENING
03-21 16:47:12.235 10976 11876 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1659219e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2dfb1a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a65a47fmSocket: android.net.LocalSocket@1e9fec4c impl:android.net.LocalSocketImpl@12def495 fd:FileDescriptor[112]
03-21 16:47:12.235 10976 11876 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e9fec4c impl:android.net.LocalSocketImpl@12def495 fd:FileDescriptor[112]
,03-21 16:47:12.235 10976 11940 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1549),
,03-21 16:47:12.240 10976 11876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-21 16:47:12.240 10976 11876 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 16:47:12.240 10976 11876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 16:47:12.245 10976 11876 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]},
03-21 16:47:12.245 10976 11876 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 16:47:12.245 10976 11876 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 16:47:12.245 10976 11876 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37b1b9aa
,03-21 16:47:12.245 10976 11876 D BluetoothSocket: channel: 6
03-21 16:47:12.245 10976 11876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 16:47:12.250  5849  5999 W bt-btif : new conn_srvc id:26, app_id:1,
03-21 16:47:12.255  5849  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 16:47:12.255  5849  5999 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
,03-21 16:47:12.255  5849  5999 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-21 16:47:12.255  5849 11643 E BluetoothRemoteDevices: setRfcommConnected true
,03-21 16:47:12.260 10976 11884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1548)
03-21 16:47:12.260 10976 11884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1548)
03-21 16:47:12.260 10976 11884 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 16:47:12.265 10976 11884 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 16:47:12.265 10976 11884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1550)
03-21 16:47:12.265 10976 11884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1550)
03-21 16:47:12.265 10976 11884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1548)
,03-21 16:47:12.270 10976 11941 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1550),
,03-21 16:47:12.525  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.525  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.525  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.525  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.525 10976 11940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1549)
,03-21 16:47:12.535 10976 11940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-21 16:47:12.540  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.540  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.540  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.545  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:12.545 10976 11940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1549),
,03-21 16:47:12.550 10976 11940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1549,
03-21 16:47:12.550 10976 11940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1549)
,03-21 16:47:12.555 10976 11940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51],
,03-21 16:47:12.555 10976 10976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51],
03-21 16:47:12.555 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 16:47:12.555 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 16:47:12.565 10976 10976 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 16:47:12.565 10976 10976 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 16:47:12.565 10976 10976 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-21 16:47:12.565 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0,
03-21 16:47:12.570  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:12.570  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.570  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.570  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.570 10976 11941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1550)
,03-21 16:47:12.570 10976 11941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-21 16:47:12.575 10976 11941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1548)
03-21 16:47:12.575 10976 11941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1548),
,03-21 16:47:12.575 10976 11941 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1550)
,03-21 16:47:12.580 10976 11940 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1549),
03-21 16:47:12.580 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:47:12.580 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:47:12.580 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:47:12.580 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:47:12.580 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:47:12.580 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:47:12.585  5849  5948 D BtGatt.AdvertiseManager: message : 1,
,03-21 16:47:12.585  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:47:12.585  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
,03-21 16:47:12.585  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:47:12.585  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:47:12.585  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:47:12.585  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:47:12.590 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:47:12.590 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:47:12.590 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:47:12.590 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:47:12.590 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:47:12.590 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:47:12.590 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:47:12.590 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 16:47:12.590 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:47:12.600  5849  6155 D BtGatt.GattService: registerClient() - UUID=600346e4-4338-4c3c-8490-58ae5b2fb7fb
,03-21 16:47:12.640  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=600346e4-4338-4c3c-8490-58ae5b2fb7fb, clientIf=7
,03-21 16:47:12.640 10976 11033 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:47:12.650  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 53
,03-21 16:47:12.655  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:47:12.655  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
,03-21 16:47:12.655  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:47:12.655  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:47:12.655  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:47:12.660  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:47:12.660  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:47:12.660  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:47:12.660  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:47:12.660  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 16:47:12.660 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:47:12.665  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:47:12.665  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:47:12.665  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 11
03-21 16:47:12.665  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:47:12.665 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 16:47:12.665 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:47:12.665 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:47:12.665 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 16:47:12.665 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:47:12.665 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:12.665  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:47:12.665  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.665  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:47:12.665  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:47:12.665  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.665  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:47:12.670  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:47:12.670  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:12.670  5849  6155 D BtGatt.GattService: registerClient() - UUID=9191de58-1e63-4193-978a-b87a98cf9276
,03-21 16:47:12.710  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=9191de58-1e63-4193-978a-b87a98cf9276, clientIf=6,
03-21 16:47:12.710 10976 10988 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:47:12.710  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:47:12.725  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 66
,03-21 16:47:12.725 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-21 16:47:12.725  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:47:12.725  5849  5949 D BtGatt.ScanManager: isFilteringSupported
,03-21 16:47:12.725  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:47:12.725 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:47:12.730  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:47:12.730  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.730  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:47:12.730  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:47:12.730  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:47:12.730  5849  5949 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-21 16:47:12.730  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:47:12.730  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:12.730  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:47:12.730  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:47:12.730  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.730  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:47:12.730  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.730  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.735  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:47:12.735  5849  5920 D BtGatt.GattService: Client app is not null!
,03-21 16:47:12.735  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 16:47:12.735 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:47:12.735 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 16:47:12.735 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:47:12.735 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:47:12.735 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:47:12.735 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:47:12.740 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 16:47:12.740  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:47:12.740  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.740 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:47:12.740 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 16:47:12.740  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 16:47:12.740  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:12.745  5849  6155 D BtGatt.GattService: registerClient() - UUID=f4c2a3a7-1a5a-4c28-85c2-46a20ac0571e
,03-21 16:47:12.785  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=f4c2a3a7-1a5a-4c28-85c2-46a20ac0571e, clientIf=7
,03-21 16:47:12.785 10976 10986 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:47:12.800  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 54
,03-21 16:47:12.800  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.800  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:47:12.800  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.800  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:12.800  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:12.800  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:47:12.800  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:47:12.800  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:47:12.800  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:47:12.805  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:47:12.805  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:47:12.810  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-21 16:47:12.810  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:47:12.810  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 16:47:12.810 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:47:12.815  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:47:12.815  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:47:12.815  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 12
03-21 16:47:12.815  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 16:47:12.815  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 16:47:12.815  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.815  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
03-21 16:47:12.815 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:47:12.815 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:47:12.815 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 16:47:12.815 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:47:12.815 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:47:12.815 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 16:47:12.820  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:47:12.820  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.820  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 16:47:12.825  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:47:12.825  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:12.825  5849  6155 D BtGatt.GattService: registerClient() - UUID=9c8f49c0-6f44-40d2-9ba3-86398f981126
,03-21 16:47:12.870  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=9c8f49c0-6f44-40d2-9ba3-86398f981126, clientIf=6
03-21 16:47:12.870 10976 11033 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
03-21 16:47:12.875  5849  5857 D BtGatt.GattService: start scan with filters
,03-21 16:47:12.905  5849  5857 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 67
,03-21 16:47:12.905  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:47:12.905  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:47:12.905  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:47:12.910  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:47:12.910  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:12.910  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:47:12.910  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:47:12.910  5849  5949 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-21 16:47:12.915  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:47:12.915  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:12.915  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:47:12.915  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:47:12.915  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:47:12.915  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:12.920  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:47:12.920  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:12.925 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:47:12.925 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 16:47:12.930  5849  5948 D BtGatt.AdvertiseManager: message : 1
03-21 16:47:12.930  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:47:12.930  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:47:12.935  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:47:12.935  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 16:47:12.935  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:47:12.935  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:47:12.935 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:47:12.935 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 16:47:12.935 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 16:47:12.935 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 16:47:12.935 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 16:47:12.935 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 16:47:12.935 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:47:12.935 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 16:47:12.935 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 16:47:12.945  5849 11643 D BtGatt.GattService: registerClient() - UUID=3a5d586e-0005-4102-bd83-cf26d30216ed
,03-21 16:47:12.985  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=3a5d586e-0005-4102-bd83-cf26d30216ed, clientIf=7
,03-21 16:47:12.985 10976 10988 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 16:47:13.000  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 55
,03-21 16:47:13.000  5849  5948 D BtGatt.AdvertiseManager: message : 0
03-21 16:47:13.000  5849  5948 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 16:47:13.000  5849  5948 D BtGatt.AdvertiseManager: size of list is =0
,03-21 16:47:13.000  5849  5948 D BtGatt.AdvertiseManager: starting advertising
,03-21 16:47:13.000  5849  5948 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 16:47:13.005  5849  5920 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 16:47:13.005  5849  5948 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 16:47:13.005  5849  5920 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 16:47:13.005  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 16:47:13.005  5849  5948 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 16:47:13.005 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 16:47:13.010  5849  5857 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:47:13.010  5849 11643 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 16:47:13.010 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:47:13.010 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 16:47:13.010 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:47:13.010 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 16:47:13.010 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 16:47:13.010 10976 10976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 16:47:13.010  5849  5949 D BtGatt.ScanManager: filter size is 1
,03-21 16:47:13.010  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 13
,03-21 16:47:13.015  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 16:47:13.015  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:13.015  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:47:13.015  5849 11643 D BtGatt.GattService: registerClient() - UUID=386d3383-3464-4c23-8952-ebb68dc00516
,03-21 16:47:13.020  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 16:47:13.020  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:13.020  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:47:13.020  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 16:47:13.020  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:13.060  5849  5920 D BtGatt.GattService: onClientRegistered() - UUID=386d3383-3464-4c23-8952-ebb68dc00516, clientIf=6
03-21 16:47:13.060 10976 10986 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 16:47:13.060  5849  5861 D BtGatt.GattService: start scan with filters
,03-21 16:47:13.080  5849  5861 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 68
,03-21 16:47:13.080  5849  5949 D BtGatt.ScanManager: handling starting scan
03-21 16:47:13.080  5849  5949 D BtGatt.ScanManager: isFilteringSupported
03-21 16:47:13.080  5849  5949 D BluetoothAdapter: setting StandAloneBleMode
,03-21 16:47:13.085  5849  5920 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 16:47:13.085  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:13.090  5849  5949 D BtGatt.ScanManager: allow scan with filters
03-21 16:47:13.090  5849  5949 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 16:47:13.090  5849  5949 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
,03-21 16:47:13.090  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 16:47:13.090  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:13.095  5849  5949 D BtGatt.ScanManager: Starting BLE batch scan
03-21 16:47:13.095  5849  5949 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 16:47:13.100  5849  5920 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 16:47:13.100  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:13.100  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 16:47:13.100  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 16:47:13.100 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 16:47:13.100 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 16:47:13.105 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 16:47:13.105 10976 10976 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-21 16:47:13.105 10976 10976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 16:47:13.105 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:47:13.105 10976 10976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 16:47:13.105 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
03-21 16:47:13.105 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-21 16:47:13.105 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 16:47:13.105 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 16:47:13.105 10976 10976 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 16:47:13.105 10976 10976 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 16:47:13.110 10976 10976 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 16:47:13.110 10976 10976 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-21 16:47:13.110 10976 10976 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-21 16:47:13.120 10976 11966 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1551),
03-21 16:47:13.120 10976 11967 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1552)
03-21 16:47:13.125 10976 11967 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49975
,03-21 16:47:13.125 10976 11967 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-21 16:47:13.125 10976 11967 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 49975 (peer ID: F8:95:C7:87:3C:51)
03-21 16:47:13.125 10976 11040 I jxcore-log: DEBUG createPeerListener: forward connection
03-21 16:47:13.125 10976 11040 I jxcore-log: 
,03-21 16:47:13.130  2876  3383 D EnterpriseController: netId is 0
03-21 16:47:13.130  2876  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 16:47:13.130 10976 11967 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-21 16:47:13.135 10976 11967 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 49975,
03-21 16:47:13.135 10976 11967 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-21 16:47:13.135 10976 11967 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 16:47:13.135 10976 11967 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 16:47:13.135 10976 11967 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1552)
03-21 16:47:13.135 10976 11967 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1552)
,03-21 16:47:13.135 10976 11966 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 48825,
03-21 16:47:13.135 10976 11966 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-21 16:47:13.140 10976 11966 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 16:47:13.140 10976 11966 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 16:47:13.140 10976 11966 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1551)
03-21 16:47:13.140 10976 11966 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1551)
,03-21 16:47:13.145 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-21 16:47:13.145 10976 11040 I jxcore-log: 
,03-21 16:47:13.145 10976 11970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1554, name: Receiver),
,03-21 16:47:13.145 10976 11969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1553, name: Sender)
,03-21 16:47:13.150 10976 11972 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1556, name: Receiver),
,03-21 16:47:13.150 10976 11971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1555, name: Sender)
,03-21 16:47:13.155 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-21 16:47:13.155 10976 11040 I jxcore-log: 
,03-21 16:47:13.170 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:47:13.170 10976 11040 I jxcore-log: 
,03-21 16:47:13.180  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:13.180  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.180  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.180  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.180  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:13.185  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.185  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.185  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.185  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.185  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.185  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.185  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.190 10976 11040 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 16:47:13.190 10976 11040 I jxcore-log: 
,03-21 16:47:13.190 10976 11040 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 16:47:13.190 10976 11040 I jxcore-log: 
,03-21 16:47:13.230  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 16:47:13.230  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.230  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.235  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.235  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.235  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.235  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.235  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.240  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:13.240  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.240  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.240  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.240 10976 11040 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 16:47:13.240 10976 11040 I jxcore-log: 
,03-21 16:47:13.245  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:13.245  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.245  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.245  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.470  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 16:47:13.470  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.470  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.470  5849  5999 D IOP_DB_BT: db_query: result 1,
,03-21 16:47:13.505 10976 11040 I jxcore-log: ok 206 server should return 200
03-21 16:47:13.505 10976 11040 I jxcore-log: 
,03-21 16:47:13.515 10976 11040 I jxcore-log: ok 207 response body should match testData
03-21 16:47:13.515 10976 11040 I jxcore-log: 
,03-21 16:47:13.530 10976 11040 I jxcore-log: # setup
03-21 16:47:13.530 10976 11040 I jxcore-log: 
,03-21 16:47:13.540  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:13.540  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.540  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.540  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.545 10976 11969 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1553, thread name: Sender)
03-21 16:47:13.545 10976 11969 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 16:47:13.545 10976 11969 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 16:47:13.545 10976 11969 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
03-21 16:47:13.545 10976 11969 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1552)
03-21 16:47:13.545 10976 11969 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1552)
03-21 16:47:13.545 10976 11969 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34074511, channel: 7, state: CONNECTED
03-21 16:47:13.545 10976 11969 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34074511, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a49c676, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2125a477mSocket: android.net.LocalSocket@2d78e4 impl:android.net.LocalSocketImpl@128a214d fd:FileDescriptor[116]
03-21 16:47:13.545 10976 11969 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d78e4 impl:android.net.LocalSocketImpl@128a214d fd:FileDescriptor[116]
03-21 16:47:13.545 10976 11969 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34074511, channel: 7, state: CLOSED
03-21 16:47:13.545 10976 11969 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34074511, channel: 7, state: CLOSED
03-21 16:47:13.545 10976 11969 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 16:47:13.545 10976 11969 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-21 16:47:13.545 10976 11969 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1554
03-21 16:47:13.545 10976 11969 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-21 16:47:13.545 10976 11969 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1553
03-21 16:47:13.545 10976 11969 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1552)
03-21 16:47:13.545  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.550  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.550  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.550 10976 11969 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1552)
03-21 16:47:13.550 10976 11969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-21 16:47:13.550 10976 11969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1553, name: Sender)
03-21 16:47:13.550  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.550 10976 11970 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1554, thread name: Receiver): bt socket closed, read return: -1
03-21 16:47:13.550 10976 11970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1554, name: Receiver)
,03-21 16:47:13.590  5849  5999 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 16:47:13.590  5849  5999 D IOP_DB_BT: db_query: result 1
03-21 16:47:13.590  5849  5999 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 16:47:13.590  5849  5999 D IOP_DB_BT: db_query: result 1
,03-21 16:47:13.645 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 16:47:13.645 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 16:47:13.645 10976 11040 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 16:47:13.645 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 16:47:13.645 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 16:47:13.645 10976 11040 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@983d402, channel: 6, state: LISTENING
03-21 16:47:13.645 10976 11040 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@983d402, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37b1b9aa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33461113mSocket: android.net.LocalSocket@35bb3f50 impl:android.net.LocalSocketImpl@35e48549 fd:FileDescriptor[117]
03-21 16:47:13.645 10976 11040 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35bb3f50 impl:android.net.LocalSocketImpl@35e48549 fd:FileDescriptor[117]
03-21 16:47:13.645 10976 11040 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 16:47:13.645 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 16:47:13.645 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 16:47:13.645 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 16:47:13.645 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 16:47:13.645 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 16:47:13.645 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 16:47:13.645 10976 11876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-21 16:47:13.645 10976 11876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-21 16:47:13.645 10976 11876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
,03-21 16:47:13.645  5849  5861 D BtGatt.GattService: stopScan() - queue size =1
,03-21 16:47:13.650  5849  5949 D BtGatt.ScanManager: filter size is 1
03-21 16:47:13.650  5849  5949 D BtGatt.ScanManager: delete FilterIndex - 14,
,03-21 16:47:13.650  5849  6155 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 16:47:13.650  5849  5920 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-21 16:47:13.650  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:13.650  5849  5949 D BtGatt.ScanManager: stopping BLe Batch
,03-21 16:47:13.655 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 16:47:13.655 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 16:47:13.655 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 16:47:13.655 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 16:47:13.655 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
,03-21 16:47:13.655 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 16:47:13.655 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 16:47:13.655  5849  5920 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 16:47:13.655  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:13.655  5849  5949 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 16:47:13.660  5849  5920 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
,03-21 16:47:13.660  5849  5920 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 16:47:13.665  5849  5948 D BtGatt.AdvertiseManager: message : 1
,03-21 16:47:13.665  5849  5948 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 16:47:13.665  5849  5948 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 16:47:13.665  5849  5948 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 16:47:13.665  5849  5920 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 16:47:13.665  5849  5920 D BtGatt.GattService: Client app is not null!
03-21 16:47:13.670  5849  5861 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 16:47:13.675 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 16:47:13.675 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 16:47:13.675 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 16:47:13.675 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-21 16:47:13.675 10976 11040 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 16:47:13.675 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:47:13.675 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 16:47:13.675 10976 11040 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 16:47:13.675 10976 11040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-21 16:47:13.675 10976 11040 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 16:47:13.675 10976 11040 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:47:13.680 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 16:47:13.680 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:47:13.680 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 16:47:13.690 10976 10976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 16:47:13.695 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:47:13.700 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-21 16:47:13.700 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-21 16:47:13.705 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 16:47:13.705 10976 10976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 16:47:13.705 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 16:47:13.705 10976 10976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 16:47:13.705 10976 10976 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-21 16:47:13.705 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 16:47:13.705 10976 10976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 16:47:13.705 10976 10976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 16:47:13.705 10976 11040 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 16:47:13.705 10976 11040 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-21 16:47:13.705 10976 11040 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 16:47:13.705 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 16:47:13.705 10976 11040 I jxcore-log: 
,03-21 16:47:13.720 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-21 16:47:13.720 10976 11040 I jxcore-log: 
,03-21 16:47:13.720 10976 11040 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 16:47:13.720 10976 11040 I jxcore-log: 
,03-21 16:47:13.725 10976 11971 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1555, thread name: Sender)
03-21 16:47:13.725 10976 11971 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 16:47:13.725 10976 11971 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 16:47:13.725 10976 11971 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1551
03-21 16:47:13.725 10976 11971 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1551)
03-21 16:47:13.725 10976 11971 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10f6ab6f, channel: 6, state: CONNECTED
03-21 16:47:13.725 10976 11971 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10f6ab6f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@281d007c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6672d05mSocket: android.net.LocalSocket@83e15a impl:android.net.LocalSocketImpl@c6c8f8b fd:FileDescriptor[115]
03-21 16:47:13.725 10976 11971 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@83e15a impl:android.net.LocalSocketImpl@c6c8f8b fd:FileDescriptor[115]
03-21 16:47:13.725 10976 11971 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10f6ab6f, channel: 6, state: CLOSED
03-21 16:47:13.725 10976 11971 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10f6ab6f, channel: 6, state: CLOSED
03-21 16:47:13.725 10976 11971 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 16:47:13.725 10976 11971 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-21 16:47:13.725 10976 11971 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1556
03-21 16:47:13.725 10976 11971 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-21 16:47:13.725 10976 11971 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1555
,03-21 16:47:13.725 10976 11971 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1551)
03-21 16:47:13.725 10976 11971 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1551)
,03-21 16:47:13.725 10976 11971 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-21 16:47:13.725 10976 11972 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1556, thread name: Receiver): bt socket closed, read return: -1
03-21 16:47:13.725 10976 11972 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1556, name: Receiver)
,03-21 16:47:13.730 10976 11971 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1555, name: Sender),
,03-21 16:47:13.735 10976 11040 I jxcore-log: DEBUG createNativeListener: mux close
03-21 16:47:13.735 10976 11040 I jxcore-log: 
,03-21 16:47:13.745 10976 11040 I jxcore-log: # 55. Test BEACONS_RETRIEVED_AND_PARSED locally
03-21 16:47:13.745 10976 11040 I jxcore-log: 
,03-21 16:47:13.745 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:47:13.745 10976 11040 I jxcore-log: 
,03-21 16:47:13.750 10976 11040 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 16:47:13.750 10976 11040 I jxcore-log: 
,03-21 16:47:13.750 10976 11040 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 16:47:13.750 10976 11040 I jxcore-log: 
,03-21 16:47:13.885  5849  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
03-21 16:47:13.885  5849  5999 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-21 16:47:14.020 10976 11040 I jxcore-log: # teardown
03-21 16:47:14.020 10976 11040 I jxcore-log: 
,03-21 16:47:14.065  5849  5999 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,03-21 16:47:14.290 10976 11040 I jxcore-log: ok 208 peerIdentifier should be hello
03-21 16:47:14.290 10976 11040 I jxcore-log: 
,03-21 16:47:14.290 10976 11040 I jxcore-log: ok 209 Response should be BEACONS_RETRIEVED_AND_PARSED
03-21 16:47:14.290 10976 11040 I jxcore-log: 
,03-21 16:47:14.290 10976 11040 I jxcore-log: ok 210 good beacon
03-21 16:47:14.290 10976 11040 I jxcore-log: 
,03-21 16:47:14.295 10976 11040 I jxcore-log: ok 211 good preAmble
03-21 16:47:14.295 10976 11040 I jxcore-log: 
03-21 16:47:14.295 10976 11040 I jxcore-log: ok 212 public keys match!
03-21 16:47:14.295 10976 11040 I jxcore-log: 
,03-21 16:47:14.295 10976 11040 I jxcore-log: ok 213 must return null after successful call
03-21 16:47:14.295 10976 11040 I jxcore-log: 
,03-21 16:47:14.305 10976 11040 I jxcore-log: # setup
03-21 16:47:14.305 10976 11040 I jxcore-log: 
,03-21 16:47:14.400 10976 11040 I jxcore-log: # 56. Test HTTP_BAD_RESPONSE locally
03-21 16:47:14.400 10976 11040 I jxcore-log: 
,03-21 16:47:14.660 10976 11040 I jxcore-log: # teardown
03-21 16:47:14.660 10976 11040 I jxcore-log: 
,03-21 16:47:14.910 10976 11040 I jxcore-log: ok 214 Response should be HTTP_BAD_RESPONSE
03-21 16:47:14.910 10976 11040 I jxcore-log: 
,03-21 16:47:14.910 10976 11040 I jxcore-log: ok 215 must return null after successful call
03-21 16:47:14.910 10976 11040 I jxcore-log: 
,03-21 16:47:14.930 10976 11040 I jxcore-log: # setup
03-21 16:47:14.930 10976 11040 I jxcore-log: 
,03-21 16:47:15.080  3390  4729 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:47:15.080  3390  4729 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:47:15.080  3390  4729 D BatteryService: online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,03-21 16:47:15.080  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 16:47:15.085  3390  4729 D BatteryService: stay LED for fully charged
,03-21 16:47:15.090  3390  3390 I MotionRecognitionService: Plugged
03-21 16:47:15.090  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:47:15.090  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:47:15.090  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:47:15.100  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 16:47:15.100  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:15.100  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:47:15.120  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:47:15.125  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:47:15.130  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:15.130  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:15.130  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:15.130  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:15.135  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:12), CUR = 37, LCD = 0
,03-21 16:47:15.190 10976 11040 I jxcore-log: # 57. Test NETWORK_PROBLEM locally
03-21 16:47:15.190 10976 11040 I jxcore-log: 
,03-21 16:47:15.435 10976 11040 I jxcore-log: # teardown
03-21 16:47:15.435 10976 11040 I jxcore-log: 
,03-21 16:47:15.480  2876  3383 D EnterpriseController: netId is 0
03-21 16:47:15.480  2876  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 16:47:16.105 10976 11040 I jxcore-log: ok 216 Response should be NETWORK_PROBLEM
03-21 16:47:16.105 10976 11040 I jxcore-log: 
,03-21 16:47:16.105 10976 11040 I jxcore-log: ok 217 reject reason should be: Could not establish TCP connection
03-21 16:47:16.105 10976 11040 I jxcore-log: 
,03-21 16:47:16.120 10976 11040 I jxcore-log: # setup
03-21 16:47:16.120 10976 11040 I jxcore-log: 
,03-21 16:47:17.145 10976 11040 I jxcore-log: # 58. Test timeout locally
03-21 16:47:17.145 10976 11040 I jxcore-log: 
,03-21 16:47:17.350 10976 11040 I jxcore-log: # teardown
03-21 16:47:17.350 10976 11040 I jxcore-log: 
,03-21 16:47:17.855  5849  5999 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
,03-21 16:47:17.855  5849  5999 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-21 16:47:17.855  5849  5999 W bt-btif : bta_dm_acl_change(), event : 1
03-21 16:47:17.855  5849  5999 W bt-btif : bta_dm_acl_change(), event : 2
03-21 16:47:17.860  5849  5920 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-21 16:47:17.880  3726  3726 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-21 16:47:17.880  5849  5920 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 16:47:17.890  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 16:47:17.890  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED,
03-21 16:47:17.890  3390  3390 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-21 16:47:17.900  3390  3576 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bee12a3 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{140cc3b3 5849:com.android.bluetooth/1002}
,03-21 16:47:17.910  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a47f10c
03-21 16:47:17.915  3390  3651 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-21 16:47:17.910  5849  5849 D BtConfig.SecureMode: isSecureModeOn:false
03-21 16:47:17.910  3390  4729 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-21 16:47:17.920  5849  5849 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-21 16:47:17.920  3726  3726 D KeyguardViewMediator: isGear1: device is not B1!
,03-21 16:47:17.925  3390  4727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bee12a3 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:47:17.935  3390  4730 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 16:47:17.950 10183 12065 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-21 16:47:17.950 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
03-21 16:47:17.950 10183 10183 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-21 16:47:17.955 10183 10183 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
,03-21 16:47:17.955 10183 10183 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-21 16:47:17.960  3390  3423 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bee12a3 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:47:17.970  3390  3423 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bee12a3 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{322e8b0e 11771:com.sec.android.app.shealth/u0a36}
,03-21 16:47:17.980  3390  4729 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bee12a3 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{c7a662d 4113:com.google.android.googlequicksearchbox:search/u0a64}
,03-21 16:47:17.985  4113  4113 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-21 16:47:17.985  4113  4113 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-21 16:47:18.535 10976 11040 I jxcore-log: ok 218 Should be NETWORK_PROBLEM caused by timeout
03-21 16:47:18.535 10976 11040 I jxcore-log: 
,03-21 16:47:18.540 10976 11040 I jxcore-log: ok 219 reject reason should be Could not establish TCP connection
03-21 16:47:18.540 10976 11040 I jxcore-log: 
,03-21 16:47:18.555 10976 11040 I jxcore-log: # setup
03-21 16:47:18.555 10976 11040 I jxcore-log: 
,03-21 16:47:18.670  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:47:19.185 10976 11040 I jxcore-log: # 59. Call the start two times
03-21 16:47:19.185 10976 11040 I jxcore-log: 
,03-21 16:47:19.395 10976 11040 I jxcore-log: # teardown
03-21 16:47:19.395 10976 11040 I jxcore-log: 
,03-21 16:47:19.500 10976 11040 I jxcore-log: ok 220 Call start once
03-21 16:47:19.500 10976 11040 I jxcore-log: 
,03-21 16:47:19.575 10976 11040 I jxcore-log: ok 221 Response should be BEACONS_RETRIEVED_AND_PARSED
03-21 16:47:19.575 10976 11040 I jxcore-log: 
,03-21 16:47:19.575 10976 11040 I jxcore-log: ok 222 must return null after successful call.
03-21 16:47:19.575 10976 11040 I jxcore-log: 
,03-21 16:47:19.590 10976 11040 I jxcore-log: # setup
03-21 16:47:19.590 10976 11040 I jxcore-log: 
,03-21 16:47:19.685 10976 11040 I jxcore-log: # 60. Call the kill before calling the start
03-21 16:47:19.685 10976 11040 I jxcore-log: 
,03-21 16:47:19.890 10976 11040 I jxcore-log: # teardown
03-21 16:47:19.890 10976 11040 I jxcore-log: 
,03-21 16:47:19.975 10976 11040 I jxcore-log: ok 223 Should be Killed
03-21 16:47:19.975 10976 11040 I jxcore-log: 
,03-21 16:47:19.980 10976 11040 I jxcore-log: ok 224 Start after killed
03-21 16:47:19.980 10976 11040 I jxcore-log: 
,03-21 16:47:19.990 10976 11040 I jxcore-log: # setup
03-21 16:47:19.990 10976 11040 I jxcore-log: 
,03-21 16:47:20.060 10976 11040 I jxcore-log: # 61. Call the kill immediately after the start
03-21 16:47:20.060 10976 11040 I jxcore-log: 
,03-21 16:47:20.255 10976 11040 I jxcore-log: # teardown
03-21 16:47:20.255 10976 11040 I jxcore-log: 
,03-21 16:47:20.325 10976 11040 I jxcore-log: ok 225 Should be KILLED
03-21 16:47:20.325 10976 11040 I jxcore-log: 
,03-21 16:47:20.325 10976 11040 I jxcore-log: ok 226 must return null after successful kill
03-21 16:47:20.325 10976 11040 I jxcore-log: 
,03-21 16:47:20.335 10976 11040 I jxcore-log: # setup
03-21 16:47:20.335 10976 11040 I jxcore-log: 
,03-21 16:47:20.410 10976 11040 I jxcore-log: # 62. Call the kill while waiting a response from the server
03-21 16:47:20.410 10976 11040 I jxcore-log: 
,03-21 16:47:20.670 10976 11040 I jxcore-log: # teardown
03-21 16:47:20.670 10976 11040 I jxcore-log: 
,03-21 16:47:22.755 10976 11040 I jxcore-log: ok 227 Should be KILLED,
03-21 16:47:22.755 10976 11040 I jxcore-log: 
,03-21 16:47:22.765 10976 11040 I jxcore-log: ok 228 must return null after successful kill
03-21 16:47:22.765 10976 11040 I jxcore-log: 
,03-21 16:47:22.790 10976 11040 I jxcore-log: # setup
03-21 16:47:22.790 10976 11040 I jxcore-log: 
,03-21 16:47:22.915 10976 11040 I jxcore-log: # 63. Test to exceed the max content size locally
03-21 16:47:22.915 10976 11040 I jxcore-log: 
,03-21 16:47:23.100 10976 11040 I jxcore-log: # teardown
03-21 16:47:23.100 10976 11040 I jxcore-log: 
,03-21 16:47:23.290 10976 11040 I jxcore-log: ok 229 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-21 16:47:23.290 10976 11040 I jxcore-log: 
,03-21 16:47:23.295 10976 11040 I jxcore-log: ok 230 must return null after successful call
03-21 16:47:23.295 10976 11040 I jxcore-log: 
,03-21 16:47:23.305 10976 11040 I jxcore-log: # setup
03-21 16:47:23.305 10976 11040 I jxcore-log: 
,03-21 16:47:23.380 10976 11040 I jxcore-log: # 64. Close the server socket while the client is waiting a response from the server. Local test.
03-21 16:47:23.380 10976 11040 I jxcore-log: 
,03-21 16:47:23.630 10976 11040 I jxcore-log: # teardown
03-21 16:47:23.630 10976 11040 I jxcore-log: 
,03-21 16:47:25.155  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:14), CUR = 35, LCD = 0
,03-21 16:47:25.220  3390  4242 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:47:25.220  3390  4242 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:47:25.220  3390  4242 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
03-21 16:47:25.220  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 16:47:25.220  3390  4242 D BatteryService: stay LED for fully charged
,03-21 16:47:25.230  3390  3390 I MotionRecognitionService: Plugged
03-21 16:47:25.230  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:47:25.230  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:47:25.230  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:47:25.235  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 16:47:25.235  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:25.235  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:47:25.250  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:47:25.250  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:47:25.260  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:25.265  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:25.265  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:25.265  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:25.825 10976 11040 I jxcore-log: ok 231 Should be NETWORK_PROBLEM caused closing server socket
03-21 16:47:25.825 10976 11040 I jxcore-log: 
,03-21 16:47:25.830 10976 11040 I jxcore-log: ok 232 Should be Could not establish TCP connection
03-21 16:47:25.830 10976 11040 I jxcore-log: 
,03-21 16:47:25.850 10976 11040 I jxcore-log: # setup
03-21 16:47:25.850 10976 11040 I jxcore-log: 
,03-21 16:47:25.935 10976 11040 I jxcore-log: # 65. Close the client socket while the client is waiting a response from the server. Local test.
03-21 16:47:25.935 10976 11040 I jxcore-log: 
,03-21 16:47:26.140 10976 11040 I jxcore-log: # teardown
03-21 16:47:26.140 10976 11040 I jxcore-log: 
,03-21 16:47:28.265 10976 11040 I jxcore-log: ok 233 Should be NETWORK_PROBLEM caused closing client socket
03-21 16:47:28.265 10976 11040 I jxcore-log: 
,03-21 16:47:28.270 10976 11040 I jxcore-log: ok 234 Should be Could not establish TCP connection
03-21 16:47:28.270 10976 11040 I jxcore-log: 
,03-21 16:47:28.290 10976 11040 I jxcore-log: # setup
03-21 16:47:28.290 10976 11040 I jxcore-log: 
,03-21 16:47:28.415 10976 11040 I jxcore-log: # 66. #generatePreambleAndBeacons bad args
03-21 16:47:28.415 10976 11040 I jxcore-log: 
,03-21 16:47:28.505 10976 11040 I jxcore-log: # teardown
03-21 16:47:28.505 10976 11040 I jxcore-log: 
,03-21 16:47:28.600 10976 10976 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 16:47:28.600 10976 10976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanS,ettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 16:47:28.660 10976 11040 I jxcore-log: ok 235 publicKeysToNotify cannot be null
03-21 16:47:28.660 10976 11040 I jxcore-log: 
,03-21 16:47:28.665 10976 11040 I jxcore-log: ok 236 ecdh for local device cannot be null
03-21 16:47:28.665 10976 11040 I jxcore-log: 
,03-21 16:47:28.665 10976 11040 I jxcore-log: ok 237 milliseconds cannot be less than 0
03-21 16:47:28.665 10976 11040 I jxcore-log: 
,03-21 16:47:28.670 10976 11040 I jxcore-log: ok 238 milliseconds cannot be 0
03-21 16:47:28.670 10976 11040 I jxcore-log: 
,03-21 16:47:28.675 10976 11040 I jxcore-log: ok 239 milliseconds cannot be greater than one_day
03-21 16:47:28.675 10976 11040 I jxcore-log: 
,03-21 16:47:28.680 10976 11040 I jxcore-log: # setup
03-21 16:47:28.680 10976 11040 I jxcore-log: 
,03-21 16:47:28.830 10976 11040 I jxcore-log: # 67. #generatePreambleAndBeacons empty keys to notify
03-21 16:47:28.830 10976 11040 I jxcore-log: 
,03-21 16:47:28.990 10976 11040 I jxcore-log: # teardown
03-21 16:47:28.990 10976 11040 I jxcore-log: 
,03-21 16:47:29.055 10976 11040 I jxcore-log: ok 240 should be equal
03-21 16:47:29.055 10976 11040 I jxcore-log: 
,03-21 16:47:29.060 10976 11040 I jxcore-log: # setup
03-21 16:47:29.060 10976 11040 I jxcore-log: 
,03-21 16:47:29.240 10976 11040 I jxcore-log: # 68. #generatePreambleAndBeacons multiple keys to notify
03-21 16:47:29.240 10976 11040 I jxcore-log: 
,03-21 16:47:29.440 10976 11040 I jxcore-log: # teardown
03-21 16:47:29.440 10976 11040 I jxcore-log: 
,03-21 16:47:29.450  3390  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 16:47:29.450  3390  3653 V NetworkStats: performPollLocked(flags=0x1)
,03-21 16:47:29.465  3390  3653 V NetworkStats: performPollLocked() took 12ms
,03-21 16:47:29.465  3390  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 16:47:29.470  3390  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 16:47:29.470  3390  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 16:47:29.725 10976 11040 I jxcore-log: ok 241 should be equal
03-21 16:47:29.725 10976 11040 I jxcore-log: 
,03-21 16:47:29.725 10976 11040 I jxcore-log: ok 242 should be equal
03-21 16:47:29.725 10976 11040 I jxcore-log: 
,03-21 16:47:29.730 10976 11040 I jxcore-log: ok 243 (unnamed assert)
03-21 16:47:29.730 10976 11040 I jxcore-log: 
,03-21 16:47:29.730 10976 11040 I jxcore-log: ok 244 should be equal
03-21 16:47:29.730 10976 11040 I jxcore-log: 
,03-21 16:47:29.730 10976 11040 I jxcore-log: # setup
03-21 16:47:29.730 10976 11040 I jxcore-log: 
,03-21 16:47:29.860 10976 11040 I jxcore-log: # 69. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-21 16:47:29.860 10976 11040 I jxcore-log: 
,03-21 16:47:30.050 10976 11040 I jxcore-log: # teardown
03-21 16:47:30.050 10976 11040 I jxcore-log: 
,03-21 16:47:30.150 10976 11040 I jxcore-log: ok 245 should throw
03-21 16:47:30.150 10976 11040 I jxcore-log: 
,03-21 16:47:30.155 10976 11040 I jxcore-log: # setup
03-21 16:47:30.155 10976 11040 I jxcore-log: 
,03-21 16:47:30.255 10976 11040 I jxcore-log: # 70. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-21 16:47:30.255 10976 11040 I jxcore-log: 
,03-21 16:47:30.375 10976 11040 I jxcore-log: # teardown
03-21 16:47:30.375 10976 11040 I jxcore-log: 
,03-21 16:47:30.565 10976 11040 I jxcore-log: ok 246 Preamble expiration must be a 64 bit integer
03-21 16:47:30.565 10976 11040 I jxcore-log: 
,03-21 16:47:30.570 10976 11040 I jxcore-log: # setup
03-21 16:47:30.570 10976 11040 I jxcore-log: 
,03-21 16:47:30.695 10976 11040 I jxcore-log: # 71. #parseBeacons expiration out of range lower
03-21 16:47:30.695 10976 11040 I jxcore-log: 
,03-21 16:47:30.835 10976 11040 I jxcore-log: # teardown
03-21 16:47:30.835 10976 11040 I jxcore-log: 
,03-21 16:47:30.960 10976 11040 I jxcore-log: ok 247 Expiration out of range
03-21 16:47:30.960 10976 11040 I jxcore-log: 
,03-21 16:47:30.965 10976 11040 I jxcore-log: # setup
03-21 16:47:30.965 10976 11040 I jxcore-log: 
,03-21 16:47:31.075 10976 11040 I jxcore-log: # 72. #parseBeacons expiration out of range lower
03-21 16:47:31.075 10976 11040 I jxcore-log: 
,03-21 16:47:31.175 10976 11040 I jxcore-log: # teardown
03-21 16:47:31.175 10976 11040 I jxcore-log: 
,03-21 16:47:31.305 10976 11040 I jxcore-log: ok 248 Expiration out of range
03-21 16:47:31.305 10976 11040 I jxcore-log: 
,03-21 16:47:31.320 10976 11040 I jxcore-log: # setup
03-21 16:47:31.320 10976 11040 I jxcore-log: 
,03-21 16:47:31.440 10976 11040 I jxcore-log: # 73. #parseBeacons no beacons returns null
03-21 16:47:31.440 10976 11040 I jxcore-log: 
,03-21 16:47:31.535  3390  3864 E Watchdog: !@Sync 9 [03-21 16:47:31.537]
,03-21 16:47:31.560 10976 11040 I jxcore-log: # teardown
03-21 16:47:31.560 10976 11040 I jxcore-log: 
,03-21 16:47:31.710 10976 11040 I jxcore-log: ok 249 should be equal
03-21 16:47:31.710 10976 11040 I jxcore-log: 
,03-21 16:47:31.715 10976 11040 I jxcore-log: # setup
03-21 16:47:31.715 10976 11040 I jxcore-log: 
,03-21 16:47:31.790 10976 11040 I jxcore-log: # 74. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-21 16:47:31.790 10976 11040 I jxcore-log: 
,03-21 16:47:31.940 10976 11040 I jxcore-log: # teardown
03-21 16:47:31.940 10976 11040 I jxcore-log: 
,03-21 16:47:32.115 10976 11040 I jxcore-log: ok 250 Malformed encrypted beacon key ID
03-21 16:47:32.115 10976 11040 I jxcore-log: 
,03-21 16:47:32.120 10976 11040 I jxcore-log: # setup
03-21 16:47:32.120 10976 11040 I jxcore-log: 
,03-21 16:47:32.200 10976 11040 I jxcore-log: # 75. #parseBeacons addressBookCallback fails decrypt
03-21 16:47:32.200 10976 11040 I jxcore-log: 
,03-21 16:47:32.290 10976 11040 I jxcore-log: # teardown
03-21 16:47:32.290 10976 11040 I jxcore-log: 
,03-21 16:47:32.840 10976 11040 I jxcore-log: ok 251 should be equal
03-21 16:47:32.840 10976 11040 I jxcore-log: 
,03-21 16:47:32.845 10976 11040 I jxcore-log: # setup
03-21 16:47:32.845 10976 11040 I jxcore-log: 
,03-21 16:47:33.120 10976 11040 I jxcore-log: # 76. #parseBeacons addressBookCallback returns no matches
03-21 16:47:33.120 10976 11040 I jxcore-log: 
,03-21 16:47:33.225 10976 11040 I jxcore-log: # teardown
03-21 16:47:33.225 10976 11040 I jxcore-log: 
,03-21 16:47:33.455 10976 11040 I jxcore-log: ok 252 should be equal
03-21 16:47:33.455 10976 11040 I jxcore-log: 
,03-21 16:47:33.455 10976 11040 I jxcore-log: ok 253 should be equal
03-21 16:47:33.455 10976 11040 I jxcore-log: 
,03-21 16:47:33.460 10976 11040 I jxcore-log: # setup
03-21 16:47:33.460 10976 11040 I jxcore-log: 
,03-21 16:47:33.570 10976 11040 I jxcore-log: # 77. #parseBeacons addressBookCallback returns spurious match
03-21 16:47:33.570 10976 11040 I jxcore-log: 
,03-21 16:47:33.710 10976 11040 I jxcore-log: # teardown
03-21 16:47:33.710 10976 11040 I jxcore-log: 
,03-21 16:47:34.060 10976 11040 I jxcore-log: ok 254 should be equal
03-21 16:47:34.060 10976 11040 I jxcore-log: 
,03-21 16:47:34.060 10976 11040 I jxcore-log: ok 255 should be equal
03-21 16:47:34.060 10976 11040 I jxcore-log: 
,03-21 16:47:34.065 10976 11040 I jxcore-log: # setup
03-21 16:47:34.065 10976 11040 I jxcore-log: 
,03-21 16:47:34.165 10976 11040 I jxcore-log: # 78. #parseBeacons addressBookCallback returns public key
03-21 16:47:34.165 10976 11040 I jxcore-log: 
,03-21 16:47:34.270 10976 11040 I jxcore-log: # teardown
03-21 16:47:34.270 10976 11040 I jxcore-log: 
,03-21 16:47:34.480  3390  3576 W ProcessCpuTracker: Skipping unknown process pid 12239
,03-21 16:47:34.520 10976 11040 I jxcore-log: ok 256 right number of calls to address book
03-21 16:47:34.520 10976 11040 I jxcore-log: 
,03-21 16:47:34.520 10976 11040 I jxcore-log: ok 257 good preAmble
03-21 16:47:34.520 10976 11040 I jxcore-log: 
03-21 16:47:34.520 10976 11040 I jxcore-log: ok 258 good unencryptedKeyId
03-21 16:47:34.520 10976 11040 I jxcore-log: 
,03-21 16:47:34.525 10976 11040 I jxcore-log: ok 259 good beacon
03-21 16:47:34.525 10976 11040 I jxcore-log: 
,03-21 16:47:34.525 10976 11040 I jxcore-log: # setup
03-21 16:47:34.525 10976 11040 I jxcore-log: 
,03-21 16:47:34.640 10976 11040 I jxcore-log: # 79. validate generatePskIdentityField
03-21 16:47:34.640 10976 11040 I jxcore-log: 
,03-21 16:47:34.815 10976 11040 I jxcore-log: # teardown
03-21 16:47:34.815 10976 11040 I jxcore-log: 
,03-21 16:47:34.950 10976 11040 I jxcore-log: ok 260 decoded buffers match
03-21 16:47:34.950 10976 11040 I jxcore-log: 
,03-21 16:47:34.955 10976 11040 I jxcore-log: # setup
03-21 16:47:34.955 10976 11040 I jxcore-log: 
,03-21 16:47:35.130 10976 11040 I jxcore-log: # 80. validate generatePskSecret
03-21 16:47:35.130 10976 11040 I jxcore-log: 
,03-21 16:47:35.175  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:14), CUR = 35, LCD = 0
,03-21 16:47:35.330 10976 11040 I jxcore-log: # teardown
03-21 16:47:35.330 10976 11040 I jxcore-log: 
,03-21 16:47:35.360  3390  4727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:47:35.360  3390  4727 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:47:35.360  3390  4727 D BatteryService: online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
03-21 16:47:35.360  3390  4727 D BatteryService: stay LED for fully charged
,03-21 16:47:35.360  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:47:35.365  3390  3390 I MotionRecognitionService: Plugged
03-21 16:47:35.365  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:47:35.365  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:47:35.365  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:47:35.370  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:35.370  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 16:47:35.375  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:47:35.385  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 16:47:35.385  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:47:35.395  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:35.395  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:35.395  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:35.400  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:35.480 10976 11040 I jxcore-log: ok 261 secrets match
03-21 16:47:35.480 10976 11040 I jxcore-log: 
,03-21 16:47:35.485 10976 11040 I jxcore-log: # setup
03-21 16:47:35.485 10976 11040 I jxcore-log: 
,03-21 16:47:35.660 10976 11040 I jxcore-log: # 81. Start and stop ThaliNotificationServer
03-21 16:47:35.660 10976 11040 I jxcore-log: 
,03-21 16:47:36.830 10976 11040 I jxcore-log: # teardown
03-21 16:47:36.830 10976 11040 I jxcore-log: 
,03-21 16:47:37.040 10976 11040 I jxcore-log: ok 262 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-21 16:47:37.040 10976 11040 I jxcore-log: 
,03-21 16:47:37.040 10976 11040 I jxcore-log: ok 263 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-21 16:47:37.040 10976 11040 I jxcore-log: 
,03-21 16:47:37.045 10976 11040 I jxcore-log: # setup
03-21 16:47:37.045 10976 11040 I jxcore-log: 
,03-21 16:47:37.360 10976 11040 I jxcore-log: # 82. Pass an empty array to ThaliNotificationServer.start
03-21 16:47:37.360 10976 11040 I jxcore-log: 
,03-21 16:47:37.555 10976 11040 I jxcore-log: # teardown
03-21 16:47:37.555 10976 11040 I jxcore-log: 
,03-21 16:47:37.675 10976 11040 I jxcore-log: ok 264 StartUpdateAdvertisingAndListening should not be called
03-21 16:47:37.675 10976 11040 I jxcore-log: 
,03-21 16:47:37.700 10976 11040 I jxcore-log: ok 265 ThaliMobile.StopAdvertisingAndListening should be called once
03-21 16:47:37.700 10976 11040 I jxcore-log: 
,03-21 16:47:37.760 10976 11040 I jxcore-log: ok 266 no error
03-21 16:47:37.760 10976 11040 I jxcore-log: 
,03-21 16:47:37.760 10976 11040 I jxcore-log: ok 267 should be 204
03-21 16:47:37.760 10976 11040 I jxcore-log: 
,03-21 16:47:37.765 10976 11040 I jxcore-log: # setup
03-21 16:47:37.765 10976 11040 I jxcore-log: 
,03-21 16:47:37.910 10976 11040 I jxcore-log: # 83. Pass a string to ThaliNotificationServer.start
03-21 16:47:37.910 10976 11040 I jxcore-log: 
,03-21 16:47:38.085 10976 11040 I jxcore-log: # teardown
03-21 16:47:38.085 10976 11040 I jxcore-log: 
,03-21 16:47:38.165 10976 11040 I jxcore-log: ok 268 StartUpdateAdvertisingAndListening should not be called
03-21 16:47:38.165 10976 11040 I jxcore-log: 
,03-21 16:47:38.165 10976 11040 I jxcore-log: # setup
03-21 16:47:38.165 10976 11040 I jxcore-log: 
,03-21 16:47:38.275 10976 11040 I jxcore-log: # 84. Pass an empty parameter to ThaliNotificationServer.start
03-21 16:47:38.275 10976 11040 I jxcore-log: 
,03-21 16:47:38.425 10976 11040 I jxcore-log: # teardown
03-21 16:47:38.425 10976 11040 I jxcore-log: 
,03-21 16:47:38.555 10976 11040 I jxcore-log: ok 269 StartUpdateAdvertisingAndListening should not be called
03-21 16:47:38.555 10976 11040 I jxcore-log: 
,03-21 16:47:38.560 10976 11040 I jxcore-log: # setup
03-21 16:47:38.560 10976 11040 I jxcore-log: 
,03-21 16:47:38.670  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:47:38.730 10976 11040 I jxcore-log: # 85. Make an HTTP request to /NotificationBeacons
03-21 16:47:38.730 10976 11040 I jxcore-log: 
,03-21 16:47:38.940 10976 11040 I jxcore-log: # teardown
03-21 16:47:38.940 10976 11040 I jxcore-log: 
,03-21 16:47:39.315 10976 11040 I jxcore-log: ok 270 no error
03-21 16:47:39.315 10976 11040 I jxcore-log: 
,03-21 16:47:39.315 10976 11040 I jxcore-log: ok 271 should be 200
03-21 16:47:39.315 10976 11040 I jxcore-log: 
03-21 16:47:39.315 10976 11040 I jxcore-log: ok 272 should be equal
03-21 16:47:39.315 10976 11040 I jxcore-log: 
,03-21 16:47:39.320 10976 11040 I jxcore-log: ok 273 should be equal
03-21 16:47:39.320 10976 11040 I jxcore-log: 
,03-21 16:47:39.345 10976 11040 I jxcore-log: ok 274 (unnamed assert)
03-21 16:47:39.345 10976 11040 I jxcore-log: 
,03-21 16:47:39.380 10976 11040 I jxcore-log: ok 275 no error
03-21 16:47:39.380 10976 11040 I jxcore-log: 
,03-21 16:47:39.385 10976 11040 I jxcore-log: ok 276 should be 204
03-21 16:47:39.385 10976 11040 I jxcore-log: 
,03-21 16:47:39.390 10976 11040 I jxcore-log: # setup
03-21 16:47:39.390 10976 11040 I jxcore-log: 
,03-21 16:47:39.480  3390  3583 I PowerManagerService: [PWL] Off : 225s ago
,03-21 16:47:39.830 10976 11040 I jxcore-log: # 86. Make an HTTP request to /NotificationBeacons (no keys)
03-21 16:47:39.830 10976 11040 I jxcore-log: 
,03-21 16:47:40.830 10976 11040 I jxcore-log: # teardown
03-21 16:47:40.830 10976 11040 I jxcore-log: 
,03-21 16:47:41.070 10976 11040 I jxcore-log: ok 277 error should be null
03-21 16:47:41.070 10976 11040 I jxcore-log: 
,03-21 16:47:41.070 10976 11040 I jxcore-log: ok 278 should be 204
03-21 16:47:41.070 10976 11040 I jxcore-log: 
,03-21 16:47:41.075 10976 11040 I jxcore-log: # setup
03-21 16:47:41.075 10976 11040 I jxcore-log: 
,03-21 16:47:41.445 10976 11040 I jxcore-log: # 87. Make an HTTP request to /NotificationBeaconsbefore calling start
03-21 16:47:41.445 10976 11040 I jxcore-log: 
,03-21 16:47:41.685 10976 11040 I jxcore-log: # teardown
03-21 16:47:41.685 10976 11040 I jxcore-log: 
,03-21 16:47:41.885 10976 11040 I jxcore-log: ok 279 should be 404
03-21 16:47:41.885 10976 11040 I jxcore-log: 
,03-21 16:47:41.890 10976 11040 I jxcore-log: # setup
03-21 16:47:41.890 10976 11040 I jxcore-log: 
,03-21 16:47:41.975 10976 11040 I jxcore-log: # 88. #testThaliPeerAction - test getters
03-21 16:47:41.975 10976 11040 I jxcore-log: 
,03-21 16:47:42.085 10976 11040 I jxcore-log: # teardown
03-21 16:47:42.085 10976 11040 I jxcore-log: 
,03-21 16:47:42.185 10976 11040 I jxcore-log: ok 280 getPeerIdentifier
03-21 16:47:42.185 10976 11040 I jxcore-log: 
,03-21 16:47:42.185 10976 11040 I jxcore-log: ok 281 getConnectionType
03-21 16:47:42.185 10976 11040 I jxcore-log: 
,03-21 16:47:42.190 10976 11040 I jxcore-log: ok 282 getActionType
03-21 16:47:42.190 10976 11040 I jxcore-log: 
,03-21 16:47:42.190 10976 11040 I jxcore-log: ok 283 getActionState
03-21 16:47:42.190 10976 11040 I jxcore-log: 
,03-21 16:47:42.195 10976 11040 I jxcore-log: # setup
03-21 16:47:42.195 10976 11040 I jxcore-log: 
,03-21 16:47:42.280 10976 11040 I jxcore-log: # 89. #testThaliPeerAction - start and kill
03-21 16:47:42.280 10976 11040 I jxcore-log: 
,03-21 16:47:42.395 10976 11040 I jxcore-log: # teardown
03-21 16:47:42.395 10976 11040 I jxcore-log: 
,03-21 16:47:42.530 10976 11040 I jxcore-log: ok 284 initial state
03-21 16:47:42.530 10976 11040 I jxcore-log: 
,03-21 16:47:42.535 10976 11040 I jxcore-log: ok 285 after start
03-21 16:47:42.535 10976 11040 I jxcore-log: 
,03-21 16:47:42.540 10976 11040 I jxcore-log: ok 286 after kill
03-21 16:47:42.540 10976 11040 I jxcore-log: 
,03-21 16:47:42.545 10976 11040 I jxcore-log: # setup
03-21 16:47:42.545 10976 11040 I jxcore-log: 
,03-21 16:47:42.625 10976 11040 I jxcore-log: # 90. #testThaliPeerAction - double start
03-21 16:47:42.625 10976 11040 I jxcore-log: 
,03-21 16:47:42.710 10976 11040 I jxcore-log: # teardown
03-21 16:47:42.710 10976 11040 I jxcore-log: 
,03-21 16:47:42.850 10976 11040 I jxcore-log: ok 287 should be equal
03-21 16:47:42.850 10976 11040 I jxcore-log: 
,03-21 16:47:42.855 10976 11040 I jxcore-log: # setup
03-21 16:47:42.855 10976 11040 I jxcore-log: 
,03-21 16:47:42.935 10976 11040 I jxcore-log: # 91. #testThaliPeerAction - start after kill
03-21 16:47:42.935 10976 11040 I jxcore-log: 
,03-21 16:47:43.090 10976 11040 I jxcore-log: # teardown
03-21 16:47:43.090 10976 11040 I jxcore-log: 
,03-21 16:47:43.185 10976 11040 I jxcore-log: ok 288 clean kill
03-21 16:47:43.185 10976 11040 I jxcore-log: 
,03-21 16:47:43.185 10976 11040 I jxcore-log: ok 289 should be equal
03-21 16:47:43.185 10976 11040 I jxcore-log: 
,03-21 16:47:43.190 10976 11040 I jxcore-log: # setup
03-21 16:47:43.190 10976 11040 I jxcore-log: 
,03-21 16:47:43.335 10976 11040 I jxcore-log: # 92. #testThaliPeerAction - make sure ids are unique
03-21 16:47:43.335 10976 11040 I jxcore-log: 
,03-21 16:47:43.460 10976 11040 I jxcore-log: # teardown
03-21 16:47:43.460 10976 11040 I jxcore-log: 
,03-21 16:47:43.570 10976 11040 I jxcore-log: ok 290 should not be equal
03-21 16:47:43.570 10976 11040 I jxcore-log: 
,03-21 16:47:43.580 10976 11040 I jxcore-log: # setup
03-21 16:47:43.580 10976 11040 I jxcore-log: 
,03-21 16:47:43.705 10976 11040 I jxcore-log: # 93. Test PeerConnectionInformation basics
03-21 16:47:43.705 10976 11040 I jxcore-log: 
,03-21 16:47:43.815 10976 11040 I jxcore-log: # teardown
03-21 16:47:43.815 10976 11040 I jxcore-log: 
,03-21 16:47:43.920 10976 11040 I jxcore-log: ok 291 getHostAddress works
03-21 16:47:43.920 10976 11040 I jxcore-log: 
,03-21 16:47:43.925 10976 11040 I jxcore-log: ok 292 getPortNumber works
03-21 16:47:43.925 10976 11040 I jxcore-log: 
,03-21 16:47:43.925 10976 11040 I jxcore-log: ok 293 getSuggestedTCPTimeout works
03-21 16:47:43.925 10976 11040 I jxcore-log: 
,03-21 16:47:43.930 10976 11040 I jxcore-log: # setup
03-21 16:47:43.930 10976 11040 I jxcore-log: 
,03-21 16:47:44.030 10976 11040 I jxcore-log: # 94. Test PeerDictionary basic functionality
03-21 16:47:44.030 10976 11040 I jxcore-log: 
,03-21 16:47:44.165 10976 11040 I jxcore-log: # teardown
03-21 16:47:44.165 10976 11040 I jxcore-log: 
,03-21 16:47:44.350 10976 11040 I jxcore-log: ok 294 Entry counter must be 1
03-21 16:47:44.350 10976 11040 I jxcore-log: 
,03-21 16:47:44.350 10976 11040 I jxcore-log: ok 295 Size must be 1
03-21 16:47:44.350 10976 11040 I jxcore-log: 
,03-21 16:47:44.355 10976 11040 I jxcore-log: ok 296 Entry counter must be 2
03-21 16:47:44.355 10976 11040 I jxcore-log: 
,03-21 16:47:44.355 10976 11040 I jxcore-log: ok 297 Size must be 2
03-21 16:47:44.355 10976 11040 I jxcore-log: 
,03-21 16:47:44.360 10976 11040 I jxcore-log: ok 298 Entry2 should not be found
03-21 16:47:44.360 10976 11040 I jxcore-log: 
,03-21 16:47:44.365 10976 11040 I jxcore-log: ok 299 Size must be 1
03-21 16:47:44.365 10976 11040 I jxcore-log: 
,03-21 16:47:44.365 10976 11040 I jxcore-log: ok 300 Size must be 0
03-21 16:47:44.365 10976 11040 I jxcore-log: 
,03-21 16:47:44.370 10976 11040 I jxcore-log: ok 301 entry not found must be thrown
03-21 16:47:44.370 10976 11040 I jxcore-log: 
,03-21 16:47:44.375 10976 11040 I jxcore-log: # setup
03-21 16:47:44.375 10976 11040 I jxcore-log: 
,03-21 16:47:44.575 10976 11040 I jxcore-log: # 95. Test PeerDictionary with multiple entries.
03-21 16:47:44.575 10976 11040 I jxcore-log: 
,03-21 16:47:44.730 10976 11040 I jxcore-log: # teardown
03-21 16:47:44.730 10976 11040 I jxcore-log: 
,03-21 16:47:45.180  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CUR = 35, LCD = 0
,03-21 16:47:45.500  3390  4030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 16:47:45.500  3390  4030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:47:45.500  3390  4030 D BatteryService: online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
03-21 16:47:45.500  3390  4030 D BatteryService: stay LED for fully charged
03-21 16:47:45.500  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:47:45.505  3390  3390 I MotionRecognitionService: Plugged
,03-21 16:47:45.505  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:47:45.505  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:47:45.505  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:47:45.510  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:47:45.510  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:45.510  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:47:45.520  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:47:45.520  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:47:45.535  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:47:45.535  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:45.535  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:45.535  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:45.665 10976 11040 I jxcore-log: ok 302 Size must be100
03-21 16:47:45.665 10976 11040 I jxcore-log: 
,03-21 16:47:45.665 10976 11040 I jxcore-log: ok 303 Entries between 20 and MAXSIZE + 20 should exist
03-21 16:47:45.665 10976 11040 I jxcore-log: 
,03-21 16:47:46.185 10976 11040 I jxcore-log: ok 304 WAITING state entry should not be removed
03-21 16:47:46.185 10976 11040 I jxcore-log: 
,03-21 16:47:46.185 10976 11040 I jxcore-log: # setup
03-21 16:47:46.185 10976 11040 I jxcore-log: 
,03-21 16:47:46.285 10976 11040 I jxcore-log: # 96. RESOLVED entries are removed before WAITING state entry.
03-21 16:47:46.285 10976 11040 I jxcore-log: 
,03-21 16:47:46.420 10976 11040 I jxcore-log: # teardown
03-21 16:47:46.420 10976 11040 I jxcore-log: 
,03-21 16:47:47.305 10976 11040 I jxcore-log: ok 305 Entries between 6 and MAXSIZE + 4 should exist
03-21 16:47:47.305 10976 11040 I jxcore-log: 
03-21 16:47:47.305 10976 11040 I jxcore-log: ok 306 Size should be MAXSIZE
03-21 16:47:47.305 10976 11040 I jxcore-log: 
03-21 16:47:47.305 10976 11040 I jxcore-log: ok 307 Size should be MAXSIZE+6
03-21 16:47:47.305 10976 11040 I jxcore-log: 
,03-21 16:47:47.305 10976 11040 I jxcore-log: # setup
03-21 16:47:47.305 10976 11040 I jxcore-log: 
,03-21 16:47:47.510 10976 11040 I jxcore-log: # 97. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
03-21 16:47:47.510 10976 11040 I jxcore-log: 
,03-21 16:47:47.640 10976 11040 I jxcore-log: # teardown
03-21 16:47:47.640 10976 11040 I jxcore-log: 
,03-21 16:47:48.415 10976 11040 I jxcore-log: ok 308 WAITING state entry should not be removed
03-21 16:47:48.415 10976 11040 I jxcore-log: 
,03-21 16:47:48.415 10976 11040 I jxcore-log: ok 309 Waiting entries between 6 and MAXSIZE + 4 should exist
03-21 16:47:48.415 10976 11040 I jxcore-log: 
03-21 16:47:48.415 10976 11040 I jxcore-log: ok 310 Size should be MAXSIZE
03-21 16:47:48.415 10976 11040 I jxcore-log: 
03-21 16:47:48.415 10976 11040 I jxcore-log: ok 311 entryCounter should be MAXSIZE+6
03-21 16:47:48.415 10976 11040 I jxcore-log: 
03-21 16:47:48.415 10976 11040 I jxcore-log: # setup
03-21 16:47:48.415 10976 11040 I jxcore-log: 
,03-21 16:47:48.580 10976 11040 I jxcore-log: # 98. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-21 16:47:48.580 10976 11040 I jxcore-log: 
,03-21 16:47:48.705 10976 11040 I jxcore-log: # teardown
03-21 16:47:48.705 10976 11040 I jxcore-log: 
,03-21 16:47:49.520 10976 11040 I jxcore-log: ok 312 Kill should be called once
03-21 16:47:49.520 10976 11040 I jxcore-log: 
03-21 16:47:49.520 10976 11040 I jxcore-log: ok 313 Size should be 100
03-21 16:47:49.520 10976 11040 I jxcore-log: 
,03-21 16:47:49.520 10976 11040 I jxcore-log: # setup
03-21 16:47:49.520 10976 11040 I jxcore-log: 
,03-21 16:47:49.690 10976 11040 I jxcore-log: # 99. #ThaliPeerPoolInterface - bad enqueues
03-21 16:47:49.690 10976 11040 I jxcore-log: 
,03-21 16:47:49.880 10976 11040 I jxcore-log: # teardown
03-21 16:47:49.880 10976 11040 I jxcore-log: 
,03-21 16:47:50.030 10976 11040 I jxcore-log: ok 314 null arg
03-21 16:47:50.030 10976 11040 I jxcore-log: 
,03-21 16:47:50.035 10976 11040 I jxcore-log: ok 315 wrong arg type
03-21 16:47:50.035 10976 11040 I jxcore-log: 
,03-21 16:47:50.040 10976 11040 I jxcore-log: ok 316 wrong state
03-21 16:47:50.040 10976 11040 I jxcore-log: 
,03-21 16:47:50.045 10976 11040 I jxcore-log: # setup
03-21 16:47:50.045 10976 11040 I jxcore-log: 
,03-21 16:47:50.220 10976 11040 I jxcore-log: # 100. #ThaliPeerPoolInterface - do not allow same object type
03-21 16:47:50.220 10976 11040 I jxcore-log: 
,03-21 16:47:50.355 10976 11040 I jxcore-log: # teardown
03-21 16:47:50.355 10976 11040 I jxcore-log: 
,03-21 16:47:50.495 10976 11040 I jxcore-log: ok 317 good enqueue
03-21 16:47:50.495 10976 11040 I jxcore-log: 
,03-21 16:47:50.500 10976 11040 I jxcore-log: ok 318 should be equal
03-21 16:47:50.500 10976 11040 I jxcore-log: 
,03-21 16:47:50.510 10976 11040 I jxcore-log: # setup
03-21 16:47:50.510 10976 11040 I jxcore-log: 
,03-21 16:47:50.675 10976 11040 I jxcore-log: # 101. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-21 16:47:50.675 10976 11040 I jxcore-log: 
,03-21 16:47:50.820 10976 11040 I jxcore-log: # teardown
03-21 16:47:50.820 10976 11040 I jxcore-log: 
,03-21 16:47:50.960 10976 11040 I jxcore-log: ok 319 good enqueue
03-21 16:47:50.960 10976 11040 I jxcore-log: 
,03-21 16:47:50.965 10976 11040 I jxcore-log: ok 320 2nd good enqueue
03-21 16:47:50.965 10976 11040 I jxcore-log: 
,03-21 16:47:50.965 10976 11040 I jxcore-log: ok 321 we are in the pool
03-21 16:47:50.965 10976 11040 I jxcore-log: 
,03-21 16:47:50.970 10976 11040 I jxcore-log: ok 322 We are out of the pool
03-21 16:47:50.970 10976 11040 I jxcore-log: 
,03-21 16:47:50.975 10976 11040 I jxcore-log: ok 323 Action was killed
03-21 16:47:50.975 10976 11040 I jxcore-log: 
,03-21 16:47:50.975 10976 11040 I jxcore-log: ok 324 The original kill was called too
03-21 16:47:50.975 10976 11040 I jxcore-log: 
,03-21 16:47:50.980 10976 11040 I jxcore-log: ok 325 second item is still in queue
03-21 16:47:50.980 10976 11040 I jxcore-log: 
,03-21 16:47:50.980 10976 11040 I jxcore-log: # setup
03-21 16:47:50.980 10976 11040 I jxcore-log: 
,03-21 16:47:51.210 10976 11040 I jxcore-log: # 102. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
03-21 16:47:51.210 10976 11040 I jxcore-log: 
,03-21 16:47:51.430 10976 11040 I jxcore-log: # teardown
03-21 16:47:51.430 10976 11040 I jxcore-log: 
,03-21 16:47:51.620 10976 11040 I jxcore-log: ok 326 good enqueue,
03-21 16:47:51.620 10976 11040 I jxcore-log: 
,03-21 16:47:51.630 10976 11040 I jxcore-log: ok 327 first kill
03-21 16:47:51.630 10976 11040 I jxcore-log: 
,03-21 16:47:51.630 10976 11040 I jxcore-log: ok 328 second NOOP kill
03-21 16:47:51.630 10976 11040 I jxcore-log: 
,03-21 16:47:51.635 10976 11040 I jxcore-log: # setup
03-21 16:47:51.635 10976 11040 I jxcore-log: 
,03-21 16:47:51.815 10976 11040 I jxcore-log: # 103. compareBufferArrays
03-21 16:47:51.815 10976 11040 I jxcore-log: 
,03-21 16:47:51.950 10976 11040 I jxcore-log: # teardown
03-21 16:47:51.950 10976 11040 I jxcore-log: 
,03-21 16:47:52.070 10976 11040 I jxcore-log: ok 329 should throw
03-21 16:47:52.070 10976 11040 I jxcore-log: 
,03-21 16:47:52.075 10976 11040 I jxcore-log: ok 330 should throw
03-21 16:47:52.075 10976 11040 I jxcore-log: 
,03-21 16:47:52.080 10976 11040 I jxcore-log: ok 331 (unnamed assert)
03-21 16:47:52.080 10976 11040 I jxcore-log: 
,03-21 16:47:52.080 10976 11040 I jxcore-log: ok 332 (unnamed assert)
03-21 16:47:52.080 10976 11040 I jxcore-log: 
,03-21 16:47:52.085 10976 11040 I jxcore-log: ok 333 (unnamed assert)
03-21 16:47:52.085 10976 11040 I jxcore-log: 
,03-21 16:47:52.090 10976 11040 I jxcore-log: ok 334 (unnamed assert)
03-21 16:47:52.090 10976 11040 I jxcore-log: 
,03-21 16:47:52.090 10976 11040 I jxcore-log: ok 335 (unnamed assert)
03-21 16:47:52.090 10976 11040 I jxcore-log: 
,03-21 16:47:52.095 10976 11040 I jxcore-log: # setup
03-21 16:47:52.095 10976 11040 I jxcore-log: 
,03-21 16:47:52.215 10976 11040 I jxcore-log: # 104. Call start twice and get error
03-21 16:47:52.215 10976 11040 I jxcore-log: 
,03-21 16:47:52.330 10976 11040 I jxcore-log: # teardown
03-21 16:47:52.330 10976 11040 I jxcore-log: 
,03-21 16:47:52.530 10976 11040 I jxcore-log: ok 336 should throw
03-21 16:47:52.530 10976 11040 I jxcore-log: 
,03-21 16:47:52.535 10976 11040 I jxcore-log: # setup
03-21 16:47:52.535 10976 11040 I jxcore-log: 
,03-21 16:47:52.775 10976 11040 I jxcore-log: # 105. Start and make sure it runs
03-21 16:47:52.775 10976 11040 I jxcore-log: 
,03-21 16:47:53.035 10976 11040 I jxcore-log: # teardown
03-21 16:47:53.035 10976 11040 I jxcore-log: 
,03-21 16:47:53.285 10976 11040 I jxcore-log: # setup
03-21 16:47:53.285 10976 11040 I jxcore-log: 
,03-21 16:47:53.790 10976 11040 I jxcore-log: # 106. Make sure getTimeWhenRun is right after start
03-21 16:47:53.790 10976 11040 I jxcore-log: 
,03-21 16:47:54.250 10976 11040 I jxcore-log: # teardown
03-21 16:47:54.250 10976 11040 I jxcore-log: 
,03-21 16:47:54.740 10976 11040 I jxcore-log: ok 337 (unnamed assert)
03-21 16:47:54.740 10976 11040 I jxcore-log: 
,03-21 16:47:54.745 10976 11040 I jxcore-log: # setup
03-21 16:47:54.745 10976 11040 I jxcore-log: 
,03-21 16:47:55.205  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:14), CUR = 34, LCD = 0
,03-21 16:47:55.330 10976 11040 I jxcore-log: # 107. Make sure getTimeWhenRun is -1 after function is called
03-21 16:47:55.330 10976 11040 I jxcore-log: 
,03-21 16:47:55.555 10976 11040 I jxcore-log: # teardown
03-21 16:47:55.555 10976 11040 I jxcore-log: 
,03-21 16:47:55.630  3390  4007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:47:55.630  3390  4007 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:47:55.630  3390  4007 D BatteryService: online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
03-21 16:47:55.630  3390  4007 D BatteryService: stay LED for fully charged
,03-21 16:47:55.635  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:47:55.640  3390  3390 I MotionRecognitionService: Plugged
03-21 16:47:55.640  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:47:55.640  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:47:55.640  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:47:55.645  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:55.645  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:47:55.645  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 16:47:55.655  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:47:55.655  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:47:55.670  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:47:55.670  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:55.670  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:47:55.670  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:47:55.715 10976 11040 I jxcore-log: ok 338 should be equal
03-21 16:47:55.715 10976 11040 I jxcore-log: 
,03-21 16:47:55.730 10976 11040 I jxcore-log: # setup
03-21 16:47:55.730 10976 11040 I jxcore-log: 
,03-21 16:47:55.915 10976 11040 I jxcore-log: # 108. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-21 16:47:55.915 10976 11040 I jxcore-log: 
,03-21 16:47:56.110 10976 11040 I jxcore-log: # teardown
03-21 16:47:56.110 10976 11040 I jxcore-log: 
,03-21 16:47:56.265 10976 11040 I jxcore-log: ok 339 should be equal
03-21 16:47:56.265 10976 11040 I jxcore-log: 
,03-21 16:47:56.265 10976 11040 I jxcore-log: ok 340 should be equal
03-21 16:47:56.265 10976 11040 I jxcore-log: 
,03-21 16:47:56.270 10976 11040 I jxcore-log: ok 341 should throw
03-21 16:47:56.270 10976 11040 I jxcore-log: 
,03-21 16:47:56.275 10976 11040 I jxcore-log: # setup
03-21 16:47:56.275 10976 11040 I jxcore-log: 
,03-21 16:47:56.470 10976 11040 I jxcore-log: # 109. Test TransientState
03-21 16:47:56.470 10976 11040 I jxcore-log: 
,03-21 16:47:56.960 10976 11040 I jxcore-log: # teardown
03-21 16:47:56.960 10976 11040 I jxcore-log: 
,03-21 16:47:57.280 10976 11040 I jxcore-log: ok 342 should throw
03-21 16:47:57.280 10976 11040 I jxcore-log: 
,03-21 16:47:57.285 10976 11040 I jxcore-log: ok 343 should throw
03-21 16:47:57.285 10976 11040 I jxcore-log: 
,03-21 16:47:57.285 10976 11040 I jxcore-log: ok 344 should be equal
03-21 16:47:57.285 10976 11040 I jxcore-log: 
,03-21 16:47:57.285 10976 11040 I jxcore-log: ok 345 should be equal
03-21 16:47:57.285 10976 11040 I jxcore-log: 
,03-21 16:47:57.290 10976 11040 I jxcore-log: ok 346 should be equal
03-21 16:47:57.290 10976 11040 I jxcore-log: 
,03-21 16:47:57.290 10976 11040 I jxcore-log: ok 347 should be equal
03-21 16:47:57.290 10976 11040 I jxcore-log: 
,03-21 16:47:57.295 10976 11040 I jxcore-log: ok 348 (unnamed assert)
03-21 16:47:57.295 10976 11040 I jxcore-log: 
,03-21 16:47:57.295 10976 11040 I jxcore-log: ok 349 (unnamed assert)
03-21 16:47:57.295 10976 11040 I jxcore-log: 
,03-21 16:47:57.300 10976 11040 I jxcore-log: # setup
03-21 16:47:57.300 10976 11040 I jxcore-log: 
,03-21 16:47:57.565 10976 11040 I jxcore-log: # 110. No peers and empty database
03-21 16:47:57.565 10976 11040 I jxcore-log: 
,03-21 16:47:57.700 10976 11040 I jxcore-log: # teardown
03-21 16:47:57.700 10976 11040 I jxcore-log: 
,03-21 16:47:57.980 10976 11040 I jxcore-log: ok 350 verify failed
03-21 16:47:57.980 10976 11040 I jxcore-log: 
,03-21 16:47:57.980 10976 11040 I jxcore-log: ok 351 constructor called once
03-21 16:47:57.980 10976 11040 I jxcore-log: 
,03-21 16:47:57.980 10976 11040 I jxcore-log: ok 352 constructor called with right args
03-21 16:47:57.980 10976 11040 I jxcore-log: 
03-21 16:47:57.980 10976 11040 I jxcore-log: ok 353 match start arg
03-21 16:47:57.980 10976 11040 I jxcore-log: 
,03-21 16:47:57.980 10976 11040 I jxcore-log: ok 354 start called once
03-21 16:47:57.980 10976 11040 I jxcore-log: 
03-21 16:47:57.985 10976 11040 I jxcore-log: ok 355 stop called once
03-21 16:47:57.985 10976 11040 I jxcore-log: 
03-21 16:47:57.985 10976 11040 I jxcore-log: ok 356 stop after start
03-21 16:47:57.985 10976 11040 I jxcore-log: 
,03-21 16:47:57.985 10976 11040 I jxcore-log: # setup
03-21 16:47:57.985 10976 11040 I jxcore-log: 
,03-21 16:47:58.220 10976 11040 I jxcore-log: # 111. One peer and empty DB
03-21 16:47:58.220 10976 11040 I jxcore-log: 
,03-21 16:47:58.510 10976 11040 I jxcore-log: # teardown
03-21 16:47:58.510 10976 11040 I jxcore-log: 
,03-21 16:47:58.675  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:47:58.870 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:47:58.870 10976 11040 I jxcore-log: 
,03-21 16:47:58.875 10976 11040 I jxcore-log: ok 357 verify failed
03-21 16:47:58.875 10976 11040 I jxcore-log: 
,03-21 16:47:58.875 10976 11040 I jxcore-log: ok 358 constructor called once
03-21 16:47:58.875 10976 11040 I jxcore-log: 
03-21 16:47:58.875 10976 11040 I jxcore-log: ok 359 constructor called with right args
03-21 16:47:58.875 10976 11040 I jxcore-log: 
,03-21 16:47:58.880 10976 11040 I jxcore-log: ok 360 match start arg
03-21 16:47:58.880 10976 11040 I jxcore-log: 
03-21 16:47:58.880 10976 11040 I jxcore-log: ok 361 start called once
03-21 16:47:58.880 10976 11040 I jxcore-log: 
03-21 16:47:58.880 10976 11040 I jxcore-log: ok 362 stop called once
03-21 16:47:58.880 10976 11040 I jxcore-log: 
03-21 16:47:58.880 10976 11040 I jxcore-log: ok 363 stop after start
03-21 16:47:58.880 10976 11040 I jxcore-log: 
,03-21 16:47:58.885 10976 11040 I jxcore-log: # setup
03-21 16:47:58.885 10976 11040 I jxcore-log: 
,03-21 16:47:59.020 10976 11040 I jxcore-log: # 112. One peer with _Local set behind current seq
03-21 16:47:59.020 10976 11040 I jxcore-log: 
,03-21 16:47:59.190  3390  3608 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-21 16:47:59.195  3390  3607 D TimaService: TimaServiceHandler.handleMessage what =1,
,03-21 16:47:59.195  3390  3608 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-21 16:47:59.220  3390  3608 I TLC_TIMA_PKM_initialize: initializing...
,03-21 16:47:59.220  3390  3608 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
03-21 16:47:59.220  3390  3608 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
,03-21 16:47:59.220  3390  3608 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
03-21 16:47:59.220  3390  3608 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
03-21 16:47:59.220  3390  3608 I TZ: mc_tlc_communication: root = 0, root_len = 1
,03-21 16:47:59.220  3390  3608 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
03-21 16:47:59.220  3390  3608 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
03-21 16:47:59.220  3390  3608 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
03-21 16:47:59.220  3390  3608 I TZ: mc_tlc_communication: device_id = 0x0
,03-21 16:47:59.225  3390  3608 I TZ: mc_tlc_communication: tlc_open() was called
03-21 16:47:59.225  3390  3608 I TZ: mc_tlc_communication: Opening MobiCore device
,03-21 16:47:59.225  3390  3608 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,03-21 16:47:59.230  3390  3608 I TZ: mc_tlc_communication: Opening the session
,03-21 16:47:59.245  3390  3608 I TZ: mc_tlc_communication: tlc_open() succeeded
,03-21 16:47:59.255  3390  3608 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-21 16:47:59.640 10976 11040 I jxcore-log: # teardown
03-21 16:47:59.640 10976 11040 I jxcore-log: 
,03-21 16:47:59.995  3390  3619 V AlarmManager: waitForAlarm result :8
,03-21 16:48:00.075 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:00.075 10976 11040 I jxcore-log: 
,03-21 16:48:00.080 10976 11040 I jxcore-log: ok 364 verify failed
03-21 16:48:00.080 10976 11040 I jxcore-log: 
,03-21 16:48:00.080 10976 11040 I jxcore-log: ok 365 constructor called once
03-21 16:48:00.080 10976 11040 I jxcore-log: 
,03-21 16:48:00.080 10976 11040 I jxcore-log: ok 366 constructor called with right args
03-21 16:48:00.080 10976 11040 I jxcore-log: 
03-21 16:48:00.080 10976 11040 I jxcore-log: ok 367 match start arg
03-21 16:48:00.080 10976 11040 I jxcore-log: 
03-21 16:48:00.080 10976 11040 I jxcore-log: ok 368 start called once
03-21 16:48:00.080 10976 11040 I jxcore-log: 
,03-21 16:48:00.080 10976 11040 I jxcore-log: ok 369 stop called once
03-21 16:48:00.080 10976 11040 I jxcore-log: 
03-21 16:48:00.080 10976 11040 I jxcore-log: ok 370 stop after start
03-21 16:48:00.080 10976 11040 I jxcore-log: 
,03-21 16:48:00.085 10976 11040 I jxcore-log: # setup
03-21 16:48:00.085 10976 11040 I jxcore-log: 
,03-21 16:48:00.645 10976 11040 I jxcore-log: # 113. One peer with _Local set equal to current seq
03-21 16:48:00.645 10976 11040 I jxcore-log: 
,03-21 16:48:00.860 10976 11040 I jxcore-log: # teardown
03-21 16:48:00.860 10976 11040 I jxcore-log: 
,03-21 16:48:01.325 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:01.325 10976 11040 I jxcore-log: 
,03-21 16:48:01.325 10976 11040 I jxcore-log: ok 371 verify failed
03-21 16:48:01.325 10976 11040 I jxcore-log: 
,03-21 16:48:01.325 10976 11040 I jxcore-log: ok 372 constructor called once
03-21 16:48:01.325 10976 11040 I jxcore-log: 
,03-21 16:48:01.330 10976 11040 I jxcore-log: ok 373 constructor called with right args
03-21 16:48:01.330 10976 11040 I jxcore-log: 
,03-21 16:48:01.330 10976 11040 I jxcore-log: ok 374 match start arg
03-21 16:48:01.330 10976 11040 I jxcore-log: 
03-21 16:48:01.330 10976 11040 I jxcore-log: ok 375 start called once
03-21 16:48:01.330 10976 11040 I jxcore-log: 
,03-21 16:48:01.330 10976 11040 I jxcore-log: ok 376 stop called once
03-21 16:48:01.330 10976 11040 I jxcore-log: 
03-21 16:48:01.330 10976 11040 I jxcore-log: ok 377 stop after start
03-21 16:48:01.330 10976 11040 I jxcore-log: 
,03-21 16:48:01.340 10976 11040 I jxcore-log: # setup
03-21 16:48:01.340 10976 11040 I jxcore-log: 
,03-21 16:48:01.545  3390  3864 E Watchdog: !@Sync 10 [03-21 16:48:01.548]
,03-21 16:48:01.720 10976 11040 I jxcore-log: # 114. One peer with _Local set ahead of current seq (and no this should not happen),
03-21 16:48:01.720 10976 11040 I jxcore-log: 
,03-21 16:48:01.890 10976 11040 I jxcore-log: # teardown
03-21 16:48:01.890 10976 11040 I jxcore-log: 
,03-21 16:48:02.395 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:02.395 10976 11040 I jxcore-log: 
,03-21 16:48:02.400 10976 11040 I jxcore-log: ok 378 verify failed
03-21 16:48:02.400 10976 11040 I jxcore-log: 
,03-21 16:48:02.400 10976 11040 I jxcore-log: ok 379 constructor called once
03-21 16:48:02.400 10976 11040 I jxcore-log: 
,03-21 16:48:02.400 10976 11040 I jxcore-log: ok 380 constructor called with right args
03-21 16:48:02.400 10976 11040 I jxcore-log: 
03-21 16:48:02.400 10976 11040 I jxcore-log: ok 381 match start arg
03-21 16:48:02.400 10976 11040 I jxcore-log: 
,03-21 16:48:02.400 10976 11040 I jxcore-log: ok 382 start called once
03-21 16:48:02.400 10976 11040 I jxcore-log: 
,03-21 16:48:02.405 10976 11040 I jxcore-log: ok 383 stop called once
03-21 16:48:02.405 10976 11040 I jxcore-log: 
03-21 16:48:02.405 10976 11040 I jxcore-log: ok 384 stop after start
03-21 16:48:02.405 10976 11040 I jxcore-log: 
,03-21 16:48:02.410 10976 11040 I jxcore-log: # setup
03-21 16:48:02.410 10976 11040 I jxcore-log: 
,03-21 16:48:02.570 10976 11040 I jxcore-log: # 115. Three peers, one not in DB, one behind and one ahead
03-21 16:48:02.570 10976 11040 I jxcore-log: 
,03-21 16:48:02.685 10976 11040 I jxcore-log: # teardown
03-21 16:48:02.685 10976 11040 I jxcore-log: 
,03-21 16:48:03.135 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:03.135 10976 11040 I jxcore-log: 
,03-21 16:48:03.135 10976 11040 I jxcore-log: ok 385 verify failed
03-21 16:48:03.135 10976 11040 I jxcore-log: 
,03-21 16:48:03.135 10976 11040 I jxcore-log: ok 386 constructor called once
03-21 16:48:03.135 10976 11040 I jxcore-log: 
03-21 16:48:03.140 10976 11040 I jxcore-log: ok 387 constructor called with right args
03-21 16:48:03.140 10976 11040 I jxcore-log: 
03-21 16:48:03.140 10976 11040 I jxcore-log: ok 388 match start arg
03-21 16:48:03.140 10976 11040 I jxcore-log: 
,03-21 16:48:03.140 10976 11040 I jxcore-log: ok 389 start called once
03-21 16:48:03.140 10976 11040 I jxcore-log: 
03-21 16:48:03.140 10976 11040 I jxcore-log: ok 390 stop called once
03-21 16:48:03.140 10976 11040 I jxcore-log: 
03-21 16:48:03.140 10976 11040 I jxcore-log: ok 391 stop after start
03-21 16:48:03.140 10976 11040 I jxcore-log: 
,03-21 16:48:03.145 10976 11040 I jxcore-log: # setup
03-21 16:48:03.145 10976 11040 I jxcore-log: 
,03-21 16:48:03.300 10976 11040 I jxcore-log: # 116. More than maximum peers, make sure we only send maximum allowed
03-21 16:48:03.300 10976 11040 I jxcore-log: 
,03-21 16:48:03.595 10976 11040 I jxcore-log: # teardown
03-21 16:48:03.595 10976 11040 I jxcore-log: 
,03-21 16:48:04.005  3390  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-21 16:48:04.005  3390  3608 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-21 16:48:04.020  3390  3608 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 16:48:04.020  3390  3608 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 16:48:04.350 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:04.350 10976 11040 I jxcore-log: 
,03-21 16:48:04.355 10976 11040 I jxcore-log: ok 392 verify failed
03-21 16:48:04.355 10976 11040 I jxcore-log: 
03-21 16:48:04.355 10976 11040 I jxcore-log: ok 393 constructor called once
03-21 16:48:04.355 10976 11040 I jxcore-log: 
03-21 16:48:04.355 10976 11040 I jxcore-log: ok 394 constructor called with right args
03-21 16:48:04.355 10976 11040 I jxcore-log: 
03-21 16:48:04.355 10976 11040 I jxcore-log: ok 395 match start arg
03-21 16:48:04.355 10976 11040 I jxcore-log: 
03-21 16:48:04.355 10976 11040 I jxcore-log: ok 396 start called once
03-21 16:48:04.355 10976 11040 I jxcore-log: 
03-21 16:48:04.355 10976 11040 I jxcore-log: ok 397 stop called once
03-21 16:48:04.355 10976 11040 I jxcore-log: 
03-21 16:48:04.355 10976 11040 I jxcore-log: ok 398 stop after start
03-21 16:48:04.355 10976 11040 I jxcore-log: 
,03-21 16:48:04.365 10976 11040 I jxcore-log: # setup
03-21 16:48:04.365 10976 11040 I jxcore-log: 
,03-21 16:48:04.560 10976 11040 I jxcore-log: # 117. two peers with empty DB, update the doc
03-21 16:48:04.560 10976 11040 I jxcore-log: 
,03-21 16:48:04.755 10976 11040 I jxcore-log: # teardown
03-21 16:48:04.755 10976 11040 I jxcore-log: 
,03-21 16:48:04.780  2896  4798 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 16:48:05.095 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:05.095 10976 11040 I jxcore-log: 
,03-21 16:48:05.130 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:05.130 10976 11040 I jxcore-log: 
,03-21 16:48:05.130 10976 11040 I jxcore-log: ok 399 verify failed
03-21 16:48:05.130 10976 11040 I jxcore-log: 
03-21 16:48:05.130 10976 11040 I jxcore-log: ok 400 constructor called once
03-21 16:48:05.130 10976 11040 I jxcore-log: 
03-21 16:48:05.130 10976 11040 I jxcore-log: ok 401 constructor called with right args
03-21 16:48:05.130 10976 11040 I jxcore-log: 
03-21 16:48:05.130 10976 11040 I jxcore-log: ok 402 last start before stop
03-21 16:48:05.130 10976 11040 I jxcore-log: 
03-21 16:48:05.130 10976 11040 I jxcore-log: ok 403 empty first start
03-21 16:48:05.130 10976 11040 I jxcore-log: 
,03-21 16:48:05.130 10976 11040 I jxcore-log: ok 404 full second start
03-21 16:48:05.130 10976 11040 I jxcore-log: 
03-21 16:48:05.130 10976 11040 I jxcore-log: ok 405 only 2 timers
03-21 16:48:05.130 10976 11040 I jxcore-log: 
,03-21 16:48:05.135 10976 11040 I jxcore-log: # setup
03-21 16:48:05.135 10976 11040 I jxcore-log: 
,03-21 16:48:05.235  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 24, LCD = 0
,03-21 16:48:05.275 10976 11040 I jxcore-log: # 118. add doc and make sure tokens refresh when they expire
03-21 16:48:05.275 10976 11040 I jxcore-log: 
,03-21 16:48:05.585 10976 11040 I jxcore-log: # teardown
03-21 16:48:05.585 10976 11040 I jxcore-log: 
,03-21 16:48:05.760  3390  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:48:05.760  3390  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:48:05.760  3390  3981 D BatteryService: online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-21 16:48:05.760  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:48:05.765  3390  3981 D BatteryService: stay LED for fully charged
,03-21 16:48:05.770  3390  3390 I MotionRecognitionService: Plugged
03-21 16:48:05.770  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:48:05.770  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:48:05.770  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:48:05.780  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 16:48:05.780  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:48:05.780  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-21 16:48:05.790  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:48:05.790  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:48:05.800  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:48:05.800  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:48:05.805  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:48:05.805  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:48:06.085 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:06.085 10976 11040 I jxcore-log: 
,03-21 16:48:06.220 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:06.220 10976 11040 I jxcore-log: 
,03-21 16:48:06.350 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:06.350 10976 11040 I jxcore-log: 
,03-21 16:48:06.355 10976 11040 I jxcore-log: ok 406 verify failed
03-21 16:48:06.355 10976 11040 I jxcore-log: 
,03-21 16:48:06.355 10976 11040 I jxcore-log: ok 407 constructor called once
03-21 16:48:06.355 10976 11040 I jxcore-log: 
,03-21 16:48:06.360 10976 11040 I jxcore-log: ok 408 constructor called with right args
03-21 16:48:06.360 10976 11040 I jxcore-log: 
,03-21 16:48:06.360 10976 11040 I jxcore-log: ok 409 start before stop
03-21 16:48:06.360 10976 11040 I jxcore-log: 
,03-21 16:48:06.365 10976 11040 I jxcore-log: ok 410 We got at least 3 calls to start
03-21 16:48:06.365 10976 11040 I jxcore-log: 
,03-21 16:48:06.365 10976 11040 I jxcore-log: ok 411 at least 3
03-21 16:48:06.365 10976 11040 I jxcore-log: 
,03-21 16:48:06.370 10976 11040 I jxcore-log: ok 412 default 1
03-21 16:48:06.370 10976 11040 I jxcore-log: 
,03-21 16:48:06.370 10976 11040 I jxcore-log: ok 413 1 run
03-21 16:48:06.370 10976 11040 I jxcore-log: 
,03-21 16:48:06.370 10976 11040 I jxcore-log: ok 414 default 2
03-21 16:48:06.370 10976 11040 I jxcore-log: 
,03-21 16:48:06.375 10976 11040 I jxcore-log: ok 415 2 run
03-21 16:48:06.375 10976 11040 I jxcore-log: 
,03-21 16:48:06.375 10976 11040 I jxcore-log: ok 416 default 3
03-21 16:48:06.375 10976 11040 I jxcore-log: 
,03-21 16:48:06.385 10976 11040 I jxcore-log: # setup
03-21 16:48:06.385 10976 11040 I jxcore-log: 
,03-21 16:48:06.490 10976 11040 I jxcore-log: # 119. start and stop and start and stop
03-21 16:48:06.490 10976 11040 I jxcore-log: 
,03-21 16:48:06.635 10976 11040 I jxcore-log: # teardown
03-21 16:48:06.635 10976 11040 I jxcore-log: 
,03-21 16:48:06.935 10976 11040 I jxcore-log: ok 417 start out null
03-21 16:48:06.935 10976 11040 I jxcore-log: 
,03-21 16:48:06.965 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:06.965 10976 11040 I jxcore-log: 
,03-21 16:48:06.965 10976 11040 I jxcore-log: ok 418 back to null
03-21 16:48:06.965 10976 11040 I jxcore-log: 
,03-21 16:48:06.990 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:06.990 10976 11040 I jxcore-log: 
,03-21 16:48:06.990 10976 11040 I jxcore-log: ok 419 still null
03-21 16:48:06.990 10976 11040 I jxcore-log: 
,03-21 16:48:06.995 10976 11040 I jxcore-log: ok 420 verify failed
03-21 16:48:06.995 10976 11040 I jxcore-log: 
03-21 16:48:06.995 10976 11040 I jxcore-log: ok 421 constructor called once
03-21 16:48:06.995 10976 11040 I jxcore-log: 
03-21 16:48:06.995 10976 11040 I jxcore-log: ok 422 constructor called with right args
03-21 16:48:06.995 10976 11040 I jxcore-log: 
03-21 16:48:06.995 10976 11040 I jxcore-log: ok 423 first start before first stop
03-21 16:48:06.995 10976 11040 I jxcore-log: 
,03-21 16:48:06.995 10976 11040 I jxcore-log: ok 424 first stop before second start
03-21 16:48:06.995 10976 11040 I jxcore-log: 
03-21 16:48:06.995 10976 11040 I jxcore-log: ok 425 second start before second stop
03-21 16:48:06.995 10976 11040 I jxcore-log: 
,03-21 16:48:07.000 10976 11040 I jxcore-log: # setup
03-21 16:48:07.000 10976 11040 I jxcore-log: 
,03-21 16:48:07.355 10976 11040 I jxcore-log: # 120. two identical starts in a row
03-21 16:48:07.355 10976 11040 I jxcore-log: 
,03-21 16:48:07.555 10976 11040 I jxcore-log: # teardown,
03-21 16:48:07.555 10976 11040 I jxcore-log: 
,03-21 16:48:07.900 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:07.900 10976 11040 I jxcore-log: 
,03-21 16:48:07.905 10976 11040 I jxcore-log: ok 426 verify failed
03-21 16:48:07.905 10976 11040 I jxcore-log: 
,03-21 16:48:07.905 10976 11040 I jxcore-log: ok 427 constructor called once
03-21 16:48:07.905 10976 11040 I jxcore-log: 
03-21 16:48:07.905 10976 11040 I jxcore-log: ok 428 constructor called with right args
03-21 16:48:07.905 10976 11040 I jxcore-log: 
03-21 16:48:07.905 10976 11040 I jxcore-log: ok 429 (unnamed assert)
03-21 16:48:07.905 10976 11040 I jxcore-log: 
,03-21 16:48:07.910 10976 11040 I jxcore-log: # setup
03-21 16:48:07.910 10976 11040 I jxcore-log: 
,03-21 16:48:08.080 10976 11040 I jxcore-log: # 121. two different starts in a row
03-21 16:48:08.080 10976 11040 I jxcore-log: 
,03-21 16:48:08.245 10976 11040 I jxcore-log: # teardown
03-21 16:48:08.245 10976 11040 I jxcore-log: 
,03-21 16:48:08.665 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:08.665 10976 11040 I jxcore-log: 
,03-21 16:48:08.670 10976 11040 I jxcore-log: ok 430 verify failed
03-21 16:48:08.670 10976 11040 I jxcore-log: 
,03-21 16:48:08.670 10976 11040 I jxcore-log: ok 431 constructor called once
03-21 16:48:08.670 10976 11040 I jxcore-log: 
03-21 16:48:08.670 10976 11040 I jxcore-log: ok 432 constructor called with right args
03-21 16:48:08.670 10976 11040 I jxcore-log: 
03-21 16:48:08.670 10976 11040 I jxcore-log: ok 433 (unnamed assert)
03-21 16:48:08.670 10976 11040 I jxcore-log: 
03-21 16:48:08.670 10976 11040 I jxcore-log: ok 434 (unnamed assert)
03-21 16:48:08.670 10976 11040 I jxcore-log: 
,03-21 16:48:08.675 10976 11040 I jxcore-log: # setup
03-21 16:48:08.675 10976 11040 I jxcore-log: 
,03-21 16:48:09.270 10976 11040 I jxcore-log: # 122. two stops and a start and two stops
03-21 16:48:09.270 10976 11040 I jxcore-log: 
,03-21 16:48:09.960 10976 11040 I jxcore-log: # teardown
03-21 16:48:09.960 10976 11040 I jxcore-log: 
,03-21 16:48:10.305 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:10.305 10976 11040 I jxcore-log: 
,03-21 16:48:10.310 10976 11040 I jxcore-log: ok 435 verify failed
03-21 16:48:10.310 10976 11040 I jxcore-log: 
,03-21 16:48:10.310 10976 11040 I jxcore-log: ok 436 constructor called once
03-21 16:48:10.310 10976 11040 I jxcore-log: 
,03-21 16:48:10.310 10976 11040 I jxcore-log: ok 437 constructor called with right args
03-21 16:48:10.310 10976 11040 I jxcore-log: 
03-21 16:48:10.315 10976 11040 I jxcore-log: ok 438 start before stop
03-21 16:48:10.315 10976 11040 I jxcore-log: 
,03-21 16:48:10.320 10976 11040 I jxcore-log: # setup
03-21 16:48:10.320 10976 11040 I jxcore-log: 
,03-21 16:48:10.685 10976 11040 I jxcore-log: # 123. we properly enqueue requests so no then needed
03-21 16:48:10.685 10976 11040 I jxcore-log: 
,03-21 16:48:10.850 10976 11040 I jxcore-log: # teardown
03-21 16:48:10.850 10976 11040 I jxcore-log: 
,03-21 16:48:11.175 10976 11040 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 16:48:11.175 10976 11040 I jxcore-log: 
,03-21 16:48:11.180 10976 11040 I jxcore-log: ok 439 verify failed
03-21 16:48:11.180 10976 11040 I jxcore-log: 
,03-21 16:48:11.180 10976 11040 I jxcore-log: ok 440 constructor called once
03-21 16:48:11.180 10976 11040 I jxcore-log: 
03-21 16:48:11.180 10976 11040 I jxcore-log: ok 441 constructor called with right args
03-21 16:48:11.180 10976 11040 I jxcore-log: 
,03-21 16:48:11.180 10976 11040 I jxcore-log: ok 442 start before stop
03-21 16:48:11.180 10976 11040 I jxcore-log: 
,03-21 16:48:11.185 10976 11040 I jxcore-log: # setup
03-21 16:48:11.185 10976 11040 I jxcore-log: 
,03-21 16:48:11.280 10976 11040 I jxcore-log: # 124. test calculateSeqPointKeyId
03-21 16:48:11.280 10976 11040 I jxcore-log: 
,03-21 16:48:11.375 10976 11040 I jxcore-log: # teardown
03-21 16:48:11.375 10976 11040 I jxcore-log: 
,03-21 16:48:11.580 10976 11040 I jxcore-log: ok 443 should be equal
03-21 16:48:11.580 10976 11040 I jxcore-log: 
,03-21 16:48:11.585 10976 11040 I jxcore-log: ok 444 should be equal
03-21 16:48:11.585 10976 11040 I jxcore-log: 
,03-21 16:48:11.590 10976 11040 I jxcore-log: # setup
03-21 16:48:11.590 10976 11040 I jxcore-log: 
,03-21 16:48:11.805 10976 11040 I jxcore-log: # 125. can create servers manager
03-21 16:48:11.805 10976 11040 I jxcore-log: 
,03-21 16:48:11.950 10976 11040 I jxcore-log: # teardown
03-21 16:48:11.950 10976 11040 I jxcore-log: 
,03-21 16:48:12.050 10976 11040 I jxcore-log: ok 445 serversManager must not be null
03-21 16:48:12.050 10976 11040 I jxcore-log: 
,03-21 16:48:12.055 10976 11040 I jxcore-log: ok 446 serversManager must be an object
03-21 16:48:12.055 10976 11040 I jxcore-log: 
,03-21 16:48:12.060 10976 11040 I jxcore-log: # setup
03-21 16:48:12.060 10976 11040 I jxcore-log: 
,03-21 16:48:12.190 10976 11040 I jxcore-log: # 126. calling stop without start causes error
03-21 16:48:12.190 10976 11040 I jxcore-log: 
,03-21 16:48:12.365 10976 11040 I jxcore-log: # teardown
03-21 16:48:12.365 10976 11040 I jxcore-log: 
,03-21 16:48:12.510 10976 11040 I jxcore-log: ok 447 We need to call start first
03-21 16:48:12.510 10976 11040 I jxcore-log: 
,03-21 16:48:12.515 10976 11040 I jxcore-log: # setup
03-21 16:48:12.515 10976 11040 I jxcore-log: 
,03-21 16:48:12.605 10976 11040 I jxcore-log: # 127. can start/stop servers manager
03-21 16:48:12.605 10976 11040 I jxcore-log: 
,03-21 16:48:12.760 10976 11040 I jxcore-log: # teardown
03-21 16:48:12.760 10976 11040 I jxcore-log: 
,03-21 16:48:12.895 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:48:12.895 10976 11040 I jxcore-log: 
,03-21 16:48:12.905 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 48480
03-21 16:48:12.905 10976 11040 I jxcore-log: 
,03-21 16:48:12.910 10976 11040 I jxcore-log: ok 448 port must be in range
03-21 16:48:12.910 10976 11040 I jxcore-log: 
,03-21 16:48:12.915 10976 11040 I jxcore-log: # setup
03-21 16:48:12.915 10976 11040 I jxcore-log: 
,03-21 16:48:13.090 10976 11040 I jxcore-log: # 128. starting twice resolves with listening port
03-21 16:48:13.090 10976 11040 I jxcore-log: 
,03-21 16:48:13.180 10976 11040 I jxcore-log: # teardown
03-21 16:48:13.180 10976 11040 I jxcore-log: 
,03-21 16:48:13.320 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:48:13.320 10976 11040 I jxcore-log: 
,03-21 16:48:13.325 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 49620
03-21 16:48:13.325 10976 11040 I jxcore-log: 
,03-21 16:48:13.330 10976 11040 I jxcore-log: ok 449 second start should return same port
03-21 16:48:13.330 10976 11040 I jxcore-log: 
,03-21 16:48:13.335 10976 11040 I jxcore-log: # setup
03-21 16:48:13.335 10976 11040 I jxcore-log: 
,03-21 16:48:13.435 10976 11040 I jxcore-log: # 129. terminateIncomingConnection will terminate a connection
03-21 16:48:13.435 10976 11040 I jxcore-log: 
,03-21 16:48:13.575 10976 11040 I jxcore-log: # teardown
03-21 16:48:13.575 10976 11040 I jxcore-log: 
,03-21 16:48:13.700 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:48:13.700 10976 11040 I jxcore-log: 
,03-21 16:48:13.705 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 52953
03-21 16:48:13.705 10976 11040 I jxcore-log: 
,03-21 16:48:13.720 10976 11040 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 16:48:13.720 10976 11040 I jxcore-log: 
,03-21 16:48:13.720 10976 11040 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 16:48:13.720 10976 11040 I jxcore-log: 
,03-21 16:48:13.725 10976 11040 I jxcore-log: DEBUG createNativeListener: new mux
03-21 16:48:13.725 10976 11040 I jxcore-log: 
,03-21 16:48:13.730 10976 11040 I jxcore-log: ok 450 we should be connected
03-21 16:48:13.730 10976 11040 I jxcore-log: 
,03-21 16:48:13.735 10976 11040 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 16:48:13.735 10976 11040 I jxcore-log: 
,03-21 16:48:13.735 10976 11040 I jxcore-log: ok 451 now we are disconnected
03-21 16:48:13.735 10976 11040 I jxcore-log: 
,03-21 16:48:13.750 10976 11040 I jxcore-log: # setup
03-21 16:48:13.750 10976 11040 I jxcore-log: 
,03-21 16:48:13.845 10976 11040 I jxcore-log: # 130. terminate an Outgoing connection will terminate the server
03-21 16:48:13.845 10976 11040 I jxcore-log: 
,03-21 16:48:13.990 10976 11040 I jxcore-log: # teardown
03-21 16:48:13.990 10976 11040 I jxcore-log: 
,03-21 16:48:14.180 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:48:14.180 10976 11040 I jxcore-log: 
,03-21 16:48:14.190 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 55377
03-21 16:48:14.190 10976 11040 I jxcore-log: 
,03-21 16:48:14.195 10976 11040 I jxcore-log: # setup
03-21 16:48:14.195 10976 11040 I jxcore-log: 
,03-21 16:48:14.370 10976 11040 I jxcore-log: # 131. terminate an Outgoing connection with wrong arguments is not harmful
03-21 16:48:14.370 10976 11040 I jxcore-log: 
,03-21 16:48:14.530 10976 11040 I jxcore-log: # teardown
03-21 16:48:14.530 10976 11040 I jxcore-log: 
,03-21 16:48:14.650 10976 11040 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 16:48:14.650 10976 11040 I jxcore-log: 
,03-21 16:48:14.655 10976 11040 I jxcore-log: DEBUG createNativeListener: listening 39030
03-21 16:48:14.655 10976 11040 I jxcore-log: 
,03-21 16:48:14.660 10976 11040 I jxcore-log: # setup
03-21 16:48:14.660 10976 11040 I jxcore-log: 
,03-21 16:48:14.810 10976 11040 I jxcore-log: # 132. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-21 16:48:14.810 10976 11040 I jxcore-log: 
,03-21 16:48:14.955 10976 11040 I jxcore-log: ok 452 should be in started state
03-21 16:48:14.955 10976 11040 I jxcore-log: 
,03-21 16:48:14.960 10976 11040 I jxcore-log: # teardown
03-21 16:48:14.960 10976 11040 I jxcore-log: 
,03-21 16:48:15.225 10976 11040 I jxcore-log: ok 453 peer identifier should match
03-21 16:48:15.225 10976 11040 I jxcore-log: 
,03-21 16:48:15.230 10976 11040 I jxcore-log: ok 454 host address should match
03-21 16:48:15.230 10976 11040 I jxcore-log: 
,03-21 16:48:15.235 10976 11040 I jxcore-log: ok 455 port should match
03-21 16:48:15.235 10976 11040 I jxcore-log: 
,03-21 16:48:15.240 10976 11040 I jxcore-log: ok 456 host address should be null
03-21 16:48:15.240 10976 11040 I jxcore-log: 
,03-21 16:48:15.240 10976 11040 I jxcore-log: ok 457 port should should be null
03-21 16:48:15.240 10976 11040 I jxcore-log: 
,03-21 16:48:15.245  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 30, LCD = 0
,03-21 16:48:15.250 10976 11040 I jxcore-log: # setup
03-21 16:48:15.250 10976 11040 I jxcore-log: 
,03-21 16:48:15.410 10976 11040 I jxcore-log: ok 458 should not be in started state
03-21 16:48:15.410 10976 11040 I jxcore-log: 
,03-21 16:48:15.420 10976 11040 I jxcore-log: # 133. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-21 16:48:15.420 10976 11040 I jxcore-log: 
,03-21 16:48:15.745 10976 11040 I jxcore-log: ok 459 should be in started state
03-21 16:48:15.745 10976 11040 I jxcore-log: 
,03-21 16:48:15.750 10976 11040 I jxcore-log: # teardown
03-21 16:48:15.750 10976 11040 I jxcore-log: 
,03-21 16:48:15.870  3390  3832 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 16:48:15.870  3390  3832 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:48:15.870  3390  3832 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
03-21 16:48:15.870  3390  3832 D BatteryService: stay LED for fully charged
03-21 16:48:15.870  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:48:15.875  3390  3390 I MotionRecognitionService: Plugged
03-21 16:48:15.875  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:48:15.875  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:48:15.875  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:48:15.880  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:48:15.880  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:48:15.880  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:48:15.880 10976 11040 I jxcore-log: ok 460 USN should have changed from the first one
03-21 16:48:15.880 10976 11040 I jxcore-log: 
,03-21 16:48:15.890  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 16:48:15.890  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:48:15.895 10976 11040 I jxcore-log: ok 461 when receiving the second byebye, the first USN should be already set
03-21 16:48:15.895 10976 11040 I jxcore-log: 
,03-21 16:48:15.900  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:48:15.900  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:48:15.900  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:48:15.905  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:48:15.905 10976 11040 I jxcore-log: # setup
03-21 16:48:15.905 10976 11040 I jxcore-log: 
,03-21 16:48:16.035 10976 11040 I jxcore-log: ok 462 should not be in started state
03-21 16:48:16.035 10976 11040 I jxcore-log: 
,03-21 16:48:16.045 10976 11040 I jxcore-log: # 134. messages with invalid location or USN should be ignored
03-21 16:48:16.045 10976 11040 I jxcore-log: 
,03-21 16:48:16.165 10976 11040 I jxcore-log: ok 463 should be in started state
03-21 16:48:16.165 10976 11040 I jxcore-log: 
,03-21 16:48:16.170 10976 11040 I jxcore-log: # teardown
03-21 16:48:16.170 10976 11040 I jxcore-log: 
,03-21 16:48:16.265 10976 11040 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
03-21 16:48:16.265 10976 11040 I jxcore-log: 
,03-21 16:48:16.265 10976 11040 I jxcore-log: ok 464 should not have emitted with invalid port
03-21 16:48:16.265 10976 11040 I jxcore-log: 
,03-21 16:48:16.265 10976 11040 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
03-21 16:48:16.265 10976 11040 I jxcore-log: 
,03-21 16:48:16.270 10976 11040 I jxcore-log: ok 465 should not have emitted with invalid USN
03-21 16:48:16.270 10976 11040 I jxcore-log: 
,03-21 16:48:16.270 10976 11040 I jxcore-log: # setup
03-21 16:48:16.270 10976 11040 I jxcore-log: 
,03-21 16:48:16.395 10976 11040 I jxcore-log: ok 466 should not be in started state
03-21 16:48:16.395 10976 11040 I jxcore-log: 
,03-21 16:48:16.400 10976 11040 I jxcore-log: # 135. verify that Thali-specific messages are filtered correctly
03-21 16:48:16.400 10976 11040 I jxcore-log: 
,03-21 16:48:16.560 10976 11040 I jxcore-log: ok 467 should be in started state
03-21 16:48:16.560 10976 11040 I jxcore-log: 
,03-21 16:48:16.565 10976 11040 I jxcore-log: # teardown
03-21 16:48:16.565 10976 11040 I jxcore-log: 
,03-21 16:48:16.700 10976 11040 I jxcore-log: ok 468 irrelevant messages should be ignored
03-21 16:48:16.700 10976 11040 I jxcore-log: 
,03-21 16:48:16.705 10976 11040 I jxcore-log: ok 469 relevant messages should not be ignored
03-21 16:48:16.705 10976 11040 I jxcore-log: 
,03-21 16:48:16.705 10976 11040 I jxcore-log: ok 470 messages from this device should be ignored
03-21 16:48:16.705 10976 11040 I jxcore-log: 
,03-21 16:48:16.710 10976 11040 I jxcore-log: # setup
03-21 16:48:16.710 10976 11040 I jxcore-log: 
,03-21 16:48:16.880 10976 11040 I jxcore-log: ok 471 should not be in started state
03-21 16:48:16.880 10976 11040 I jxcore-log: 
,03-21 16:48:16.885 10976 11040 I jxcore-log: # 136. #startListeningForAdvertisements should fail if start not called
03-21 16:48:16.885 10976 11040 I jxcore-log: 
,03-21 16:48:17.060 10976 11040 I jxcore-log: ok 472 should be in started state
03-21 16:48:17.060 10976 11040 I jxcore-log: 
,03-21 16:48:17.070 10976 11040 I jxcore-log: # teardown
03-21 16:48:17.070 10976 11040 I jxcore-log: 
,03-21 16:48:17.200 10976 11040 I jxcore-log: ok 473 specific error should be returned
03-21 16:48:17.200 10976 11040 I jxcore-log: 
,03-21 16:48:17.205 10976 11040 I jxcore-log: # setup
03-21 16:48:17.205 10976 11040 I jxcore-log: 
,03-21 16:48:17.315 10976 11040 I jxcore-log: ok 474 should not be in started state
03-21 16:48:17.315 10976 11040 I jxcore-log: 
,03-21 16:48:17.325 10976 11040 I jxcore-log: # 137. #startUpdateAdvertisingAndListening should fail if start not called
03-21 16:48:17.325 10976 11040 I jxcore-log: 
,03-21 16:48:17.485 10976 11040 I jxcore-log: ok 475 should be in started state
03-21 16:48:17.485 10976 11040 I jxcore-log: 
,03-21 16:48:17.495 10976 11040 I jxcore-log: # teardown
03-21 16:48:17.495 10976 11040 I jxcore-log: 
,03-21 16:48:17.635 10976 11040 I jxcore-log: ok 476 specific error should be returned
03-21 16:48:17.635 10976 11040 I jxcore-log: 
,03-21 16:48:17.640 10976 11040 I jxcore-log: # setup
03-21 16:48:17.640 10976 11040 I jxcore-log: 
,03-21 16:48:17.775 10976 11040 I jxcore-log: ok 477 should not be in started state
03-21 16:48:17.775 10976 11040 I jxcore-log: 
,03-21 16:48:17.775 10976 11040 I jxcore-log: # 138. #start should fail if called twice in a row
03-21 16:48:17.775 10976 11040 I jxcore-log: 
,03-21 16:48:17.955 10976 11040 I jxcore-log: ok 478 should be in started state
03-21 16:48:17.955 10976 11040 I jxcore-log: 
,03-21 16:48:17.960 10976 11040 I jxcore-log: # teardown
03-21 16:48:17.960 10976 11040 I jxcore-log: 
,03-21 16:48:18.065 10976 11040 I jxcore-log: ok 479 specific error should be received
03-21 16:48:18.065 10976 11040 I jxcore-log: 
,03-21 16:48:18.065 10976 11040 I jxcore-log: # setup
03-21 16:48:18.065 10976 11040 I jxcore-log: 
,03-21 16:48:18.250 10976 11040 I jxcore-log: ok 480 should not be in started state
03-21 16:48:18.250 10976 11040 I jxcore-log: 
,03-21 16:48:18.255 10976 11040 I jxcore-log: # 139. should not be started after stop is called
03-21 16:48:18.255 10976 11040 I jxcore-log: 
,03-21 16:48:18.435 10976 11040 I jxcore-log: ok 481 should be in started state
03-21 16:48:18.435 10976 11040 I jxcore-log: 
,03-21 16:48:18.440 10976 11040 I jxcore-log: # teardown
03-21 16:48:18.440 10976 11040 I jxcore-log: 
,03-21 16:48:18.615 10976 11040 I jxcore-log: ok 482 should not be started
03-21 16:48:18.615 10976 11040 I jxcore-log: 
,03-21 16:48:18.615 10976 11040 I jxcore-log: ok 483 should not be listening
03-21 16:48:18.615 10976 11040 I jxcore-log: 
,03-21 16:48:18.620 10976 11040 I jxcore-log: ok 484 should not target listening
03-21 16:48:18.620 10976 11040 I jxcore-log: 
,03-21 16:48:18.620 10976 11040 I jxcore-log: ok 485 should not be advertising
03-21 16:48:18.620 10976 11040 I jxcore-log: 
,03-21 16:48:18.625 10976 11040 I jxcore-log: ok 486 should not target advertising
03-21 16:48:18.625 10976 11040 I jxcore-log: 
,03-21 16:48:18.630 10976 11040 I jxcore-log: # setup
03-21 16:48:18.630 10976 11040 I jxcore-log: 
,03-21 16:48:18.675  3390  6075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 16:48:18.795 10976 11040 I jxcore-log: ok 487 should not be in started state
03-21 16:48:18.795 10976 11040 I jxcore-log: 
,03-21 16:48:18.800 10976 11040 I jxcore-log: # 140. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-21 16:48:18.800 10976 11040 I jxcore-log: 
,03-21 16:48:18.975 10976 11040 I jxcore-log: ok 488 should be in started state
03-21 16:48:18.975 10976 11040 I jxcore-log: 
,03-21 16:48:18.980 10976 11040 I jxcore-log: # teardown
03-21 16:48:18.980 10976 11040 I jxcore-log: 
,03-21 16:48:19.125 10976 11040 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-21 16:48:19.125 10976 11040 I jxcore-log: 
,03-21 16:48:19.130 10976 11040 I jxcore-log: ok 489 specific error should be received
03-21 16:48:19.130 10976 11040 I jxcore-log: 
,03-21 16:48:19.135 10976 11040 I jxcore-log: # setup
03-21 16:48:19.135 10976 11040 I jxcore-log: 
,03-21 16:48:19.330 10976 11040 I jxcore-log: ok 490 should not be in started state
03-21 16:48:19.330 10976 11040 I jxcore-log: 
,03-21 16:48:19.335 10976 11040 I jxcore-log: # 141. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-21 16:48:19.335 10976 11040 I jxcore-log: 
,03-21 16:48:19.575 10976 11040 I jxcore-log: ok 491 should be in started state
03-21 16:48:19.575 10976 11040 I jxcore-log: 
,03-21 16:48:19.580 10976 11040 I jxcore-log: # teardown
03-21 16:48:19.580 10976 11040 I jxcore-log: 
,03-21 16:48:19.790 10976 11040 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-21 16:48:19.790 10976 11040 I jxcore-log: 
,03-21 16:48:19.795 10976 11040 I jxcore-log: ok 492 specific error expected
03-21 16:48:19.795 10976 11040 I jxcore-log: 
,03-21 16:48:19.800 10976 11040 I jxcore-log: # setup
03-21 16:48:19.800 10976 11040 I jxcore-log: 
,03-21 16:48:19.960 10976 11040 I jxcore-log: ok 493 should not be in started state
03-21 16:48:19.960 10976 11040 I jxcore-log: 
,03-21 16:48:19.965 10976 11040 I jxcore-log: # 142. #startUpdateAdvertisingAndListening should start hosting given router object
03-21 16:48:19.965 10976 11040 I jxcore-log: 
,03-21 16:48:20.135 10976 11040 I jxcore-log: ok 494 should be in started state
03-21 16:48:20.135 10976 11040 I jxcore-log: 
,03-21 16:48:20.145 10976 11040 I jxcore-log: # teardown
03-21 16:48:20.145 10976 11040 I jxcore-log: 
,03-21 16:48:20.295  3390  4415 I ActivityManager: Killing 10034:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-21 16:48:20.310  2876  3383 D EnterpriseController: netId is 0
03-21 16:48:20.310  2876  3383 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 16:48:20.345 10976 11040 I jxcore-log: ok 495 server should respond with code 200
03-21 16:48:20.345 10976 11040 I jxcore-log: 
,03-21 16:48:20.355 10976 11040 I jxcore-log: # setup
03-21 16:48:20.355 10976 11040 I jxcore-log: 
,03-21 16:48:20.550 10976 11040 I jxcore-log: ok 496 should not be in started state
03-21 16:48:20.550 10976 11040 I jxcore-log: 
,03-21 16:48:20.560 10976 11040 I jxcore-log: # 143. #stop can be called multiple times in a row
03-21 16:48:20.560 10976 11040 I jxcore-log: 
,03-21 16:48:20.700 10976 11040 I jxcore-log: ok 497 should be in started state
03-21 16:48:20.700 10976 11040 I jxcore-log: 
,03-21 16:48:20.705 10976 11040 I jxcore-log: # teardown
03-21 16:48:20.705 10976 11040 I jxcore-log: 
,03-21 16:48:20.865 10976 11040 I jxcore-log: ok 498 should be in stopped state
03-21 16:48:20.865 10976 11040 I jxcore-log: 
,03-21 16:48:20.870 10976 11040 I jxcore-log: ok 499 should still be in stopped state
03-21 16:48:20.870 10976 11040 I jxcore-log: 
,03-21 16:48:20.875 10976 11040 I jxcore-log: # setup
03-21 16:48:20.875 10976 11040 I jxcore-log: 
,03-21 16:48:20.965 10976 11040 I jxcore-log: ok 500 should not be in started state
03-21 16:48:20.965 10976 11040 I jxcore-log: 
,03-21 16:48:20.970 10976 11040 I jxcore-log: # 144. #startListeningForAdvertisements can be called multiple times in a row
03-21 16:48:20.970 10976 11040 I jxcore-log: 
,03-21 16:48:21.095 10976 11040 I jxcore-log: ok 501 should be in started state
03-21 16:48:21.095 10976 11040 I jxcore-log: 
,03-21 16:48:21.100 10976 11040 I jxcore-log: # teardown
03-21 16:48:21.100 10976 11040 I jxcore-log: 
,03-21 16:48:21.305 10976 11040 I jxcore-log: ok 502 should be in listening state
03-21 16:48:21.305 10976 11040 I jxcore-log: 
,03-21 16:48:21.310 10976 11040 I jxcore-log: ok 503 should still be in listening state
03-21 16:48:21.310 10976 11040 I jxcore-log: 
,03-21 16:48:21.320 10976 11040 I jxcore-log: # setup
03-21 16:48:21.320 10976 11040 I jxcore-log: 
,03-21 16:48:21.570 10976 11040 I jxcore-log: ok 504 should not be in started state
03-21 16:48:21.570 10976 11040 I jxcore-log: 
,03-21 16:48:21.575 10976 11040 I jxcore-log: # 145. #stopListeningForAdvertisements can be called multiple times in a row
03-21 16:48:21.575 10976 11040 I jxcore-log: 
,03-21 16:48:21.755 10976 11040 I jxcore-log: ok 505 should be in started state
03-21 16:48:21.755 10976 11040 I jxcore-log: 
,03-21 16:48:21.760 10976 11040 I jxcore-log: # teardown
03-21 16:48:21.760 10976 11040 I jxcore-log: 
,03-21 16:48:21.960 10976 11040 I jxcore-log: ok 506 should not be in listening state
03-21 16:48:21.960 10976 11040 I jxcore-log: 
,03-21 16:48:21.965 10976 11040 I jxcore-log: ok 507 should still not be in listening state
03-21 16:48:21.965 10976 11040 I jxcore-log: 
,03-21 16:48:21.970 10976 11040 I jxcore-log: # setup
03-21 16:48:21.970 10976 11040 I jxcore-log: 
,03-21 16:48:22.155 10976 11040 I jxcore-log: ok 508 should not be in started state
03-21 16:48:22.155 10976 11040 I jxcore-log: 
,03-21 16:48:22.160 10976 11040 I jxcore-log: # 146. #stopAdvertisingAndListening can be called multiple times in a row
03-21 16:48:22.160 10976 11040 I jxcore-log: 
,03-21 16:48:22.350 10976 11040 I jxcore-log: ok 509 should be in started state
03-21 16:48:22.350 10976 11040 I jxcore-log: 
,03-21 16:48:22.360 10976 11040 I jxcore-log: # teardown
03-21 16:48:22.360 10976 11040 I jxcore-log: 
,03-21 16:48:22.530 10976 11040 I jxcore-log: ok 510 should not be in advertising state
03-21 16:48:22.530 10976 11040 I jxcore-log: 
,03-21 16:48:22.535 10976 11040 I jxcore-log: ok 511 should still not be in advertising state
03-21 16:48:22.535 10976 11040 I jxcore-log: 
,03-21 16:48:22.540 10976 11040 I jxcore-log: # setup
03-21 16:48:22.540 10976 11040 I jxcore-log: 
,03-21 16:48:22.710 10976 11040 I jxcore-log: ok 512 should not be in started state
03-21 16:48:22.710 10976 11040 I jxcore-log: 
,03-21 16:48:22.715 10976 11040 I jxcore-log: # 147. functions are run from a queue in the right order
03-21 16:48:22.715 10976 11040 I jxcore-log: 
,03-21 16:48:22.970 10976 11040 I jxcore-log: ok 513 should be in started state
03-21 16:48:22.970 10976 11040 I jxcore-log: 
,03-21 16:48:22.975 10976 11040 I jxcore-log: # teardown
03-21 16:48:22.975 10976 11040 I jxcore-log: 
,03-21 16:48:23.200 10976 11040 I jxcore-log: ok 514 call order must match
03-21 16:48:23.200 10976 11040 I jxcore-log: 
,03-21 16:48:23.205 10976 11040 I jxcore-log: # setup
03-21 16:48:23.205 10976 11040 I jxcore-log: 
,03-21 16:48:23.355 10976 11040 I jxcore-log: ok 515 should not be in started state
03-21 16:48:23.355 10976 11040 I jxcore-log: 
,03-21 16:48:23.360 10976 11040 I jxcore-log: # 148. #ThaliPeerPoolDefault - single action
03-21 16:48:23.360 10976 11040 I jxcore-log: 
,03-21 16:48:23.555 10976 11040 I jxcore-log: # teardown
03-21 16:48:23.555 10976 11040 I jxcore-log: 
,03-21 16:48:23.795 10976 11040 I jxcore-log: ok 516 is an agent
03-21 16:48:23.795 10976 11040 I jxcore-log: 
,03-21 16:48:23.795 10976 11040 I jxcore-log: ok 517 enqueue is fine
03-21 16:48:23.795 10976 11040 I jxcore-log: 
,03-21 16:48:23.800 10976 11040 I jxcore-log: ok 518 Everything should be off the queue
03-21 16:48:23.800 10976 11040 I jxcore-log: 
,03-21 16:48:23.805 10976 11040 I jxcore-log: # setup
03-21 16:48:23.805 10976 11040 I jxcore-log: 
,03-21 16:48:23.960 10976 11040 I jxcore-log: # 149. #ThaliPeerPoolDefault - multiple actions
03-21 16:48:23.960 10976 11040 I jxcore-log: 
,03-21 16:48:24.310 10976 11040 I jxcore-log: # teardown
03-21 16:48:24.310 10976 11040 I jxcore-log: 
,03-21 16:48:24.505 10976 11040 I jxcore-log: ok 519 is an agent
03-21 16:48:24.505 10976 11040 I jxcore-log: 
,03-21 16:48:24.510 10976 11040 I jxcore-log: ok 520 first enqueue is fine
03-21 16:48:24.510 10976 11040 I jxcore-log: 
,03-21 16:48:24.515 10976 11040 I jxcore-log: ok 521 is an agent
03-21 16:48:24.515 10976 11040 I jxcore-log: 
,03-21 16:48:24.515 10976 11040 I jxcore-log: ok 522 second enqueue is fine
03-21 16:48:24.515 10976 11040 I jxcore-log: 
,03-21 16:48:24.520 10976 11040 I jxcore-log: ok 523 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-21 16:48:24.520 10976 11040 I jxcore-log: 
,03-21 16:48:24.525 10976 11040 I jxcore-log: ok 524 Queue is empty
03-21 16:48:24.525 10976 11040 I jxcore-log: 
,03-21 16:48:24.530 10976 11040 I jxcore-log: Tests Complete
03-21 16:48:24.530 10976 11040 I jxcore-log: 
,03-21 16:48:25.055 10976 10976 I chromium: [INFO:CONSOLE(86)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (86)
,03-21 16:48:25.060 10976 11040 I jxcore-log: Total: 0	Passed: 0	Failed: 0
03-21 16:48:25.060 10976 11040 I jxcore-log: 
,03-21 16:48:25.070 10976 11040 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 16:48:25.070 10976 11040 I jxcore-log: 
,03-21 16:48:25.080 10976 10976 I chromium: [INFO:CONSOLE(86)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (86)
,03-21 16:48:25.250  3390  6044 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 31, LCD = 0
,03-21 16:48:25.435 12880 12880 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-21 16:48:25.440 12880 12880 D AndroidRuntime: CheckJNI is OFF
,03-21 16:48:25.440 12880 12880 D AndroidRuntime: readGMSProperty: start
03-21 16:48:25.440 12880 12880 D AndroidRuntime: readGMSProperty: already setted!!
03-21 16:48:25.440 12880 12880 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 16:48:25.440 12880 12880 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 16:48:25.440 12880 12880 D AndroidRuntime: readGMSProperty: end
03-21 16:48:25.440 12880 12880 D AndroidRuntime: addProductProperty: start
,03-21 16:48:25.670 12880 12880 E AffinityControl: AffinityControl: registerfunction enter
,03-21 16:48:25.695 12880 12880 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 16:48:25.705  3390  3744 D PackageManager: START PACKAGE DELETE: observer{14535001}
03-21 16:48:25.705  3390  3744 D PackageManager: pkg{<packageName>}
03-21 16:48:25.705  3390  3744 D PackageManager: user{0}
03-21 16:48:25.705  3390  3744 D PackageManager: caller{2000}
03-21 16:48:25.705  3390  3744 D PackageManager: flags{2}
03-21 16:48:25.705  3390  3744 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 16:48:25.705  3390  3744 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 16:48:25.705  3390  3744 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 16:48:25.710  3390  3592 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-21 16:48:25.710  3390  3744 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 16:48:25.710  3390  3744 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 16:48:25.710  3390  3592 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 16:48:25.710  3390  3592 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-21 16:48:25.710  3390  3592 D ApplicationPolicy: getApplicationUninstallationEnabled
03-21 16:48:25.710  3390  3592 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-21 16:48:25.710  3390  3592 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-21 16:48:25.710  3390  3576 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-21 16:48:25.715  3390  3576 I ActivityManager: Killing 10976:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-21 16:48:25.740  3390  3576 I ActivityManager:   Force finishing activity 3 ActivityRecord{34f30454 u0 com.test.thalitest/.MainActivity t41}
,03-21 16:48:25.745  3390  3576 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 16:48:25.750  3390  3576 D InputDispatcher: Focus left window: 10976
,03-21 16:48:25.755  2862  4527 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
03-21 16:48:25.755  2862  3019 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,03-21 16:48:25.760  3390  3576 D InputDispatcher: Focused application released
03-21 16:48:25.760  3390  3581 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3390 uid:1000
03-21 16:48:25.760  3390  3581 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 16:48:25.760  3390  3581 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3390 uid:1000
03-21 16:48:25.760  3390  3581 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-21 16:48:25.950  3390  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-21 16:48:25.955  3390  3592 W PackageSettings: Skipping PackageSetting{38bc49d1 com.example.hello/10691} due to missing metadata
,03-21 16:48:25.985  3390  3592 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-21 16:48:25.985  3390  3981 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 16:48:25.985  3390  3981 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 16:48:25.985  3390  3981 D BatteryService: online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
03-21 16:48:25.985  3390  3981 D BatteryService: stay LED for fully charged
03-21 16:48:25.990  3390  3390 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 16:48:25.990  3390  3390 I MotionRecognitionService: Plugged
03-21 16:48:25.990  3390  3390 D MotionRecognitionService:   cableConnection= 1
03-21 16:48:25.990  3390  3390 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 16:48:25.990  3390  3390 D MotionRecognitionService: skip setTransmitPower. 
,03-21 16:48:25.995  3726  3726 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:48:25.995  3726  3726 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 16:48:25.995  3726  3726 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 16:48:26.000  5849  5849 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 16:48:26.000  5849  5950 D HeadsetStateMachine: Disconnected process message: 10
,03-21 16:48:26.005  3390  3592 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
,03-21 16:48:26.015  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 16:48:26.015  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:48:26.015  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 16:48:26.015  3726  3726 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 16:48:26.055  3920  3920 I art     : Explicit concurrent mark sweep GC freed 1335(73KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 506us total 17.850ms
,03-21 16:48:26.060  3390  3592 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 16:48:26.060  9045  9045 I art     : Explicit concurrent mark sweep GC freed 25156(1357KB) AllocSpace objects, 2(32KB) LOS objects, 69% free, 1812KB/5MB, paused 830us total 29.298ms
,03-21 16:48:26.065  3390  3390 I art     : WaitForGcToComplete blocked for 7.192ms for cause Explicit
,03-21 16:48:26.080  4014  4014 I art     : Explicit concurrent mark sweep GC freed 2335(126KB) AllocSpace objects, 12(1777KB) LOS objects, 12% free, 56MB/64MB, paused 2.356ms total 36.666ms
,03-21 16:48:26.080  4695  4695 I art     : Explicit concurrent mark sweep GC freed 2976(185KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 8MB/11MB, paused 703us total 70.100ms
,03-21 16:48:26.085  4695  4712 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-21 16:48:26.095  4113  4113 I art     : Explicit concurrent mark sweep GC freed 5135(285KB) AllocSpace objects, 1(16KB) LOS objects, 26% free, 5MB/7MB, paused 1.582ms total 56.611ms
,03-21 16:48:26.100  3726  3726 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
03-21 16:48:26.105  4507  4507 E SamsungIME: mOCRHelper is null
03-21 16:48:26.105  3390  3632 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 16:48:26.115  4454  4869 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 16:48:26.120 10541 10541 D LWLocationManager: getDeviceLocationId :  id = -100
03-21 16:48:26.120 10541 10541 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-21 16:48:26.120  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.120  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.120  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.120  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.140 12912 12912 E Zygote  : MountEmulatedStorage()
,03-21 16:48:26.140 12912 12912 E Zygote  : v2
03-21 16:48:26.140 12912 12912 I libpersona: KNOX_SDCARD checking this for 10063
,03-21 16:48:26.140 12912 12912 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.145 12912 12912 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 16:48:26.145 12912 12912 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:26.145  3390  3576 I ActivityManager: Start proc 12912:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
03-21 16:48:26.145 12912 12912 E Zygote  : accessInfo : 0
,03-21 16:48:26.145 12912 12912 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.150  5599  5617 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
,03-21 16:48:26.150  5599  5617 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-21 16:48:26.165  3390  3692 D TaskPersister: removeObsoleteFile: deleting file=41_task.xml
03-21 16:48:26.165  3390  3692 D TaskPersister: removeObsoleteFile: deleting file=41_task_thumbnail.png
,03-21 16:48:26.170  3390  3573 D EnterpriseDeviceManagerService: Package has changed for user 0
03-21 16:48:26.170  3390  3573 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-21 16:48:26.175  3390  3573 W TextServicesManagerService: no available spell checker services found
,03-21 16:48:26.180 12912 12912 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:26.180  3390  3653 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 16:48:26.180  3390  3653 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-21 16:48:26.180  3390  3653 V NetworkStats: performPollLocked(flags=0x3)
,03-21 16:48:26.185 12912 12912 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:26.185  3390  3653 V NetworkStats: performPollLocked() took 7ms
03-21 16:48:26.185  3390  3653 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 16:48:26.190  3982  3982 D RegisteredServicesCache: empty dynamic service
,03-21 16:48:26.200  3390  3423 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2b0e5c64 12912:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-21 16:48:26.210  3982  3982 D RegisteredComponentCache: Collect Tech packages for Knox
,03-21 16:48:26.230 12912 12912 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
,03-21 16:48:26.230 12912 12912 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
,03-21 16:48:26.230 12912 12912 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,03-21 16:48:26.235  3390  3390 I art     : Explicit concurrent mark sweep GC freed 26559(2033KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.605ms total 170.390ms
03-21 16:48:26.235  3390  3592 I art     : WaitForGcToComplete blocked for 71.550ms for cause Explicit
,03-21 16:48:26.245  3390  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 16:48:26.245  3390  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 16:48:26.250  3390  4007 I ActivityManager: Killing 9968:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,03-21 16:48:26.250  3390  4007 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{308bf7b6 7065:com.samsung.klmsagent/u0a21}
03-21 16:48:26.255  7065  7065 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 21 16:48:26 GMT+01:00 2016
,03-21 16:48:26.265  3390  3744 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,03-21 16:48:26.265  3390  3981 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-21 16:48:26.270  7065  7065 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-21 16:48:26.275  3390  4415 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-21 16:48:26.275  3390  4415 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,03-21 16:48:26.275  7065  7065 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
,03-21 16:48:26.280  7065  7065 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-21 16:48:26.280  3390  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{39221d6b 6822:com.samsung.aasaservice/1000}
,03-21 16:48:26.280  7065  7065 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-21 16:48:26.280  6822  6822 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,03-21 16:48:26.280  6822  6822 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-21 16:48:26.280  6822  6822 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-21 16:48:26.280  7065 12929 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-21 16:48:26.285  6822  6822 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-21 16:48:26.285  6822  6822 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-21 16:48:26.285  6822  6822 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-21 16:48:26.285  6822  6822 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-21 16:48:26.285  6822  6822 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 16:48:26.285  6822  6822 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.285  6822  6822 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 16:48:26.285  6822  6822 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 16:48:26.285  6822  6822 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 16:48:26.285  6822  6822 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 16:48:26.285  6822  6822 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 16:48:26.285  7065 12929 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
,03-21 16:48:26.285  7065 12929 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-21 16:48:26.285  7065 12929 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-21 16:48:26.285  7065 12929 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-21 16:48:26.285  7065 12929 I KLMS-2.5.262: : MDMBridge.getInstance()
,03-21 16:48:26.285  7065 12929 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-21 16:48:26.285  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.285  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.285  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.285  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.290  7065 12929 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-21 16:48:26.290  7065 12929 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-21 16:48:26.295  7065 12929 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-21 16:48:26.295  7065 12929 E KLMS-2.5.262: : arr si null
,03-21 16:48:26.300  3390  3573 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 16:48:26.305 12930 12930 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.305 12930 12930 E Zygote  : v2
03-21 16:48:26.305 12930 12930 I libpersona: KNOX_SDCARD checking this for 10042
03-21 16:48:26.305 12930 12930 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.305 12930 12930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.305 12930 12930 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 16:48:26.305  7065 12929 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-21 16:48:26.305  7065 12929 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-21 16:48:26.305 12930 12930 E Zygote  : accessInfo : 0
03-21 16:48:26.305  7065 12929 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-21 16:48:26.305  7065 12929 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
,03-21 16:48:26.310 12930 12930 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.320  3390  3576 I ActivityManager: Start proc 12930:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,03-21 16:48:26.320  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.320  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.320  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.320  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.340 12945 12945 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.340 12945 12945 E Zygote  : v2
03-21 16:48:26.340 12945 12945 I libpersona: KNOX_SDCARD checking this for 1000
03-21 16:48:26.340 12945 12945 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.340 12945 12945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.340 12930 12930 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 16:48:26.345 12945 12945 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 16:48:26.345 12930 12930 D ActivityThread: Added TimaKeyStore provider
03-21 16:48:26.345  3390  3576 I ActivityManager: Start proc 12945:com.samsung.android.sm/1000 for broadcast-4 com.samsung.android.sm/.ui.security.MonitorReceiver
03-21 16:48:26.345 12945 12945 E Zygote  : accessInfo : 0
,03-21 16:48:26.345 12945 12945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.345  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.345  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.345  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.345  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.365 12956 12956 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.365  3390  3573 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 16:48:26.365  3390  3573 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 16:48:26.365  3390  3573 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 16:48:26.365 12956 12956 E Zygote  : v2
03-21 16:48:26.365 12956 12956 I libpersona: KNOX_SDCARD checking this for 1000
03-21 16:48:26.365 12956 12956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.365 12956 12956 I libpersona: KNOX_SDCARD not a persona
03-21 16:48:26.365  3390  3573 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
03-21 16:48:26.370 12956 12956 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:26.370 12956 12956 E Zygote  : accessInfo : 0
,03-21 16:48:26.370 12956 12956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.370  3390  3576 I ActivityManager: Start proc 12956:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
,03-21 16:48:26.390 12945 12945 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:26.390 12945 12945 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:26.390  3390  3592 I art     : Explicit concurrent mark sweep GC freed 12850(797KB) AllocSpace objects, 1(2MB) LOS objects, 33% free, 25MB/37MB, paused 2.817ms total 154.847ms
,03-21 16:48:26.405 12956 12956 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:26.405 12956 12956 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:26.405  3390  4007 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3b372e73 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{26980130 12945:com.samsung.android.sm/1000}
,03-21 16:48:26.410 10541 12921 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 16:48:26.415  7065 12929 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-21 16:48:26.415  7065 12929 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-21 16:48:26.415  7065 12929 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-21 16:48:26.415  7065 12929 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-21 16:48:26.415  3390  4030 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a3551a9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{394b732e 12956:com.sec.android.app.popupuireceiver/1000}
,03-21 16:48:26.420  7065 12929 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-21 16:48:26.420 12945 12945 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 16:48:26.420  7065 12929 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-21 16:48:26.420  7065 12929 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-21 16:48:26.420  7065 12929 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-21 16:48:26.425  3390  4415 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{34a4f7b1 3390:system/1000}
,03-21 16:48:26.430  3390  4242 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{25cc3ecf u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3634005c 12930:com.samsung.android.sdk.samsunglink/u0a42}
,03-21 16:48:26.430  7065  7065 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,03-21 16:48:26.435 12956 12956 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-21 16:48:26.445  3390  4007 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-21 16:48:26.445  3390  3651 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-21 16:48:26.450 12956 12956 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
03-21 16:48:26.450 12930 12930 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 16:48:26.450  3390  4729 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
03-21 16:48:26.450 12930 12930 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-21 16:48:26.450 12956 12956 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-21 16:48:26.450 12956 12956 D PopupuiReceiver: Action package removed
,03-21 16:48:26.455  3390  3744 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a3551a9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{22af03b7 10475:com.samsung.android.snote/u0a160}
,03-21 16:48:26.460  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.465  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.465  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.465  3390  4730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.475 12975 12975 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.475 12975 12975 E Zygote  : v2
03-21 16:48:26.475 12975 12975 I libpersona: KNOX_SDCARD checking this for 10183
03-21 16:48:26.475 12975 12975 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.475 12975 12975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.475 12975 12975 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:26.475 10541 12921 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 16:48:26.480 10541 12921 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 16:48:26.480 10541 12921 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 16:48:26.480 10541 12921 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-21 16:48:26.480 12975 12975 E Zygote  : accessInfo : 0
03-21 16:48:26.480 12975 12975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.480  3390  4730 I ActivityManager: Start proc 12975:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,03-21 16:48:26.485  3390  4730 I ActivityManager: Killing 10228:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
,03-21 16:48:26.495 12975 12975 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:26.500 12975 12975 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:26.505  3390  3422 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a3551a9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{f685f65 12975:com.samsung.android.provider.shootingmodeprovider/u0a183}
,03-21 16:48:26.510 12945 12945 I art     : Explicit concurrent mark sweep GC freed 6038(291KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1733KB/3MB, paused 443us total 12.810ms
,03-21 16:48:26.525  3390  4111 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3b372e73 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{26980130 12945:com.samsung.android.sm/1000}
,03-21 16:48:26.530  3390  4111 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3b372e73 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{26980130 12945:com.samsung.android.sm/1000}
,03-21 16:48:26.540 12975 12975 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-21 16:48:26.540  3390  3980 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.540  3390  3980 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.540  3390  3980 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.540  3390  3980 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.560 12995 12995 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.560 12995 12995 E Zygote  : v2
03-21 16:48:26.560 12995 12995 I libpersona: KNOX_SDCARD checking this for 1000
03-21 16:48:26.560 12995 12995 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.560 12995 12995 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.560 12995 12995 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:26.565 12995 12995 E Zygote  : accessInfo : 0
,03-21 16:48:26.565 12995 12995 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.565  3390  3980 I ActivityManager: Start proc 12995:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,03-21 16:48:26.570  3390  3980 I ActivityManager: Killing 10307:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-21 16:48:26.575 12945 12990 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-21 16:48:26.575 12930 12930 I SL_DEBUG: isLoggable:: isProductShip = 1
,03-21 16:48:26.575 12930 12930 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,03-21 16:48:26.585  3390  3592 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-21 16:48:26.585  3390  3592 D PackageManager: delete codoeFile: 
03-21 16:48:26.585  3390  4727 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,03-21 16:48:26.590 10637 10647 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
03-21 16:48:26.590 10637 10647 D BadgeProvider: sendNotify, [notify] : null
03-21 16:48:26.590 10637 10647 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-21 16:48:26.590 10637 10647 D BadgeProvider: update, [uri.query] : null
03-21 16:48:26.590 10637 10647 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 16:48:26.590 10637 10647 D BadgeProvider: update, [UpdateCount] : 1
,03-21 16:48:26.590  3390  3592 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-21 16:48:26.590  3390  3592 I AASA_removePackage: UID=10011 Target=com.test.thalitest
,03-21 16:48:26.590  4014  4014 D Launcher.Model: reloadBadges entered.
03-21 16:48:26.590  3390  3592 D PackageManager: result of delete: 1{14535001}
,03-21 16:48:26.590 12995 12995 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:26.595 12995 12995 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:26.600 12880 12880 I art     : System.exit called, status: 0
03-21 16:48:26.600 12880 12880 I AndroidRuntime: VM exiting with result code 0.
03-21 16:48:26.600  3390  3592 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 16:48:26.600  3390  3592 D PackageManager: userId{-1}
03-21 16:48:26.600  3390  3592 D PackageManager: andCode{true}
,03-21 16:48:26.610 10637 10647 D BadgeProvider: query, [selection] : null
03-21 16:48:26.610  3390  4415 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3b372e73 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{22c0896d 12995:com.samsung.android.app.assistantmenu/1000}
,03-21 16:48:26.615  3390  4007 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.615  3390  4007 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.615  3390  4007 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.615  3390  4007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.625  3390  3390 D RCPManagerService: PackageReceiver onReceive()
03-21 16:48:26.625  3390  3390 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-21 16:48:26.630  3390  3390 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-21 16:48:26.630  3390  3390 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-21 16:48:26.630  3390  3390 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-21 16:48:26.630  3390  3390 I OTPFW   : ProvisionData::getAllEntries Enter
,03-21 16:48:26.630  3390  3390 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-21 16:48:26.630  3390  3390 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 16:48:26.630  3390  3390 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 16:48:26.635 13014 13014 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.635 13014 13014 E Zygote  : v2
03-21 16:48:26.635 13014 13014 I libpersona: KNOX_SDCARD checking this for 10190
03-21 16:48:26.635 13014 13014 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.635 13014 13014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.635 13014 13014 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:26.635 13014 13014 E Zygote  : accessInfo : 0
,03-21 16:48:26.635 13014 13014 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.640  3390  4007 I ActivityManager: Start proc 13014:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
,03-21 16:48:26.645  3390  3573 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-21 16:48:26.645  3390  3573 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicy: uID is 10011
03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 16:48:26.645  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 16:48:26.650  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 16:48:26.650  3390  3390 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 16:48:26.650  3390  3390 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-21 16:48:26.650  3390  3390 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
,03-21 16:48:26.650  4014  4014 E Launcher.Model: onPackageRemoved :com.test.thalitest
,03-21 16:48:26.655  3390  3390 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-21 16:48:26.655  3390  3594 D EnterprisePartitionManager: RCV <-
03-21 16:48:26.655  3390  3390 D EnterprisePartitionManager: RMV <-
,03-21 16:48:26.660 13014 13014 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:26.665 13014 13014 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:26.670  9637 13030 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-21 16:48:26.670  9637 13030 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
,03-21 16:48:26.670  9637 13030 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-21 16:48:26.670  9637 13030 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
,03-21 16:48:26.670  9637 13030 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-21 16:48:26.670  3390  3390 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-21 16:48:26.675  3390  3390 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-21 16:48:26.675  3390  3390 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 16:48:26.675  3390  3390 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-21 16:48:26.675  3390  4111 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a3551a9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{34a4e102 13014:com.sec.android.widgetapp.tapandpay/u0a190}
03-21 16:48:26.675  3390  3390 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-21 16:48:26.675  3390  3390 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.675  3390  3390 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.675  3390  3390 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 16:48:26.675  3390  3390 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 16:48:26.675  3390  3390 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 16:48:26.675  3390  3390 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 16:48:26.675  3390  3390 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-21 16:48:26.675  3390  3390 W System.err: 	at libcore.io.Posix.open(Native Method)
03-21 16:48:26.675  3390  3390 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 16:48:26.675  3390  3390 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 16:48:26.675  3390  3390 W System.err: 	... 18 more
03-21 16:48:26.675  3390  3390 E SdpManagerService: failed to get engine list
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicy: uID is 10011
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 16:48:26.675  3390  6044 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicyStorage: getProfileF,orApplication - enter
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 16:48:26.675  9637 13030 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
03-21 16:48:26.675 12995 12995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
03-21 16:48:26.675  3390  3390 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 16:48:26.680  3390  4007 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-21 16:48:26.695  3390  3390 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2bbb19a7 6111:com.sec.android.service.health/u0a19}
,03-21 16:48:26.700  6111  6111 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,03-21 16:48:26.700  6111  6111 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-21 16:48:26.700  6111  6111 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-21 16:48:26.700  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.700  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.700  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.700  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.715 13033 13033 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.715 13033 13033 I libpersona: KNOX_SDCARD checking this for 1000
03-21 16:48:26.715 13033 13033 E Zygote  : v2
03-21 16:48:26.715 13033 13033 I libpersona: KNOX_SDCARD not a persona
03-21 16:48:26.720 13014 13014 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-21 16:48:26.720 13014 13014 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
03-21 16:48:26.720 13033 13033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.720 13033 13033 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 16:48:26.720 13033 13033 E Zygote  : accessInfo : 0
03-21 16:48:26.720 13033 13033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.735  3390  3651 I ActivityManager: Start proc 13033:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
,03-21 16:48:26.735 13014 13014 I TapandpayWidget:Utils: Clear T&P info.
,03-21 16:48:26.740  3390  3390 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
,03-21 16:48:26.745 13014 13014 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,03-21 16:48:26.750  3390  3651 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2f1729f2 10541:com.sec.android.widgetapp.locationwidget/u0a22}
,03-21 16:48:26.755 13033 13033 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 16:48:26.755 13033 13033 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:26.760  3390  3651 I ActivityManager: Killing 10347:com.samsung.helphub/1000 (adj 15): emptyCount ##31
,03-21 16:48:26.765  2903  2903 I art     : Explicit concurrent mark sweep GC freed 8767(373KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 419us total 30.756ms
,03-21 16:48:26.770 10541 10541 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-21 16:48:26.770  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 290us total 8.807ms
,03-21 16:48:26.780  3390  3832 I ActivityManager: Killing 10379:com.samsung.android.intelligenceservice/u0a3 (adj 15): emptyCount ##31
,03-21 16:48:26.780  2903  2903 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 303us total 8.494ms
,03-21 16:48:26.785  3390  3832 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3b372e73 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{13198e5a 13033:com.sec.knox.bridge/1000}
,03-21 16:48:26.790  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.790  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.790  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.790  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:26.800 13033 13033 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 16:48:26.805 13049 13049 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.805 13049 13049 E Zygote  : v2
03-21 16:48:26.805 13049 13049 I libpersona: KNOX_SDCARD checking this for 10193
03-21 16:48:26.805 12945 12992 E SQLiteLog: (10) unixWrite() File Descriptor : 35 gets errno : 9
03-21 16:48:26.805 13049 13049 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.805 13049 13049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.810 13049 13049 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:26.810 13049 13049 E Zygote  : accessInfo : 0
03-21 16:48:26.810 13049 13049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 16:48:26.810  3390  3651 I ActivityManager: Start proc 13049:com.sec.enterprise.knox.cloudmdm.smdms/u0a193 for broadcast-4 com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver
,03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Error Code : 778 (SQLITE_IOERR_WRITE)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Caused By : Disk I/O error occurred during 'write' operation.
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 778))
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:185)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 16:48:26.815 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.815 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.815 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.815 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Error inserting name=DBVersion value=2003
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is p,ossibility the partition changed to read-only.
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.815 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.820 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.820 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 ,16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.820 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.820 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Error inserting name=UT enabled value=false
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.820 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.820 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.820 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.825 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.825 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.825  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.825 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.825  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.825 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 16:48:26.825  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.825 13049 13049 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 16:48:26.825  3390  3651 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.1.1
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.825 12945 12992 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:26.825 12945 12992 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 16:48:26.825 13049 13049 D ActivityThread: Added TimaKeyStore provider
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Error inserting name=status value=successfully initialized
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: #################################################################
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.825 12945 12992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 16:48:26.845  2860  3056 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
03-21 16:48:26.845  2860  3056 W Vold    : Returning OperationFailed - no handler for errno 0
03-21 16:48:26.845 12930 12930 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
03-21 16:48:26.845 12930 12930 D SecWifiDisplayUtil: Metadata value : none
03-21 16:48:26.850 13066 13066 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.850 13066 13066 I libpersona: KNOX_SDCARD checking this for 1000
03-21 16:48:26.850 13066 13066 E Zygote  : v2
03-21 16:48:26.850 13066 13066 I libpersona: KNOX_SDCARD not a persona
03-21 16:48:26.850 13066 13066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.850 13066 13066 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 16:48:26.855 13066 13066 E Zygote  : accessInfo : 0
,03-21 16:48:26.855 13066 13066 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 16:48:26.855 13033 13033 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
03-21 16:48:26.855  3390  3651 I ActivityManager: Start proc 13066:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
03-21 16:48:26.855  3390  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-21 16:48:26.855  3390  3604 D UsbHostManager: displayNotification : [02h,02h,01h]
03-21 16:48:26.860  3390  4657 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-21 16:48:26.860  3390  3651 I ActivityManager: Killing 10396:com.samsung.android.bbc.bbcagent/1000 (adj 15): emptyCount ##31
03-21 16:48:26.860  3390  4657 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
03-21 16:48:26.865  3390  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-21 16:48:26.865  3390  3604 D UsbHostManager: displayNotification : [0ah,00h,00h]
03-21 16:48:26.865  3390  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-21 16:48:26.865  3390  3604 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-21 16:48:26.865  3390  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-21 16:48:26.865  3390  3604 D UsbHostManager: displayNotification : [0ah,00h,01h]
03-21 16:48:26.865  3390  3694 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-21 16:48:26.865  3390  3694 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-21 16:48:26.865  3390  3694 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
03-21 16:48:26.870 13066 13066 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 16:48:26.870 13066 13066 D ActivityThread: Added TimaKeyStore provider
03-21 16:48:26.870  3390  4242 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a3551a9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{ad23626 13049:com.sec.enterprise.knox.cloudmdm.smdms/u0a193}
03-21 16:48:26.880  3390  3604 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-21 16:48:26.880  3390  3604 D UsbHostManager: displayNotification : [09h,00h,00h]
03-21 16:48:26.885  3390  4727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2f64d267 13066:com.sec.pcw.device/1000}
03-21 16:48:26.885 13049 13049 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-21 16:48:26.885  3390  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.885  3390  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.885  3390  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.885  3390  4030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:26.890  3390  3694 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-21 16:48:26.890  3390  3694 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,03-21 16:48:26.945 13049 13049 D [0]UMC:UMCContentProvider: @onCreate
,03-21 16:48:26.955  3390  3632 I EventHub: Removing device '/dev/input/event10' due to inotify event
,03-21 16:48:26.960 13090 13090 E Zygote  : MountEmulatedStorage()
03-21 16:48:26.960 13090 13090 E Zygote  : v2
03-21 16:48:26.960 13090 13090 I libpersona: KNOX_SDCARD checking this for 10101
03-21 16:48:26.960 13090 13090 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:26.960 13090 13090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:26.960  3390  4030 I ActivityManager: Start proc 13090:com.google.android.apps.docs/u0a101 for broadcast-4 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
03-21 16:48:26.965 13090 13090 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 16:48:26.965 13090 13090 E Zygote  : accessInfo : 0
03-21 16:48:26.965 13090 13090 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-21 16:48:26.970 13066 13066 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-21 16:48:26.970 13066 13066 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-21 16:48:26.970 13066 13066 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-21 16:48:26.970 13066 13066 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
03-21 16:48:26.970  3390  4030 I ActivityManager: Killing 10425:com.google.android.apps.plus/u0a147 (adj 15): emptyCount ##31
,03-21 16:48:26.975 13066 13066 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: #################################################################
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: #################################################################
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
,03-21 16:48:26.975 13066 13066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 16:48:26.975 13066 13066 D AndroidRuntime: Shutting down VM
03-21 16:48:26.975  3390  4111 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
03-21 16:48:26.980 13066 13066 E AndroidRuntime: FATAL EXCEPTION: main
03-21 16:48:26.980 13066 13066 E AndroidRuntime: Process: com.sec.pcw.device, PID: 13066
03-21 16:48:26.980 13066 13066 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
03-21 16:48:26.980 13066 13066 E AndroidRuntime: #################################################################
03-21 16:48:26.980 13066 13066 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 16:48:26.980 13066 13066 E AndroidRuntime: #################################################################
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 16:48:26.980 13066 13066 E AndroidRuntime: #################################################################
03-21 16:48:26.980 13066 13066 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 16:48:26.980 13066 13066 E AndroidRuntime: #################################################################
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.database.sqli,te.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 16:48:26.980 13066 13066 E AndroidRuntime: 	... 11 more
,03-21 16:48:27.005 13090 13090 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:27.010 13090 13090 D ActivityThread: Added TimaKeyStore provider
03-21 16:48:27.010  3390  3632 I EventHub: Removing device '/dev/input/event7' due to inotify event
,03-21 16:48:27.030 13049 13049 D [0]UMC:Core: onCreate(): 
03-21 16:48:27.030 13049 13049 D [0]UMC:Core: @isManagedProfileUser
,03-21 16:48:27.030  3390  4730 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,03-21 16:48:27.035 13049 13049 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-21 16:48:27.035  2860  3056 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
03-21 16:48:27.035  2860  3056 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 16:48:27.040 12930 12930 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,03-21 16:48:27.055  3390  4729 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{3b372e73 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1df658bd 13090:com.google.android.apps.docs/u0a101}
03-21 16:48:27.060  3390  3632 I EventHub: Removing device '/dev/input/event8' due to inotify event
,03-21 16:48:27.075  3390 13105 E DropBoxManagerService: Can't write: system_app_crash
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 16:48:27.075  3390 13105 E DropBoxManagerService: 	... 5 more
,03-21 16:48:27.080  3390 13105 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop227.tmp
,03-21 16:48:27.090  3390  4007 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,03-21 16:48:27.100 12945 12945 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-21 16:48:27.100  3390  3632 I EventHub: Removing device '/dev/input/event9' due to inotify event
03-21 16:48:27.105  3390  4007 I ActivityManager: Killing 10497:com.samsung.android.snote:provider/u0a160 (adj 15): emptyCount ##31
,03-21 16:48:27.135  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:27.135  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:27.135  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:27.135  3390  3576 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:27.145 13049 13049 D [0]UMC:DeviceInfo: USA==US==
,03-21 16:48:27.160  3390  3632 I EventHub: Removing device '/dev/input/event11' due to inotify event
,03-21 16:48:27.175 13108 13108 E Zygote  : MountEmulatedStorage()
03-21 16:48:27.175 13108 13108 E Zygote  : v2
03-21 16:48:27.175 13108 13108 I libpersona: KNOX_SDCARD checking this for 10035
03-21 16:48:27.175 13108 13108 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:27.180 13108 13108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 16:48:27.180 13108 13108 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:27.185 13108 13108 E Zygote  : accessInfo : 0
,03-21 16:48:27.190 13108 13108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 16:48:27.190  3390  3576 I ActivityManager: Start proc 13108:com.samsung.android.app.galaxyfinder/u0a35 for broadcast-3 com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver
,03-21 16:48:27.200 13066 13066 I Process : Sending signal. PID: 13066 SIG: 9
,03-21 16:48:27.205 10637 10649 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 16:48:27.205 10637 10649 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
03-21 16:48:27.215  3390  3632 I EventHub: Removing device '/dev/input/event12' due to inotify event
,03-21 16:48:27.220  3390  3423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:27.220  3390  3423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:27.220  3390  3423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 16:48:27.220  3390  3423 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 16:48:27.225 13049 13049 D USER_AGENT: UMC/1.4.26 (SM-N910C) SAFE-5.4.1 KNOX-2.4.1 en_US
,03-21 16:48:27.230 10637 10649 E DatabaseUtils: Writing exception to parcel
03-21 16:48:27.230 10637 10649 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: #################################################################
03-21 16:48:27.230 10637 10649 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	(disk I/O error (code 6922))
03-21 16:48:27.230 10637 10649 E DatabaseUtils: #################################################################
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
03-21 16:48:27.230 10637 10649 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-21 16:48:27.235 13049 13049 D [0]UMC:AdminManager: init - start
,03-21 16:48:27.240 13090 13090 E PhotosPlugin: Loading PhotosPlugin
,03-21 16:48:27.260 13123 13123 E Zygote  : MountEmulatedStorage()
03-21 16:48:27.260 13123 13123 E Zygote  : v2
03-21 16:48:27.260 13123 13123 I libpersona: KNOX_SDCARD checking this for 10045
03-21 16:48:27.260 13123 13123 I libpersona: KNOX_SDCARD not a persona
,03-21 16:48:27.260 13049 13049 D [0]UMC:AdminManager: loadAdmins
,03-21 16:48:27.265 13123 13123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 16:48:27.265 13123 13123 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 16:48:27.270 13123 13123 E Zygote  : accessInfo : 0
03-21 16:48:27.270  3390  3423 I ActivityManager: Start proc 13123:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
,03-21 16:48:27.275 13123 13123 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 16:48:27.275  3390  3632 I EventHub: Removing device '/dev/input/event13' due to inotify event
,03-21 16:48:27.280 13108 13108 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:27.280 13108 13108 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:27.300 13049 13049 D [0]UMC:AdminManager: init - end
,03-21 16:48:27.305 13049 13049 D GSLBManager: migrateStoredUrlFromOldPref
,03-21 16:48:27.315 13049 13049 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-21 16:48:27.325 13123 13123 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 16:48:27.330 13123 13123 D ActivityThread: Added TimaKeyStore provider
,03-21 16:48:27.330  3390  3632 I EventHub: Removing device '/dev/input/event14' due to inotify event
,03-21 16:48:27.340  3390  4730 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2435e5f7 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{284fa75f 13108:com.samsung.android.app.galaxyfinder/u0a35}
,03-21 16:48:27.345  3390  4657 I ActivityManager: Process com.sec.pcw.device (pid 13066)(adj 9) has died(278,1513)
03-21 16:48:27.345 13049 13049 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
03-21 16:48:27.345 13049 13049 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
03-21 16:48:27.345 13049 13049 D [0]UMC:CoreReceiver: Intent Replacing : false
,03-21 16:48:27.355  3390  4730 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 16:48:27.370 13049 13049 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-21 16:48:27.380 13049 13049 V [0]UMC:ProfileStorage: Enter loadList
,03-21 16:48:27.385 13049 13049 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
,03-21 16:48:27.385  3390  3651 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{25cc3ecf u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{16365ac 13123:com.osp.app.signin/u0a45}
,03-21 16:48:27.405  3390  4007 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{1a3551a9 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{963a9dd 4454:com.google.android.gms.persistent/u0a14}
,03-21 16:48:27.415  3390  4030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms

```
