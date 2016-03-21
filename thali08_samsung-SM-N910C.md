#### Test 625481246894564_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
,03-21 13:04:17.935  3369  5929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 13:04:17.935  3369  5929 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:04:17.935  3369  5929 D BatteryService: online:4, current avg:69, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
03-21 13:04:17.940  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 13:04:17.945  3369  5929 D BatteryService: stay LED for fully charged
03-21 13:04:17.945  3369  3369 I MotionRecognitionService: Plugged
03-21 13:04:17.945  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:04:17.945  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:04:17.945  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
03-21 13:04:17.955  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:04:17.955  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:04:17.955  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 13:04:17.970  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 13:04:17.970  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
03-21 13:04:17.985  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:04:17.985  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:17.985  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:17.985  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:18.415 11181 11181 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 13:04:18.420 11181 11181 D AndroidRuntime: CheckJNI is OFF
03-21 13:04:18.420 11181 11181 D AndroidRuntime: readGMSProperty: start
03-21 13:04:18.420 11181 11181 D AndroidRuntime: readGMSProperty: already setted!!
03-21 13:04:18.420 11181 11181 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 13:04:18.420 11181 11181 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 13:04:18.420 11181 11181 D AndroidRuntime: readGMSProperty: end
03-21 13:04:18.420 11181 11181 D AndroidRuntime: addProductProperty: start
03-21 13:04:18.520 11181 11181 E AffinityControl: AffinityControl: registerfunction enter
03-21 13:04:18.535 11181 11181 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 13:04:18.545  3369  3822 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 13:04:18.550  3369  3822 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 13:04:18.590  3369  3822 W ActivityManager: mDVFSHelper.acquire()
03-21 13:04:18.590  3369  3822 D FocusedStackFrame: Set to : 0
03-21 13:04:18.595  3369  3822 V WindowManager: addAppToken: AppWindowToken{1cf0fc2b token=Token{14199c7a ActivityRecord{2d6060a5 u0 com.test.thalitest/.MainActivity t41}}} to stack=1 task=41 at 0
03-21 13:04:18.595  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:04:18.595  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:04:18.595  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:04:18.595  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:04:18.605  3369  3580 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 13:04:18.605  3369  3580 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 13:04:18.605  3369  3580 D SecWifiDisplayUtil: Metadata value : none
03-21 13:04:18.610  3369  3580 V WindowManager: Adding window Window{2f0b40d2 u0 d0 Starting com.test.thalitest} at 2 of 6 (after Window{145e87b2 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher})
03-21 13:04:18.615 11201 11201 E Zygote  : MountEmulatedStorage()
03-21 13:04:18.615 11201 11201 E Zygote  : v2
03-21 13:04:18.615 11201 11201 I libpersona: KNOX_SDCARD checking this for 10011
03-21 13:04:18.615 11201 11201 I libpersona: KNOX_SDCARD not a persona
03-21 13:04:18.620 11201 11201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:04:18.620 11201 11201 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 13:04:18.620 11201 11201 E Zygote  : accessInfo : 0
03-21 13:04:18.620 11201 11201 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 13:04:18.620  3369  3822 I ActivityManager: Start proc 11201:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-21 13:04:18.620  3369  3822 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 13:04:18.620  3369  3822 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 13:04:18.625  3369  3822 D InputDispatcher: Focused application set to: xxxx
03-21 13:04:18.625  3369  3822 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-21 13:04:18.625  3369  3822 D InputDispatcher: Focus left window: 4032
03-21 13:04:18.625 11181 11181 D AndroidRuntime: Shutting down VM
03-21 13:04:18.625  3369  3580 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 13:04:18.625  3369  3580 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 13:04:18.625  2858  2858 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-21 13:04:18.640 11201 11201 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 13:04:18.645 11201 11201 D ActivityThread: Added TimaKeyStore provider
03-21 13:04:18.650  3369  3387 V WindowOrientationListener: setCurrentAppOrientation :-1
03-21 13:04:18.650  3369  3387 V WindowOrientationListener: setCurrentAppOrientation enable auto rotation
03-21 13:04:18.650  3369  3387 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false
03-21 13:04:18.650  3369  3387 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 13:04:18.650  3369  3387 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 13:04:18.650  3369  3387 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 13:04:18.650  3369  3387 D PowerManagerService: setKeyboardVisibility: false
03-21 13:04:18.650  3369  3387 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 13:04:18.650  3369  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3369 uid:1000
03-21 13:04:18.650  3369  3578 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{2f0b40d2 u0 d0 Starting com.test.thalitest}
03-21 13:04:18.650  3369  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 13:04:18.650  3369  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3369 uid:1000
03-21 13:04:18.650  3369  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 13:04:18.655  3369  3387 D ActivityManager:  Launching com.test.thalitest, updated priority
03-21 13:04:18.665  3369  3387 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{2d6060a5 u0 com.test.thalitest/.MainActivity t41}
03-21 13:04:18.670  3369  3620 V AlarmManager: waitForAlarm result :4
03-21 13:04:18.685  2858  3632 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
03-21 13:04:18.685  2858  3012 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
03-21 13:04:18.690  4032  4032 V ActivityThread: updateVisibility : ActivityRecord{1d9a33c2 token=android.os.BinderProxy@29e520ef {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-21 13:04:18.690  4032  4032 D Launcher: onTrimMemory. Level: 20
03-21 13:04:18.830  3369  6063 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 13:04:18.870 11201 11201 D SecWifiDisplayUtil: Metadata value : none
,03-21 13:04:18.920 11201 11201 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-21 13:04:18.930 11201 11201 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5990-5991)
03-21 13:04:18.930 11201 11201 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 13:04:18.945 11201 11201 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d6f115c}
03-21 13:04:18.945 11201 11217 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-21 13:04:18.945 11201 11201 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 13:04:18.945 11201 11201 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 13:04:18.965 11201 11201 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 13:04:18.965 11201 11201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 13:04:18.970 11201 11201 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 13:04:18.990 11201 11201 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-21 13:04:18.995 11201 11201 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-21 13:04:18.995 11201 11201 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-21 13:04:19.070 11201 11240 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-21 13:04:19.120 11201 11201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 13:04:19.145 11201 11201 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 13:04:19.165  3369  6063 D SSRM:n  : SIOP:: AP = 270, PST = 282 (W:14), CUR = 69, LCD = 0
,03-21 13:04:19.165 11201 11201 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 13:04:19.165 11201 11201 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-21 13:04:19.175 11201 11201 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-21 13:04:19.190 11201 11201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 13:04:19.190 11201 11201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 13:04:19.250 11201 11253 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 13:04:19.255  3369  3965 V WindowManager: Adding window Window{6cd0ae8 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (before Window{2f0b40d2 u0 d0 Starting com.test.thalitest})
,03-21 13:04:19.260  3369  4402 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-21 13:04:19.260  3369  4402 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 13:04:19.260  3369  4402 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-21 13:04:19.260  3369  3369 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-21 13:04:19.260  3369  3369 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
,03-21 13:04:19.260  3369  3369 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-21 13:04:19.265  3369  3369 I EnterpriseSharedDevicePolicy: Get Result: -1
03-21 13:04:19.265  3369  3369 I EnterpriseSharedDevicePolicy: status: false
03-21 13:04:19.265  3369  3369 I KnoxTimeoutHandler: Shared devices show user statefalse
03-21 13:04:19.265  3369  3369 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 13:04:19.280 11201 11201 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 13:04:19.280 11201 11201 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-21 13:04:19.285 11201 11201 D SecWifiDisplayUtil: Metadata value : none
,03-21 13:04:19.290  2858  2858 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,03-21 13:04:19.290  3369  4404 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 13:04:19.300  3369  4404 D InputDispatcher: Focus entered window: 11201
,03-21 13:04:19.305  3369  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3369 uid:1000
03-21 13:04:19.305  3369  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 13:04:19.305  3369  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3369 uid:1000
03-21 13:04:19.305  3369  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 13:04:19.305 11201 11201 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-21 13:04:19.305 11201 11253 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 13:04:19.305 11201 11253 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae82fe50 ,&mEglDisplay = 1 , &mEglConfig = -1266876144 
,03-21 13:04:19.310 11201 11253 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-21 13:04:19.310 11201 11253 D OpenGLRenderer: Enabling debug mode 0
,03-21 13:04:19.310 11201 11253 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-21 13:04:19.310 11201 11201 V ActivityThread: updateVisibility : ActivityRecord{1f837e24 token=android.os.BinderProxy@324279b6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-21 13:04:19.375  3369  3965 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 13:04:19.380  3728  3728 D PanelView: There is/are notification(s) 
,03-21 13:04:19.385  3369  3580 I ActivityManager: Displayed Component not be shown by security: +577ms (total +1m27s957ms)
,03-21 13:04:19.385  3369  3580 W ActivityManager: mDVFSHelper.release()
,03-21 13:04:19.385  3369  3580 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d6060a5 u0 com.test.thalitest/.MainActivity t41} time:186449
,03-21 13:04:19.390  2858  3010 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,03-21 13:04:19.390  2858  3012 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,03-21 13:04:19.415 11201 11201 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 13:04:19.415 11201 11201 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@324279b6 time:186476
,03-21 13:04:19.440 11201 11201 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11201
,03-21 13:04:19.565 11201 11201 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 13:04:19.635 11201 11257 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626265472
,03-21 13:04:19.640 11201 11257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 13:04:19.640 11201 11257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 13:04:19.640 11201 11257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 13:04:19.640 11201 11257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 13:04:19.640 11201 11257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 13:04:19.640 11201 11257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b443fd added. We now have 1 listener(s)
,03-21 13:04:19.645 11201 11257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-21 13:04:19.645 11201 11257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 13:04:19.645 11201 11257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 13:04:19.650 11201 11257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 13:04:19.650 11201 11217 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 13:04:19.650 11201 11257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ef05c0 added. We now have 1 listener(s)
03-21 13:04:19.650 11201 11257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 13:04:19.655 11201 11257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 13:04:19.660 11201 11257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-21 13:04:19.660 11201 11257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 13:04:19.660 11201 11257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 13:04:19.660 11201 11257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 13:04:19.665 11201 11257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-21 13:04:19.665 11201 11257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:04:19.670 11201 11257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:04:19.670 11201 11257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 13:04:19.670 11201 11257 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-21 13:04:19.670 11201 11257 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 13:04:19.675 11201 11201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 13:04:19.675 11201 11201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 13:04:19.700 11201 11201 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 13:04:20.075 11201 11264 W jxcore-log: Initializing JXcore engine
03-21 13:04:20.075 11201 11264 W jxcore-log: JXcore engine is ready
,03-21 13:04:20.105  4755  4755 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-21 13:04:20.105  4755  4755 E audit   : type=1400 msg=audit(1458561860.105:195): avc:  denied  { ioctl } for  pid=11264 comm="Thread-1534" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2207 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-21 13:04:20.105  3369  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-21 13:04:20.105  3369  3576 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-21 13:04:20.105  4755  4755 E audit   :  SEPF_SM-N910C_5.1.1_0035
03-21 13:04:20.105  4755  4755 E audit   : type=1300 msg=audit(1458561860.105:195): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=962048d8 items=0 ppid=2901 ppcomm=main pid=11264 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1534" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 13:04:20.105  4755  4755 E audit   : type=1320 msg=audit(1458561860.105:195): 
,03-21 13:04:20.110  3369  3576 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-21 13:04:20.110  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:04:20.110  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:04:20.110  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:04:20.110 11201 11264 W jxcore-log: Starting JXcore engine
03-21 13:04:20.110  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:04:20.120 11265 11265 E Zygote  : MountEmulatedStorage()
03-21 13:04:20.120 11265 11265 E Zygote  : v2
03-21 13:04:20.120 11265 11265 I libpersona: KNOX_SDCARD checking this for 1000
03-21 13:04:20.120 11265 11265 I libpersona: KNOX_SDCARD not a persona
,03-21 13:04:20.125 11265 11265 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 13:04:20.125 11265 11265 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:04:20.125 11265 11265 E Zygote  : accessInfo : 0
03-21 13:04:20.125  3369  3554 I ActivityManager: Start proc 11265:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
03-21 13:04:20.125 11265 11265 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 13:04:20.145 11265 11265 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:04:20.145 11265 11265 D ActivityThread: Added TimaKeyStore provider
,03-21 13:04:20.150  3369  3386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{152f5b2c u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{22f969f5 11265:com.samsung.android.securitylogagent/1000}
,03-21 13:04:20.160 11201 11264 W jxcore-log: Platform android
03-21 13:04:20.160 11201 11264 W jxcore-log: 
03-21 13:04:20.160 11201 11264 W jxcore-log: Process ARCH arm
03-21 13:04:20.160 11201 11264 W jxcore-log: 
,03-21 13:04:20.170 11265 11265 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
03-21 13:04:20.170 11265 11265 D SecurityLogAgent:  SeDenialReceiver : File path = null
03-21 13:04:20.175  3369  4404 I ActivityManager: Killing 10211:com.facebook.system/u0a10 (adj 15): emptyCount ##31
03-21 13:04:20.255 11201 11264 I jxcore-log: JXcore Cordova bridge is ready!
03-21 13:04:20.255 11201 11264 I jxcore-log: 
03-21 13:04:20.255 11201 11264 W jxcore-log: JXcore engine is started
03-21 13:04:20.265 11201 11257 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-21 13:04:20.265 11201 11201 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 13:04:21.610  3369  3693 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/41_task.xml.bak
,03-21 13:04:22.930  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 13:04:25.655  3369  3866 E Watchdog: !@Sync 6 [03-21 13:04:25.658]
,03-21 13:04:26.200 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:04:26.200 11201 11264 I jxcore-log: 
,03-21 13:04:26.205 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:04:26.205 11201 11264 I jxcore-log: 
,03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:04:26.205 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:04:26.210 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:04:26.210 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:04:26.210 11201 11264 I jxcore-log: 
,03-21 13:04:26.210 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:04:26.210 11201 11264 I jxcore-log: 
,03-21 13:04:26.535 11201 11264 I jxcore-log: Unit Test app is loaded
03-21 13:04:26.535 11201 11264 I jxcore-log: 
,03-21 13:04:26.540 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:04:26.540 11201 11264 I jxcore-log: 
,03-21 13:04:26.545 11201 11201 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 13:04:26.545 11201 11264 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-21 13:04:26.545 11201 11264 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-21 13:04:26.545 11201 11264 I jxcore-log: 
,03-21 13:04:26.550 11201 11264 I jxcore-log: My device name is: samsung-SM-N910C
03-21 13:04:26.550 11201 11264 I jxcore-log: 
,03-21 13:04:28.055  3369  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 13:04:28.055  3369  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:04:28.055  3369  3965 D BatteryService: online:4, current avg:-79, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-178
03-21 13:04:28.055  3369  3965 D BatteryService: stay LED for fully charged
03-21 13:04:28.055  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:04:28.055  3369  3369 I MotionRecognitionService: Plugged
03-21 13:04:28.055  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:04:28.055  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:04:28.055  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:04:28.055  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:04:28.055  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:04:28.060  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 13:04:28.060  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:04:28.060  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 13:04:28.060  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:04:28.075  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:28.075  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:28.075  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:04:28.645  3369  3588 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-21 13:04:28.660  3369  3588 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-21 13:04:28.875  2894  4757 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 13:04:28.925 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 13:04:28.925 11201 11264 I jxcore-log: 
,03-21 13:04:29.140 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-21 13:04:29.140 11201 11264 I jxcore-log: 
,03-21 13:04:29.145 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-21 13:04:29.145 11201 11264 I jxcore-log: 
,03-21 13:04:29.150 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-21 13:04:29.150 11201 11264 I jxcore-log: 
,03-21 13:04:29.170 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-21 13:04:29.170 11201 11264 I jxcore-log: 
,03-21 13:04:29.175  3369  6063 D SSRM:n  : SIOP:: AP = 310, PST = 282 (W:10), CUR = -79, LCD = 0
,03-21 13:04:29.180 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-21 13:04:29.180 11201 11264 I jxcore-log: 
,03-21 13:04:29.180 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-21 13:04:29.180 11201 11264 I jxcore-log: 
,03-21 13:04:30.415 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 13:04:30.415 11201 11264 I jxcore-log: 
,03-21 13:04:30.425 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-21 13:04:30.425 11201 11264 I jxcore-log: 
,03-21 13:04:30.430 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-21 13:04:30.430 11201 11264 I jxcore-log: 
,03-21 13:04:30.500 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-21 13:04:30.500 11201 11264 I jxcore-log: 
,03-21 13:04:30.535 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-21 13:04:30.535 11201 11264 I jxcore-log: 
,03-21 13:04:30.615 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-21 13:04:30.615 11201 11264 I jxcore-log: 
,03-21 13:04:30.615 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-21 13:04:30.615 11201 11264 I jxcore-log: 
,03-21 13:04:30.620 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-21 13:04:30.620 11201 11264 I jxcore-log: 
,03-21 13:04:30.630 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-21 13:04:30.630 11201 11264 I jxcore-log: 
,03-21 13:04:30.640 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-21 13:04:30.640 11201 11264 I jxcore-log: 
,03-21 13:04:30.705 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-21 13:04:30.705 11201 11264 I jxcore-log: 
,03-21 13:04:30.705 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-21 13:04:30.705 11201 11264 I jxcore-log: 
,03-21 13:04:30.720 11201 11264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-21 13:04:30.720 11201 11264 I jxcore-log: 
,03-21 13:04:31.660 11201 11264 I jxcore-log: TAP version 13
03-21 13:04:31.660 11201 11264 I jxcore-log: 
,03-21 13:04:31.660 11201 11264 I jxcore-log: # setup
03-21 13:04:31.660 11201 11264 I jxcore-log: 
,03-21 13:04:31.660 11201 11264 I jxcore-log: # 1. calling createNativeListener directly rejects
03-21 13:04:31.660 11201 11264 I jxcore-log: 
,03-21 13:04:32.010 11201 11264 I jxcore-log: # teardown
03-21 13:04:32.010 11201 11264 I jxcore-log: 
,03-21 13:04:32.070 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:32.070 11201 11264 I jxcore-log: 
,03-21 13:04:32.080 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 42116
03-21 13:04:32.080 11201 11264 I jxcore-log: 
,03-21 13:04:32.090 11201 11264 I jxcore-log: ok 1 Should throw
03-21 13:04:32.090 11201 11264 I jxcore-log: 
,03-21 13:04:32.100 11201 11264 I jxcore-log: # setup
03-21 13:04:32.100 11201 11264 I jxcore-log: 
,03-21 13:04:32.185 11201 11264 I jxcore-log: # 2. emits incomingConnectionState
03-21 13:04:32.185 11201 11264 I jxcore-log: 
,03-21 13:04:32.275 11201 11264 I jxcore-log: # teardown
03-21 13:04:32.275 11201 11264 I jxcore-log: 
,03-21 13:04:32.380 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:32.380 11201 11264 I jxcore-log: 
,03-21 13:04:32.385 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 40143
03-21 13:04:32.385 11201 11264 I jxcore-log: 
,03-21 13:04:32.400 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:32.400 11201 11264 I jxcore-log: 
,03-21 13:04:32.405 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:32.405 11201 11264 I jxcore-log: 
,03-21 13:04:32.415 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:32.415 11201 11264 I jxcore-log: 
,03-21 13:04:32.425 11201 11264 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-21 13:04:32.425 11201 11264 I jxcore-log: 
,03-21 13:04:32.440 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:32.440 11201 11264 I jxcore-log: 
,03-21 13:04:32.440 11201 11264 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-21 13:04:32.440 11201 11264 I jxcore-log: 
,03-21 13:04:32.445 11201 11264 I jxcore-log: # setup
03-21 13:04:32.445 11201 11264 I jxcore-log: 
,03-21 13:04:32.595 11201 11264 I jxcore-log: # 3. emits routerPortConnectionFailed
03-21 13:04:32.595 11201 11264 I jxcore-log: 
,03-21 13:04:32.790 11201 11264 I jxcore-log: # teardown
03-21 13:04:32.790 11201 11264 I jxcore-log: 
,03-21 13:04:32.935 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:32.935 11201 11264 I jxcore-log: 
,03-21 13:04:32.940 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 40315
03-21 13:04:32.940 11201 11264 I jxcore-log: 
,03-21 13:04:32.950 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:32.950 11201 11264 I jxcore-log: 
,03-21 13:04:32.955 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:32.955 11201 11264 I jxcore-log: 
,03-21 13:04:32.955 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:32.955 11201 11264 I jxcore-log: 
,03-21 13:04:32.995 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:32.995 11201 11264 I jxcore-log: 
,03-21 13:04:33.000 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:33.000 11201 11264 I jxcore-log: 
,03-21 13:04:33.005 11201 11264 I jxcore-log: DEBUG createNativeListener: 
03-21 13:04:33.005 11201 11264 I jxcore-log: 
,03-21 13:04:33.005 11201 11264 I jxcore-log: ok 4 tried to connect to right port
03-21 13:04:33.005 11201 11264 I jxcore-log: 
,03-21 13:04:33.005 11201 11264 I jxcore-log: ok 5 failed due to refused connection
03-21 13:04:33.005 11201 11264 I jxcore-log: 
,03-21 13:04:33.010 11201 11264 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-21 13:04:33.010 11201 11264 I jxcore-log: 
,03-21 13:04:33.025 11201 11264 I jxcore-log: # setup
03-21 13:04:33.025 11201 11264 I jxcore-log: 
,03-21 13:04:33.025 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:33.025 11201 11264 I jxcore-log: 
,03-21 13:04:33.165 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:33.165 11201 11264 I jxcore-log: 
,03-21 13:04:33.175 11201 11264 I jxcore-log: # 4. native server connections all up
03-21 13:04:33.175 11201 11264 I jxcore-log: 
,03-21 13:04:33.175 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:33.175 11201 11264 I jxcore-log: 
,03-21 13:04:33.270 11201 11264 I jxcore-log: # teardown
03-21 13:04:33.270 11201 11264 I jxcore-log: 
,03-21 13:04:33.355 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:33.355 11201 11264 I jxcore-log: 
,03-21 13:04:33.360 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 44095
03-21 13:04:33.360 11201 11264 I jxcore-log: 
,03-21 13:04:33.370 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:33.370 11201 11264 I jxcore-log: 
,03-21 13:04:33.375 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:33.375 11201 11264 I jxcore-log: 
,03-21 13:04:33.375 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:33.375 11201 11264 I jxcore-log: 
,03-21 13:04:33.410 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:33.410 11201 11264 I jxcore-log: 
,03-21 13:04:33.415 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:33.415 11201 11264 I jxcore-log: 
,03-21 13:04:33.415 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:33.415 11201 11264 I jxcore-log: 
,03-21 13:04:33.420 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:33.420 11201 11264 I jxcore-log: 
,03-21 13:04:33.440 11201 11264 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-21 13:04:33.440 11201 11264 I jxcore-log: 
,03-21 13:04:33.445 11201 11264 I jxcore-log: ok 8 Send/recvd #1 should be same
03-21 13:04:33.445 11201 11264 I jxcore-log: 
,03-21 13:04:33.445 11201 11264 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-21 13:04:33.445 11201 11264 I jxcore-log: 
,03-21 13:04:33.445 11201 11264 I jxcore-log: ok 10 Send/recvd #2 should be same
03-21 13:04:33.445 11201 11264 I jxcore-log: 
,03-21 13:04:33.450 11201 11264 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-21 13:04:33.450 11201 11264 I jxcore-log: 
,03-21 13:04:33.455 11201 11264 I jxcore-log: # setup
03-21 13:04:33.455 11201 11264 I jxcore-log: 
,03-21 13:04:33.505 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:33.505 11201 11264 I jxcore-log: 
,03-21 13:04:33.525 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:33.525 11201 11264 I jxcore-log: 
,03-21 13:04:33.525 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:33.525 11201 11264 I jxcore-log: 
,03-21 13:04:33.530 11201 11264 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-21 13:04:33.530 11201 11264 I jxcore-log: 
,03-21 13:04:33.530 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:33.530 11201 11264 I jxcore-log: 
,03-21 13:04:33.645 11201 11264 I jxcore-log: # teardown
03-21 13:04:33.645 11201 11264 I jxcore-log: 
,03-21 13:04:33.760 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:33.760 11201 11264 I jxcore-log: 
,03-21 13:04:33.785 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 60606
03-21 13:04:33.785 11201 11264 I jxcore-log: 
,03-21 13:04:33.810 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:33.810 11201 11264 I jxcore-log: 
,03-21 13:04:33.815 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:33.815 11201 11264 I jxcore-log: 
,03-21 13:04:33.820 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:33.820 11201 11264 I jxcore-log: 
,03-21 13:04:33.835 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:33.835 11201 11264 I jxcore-log: 
,03-21 13:04:33.840 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:33.840 11201 11264 I jxcore-log: 
,03-21 13:04:33.855 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:33.855 11201 11264 I jxcore-log: 
,03-21 13:04:33.875 11201 11264 I jxcore-log: ok 12 socket shouldn't close until after stream
03-21 13:04:33.875 11201 11264 I jxcore-log: 
,03-21 13:04:33.875 11201 11264 I jxcore-log: ok 13 incoming remains open
03-21 13:04:33.875 11201 11264 I jxcore-log: 
,03-21 13:04:33.885 11201 11264 I jxcore-log: # setup
03-21 13:04:33.885 11201 11264 I jxcore-log: 
,03-21 13:04:34.050 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:34.050 11201 11264 I jxcore-log: 
,03-21 13:04:34.055 11201 11264 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-21 13:04:34.055 11201 11264 I jxcore-log: 
,03-21 13:04:34.060 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:34.060 11201 11264 I jxcore-log: 
,03-21 13:04:34.190 11201 11264 I jxcore-log: # teardown
03-21 13:04:34.190 11201 11264 I jxcore-log: 
,03-21 13:04:34.385 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:34.385 11201 11264 I jxcore-log: 
,03-21 13:04:34.390 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 38501
03-21 13:04:34.390 11201 11264 I jxcore-log: 
,03-21 13:04:34.400 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:34.400 11201 11264 I jxcore-log: 
,03-21 13:04:34.405 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:34.405 11201 11264 I jxcore-log: 
,03-21 13:04:34.405 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:34.405 11201 11264 I jxcore-log: 
,03-21 13:04:34.420 11201 11264 I jxcore-log: ok 14 we should not have gotten an error
03-21 13:04:34.420 11201 11264 I jxcore-log: 
,03-21 13:04:34.430 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:34.430 11201 11264 I jxcore-log: 
,03-21 13:04:34.435 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:34.435 11201 11264 I jxcore-log: 
,03-21 13:04:34.450 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:34.450 11201 11264 I jxcore-log: 
,03-21 13:04:34.450 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:34.450 11201 11264 I jxcore-log: 
,03-21 13:04:34.460 11201 11264 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-21 13:04:34.460 11201 11264 I jxcore-log: 
03-21 13:04:34.465 11201 11264 I jxcore-log: ok 16 incoming is cleaned up
03-21 13:04:34.465 11201 11264 I jxcore-log: 
03-21 13:04:34.475 11201 11264 I jxcore-log: # setup
03-21 13:04:34.475 11201 11264 I jxcore-log: 
,03-21 13:04:34.635 11201 11264 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-21 13:04:34.635 11201 11264 I jxcore-log: 
,03-21 13:04:34.805 11201 11264 I jxcore-log: # teardown
03-21 13:04:34.805 11201 11264 I jxcore-log: 
,03-21 13:04:34.900 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:34.900 11201 11264 I jxcore-log: 
,03-21 13:04:34.905 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 47626
03-21 13:04:34.905 11201 11264 I jxcore-log: 
,03-21 13:04:34.915 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:34.915 11201 11264 I jxcore-log: 
,03-21 13:04:34.920 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:34.920 11201 11264 I jxcore-log: 
,03-21 13:04:34.925 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:34.925 11201 11264 I jxcore-log: 
,03-21 13:04:34.935 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:34.935 11201 11264 I jxcore-log: 
,03-21 13:04:34.940 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:34.940 11201 11264 I jxcore-log: 
,03-21 13:04:34.960 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:34.960 11201 11264 I jxcore-log: 
,03-21 13:04:34.975 11201 11264 I jxcore-log: ok 17 stream was closed
03-21 13:04:34.975 11201 11264 I jxcore-log: 
,03-21 13:04:34.975 11201 11264 I jxcore-log: ok 18 incoming should survive
03-21 13:04:34.975 11201 11264 I jxcore-log: 
,03-21 13:04:34.975 11201 11264 I jxcore-log: ok 19 mux should have no streams
03-21 13:04:34.975 11201 11264 I jxcore-log: 
,03-21 13:04:34.985 11201 11264 I jxcore-log: # setup
03-21 13:04:34.985 11201 11264 I jxcore-log: 
,03-21 13:04:35.100 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:35.100 11201 11264 I jxcore-log: 
,03-21 13:04:35.110 11201 11264 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-21 13:04:35.110 11201 11264 I jxcore-log: 
,03-21 13:04:35.110 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:35.110 11201 11264 I jxcore-log: 
,03-21 13:04:35.450 11201 11264 I jxcore-log: # teardown
03-21 13:04:35.450 11201 11264 I jxcore-log: 
,03-21 13:04:35.515 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:35.515 11201 11264 I jxcore-log: 
,03-21 13:04:35.520 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 38269
03-21 13:04:35.520 11201 11264 I jxcore-log: 
,03-21 13:04:35.530 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:35.530 11201 11264 I jxcore-log: 
,03-21 13:04:35.530 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:35.530 11201 11264 I jxcore-log: 
,03-21 13:04:35.535 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:35.535 11201 11264 I jxcore-log: 
,03-21 13:04:35.545 11201 11264 I jxcore-log: ok 20 we should not have gotten an error
03-21 13:04:35.545 11201 11264 I jxcore-log: 
,03-21 13:04:35.555 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:35.555 11201 11264 I jxcore-log: 
,03-21 13:04:35.560 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:35.560 11201 11264 I jxcore-log: 
,03-21 13:04:35.570 11201 11264 I jxcore-log: ok 21 Buffers are identical
03-21 13:04:35.570 11201 11264 I jxcore-log: 
,03-21 13:04:35.575 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:35.575 11201 11264 I jxcore-log: 
,03-21 13:04:35.580 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:35.580 11201 11264 I jxcore-log: 
,03-21 13:04:35.585 11201 11264 I jxcore-log: ok 22 native server is nulled out
03-21 13:04:35.585 11201 11264 I jxcore-log: 
,03-21 13:04:35.585 11201 11264 I jxcore-log: ok 23 native server should be closed
03-21 13:04:35.585 11201 11264 I jxcore-log: 
,03-21 13:04:35.585 11201 11264 I jxcore-log: ok 24 incoming has been removed
03-21 13:04:35.585 11201 11264 I jxcore-log: 
,03-21 13:04:35.585 11201 11264 I jxcore-log: ok 25 Incoming should be done
03-21 13:04:35.585 11201 11264 I jxcore-log: 
,03-21 13:04:35.585 11201 11264 I jxcore-log: ok 26 The mux object should be closed
03-21 13:04:35.585 11201 11264 I jxcore-log: 
,03-21 13:04:35.585 11201 11264 I jxcore-log: ok 27 The mux stream should be closed
03-21 13:04:35.585 11201 11264 I jxcore-log: 
,03-21 13:04:35.590 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:35.590 11201 11264 I jxcore-log: 
,03-21 13:04:35.605 11201 11264 I jxcore-log: # setup
03-21 13:04:35.605 11201 11264 I jxcore-log: 
,03-21 13:04:35.715 11201 11264 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-21 13:04:35.715 11201 11264 I jxcore-log: 
,03-21 13:04:35.870 11201 11264 I jxcore-log: # teardown
03-21 13:04:35.870 11201 11264 I jxcore-log: 
,03-21 13:04:36.060 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:36.060 11201 11264 I jxcore-log: 
,03-21 13:04:36.065 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 42644
03-21 13:04:36.065 11201 11264 I jxcore-log: 
,03-21 13:04:36.100 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.100 11201 11264 I jxcore-log: 
,03-21 13:04:36.105 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.105 11201 11264 I jxcore-log: 
,03-21 13:04:36.105 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.105 11201 11264 I jxcore-log: 
,03-21 13:04:36.110 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.110 11201 11264 I jxcore-log: 
,03-21 13:04:36.110 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.110 11201 11264 I jxcore-log: 
,03-21 13:04:36.115 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.115 11201 11264 I jxcore-log: 
,03-21 13:04:36.120 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.120 11201 11264 I jxcore-log: 
,03-21 13:04:36.120 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.120 11201 11264 I jxcore-log: 
,03-21 13:04:36.125 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.125 11201 11264 I jxcore-log: 
,03-21 13:04:36.125 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.125 11201 11264 I jxcore-log: 
,03-21 13:04:36.130 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.130 11201 11264 I jxcore-log: 
,03-21 13:04:36.130 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.130 11201 11264 I jxcore-log: 
,03-21 13:04:36.135 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.135 11201 11264 I jxcore-log: 
,03-21 13:04:36.140 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.140 11201 11264 I jxcore-log: 
,03-21 13:04:36.140 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.140 11201 11264 I jxcore-log: 
,03-21 13:04:36.145 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.145 11201 11264 I jxcore-log: 
,03-21 13:04:36.150 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.150 11201 11264 I jxcore-log: 
,03-21 13:04:36.150 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.150 11201 11264 I jxcore-log: 
,03-21 13:04:36.155 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.155 11201 11264 I jxcore-log: 
,03-21 13:04:36.155 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.155 11201 11264 I jxcore-log: 
,03-21 13:04:36.160 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.160 11201 11264 I jxcore-log: 
,03-21 13:04:36.165 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.165 11201 11264 I jxcore-log: 
,03-21 13:04:36.165 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.165 11201 11264 I jxcore-log: 
,03-21 13:04:36.165 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.165 11201 11264 I jxcore-log: 
,03-21 13:04:36.170 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.170 11201 11264 I jxcore-log: 
,03-21 13:04:36.175 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.175 11201 11264 I jxcore-log: 
,03-21 13:04:36.180 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.180 11201 11264 I jxcore-log: 
,03-21 13:04:36.180 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:36.180 11201 11264 I jxcore-log: 
,03-21 13:04:36.185 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:36.185 11201 11264 I jxcore-log: 
,03-21 13:04:36.185 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:36.185 11201 11264 I jxcore-log: 
,03-21 13:04:36.325 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.325 11201 11264 I jxcore-log: 
,03-21 13:04:36.325 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.325 11201 11264 I jxcore-log: 
,03-21 13:04:36.330 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.330 11201 11264 I jxcore-log: 
,03-21 13:04:36.330 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.330 11201 11264 I jxcore-log: 
,03-21 13:04:36.330 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.330 11201 11264 I jxcore-log: 
,03-21 13:04:36.335 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.335 11201 11264 I jxcore-log: 
,03-21 13:04:36.335 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.335 11201 11264 I jxcore-log: 
,03-21 13:04:36.335 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.335 11201 11264 I jxcore-log: 
,03-21 13:04:36.340 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.340 11201 11264 I jxcore-log: 
,03-21 13:04:36.340 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.340 11201 11264 I jxcore-log: 
,03-21 13:04:36.340 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.340 11201 11264 I jxcore-log: 
,03-21 13:04:36.345 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.345 11201 11264 I jxcore-log: 
,03-21 13:04:36.345 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.345 11201 11264 I jxcore-log: 
,03-21 13:04:36.345 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.345 11201 11264 I jxcore-log: 
,03-21 13:04:36.350 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.350 11201 11264 I jxcore-log: 
,03-21 13:04:36.350 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.350 11201 11264 I jxcore-log: 
,03-21 13:04:36.350 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.350 11201 11264 I jxcore-log: 
,03-21 13:04:36.355 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.355 11201 11264 I jxcore-log: 
,03-21 13:04:36.355 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.355 11201 11264 I jxcore-log: 
,03-21 13:04:36.355 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.355 11201 11264 I jxcore-log: 
,03-21 13:04:36.355 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.355 11201 11264 I jxcore-log: 
,03-21 13:04:36.365 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.365 11201 11264 I jxcore-log: 
,03-21 13:04:36.365 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.365 11201 11264 I jxcore-log: 
,03-21 13:04:36.365 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.365 11201 11264 I jxcore-log: 
,03-21 13:04:36.370 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.370 11201 11264 I jxcore-log: 
,03-21 13:04:36.370 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.370 11201 11264 I jxcore-log: 
,03-21 13:04:36.370 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.370 11201 11264 I jxcore-log: 
,03-21 13:04:36.375 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.375 11201 11264 I jxcore-log: 
,03-21 13:04:36.375 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.375 11201 11264 I jxcore-log: 
,03-21 13:04:36.375 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.375 11201 11264 I jxcore-log: 
,03-21 13:04:36.375 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.375 11201 11264 I jxcore-log: 
,03-21 13:04:36.375 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.375 11201 11264 I jxcore-log: 
,03-21 13:04:36.380 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.380 11201 11264 I jxcore-log: 
,03-21 13:04:36.380 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.380 11201 11264 I jxcore-log: 
,03-21 13:04:36.380 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.380 11201 11264 I jxcore-log: 
,03-21 13:04:36.385 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.385 11201 11264 I jxcore-log: 
,03-21 13:04:36.385 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.385 11201 11264 I jxcore-log: 
,03-21 13:04:36.385 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.385 11201 11264 I jxcore-log: 
,03-21 13:04:36.385 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.385 11201 11264 I jxcore-log: 
,03-21 13:04:36.390 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.390 11201 11264 I jxcore-log: 
,03-21 13:04:36.390 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.390 11201 11264 I jxcore-log: 
,03-21 13:04:36.390 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.390 11201 11264 I jxcore-log: 
,03-21 13:04:36.395 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.395 11201 11264 I jxcore-log: 
,03-21 13:04:36.395 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.395 11201 11264 I jxcore-log: 
,03-21 13:04:36.395 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.395 11201 11264 I jxcore-log: 
,03-21 13:04:36.400 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.400 11201 11264 I jxcore-log: 
,03-21 13:04:36.400 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.400 11201 11264 I jxcore-log: 
,03-21 13:04:36.400 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.400 11201 11264 I jxcore-log: 
,03-21 13:04:36.410 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.410 11201 11264 I jxcore-log: 
,03-21 13:04:36.410 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.410 11201 11264 I jxcore-log: 
,03-21 13:04:36.410 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.410 11201 11264 I jxcore-log: 
,03-21 13:04:36.415 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.415 11201 11264 I jxcore-log: 
,03-21 13:04:36.415 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.415 11201 11264 I jxcore-log: 
,03-21 13:04:36.415 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.415 11201 11264 I jxcore-log: 
,03-21 13:04:36.420 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.420 11201 11264 I jxcore-log: 
,03-21 13:04:36.420 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.420 11201 11264 I jxcore-log: 
,03-21 13:04:36.420 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.420 11201 11264 I jxcore-log: 
,03-21 13:04:36.425 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.425 11201 11264 I jxcore-log: 
,03-21 13:04:36.425 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.425 11201 11264 I jxcore-log: 
,03-21 13:04:36.425 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.425 11201 11264 I jxcore-log: 
,03-21 13:04:36.425 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.425 11201 11264 I jxcore-log: 
,03-21 13:04:36.430 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.430 11201 11264 I jxcore-log: 
,03-21 13:04:36.430 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.430 11201 11264 I jxcore-log: 
,03-21 13:04:36.430 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.430 11201 11264 I jxcore-log: 
,03-21 13:04:36.435 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.435 11201 11264 I jxcore-log: 
,03-21 13:04:36.435 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.435 11201 11264 I jxcore-log: 
,03-21 13:04:36.435 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.435 11201 11264 I jxcore-log: 
,03-21 13:04:36.440 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.440 11201 11264 I jxcore-log: 
,03-21 13:04:36.440 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.440 11201 11264 I jxcore-log: 
,03-21 13:04:36.440 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.440 11201 11264 I jxcore-log: 
,03-21 13:04:36.440 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.440 11201 11264 I jxcore-log: 
,03-21 13:04:36.440 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.440 11201 11264 I jxcore-log: 
,03-21 13:04:36.445 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.445 11201 11264 I jxcore-log: 
,03-21 13:04:36.445 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.445 11201 11264 I jxcore-log: 
,03-21 13:04:36.445 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.445 11201 11264 I jxcore-log: 
,03-21 13:04:36.450 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.450 11201 11264 I jxcore-log: 
,03-21 13:04:36.450 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.450 11201 11264 I jxcore-log: 
,03-21 13:04:36.450 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.450 11201 11264 I jxcore-log: 
,03-21 13:04:36.450 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:36.450 11201 11264 I jxcore-log: 
,03-21 13:04:36.455 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:36.455 11201 11264 I jxcore-log: 
,03-21 13:04:36.520 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.520 11201 11264 I jxcore-log: 
,03-21 13:04:36.520 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.520 11201 11264 I jxcore-log: 
,03-21 13:04:36.520 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.520 11201 11264 I jxcore-log: 
,03-21 13:04:36.520 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.520 11201 11264 I jxcore-log: 
,03-21 13:04:36.525 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.525 11201 11264 I jxcore-log: 
,03-21 13:04:36.525 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.525 11201 11264 I jxcore-log: 
,03-21 13:04:36.525 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.525 11201 11264 I jxcore-log: 
03-21 13:04:36.525 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.525 11201 11264 I jxcore-log: 
,03-21 13:04:36.525 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.525 11201 11264 I jxcore-log: 
03-21 13:04:36.525 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.525 11201 11264 I jxcore-log: 
,03-21 13:04:36.530 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.530 11201 11264 I jxcore-log: 
,03-21 13:04:36.530 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.530 11201 11264 I jxcore-log: 
,03-21 13:04:36.530 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.530 11201 11264 I jxcore-log: 
03-21 13:04:36.530 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.530 11201 11264 I jxcore-log: 
,03-21 13:04:36.530 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.530 11201 11264 I jxcore-log: 
,03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
,03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
,03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.535 11201 11264 I jxcore-log: 
,03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
,03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
,03-21 13:04:36.535 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.535 11201 11264 I jxcore-log: 
03-21 13:04:36.540 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.540 11201 11264 I jxcore-log: 
,03-21 13:04:36.540 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.540 11201 11264 I jxcore-log: 
,03-21 13:04:36.540 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.540 11201 11264 I jxcore-log: 
,03-21 13:04:36.540 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.540 11201 11264 I jxcore-log: 
03-21 13:04:36.540 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.540 11201 11264 I jxcore-log: 
,03-21 13:04:36.540 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.540 11201 11264 I jxcore-log: 
,03-21 13:04:36.540 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.540 11201 11264 I jxcore-log: 
03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.545 11201 11264 I jxcore-log: 
,03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.545 11201 11264 I jxcore-log: 
03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.545 11201 11264 I jxcore-log: 
,03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.545 11201 11264 I jxcore-log: 
,03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.545 11201 11264 I jxcore-log: 
03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.545 11201 11264 I jxcore-log: 
,03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.545 11201 11264 I jxcore-log: 
03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
,03-21 13:04:36.545 11201 11264 I jxcore-log: 
03-21 13:04:36.545 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.545 11201 11264 I jxcore-log: 
,03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
,03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
,03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.550 11201 11264 I jxcore-log: 
,03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
,03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
,03-21 13:04:36.550 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:36.550 11201 11264 I jxcore-log: 
,03-21 13:04:36.555 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:36.555 11201 11264 I jxcore-log: 
,03-21 13:04:36.555 11201 11264 I jxcore-log: ok 28 native server is nulled out
03-21 13:04:36.555 11201 11264 I jxcore-log: 
,03-21 13:04:36.555 11201 11264 I jxcore-log: ok 29 native server should be closed
03-21 13:04:36.555 11201 11264 I jxcore-log: 
03-21 13:04:36.555 11201 11264 I jxcore-log: ok 30 incoming has been removed
03-21 13:04:36.555 11201 11264 I jxcore-log: 
,03-21 13:04:36.555 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.555 11201 11264 I jxcore-log: 
03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
,03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
,03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
,03-21 13:04:36.560 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:36.560 11201 11264 I jxcore-log: 
,03-21 13:04:36.655 11201 11264 I jxcore-log: # setup
03-21 13:04:36.655 11201 11264 I jxcore-log: 
,03-21 13:04:36.725 11201 11264 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-21 13:04:36.725 11201 11264 I jxcore-log: 
,03-21 13:04:36.900 11201 11264 I jxcore-log: # teardown
03-21 13:04:36.900 11201 11264 I jxcore-log: 
,03-21 13:04:37.010 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:37.010 11201 11264 I jxcore-log: 
,03-21 13:04:37.015 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 44947
03-21 13:04:37.015 11201 11264 I jxcore-log: 
,03-21 13:04:37.025 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:37.025 11201 11264 I jxcore-log: 
,03-21 13:04:37.025 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:37.025 11201 11264 I jxcore-log: 
,03-21 13:04:37.030 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:37.030 11201 11264 I jxcore-log: 
,03-21 13:04:37.050 11201 11264 I jxcore-log: ok 31 we should not have gotten an error
03-21 13:04:37.050 11201 11264 I jxcore-log: 
,03-21 13:04:37.055 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:37.055 11201 11264 I jxcore-log: 
,03-21 13:04:37.060 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:37.060 11201 11264 I jxcore-log: 
,03-21 13:04:37.075 11201 11264 I jxcore-log: ok 32 Buffers are identical
03-21 13:04:37.075 11201 11264 I jxcore-log: 
,03-21 13:04:37.075 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:37.075 11201 11264 I jxcore-log: 
,03-21 13:04:37.080 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:37.080 11201 11264 I jxcore-log: 
,03-21 13:04:37.100 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:37.100 11201 11264 I jxcore-log: 
,03-21 13:04:37.100 11201 11264 I jxcore-log: ok 33 server should be fine
03-21 13:04:37.100 11201 11264 I jxcore-log: 
,03-21 13:04:37.105 11201 11264 I jxcore-log: ok 34 server should be open
03-21 13:04:37.105 11201 11264 I jxcore-log: 
,03-21 13:04:37.105 11201 11264 I jxcore-log: ok 35 incoming has been removed
03-21 13:04:37.105 11201 11264 I jxcore-log: 
,03-21 13:04:37.105 11201 11264 I jxcore-log: ok 36 The mux object should be closed
03-21 13:04:37.105 11201 11264 I jxcore-log: 
,03-21 13:04:37.110 11201 11264 I jxcore-log: ok 37 The mux stream should be closed
03-21 13:04:37.110 11201 11264 I jxcore-log: 
,03-21 13:04:37.115 11201 11264 I jxcore-log: # setup
03-21 13:04:37.115 11201 11264 I jxcore-log: 
,03-21 13:04:37.175 11201 11264 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-21 13:04:37.175 11201 11264 I jxcore-log: 
,03-21 13:04:37.320 11201 11264 I jxcore-log: # teardown
03-21 13:04:37.320 11201 11264 I jxcore-log: 
,03-21 13:04:37.425 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server,
03-21 13:04:37.425 11201 11264 I jxcore-log: 
,03-21 13:04:37.435 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 52347
03-21 13:04:37.435 11201 11264 I jxcore-log: 
,03-21 13:04:37.445 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:04:37.445 11201 11264 I jxcore-log: 
,03-21 13:04:37.450 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:04:37.450 11201 11264 I jxcore-log: 
,03-21 13:04:37.455 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:04:37.455 11201 11264 I jxcore-log: 
,03-21 13:04:37.465 11201 11264 I jxcore-log: ok 38 we should not have gotten an error
03-21 13:04:37.465 11201 11264 I jxcore-log: 
,03-21 13:04:37.470 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:04:37.470 11201 11264 I jxcore-log: 
,03-21 13:04:37.470 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:04:37.470 11201 11264 I jxcore-log: 
,03-21 13:04:37.485 11201 11264 I jxcore-log: ok 39 Buffers are identical
03-21 13:04:37.485 11201 11264 I jxcore-log: 
,03-21 13:04:37.490 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-21 13:04:37.490 11201 11264 I jxcore-log: 
,03-21 13:04:37.490 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:04:37.490 11201 11264 I jxcore-log: 
,03-21 13:04:37.495 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:04:37.495 11201 11264 I jxcore-log: 
,03-21 13:04:37.500 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:04:37.500 11201 11264 I jxcore-log: 
,03-21 13:04:37.500 11201 11264 I jxcore-log: ok 40 server should be fine
03-21 13:04:37.500 11201 11264 I jxcore-log: 
,03-21 13:04:37.500 11201 11264 I jxcore-log: ok 41 server should be open
03-21 13:04:37.500 11201 11264 I jxcore-log: 
03-21 13:04:37.500 11201 11264 I jxcore-log: ok 42 incoming has been removed
03-21 13:04:37.500 11201 11264 I jxcore-log: 
,03-21 13:04:37.500 11201 11264 I jxcore-log: ok 43 The mux object should be closed
03-21 13:04:37.500 11201 11264 I jxcore-log: 
,03-21 13:04:37.505 11201 11264 I jxcore-log: ok 44 The mux stream should be closed
03-21 13:04:37.505 11201 11264 I jxcore-log: 
,03-21 13:04:37.510 11201 11264 I jxcore-log: # setup
03-21 13:04:37.510 11201 11264 I jxcore-log: 
,03-21 13:04:37.630 11201 11264 I jxcore-log: # 12. closeAll can close even when connections open
03-21 13:04:37.630 11201 11264 I jxcore-log: 
,03-21 13:04:37.770 11201 11264 I jxcore-log: # teardown
03-21 13:04:37.770 11201 11264 I jxcore-log: 
,03-21 13:04:37.910 11201 11264 I jxcore-log: ok 45 not possible to connect to the server anymore
03-21 13:04:37.910 11201 11264 I jxcore-log: 
,03-21 13:04:37.920 11201 11264 I jxcore-log: # setup
03-21 13:04:37.920 11201 11264 I jxcore-log: 
,03-21 13:04:38.080 11201 11264 I jxcore-log: # 13. closeAll with promise
03-21 13:04:38.080 11201 11264 I jxcore-log: 
,03-21 13:04:38.165  3369  3387 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:04:38.170  3369  3387 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:04:38.170  3369  3387 D BatteryService: online:4, current avg:-13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
03-21 13:04:38.170  3369  3387 D BatteryService: stay LED for fully charged
03-21 13:04:38.170  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:04:38.170  3369  3369 I MotionRecognitionService: Plugged
03-21 13:04:38.170  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:04:38.170  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:04:38.170  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:04:38.175  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:04:38.175  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:04:38.175  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:04:38.180  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 13:04:38.180  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:04:38.195 11201 11264 I jxcore-log: # teardown
03-21 13:04:38.195 11201 11264 I jxcore-log: 
,03-21 13:04:38.195  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:04:38.195  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:38.195  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:38.195  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:04:38.365 11201 11264 I jxcore-log: ok 46 not possible to connect to the server anymore
03-21 13:04:38.365 11201 11264 I jxcore-log: 
,03-21 13:04:38.370 11201 11264 I jxcore-log: # setup
03-21 13:04:38.370 11201 11264 I jxcore-log: 
,03-21 13:04:38.515 11201 11264 I jxcore-log: # 14. multiplex can send data
03-21 13:04:38.515 11201 11264 I jxcore-log: 
,03-21 13:04:38.665 11201 11264 I jxcore-log: # teardown
03-21 13:04:38.665 11201 11264 I jxcore-log: 
,03-21 13:04:38.810 11201 11264 I jxcore-log: ok 47 String should be length:200
03-21 13:04:38.810 11201 11264 I jxcore-log: 
,03-21 13:04:38.820 11201 11264 I jxcore-log: # setup
03-21 13:04:38.820 11201 11264 I jxcore-log: 
,03-21 13:04:38.930  3369  3582 I PowerManagerService: [PWL] Off : 140s ago
,03-21 13:04:38.945 11201 11264 I jxcore-log: # 15. enqueue and run in order
03-21 13:04:38.945 11201 11264 I jxcore-log: 
,03-21 13:04:39.030 11201 11264 I jxcore-log: # teardown
03-21 13:04:39.030 11201 11264 I jxcore-log: 
,03-21 13:04:39.185  3369  6063 D SSRM:n  : SIOP:: AP = 300, PST = 280 (W:10), CUR = -13, LCD = 0
,03-21 13:04:39.245 11201 11264 I jxcore-log: ok 48 firstPromise setTimeout
03-21 13:04:39.245 11201 11264 I jxcore-log: 
,03-21 13:04:39.245 11201 11264 I jxcore-log: ok 49 firstPromise result
03-21 13:04:39.245 11201 11264 I jxcore-log: 
,03-21 13:04:39.250 11201 11264 I jxcore-log: ok 50 firstPromise testValue
03-21 13:04:39.250 11201 11264 I jxcore-log: 
,03-21 13:04:39.355 11201 11264 I jxcore-log: ok 51 secondPromise setTimeout
03-21 13:04:39.355 11201 11264 I jxcore-log: 
,03-21 13:04:39.365 11201 11264 I jxcore-log: ok 52 secondPromise result
03-21 13:04:39.365 11201 11264 I jxcore-log: 
,03-21 13:04:39.375 11201 11264 I jxcore-log: ok 53 secondPromise testValue
03-21 13:04:39.375 11201 11264 I jxcore-log: 
,03-21 13:04:39.380 11201 11264 I jxcore-log: ok 54 thirdPromise in promise
03-21 13:04:39.380 11201 11264 I jxcore-log: 
,03-21 13:04:39.385 11201 11264 I jxcore-log: ok 55 thirdPromise result
03-21 13:04:39.385 11201 11264 I jxcore-log: 
,03-21 13:04:39.390 11201 11264 I jxcore-log: ok 56 thirdPromise testValue
03-21 13:04:39.390 11201 11264 I jxcore-log: 
,03-21 13:04:39.400 11201 11264 I jxcore-log: # setup
03-21 13:04:39.400 11201 11264 I jxcore-log: 
,03-21 13:04:39.520 11201 11264 I jxcore-log: # 16. enqueueAtTop and run backwards
03-21 13:04:39.520 11201 11264 I jxcore-log: 
,03-21 13:04:39.670 11201 11264 I jxcore-log: # teardown
03-21 13:04:39.670 11201 11264 I jxcore-log: 
,03-21 13:04:40.245 11201 11264 I jxcore-log: ok 57 thirdPromise - first to run
03-21 13:04:40.245 11201 11264 I jxcore-log: 
,03-21 13:04:40.250 11201 11264 I jxcore-log: ok 58 thirdPromise - in resolve
03-21 13:04:40.250 11201 11264 I jxcore-log: 
,03-21 13:04:40.255 11201 11264 I jxcore-log: ok 59 secondPromise - second to run
03-21 13:04:40.255 11201 11264 I jxcore-log: 
,03-21 13:04:40.255 11201 11264 I jxcore-log: ok 60 secondPromise - in catch
03-21 13:04:40.255 11201 11264 I jxcore-log: 
,03-21 13:04:40.260 11201 11264 I jxcore-log: ok 61 firstPromise - third to run
03-21 13:04:40.260 11201 11264 I jxcore-log: 
,03-21 13:04:40.260 11201 11264 I jxcore-log: ok 62 firstPromise - in then
03-21 13:04:40.260 11201 11264 I jxcore-log: 
,03-21 13:04:40.265 11201 11264 I jxcore-log: ok 63 testing promises
03-21 13:04:40.265 11201 11264 I jxcore-log: 
,03-21 13:04:40.270 11201 11264 I jxcore-log: # setup
03-21 13:04:40.270 11201 11264 I jxcore-log: 
,03-21 13:04:40.575 11201 11264 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-21 13:04:40.575 11201 11264 I jxcore-log: 
,03-21 13:04:40.750 11201 11264 I jxcore-log: # teardown
03-21 13:04:40.750 11201 11264 I jxcore-log: 
,03-21 13:04:40.970 11201 11264 I jxcore-log: ok 64 fourth
03-21 13:04:40.970 11201 11264 I jxcore-log: 
,03-21 13:04:40.970 11201 11264 I jxcore-log: ok 65 fourth
03-21 13:04:40.970 11201 11264 I jxcore-log: 
,03-21 13:04:40.975 11201 11264 I jxcore-log: ok 66 second
03-21 13:04:40.975 11201 11264 I jxcore-log: 
,03-21 13:04:40.980 11201 11264 I jxcore-log: ok 67 secondPromise - in then
03-21 13:04:40.980 11201 11264 I jxcore-log: 
,03-21 13:04:41.085 11201 11264 I jxcore-log: ok 68 first,
,03-21 13:04:41.085 11201 11264 I jxcore-log: 
,03-21 13:04:41.100 11201 11264 I jxcore-log: ok 69 firstPromise - in catch
03-21 13:04:41.100 11201 11264 I jxcore-log: 
,03-21 13:04:41.105 11201 11264 I jxcore-log: ok 70 third
03-21 13:04:41.105 11201 11264 I jxcore-log: 
,03-21 13:04:41.110 11201 11264 I jxcore-log: ok 71 thirdPromise - in then
03-21 13:04:41.110 11201 11264 I jxcore-log: 
,03-21 13:04:41.110 11201 11264 I jxcore-log: ok 72 testingPromises
03-21 13:04:41.110 11201 11264 I jxcore-log: 
,03-21 13:04:41.120 11201 11264 I jxcore-log: # setup
03-21 13:04:41.120 11201 11264 I jxcore-log: 
,03-21 13:04:41.180 11201 11264 I jxcore-log: # 18. queues handled independently
03-21 13:04:41.180 11201 11264 I jxcore-log: 
,03-21 13:04:41.330 11201 11264 I jxcore-log: # teardown
03-21 13:04:41.330 11201 11264 I jxcore-log: 
,03-21 13:04:41.500 11201 11264 I jxcore-log: ok 73 all short operations completed before the long resolves
03-21 13:04:41.500 11201 11264 I jxcore-log: 
,03-21 13:04:41.510 11201 11264 I jxcore-log: # setup
03-21 13:04:41.510 11201 11264 I jxcore-log: 
,03-21 13:04:41.600 11201 11264 I jxcore-log: # 19. basic
03-21 13:04:41.600 11201 11264 I jxcore-log: 
,03-21 13:04:41.715 11201 11264 I jxcore-log: # teardown
03-21 13:04:41.715 11201 11264 I jxcore-log: 
,03-21 13:04:41.855 11201 11264 I jxcore-log: ok 74 sane
03-21 13:04:41.855 11201 11264 I jxcore-log: 
,03-21 13:04:41.865 11201 11264 I jxcore-log: # setup
03-21 13:04:41.865 11201 11264 I jxcore-log: 
,03-21 13:04:41.980 11201 11264 I jxcore-log: # 20. another
03-21 13:04:41.980 11201 11264 I jxcore-log: 
,03-21 13:04:42.085 11201 11264 I jxcore-log: # teardown
03-21 13:04:42.085 11201 11264 I jxcore-log: 
,03-21 13:04:42.185 11201 11264 I jxcore-log: ok 75 sane
03-21 13:04:42.185 11201 11264 I jxcore-log: 
,03-21 13:04:42.190 11201 11264 I jxcore-log: # setup
03-21 13:04:42.190 11201 11264 I jxcore-log: 
,03-21 13:04:42.355 11201 11264 I jxcore-log: # 21. #startListeningForAdvertisements should fail if start not called
03-21 13:04:42.355 11201 11264 I jxcore-log: 
,03-21 13:04:42.485 11201 11264 I jxcore-log: # teardown
03-21 13:04:42.485 11201 11264 I jxcore-log: 
,03-21 13:04:42.605 11201 11264 I jxcore-log: ok 76 specific error should be returned
03-21 13:04:42.605 11201 11264 I jxcore-log: 
,03-21 13:04:42.605 11201 11264 I jxcore-log: # setup
03-21 13:04:42.605 11201 11264 I jxcore-log: 
,03-21 13:04:42.765 11201 11264 I jxcore-log: ok 77 error should be null
03-21 13:04:42.765 11201 11264 I jxcore-log: 
,03-21 13:04:42.770 11201 11264 I jxcore-log: ok 78 error should be null
03-21 13:04:42.770 11201 11264 I jxcore-log: 
,03-21 13:04:42.770 11201 11264 I jxcore-log: # 22. #startUpdateAdvertisingAndListening should fail if start not called
03-21 13:04:42.770 11201 11264 I jxcore-log: 
,03-21 13:04:42.870 11201 11264 I jxcore-log: # teardown
03-21 13:04:42.870 11201 11264 I jxcore-log: 
,03-21 13:04:42.930  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 13:04:42.960 11201 11264 I jxcore-log: ok 79 specific error should be returned
03-21 13:04:42.960 11201 11264 I jxcore-log: 
,03-21 13:04:42.965 11201 11264 I jxcore-log: # setup
03-21 13:04:42.965 11201 11264 I jxcore-log: 
,03-21 13:04:43.085 11201 11264 I jxcore-log: ok 80 error should be null
03-21 13:04:43.085 11201 11264 I jxcore-log: 
,03-21 13:04:43.085 11201 11264 I jxcore-log: ok 81 error should be null
03-21 13:04:43.085 11201 11264 I jxcore-log: 
,03-21 13:04:43.090 11201 11264 I jxcore-log: # 23. should be able to call #stopListeningForAdvertisements many times
03-21 13:04:43.090 11201 11264 I jxcore-log: 
,03-21 13:04:43.170 11201 11264 I jxcore-log: # teardown
03-21 13:04:43.170 11201 11264 I jxcore-log: 
,03-21 13:04:43.375 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:43.375 11201 11264 I jxcore-log: 
,03-21 13:04:43.375 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 53300
03-21 13:04:43.375 11201 11264 I jxcore-log: 
,03-21 13:04:43.385 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:04:43.385 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:04:43.385 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:43.395 11201 11264 I jxcore-log: ok 82 error should be null
03-21 13:04:43.395 11201 11264 I jxcore-log: 
,03-21 13:04:43.395 11201 11264 I jxcore-log: ok 83 error should be null
03-21 13:04:43.395 11201 11264 I jxcore-log: 
,03-21 13:04:43.400 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:04:43.400 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:04:43.400 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:43.405 11201 11264 I jxcore-log: ok 84 error should be null
03-21 13:04:43.405 11201 11264 I jxcore-log: 
,03-21 13:04:43.405 11201 11264 I jxcore-log: ok 85 error should be null
03-21 13:04:43.405 11201 11264 I jxcore-log: 
,03-21 13:04:43.415 11201 11264 I jxcore-log: # setup
03-21 13:04:43.415 11201 11264 I jxcore-log: 
,03-21 13:04:44.115 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:04:44.115 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:04:44.120 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:44.125 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:04:44.125 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:04:44.125 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:44.140 11201 11264 I jxcore-log: ok 86 error should be null
03-21 13:04:44.140 11201 11264 I jxcore-log: 
,03-21 13:04:44.140 11201 11264 I jxcore-log: ok 87 error should be null
03-21 13:04:44.140 11201 11264 I jxcore-log: 
,03-21 13:04:44.150 11201 11264 I jxcore-log: # 24. should be able to call #startListeningForAdvertisements many times
03-21 13:04:44.150 11201 11264 I jxcore-log: 
,03-21 13:04:44.735 11201 11264 I jxcore-log: # teardown
03-21 13:04:44.735 11201 11264 I jxcore-log: 
,03-21 13:04:46.220 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:46.220 11201 11264 I jxcore-log: 
,03-21 13:04:46.225 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 59921
03-21 13:04:46.225 11201 11264 I jxcore-log: 
,03-21 13:04:46.240 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-21 13:04:46.240 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:04:46.240 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:04:46.240 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 13:04:46.240 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:04:46.240 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:04:46.250 11201 11264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:04:46.260 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 13:04:46.265 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 13:04:46.270 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:04:46.270 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:04:46.270 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:04:46.280  5877  9150 D BtGatt.GattService: registerClient() - UUID=79484f68-a17e-49bf-b0cf-2413ae7f0fa8
,03-21 13:04:46.325  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=79484f68-a17e-49bf-b0cf-2413ae7f0fa8, clientIf=6
,03-21 13:04:46.325 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:04:46.325  5877  5976 D BtGatt.GattService: start scan with filters
,03-21 13:04:46.340  5877  5976 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.android.bluetooth/shared_prefs/LESC.xml.bak
03-21 13:04:46.340  5877  5976 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 1
,03-21 13:04:46.345  5877  5976 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.android.bluetooth/shared_prefs/LESC_LAST_DATE.xml.bak
,03-21 13:04:46.350 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:04:46.350 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:04:46.350  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:04:46.350  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:04:46.350 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:04:46.350 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:04:46.350  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:04:46.350 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:04:46.350 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:04:46.350 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 13:04:46.350  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:04:46.350  5877  5973 D BluetoothAdapter: setting StandAloneBleMode,
,03-21 13:04:46.355  5877  5973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d6f115c
,03-21 13:04:46.355 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:04:46.355 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 13:04:46.355 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:04:46.355 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:04:46.355 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:04:46.355 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:04:46.370  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 13:04:46.370  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:46.370  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:04:46.370  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:04:46.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:04:46.370 11201 11264 I jxcore-log: 
,03-21 13:04:46.370  5877  5973 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-21 13:04:46.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:04:46.370 11201 11264 I jxcore-log: 
,03-21 13:04:46.370  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:04:46.370  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:46.375  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:04:46.375  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:04:46.375 11201 11264 I jxcore-log: ok 88 error should be null
03-21 13:04:46.375 11201 11264 I jxcore-log: 
,03-21 13:04:46.375 11201 11264 I jxcore-log: ok 89 error should be null
03-21 13:04:46.375 11201 11264 I jxcore-log: 
,03-21 13:04:46.375  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:04:46.375  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:46.380  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 13:04:46.380  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:46.385 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-21 13:04:46.385 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:04:46.385 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:04:46.385 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:04:46.385 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:04:46.390 11201 11264 I jxcore-log: ok 90 error should be null
03-21 13:04:46.390 11201 11264 I jxcore-log: 
,03-21 13:04:46.390 11201 11264 I jxcore-log: ok 91 error should be null
03-21 13:04:46.390 11201 11264 I jxcore-log: 
,03-21 13:04:46.400 11201 11264 I jxcore-log: # setup
03-21 13:04:46.400 11201 11264 I jxcore-log: 
,03-21 13:04:46.560 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:04:46.560 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:04:46.565 11201 11264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 13:04:46.565 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 13:04:46.565 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 13:04:46.565 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-21 13:04:46.565 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 13:04:46.565 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 13:04:46.570 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:04:46.570  5877  8684 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:04:46.575  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:04:46.575  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 3
03-21 13:04:46.575  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:04:46.575  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:46.575  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:04:46.580  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 13:04:46.580  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:46.580  5877  5888 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 13:04:46.585  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:04:46.585  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:04:46.585  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:46.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 13:04:46.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:04:46.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 13:04:46.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 13:04:46.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 13:04:46.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 13:04:46.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 13:04:46.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:04:46.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 13:04:46.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-21 13:04:46.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:04:46.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-21 13:04:46.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:04:46.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:04:46.605 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:04:46.605 11201 11264 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 13:04:46.605 11201 11264 I jxcore-log: 
,03-21 13:04:46.610 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 13:04:46.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 13:04:46.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:04:46.615 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 13:04:46.615 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:04:46.615 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:04:46.615 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:04:46.620 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 13:04:46.620 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:04:46.620 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:46.620 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:04:46.620 11201 11264 I jxcore-log: 
,03-21 13:04:46.620 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:04:46.620 11201 11264 I jxcore-log: 
,03-21 13:04:46.625 11201 11264 I jxcore-log: ok 92 error should be null
03-21 13:04:46.625 11201 11264 I jxcore-log: 
,03-21 13:04:46.625 11201 11264 I jxcore-log: ok 93 error should be null
03-21 13:04:46.625 11201 11264 I jxcore-log: 
,03-21 13:04:46.630 11201 11264 I jxcore-log: # 25. should be able to call #startUpdateAdvertisingAndListening many times
03-21 13:04:46.630 11201 11264 I jxcore-log: 
,03-21 13:04:46.955 11201 11264 I jxcore-log: # teardown
03-21 13:04:46.955 11201 11264 I jxcore-log: 
,03-21 13:04:47.125 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:47.125 11201 11264 I jxcore-log: 
,03-21 13:04:47.130 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 56305
03-21 13:04:47.130 11201 11264 I jxcore-log: 
,03-21 13:04:47.150 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 56305, start advertisements: true
03-21 13:04:47.150 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:04:47.150 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 13:04:47.150 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:04:47.155 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-21 13:04:47.155 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:04:47.155 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:04:47.155 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:04:47.160  5877  5888 D BtGatt.GattService: registerClient() - UUID=b62d271b-fc23-4e19-9e24-67f007853618
,03-21 13:04:47.200  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=b62d271b-fc23-4e19-9e24-67f007853618, clientIf=6
,03-21 13:04:47.200 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:04:47.200  5877  5890 D BtGatt.GattService: start scan with filters
,03-21 13:04:47.215  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 2
,03-21 13:04:47.215  5877  5973 D BtGatt.ScanManager: handling starting scan
,03-21 13:04:47.215  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:04:47.215  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:04:47.220 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 13:04:47.220 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:04:47.220 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:04:47.220 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-21 13:04:47.220 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:04:47.220 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:04:47.220 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 13:04:47.220 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 13:04:47.225 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 13:04:47.225 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:04:47.225  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 13:04:47.225  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:47.225 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:04:47.225 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:04:47.225  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:04:47.225  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:04:47.225  5877  5973 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,03-21 13:04:47.230  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:04:47.230  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:47.230  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:04:47.230  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:04:47.235  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 13:04:47.235  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:47.235  5877  5888 D BtGatt.GattService: registerClient() - UUID=2eaf03bd-d249-4b28-90a4-a7fee64727ec
,03-21 13:04:47.235  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:04:47.235  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:47.275  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=2eaf03bd-d249-4b28-90a4-a7fee64727ec, clientIf=7,
03-21 13:04:47.280 11201 11211 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:04:47.300  5877  5890 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.android.bluetooth/shared_prefs/LEAV.xml.bak
,03-21 13:04:47.300  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 1
,03-21 13:04:47.305  5877  5890 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.android.bluetooth/shared_prefs/LEAV_LAST_DATE.xml.bak
,03-21 13:04:47.310  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:04:47.310  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:04:47.310  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:04:47.315  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:04:47.315  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:04:47.320  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:04:47.320  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:04:47.325  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:04:47.325  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 13:04:47.325  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:04:47.325 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:04:47.325 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 13:04:47.330 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:04:47.330 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:04:47.330 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-21 13:04:47.335 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 13:04:47.335 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 13:04:47.335 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-21 13:04:47.340 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 13:04:47.340 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-21 13:04:47.340 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:04:47.340 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:04:47.340 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:04:47.340 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:04:47.340 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:04:47.340 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:04:47.340 11201 11201 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:04:47.340 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:04:47.340 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:04:47.340 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:04:47.340 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 13:04:47.340 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 13:04:47.340 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:04:47.355 11201 11494 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:04:47.355 11201 11494 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 13:04:47.365 11201 11494 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[120]}
03-21 13:04:47.365 11201 11494 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:04:47.365 11201 11494 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:04:47.365 11201 11494 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b93cd9f
03-21 13:04:47.365 11201 11494 D BluetoothSocket: channel: 6
03-21 13:04:47.365 11201 11494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 13:04:47.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:04:47.370 11201 11264 I jxcore-log: 
03-21 13:04:47.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:04:47.370 11201 11264 I jxcore-log: 
03-21 13:04:47.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:04:47.370 11201 11264 I jxcore-log: 
03-21 13:04:47.375 11201 11264 I jxcore-log: ok 94 error should be null
03-21 13:04:47.375 11201 11264 I jxcore-log: 
03-21 13:04:47.375 11201 11264 I jxcore-log: ok 95 error should be null
03-21 13:04:47.375 11201 11264 I jxcore-log: 
,03-21 13:04:47.380 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 56305, start advertisements: true
,03-21 13:04:47.380 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:04:47.380 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:04:47.380 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:04:47.380 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:04:47.395 11201 11264 I jxcore-log: ok 96 error should be null
03-21 13:04:47.395 11201 11264 I jxcore-log: 
,03-21 13:04:47.395 11201 11264 I jxcore-log: ok 97 error should be null
03-21 13:04:47.395 11201 11264 I jxcore-log: 
,03-21 13:04:47.400 11201 11264 I jxcore-log: # setup
03-21 13:04:47.400 11201 11264 I jxcore-log: 
,03-21 13:04:48.240  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:04:48.245  5877  5877 D BtGatt.ScanManager: awakened up at time 215307
03-21 13:04:48.250  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:04:48.255  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:04:48.255  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:48.255  5877  5968 D BtGatt.GattService: current time is 215319294649,
03-21 13:04:48.255  5877  5968 D BtGatt.GattService: Batch record : [-109, 8, -122, -81, -46, 87, 1, -128, -66, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-21 13:04:48.285  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:04:48.285  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:04:48.290  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=57:D2:AF:86:08:93, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-66, mTimestampNanos=215069789107}
03-21 13:04:48.290  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:04:48.290 11201 11211 D ScanRecord: parseFromBytes
,03-21 13:04:48.300 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 13:04:48.300 11201 11201 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 13:04:48.305 11201 11264 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-21 13:04:48.305 11201 11264 I jxcore-log: 
,03-21 13:04:48.315 11201 11264 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-21 13:04:48.315 11201 11264 I jxcore-log: 
,03-21 13:04:48.360  3369  3386 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:04:48.360  3369  3386 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:04:48.360  3369  3386 D BatteryService: online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:85
03-21 13:04:48.360  3369  3386 D BatteryService: stay LED for fully charged
03-21 13:04:48.360  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:04:48.360  3369  3369 I MotionRecognitionService: Plugged
03-21 13:04:48.360  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:04:48.360  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:04:48.360  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:04:48.365  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:04:48.365  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:04:48.365  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:04:48.370  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:04:48.370  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 13:04:48.370  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:04:48.385  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:04:48.385  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:48.385  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:04:48.470 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:04:48.470 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-21 13:04:48.470 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 13:04:48.475 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 13:04:48.475 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 13:04:48.475 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9cb12b5, channel: 6, state: LISTENING
,03-21 13:04:48.480 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9cb12b5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b93cd9f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38284d4amSocket: android.net.LocalSocket@1f1a4bb impl:android.net.LocalSocketImpl@17b64dd8 fd:FileDescriptor[120]
,03-21 13:04:48.480 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f1a4bb impl:android.net.LocalSocketImpl@17b64dd8 fd:FileDescriptor[120]
,03-21 13:04:48.480 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 13:04:48.485 11201 11494 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:04:48.485 11201 11494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 13:04:48.485 11201 11494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:04:48.485 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:04:48.485 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 13:04:48.485 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:04:48.485 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 13:04:48.485 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 13:04:48.485 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:04:48.485 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:04:48.485 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-21 13:04:48.485 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:04:48.490  5877  9150 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:04:48.490  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:04:48.490  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 4
03-21 13:04:48.495  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:04:48.495  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:48.495  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:04:48.495  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 13:04:48.495  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:48.495  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:04:48.500  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:04:48.500  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:48.500  5877  5968 D BtGatt.GattService: current time is 215561990399
03-21 13:04:48.500  5877  5968 D BtGatt.GattService: Batch record : [-109, 8, -122, -81, -46, 87, 1, -128, -71, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:04:48.500  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-21 13:04:48.500  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:04:48.505  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 13:04:48.505 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-21 13:04:48.505 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-21 13:04:48.505 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,03-21 13:04:48.505 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 13:04:48.505 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
,03-21 13:04:48.505 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:04:48.505 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-21 13:04:48.510  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:04:48.510  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:04:48.510  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 13:04:48.515  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:04:48.515  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:04:48.515  5877  5968 D BtGatt.GattService: Client app is not null!,
,03-21 13:04:48.515  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:04:48.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 13:04:48.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:04:48.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:04:48.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-21 13:04:48.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:04:48.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:04:48.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,03-21 13:04:48.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-21 13:04:48.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-21 13:04:48.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear,
03-21 13:04:48.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:04:48.520 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-21 13:04:48.520 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-21 13:04:48.520 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:04:48.520 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-21 13:04:48.520 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 13:04:48.525 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-21 13:04:48.530 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:04:48.530 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 13:04:48.530 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:04:48.535 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:04:48.535 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-21 13:04:48.535 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:04:48.540 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 13:04:48.540 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:04:48.545 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:04:48.555 11201 11264 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 13:04:48.555 11201 11264 I jxcore-log: 
03-21 13:04:48.555 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:04:48.555 11201 11264 I jxcore-log: 
,03-21 13:04:48.555 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-21 13:04:48.555 11201 11264 I jxcore-log: 
,03-21 13:04:48.560 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:04:48.560 11201 11264 I jxcore-log: 
,03-21 13:04:48.565 11201 11264 I jxcore-log: ok 98 error should be null
03-21 13:04:48.565 11201 11264 I jxcore-log: 
,03-21 13:04:48.565 11201 11264 I jxcore-log: ok 99 error should be null
03-21 13:04:48.565 11201 11264 I jxcore-log: 
,03-21 13:04:48.570 11201 11264 I jxcore-log: # 26. should be able to call #stopAdvertisingAndListening many times
03-21 13:04:48.570 11201 11264 I jxcore-log: 
,03-21 13:04:49.215  3369  6063 D SSRM:n  : SIOP:: AP = 290, PST = 281 (W:10), CUR = 43, LCD = 0
,03-21 13:04:55.655  3369  3866 E Watchdog: !@Sync 7 [03-21 13:04:55.659]
,03-21 13:04:56.185 11201 11264 I jxcore-log: # teardown
03-21 13:04:56.185 11201 11264 I jxcore-log: 
,03-21 13:04:56.350 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:56.350 11201 11264 I jxcore-log: 
,03-21 13:04:56.360 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 47579
03-21 13:04:56.360 11201 11264 I jxcore-log: 
,03-21 13:04:56.365 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:04:56.365 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:04:56.365 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:56.370 11201 11264 I jxcore-log: ok 100 error should be null
03-21 13:04:56.370 11201 11264 I jxcore-log: 
,03-21 13:04:56.375 11201 11264 I jxcore-log: ok 101 error should be null
03-21 13:04:56.375 11201 11264 I jxcore-log: 
,03-21 13:04:56.375 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:04:56.375 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:04:56.375 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:56.380 11201 11264 I jxcore-log: ok 102 error should be null
03-21 13:04:56.380 11201 11264 I jxcore-log: 
,03-21 13:04:56.385 11201 11264 I jxcore-log: ok 103 error should be null
03-21 13:04:56.385 11201 11264 I jxcore-log: 
,03-21 13:04:56.390 11201 11264 I jxcore-log: # setup
03-21 13:04:56.390 11201 11264 I jxcore-log: 
,03-21 13:04:56.835 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:04:56.835 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:04:56.835 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:56.840 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:04:56.840 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:04:56.840 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:56.850 11201 11264 I jxcore-log: ok 104 error should be null
03-21 13:04:56.850 11201 11264 I jxcore-log: 
,03-21 13:04:56.855 11201 11264 I jxcore-log: ok 105 error should be null
03-21 13:04:56.855 11201 11264 I jxcore-log: 
,03-21 13:04:56.860 11201 11264 I jxcore-log: # 27. #start should fail if called twice in a row
03-21 13:04:56.860 11201 11264 I jxcore-log: 
,03-21 13:04:56.975 11201 11264 I jxcore-log: # teardown
03-21 13:04:56.975 11201 11264 I jxcore-log: 
,03-21 13:04:57.145 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:57.145 11201 11264 I jxcore-log: 
,03-21 13:04:57.150 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 46661
03-21 13:04:57.150 11201 11264 I jxcore-log: 
,03-21 13:04:57.155 11201 11264 I jxcore-log: ok 106 first call should succeed
03-21 13:04:57.155 11201 11264 I jxcore-log: 
,03-21 13:04:57.160 11201 11264 I jxcore-log: ok 107 first call should succeed
03-21 13:04:57.160 11201 11264 I jxcore-log: 
,03-21 13:04:57.165 11201 11264 I jxcore-log: ok 108 specific error should be returned
03-21 13:04:57.165 11201 11264 I jxcore-log: 
,03-21 13:04:57.165 11201 11264 I jxcore-log: # setup
03-21 13:04:57.165 11201 11264 I jxcore-log: 
,03-21 13:04:57.280 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:04:57.285 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:04:57.285 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:57.290 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:04:57.290 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:04:57.290 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:04:57.300 11201 11264 I jxcore-log: ok 109 error should be null
03-21 13:04:57.300 11201 11264 I jxcore-log: 
,03-21 13:04:57.300 11201 11264 I jxcore-log: ok 110 error should be null
03-21 13:04:57.300 11201 11264 I jxcore-log: 
,03-21 13:04:57.310 11201 11264 I jxcore-log: # 28. does not emit duplicate discoveryAdvertisingStateUpdate
03-21 13:04:57.310 11201 11264 I jxcore-log: 
,03-21 13:04:57.360 11201 11264 I jxcore-log: # teardown
03-21 13:04:57.360 11201 11264 I jxcore-log: 
,03-21 13:04:57.550 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:04:57.550 11201 11264 I jxcore-log: 
,03-21 13:04:57.555 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 57927
03-21 13:04:57.555 11201 11264 I jxcore-log: 
,03-21 13:04:57.565 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 56305, start advertisements: false
,03-21 13:04:57.565 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:04:57.565 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 13:04:57.565 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 13:04:57.570 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:04:57.570 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:04:57.570 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:04:57.575  5877  5888 D BtGatt.GattService: registerClient() - UUID=87fe898f-79c4-4dc8-8025-46ad454e0424
,03-21 13:04:57.620  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=87fe898f-79c4-4dc8-8025-46ad454e0424, clientIf=6
,03-21 13:04:57.620 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,03-21 13:04:57.630  5877  5890 D BtGatt.GattService: start scan with filters,
,03-21 13:04:57.645  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 3
,03-21 13:04:57.650  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:04:57.650  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:04:57.650  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:04:57.660 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:04:57.660 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:04:57.660 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:04:57.660 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:04:57.660 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:04:57.660 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:04:57.660 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 13:04:57.665  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:04:57.665  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:57.665  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:04:57.665  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:04:57.665  5877  5973 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-21 13:04:57.665  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:04:57.665  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:57.665  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:04:57.665  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:04:57.670 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:04:57.670  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:04:57.670  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:57.670  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 13:04:57.670  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:04:57.675 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,03-21 13:04:57.675 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-21 13:04:57.675 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:04:57.675 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:04:57.675 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:04:57.685 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:04:57.685 11201 11264 I jxcore-log: 
,03-21 13:04:57.690 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:04:57.690 11201 11264 I jxcore-log: 
,03-21 13:04:57.700 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 57927, start advertisements: true
,03-21 13:04:57.700 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:04:57.700 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-21 13:04:57.700 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:04:57.705 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:04:57.705 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-21 13:04:57.705 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 13:04:57.705 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:04:57.705 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 13:04:57.705 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 13:04:57.710 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:04:57.710 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:04:57.710  5877  5976 D BtGatt.GattService: registerClient() - UUID=a189d79c-5322-4860-8bdf-85965a3609bd
,03-21 13:04:57.755  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=a189d79c-5322-4860-8bdf-85965a3609bd, clientIf=7
,03-21 13:04:57.755 11201 11211 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:04:57.765  5877  8684 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 2
,03-21 13:04:57.765  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:04:57.765  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:04:57.765  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:04:57.765  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:04:57.765  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:04:57.770  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:04:57.770  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:04:57.770  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:04:57.770  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:04:57.770  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 13:04:57.770 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-21 13:04:57.770 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:04:57.770 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:04:57.770 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:04:57.770 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:04:57.775 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:04:57.775 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 13:04:57.775 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:04:57.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 13:04:57.775 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 13:04:57.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:04:57.775 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:04:57.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 13:04:57.775 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 13:04:57.775 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 13:04:57.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-21 13:04:57.775 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:04:57.775 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 13:04:57.775 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:04:57.775 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 13:04:57.780 11201 11537 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:04:57.780 11201 11537 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:04:57.780 11201 11537 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,03-21 13:04:57.780 11201 11537 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:04:57.780 11201 11537 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:04:57.780 11201 11537 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d2e6f84
03-21 13:04:57.780 11201 11537 D BluetoothSocket: channel: 6
03-21 13:04:57.780 11201 11537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:04:57.785 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:04:57.785 11201 11264 I jxcore-log: 
,03-21 13:04:57.790 11201 11264 I jxcore-log: ok 111 called only once
03-21 13:04:57.790 11201 11264 I jxcore-log: 
,03-21 13:04:57.795 11201 11264 I jxcore-log: ok 112 discovery state matches
03-21 13:04:57.795 11201 11264 I jxcore-log: 
,03-21 13:04:57.795 11201 11264 I jxcore-log: ok 113 advertising state matches
03-21 13:04:57.795 11201 11264 I jxcore-log: 
,03-21 13:04:57.800 11201 11264 I jxcore-log: # setup
03-21 13:04:57.800 11201 11264 I jxcore-log: 
,03-21 13:04:58.010 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 13:04:58.010 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 13:04:58.010 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 13:04:58.010 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 13:04:58.010 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 13:04:58.010 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36d7e36d, channel: 6, state: LISTENING
03-21 13:04:58.010 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36d7e36d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d2e6f84, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34853ba2mSocket: android.net.LocalSocket@3631f033 impl:android.net.LocalSocketImpl@4e4fff0 fd:FileDescriptor[118]
03-21 13:04:58.010 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3631f033 impl:android.net.LocalSocketImpl@4e4fff0 fd:FileDescriptor[118]
,03-21 13:04:58.010 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-21 13:04:58.010 11201 11537 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
,03-21 13:04:58.010 11201 11537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
,03-21 13:04:58.010 11201 11537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
03-21 13:04:58.015 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 13:04:58.015 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-21 13:04:58.015 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
,03-21 13:04:58.015 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-21 13:04:58.015 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 13:04:58.015 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-21 13:04:58.015 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:04:58.015 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-21 13:04:58.015 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 13:04:58.020  5877  5888 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:04:58.020  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:04:58.020  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 5,
03-21 13:04:58.020  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:04:58.020  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 13:04:58.020  5877  5973 D BtGatt.ScanManager: stopping BLe Batch,
03-21 13:04:58.020  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:04:58.020  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 13:04:58.020  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:04:58.025  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:04:58.025 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:04:58.025 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:04:58.025 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:04:58.025 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-21 13:04:58.025 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 13:04:58.025 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:04:58.025 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 13:04:58.030  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:04:58.030  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:04:58.030  5877  5968 D BtGatt.GattService: current time is 225090298608
,03-21 13:04:58.030  5877  5968 D BtGatt.GattService: Batch record : [-77, 36, 110, -120, -40, 95, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:04:58.030  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:04:58.030  5877  5968 D ScanRecord: parseFromBytes
03-21 13:04:58.035  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:04:58.035  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-21 13:04:58.035  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:04:58.035  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:04:58.035  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:04:58.035  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:04:58.040  5877  8684 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:04:58.040 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 13:04:58.040 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:04:58.040 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:04:58.040 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:04:58.040 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-21 13:04:58.040 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:04:58.040 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:04:58.040 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:04:58.045 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:04:58.045 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:04:58.045 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,03-21 13:04:58.045 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:04:58.045 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:04:58.045 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:04:58.045 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 13:04:58.050 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 13:04:58.055 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 13:04:58.055 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:04:58.055 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:04:58.060 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:04:58.065 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:04:58.065 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:04:58.065 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:04:58.065 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:04:58.070 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:04:58.075 11201 11264 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-21 13:04:58.075 11201 11264 I jxcore-log: 
03-21 13:04:58.080 11201 11264 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 13:04:58.080 11201 11264 I jxcore-log: 
03-21 13:04:58.085 11201 11264 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 13:04:58.085 11201 11264 I jxcore-log: 
03-21 13:04:58.090 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:04:58.090 11201 11264 I jxcore-log: 
03-21 13:04:58.090 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:04:58.090 11201 11264 I jxcore-log: 
03-21 13:04:58.090 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:04:58.090 11201 11264 I jxcore-log: 
,03-21 13:04:58.095 11201 11264 I jxcore-log: ok 114 error should be null
03-21 13:04:58.095 11201 11264 I jxcore-log: 
,03-21 13:04:58.095 11201 11264 I jxcore-log: ok 115 error should be null
03-21 13:04:58.095 11201 11264 I jxcore-log: 
,03-21 13:04:58.100 11201 11264 I jxcore-log: # 29. does not send duplicate availability changes
03-21 13:04:58.100 11201 11264 I jxcore-log: 
,03-21 13:04:58.500  3369  4776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 13:04:58.500  3369  4776 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:04:58.500  3369  4776 D BatteryService: online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:72
,03-21 13:04:58.500  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:04:58.510  3369  4776 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 11ms,
03-21 13:04:58.510  3369  4776 D BatteryService: stay LED for fully charged,
,03-21 13:04:58.510  3369  3369 I MotionRecognitionService: Plugged
,03-21 13:04:58.510  3369  3369 D MotionRecognitionService:   cableConnection= 1,
,03-21 13:04:58.510  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 13:04:58.510  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:04:58.530  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 13:04:58.530  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 13:04:58.530  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:04:58.545  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 13:04:58.545  5877  5974 D HeadsetStateMachine: Disconnected process message: 10,
,03-21 13:04:58.555  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:04:58.555  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:58.555  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:04:58.555  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:04:59.005 11201 11264 I jxcore-log: # teardown
03-21 13:04:59.005 11201 11264 I jxcore-log: 
,03-21 13:04:59.130 11201 11264 I jxcore-log: ok 116 should be called once
03-21 13:04:59.130 11201 11264 I jxcore-log: 
,03-21 13:04:59.130 11201 11264 I jxcore-log: ok 117 should not have been called more than once
03-21 13:04:59.130 11201 11264 I jxcore-log: 
,03-21 13:04:59.135 11201 11264 I jxcore-log: # setup
03-21 13:04:59.135 11201 11264 I jxcore-log: 
,03-21 13:04:59.230  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:10), CUR = 61, LCD = 0
,03-21 13:04:59.465 11201 11264 I jxcore-log: ok 118 error should be null
03-21 13:04:59.465 11201 11264 I jxcore-log: 
,03-21 13:04:59.465 11201 11264 I jxcore-log: ok 119 error should be null
03-21 13:04:59.465 11201 11264 I jxcore-log: 
,03-21 13:04:59.470 11201 11264 I jxcore-log: # 30. can get the network status
03-21 13:04:59.470 11201 11264 I jxcore-log: 
,03-21 13:04:59.605 11201 11264 I jxcore-log: # teardown
03-21 13:04:59.605 11201 11264 I jxcore-log: 
,03-21 13:04:59.800 11201 11264 I jxcore-log: ok 120 network status should have certain non-empty properties
03-21 13:04:59.800 11201 11264 I jxcore-log: 
,03-21 13:04:59.805 11201 11264 I jxcore-log: # setup
03-21 13:04:59.805 11201 11264 I jxcore-log: 
,03-21 13:04:59.945 11201 11264 I jxcore-log: ok 121 error should be null
03-21 13:04:59.945 11201 11264 I jxcore-log: 
,03-21 13:04:59.945 11201 11264 I jxcore-log: ok 122 error should be null
03-21 13:04:59.945 11201 11264 I jxcore-log: 
,03-21 13:04:59.950 11201 11264 I jxcore-log: # 31. wifi peer is marked unavailable if announcements stop
03-21 13:04:59.950 11201 11264 I jxcore-log: 
,03-21 13:04:59.995  3369  3620 V AlarmManager: waitForAlarm result :8
,03-21 13:05:00.175 11201 11264 I jxcore-log: # teardown
03-21 13:05:00.175 11201 11264 I jxcore-log: 
,03-21 13:05:00.380 11201 11264 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-21 13:05:00.380 11201 11264 I jxcore-log: 
,03-21 13:05:00.420 11201 11264 I jxcore-log: ok 123 host address should match
03-21 13:05:00.420 11201 11264 I jxcore-log: 
,03-21 13:05:00.420 11201 11264 I jxcore-log: ok 124 port should match
03-21 13:05:00.420 11201 11264 I jxcore-log: 
,03-21 13:05:01.380 11201 11264 I jxcore-log: ok 125 host address should be null
03-21 13:05:01.380 11201 11264 I jxcore-log: 
,03-21 13:05:01.390 11201 11264 I jxcore-log: ok 126 port should should be null
03-21 13:05:01.390 11201 11264 I jxcore-log: 
,03-21 13:05:01.410 11201 11264 I jxcore-log: # setup
03-21 13:05:01.410 11201 11264 I jxcore-log: 
,03-21 13:05:01.555 11201 11264 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 13:05:01.555 11201 11264 I jxcore-log: 
,03-21 13:05:01.560 11201 11264 I jxcore-log: ok 127 error should be null
03-21 13:05:01.560 11201 11264 I jxcore-log: 
,03-21 13:05:01.565 11201 11264 I jxcore-log: ok 128 error should be null
03-21 13:05:01.565 11201 11264 I jxcore-log: 
,03-21 13:05:01.570 11201 11264 I jxcore-log: # 32. Can call start/stopListeningForAdvertisements
03-21 13:05:01.570 11201 11264 I jxcore-log: 
,03-21 13:05:01.770 11201 11264 I jxcore-log: # teardown
03-21 13:05:01.770 11201 11264 I jxcore-log: 
,03-21 13:05:01.890 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 57927, start advertisements: false
,03-21 13:05:01.890 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:01.895 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 13:05:01.895 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 13:05:01.900 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:01.900 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:01.900 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:01.905  5877  8684 D BtGatt.GattService: registerClient() - UUID=0d626d87-dedb-48a0-8dc5-38766701e5b1
,03-21 13:05:01.945  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=0d626d87-dedb-48a0-8dc5-38766701e5b1, clientIf=6
,03-21 13:05:01.945 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:01.950  5877  5888 D BtGatt.GattService: start scan with filters
,03-21 13:05:01.960  5877  5888 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 4
,03-21 13:05:01.960 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:01.960 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:01.960 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:01.960 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:01.960 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:01.960 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:05:01.960 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:01.960  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:01.960  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:01.960  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:01.960 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:01.960 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:01.965 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:01.965 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:01.965 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:01.965 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:01.965  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:01.965  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:01.965  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:01.965  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:01.965  5877  5973 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,03-21 13:05:01.965 11201 11264 I jxcore-log: ok 129 Can call startListeningForAdvertisements without error
03-21 13:05:01.965 11201 11264 I jxcore-log: 
,03-21 13:05:01.965  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:01.965  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:01.965  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:01.965  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:01.965 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 13:05:01.965 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:05:01.965 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 13:05:01.965 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:05:01.970  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 13:05:01.970  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:01.970  5877  5976 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:05:01.970  5877  8684 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:01.970  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:01.970  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:01.970 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:01.970 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:01.970 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:05:01.970 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 13:05:01.970 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 13:05:01.970 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 13:05:01.970 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:01.970 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:05:01.970 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 13:05:01.975 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:01.975 11201 11264 I jxcore-log: 
,03-21 13:05:01.975 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:01.975 11201 11264 I jxcore-log: 
03-21 13:05:01.975  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:01.975  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 6
03-21 13:05:01.975  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:01.975  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:01.975  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:01.980 11201 11264 I jxcore-log: ok 130 Can call stopListeningForAdvertisements without error
03-21 13:05:01.980 11201 11264 I jxcore-log: 
,03-21 13:05:01.980  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:01.980  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:01.980  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:01.980  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:01.980  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:01.985 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:01.985 11201 11264 I jxcore-log: 
,03-21 13:05:01.985 11201 11264 I jxcore-log: # setup
03-21 13:05:01.985 11201 11264 I jxcore-log: ,
,03-21 13:05:02.110 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:02.110 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:05:02.110 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:02.115 11201 11264 I jxcore-log: ok 131 Should be able to call stopListeningForAdvertisments in teardown
03-21 13:05:02.115 11201 11264 I jxcore-log: 
,03-21 13:05:02.120 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:02.120 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:02.120 11201 11264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 13:05:02.125 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 13:05:02.125 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 13:05:02.125 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:02.125 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 13:05:02.125 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 13:05:02.125 11201 11264 D BluetoothLeScanner: could not find callback wrapper,
03-21 13:05:02.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 13:05:02.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 13:05:02.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-21 13:05:02.130 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 13:05:02.135 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,03-21 13:05:02.135 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:02.135 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-21 13:05:02.135 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:02.135 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:05:02.145 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:02.150 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,03-21 13:05:02.155 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-21 13:05:02.155 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:02.160 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,03-21 13:05:02.160 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:02.160 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 13:05:02.165 11201 11264 I jxcore-log: ok 132 Should be able to call stopAdvertisingAndListening in teardown
03-21 13:05:02.165 11201 11264 I jxcore-log: 
,03-21 13:05:02.170 11201 11264 I jxcore-log: # 33. Calling startListeningForAdvertisements twice is NOT an error
03-21 13:05:02.170 11201 11264 I jxcore-log: 
,03-21 13:05:02.175 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:02.175 11201 11264 I jxcore-log: 
,03-21 13:05:02.330 11201 11264 I jxcore-log: # teardown
03-21 13:05:02.330 11201 11264 I jxcore-log: 
,03-21 13:05:02.510 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 57927, start advertisements: false
,03-21 13:05:02.510 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:02.515 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:02.515 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 13:05:02.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:02.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:02.520 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:02.525  5877  5888 D BtGatt.GattService: registerClient() - UUID=011e1e30-89f8-49e3-b081-55d888799e80
,03-21 13:05:02.565  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=011e1e30-89f8-49e3-b081-55d888799e80, clientIf=6
03-21 13:05:02.565 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:05:02.570  5877  9150 D BtGatt.GattService: start scan with filters
,03-21 13:05:02.580  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 5
,03-21 13:05:02.580  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:02.580  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:02.580  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:02.585  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:02.585  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:02.585  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:02.585  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:02.585  5877  5973 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-21 13:05:02.585  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:02.585  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:02.585  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:02.585  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:02.590  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:02.590  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:02.590  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:02.590  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:02.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:02.600 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:02.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:02.600 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:02.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:02.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:05:02.600 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 13:05:02.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:02.600 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:02.600 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:02.600 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:02.600 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:02.600 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:02.605 11201 11264 I jxcore-log: ok 133 Can call startListeningForAdvertisements without error
03-21 13:05:02.605 11201 11264 I jxcore-log: 
,03-21 13:05:02.610 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 57927, start advertisements: false
,03-21 13:05:02.610 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:02.610 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:02.610 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:05:02.610 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:02.610 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:02.610 11201 11264 I jxcore-log: 
,03-21 13:05:02.610 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:02.610 11201 11264 I jxcore-log: 
,03-21 13:05:02.615 11201 11264 I jxcore-log: ok 134 Can call startListeningForAdvertisements twice without error
03-21 13:05:02.615 11201 11264 I jxcore-log: 
,03-21 13:05:02.620 11201 11264 I jxcore-log: # setup
03-21 13:05:02.620 11201 11264 I jxcore-log: 
,03-21 13:05:02.875 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:02.880 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
,03-21 13:05:02.880 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-21 13:05:02.885 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-21 13:05:02.890  5877  5890 D BtGatt.GattService: stopScan() - queue size =1,
03-21 13:05:02.890  5877  5973 D BtGatt.ScanManager: filter size is 1
,03-21 13:05:02.890  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 7,
03-21 13:05:02.890  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 13:05:02.890  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:02.890  5877  5973 D BtGatt.ScanManager: stopping BLe Batch,
,03-21 13:05:02.895  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:02.895  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:02.895  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-21 13:05:02.895  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:02.895  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:02.900  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:02.905 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 13:05:02.905 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:02.905 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-21 13:05:02.905 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-21 13:05:02.905 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 13:05:02.905 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-21 13:05:02.905 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-21 13:05:02.910 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:05:02.910 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 13:05:02.915 11201 11264 I jxcore-log: ok 135 Should be able to call stopListeningForAdvertisments in teardown,
03-21 13:05:02.915 11201 11264 I jxcore-log: 
,03-21 13:05:02.920 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:02.920 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:02.920 11201 11264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 13:05:02.920 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 13:05:02.920 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 13:05:02.920 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:02.920 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 13:05:02.920 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 13:05:02.925 11201 11264 D BluetoothLeScanner: could not find callback wrapper,
03-21 13:05:02.925 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 13:05:02.925 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:02.925 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-21 13:05:02.925 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 13:05:02.930 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-21 13:05:02.930 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:02.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-21 13:05:02.930  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-21 13:05:02.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:02.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-21 13:05:02.935 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:02.940 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-21 13:05:02.940 11201 11264 I jxcore-log: 
,03-21 13:05:02.945 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-21 13:05:02.945 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:02.945 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:02.950 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-21 13:05:02.950 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:02.950 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-21 13:05:02.955 11201 11264 I jxcore-log: ok 136 Should be able to call stopAdvertisingAndListening in teardown
03-21 13:05:02.955 11201 11264 I jxcore-log: 
,03-21 13:05:02.970 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:02.970 11201 11264 I jxcore-log: 
,03-21 13:05:02.970 11201 11264 I jxcore-log: # 34. Can call start/stopUpdateAdvertisingAndListening
03-21 13:05:02.970 11201 11264 I jxcore-log: 
,03-21 13:05:03.130 11201 11264 I jxcore-log: # teardown
03-21 13:05:03.130 11201 11264 I jxcore-log: 
,03-21 13:05:03.340 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-21 13:05:03.340 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:03.345 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 13:05:03.345 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:03.350 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:05:03.350 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:03.350 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:03.350 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:03.355  5877  8684 D BtGatt.GattService: registerClient() - UUID=8b76a44b-83af-4747-ae73-68c7b42eac78
,03-21 13:05:03.400  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=8b76a44b-83af-4747-ae73-68c7b42eac78, clientIf=6
03-21 13:05:03.400 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:05:03.405  5877  5888 D BtGatt.GattService: start scan with filters
,03-21 13:05:03.430  5877  5888 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 6
,03-21 13:05:03.430  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:03.430  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:03.430  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:03.440  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:03.440  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:03.440  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:03.440  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:03.440  5877  5973 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-21 13:05:03.440  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:03.440  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:03.445  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 13:05:03.445  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:03.445  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:03.445  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:03.450  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:03.450  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:03.455 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 13:05:03.455 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:03.455 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-21 13:05:03.455 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:03.455 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:03.455 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:03.455 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 13:05:03.455 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:03.455 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:03.455 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:03.455 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:03.455 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:03.460  5877  8684 D BtGatt.GattService: registerClient() - UUID=ba58166b-4281-4547-b784-e2bb5bcea186
,03-21 13:05:03.505  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=ba58166b-4281-4547-b784-e2bb5bcea186, clientIf=7,
,03-21 13:05:03.505 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-21 13:05:03.530  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 3
,03-21 13:05:03.530  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:03.530  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:03.530  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:03.535  5877  5972 D BtGatt.AdvertiseManager: starting advertising
03-21 13:05:03.535  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 13:05:03.540  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:03.540  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:03.545  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:03.545  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 13:05:03.545  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:05:03.545 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:03.545 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:05:03.550 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:03.550 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:03.550 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 13:05:03.550 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:03.550 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 13:05:03.550 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 13:05:03.550 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 13:05:03.550 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 13:05:03.550 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:03.550 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:03.550 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:03.550 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:03.550 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:03.550 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:05:03.550 11201 11201 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:03.550 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:03.550 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:05:03.550 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:03.550 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 13:05:03.550 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:03.550 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:03.560 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:03.560 11201 11264 I jxcore-log: 
03-21 13:05:03.560 11201 11605 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:05:03.565 11201 11605 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 13:05:03.565 11201 11605 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-21 13:05:03.570 11201 11605 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:05:03.570 11201 11605 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:03.570 11201 11605 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23a18ec6
03-21 13:05:03.570 11201 11605 D BluetoothSocket: channel: 6
03-21 13:05:03.570 11201 11605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 13:05:03.575 11201 11264 I jxcore-log: ok 137 Can call startUpdateAdvertisingAndListening without error
03-21 13:05:03.575 11201 11264 I jxcore-log: 
03-21 13:05:03.575 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 13:05:03.575 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 13:05:03.575 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 13:05:03.575 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 13:05:03.575 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 13:05:03.575 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@186e4e87, channel: 6, state: LISTENING
03-21 13:05:03.575 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@186e4e87, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23a18ec6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@64ec1b4mSocket: android.net.LocalSocket@33c581dd impl:android.net.LocalSocketImpl@697d152 fd:FileDescriptor[92]
03-21 13:05:03.580 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33c581dd impl:android.net.LocalSocketImpl@697d152 fd:FileDescriptor[92]
03-21 13:05:03.580 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 13:05:03.580 11201 11605 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:05:03.580 11201 11605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 13:05:03.580 11201 11605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:05:03.580 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 13:05:03.580 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 13:05:03.580 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:05:03.580 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 13:05:03.580 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 13:05:03.585 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:03.585 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:03.585 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 13:05:03.585 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:05:03.585  5877  5890 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:03.585  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:03.585  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 8
03-21 13:05:03.590  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:03.590  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:03.590  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:03.590  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:03.590  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:03.590  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:03.590  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:03.590  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:03.595  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:03.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:03.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:03.600 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:05:03.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 13:05:03.600 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 13:05:03.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:03.600 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 13:05:03.605  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:05:03.605  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:03.605  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:03.605  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:03.610  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:03.610  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:05:03.610  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:05:03.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:03.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:03.610 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:03.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:05:03.610 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:03.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:03.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:03.610 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:05:03.615 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:05:03.615 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:03.615 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:03.615 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:03.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:03.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:03.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 13:05:03.615 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:03.615 11201 11264 I jxcore-log: 
03-21 13:05:03.615 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:03.615 11201 11264 I jxcore-log: 
03-21 13:05:03.620 11201 11264 I jxcore-log: ok 138 Can call stopAdvertisingAndListening without error
03-21 13:05:03.620 11201 11264 I jxcore-log: 
03-21 13:05:03.620 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:03.630 11201 11264 I jxcore-log: # setup
03-21 13:05:03.630 11201 11264 I jxcore-log: 
03-21 13:05:03.635 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:03.635 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:03.635 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:03.635 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:03.635 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:03.635 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:03.640 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:05:03.640 11201 11264 I jxcore-log: 
03-21 13:05:03.640 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:03.640 11201 11264 I jxcore-log: 
03-21 13:05:03.640 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:03.640 11201 11264 I jxcore-log: 
,03-21 13:05:03.765 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:03.765 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:05:03.770 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:03.770 11201 11264 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-21 13:05:03.770 11201 11264 I jxcore-log: 
,03-21 13:05:03.775 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:03.775 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:03.775 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:03.780 11201 11264 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-21 13:05:03.780 11201 11264 I jxcore-log: 
,03-21 13:05:03.790 11201 11264 I jxcore-log: # 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-21 13:05:03.790 11201 11264 I jxcore-log: 
,03-21 13:05:03.950 11201 11264 I jxcore-log: # teardown
03-21 13:05:03.950 11201 11264 I jxcore-log: 
,03-21 13:05:04.075 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-21 13:05:04.075 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:04.075 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 13:05:04.075 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:04.080 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:05:04.085 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:04.085 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:04.085 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:04.090  5877  8684 D BtGatt.GattService: registerClient() - UUID=3105ecb7-e04f-4d15-a5a7-53f1cc8ee639
,03-21 13:05:04.135  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=3105ecb7-e04f-4d15-a5a7-53f1cc8ee639, clientIf=6
,03-21 13:05:04.135 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:05:04.135  5877  9150 D BtGatt.GattService: start scan with filters
,03-21 13:05:04.150  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 7
,03-21 13:05:04.150  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:04.150  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:04.150  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:04.155  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:04.155  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:04.160  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:04.160  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:04.160  5877  5973 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-21 13:05:04.160  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:04.160  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:04.165  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:04.165  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:04.165 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:04.165 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:04.165 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:04.165 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:04.165 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:04.165 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:04.165 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:04.165 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:04.165 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:04.165 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:04.165 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:04.165 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:04.165  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 13:05:04.165  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 13:05:04.170  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:04.170  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:04.170  5877  8684 D BtGatt.GattService: registerClient() - UUID=d4cf8f71-e0df-4606-a56f-b1e592ecbeed
,03-21 13:05:04.210  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=d4cf8f71-e0df-4606-a56f-b1e592ecbeed, clientIf=7
,03-21 13:05:04.210 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:04.225  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 4,
03-21 13:05:04.225  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:04.225  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:04.225  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:04.225  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:04.225  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:04.230  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:04.230  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:04.230  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:04.230  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:04.230  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:05:04.230 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:05:04.230 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 13:05:04.235 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:04.240 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:04.240 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-21 13:05:04.240 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:04.240 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 13:05:04.240 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 13:05:04.240 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 13:05:04.240 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 13:05:04.240 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:04.240 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:04.240 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:04.240 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 13:05:04.240 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:04.240 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:04.240 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:05:04.240 11201 11201 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:04.240 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:04.240 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 13:05:04.240 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:04.240 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 13:05:04.240 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 13:05:04.245 11201 11616 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:05:04.245 11201 11616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:04.245 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:04.245 11201 11264 I jxcore-log: 
,03-21 13:05:04.250 11201 11264 I jxcore-log: ok 141 Can call startUpdateAdvertisingAndListening without error
03-21 13:05:04.250 11201 11264 I jxcore-log: 
03-21 13:05:04.250 11201 11616 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-21 13:05:04.250 11201 11616 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 13:05:04.250 11201 11616 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:04.250 11201 11616 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b3db09e
03-21 13:05:04.250 11201 11616 D BluetoothSocket: channel: 6
03-21 13:05:04.250 11201 11616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:04.255 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-21 13:05:04.255 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:04.255 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:05:04.255 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:05:04.255 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:04.255 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:04.255 11201 11264 I jxcore-log: 
,03-21 13:05:04.260 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:04.260 11201 11264 I jxcore-log: 
,03-21 13:05:04.260 11201 11264 I jxcore-log: ok 142 Can call startUpdateAdvertisingAndListening twice without error
03-21 13:05:04.260 11201 11264 I jxcore-log: 
,03-21 13:05:04.265 11201 11264 I jxcore-log: # setup
03-21 13:05:04.265 11201 11264 I jxcore-log: 
,03-21 13:05:04.450 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:04.455 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-21 13:05:04.455 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 13:05:04.455 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 13:05:04.460  5877  8684 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:04.460  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:04.460  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 9
03-21 13:05:04.465  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:04.465  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:04.465  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:04.470  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 13:05:04.470  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:04.470  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:04.470  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
03-21 13:05:04.470  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:04.470  5877  5968 D BtGatt.GattService: current time is 231534160151,
03-21 13:05:04.470  5877  5968 D BtGatt.GattService: Batch record : [56, -5, 123, 34, -12, 107, 1, -128, -82, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:04.470  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-21 13:05:04.470  5877  5968 D ScanRecord: parseFromBytes,
03-21 13:05:04.480  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-21 13:05:04.480 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:04.480 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 13:05:04.480 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:05:04.480 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 13:05:04.480 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
,03-21 13:05:04.485 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:04.485 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 13:05:04.485 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 13:05:04.485 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-21 13:05:04.490 11201 11264 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown,
03-21 13:05:04.490 11201 11264 I jxcore-log: 
,03-21 13:05:04.495 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:04.495 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-21 13:05:04.495 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 13:05:04.495 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 13:05:04.495 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 13:05:04.495 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d48877f, channel: 6, state: LISTENING
03-21 13:05:04.495 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d48877f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b3db09e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c64934cmSocket: android.net.LocalSocket@147c0f95 impl:android.net.LocalSocketImpl@27d038aa fd:FileDescriptor[92]
,03-21 13:05:04.495 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@147c0f95 impl:android.net.LocalSocketImpl@27d038aa fd:FileDescriptor[92]
,03-21 13:05:04.500 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 13:05:04.500 11201 11616 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:05:04.500 11201 11616 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 13:05:04.500 11201 11616 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:05:04.500 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:05:04.500 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 13:05:04.500 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:05:04.500 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 13:05:04.505 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-21 13:05:04.505 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-21 13:05:04.505 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:04.505 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 13:05:04.505 11201 11264 D BluetoothLeScanner: could not find callback wrapper,
03-21 13:05:04.505 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:04.505 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 13:05:04.510  5877  5972 D BtGatt.AdvertiseManager: message : 1,
03-21 13:05:04.510  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:04.510  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 13:05:04.510  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:04.515  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 13:05:04.515  5877  5968 D BtGatt.GattService: Client app is not null!,
,03-21 13:05:04.515  5877  8684 D BtGatt.GattService: unregisterClient() - clientIf=7,
03-21 13:05:04.515 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 13:05:04.515 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:04.515 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:04.515 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-21 13:05:04.515 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:04.515 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:04.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:04.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 13:05:04.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:05:04.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:04.520 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:04.520 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:04.520 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:04.520 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:04.520 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:05:04.520 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:05:04.520 11201 11264 I jxcore-log: 
,03-21 13:05:04.525 11201 11264 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown,
03-21 13:05:04.525 11201 11264 I jxcore-log: 
,03-21 13:05:04.525 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:04.530 11201 11264 I jxcore-log: # 36. peerAvailabilityChange is called
03-21 13:05:04.530 11201 11264 I jxcore-log: 
,03-21 13:05:04.530 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 13:05:04.535 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:04.535 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:04.535 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 13:05:04.535 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:04.540 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:04.540 11201 11264 I jxcore-log: 
,03-21 13:05:04.540 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:04.540 11201 11264 I jxcore-log: 
,03-21 13:05:04.610 11201 11264 I jxcore-log: # teardown
03-21 13:05:04.610 11201 11264 I jxcore-log: 
,03-21 13:05:04.800 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-21 13:05:04.800 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:04.800 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:04.800 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:04.805 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-21 13:05:04.805 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
,03-21 13:05:04.805 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,03-21 13:05:04.805 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
,03-21 13:05:04.815  5877  9150 D BtGatt.GattService: registerClient() - UUID=3457d0a6-3256-4066-835a-859d98723b5f
,03-21 13:05:04.855  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=3457d0a6-3256-4066-835a-859d98723b5f, clientIf=6
,03-21 13:05:04.855 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:04.855  5877  8684 D BtGatt.GattService: start scan with filters
,03-21 13:05:04.870  5877  8684 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 8
,03-21 13:05:04.870 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:04.870 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:04.870 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:04.870  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:04.870 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:04.870  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:04.870 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:04.870  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:04.870 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:04.870 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:04.870 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:04.870 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:04.870 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:04.870 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:04.870 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:04.870  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:04.870  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:04.870  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:04.870  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:04.870  5877  5973 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
,03-21 13:05:04.875  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-21 13:05:04.875  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:04.875  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:04.875  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:04.875  5877  8684 D BtGatt.GattService: registerClient() - UUID=c0582134-d808-4511-b393-a9f6964dad36
,03-21 13:05:04.875  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:04.875  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:04.880  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 13:05:04.880  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:04.915  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=c0582134-d808-4511-b393-a9f6964dad36, clientIf=7
,03-21 13:05:04.915 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:04.960  5877  5976 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 5,
03-21 13:05:04.960  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:05:04.960  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:04.960  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
03-21 13:05:04.970  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:04.970  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse,
,03-21 13:05:04.980  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
,03-21 13:05:04.995  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising,
,03-21 13:05:05.005  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
,03-21 13:05:05.005  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
,03-21 13:05:05.005  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0,
,03-21 13:05:05.015 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:05:05.015 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 13:05:05.035 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:05.035 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 13:05:05.035 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-21 13:05:05.035 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 13:05:05.040 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 13:05:05.040 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-21 13:05:05.040 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 13:05:05.040 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-21 13:05:05.040 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:05.045 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:05.045 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:05.045 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:05.045 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:05.045 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:05:05.045 11201 11201 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:05.045 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:05.045 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:05:05.045 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:05.045 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 13:05:05.045 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 13:05:05.045 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK,
,03-21 13:05:05.050 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:05.050 11201 11264 I jxcore-log: 
,03-21 13:05:05.055 11201 11639 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 13:05:05.060 11201 11639 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:05.065 11201 11264 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListeningwithout error
03-21 13:05:05.065 11201 11264 I jxcore-log: 
,03-21 13:05:05.065 11201 11639 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
,03-21 13:05:05.065 11201 11639 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:05:05.065 11201 11639 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 13:05:05.070 11201 11639 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27513576
03-21 13:05:05.070 11201 11639 D BluetoothSocket: channel: 6
,03-21 13:05:05.070 11201 11639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:05.075 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-21 13:05:05.075 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:05.075 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-21 13:05:05.075 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:05.075 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:05.080 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:05.080 11201 11264 I jxcore-log: 
,03-21 13:05:05.080 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:05.080 11201 11264 I jxcore-log: 
,03-21 13:05:05.085 11201 11264 I jxcore-log: ok 146 Can call startListeningForAdvertisements without error
03-21 13:05:05.085 11201 11264 I jxcore-log: 
,03-21 13:05:05.880  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:05.905  5877  5877 D BtGatt.ScanManager: awakened up at time 232967
,03-21 13:05:05.905  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:05.915  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:05.915  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:05.915  5877  5968 D BtGatt.GattService: current time is 232977889484
03-21 13:05:05.915  5877  5968 D BtGatt.GattService: Batch record : [-85, -34, 24, 96, -84, 101, 1, -128, -70, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:05.915  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:05.915  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:05.915  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=65:AC:60:18:DE:AB, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-70, mTimestampNanos=232978072818}
03-21 13:05:05.915  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:05.915 11201 11213 D ScanRecord: parseFromBytes
03-21 13:05:05.920 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 13:05:05.920 11201 11201 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 13:05:05.935 11201 11264 I jxcore-log: ok 147 peers must be an array
03-21 13:05:05.935 11201 11264 I jxcore-log: 
,03-21 13:05:05.945  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-21 13:05:05.945  3728  3728 I PERF    : received broadcast android.intent.action.TIME_TICK
03-21 13:05:05.945  3728  3728 D KeyguardUpdateMonitor: handleTimeUpdate
,03-21 13:05:05.950 11201 11264 I jxcore-log: ok 148 peers must not be zero-length
03-21 13:05:05.950 11201 11264 I jxcore-log: 
,03-21 13:05:05.950 11201 11264 I jxcore-log: ok 149 peer must have peerIdentifier
03-21 13:05:05.950 11201 11264 I jxcore-log: 
,03-21 13:05:05.955 11201 11264 I jxcore-log: ok 150 peerIdentifier must be a string
03-21 13:05:05.955 11201 11264 I jxcore-log: 
03-21 13:05:05.955 11201 11264 I jxcore-log: ok 151 peer must have peerAvailable
03-21 13:05:05.955 11201 11264 I jxcore-log: 
,03-21 13:05:05.955 11201 11264 I jxcore-log: ok 152 peer must have pleaseConnect
03-21 13:05:05.955 11201 11264 I jxcore-log: 
03-21 13:05:05.955  3728  3728 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-21 13:05:05.960  3728  3728 D SecKeyguardClockView: HomeTimezone(): 1
,03-21 13:05:05.965 11201 11264 I jxcore-log: # setup
03-21 13:05:05.965 11201 11264 I jxcore-log: 
,03-21 13:05:05.970  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 13:05:05.970  3728  3728 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 13:05:05.975  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 13:05:06.015  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 13:05:06.020  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 13:05:06.020  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 13:05:06.025  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 13:05:06.030  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-21 13:05:06.030  3728  3728 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 13:05:06.050  3728  3728 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 13:05:06.120 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 13:05:06.120 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 13:05:06.120 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 13:05:06.120 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:05:06.120  5877  5976 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:05:06.120  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:06.120  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 10
03-21 13:05:06.120  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 13:05:06.125 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:06.125 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 13:05:06.125 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:05:06.125 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 13:05:06.125 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 13:05:06.125 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
03-21 13:05:06.125 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:06.125  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:06.125  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:06.125  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:06.125 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 13:05:06.125 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 13:05:06.130  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:06.130  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:06.130 11201 11264 I jxcore-log: ok 153 Should be able to call stopListeningForAdvertisments in teardown
03-21 13:05:06.130 11201 11264 I jxcore-log: 
03-21 13:05:06.130  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:06.130 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 13:05:06.130 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-21 13:05:06.130 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 13:05:06.130 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 13:05:06.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 13:05:06.130 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@effffe4, channel: 6, state: LISTENING
03-21 13:05:06.130 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@effffe4, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27513576, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@314f9c4dmSocket: android.net.LocalSocket@31133302 impl:android.net.LocalSocketImpl@34438413 fd:FileDescriptor[92]
03-21 13:05:06.130 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31133302 impl:android.net.LocalSocketImpl@34438413 fd:FileDescriptor[92]
03-21 13:05:06.130 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 13:05:06.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 13:05:06.130 11201 11639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:05:06.130 11201 11639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 13:05:06.130 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 13:05:06.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:06.130 11201 11639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:05:06.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:06.130 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 13:05:06.130  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:06.130  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:06.130  5877  5968 D BtGatt.GattService: current time is 233194853651
03-21 13:05:06.135  5877  5968 D BtGatt.GattService: Batch record : [-85, -34, 24, 96, -84, 101, 1, -128, -71, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:06.135  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:06.135  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:06.135 11201 11264 D BluetoothLeScanner: could not find callback wrapper
03-21 13:05:06.135 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:06.135 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 13:05:06.135  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:05:06.135  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:06.135  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:06.135  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:06.140  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 13:05:06.140  5877  5968 D BtGatt.GattService: Client app is not null!
,03-21 13:05:06.140  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:06.140 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 13:05:06.140 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:06.140 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:06.140 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:05:06.140 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:06.140 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 13:05:06.140 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:06.140 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:05:06.145 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:05:06.145 11201 11264 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 13:05:06.145 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:06.145 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:06.145 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:06.145 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:05:06.145 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:05:06.145 11201 11264 I jxcore-log: 
,03-21 13:05:06.150 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:06.155 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 13:05:06.155 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 13:05:06.155 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:06.160 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:05:06.160 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:05:06.160 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:06.160 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:06.160 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:06.160 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:06.160 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 13:05:06.165 11201 11264 I jxcore-log: ok 154 Should be able to call stopAdvertisingAndListening in teardown
03-21 13:05:06.165 11201 11264 I jxcore-log: 
,03-21 13:05:06.175 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:06.175 11201 11264 I jxcore-log: 
,03-21 13:05:06.175 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:06.175 11201 11264 I jxcore-log: 
,03-21 13:05:06.175 11201 11264 I jxcore-log: # 37. Can connect to a remote peer
03-21 13:05:06.175 11201 11264 I jxcore-log: 
,03-21 13:05:06.200 11201 11210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9cb12b5, channel: 6, state: CLOSED
,03-21 13:05:06.200 11201 11210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36d7e36d, channel: 6, state: CLOSED
,03-21 13:05:06.205 11201 11210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@186e4e87, channel: 6, state: CLOSED
,03-21 13:05:06.205 11201 11210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d48877f, channel: 6, state: CLOSED
,03-21 13:05:06.205 11201 11210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@effffe4, channel: 6, state: CLOSED
,03-21 13:05:06.305 11201 11264 I jxcore-log: # teardown,
03-21 13:05:06.305 11201 11264 I jxcore-log: 
,03-21 13:05:06.425 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 52840, start advertisements: true
,03-21 13:05:06.425 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:06.425 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 13:05:06.425 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:06.430 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:05:06.430 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:06.430 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:06.435 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:06.440  5877  5976 D BtGatt.GattService: registerClient() - UUID=bd5793e6-e251-4a1b-8a7f-147e854d8b58
,03-21 13:05:06.480  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=bd5793e6-e251-4a1b-8a7f-147e854d8b58, clientIf=6
03-21 13:05:06.480 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:05:06.490  5877  5890 D BtGatt.GattService: start scan with filters,
,03-21 13:05:06.510  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 9
,03-21 13:05:06.510 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:06.510 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:06.510  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:06.510  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:06.510  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:06.510 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:06.510 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:06.510 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:06.510 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:06.510 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 13:05:06.510 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:06.510 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:06.510 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:06.510 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:06.510 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:06.515  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:06.515  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:06.515  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:06.515  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:06.515  5877  5973 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
,03-21 13:05:06.515  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
,03-21 13:05:06.515  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:06.515  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:06.515  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:06.520  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:06.520  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:06.520  5877  5888 D BtGatt.GattService: registerClient() - UUID=4cfda72b-60d1-4420-93f2-be06033c2a95
,03-21 13:05:06.520  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:06.520  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:06.560  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=4cfda72b-60d1-4420-93f2-be06033c2a95, clientIf=7,
03-21 13:05:06.560 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:06.580  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 6
,03-21 13:05:06.580  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:06.580  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
,03-21 13:05:06.580  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:06.580  5877  5972 D BtGatt.AdvertiseManager: starting advertising
03-21 13:05:06.580  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:06.585  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:06.585  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:06.590  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:06.590  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:06.590  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:05:06.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:05:06.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 13:05:06.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:06.595 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:06.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 13:05:06.595 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:06.595 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 13:05:06.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-21 13:05:06.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 13:05:06.595 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 13:05:06.595 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:06.595 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:06.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:06.595 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:06.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:06.595 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:06.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:05:06.595 11201 11201 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:06.595 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:06.595 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 13:05:06.595 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:06.595 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 13:05:06.595 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:06.600 11201 11661 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:05:06.600 11201 11661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:06.605 11201 11661 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
,03-21 13:05:06.605 11201 11661 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:05:06.605 11201 11661 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:06.605 11201 11661 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fd84e6f
03-21 13:05:06.605 11201 11661 D BluetoothSocket: channel: 6
03-21 13:05:06.605 11201 11661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:06.610 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:06.610 11201 11264 I jxcore-log: 
,03-21 13:05:06.610 11201 11264 I jxcore-log: ok 155 Can call startUpdateAdvertisingAndListening without error
03-21 13:05:06.610 11201 11264 I jxcore-log: 
,03-21 13:05:06.615 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 52840, start advertisements: false
,03-21 13:05:06.615 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:06.615 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-21 13:05:06.615 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:05:06.615 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:06.615 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:06.615 11201 11264 I jxcore-log: 
,03-21 13:05:06.620 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:06.620 11201 11264 I jxcore-log: 
,03-21 13:05:06.620 11201 11264 I jxcore-log: ok 156 Can call startListeningForAdvertisements without error
03-21 13:05:06.620 11201 11264 I jxcore-log: 
,03-21 13:05:07.525  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:07.535  5877  5877 D BtGatt.ScanManager: awakened up at time 234598
03-21 13:05:07.540  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:07.555  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:07.555  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:07.555  5877  5968 D BtGatt.GattService: current time is 234618745151
03-21 13:05:07.555  5877  5968 D BtGatt.GattService: Batch record : [-38, 8, -114, -98, 127, 75, 1, -128, -71, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:07.555  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:07.555  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:07.555  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=4B:7F:9E:8E:08:DA, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=234518894568}
03-21 13:05:07.555  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:07.560 11201 11213 D ScanRecord: parseFromBytes
03-21 13:05:07.560 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 13:05:07.560 11201 11201 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 13:05:07.580 11201 11264 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-21 13:05:07.580 11201 11264 I jxcore-log: 
,03-21 13:05:07.585 11201 11264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-21 13:05:07.585 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:07.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-21 13:05:07.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-21 13:05:07.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-21 13:05:07.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
,03-21 13:05:07.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
,03-21 13:05:07.595 11201 11264 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-21 13:05:07.595 11201 11664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1541)
,03-21 13:05:07.605 11201 11664 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-21 13:05:07.605 11201 11664 D BluetoothSocket: connect(): myUserId = 0
,03-21 13:05:07.605 11201 11664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:07.610  5877  5890 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 13:05:07.610  5877  6023 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:07.610  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 13:05:07.610  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 13:05:07.610  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-21 13:05:07.610  5877  6023 D IOP_DB_BT: db_query_execute: result 1
03-21 13:05:07.610  5877  6023 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 13:05:07.615 11201 11664 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,03-21 13:05:08.570  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:08.575  5877  5877 D BtGatt.ScanManager: awakened up at time 235637
03-21 13:05:08.580  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:08.585  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:08.585  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:08.585  5877  5968 D BtGatt.GattService: current time is 235646610485
03-21 13:05:08.585  5877  5968 D BtGatt.GattService: Batch record : [-38, 8, -114, -98, 127, 75, 1, -128, -68, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:08.585  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:08.585  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:05:08.585  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=4B:7F:9E:8E:08:DA, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=235646806985},
,03-21 13:05:08.585  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
03-21 13:05:08.585 11201 11211 D ScanRecord: parseFromBytes
,03-21 13:05:08.590 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:08.660  3369  3964 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:05:08.660  3369  3964 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:05:08.660  3369  3964 D BatteryService: online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
03-21 13:05:08.660  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:05:08.660  3369  3964 D BatteryService: stay LED for fully charged
,03-21 13:05:08.665  3369  3369 I MotionRecognitionService: Plugged,
03-21 13:05:08.665  3369  3369 D MotionRecognitionService:   cableConnection= 1
,03-21 13:05:08.665  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:05:08.665  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:05:08.670  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:05:08.670  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:05:08.670  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:05:08.675  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:05:08.680  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 13:05:08.680  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:05:08.695  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:05:08.695  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:08.695  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:05:09.255  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:12), CUR = 66, LCD = 0
,03-21 13:05:09.595  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:09.605  5877  5877 D BtGatt.ScanManager: awakened up at time 236669
,03-21 13:05:09.615  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:09.620  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:09.620  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:09.620  5877  5968 D BtGatt.GattService: current time is 236684876235
03-21 13:05:09.625  5877  5968 D BtGatt.GattService: Batch record : [-38, 8, -114, -98, 127, 75, 1, -128, -69, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:09.625  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:09.625  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:09.625  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=4B:7F:9E:8E:08:DA, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-69, mTimestampNanos=236435520485}
03-21 13:05:09.625  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:09.630 11201 11213 D ScanRecord: parseFromBytes
03-21 13:05:09.630 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:09.725  5877  6023 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:09.725  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:09.725  5877  6023 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 13:05:09.745  5877  6023 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:09.745  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 13:05:09.745  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 13:05:09.745  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
,03-21 13:05:09.750  5877  6023 D IOP_DB_BT: db_query_execute: result 1
03-21 13:05:09.750  5877  6023 W bt-btif : bta_dm_acl_change(), event : 0
03-21 13:05:09.750  5877  6023 W bt-btif : info:x10
03-21 13:05:09.750  5877  6023 W bt-btif : bta_dm_acl_change(), event : 2
03-21 13:05:09.750  5877  5968 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-21 13:05:09.750  5877  5968 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-21 13:05:09.765  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
,03-21 13:05:09.775  5877  6023 W bt-sdp  : process_service_search_attr_rsp,
,03-21 13:05:09.950  5877  5968 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-21 13:05:09.960  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 13:05:09.980  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 13:05:09.980  5877  5968 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-21 13:05:09.985  3369  4396 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 13:05:09.985  5877  5968 E bt-btif : check_cod: remote_cod = 0x5a020c
03-21 13:05:09.985  5877  5968 W bt-btif : btif_dm_ssp_reply: accept=1
,03-21 13:05:09.990  5877  5971 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-21 13:05:09.995  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,03-21 13:05:09.995  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 13:05:10.000  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED,
,03-21 13:05:10.000  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,03-21 13:05:10.000  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
,03-21 13:05:10.000  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
03-21 13:05:10.010  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 13:05:10.010  3369  3554 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{55e3b51 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b1d1a32 10122:com.android.settings/1000},
03-21 13:05:10.010  3369  5929 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-21 13:05:10.015  5877  5971 D BtConfig.SecureMode: isSecureModeOn:false
03-21 13:05:10.015  5877  5971 I BluetoothBondStateMachine: Entering PendingCommandState State
03-21 13:05:10.015  3728  4740 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 13:05:10.020 10122 10122 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 13:05:10.030 10312 11688 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:10.030 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
03-21 13:05:10.030  3369  3964 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{55e3b51 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:10.030 10312 10312 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 13:05:10.035 10312 10312 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-21 13:05:10.040  3369  4402 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{55e3b51 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:10.040  3369  3387 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:10.050 10312 11689 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:10.050 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 13:05:10.050  3369  3822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{55e3b51 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{780b547 10459:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 13:05:10.060 10459 10459 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 13:05:10.065 10459 10459 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 13:05:10.065 10459 10459 D GMHFPReceiver: jangil::setProperties()
,03-21 13:05:10.065 10459 10459 D GMHFPReceiver: jangil::printBTStatus()
,03-21 13:05:10.070  3369  3964 D SettingsProvider: name = Wearable0001
03-21 13:05:10.070  3369  3964 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:10.070  3369  3964 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:10.070  3369  3964 D SettingsProvider: selectionArgs: false
03-21 13:05:10.070  3369  3964 D SettingsProvider: selectionArgs: 10121
03-21 13:05:10.070  3369  3964 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:10.070  3369  3964 D SettingsProvider: ret = -1
,03-21 13:05:10.075  3369  3964 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-21 13:05:10.085 10459 10459 D GMHFPReceiver: ::::::::Wearable0001::false
,03-21 13:05:10.090  3369  4389 D SettingsProvider: name = Wearable0002
03-21 13:05:10.090  3369  4389 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:10.090  3369  4389 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:10.090  3369  4389 D SettingsProvider: selectionArgs: false
03-21 13:05:10.090  3369  4389 D SettingsProvider: selectionArgs: 10121
03-21 13:05:10.090  3369  4389 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:10.095  3369  4389 D SettingsProvider: ret = -1
,03-21 13:05:10.095  3728  3728 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 13:05:10.100  3369  4389 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121,
03-21 13:05:10.100  5877  5968 W bt-btif : btif_dm_auth_cmpl_evt
03-21 13:05:10.100  5877  5968 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
03-21 13:05:10.100 10459 10459 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 13:05:10.105  3369  4402 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{55e3b51 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{266265af 4298:com.google.android.gms.persistent/u0a14}
,03-21 13:05:10.115  5877  5968 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-21 13:05:10.115  5877  5971 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-21 13:05:10.115  3369  4389 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 13:05:10.120  5877  5971 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-21 13:05:10.120  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,03-21 13:05:10.120  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 13:05:10.120  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-21 13:05:10.120  3728  3728 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 13:05:10.120  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-21 13:05:10.120  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-21 13:05:10.120  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 13:05:10.125  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 13:05:10.130  3728  4740 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 13:05:10.130  3369  3554 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d8b5553 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b1d1a32 10122:com.android.settings/1000}
,03-21 13:05:10.130  5877  5971 D BtConfig.SecureMode: isSecureModeOn:false
03-21 13:05:10.130  3369  4404 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:10.130 10122 10122 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 13:05:10.140 10312 11696 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:10.140  5877  5971 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@b5d1852
03-21 13:05:10.140  3369  3387 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d8b5553 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:10.140 10312 10312 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 13:05:10.140  3369  3965 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-21 13:05:10.140  3369  3965 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:10.140  3369  3965 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:10.140  3369  3965 D SettingsProvider: selectionArgs: false
03-21 13:05:10.140  3369  3965 D SettingsProvider: selectionArgs: 1002
03-21 13:05:10.140  3369  3965 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:10.145  3369  3965 D SettingsProvider: ret = -1
03-21 13:05:10.145  5877  5971 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-21 13:05:10.145 10312 10312 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-21 13:05:10.145  3369  5929 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
03-21 13:05:10.145  3369  5929 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:10.145  3369  5929 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:10.145  3369  5929 D SettingsProvider: selectionArgs: false
03-21 13:05:10.145  3369  5929 D SettingsProvider: selectionArgs: 1002
03-21 13:05:10.145  3369  5929 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:10.145  3369  5929 D SettingsProvider: ret = -1
,03-21 13:05:10.150  3369  3964 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
,03-21 13:05:10.150  3369  3964 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:10.150  3369  3964 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:10.150  3369  3964 D SettingsProvider: selectionArgs: false
03-21 13:05:10.150  3369  3964 D SettingsProvider: selectionArgs: 1002
03-21 13:05:10.150  3369  3964 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:10.150  3369  3964 D SettingsProvider: ret = -1
,03-21 13:05:10.150  5877  5971 I BluetoothBondStateMachine: StableState(): Entering Off State
03-21 13:05:10.150  3369  3721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d8b5553 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:10.150  3369  4404 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:10.155 10312 11698 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:10.160  3369  3721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d8b5553 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{780b547 10459:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 13:05:10.160 10459 10459 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 13:05:10.165 10459 10459 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 13:05:10.165 10459 10459 D GMHFPReceiver: jangil::setProperties()
,03-21 13:05:10.165 10459 10459 D GMHFPReceiver: jangil::printBTStatus()
,03-21 13:05:10.165  3369  3387 D SettingsProvider: name = Wearable0001
,03-21 13:05:10.165  3369  3387 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:10.165  3369  3387 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:10.165  3369  3387 D SettingsProvider: selectionArgs: false
03-21 13:05:10.165  3369  3387 D SettingsProvider: selectionArgs: 10121
03-21 13:05:10.165  3369  3387 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 13:05:10.170  3369  3387 D SettingsProvider: ret = -1
,03-21 13:05:10.170 10459 10459 D GMHFPReceiver: ::::::::Wearable0001::false
03-21 13:05:10.170  3369  3836 D SettingsProvider: name = Wearable0002
,03-21 13:05:10.170  3369  3836 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:10.170  3369  3836 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:10.170  3369  3836 D SettingsProvider: selectionArgs: false
03-21 13:05:10.170  3369  3836 D SettingsProvider: selectionArgs: 10121
03-21 13:05:10.170  3369  3836 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 13:05:10.170  3369  3836 D SettingsProvider: ret = -1
,03-21 13:05:10.170 10459 10459 D GMHFPReceiver: ::::::::Wearable0002::false
03-21 13:05:10.170 10459 10459 D GMHFPReceiver: onServiceConnected() : 1
,03-21 13:05:10.170 10459 10459 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 13:05:10.175  3369  4031 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3d8b5553 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{266265af 4298:com.google.android.gms.persistent/u0a14}
,03-21 13:05:10.265 10459 10459 D GMHFPReceiver: onServiceConnected() : 1
03-21 13:05:10.265 10459 10459 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 13:05:10.640  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:10.655  5877  5877 D BtGatt.ScanManager: awakened up at time 237715
,03-21 13:05:10.665  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:10.665  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:10.665  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:11.675  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:11.685  5877  5877 D BtGatt.ScanManager: awakened up at time 238749
,03-21 13:05:11.695  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:11.700  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:11.700  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:12.715  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:12.725  5877  5877 D BtGatt.ScanManager: awakened up at time 239789
,03-21 13:05:12.735  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:12.740  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-21 13:05:12.740  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:13.755  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:13.765  5877  5877 D BtGatt.ScanManager: awakened up at time 240825
,03-21 13:05:13.765  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:13.770  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:13.770  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:13.775  5877  5968 D BtGatt.GattService: current time is 240835394860
03-21 13:05:13.775  5877  5968 D BtGatt.GattService: Batch record : [-38, 8, -114, -98, 127, 75, 1, -128, -79, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:13.775  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:13.775  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:05:13.775  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=4B:7F:9E:8E:08:DA, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-79, mTimestampNanos=240785847527}
,03-21 13:05:13.775  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:13.780 11201 11213 D ScanRecord: parseFromBytes
,03-21 13:05:13.780 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:14.775  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:14.790  5877  5877 D BtGatt.ScanManager: awakened up at time 241851
,03-21 13:05:14.795  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-21 13:05:14.800  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
03-21 13:05:14.800  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:14.800  5877  5968 D BtGatt.GattService: current time is 241863301527,
,03-21 13:05:14.800  5877  5968 D BtGatt.GattService: Batch record : [-38, 8, -114, -98, 127, 75, 1, -128, -77, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:14.800  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:14.800  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:05:14.800  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=4B:7F:9E:8E:08:DA, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=241513446860}
03-21 13:05:14.800  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,03-21 13:05:14.800 11201 11211 D ScanRecord: parseFromBytes,
03-21 13:05:14.805 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1,
,03-21 13:05:15.815  3369  3620 V AlarmManager: waitForAlarm result :4,
,03-21 13:05:15.825  5877  5877 D BtGatt.ScanManager: awakened up at time 242889,
,03-21 13:05:15.840  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:15.840  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 13:05:15.840  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:16.560  5877  6023 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 66 RCID: 67
,03-21 13:05:16.585  5877  6023 W bt-btif : new conn_srvc id:26, app_id:255
03-21 13:05:16.585  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 13:05:16.585  5877  6023 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-21 13:05:16.585 11201 11661 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@128f1f81
,03-21 13:05:16.585  5877  6023 W bt-btif : new conn_srvc id:26, app_id:1
03-21 13:05:16.585  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 13:05:16.585  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-21 13:05:16.585  5877  6023 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-21 13:05:16.595  5877  5888 E BluetoothRemoteDevices: setRfcommConnected true
03-21 13:05:16.600  5877  9150 E BluetoothRemoteDevices: setRfcommConnected true
,03-21 13:05:16.605 11201 11661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted,
,03-21 13:05:16.610 11201 11664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1541)
03-21 13:05:16.610 11201 11664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1541)
,03-21 13:05:16.620 11201 11664 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-21 13:05:16.625 11201 11661 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-21 13:05:16.630 11201 11664 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-21 13:05:16.630  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:16.630  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:16.630  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:16.630  5877  6023 D IOP_DB_BT: db_query: result 1,
03-21 13:05:16.630 11201 11664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1543)
03-21 13:05:16.630 11201 11664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1543)
,03-21 13:05:16.630 11201 11664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1541)
03-21 13:05:16.640 11201 11661 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-21 13:05:16.640 11201 11661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1542)
03-21 13:05:16.640 11201 11661 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@214fe826, channel: 6, state: LISTENING
03-21 13:05:16.640 11201 11661 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@214fe826, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fd84e6f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b259c67mSocket: android.net.LocalSocket@3552a14 impl:android.net.LocalSocketImpl@3d8d32bd fd:FileDescriptor[93]
,03-21 13:05:16.640 11201 11661 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3552a14 impl:android.net.LocalSocketImpl@3d8d32bd fd:FileDescriptor[93]
03-21 13:05:16.640 11201 11661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 13:05:16.645 11201 11661 D BluetoothSocket: bindListen(): myUserId = 0,
03-21 13:05:16.645 11201 11661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:16.650 11201 11736 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1543),
03-21 13:05:16.650 11201 11661 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
03-21 13:05:16.650 11201 11661 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 13:05:16.650 11201 11661 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:16.650 11201 11661 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35c260b2
,03-21 13:05:16.650 11201 11661 D BluetoothSocket: channel: 6
03-21 13:05:16.650 11201 11661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 13:05:16.650 11201 11737 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1542)
03-21 13:05:16.650 11201 11737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1542)
,03-21 13:05:16.650 11201 11737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:16.655  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 13:05:16.655  5877  6023 D IOP_DB_BT: db_query: result 1,
,03-21 13:05:16.655  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 13:05:16.655  5877  6023 D IOP_DB_BT: db_query: result 1,
03-21 13:05:16.655  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:16.660  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:16.660  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:16.660  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:16.660 11201 11736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1543)
03-21 13:05:16.660 11201 11736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:16.660 11201 11736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1541)
03-21 13:05:16.660 11201 11736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1541)
,03-21 13:05:16.660 11201 11201 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:16.660 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:16.660 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 13:05:16.665 11201 11201 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 13:05:16.670 11201 11201 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 13:05:16.670 11201 11201 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-21 13:05:16.670 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-21 13:05:16.675 11201 11737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1542)
03-21 13:05:16.675 11201 11737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1542
03-21 13:05:16.675 11201 11737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1542)
03-21 13:05:16.675 11201 11737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:16.675 11201 11737 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1542)
03-21 13:05:16.675 11201 11736 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1543)
,03-21 13:05:16.680 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:16.680 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:16.680 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:16.680 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:16.680 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:16.680 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:16.680  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:05:16.685  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:16.685  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:16.685  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:16.685  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:16.685  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:05:16.685  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:05:16.685 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:16.685 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:16.685 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:16.685 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:16.685 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 13:05:16.685 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:16.685 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:16.685 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:16.685 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:16.690  5877  8684 D BtGatt.GattService: registerClient() - UUID=6faff668-939d-4316-8c84-6a2c362f6b2e
,03-21 13:05:16.735  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=6faff668-939d-4316-8c84-6a2c362f6b2e, clientIf=7
,03-21 13:05:16.735 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:16.745  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 7
,03-21 13:05:16.745  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:05:16.745  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
,03-21 13:05:16.745  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:16.745  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:16.745  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:16.750  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:16.750  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:16.755  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:16.755  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:16.755  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:05:16.755 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:05:16.755  5877  5890 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:16.755  5877  5973 D BtGatt.ScanManager: filter size is 1,
03-21 13:05:16.755  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 11
03-21 13:05:16.755  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:16.760  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:16.760  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:16.760 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:16.760 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:16.760 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 13:05:16.760 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:05:16.760 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:16.760  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:16.760 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:16.760  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:16.760  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:16.760  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:16.765  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 13:05:16.765  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:16.765  5877  5890 D BtGatt.GattService: registerClient() - UUID=133fed0b-1505-42a6-923e-a1f9c5935e0f
,03-21 13:05:16.805  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=133fed0b-1505-42a6-923e-a1f9c5935e0f, clientIf=6
,03-21 13:05:16.805 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:16.810  5877  5976 D BtGatt.GattService: start scan with filters
,03-21 13:05:16.825  5877  5976 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 10
,03-21 13:05:16.825  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:16.825  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:16.825  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:16.830  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:16.830  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:16.830  5877  5973 D BtGatt.ScanManager: allow scan with filters
,03-21 13:05:16.835  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:16.835  5877  5973 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-21 13:05:16.835  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:16.835  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:16.840  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:16.840  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:16.840  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:16.840  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:16.840  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 13:05:16.840  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:16.845 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-21 13:05:16.845 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-21 13:05:16.845 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-21 13:05:16.850 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:16.850 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:16.850 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:16.850 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:16.850 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:16.850 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:16.850  5877  5972 D BtGatt.AdvertiseManager: message : 1
,03-21 13:05:16.850  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:16.850  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:16.855  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:16.855  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:16.855  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:05:16.855  5877  5888 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:05:16.855 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 13:05:16.855 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED,
03-21 13:05:16.855 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 13:05:16.855 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-21 13:05:16.855 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0",
,03-21 13:05:16.855 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0,
,03-21 13:05:16.855 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 13:05:16.855 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:16.855 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:16.865  5877  5890 D BtGatt.GattService: registerClient() - UUID=06b527df-9273-4f0f-839f-5f7d52049a82
,03-21 13:05:16.905  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=06b527df-9273-4f0f-839f-5f7d52049a82, clientIf=7
,03-21 13:05:16.910 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:16.920  5877  8684 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 8
,03-21 13:05:16.920  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:05:16.920  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:16.920  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:16.920  5877  5972 D BtGatt.AdvertiseManager: starting advertising
03-21 13:05:16.920  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:16.925  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:16.925  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:16.925  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:16.925  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:16.925  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 13:05:16.930 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:05:16.930  5877  5888 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:05:16.930  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:16.930  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 12
03-21 13:05:16.930  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 13:05:16.930 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:16.930 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 13:05:16.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:16.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:05:16.930 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:16.930 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:16.930  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:16.930  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:16.930  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:16.935  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:16.935  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:16.935  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:16.935  5877  5890 D BtGatt.GattService: registerClient() - UUID=6034e3c7-4e95-4ac9-aa6a-e7194f112cd6
03-21 13:05:16.935  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 13:05:16.935  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:16.980  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=6034e3c7-4e95-4ac9-aa6a-e7194f112cd6, clientIf=6
,03-21 13:05:16.980 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:05:16.980  5877  5976 D BtGatt.GattService: start scan with filters
,03-21 13:05:17.015  5877  5976 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 11
,03-21 13:05:17.025 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:17.025 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 13:05:17.025  5877  5973 D BtGatt.ScanManager: handling starting scan
,03-21 13:05:17.025  5877  5973 D BtGatt.ScanManager: isFilteringSupported,
,03-21 13:05:17.025  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:17.040  5877  5972 D BtGatt.AdvertiseManager: message : 1,
,03-21 13:05:17.040  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-21 13:05:17.040  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:17.045  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 13:05:17.045  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 13:05:17.045  5877  5973 D BtGatt.ScanManager: allow scan with filters,
,03-21 13:05:17.045  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
,03-21 13:05:17.045  5877  5973 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-21 13:05:17.050  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
03-21 13:05:17.050  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 13:05:17.050  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 13:05:17.050  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:17.050  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:17.050  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
,03-21 13:05:17.055  5877  5968 D BtGatt.GattService: Client app is not null!,
03-21 13:05:17.055  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:17.070  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 13:05:17.070  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:17.070 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 13:05:17.070 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-21 13:05:17.070 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 13:05:17.070 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 13:05:17.070 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:17.075 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0,
,03-21 13:05:17.075 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-21 13:05:17.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-21 13:05:17.075 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:17.075  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 13:05:17.075  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:17.105  5877  9150 D BtGatt.GattService: registerClient() - UUID=458ec20b-6119-43af-baa1-e49a6d74673d
03-21 13:05:17.145  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=458ec20b-6119-43af-baa1-e49a6d74673d, clientIf=7
03-21 13:05:17.150 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:17.180  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 9
03-21 13:05:17.180  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:05:17.180  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:17.180  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:17.185  5877  5972 D BtGatt.AdvertiseManager: starting advertising,
03-21 13:05:17.185  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 13:05:17.185  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-21 13:05:17.190  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:17.190  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-21 13:05:17.190  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 13:05:17.190  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 13:05:17.190 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:17.195  5877  5888 D BtGatt.GattService: stopScan() - queue size =1,
03-21 13:05:17.195  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:17.195  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 13
03-21 13:05:17.195  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:17.195 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:17.195 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 13:05:17.195 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:17.195 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:05:17.195 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:17.195 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:17.200  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-21 13:05:17.200  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:17.200  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:17.200  5877  5976 D BtGatt.GattService: registerClient() - UUID=5c3634ac-0ecd-420d-9c54-310bf33a5b3d
03-21 13:05:17.205  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:17.205  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:17.205  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:17.205  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:17.205  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:17.245  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=5c3634ac-0ecd-420d-9c54-310bf33a5b3d, clientIf=6
,03-21 13:05:17.245 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:17.245  5877  9150 D BtGatt.GattService: start scan with filters
,03-21 13:05:17.255  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 12
,03-21 13:05:17.255 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:17.255 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:17.255  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:17.255  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:17.255  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:17.255 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 13:05:17.255 11201 11201 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-21 13:05:17.255 11201 11201 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:17.255 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:17.255 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:17.255 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:17.255 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:17.255 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:17.255 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:17.255 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 13:05:17.255 11201 11759 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1544)
,03-21 13:05:17.255  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 13:05:17.255  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:17.255  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:17.255  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:17.255  5877  5973 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
,03-21 13:05:17.260 11201 11759 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37222
03-21 13:05:17.260  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:17.260  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 13:05:17.260 11201 11759 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-21 13:05:17.260 11201 11759 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 37222 (peer ID: F8:95:C7:87:3C:51)
03-21 13:05:17.260  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:17.260  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:17.260 11201 11759 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-21 13:05:17.260 11201 11201 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 13:05:17.260  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:17.260  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:17.260  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 13:05:17.260  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:17.265 11201 11201 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 13:05:17.265 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 13:05:17.265 11201 11201 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-21 13:05:17.265 11201 11760 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1545)
,03-21 13:05:17.265  2873  3396 D EnterpriseController: netId is 0
03-21 13:05:17.265  2873  3396 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 13:05:17.265 11201 11264 I jxcore-log: INFO testThaliMobileNative: 
03-21 13:05:17.265 11201 11264 I jxcore-log: 
,03-21 13:05:17.270 11201 11264 I jxcore-log: ok 157 Must have listeningPort
03-21 13:05:17.270 11201 11264 I jxcore-log: 
,03-21 13:05:17.270 11201 11264 I jxcore-log: ok 158 listeningPort must be a number
03-21 13:05:17.270 11201 11264 I jxcore-log: 
,03-21 13:05:17.270 11201 11264 I jxcore-log: ok 159 Connection must have clientPort
03-21 13:05:17.270 11201 11264 I jxcore-log: 
03-21 13:05:17.270 11201 11760 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 52840
03-21 13:05:17.270 11201 11760 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-21 13:05:17.270 11201 11264 I jxcore-log: ok 160 clientPort must be a number
03-21 13:05:17.270 11201 11264 I jxcore-log: 
,03-21 13:05:17.270 11201 11760 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:17.270 11201 11760 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:17.270 11201 11264 I jxcore-log: ok 161 Connection must have serverPort
03-21 13:05:17.270 11201 11264 I jxcore-log: 
,03-21 13:05:17.270 11201 11762 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1546, name: Sender)
03-21 13:05:17.270 11201 11760 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1545)
03-21 13:05:17.270 11201 11760 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1545)
03-21 13:05:17.270 11201 11264 I jxcore-log: ok 162 serverPort must be a number
03-21 13:05:17.270 11201 11264 I jxcore-log: 
,03-21 13:05:17.275 11201 11264 I jxcore-log: ok 163 forward connection must have clientPort == 0
03-21 13:05:17.275 11201 11264 I jxcore-log: 
,03-21 13:05:17.275 11201 11763 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1547, name: Receiver)
03-21 13:05:17.275 11201 11264 I jxcore-log: ok 164 forward connection must have serverPort == 0
03-21 13:05:17.275 11201 11264 I jxcore-log: 
,03-21 13:05:17.285 11201 11264 I jxcore-log: # setup
03-21 13:05:17.285 11201 11264 I jxcore-log: 
,03-21 13:05:17.520 11201 11762 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1546, thread name: Sender)
03-21 13:05:17.520 11201 11762 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 13:05:17.520 11201 11762 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 13:05:17.520 11201 11762 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1545
03-21 13:05:17.520 11201 11762 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1545)
03-21 13:05:17.520 11201 11762 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f5f3db9, channel: 6, state: CONNECTED
03-21 13:05:17.520 11201 11762 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1f5f3db9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1671d5fe, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e1fb15fmSocket: android.net.LocalSocket@2a03a7ac impl:android.net.LocalSocketImpl@1bacfc75 fd:FileDescriptor[92]
03-21 13:05:17.520 11201 11762 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a03a7ac impl:android.net.LocalSocketImpl@1bacfc75 fd:FileDescriptor[92]
03-21 13:05:17.520 11201 11763 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1547, thread name: Receiver): bt socket closed, read return: -1
03-21 13:05:17.520 11201 11763 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1547, name: Receiver)
,03-21 13:05:17.525  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 13:05:17.525  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:17.525  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:17.525  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:17.525 11201 11762 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f5f3db9, channel: 6, state: CLOSED
03-21 13:05:17.530 11201 11762 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f5f3db9, channel: 6, state: CLOSED
,03-21 13:05:17.530 11201 11762 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 13:05:17.530 11201 11762 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...,
03-21 13:05:17.530 11201 11762 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1547
03-21 13:05:17.530 11201 11762 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-21 13:05:17.530 11201 11762 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1546
,03-21 13:05:17.530 11201 11762 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1545)
,03-21 13:05:17.530 11201 11762 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1545),
03-21 13:05:17.530 11201 11762 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-21 13:05:17.535  5877  6023 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-21 13:05:17.535  5877  6023 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
03-21 13:05:17.540 11201 11762 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1546, name: Sender)
,03-21 13:05:17.545 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:17.545 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-21 13:05:17.545 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 13:05:17.545 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:05:17.550  5877  5976 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:17.550  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:17.550  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 14
03-21 13:05:17.550  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:17.550  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:17.550  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:17.550  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 13:05:17.550  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:17.555  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:17.555  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:17.555  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,03-21 13:05:17.555  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:17.555  5877  5968 D BtGatt.GattService: current time is 244619080486
03-21 13:05:17.555  5877  5968 D BtGatt.GattService: Batch record : [-1, -38, -126, -44, -127, 110, 1, -128, -80, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:17.555  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:17.555  5877  5968 D ScanRecord: parseFromBytes,
,03-21 13:05:17.560 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:17.560 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:17.560 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-21 13:05:17.560 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-21 13:05:17.560 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-21 13:05:17.560 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-21 13:05:17.565 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:17.565 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-21 13:05:17.565 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-21 13:05:17.575 11201 11264 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 13:05:17.575 11201 11264 I jxcore-log: 
,03-21 13:05:17.575 11201 11264 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 13:05:17.575 11201 11264 I jxcore-log: 
,03-21 13:05:17.580 11201 11264 I jxcore-log: ok 165 Should be able to call stopListeningForAdvertisments in teardown
03-21 13:05:17.580 11201 11264 I jxcore-log: 
,03-21 13:05:17.580 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:17.580 11201 11264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:17.580 11201 11264 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1544)
03-21 13:05:17.580 11201 11264 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1544)
,03-21 13:05:17.580 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3511540a, channel: 7, state: CONNECTED
,03-21 13:05:17.580 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3511540a, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29b8047b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6d99298mSocket: android.net.LocalSocket@2eddeaf1 impl:android.net.LocalSocketImpl@3978a6d6 fd:FileDescriptor[115]
03-21 13:05:17.580 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2eddeaf1 impl:android.net.LocalSocketImpl@3978a6d6 fd:FileDescriptor[115]
,03-21 13:05:17.585 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3511540a, channel: 7, state: CLOSED
,03-21 13:05:17.585 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3511540a, channel: 7, state: CLOSED
03-21 13:05:17.585 11201 11264 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-21 13:05:17.585 11201 11264 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1544)
03-21 13:05:17.585 11201 11264 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1544)
,03-21 13:05:17.585 11201 11759 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1544)
,03-21 13:05:17.585 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-21 13:05:17.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 13:05:17.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 13:05:17.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 13:05:17.590 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ab86d57, channel: 6, state: LISTENING
,03-21 13:05:17.590 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ab86d57, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35c260b2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a214044mSocket: android.net.LocalSocket@1a55452d impl:android.net.LocalSocketImpl@1f305a62 fd:FileDescriptor[116]
,03-21 13:05:17.590 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a55452d impl:android.net.LocalSocketImpl@1f305a62 fd:FileDescriptor[116]
,03-21 13:05:17.590 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-21 13:05:17.590 11201 11661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:05:17.590 11201 11661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-21 13:05:17.590 11201 11661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:05:17.595 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:05:17.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 13:05:17.595 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:05:17.595 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 13:05:17.595 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 13:05:17.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:17.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:17.595 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-21 13:05:17.600 11201 11264 D BluetoothLeScanner: could not find callback wrapper,
03-21 13:05:17.600 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:17.600 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 13:05:17.600  5877  5972 D BtGatt.AdvertiseManager: message : 1,
,03-21 13:05:17.600  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7,
,03-21 13:05:17.600  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:17.605  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:17.605  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:17.605  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:05:17.605  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:17.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:17.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:17.610 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:17.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:05:17.610 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:17.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-21 13:05:17.610 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:17.610 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 13:05:17.615 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:05:17.615 11201 11264 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 13:05:17.615 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:17.615 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:17.615 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 13:05:17.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:17.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:17.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 13:05:17.615 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:05:17.615 11201 11264 I jxcore-log: 
03-21 13:05:17.620 11201 11264 I jxcore-log: ok 166 Should be able to call stopAdvertisingAndListening in teardown
03-21 13:05:17.620 11201 11264 I jxcore-log: 
,03-21 13:05:17.625 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:17.625 11201 11264 I jxcore-log: # 38. Can shift large amounts of data
03-21 13:05:17.625 11201 11264 I jxcore-log: 
,03-21 13:05:17.630 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 13:05:17.630 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:17.630 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:17.635 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:17.635 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:17.635 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:17.635 11201 11264 I jxcore-log: 
,03-21 13:05:17.635 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:17.635 11201 11264 I jxcore-log: 
,03-21 13:05:18.060  5877  6023 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-21 13:05:18.560 11201 11264 I jxcore-log: # teardown
03-21 13:05:18.560 11201 11264 I jxcore-log: 
,03-21 13:05:18.760  3369  4389 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:05:18.765  3369  4389 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:05:18.765  3369  4389 D BatteryService: online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
03-21 13:05:18.765  3369  4389 D BatteryService: stay LED for fully charged
03-21 13:05:18.765  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:05:18.775 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 44789, start advertisements: true
03-21 13:05:18.775 11201 11264 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectabl,e: false
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:18.775 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:18.775 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:05:18.775 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:05:18.775 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:18.780 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:18.780  5877  5890 D BtGatt.GattService: registerClient() - UUID=0f3f608d-2847-4388-a235-a01abee83603
,03-21 13:05:18.785  3369  3369 I MotionRecognitionService: Plugged
,03-21 13:05:18.785  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:05:18.790  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:05:18.790  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:05:18.790  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 13:05:18.790  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:05:18.790  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:05:18.795  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 13:05:18.795  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:05:18.810  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:05:18.810  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:18.810  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:18.815  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:05:18.820  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=0f3f608d-2847-4388-a235-a01abee83603, clientIf=6
,03-21 13:05:18.820 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:18.820  5877  9150 D BtGatt.GattService: start scan with filters
,03-21 13:05:18.835  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 13
,03-21 13:05:18.835 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 13:05:18.835 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:18.835 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:18.835  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:18.835 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:18.835  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:18.835 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:18.835  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:18.835 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:18.835 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 13:05:18.835 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:18.835 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:18.835 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:18.835 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:18.835 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:18.840  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:18.840  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:18.840  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:18.840  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:18.840  5877  5973 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
03-21 13:05:18.840  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:18.840  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:18.840  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:18.840  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:18.845  5877  5890 D BtGatt.GattService: registerClient() - UUID=66361156-1fed-4a2a-bb6b-8317891f6f22
,03-21 13:05:18.845  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:18.845  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:18.845  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 13:05:18.845  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:18.885  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=66361156-1fed-4a2a-bb6b-8317891f6f22, clientIf=7,
03-21 13:05:18.885 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:18.910  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 10
,03-21 13:05:18.910  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:18.910  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
,03-21 13:05:18.910  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:18.915  5877  5972 D BtGatt.AdvertiseManager: starting advertising
03-21 13:05:18.915  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 13:05:18.920  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:18.920  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:18.925  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:18.925  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:18.930  3369  3582 I PowerManagerService: [PWL] Off : 180s ago
03-21 13:05:18.925  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 13:05:18.930  3369  3582 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-21 13:05:18.925 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:18.930  3369  3582 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-21 13:05:18.925 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:05:18.930  3369  3582 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5877, ws=null) (elapsedTime=11385)
03-21 13:05:18.925 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:18.925 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:18.925 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 13:05:18.925 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:18.930 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 13:05:18.930 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 13:05:18.930 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 13:05:18.930 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 13:05:18.930 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:18.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:18.930 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 13:05:18.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:18.930 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:18.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:05:18.930 11201 11201 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:18.930 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,03-21 13:05:18.930 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:05:18.930 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 13:05:18.930 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 13:05:18.930 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:18.930 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:18.930 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:18.930 11201 11264 I jxcore-log: 
,03-21 13:05:18.940 11201 11264 I jxcore-log: ok 167 Can call startUpdateAdvertisingAndListening without error,
03-21 13:05:18.940 11201 11264 I jxcore-log: 
,03-21 13:05:18.945 11201 11789 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:05:18.945 11201 11789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:18.950 11201 11789 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
03-21 13:05:18.950 11201 11789 D BluetoothSocket: bindListen(), new LocalSocket ,
03-21 13:05:18.950 11201 11789 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:18.950 11201 11789 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fbdbaae
03-21 13:05:18.950 11201 11789 D BluetoothSocket: channel: 6
03-21 13:05:18.950 11201 11789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:18.955 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 44789, start advertisements: false,
,03-21 13:05:18.955 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:18.955 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-21 13:05:18.955 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:18.955 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:18.960 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:18.960 11201 11264 I jxcore-log: 
,03-21 13:05:18.965 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:18.965 11201 11264 I jxcore-log: 
,03-21 13:05:18.965 11201 11264 I jxcore-log: ok 168 Can call startListeningForAdvertisements without error
03-21 13:05:18.965 11201 11264 I jxcore-log: 
,03-21 13:05:19.285  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:12), CUR = 66, LCD = 0
,03-21 13:05:19.845  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:19.860  5877  5877 D BtGatt.ScanManager: awakened up at time 246921
,03-21 13:05:19.870  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:19.875  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:19.875  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:19.875  5877  5968 D BtGatt.GattService: current time is 246936491153
03-21 13:05:19.875  5877  5968 D BtGatt.GattService: Batch record : [-36, -55, 12, -68, 47, 83, 1, -128, -71, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:19.875  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:19.875  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:19.875  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=53:2F:BC:0C:C9:DC, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=246636649944}
03-21 13:05:19.875  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:19.885 11201 11793 D ScanRecord: parseFromBytes,
03-21 13:05:19.885 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 13:05:19.885 11201 11201 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 13:05:19.900 11201 11264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-21 13:05:19.900 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:19.900 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,03-21 13:05:19.900 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-21 13:05:19.905 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-21 13:05:19.905 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
,03-21 13:05:19.905 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-21 13:05:19.905 11201 11264 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-21 13:05:19.905 11201 11798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1550)
,03-21 13:05:19.910 11201 11798 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-21 13:05:19.910 11201 11798 D BluetoothSocket: connect(): myUserId = 0
03-21 13:05:19.910 11201 11798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:19.910  5877  5888 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 13:05:19.915 11201 11798 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,03-21 13:05:20.245  5877  6023 W bt-sdp  : process_service_search_attr_rsp
,03-21 13:05:20.810  5877  6023 W bt-btif : new conn_srvc id:26, app_id:1
03-21 13:05:20.810  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-21 13:05:20.810  5877  6023 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-21 13:05:20.820  5877  5976 E BluetoothRemoteDevices: setRfcommConnected true
,03-21 13:05:20.830 11201 11798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1550)
03-21 13:05:20.830 11201 11798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1550),
,03-21 13:05:20.840 11201 11798 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 13:05:20.845 11201 11798 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 13:05:20.845 11201 11798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1551)
03-21 13:05:20.850 11201 11798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1551)
03-21 13:05:20.850 11201 11798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1550)
,03-21 13:05:20.850  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:20.850 11201 11806 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1551)
03-21 13:05:20.850  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:20.850  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:20.850  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:20.895  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:20.895  5877  5877 D BtGatt.ScanManager: awakened up at time 247959
,03-21 13:05:20.900  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-21 13:05:20.900  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:20.905  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:20.905  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:20.905  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:20.905 11201 11806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1551)
03-21 13:05:20.910  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:20.910  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:20.910  5877  5968 D BtGatt.GattService: current time is 247970775694
03-21 13:05:20.910  5877  5968 D BtGatt.GattService: Batch record : [-36, -55, 12, -68, 47, 83, 1, -128, -71, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:20.910  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:20.910  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:05:20.910  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=53:2F:BC:0C:C9:DC, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-71, mTimestampNanos=247821183778}
,03-21 13:05:20.910  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:20.910 11201 11213 D ScanRecord: parseFromBytes,
03-21 13:05:20.915 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 13:05:20.920 11201 11806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:20.920 11201 11806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1550)
,03-21 13:05:20.920 11201 11806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1550)
,03-21 13:05:20.920 11201 11806 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1551),
03-21 13:05:20.925 11201 11201 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:20.925 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:20.925 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:20.925 11201 11201 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-21 13:05:20.930 11201 11201 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-21 13:05:20.930 11201 11201 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-21 13:05:20.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-21 13:05:20.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:20.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:20.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:20.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:20.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:20.930 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 13:05:20.935  5877  5972 D BtGatt.AdvertiseManager: message : 1
,03-21 13:05:20.935  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:20.935  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 13:05:20.935  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:20.940  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:20.940  5877  5968 D BtGatt.GattService: Client app is not null!,
03-21 13:05:20.940  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:05:20.940 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 13:05:20.940 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:20.940 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false,
,03-21 13:05:20.940 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 13:05:20.945 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:20.945 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 13:05:20.945 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:20.945 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:20.945 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:20.950  5877  5976 D BtGatt.GattService: registerClient() - UUID=f448f36b-8bee-47e0-9830-8b1fbe4d81aa,
,03-21 13:05:20.990  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=f448f36b-8bee-47e0-9830-8b1fbe4d81aa, clientIf=7,
,03-21 13:05:20.990 11201 11793 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-21 13:05:21.025  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 11
,03-21 13:05:21.025  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:21.025  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:21.025  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:21.030  5877  5972 D BtGatt.AdvertiseManager: starting advertising
03-21 13:05:21.035  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:21.035  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:21.040  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:21.040  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:21.045  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 13:05:21.045  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:05:21.045 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:21.045  5877  8684 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:21.045  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:21.045  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 15
03-21 13:05:21.050  5877  5888 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:21.050 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:21.050 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:21.050 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:21.050 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:05:21.050 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:21.050 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:21.050  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:21.050  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.055  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:21.055  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:21.055  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.055  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:21.060  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:21.060  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:21.065  5877  8684 D BtGatt.GattService: registerClient() - UUID=b9d43458-14e3-4885-8ada-0a5c214c61d3,
,03-21 13:05:21.105  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=b9d43458-14e3-4885-8ada-0a5c214c61d3, clientIf=6
,03-21 13:05:21.105 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:21.105  5877  5888 D BtGatt.GattService: start scan with filters
,03-21 13:05:21.115  5877  5888 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 14
,03-21 13:05:21.115 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-21 13:05:21.115  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:21.115  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:21.115  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:21.115 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 13:05:21.120  5877  5972 D BtGatt.AdvertiseManager: message : 1
,03-21 13:05:21.120  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:21.120  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 13:05:21.120  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:21.120  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.120  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:21.120  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 13:05:21.120  5877  5973 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-21 13:05:21.120  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:21.120  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:21.120  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.120  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:21.120  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:21.120  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:21.120  5877  5968 D BtGatt.GattService: Client app is not null!
,03-21 13:05:21.120  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:21.125 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:21.125 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
,03-21 13:05:21.125 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 13:05:21.125 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:21.125 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:21.125 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:21.125 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:21.125 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:21.125 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:21.125  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 13:05:21.125  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:21.130  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 13:05:21.130  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.130  5877  5890 D BtGatt.GattService: registerClient() - UUID=7335d78c-a5af-46e3-ab6f-0298bad9893f
,03-21 13:05:21.170  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=7335d78c-a5af-46e3-ab6f-0298bad9893f, clientIf=7
,03-21 13:05:21.170 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:21.195  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 12
03-21 13:05:21.205  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:05:21.205  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:21.205  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
03-21 13:05:21.210  5877  5972 D BtGatt.AdvertiseManager: starting advertising
03-21 13:05:21.210  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 13:05:21.215  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-21 13:05:21.215  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
03-21 13:05:21.215  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:21.220  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:21.220  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-21 13:05:21.220 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:21.220  5877  5888 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:21.225  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:21.225  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:21.225  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 3
03-21 13:05:21.225 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:21.230  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:21.230  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.230 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:21.230 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:21.230 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-21 13:05:21.230 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:21.230 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:21.230  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:21.230  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:21.230  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.230  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:21.230  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:21.230  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:21.235  5877  5976 D BtGatt.GattService: registerClient() - UUID=d173db13-d9bd-4771-b1c7-fae0162c97d4
,03-21 13:05:21.275  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=d173db13-d9bd-4771-b1c7-fae0162c97d4, clientIf=6
,03-21 13:05:21.275 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:05:21.280  5877  5890 D BtGatt.GattService: start scan with filters
,03-21 13:05:21.295  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 15
,03-21 13:05:21.300  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:21.300  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:21.300  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:21.305  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:21.305  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:21.310  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:21.310  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:21.310  5877  5973 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-21 13:05:21.310  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:21.310  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:21.310  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:21.310  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:21.315  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:21.315  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:21.315  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
,03-21 13:05:21.315  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 13:05:21.325 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0,
03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:21.325 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:21.330  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:05:21.330  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-21 13:05:21.330  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:21.330  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:21.330  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:21.330  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:05:21.335  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:21.335 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:21.335 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 13:05:21.335 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 13:05:21.335 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:21.335 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:21.335 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 13:05:21.335 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:21.335 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:21.335 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:21.340  5877  9150 D BtGatt.GattService: registerClient() - UUID=82e9a8c2-e1cc-4af0-8079-8fbf0a30ed8e
,03-21 13:05:21.380  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=82e9a8c2-e1cc-4af0-8079-8fbf0a30ed8e, clientIf=7
,03-21 13:05:21.380 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:21.400  5877  5976 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 13
,03-21 13:05:21.400  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:21.405  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:21.405  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:21.410  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:21.410  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:21.415  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:21.420  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:21.425  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:21.425  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 13:05:21.425  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-21 13:05:21.425 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:21.430  5877  5888 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:21.430  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:21.430  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 4
,03-21 13:05:21.430  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:21.430  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.430  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:21.430  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 13:05:21.430  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:21.430  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.435  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:21.435 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 13:05:21.435 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-21 13:05:21.435 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:21.435 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:21.435 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:21.435 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:21.435  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
03-21 13:05:21.435  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.445  5877  5888 D BtGatt.GattService: registerClient() - UUID=d738c282-6f66-402e-9a87-42062064e18b
,03-21 13:05:21.485  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=d738c282-6f66-402e-9a87-42062064e18b, clientIf=6
03-21 13:05:21.485 11201 11793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 13:05:21.490  5877  5890 D BtGatt.GattService: start scan with filters,
,03-21 13:05:21.500  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 16
,03-21 13:05:21.500 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 13:05:21.500 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,03-21 13:05:21.500  5877  5973 D BtGatt.ScanManager: handling starting scan,
,03-21 13:05:21.500  5877  5973 D BtGatt.ScanManager: isFilteringSupported,
,03-21 13:05:21.500  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:21.500 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 13:05:21.500 11201 11201 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-21 13:05:21.500 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:21.500 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:21.500 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:21.500 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:21.500 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:21.500  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:21.500  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.500  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:21.500  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:21.500  5877  5973 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-21 13:05:21.500 11201 11822 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1552)
03-21 13:05:21.505 11201 11822 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56646
03-21 13:05:21.505 11201 11822 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-21 13:05:21.505 11201 11822 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 56646 (peer ID: F8:95:C7:87:3C:51)
03-21 13:05:21.505  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:21.505  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.505  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 13:05:21.505  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:21.505 11201 11264 I jxcore-log: INFO testThaliMobileNative: 
03-21 13:05:21.505 11201 11264 I jxcore-log: 
03-21 13:05:21.505  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:21.505  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.505 11201 11264 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-21 13:05:21.505 11201 11264 I jxcore-log: 
03-21 13:05:21.505  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:21.505  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:21.505 11201 11822 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-21 13:05:21.515 11201 11822 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 56646
03-21 13:05:21.515 11201 11822 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-21 13:05:21.515 11201 11822 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:21.515 11201 11822 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 13:05:21.515 11201 11825 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1553, name: Sender)
03-21 13:05:21.515 11201 11822 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1552)
03-21 13:05:21.515 11201 11822 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1552)
,03-21 13:05:21.520 11201 11826 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1554, name: Receiver)
,03-21 13:05:21.520 11201 11264 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-21 13:05:21.520 11201 11264 I jxcore-log: 
,03-21 13:05:21.520  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:21.520  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:21.520  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:21.520  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:21.680  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 13:05:21.680  5877  6023 D IOP_DB_BT: db_query: result 1,
,03-21 13:05:21.680  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:21.680  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:21.700 11201 11264 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 13:05:21.700 11201 11264 I jxcore-log: 
,03-21 13:05:21.750  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:21.755  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:21.755  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:21.755  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:21.780 11201 11264 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 13:05:21.780 11201 11264 I jxcore-log: 
,03-21 13:05:21.885  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:21.885  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:21.885  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:21.885  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:21.900 11201 11264 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 13:05:21.900 11201 11264 I jxcore-log: 
,03-21 13:05:22.020  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.020  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.020  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.020  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:22.035 11201 11264 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 13:05:22.035 11201 11264 I jxcore-log: 
,03-21 13:05:22.080  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:22.080  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.080  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.080  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.085  5877  6023 W bt-btif : new conn_srvc id:26, app_id:255
03-21 13:05:22.085  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-21 13:05:22.085  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 13:05:22.085  5877  6023 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-21 13:05:22.085 11201 11789 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@35aed3ba
,03-21 13:05:22.090  5877  9150 E BluetoothRemoteDevices: setRfcommConnected true,
03-21 13:05:22.090 11201 11789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-21 13:05:22.095 11201 11789 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-21 13:05:22.100 11201 11789 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-21 13:05:22.100 11201 11789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1555)
03-21 13:05:22.100 11201 11789 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bcf026b, channel: 6, state: LISTENING
,03-21 13:05:22.100 11201 11789 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1bcf026b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1fbdbaae, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33a2d1c8mSocket: android.net.LocalSocket@20ee7261 impl:android.net.LocalSocketImpl@4667186 fd:FileDescriptor[93]
03-21 13:05:22.100 11201 11789 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20ee7261 impl:android.net.LocalSocketImpl@4667186 fd:FileDescriptor[93]
,03-21 13:05:22.105 11201 11264 I jxcore-log: INFO testThaliMobileNative: forwardData,
03-21 13:05:22.105 11201 11264 I jxcore-log: 
,03-21 13:05:22.110 11201 11789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-21 13:05:22.110 11201 11789 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 13:05:22.110 11201 11789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:22.115 11201 11830 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1555)
,03-21 13:05:22.120 11201 11789 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[119]},
03-21 13:05:22.120 11201 11789 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:05:22.120 11201 11789 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:22.120 11201 11789 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29d95a47,
03-21 13:05:22.120 11201 11789 D BluetoothSocket: channel: 6
03-21 13:05:22.120 11201 11789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-21 13:05:22.120 11201 11264 I jxcore-log: ok 169 received should match sent forward
03-21 13:05:22.120 11201 11264 I jxcore-log: 
,03-21 13:05:22.135 11201 11264 I jxcore-log: # setup
03-21 13:05:22.135 11201 11264 I jxcore-log: 
,03-21 13:05:22.505  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:22.520  5877  5877 D BtGatt.ScanManager: awakened up at time 249581
,03-21 13:05:22.525  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:22.530  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:22.530  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:22.530  5877  5968 D BtGatt.GattService: current time is 249593431403
03-21 13:05:22.530  5877  5968 D BtGatt.GattService: Batch record : [120, 64, -7, -35, -121, 82, 1, -128, -82, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:22.530  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-21 13:05:22.530  5877  5968 D ScanRecord: parseFromBytes,
03-21 13:05:22.535  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=52:87:DD:F9:40:78, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-82, mTimestampNanos=249043787903},
03-21 13:05:22.535  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:22.535 11201 11213 D ScanRecord: parseFromBytes
03-21 13:05:22.550 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:22.605  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.605 11201 11830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1555)
,03-21 13:05:22.610  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.610  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.610  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.610 11201 11830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:22.610 11201 11830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1555)
03-21 13:05:22.610 11201 11830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1555
03-21 13:05:22.610 11201 11830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1555)
03-21 13:05:22.610 11201 11830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:22.610 11201 11201 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:22.610 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:22.610  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.610 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 13:05:22.610 11201 11830 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1555)
,03-21 13:05:22.610  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.610  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.610  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:22.610 11201 11201 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 13:05:22.615 11201 11201 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 13:05:22.615 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 13:05:22.615 11201 11201 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-21 13:05:22.615 11201 11840 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1556)
,03-21 13:05:22.615  2873  3396 D EnterpriseController: netId is 0
03-21 13:05:22.615  2873  3396 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 13:05:22.620 11201 11840 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 44789
,03-21 13:05:22.620 11201 11840 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-21 13:05:22.620 11201 11840 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:22.620 11201 11840 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:22.620 11201 11840 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1556)
03-21 13:05:22.620 11201 11840 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1556)
,03-21 13:05:22.620 11201 11843 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1558, name: Receiver)
03-21 13:05:22.620 11201 11842 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1557, name: Sender)
,03-21 13:05:22.750  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.750  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.750  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.750  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:22.765  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.765  5877  6023 D IOP_DB_BT: db_query: result 1,
03-21 13:05:22.765  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.765  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:22.895  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.900  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.900  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.900  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.900  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.900  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.900  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.900  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:22.920  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.920  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.920  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.920  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:22.935  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 13:05:22.970  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.970  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.970  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.970  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:22.975  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:22.975  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:22.975  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 13:05:22.975  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:23.035  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:23.035  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:23.035  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:23.040  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:23.055  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:23.055  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:23.055  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:23.055  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:23.280  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:23.285  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:23.285  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:23.285  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:23.285  5877  6128 W bt-btif : invalid rfc slot id: 14
03-21 13:05:23.285 11201 11826 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1554, thread name: Receiver): bt socket closed, read return: -1
03-21 13:05:23.285 11201 11826 E io.jxcore.node.OutgoingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-21 13:05:23.285 11201 11826 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-21 13:05:23.285 11201 11826 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
03-21 13:05:23.285 11201 11826 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1552)
03-21 13:05:23.285 11201 11826 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1552)
03-21 13:05:23.285 11201 11826 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30a82012, channel: 7, state: CONNECTED
03-21 13:05:23.285 11201 11826 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30a82012, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@114753e3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b8011e0mSocket: android.net.LocalSocket@2e3a0c99 impl:android.net.LocalSocketImpl@35e42b5e fd:FileDescriptor[115]
03-21 13:05:23.285 11201 11826 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e3a0c99 impl:android.net.LocalSocketImpl@35e42b5e fd:FileDescriptor[115]
,03-21 13:05:23.300 11201 11826 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30a82012, channel: 7, state: CLOSED,
03-21 13:05:23.300 11201 11826 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30a82012, channel: 7, state: CLOSED
03-21 13:05:23.300 11201 11826 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 13:05:23.300 11201 11826 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-21 13:05:23.300 11201 11826 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1554
03-21 13:05:23.300 11201 11826 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-21 13:05:23.300 11201 11826 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1553
03-21 13:05:23.300 11201 11826 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1552)
03-21 13:05:23.300 11201 11826 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1552)
03-21 13:05:23.305 11201 11826 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-21 13:05:23.305 11201 11826 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1554, name: Receiver),
03-21 13:05:23.305 11201 11825 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1553, thread name: Sender): Socket closed
03-21 13:05:23.305 11201 11825 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1553, name: Sender)
,03-21 13:05:23.465 11201 11842 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1557, thread name: Sender)
03-21 13:05:23.465 11201 11842 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 13:05:23.465 11201 11842 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 13:05:23.465 11201 11842 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1556
03-21 13:05:23.465 11201 11842 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1556)
03-21 13:05:23.465 11201 11842 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20114b3f, channel: 6, state: CONNECTED
03-21 13:05:23.465 11201 11842 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@20114b3f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e046c0c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e15d955mSocket: android.net.LocalSocket@4439f6a impl:android.net.LocalSocketImpl@21595c5b fd:FileDescriptor[118]
03-21 13:05:23.465 11201 11842 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4439f6a impl:android.net.LocalSocketImpl@21595c5b fd:FileDescriptor[118]
03-21 13:05:23.465 11201 11843 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1558, thread name: Receiver): bt socket closed, read return: -1
03-21 13:05:23.465 11201 11843 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1558, name: Receiver)
,03-21 13:05:23.475 11201 11842 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20114b3f, channel: 6, state: CLOSED,
03-21 13:05:23.475 11201 11842 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@20114b3f, channel: 6, state: CLOSED
03-21 13:05:23.475 11201 11842 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 13:05:23.475 11201 11842 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-21 13:05:23.475 11201 11842 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1558,
03-21 13:05:23.475 11201 11842 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-21 13:05:23.475 11201 11842 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1557
03-21 13:05:23.475 11201 11842 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1556)
03-21 13:05:23.475 11201 11842 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1556)
03-21 13:05:23.475 11201 11842 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-21 13:05:23.480 11201 11842 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1557, name: Sender),
,03-21 13:05:23.485 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-21 13:05:23.485 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 13:05:23.485 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 13:05:23.485 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:05:23.490  5877  5890 D BtGatt.GattService: stopScan() - queue size =1,
,03-21 13:05:23.490  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:23.490  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 5
03-21 13:05:23.490  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:23.490  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:23.490  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:23.495  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:23.495  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 13:05:23.495  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:23.495  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:23.495  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:23.500  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 13:05:23.500 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:23.500 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,03-21 13:05:23.500 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:05:23.500 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 13:05:23.500 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-21 13:05:23.500 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:23.505 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:23.505 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 13:05:23.505 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,03-21 13:05:23.505 11201 11264 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 13:05:23.505 11201 11264 I jxcore-log: 
,03-21 13:05:23.510 11201 11264 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 13:05:23.510 11201 11264 I jxcore-log: 
,03-21 13:05:23.510 11201 11264 I jxcore-log: ok 170 Should be able to call stopListeningForAdvertisments in teardown
03-21 13:05:23.510 11201 11264 I jxcore-log: 
,03-21 13:05:23.515 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:23.515 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-21 13:05:23.515 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 13:05:23.515 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 13:05:23.515 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 13:05:23.515 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36923cf8, channel: 6, state: LISTENING
03-21 13:05:23.515 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36923cf8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29d95a47, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2aa7b5d1mSocket: android.net.LocalSocket@33744836 impl:android.net.LocalSocketImpl@26476337 fd:FileDescriptor[119]
03-21 13:05:23.515 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33744836 impl:android.net.LocalSocketImpl@26476337 fd:FileDescriptor[119]
,03-21 13:05:23.515 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 13:05:23.520 11201 11789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:05:23.520 11201 11789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 13:05:23.520 11201 11789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:05:23.520 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:05:23.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 13:05:23.520 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:05:23.520 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 13:05:23.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 13:05:23.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:23.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:23.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 13:05:23.520 11201 11264 D BluetoothLeScanner: could not find callback wrapper
,03-21 13:05:23.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:23.525 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 13:05:23.525  5877  5972 D BtGatt.AdvertiseManager: message : 1,
03-21 13:05:23.525  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-21 13:05:23.525  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:23.525  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:23.530  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:23.530  5877  5968 D BtGatt.GattService: Client app is not null!
,03-21 13:05:23.535  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:05:23.535 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:23.535 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:23.535 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:23.535 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:05:23.535 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:23.535 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:23.535 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:23.535 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:05:23.535 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:05:23.535 11201 11264 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 13:05:23.535 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:23.535 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:23.535 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:23.535 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:23.535 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:23.535 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:05:23.540 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true},
03-21 13:05:23.540 11201 11264 I jxcore-log: 
03-21 13:05:23.540 11201 11264 I jxcore-log: ok 171 Should be able to call stopAdvertisingAndListening in teardown
03-21 13:05:23.540 11201 11264 I jxcore-log: 
03-21 13:05:23.540 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:23.545 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 13:05:23.550 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:23.550 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:23.550 11201 11264 I jxcore-log: # 39. #startListeningForAdvertisements should fail if start not called
03-21 13:05:23.550 11201 11264 I jxcore-log: 
,03-21 13:05:23.550 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 13:05:23.550 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:23.550  5877  6023 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
03-21 13:05:23.550  5877  6023 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-21 13:05:23.555 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:23.555 11201 11264 I jxcore-log: 
,03-21 13:05:23.555 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:23.555 11201 11264 I jxcore-log: 
,03-21 13:05:23.770 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:23.770 11201 11264 I jxcore-log: 
,03-21 13:05:23.775 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:23.775 11201 11264 I jxcore-log: 
,03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:23.785 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:23.785 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:23.790 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:23.790 11201 11264 I jxcore-log: 
,03-21 13:05:23.795 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:23.795 11201 11264 I jxcore-log: 
,03-21 13:05:23.800 11201 11264 I jxcore-log: # teardown
03-21 13:05:23.800 11201 11264 I jxcore-log: 
,03-21 13:05:23.800 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:23.800 11201 11264 I jxcore-log: 
,03-21 13:05:24.110 11201 11264 I jxcore-log: ok 172 specific error should be returned
03-21 13:05:24.110 11201 11264 I jxcore-log: 
,03-21 13:05:24.115 11201 11264 I jxcore-log: # setup
03-21 13:05:24.115 11201 11264 I jxcore-log: 
,03-21 13:05:24.250 11201 11264 I jxcore-log: # 40. #startUpdateAdvertisingAndListening should fail if start not called
03-21 13:05:24.250 11201 11264 I jxcore-log: 
,03-21 13:05:24.345 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:24.345 11201 11264 I jxcore-log: 
,03-21 13:05:24.345 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:24.345 11201 11264 I jxcore-log: 
,03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:24.360 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:24.365 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:24.365 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:24.365 11201 11264 I jxcore-log: 
,03-21 13:05:24.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:24.370 11201 11264 I jxcore-log: 
,03-21 13:05:24.375 11201 11264 I jxcore-log: # teardown
03-21 13:05:24.375 11201 11264 I jxcore-log: 
,03-21 13:05:24.380 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:24.380 11201 11264 I jxcore-log: 
,03-21 13:05:24.525 11201 11264 I jxcore-log: ok 173 specific error should be returned
03-21 13:05:24.525 11201 11264 I jxcore-log: 
,03-21 13:05:24.530 11201 11264 I jxcore-log: # setup
03-21 13:05:24.530 11201 11264 I jxcore-log: 
,03-21 13:05:24.645 11201 11264 I jxcore-log: # 41. should be able to call #stopListeningForAdvertisements many times
03-21 13:05:24.645 11201 11264 I jxcore-log: 
,03-21 13:05:24.745 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:24.745 11201 11264 I jxcore-log: 
,03-21 13:05:24.750 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:24.750 11201 11264 I jxcore-log: 
,03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:24.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:24.760 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:24.760 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:24.760 11201 11264 I jxcore-log: 
,03-21 13:05:24.765 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:24.765 11201 11264 I jxcore-log: 
,03-21 13:05:24.770 11201 11264 I jxcore-log: # teardown
03-21 13:05:24.770 11201 11264 I jxcore-log: 
,03-21 13:05:24.770 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:24.770 11201 11264 I jxcore-log: 
,03-21 13:05:24.875 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:05:24.875 11201 11264 I jxcore-log: 
,03-21 13:05:24.880 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 55103
03-21 13:05:24.880 11201 11264 I jxcore-log: 
,03-21 13:05:24.885 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:24.885 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:05:24.885 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:24.895 11201 11264 I jxcore-log: ok 174 no errors
03-21 13:05:24.895 11201 11264 I jxcore-log: 
,03-21 13:05:24.900 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:24.905 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:05:24.910 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:24.910 11201 11264 I jxcore-log: ok 175 still no errors
03-21 13:05:24.910 11201 11264 I jxcore-log: 
,03-21 13:05:24.930 11201 11264 I jxcore-log: # setup
03-21 13:05:24.930 11201 11264 I jxcore-log: 
,03-21 13:05:24.930  3369  3554 W ProcessCpuTracker: Skipping unknown process pid 11875
,03-21 13:05:24.995 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 13:05:24.995 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:24.995 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:25.000 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:25.005 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:05:25.005 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:25.020 11201 11264 I jxcore-log: # 42. should be able to call #startListeningForAdvertisements many times
03-21 13:05:25.020 11201 11264 I jxcore-log: 
,03-21 13:05:25.155 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:25.155 11201 11264 I jxcore-log: 
,03-21 13:05:25.165 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:25.165 11201 11264 I jxcore-log: 
,03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:25.170 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:25.175 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:25.180 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:25.180 11201 11264 I jxcore-log: 
,03-21 13:05:25.185 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:25.185 11201 11264 I jxcore-log: 
,03-21 13:05:25.185 11201 11264 I jxcore-log: # teardown
03-21 13:05:25.185 11201 11264 I jxcore-log: 
,03-21 13:05:25.190 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:25.190 11201 11264 I jxcore-log: 
,03-21 13:05:25.285 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:05:25.285 11201 11264 I jxcore-log: 
,03-21 13:05:25.285 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 41012
03-21 13:05:25.285 11201 11264 I jxcore-log: 
,03-21 13:05:25.290 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 44789, start advertisements: false
03-21 13:05:25.290 11201 11264 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:25.290 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:25.295 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectab,le: false
03-21 13:05:25.295 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:25.295 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:25.295 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:25.295 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 13:05:25.295 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:25.295 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:25.295 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:25.300  5877  5976 D BtGatt.GattService: registerClient() - UUID=28fb0d09-cc30-41a6-9567-65eb6b536ca7
,03-21 13:05:25.340  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=28fb0d09-cc30-41a6-9567-65eb6b536ca7, clientIf=6
,03-21 13:05:25.340 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:25.340  5877  8684 D BtGatt.GattService: start scan with filters
,03-21 13:05:25.360  5877  8684 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 17
,03-21 13:05:25.360 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 13:05:25.360 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:25.360 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-21 13:05:25.360 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:25.360 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:25.360 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:05:25.360  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:25.360  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:25.360 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 13:05:25.360  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:25.365  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:25.365  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:25.365  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:25.365  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:25.365  5877  5973 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-21 13:05:25.365 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:25.365 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:25.365 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:25.365 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:25.365  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:25.365 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:25.365  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:25.365  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:25.365 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:25.365  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:25.370  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 13:05:25.370  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:25.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:25.370 11201 11264 I jxcore-log: 
,03-21 13:05:25.370  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 13:05:25.370  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:25.370 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:25.370 11201 11264 I jxcore-log: 
,03-21 13:05:25.375 11201 11264 I jxcore-log: ok 176 no errors
03-21 13:05:25.375 11201 11264 I jxcore-log: 
,03-21 13:05:25.380 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 44789, start advertisements: false
,03-21 13:05:25.380 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:25.380 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:25.380 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 13:05:25.380 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:25.385 11201 11264 I jxcore-log: ok 177 still no errors
03-21 13:05:25.385 11201 11264 I jxcore-log: 
,03-21 13:05:25.390 11201 11264 I jxcore-log: # setup
03-21 13:05:25.390 11201 11264 I jxcore-log: 
,03-21 13:05:25.560 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:25.565 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:25.565 11201 11264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 13:05:25.565 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
03-21 13:05:25.565 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 13:05:25.565 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,03-21 13:05:25.570 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 13:05:25.570 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 13:05:25.570 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:05:25.575  5877  5888 D BtGatt.GattService: stopScan() - queue size =1,
03-21 13:05:25.575  5877  5973 D BtGatt.ScanManager: filter size is 1
,03-21 13:05:25.575  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 6,
,03-21 13:05:25.575  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-21 13:05:25.575  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:25.575  5877  5973 D BtGatt.ScanManager: stopping BLe Batch,
,03-21 13:05:25.580  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:25.580  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 13:05:25.580  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:25.580  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
,03-21 13:05:25.580  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 13:05:25.585  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 13:05:25.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 13:05:25.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:25.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 13:05:25.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 13:05:25.590 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 13:05:25.590 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-21 13:05:25.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 13:05:25.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:25.595 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:05:25.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-21 13:05:25.595 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:25.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:25.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:25.595 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
03-21 13:05:25.605 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 13:05:25.610 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:25.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:25.615 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:25.615 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:25.615 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:25.615 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:25.615 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:25.615 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:25.615 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:05:25.615 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-21 13:05:25.625 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-21 13:05:25.625 11201 11264 I jxcore-log: 
,03-21 13:05:25.625 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:25.625 11201 11264 I jxcore-log: 
,03-21 13:05:25.640 11201 11264 I jxcore-log: # 43. should be able to call #startUpdateAdvertisingAndListening many times
03-21 13:05:25.640 11201 11264 I jxcore-log: 
,03-21 13:05:25.660  3369  3866 E Watchdog: !@Sync 8 [03-21 13:05:25.667]
,03-21 13:05:25.825 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:25.825 11201 11264 I jxcore-log: 
,03-21 13:05:25.830 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:25.830 11201 11264 I jxcore-log: 
,03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:25.835 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:25.840 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:25.850 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:25.850 11201 11264 I jxcore-log: 
,03-21 13:05:25.850 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:25.850 11201 11264 I jxcore-log: 
,03-21 13:05:25.855 11201 11264 I jxcore-log: # teardown
03-21 13:05:25.855 11201 11264 I jxcore-log: 
,03-21 13:05:25.860 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:25.860 11201 11264 I jxcore-log: 
,03-21 13:05:25.950 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:05:25.950 11201 11264 I jxcore-log: 
,03-21 13:05:25.960 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 57643
03-21 13:05:25.960 11201 11264 I jxcore-log: 
,03-21 13:05:25.965 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 57643, start advertisements: true
,03-21 13:05:25.965 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:25.965 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:25.965 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:25.970 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:05:25.970 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:25.970 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:25.970 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:25.975  5877  5976 D BtGatt.GattService: registerClient() - UUID=010a7a47-1231-415a-b861-2f828137a333
,03-21 13:05:26.015  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=010a7a47-1231-415a-b861-2f828137a333, clientIf=6
,03-21 13:05:26.015 11201 11793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:26.015  5877  8684 D BtGatt.GattService: start scan with filters
,03-21 13:05:26.030  5877  8684 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 18
,03-21 13:05:26.030 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:26.030 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:26.030 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:26.030 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:26.030  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:26.030 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:26.030  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:26.030  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:26.030 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:26.030 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:26.030 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:26.030 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:26.030 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:26.030 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:26.030 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:26.030  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:26.030  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:26.030  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:26.030  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:26.030  5877  5973 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,03-21 13:05:26.035  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-21 13:05:26.035  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:26.035  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:26.035  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:26.035  5877  8684 D BtGatt.GattService: registerClient() - UUID=7dfecc36-fae4-4184-acee-a5951642ccb0
,03-21 13:05:26.035  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:26.035  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:26.040  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:26.040  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:26.075  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=7dfecc36-fae4-4184-acee-a5951642ccb0, clientIf=7
,03-21 13:05:26.075 11201 11211 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:26.110  5877  5888 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 14
,03-21 13:05:26.110  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:05:26.110  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:26.110  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:26.115  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:26.115  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:26.120  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:26.125  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:26.130  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 13:05:26.130  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:26.130  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:05:26.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:26.130 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 13:05:26.135 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:26.135 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:26.135 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 13:05:26.135 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:26.140 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 13:05:26.140 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 13:05:26.140 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 13:05:26.140 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-21 13:05:26.145 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:26.145 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:26.145 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:26.145 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:26.145 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:26.145 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:05:26.145 11201 11201 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:26.145 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-21 13:05:26.145 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:05:26.145 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-21 13:05:26.145 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 13:05:26.145 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 13:05:26.150 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK,
,03-21 13:05:26.150 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:26.150 11201 11264 I jxcore-log: 
,03-21 13:05:26.160 11201 11910 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:05:26.160 11201 11910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:26.165 11201 11910 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]},
03-21 13:05:26.165 11201 11910 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:05:26.165 11201 11910 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 13:05:26.165 11201 11910 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3aa0280e
03-21 13:05:26.170 11201 11910 D BluetoothSocket: channel: 6
03-21 13:05:26.170 11201 11910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:26.170 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:26.170 11201 11264 I jxcore-log: 
,03-21 13:05:26.170 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:26.170 11201 11264 I jxcore-log: 
,03-21 13:05:26.175 11201 11264 I jxcore-log: ok 178 no errors
03-21 13:05:26.175 11201 11264 I jxcore-log: 
,03-21 13:05:26.180 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 57643, start advertisements: true
,03-21 13:05:26.180 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:26.180 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:05:26.180 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:26.185 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:26.185 11201 11264 I jxcore-log: ok 179 still no errors
03-21 13:05:26.185 11201 11264 I jxcore-log: 
,03-21 13:05:26.195 11201 11264 I jxcore-log: # setup
03-21 13:05:26.195 11201 11264 I jxcore-log: 
,03-21 13:05:26.415 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:26.415 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-21 13:05:26.415 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 13:05:26.415 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 13:05:26.420 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 13:05:26.420 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@b39822f, channel: 6, state: LISTENING
,03-21 13:05:26.420 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@b39822f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3aa0280e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c80f03cmSocket: android.net.LocalSocket@680c1c5 impl:android.net.LocalSocketImpl@233ab71a fd:FileDescriptor[115],
,03-21 13:05:26.420 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@680c1c5 impl:android.net.LocalSocketImpl@233ab71a fd:FileDescriptor[115]
,03-21 13:05:26.425 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-21 13:05:26.425 11201 11910 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-21 13:05:26.425 11201 11910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 13:05:26.425 11201 11910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-21 13:05:26.425 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:05:26.430 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 13:05:26.430 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-21 13:05:26.430 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
,03-21 13:05:26.430 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,03-21 13:05:26.430 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:26.430 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:26.430 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 13:05:26.430 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 13:05:26.435  5877  8684 D BtGatt.GattService: stopScan() - queue size =1
03-21 13:05:26.435  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:26.435  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 7
03-21 13:05:26.440  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:26.440  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:26.440  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:26.440  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:26.440  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:26.445  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:26.445  5877  5888 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 13:05:26.445  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:26.445  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:26.445  5877  5968 D BtGatt.GattService: current time is 253509266612
03-21 13:05:26.445  5877  5968 D BtGatt.GattService: Batch record : [-116, 120, 60, -105, -76, 74, 1, -128, -71, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:26.445  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:26.445  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:26.450 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:26.450 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:26.450 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:05:26.450 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 13:05:26.450 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 13:05:26.450 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:26.450 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 13:05:26.450  5877  5972 D BtGatt.AdvertiseManager: message : 1,
03-21 13:05:26.450  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:26.450  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 13:05:26.455  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:26.455  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:26.455  5877  5968 D BtGatt.GattService: Client app is not null!
,03-21 13:05:26.455  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:26.455 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:26.460 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-21 13:05:26.460 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:26.460 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:05:26.460 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:26.460 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:26.460 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:26.460 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:05:26.460 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:05:26.460 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:26.460 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:26.460 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:26.460 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:26.460 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:26.460 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:05:26.460 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 13:05:26.460 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:05:26.460 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:26.465 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:26.470 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 13:05:26.470 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:26.470 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:26.470 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 13:05:26.475 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:26.475 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:26.475 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:05:26.475 11201 11264 I jxcore-log: 
,03-21 13:05:26.475 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:26.475 11201 11264 I jxcore-log: 
,03-21 13:05:26.475 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:26.475 11201 11264 I jxcore-log: 
,03-21 13:05:26.485 11201 11264 I jxcore-log: # 44. should be able to call #stopAdvertisingAndListening many times
03-21 13:05:26.485 11201 11264 I jxcore-log: 
,03-21 13:05:26.620 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-21 13:05:26.620 11201 11264 I jxcore-log: 
,03-21 13:05:26.630 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:26.630 11201 11264 I jxcore-log: 
,03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:26.640 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:26.645 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:26.650 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:26.650 11201 11264 I jxcore-log: 
,03-21 13:05:26.650 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:26.650 11201 11264 I jxcore-log: 
,03-21 13:05:26.655 11201 11264 I jxcore-log: # teardown
03-21 13:05:26.655 11201 11264 I jxcore-log: 
,03-21 13:05:26.660 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:26.660 11201 11264 I jxcore-log: 
,03-21 13:05:26.795 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:05:26.795 11201 11264 I jxcore-log: 
,03-21 13:05:26.800 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 49448
03-21 13:05:26.800 11201 11264 I jxcore-log: 
,03-21 13:05:26.805 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:26.805 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:26.805 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:26.810 11201 11264 I jxcore-log: ok 180 no errors
03-21 13:05:26.810 11201 11264 I jxcore-log: 
,03-21 13:05:26.815 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:26.815 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:26.815 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:26.820 11201 11264 I jxcore-log: ok 181 still no errors
03-21 13:05:26.820 11201 11264 I jxcore-log: 
,03-21 13:05:26.825 11201 11264 I jxcore-log: # setup
03-21 13:05:26.825 11201 11264 I jxcore-log: 
,03-21 13:05:26.925 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:26.925 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 13:05:26.930 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:26.930 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:26.935 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:05:26.935 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:26.950 11201 11264 I jxcore-log: # 45. can get the network status before starting
03-21 13:05:26.950 11201 11264 I jxcore-log: 
,03-21 13:05:27.050 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:27.050 11201 11264 I jxcore-log: 
,03-21 13:05:27.050 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:27.050 11201 11264 I jxcore-log: 
,03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:27.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:27.060 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:27.065 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:27.065 11201 11264 I jxcore-log: 
,03-21 13:05:27.065 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:27.065 11201 11264 I jxcore-log: 
,03-21 13:05:27.070 11201 11264 I jxcore-log: # teardown
03-21 13:05:27.070 11201 11264 I jxcore-log: 
,03-21 13:05:27.075 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:27.075 11201 11264 I jxcore-log: 
,03-21 13:05:27.980 11201 11264 I jxcore-log: ok 182 network status should have certain non-empty properties
03-21 13:05:27.980 11201 11264 I jxcore-log: 
,03-21 13:05:27.985 11201 11264 I jxcore-log: # setup
03-21 13:05:27.985 11201 11264 I jxcore-log: 
,03-21 13:05:28.145 11201 11264 I jxcore-log: # 46. error returned with bad router
03-21 13:05:28.145 11201 11264 I jxcore-log: 
,03-21 13:05:28.875  2894  4757 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 13:05:28.905  3369  3965 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 13:05:28.910  3369  3965 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:05:28.910  3369  3965 D BatteryService: online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
03-21 13:05:28.910  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 13:05:28.910  3369  3965 D BatteryService: stay LED for fully charged
,03-21 13:05:28.915  3369  3369 I MotionRecognitionService: Plugged,
03-21 13:05:28.915  3369  3369 D MotionRecognitionService:   cableConnection= 1,
,03-21 13:05:28.915  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0,
,03-21 13:05:28.915  3369  3369 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 13:05:28.930  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 13:05:28.930  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:05:28.930  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:05:28.945  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 13:05:28.950  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-21 13:05:28.950  5877  5974 D HeadsetStateMachine: Disconnected process message: 10,
,03-21 13:05:28.960  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:28.960  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:28.960  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:05:28.985 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:28.985 11201 11264 I jxcore-log: 
,03-21 13:05:28.990 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:28.990 11201 11264 I jxcore-log: 
,03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:28.995 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:28.995 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:29.000 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:29.000 11201 11264 I jxcore-log: 
,03-21 13:05:29.000 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:29.000 11201 11264 I jxcore-log: 
,03-21 13:05:29.005 11201 11264 I jxcore-log: # teardown
03-21 13:05:29.005 11201 11264 I jxcore-log: 
,03-21 13:05:29.005 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:29.005 11201 11264 I jxcore-log: 
,03-21 13:05:29.120 11201 11264 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-21 13:05:29.120 11201 11264 I jxcore-log: 
,03-21 13:05:29.125 11201 11264 I jxcore-log: ok 183 specific error expected
03-21 13:05:29.125 11201 11264 I jxcore-log: 
,03-21 13:05:29.130 11201 11264 I jxcore-log: # setup
03-21 13:05:29.130 11201 11264 I jxcore-log: 
,03-21 13:05:29.315  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:12), CUR = 65, LCD = 0
,03-21 13:05:29.430  5877  6023 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-21 13:05:29.435  5877  6023 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-21 13:05:29.435  5877  6023 W bt-btif : bta_dm_acl_change(), event : 1
03-21 13:05:29.435  5877  6023 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 13:05:29.435  5877  5968 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX,
03-21 13:05:29.455  3728  3728 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-21 13:05:29.455  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
03-21 13:05:29.465  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-21 13:05:29.465  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-21 13:05:29.465  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-21 13:05:29.480  3369  3554 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{34f14a97 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{8d498b5 5877:com.android.bluetooth/1002}
,03-21 13:05:29.490  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d6f115c
03-21 13:05:29.490  5877  5877 D BtConfig.SecureMode: isSecureModeOn:false
03-21 13:05:29.490  3369  3721 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-21 13:05:29.495  5877  5877 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-21 13:05:29.495  3369  3965 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-21 13:05:29.500  3728  3728 D KeyguardViewMediator: isGear1: device is not B1!
,03-21 13:05:29.500  3369  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:05:29.500  3369  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:05:29.500  3369  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:05:29.500  3369  3387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:05:29.520 11947 11947 E Zygote  : MountEmulatedStorage()
03-21 13:05:29.520 11947 11947 I libpersona: KNOX_SDCARD checking this for 10036
03-21 13:05:29.520 11947 11947 E Zygote  : v2
03-21 13:05:29.520 11947 11947 I libpersona: KNOX_SDCARD not a persona
,03-21 13:05:29.525 11947 11947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:05:29.525 11947 11947 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:05:29.525 11947 11947 E Zygote  : accessInfo : 0
,03-21 13:05:29.525  3369  3387 I ActivityManager: Start proc 11947:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
03-21 13:05:29.525 11947 11947 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-21 13:05:29.530  3369  3964 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:29.540 10312 11960 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-21 13:05:29.545 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-21 13:05:29.545 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-21 13:05:29.550 10312 10312 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-21 13:05:29.550 10312 10312 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-21 13:05:29.550 11947 11947 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:05:29.550 11947 11947 D ActivityThread: Added TimaKeyStore provider
,03-21 13:05:29.560  3369  4404 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{34f14a97 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:29.570 11947 11947 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 13:05:29.655  3369  3965 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 13:05:29.665  3369  3387 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{34f14a97 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:29.665  6112 11975 I System.out: Thread-508(ApacheHTTPLog):isSBSettingEnabled false
,03-21 13:05:29.670  6112 11975 I System.out: Thread-508(ApacheHTTPLog):isShipBuild true
03-21 13:05:29.670  6112 11975 I System.out: Thread-508(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-21 13:05:29.670  6112 11975 I System.out: Thread-508(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-21 13:05:29.670  2873  3396 D EnterpriseController: netId is 0
03-21 13:05:29.670  2873  3396 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,03-21 13:05:29.690 11947 11947 D HealthConsole: Service for HealthDataConsole is connected
,03-21 13:05:29.690 11947 11947 D HealthConsole: Service for HealthDataConsole is connected
,03-21 13:05:29.690 11201 11264 I jxcore-log: # 47. all services are stopped when we call stop
03-21 13:05:29.690 11201 11264 I jxcore-log: 
,03-21 13:05:29.695  3369  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{34f14a97 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:29.705  3369  4389 I ActivityManager: Killing 10175:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-21 13:05:29.705  3369  4389 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{34f14a97 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3964d288 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-21 13:05:29.725  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-21 13:05:29.730  4129  4129 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-21 13:05:29.885 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:29.885 11201 11264 I jxcore-log: 
,03-21 13:05:29.890 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:29.890 11201 11264 I jxcore-log: 
,03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:29.900 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:29.905 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:29.910 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:29.910 11201 11264 I jxcore-log: 
,03-21 13:05:29.915 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:29.915 11201 11264 I jxcore-log: 
,03-21 13:05:29.915 11201 11264 I jxcore-log: # teardown
03-21 13:05:29.915 11201 11264 I jxcore-log: 
,03-21 13:05:29.920 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:29.920 11201 11264 I jxcore-log: 
,03-21 13:05:30.170 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:05:30.170 11201 11264 I jxcore-log: 
,03-21 13:05:30.175 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 43331
03-21 13:05:30.175 11201 11264 I jxcore-log: 
,03-21 13:05:30.185 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 57643, start advertisements: false
,03-21 13:05:30.185 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:30.185 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:30.185 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 13:05:30.190 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:30.190 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:30.190 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:30.195  5877  9150 D BtGatt.GattService: registerClient() - UUID=5016aa4b-0aaa-4a47-b0b7-6555b6ed1b0f
,03-21 13:05:30.235  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=5016aa4b-0aaa-4a47-b0b7-6555b6ed1b0f, clientIf=6
,03-21 13:05:30.235 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:30.235  5877  5888 D BtGatt.GattService: start scan with filters
,03-21 13:05:30.250  5877  5888 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 19
,03-21 13:05:30.250 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 13:05:30.250 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:30.250 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:30.250  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:30.250 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:30.250  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:30.250 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:30.250  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
03-21 13:05:30.250 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 13:05:30.250 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 13:05:30.255 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:30.255 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:30.255 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:30.255 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:30.255 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:30.255 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 13:05:30.255  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:30.255  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:30.255  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:30.255  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 13:05:30.255  5877  5973 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6,
03-21 13:05:30.255 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:30.255 11201 11264 I jxcore-log: 
03-21 13:05:30.255  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-21 13:05:30.255  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:30.260  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 13:05:30.260  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:30.260 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:30.260 11201 11264 I jxcore-log: 
03-21 13:05:30.260  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:30.260  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:30.260  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:30.260  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:30.265 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 43331, start advertisements: true
03-21 13:05:30.265 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 13:05:30.265 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 13:05:30.265 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:30.265 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:05:30.265 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-21 13:05:30.265 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:30.265 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:30.265 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 13:05:30.265 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:30.270 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:30.270 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:30.270  5877  5976 D BtGatt.GattService: registerClient() - UUID=d09518a6-cbc7-4a32-9a08-79c8c7161ad0
,03-21 13:05:30.310  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=d09518a6-cbc7-4a32-9a08-79c8c7161ad0, clientIf=7
,03-21 13:05:30.310 11201 11793 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:30.330  5877  9150 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 15
,03-21 13:05:30.330  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:30.330  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:30.330  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:30.330  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:30.330  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:30.335  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:30.335  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:30.340  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:30.340  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:30.340  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 13:05:30.340 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:30.340 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:30.340 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:05:30.340 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 13:05:30.340 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:30.340 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:30.340 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 13:05:30.345 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 13:05:30.345 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 13:05:30.345 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 13:05:30.345 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:30.345 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 13:05:30.345 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 13:05:30.345 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 13:05:30.345 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 13:05:30.345 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 13:05:30.345 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:30.345 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 13:05:30.345 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:30.345 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 13:05:30.350 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:30.350 11201 11264 I jxcore-log: 
03-21 13:05:30.350 11201 12000 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:05:30.350 11201 12000 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:30.355 11201 12000 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
03-21 13:05:30.355 11201 12000 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:05:30.355 11201 12000 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:30.355 11201 12000 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4bd2ae6
03-21 13:05:30.355 11201 12000 D BluetoothSocket: channel: 6
03-21 13:05:30.355 11201 12000 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:30.360 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:05:30.360 11201 11264 I jxcore-log: 
,03-21 13:05:30.365 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:05:30.365 11201 11264 I jxcore-log: 
,03-21 13:05:30.365 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:05:30.365 11201 11264 I jxcore-log: 
,03-21 13:05:30.370 11201 11264 I jxcore-log: ok 184 connection to servers manager should succeed after starting
03-21 13:05:30.370 11201 11264 I jxcore-log: 
,03-21 13:05:30.385 11201 11264 I jxcore-log: ok 185 connection to router server should succeed after starting
03-21 13:05:30.385 11201 11264 I jxcore-log: 
,03-21 13:05:30.385 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:30.385 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 13:05:30.385 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 13:05:30.385 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 13:05:30.385 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 13:05:30.385 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b818827, channel: 6, state: LISTENING
03-21 13:05:30.385 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b818827, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4bd2ae6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cd0ad4mSocket: android.net.LocalSocket@1e92647d impl:android.net.LocalSocketImpl@14a10f72 fd:FileDescriptor[115]
,03-21 13:05:30.385 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e92647d impl:android.net.LocalSocketImpl@14a10f72 fd:FileDescriptor[115]
03-21 13:05:30.385 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 13:05:30.385 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 13:05:30.385 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 13:05:30.385 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 13:05:30.385 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:30.385 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 13:05:30.385 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 13:05:30.385 11201 12000 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:05:30.385 11201 12000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-21 13:05:30.385 11201 12000 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:05:30.390  5877  5888 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:05:30.390  5877  5973 D BtGatt.ScanManager: filter size is 1
03-21 13:05:30.390  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 8
03-21 13:05:30.390  5877  8684 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 13:05:30.390 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:30.390 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:30.390 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 13:05:30.390 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 13:05:30.390 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 13:05:30.390 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:30.390  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:30.390 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 13:05:30.390  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:30.390  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:30.395  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:05:30.395  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:30.395  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 13:05:30.395  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:30.395  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:30.395  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:30.395  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:30.395  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 13:05:30.395  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:30.395  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 13:05:30.395  5877  5968 D BtGatt.GattService: Client app is not null!
,03-21 13:05:30.395  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:05:30.400 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:30.400 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-21 13:05:30.400 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:30.400 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:05:30.400 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:30.400 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:30.400 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:30.400 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:05:30.400 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-21 13:05:30.400 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:30.400 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:30.400 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:30.400 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:05:30.405 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:05:30.405 11201 11264 I jxcore-log: 
,03-21 13:05:30.405 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:30.410 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 13:05:30.410 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:30.410 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:30.410 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:05:30.410 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:05:30.410 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:30.415 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:30.415 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:30.415 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:30.415 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:30.415 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 13:05:30.415 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 13:05:30.415 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 13:05:30.415 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:30.415 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:05:30.415 11201 11264 I jxcore-log: 
,03-21 13:05:30.420 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:30.420 11201 11264 I jxcore-log: 
,03-21 13:05:30.420 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:30.420 11201 11264 I jxcore-log: 
,03-21 13:05:30.425 11201 11264 I jxcore-log: ok 186 is stopped after calling stop
03-21 13:05:30.425 11201 11264 I jxcore-log: 
,03-21 13:05:30.430 11201 11264 I jxcore-log: ok 187 connection to servers manager should fail after stopping
03-21 13:05:30.430 11201 11264 I jxcore-log: 
,03-21 13:05:30.440 11201 11264 I jxcore-log: ok 188 connection to router server should fail after stopping
03-21 13:05:30.440 11201 11264 I jxcore-log: 
,03-21 13:05:30.445 11201 11264 I jxcore-log: # setup
03-21 13:05:30.445 11201 11264 I jxcore-log: 
,03-21 13:05:30.595 11201 11264 I jxcore-log: # 48. make sure terminateConnection is properly hooked up
03-21 13:05:30.595 11201 11264 I jxcore-log: 
,03-21 13:05:30.740 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:30.740 11201 11264 I jxcore-log: 
,03-21 13:05:30.745 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:30.745 11201 11264 I jxcore-log: 
,03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:30.755 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:30.760 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:30.760 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:30.760 11201 11264 I jxcore-log: 
,03-21 13:05:30.765 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:30.765 11201 11264 I jxcore-log: 
,03-21 13:05:30.770 11201 11264 I jxcore-log: # teardown
03-21 13:05:30.770 11201 11264 I jxcore-log: 
,03-21 13:05:30.770 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:30.770 11201 11264 I jxcore-log: 
,03-21 13:05:30.905 11201 11264 I jxcore-log: ok 189 called with right arguments
03-21 13:05:30.905 11201 11264 I jxcore-log: 
,03-21 13:05:30.915 11201 11264 I jxcore-log: # setup
03-21 13:05:30.915 11201 11264 I jxcore-log: 
,03-21 13:05:31.045 11201 11264 I jxcore-log: # 49. make sure terminateListener is properly hooked up
03-21 13:05:31.045 11201 11264 I jxcore-log: 
,03-21 13:05:31.195 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:31.195 11201 11264 I jxcore-log: 
,03-21 13:05:31.200 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:31.200 11201 11264 I jxcore-log: 
,03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:31.210 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:31.215 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:31.215 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:31.215 11201 11264 I jxcore-log: 
,03-21 13:05:31.220 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:31.220 11201 11264 I jxcore-log: 
,03-21 13:05:31.225 11201 11264 I jxcore-log: # teardown
03-21 13:05:31.225 11201 11264 I jxcore-log: 
,03-21 13:05:31.230 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:31.230 11201 11264 I jxcore-log: 
,03-21 13:05:31.410 11201 11264 I jxcore-log: ok 190 called with right arguments
03-21 13:05:31.410 11201 11264 I jxcore-log: 
,03-21 13:05:31.415 11201 11264 I jxcore-log: # setup
03-21 13:05:31.415 11201 11264 I jxcore-log: 
,03-21 13:05:31.575 11201 11264 I jxcore-log: # 50. make sure we actually call kill connections properly
03-21 13:05:31.575 11201 11264 I jxcore-log: 
,03-21 13:05:31.705 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:31.705 11201 11264 I jxcore-log: 
,03-21 13:05:31.710 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:31.710 11201 11264 I jxcore-log: 
,03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:31.720 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:31.720 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:31.725 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:31.725 11201 11264 I jxcore-log: 
,03-21 13:05:31.725 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:31.725 11201 11264 I jxcore-log: 
,03-21 13:05:31.730 11201 11264 I jxcore-log: # teardown
03-21 13:05:31.730 11201 11264 I jxcore-log: 
,03-21 13:05:31.735 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:31.735 11201 11264 I jxcore-log: 
,03-21 13:05:31.950 11201 11264 I jxcore-log: ok 191 specific error expected
03-21 13:05:31.950 11201 11264 I jxcore-log: 
,03-21 13:05:31.955 11201 11264 I jxcore-log: # setup
03-21 13:05:31.955 11201 11264 I jxcore-log: 
,03-21 13:05:32.110 11201 11264 I jxcore-log: # 51. can do HTTP requests between peers
03-21 13:05:32.110 11201 11264 I jxcore-log: 
,03-21 13:05:32.290 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:32.290 11201 11264 I jxcore-log: 
,03-21 13:05:32.290 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:32.290 11201 11264 I jxcore-log: 
,03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:32.300 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:32.305 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:32.310 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:32.310 11201 11264 I jxcore-log: 
,03-21 13:05:32.310 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:32.310 11201 11264 I jxcore-log: 
,03-21 13:05:32.315 11201 11264 I jxcore-log: # teardown
03-21 13:05:32.315 11201 11264 I jxcore-log: 
,03-21 13:05:32.320 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:32.320 11201 11264 I jxcore-log: 
,03-21 13:05:32.500 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:05:32.500 11201 11264 I jxcore-log: 
,03-21 13:05:32.505 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 48423
03-21 13:05:32.505 11201 11264 I jxcore-log: 
,03-21 13:05:32.515 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 43331, start advertisements: false
,03-21 13:05:32.515 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:32.515 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 13:05:32.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 13:05:32.520 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:32.520 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:32.525 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:32.525  5877  8684 D BtGatt.GattService: registerClient() - UUID=dd5eb0a0-c44b-46b0-ac87-b9df02841a44
,03-21 13:05:32.570  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=dd5eb0a0-c44b-46b0-ac87-b9df02841a44, clientIf=6,
,03-21 13:05:32.570 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:32.580  5877  5890 D BtGatt.GattService: start scan with filters,
,03-21 13:05:32.600  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 20
,03-21 13:05:32.605  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:32.605  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:32.605  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:32.610  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:32.610  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:32.610  5877  5973 D BtGatt.ScanManager: allow scan with filters
,03-21 13:05:32.610  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:32.610  5877  5973 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-21 13:05:32.615  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:32.615  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:32.615  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:32.615  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:32.620  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:32.620  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:32.620  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:32.620  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:32.625 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 13:05:32.625 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 13:05:32.625 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 13:05:32.625 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 13:05:32.625 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 13:05:32.625 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 13:05:32.625 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 13:05:32.630 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 13:05:32.630 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 13:05:32.630 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 13:05:32.630 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-21 13:05:32.630 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 13:05:32.630 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:32.630 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:32.630 11201 11264 I jxcore-log: 
03-21 13:05:32.630 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 13:05:32.630 11201 11264 I jxcore-log: 
,03-21 13:05:32.640 11201 11264 I io.jxcore.node.ConnectionHelper: start: Port number: 48423, start advertisements: true
,03-21 13:05:32.645 11201 11264 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 13:05:32.645 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-21 13:05:32.645 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 13:05:32.645 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 13:05:32.650 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-21 13:05:32.650 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 13:05:32.650 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 13:05:32.650 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 13:05:32.650 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 13:05:32.650 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:32.650 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:32.655  5877  9150 D BtGatt.GattService: registerClient() - UUID=9dc278b7-eba0-4ae0-a2a6-9337a6c69602
,03-21 13:05:32.700  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=9dc278b7-eba0-4ae0-a2a6-9337a6c69602, clientIf=7
03-21 13:05:32.700 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:32.730  5877  5888 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 16
,03-21 13:05:32.730  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:32.735  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:32.735  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:32.740  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:32.740  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:32.745  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:32.750  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:32.750  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:32.755  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 13:05:32.755  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0,
,03-21 13:05:32.755 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:32.755 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
,03-21 13:05:32.755 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 13:05:32.755 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:32.755 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-21 13:05:32.760 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 13:05:32.760 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 13:05:32.760 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 13:05:32.760 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 13:05:32.765 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-21 13:05:32.765 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-21 13:05:32.765 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:32.770 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 13:05:32.770 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-21 13:05:32.770 11201 11264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 13:05:32.770 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 13:05:32.770 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 13:05:32.770 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:32.770 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 13:05:32.770 11201 11264 I io.jxcore.node.ConnectionHelper: start: OK
03-21 13:05:32.770 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 13:05:32.770 11201 11264 I jxcore-log: 
,03-21 13:05:32.780 11201 12027 D BluetoothSocket: bindListen(): myUserId = 0,
03-21 13:05:32.780 11201 12027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:32.780 11201 12027 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]},
03-21 13:05:32.780 11201 12027 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 13:05:32.780 11201 12027 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 13:05:32.780 11201 12027 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@346cb0be
03-21 13:05:32.780 11201 12027 D BluetoothSocket: channel: 6
03-21 13:05:32.780 11201 12027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:33.620  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:33.630  5877  5877 D BtGatt.ScanManager: awakened up at time 260694
,03-21 13:05:33.640  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:33.650  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:33.650  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:33.650  5877  5968 D BtGatt.GattService: current time is 260714516988,
03-21 13:05:33.650  5877  5968 D BtGatt.GattService: Batch record : [-64, -43, 62, -26, -16, 108, 1, -128, -70, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:33.650  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:33.650  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:05:33.655  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=6C:F0:E6:3E:D5:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-70, mTimestampNanos=260614660696}
03-21 13:05:33.655  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:33.655 11201 11211 D ScanRecord: parseFromBytes
,03-21 13:05:33.655 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 13:05:33.655 11201 11201 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-21 13:05:33.660 11201 11264 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-21 13:05:33.660 11201 11264 I jxcore-log: 
,03-21 13:05:33.680 11201 11264 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-21 13:05:33.680 11201 11264 I jxcore-log: 
,03-21 13:05:33.680 11201 11264 I jxcore-log: ok 192 found a peer! {"peerIdentifier":"F8:95:C7:87:3C:51","portNumber":57267,"hostAddress":"127.0.0.1"}
03-21 13:05:33.680 11201 11264 I jxcore-log: 
,03-21 13:05:33.690 11201 11264 I jxcore-log: DEBUG createPeerListener: first connection
03-21 13:05:33.690 11201 11264 I jxcore-log: 
,03-21 13:05:33.695 11201 11264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-21 13:05:33.695 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:33.700 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,03-21 13:05:33.700 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-21 13:05:33.700 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-21 13:05:33.700 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-21 13:05:33.700 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-21 13:05:33.700 11201 11264 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-21 13:05:33.700 11201 12036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1562)
,03-21 13:05:33.705 11201 12036 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,03-21 13:05:33.705 11201 12036 D BluetoothSocket: connect(): myUserId = 0
03-21 13:05:33.705 11201 12036 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:33.710  5877  5890 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-21 13:05:33.710  5877  6023 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:33.710  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 13:05:33.710  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 13:05:33.710  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-21 13:05:33.710 11201 12036 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[119]}
03-21 13:05:33.710  5877  6023 D IOP_DB_BT: db_query_execute: result 1
03-21 13:05:33.710  5877  6023 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 13:05:34.385  5877  6023 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:34.385  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 13:05:34.385  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 13:05:34.385  5877  6023 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
,03-21 13:05:34.385  5877  6023 D IOP_DB_BT: db_query_execute: result 1
03-21 13:05:34.385  5877  6023 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:34.390  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:34.390  5877  6023 W bt-btif : bta_dm_acl_change(), event : 0
03-21 13:05:34.390  5877  6023 W bt-btif : info:x10
03-21 13:05:34.390  5877  5968 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-21 13:05:34.390  5877  5968 E BluetoothRemoteDevices: aclStateChangeCallback: State:Connected to Device:F8:95:C7:87:3C:XX
03-21 13:05:34.395  5877  6023 W bt-btif : bta_dm_acl_change(), event : 2
03-21 13:05:34.415  3728  3728 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_CONNECTED
03-21 13:05:34.415  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 13:05:34.440  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-21 13:05:34.440  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_CONNECTED
03-21 13:05:34.440  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_CONNECTED
,03-21 13:05:34.450  3369  3554 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c6f9e52 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:34.450  3369  3721 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:34.450  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 13:05:34.455  5877  6023 W bt-sdp  : process_service_search_attr_rsp
03-21 13:05:34.455  3728  3728 D KeyguardViewMediator: isGear1: device is not B1!
,03-21 13:05:34.465 10312 12041 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,03-21 13:05:34.465  3369  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c6f9e52 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:34.470 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,03-21 13:05:34.475  3369  3721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c6f9e52 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:34.480 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
03-21 13:05:34.480 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage CONNECTION_COMPLETE
,03-21 13:05:34.500  3369  4031 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c6f9e52 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{1b1d1a32 10122:com.android.settings/1000}
,03-21 13:05:34.500 10122 10122 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 13:05:34.510  3369  4031 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c6f9e52 u0 android.bluetooth.device.action.ACL_CONNECTED} DELIVERED for app ProcessRecord{3964d288 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-21 13:05:34.520  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-21 13:05:34.525  4129  4129 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-21 13:05:34.675  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:34.685  5877  5877 D BtGatt.ScanManager: awakened up at time 261745
,03-21 13:05:34.690  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:34.695  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:34.695  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:34.695  5877  5968 D BtGatt.GattService: current time is 261757747404
03-21 13:05:34.695  5877  5968 D BtGatt.GattService: Batch record : [-64, -43, 62, -26, -16, 108, 1, -128, -68, 21, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-21 13:05:34.695  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:34.695  5877  5968 D ScanRecord: parseFromBytes
,03-21 13:05:34.700  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=6C:F0:E6:3E:D5:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=260708163488}
03-21 13:05:34.700  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:34.705 11201 11213 D ScanRecord: parseFromBytes
,03-21 13:05:34.710 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1,
,03-21 13:05:35.425  5877  5968 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-21 13:05:35.440  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 13:05:35.450  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 13:05:35.450  5877  5968 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-21 13:05:35.465  3369  4776 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 13:05:35.465  5877  5968 E bt-btif : check_cod: remote_cod = 0x5a020c
03-21 13:05:35.470  5877  5968 W bt-btif : btif_dm_ssp_reply: accept=1,
,03-21 13:05:35.470  5877  5971 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-21 13:05:35.475  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 13:05:35.475  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED,
03-21 13:05:35.475  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-21 13:05:35.475  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-21 13:05:35.475  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-21 13:05:35.475  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 13:05:35.480  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 13:05:35.485  3369  3554 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{383d4fd9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b1d1a32 10122:com.android.settings/1000}
,03-21 13:05:35.485 10122 10122 D BluetoothNotiBroadcastReceiver: onReceive
03-21 13:05:35.485  3369  3836 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-21 13:05:35.485  5877  5971 D BtConfig.SecureMode: isSecureModeOn:false
03-21 13:05:35.485  3728  4740 D BluetoothTile:  handleUpdatestate:false name:null
03-21 13:05:35.485  5877  5971 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-21 13:05:35.495 10312 12052 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:35.495 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 13:05:35.500  3369  3822 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{383d4fd9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:35.500 10312 10312 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 13:05:35.500 10312 10312 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-21 13:05:35.505  3369  4047 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{383d4fd9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:35.510  3369  4031 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:35.515 10312 12053 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:35.515 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 13:05:35.520  3369  4047 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{383d4fd9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{780b547 10459:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 13:05:35.520 10459 10459 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 13:05:35.520 10459 10459 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 13:05:35.520 10459 10459 D GMHFPReceiver: jangil::setProperties()
,03-21 13:05:35.525 10459 10459 D GMHFPReceiver: jangil::printBTStatus()
,03-21 13:05:35.525  3369  4396 D SettingsProvider: name = Wearable0001
03-21 13:05:35.525  3369  4396 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:35.525  3369  4396 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:35.525  3369  4396 D SettingsProvider: selectionArgs: false
03-21 13:05:35.525  3369  4396 D SettingsProvider: selectionArgs: 10121
03-21 13:05:35.525  3369  4396 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:35.525  3369  4396 D SettingsProvider: ret = -1
03-21 13:05:35.525 10459 10459 D GMHFPReceiver: ::::::::Wearable0001::false
,03-21 13:05:35.525  3369  3836 D SettingsProvider: name = Wearable0002
03-21 13:05:35.525  3369  3836 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:35.525  3369  3836 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:35.525  3369  3836 D SettingsProvider: selectionArgs: false
,03-21 13:05:35.525  3369  3836 D SettingsProvider: selectionArgs: 10121
03-21 13:05:35.525  3369  3836 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:35.530  3369  3836 D SettingsProvider: ret = -1
03-21 13:05:35.530 10459 10459 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 13:05:35.535  3369  4389 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{383d4fd9 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{266265af 4298:com.google.android.gms.persistent/u0a14}
,03-21 13:05:35.620 10459 10459 D GMHFPReceiver: onServiceConnected() : 1
03-21 13:05:35.620 10459 10459 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 13:05:35.705  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:35.715  5877  5877 D BtGatt.ScanManager: awakened up at time 262779
03-21 13:05:35.725  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:35.725  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:35.725  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:35.900  5877  5968 W bt-btif : btif_dm_auth_cmpl_evt
03-21 13:05:35.900  5877  5968 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-21 13:05:35.930  5877  5968 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-21 13:05:35.930  5877  5971 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-21 13:05:35.935  3369  3387 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 13:05:35.940  5877  5971 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-21 13:05:35.940  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-21 13:05:35.940  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 13:05:35.945  3728  3728 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
03-21 13:05:35.940  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-21 13:05:35.940  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-21 13:05:35.940  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-21 13:05:35.940  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 13:05:35.950  3728  4740 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 13:05:35.950  3369  3554 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{560859b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{1b1d1a32 10122:com.android.settings/1000}
,03-21 13:05:35.955  3369  3964 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-21 13:05:35.955 10122 10122 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 13:05:35.955  5877  5971 D BtConfig.SecureMode: isSecureModeOn:false
,03-21 13:05:35.955  5877  5971 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@b5d1852
,03-21 13:05:35.960  3369  3386 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-21 13:05:35.960  3369  3386 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:35.960  3369  3386 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:35.960  3369  3386 D SettingsProvider: selectionArgs: false
03-21 13:05:35.960  3369  3386 D SettingsProvider: selectionArgs: 1002
03-21 13:05:35.960  3369  3386 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:35.960  3369  3386 D SettingsProvider: ret = -1
03-21 13:05:35.960  5877  5971 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-21 13:05:35.960  3369  4047 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
,03-21 13:05:35.960  3369  4047 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:35.960  3369  4047 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:35.960  3369  4047 D SettingsProvider: selectionArgs: false
03-21 13:05:35.960  3369  4047 D SettingsProvider: selectionArgs: 1002
03-21 13:05:35.960  3369  4047 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 13:05:35.960  3369  4047 D SettingsProvider: ret = -1
,03-21 13:05:35.965  3369  4389 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
03-21 13:05:35.965  3369  4389 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:35.965  3369  4389 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
03-21 13:05:35.965  3369  4389 D SettingsProvider: selectionArgs: false
03-21 13:05:35.965  3369  4389 D SettingsProvider: selectionArgs: 1002
03-21 13:05:35.965  3369  4389 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 13:05:35.965  3369  4389 D SettingsProvider: ret = -1
,03-21 13:05:35.965  5877  5971 I BluetoothBondStateMachine: StableState(): Entering Off State
03-21 13:05:35.965  3369  4402 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{560859b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:35.970 10312 12064 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:35.970 10312 10312 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 13:05:35.975 10312 10312 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,03-21 13:05:35.980  3369  3836 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{560859b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{247f089f 10312:com.sec.android.automotive.drivelink/u0a102}
,03-21 13:05:35.980  3369  5929 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:35.985 10312 12065 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 13:05:35.990  3369  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{560859b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{780b547 10459:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 13:05:35.990 10459 10459 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 13:05:35.995 10459 10459 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 13:05:35.995 10459 10459 D GMHFPReceiver: jangil::setProperties()
,03-21 13:05:35.995 10459 10459 D GMHFPReceiver: jangil::printBTStatus()
,03-21 13:05:35.995  3369  4402 D SettingsProvider: name = Wearable0001
03-21 13:05:35.995  3369  4402 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 13:05:35.995  3369  4402 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:36.000  3369  4402 D SettingsProvider: selectionArgs: false
03-21 13:05:36.000  3369  4402 D SettingsProvider: selectionArgs: 10121
03-21 13:05:36.000  3369  4402 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 13:05:36.000  3369  4402 D SettingsProvider: ret = -1
03-21 13:05:36.000 10459 10459 D GMHFPReceiver: ::::::::Wearable0001::false
,03-21 13:05:36.000  3369  4776 D SettingsProvider: name = Wearable0002
03-21 13:05:36.000  3369  4776 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-21 13:05:36.000  3369  4776 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 13:05:36.000  3369  4776 D SettingsProvider: selectionArgs: false
03-21 13:05:36.000  3369  4776 D SettingsProvider: selectionArgs: 10121
03-21 13:05:36.000  3369  4776 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 13:05:36.000  3369  4776 D SettingsProvider: ret = -1
03-21 13:05:36.000 10459 10459 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 13:05:36.005  3369  4031 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{560859b u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{266265af 4298:com.google.android.gms.persistent/u0a14},
,03-21 13:05:36.095 10459 10459 D GMHFPReceiver: onServiceConnected() : 1
03-21 13:05:36.095 10459 10459 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 13:05:36.730  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:36.745  5877  5877 D BtGatt.ScanManager: awakened up at time 263806
,03-21 13:05:36.750  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:36.755  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:36.755  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 13:05:37.770  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:37.780  5877  5877 D BtGatt.ScanManager: awakened up at time 264843
,03-21 13:05:37.785  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:37.795  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:37.795  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 13:05:37.795  5877  5968 D BtGatt.GattService: current time is 264859511780
03-21 13:05:37.795  5877  5968 D BtGatt.GattService: Batch record : [-64, -43, 62, -26, -16, 108, 1, -128, -68, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-21 13:05:37.800  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:37.800  5877  5968 D ScanRecord: parseFromBytes,
,03-21 13:05:37.800  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=6C:F0:E6:3E:D5:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=264809852696},
,03-21 13:05:37.800  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:37.800 11201 11213 D ScanRecord: parseFromBytes
03-21 13:05:37.800 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:38.815  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:38.830  5877  5877 D BtGatt.ScanManager: awakened up at time 265890
,03-21 13:05:38.830  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:38.840  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:38.840  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:38.840  5877  5968 D BtGatt.GattService: current time is 265903420988
03-21 13:05:38.840  5877  5968 D BtGatt.GattService: Batch record : [-64, -43, 62, -26, -16, 108, 1, -128, -68, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:38.840  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:38.840  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:38.840  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=6C:F0:E6:3E:D5:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=265853567988}
03-21 13:05:38.840  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:38.840 11201 11793 D ScanRecord: parseFromBytes
03-21 13:05:38.845 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:39.035  3369  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:05:39.040  3369  3836 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:05:39.040  3369  3836 D BatteryService: online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
03-21 13:05:39.040  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 13:05:39.045  3369  3836 D BatteryService: stay LED for fully charged
,03-21 13:05:39.050  3369  3369 I MotionRecognitionService: Plugged
03-21 13:05:39.050  3369  3369 D MotionRecognitionService:   cableConnection= 1,
03-21 13:05:39.050  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:05:39.050  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:05:39.060  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 13:05:39.060  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:05:39.060  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:05:39.080  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 13:05:39.080  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:05:39.090  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:05:39.090  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:39.090  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:39.090  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:05:39.345  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 283 (W:12), CUR = 63, LCD = 0
,03-21 13:05:39.850  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:39.870  5877  5877 D BtGatt.ScanManager: awakened up at time 266930
,03-21 13:05:39.870  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:39.875  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:39.875  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:39.880  5877  5968 D BtGatt.GattService: current time is 266939933447
,03-21 13:05:39.880  5877  5968 D BtGatt.GattService: Batch record : [-64, -43, 62, -26, -16, 108, 1, -128, -68, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:39.880  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:39.880  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:39.880  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=6C:F0:E6:3E:D5:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-68, mTimestampNanos=266492473238}
03-21 13:05:39.880  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:39.880 11201 11211 D ScanRecord: parseFromBytes,
,03-21 13:05:39.880 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:40.895  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:40.910  5877  5877 D BtGatt.ScanManager: awakened up at time 267969
,03-21 13:05:40.915  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:40.915  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:40.915  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:41.940  3369  3620 V AlarmManager: waitForAlarm result :4
,03-21 13:05:41.950  5877  5877 D BtGatt.ScanManager: awakened up at time 269012
,03-21 13:05:41.955  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:41.960  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:41.960  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:42.665  5877  6023 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 73 RCID: 74
,03-21 13:05:42.710  5877  6023 W bt-btif : new conn_srvc id:26, app_id:255
03-21 13:05:42.710  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 13:05:42.710  5877  6023 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-21 13:05:42.715 11201 12027 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2d2f9758
03-21 13:05:42.720  5877  6023 W bt-btif : new conn_srvc id:26, app_id:1
03-21 13:05:42.720  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 13:05:42.720  5877  6023 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-21 13:05:42.720  5877  6023 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-21 13:05:42.730  5877  5890 E BluetoothRemoteDevices: setRfcommConnected true,
03-21 13:05:42.730  5877  5888 E BluetoothRemoteDevices: setRfcommConnected true
03-21 13:05:42.735 11201 12036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1562)
,03-21 13:05:42.735 11201 12036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1562),
,03-21 13:05:42.740 11201 12027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-21 13:05:42.750 11201 12036 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 13:05:42.750 11201 12027 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-21 13:05:42.760 11201 12036 D BluetoothSocket: getOutputStream(): myUserId = 0,
,03-21 13:05:42.765 11201 12027 D BluetoothSocket: getOutputStream(): myUserId = 0,
03-21 13:05:42.765 11201 12027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1563)
03-21 13:05:42.765 11201 12027 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@237070b1, channel: 6, state: LISTENING
03-21 13:05:42.765 11201 12027 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@237070b1, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@346cb0be, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@331c1996mSocket: android.net.LocalSocket@32c6c917 impl:android.net.LocalSocketImpl@eb2d104 fd:FileDescriptor[115]
03-21 13:05:42.765 11201 12027 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32c6c917 impl:android.net.LocalSocketImpl@eb2d104 fd:FileDescriptor[115]
,03-21 13:05:42.765 11201 12036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1564)
,03-21 13:05:42.765 11201 12036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1564)
03-21 13:05:42.765 11201 12036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1562)
,03-21 13:05:42.770 11201 12027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
03-21 13:05:42.770 11201 12027 D BluetoothSocket: bindListen(): myUserId = 0
03-21 13:05:42.770 11201 12027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 13:05:42.775 11201 12099 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1564),
,03-21 13:05:42.780 11201 12100 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1563),
03-21 13:05:42.780 11201 12027 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[120]}
03-21 13:05:42.780 11201 12027 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 13:05:42.780 11201 12027 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 13:05:42.780 11201 12027 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aea66ed
03-21 13:05:42.780 11201 12027 D BluetoothSocket: channel: 6
03-21 13:05:42.780 11201 12027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 13:05:42.860  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:42.860 11201 12100 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1563)
03-21 13:05:42.860  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:42.860  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:42.860  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:42.860 11201 12100 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:42.865 11201 12100 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1563)
03-21 13:05:42.865 11201 12100 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1563
,03-21 13:05:42.865 11201 12100 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1563)
03-21 13:05:42.865  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:42.865 11201 12100 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:42.865 11201 11201 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:42.865 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:42.865  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:42.865 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:42.865  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:42.865 11201 12100 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1563)
03-21 13:05:42.865  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:42.880 11201 11201 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 13:05:42.885 11201 11201 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 13:05:42.885 11201 11201 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-21 13:05:42.885 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-21 13:05:42.885 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:42.885 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:42.885 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:42.885 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:42.885 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:42.885 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 13:05:42.885  5877  5972 D BtGatt.AdvertiseManager: message : 1,
03-21 13:05:42.885  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:42.885  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 13:05:42.890  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 13:05:42.890  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-21 13:05:42.890  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:05:42.890  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:42.895 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 13:05:42.895 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:42.895 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:42.895 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:42.895 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:42.895 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:42.895 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 13:05:42.895 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:42.895 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 13:05:42.900  5877  8684 D BtGatt.GattService: registerClient() - UUID=079f6bec-84b8-46a3-b57f-f1438df2b63f
,03-21 13:05:42.910  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:42.910  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:42.910  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:42.910  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:42.910 11201 12099 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1564)
03-21 13:05:42.915 11201 12099 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:42.915 11201 12099 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1562)
03-21 13:05:42.915 11201 12099 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1562)
03-21 13:05:42.915 11201 12099 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1564)
,03-21 13:05:42.935  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-21 13:05:42.940  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=079f6bec-84b8-46a3-b57f-f1438df2b63f, clientIf=7,
03-21 13:05:42.940 11201 11213 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:42.965  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 17
,03-21 13:05:42.965  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:42.970  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:42.970  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:42.970  3369  3620 V AlarmManager: waitForAlarm result :4
03-21 13:05:42.975  5877  5877 D BtGatt.ScanManager: awakened up at time 270038
03-21 13:05:42.980  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:42.985  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 13:05:42.985  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:42.985  5877  5968 D BtGatt.GattService: current time is 270049564030
03-21 13:05:42.985  5877  5968 D BtGatt.GattService: Batch record : [-64, -43, 62, -26, -16, 108, 1, -128, -75, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 13:05:42.985  5877  5968 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 13:05:42.990  5877  5968 D ScanRecord: parseFromBytes
03-21 13:05:42.990  5877  5968 D BtGatt.GattService: result: ScanResult{mDevice=6C:F0:E6:3E:D5:C0, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-75, mTimestampNanos=269899708697}
,03-21 13:05:42.990  5877  5968 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:42.990 11201 11793 D ScanRecord: parseFromBytes
,03-21 13:05:42.995  5877  5972 D BtGatt.AdvertiseManager: starting advertising,
,03-21 13:05:42.995  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 13:05:43.000  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0,
,03-21 13:05:43.005  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising,
,03-21 13:05:43.005  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 13:05:43.005  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,03-21 13:05:43.005  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 13:05:43.010 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 13:05:43.010  5877  5976 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:05:43.010  5877  8684 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:43.015 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:43.015 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:43.015 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:43.015 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:05:43.015 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:43.015 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 13:05:43.015  5877  5973 D BtGatt.ScanManager: filter size is 1
,03-21 13:05:43.015  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 9
03-21 13:05:43.020  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:43.020  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.020  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
03-21 13:05:43.020  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 13:05:43.020  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.020  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:43.020  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 13:05:43.020  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.020  5877  5976 D BtGatt.GattService: registerClient() - UUID=ecbcb6aa-c6c2-42b9-8f49-9502170e2933
,03-21 13:05:43.050  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.050  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.050  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.050  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.060  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=ecbcb6aa-c6c2-42b9-8f49-9502170e2933, clientIf=6
,03-21 13:05:43.060 11201 11793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:43.065  5877  5888 D BtGatt.GattService: start scan with filters
,03-21 13:05:43.075  5877  5888 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 21
,03-21 13:05:43.075 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-21 13:05:43.075  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:43.075  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:43.075 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:43.075  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:43.075  5877  5972 D BtGatt.AdvertiseManager: message : 1
,03-21 13:05:43.075  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:43.075  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 13:05:43.075  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:43.075  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.075  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:43.075  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:43.075  5877  5973 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-21 13:05:43.080  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:43.080  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:43.080  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.080  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 13:05:43.080  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:43.080  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:43.080  5877  5968 D BtGatt.GattService: Client app is not null!
,03-21 13:05:43.080  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 13:05:43.080 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:43.080 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 13:05:43.080 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 13:05:43.080 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:43.080 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:43.080 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 13:05:43.080 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:43.080 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:43.080 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:43.080  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:43.080  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.085  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:43.085  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.085  5877  9150 D BtGatt.GattService: registerClient() - UUID=0c4dae2d-b7ba-4c09-b071-31d1e9c85369
,03-21 13:05:43.125  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=0c4dae2d-b7ba-4c09-b071-31d1e9c85369, clientIf=7
,03-21 13:05:43.130 11201 11211 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:43.145  5877  5976 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 18
,03-21 13:05:43.145  5877  5972 D BtGatt.AdvertiseManager: message : 0
03-21 13:05:43.145  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:43.145  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:43.145  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:43.145  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:43.150  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:43.150  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:43.155  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:43.155  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:43.155  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 13:05:43.155 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:05:43.155  5877  5888 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:05:43.155  5877  5973 D BtGatt.ScanManager: filter size is 1
,03-21 13:05:43.155  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 10
03-21 13:05:43.155  5877  8684 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 13:05:43.160  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 13:05:43.160  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.160 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:43.160 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:43.160  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:43.160 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:43.160 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 13:05:43.160 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 13:05:43.160 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 13:05:43.165  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:43.165  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.165  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:43.165  5877  5888 D BtGatt.GattService: registerClient() - UUID=0f6b9e43-d5b1-46c4-a64d-80e73f48ac84,
03-21 13:05:43.165  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:43.165  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.205  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=0f6b9e43-d5b1-46c4-a64d-80e73f48ac84, clientIf=6
,03-21 13:05:43.205 11201 11213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 13:05:43.205  5877  8684 D BtGatt.GattService: start scan with filters
,03-21 13:05:43.220  5877  8684 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 22
,03-21 13:05:43.220 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:43.220  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-21 13:05:43.220  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:43.220  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:43.220 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 13:05:43.220  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:43.220  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.220  5877  5973 D BtGatt.ScanManager: allow scan with filters
,03-21 13:05:43.220  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:43.225  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:05:43.225  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:43.225  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:43.225  5877  5973 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
,03-21 13:05:43.225  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:43.225  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:43.225  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.225  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:43.225  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 13:05:43.225  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:43.225  5877  5968 D BtGatt.GattService: Client app is not null!
,03-21 13:05:43.225  5877  5890 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-21 13:05:43.230 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:43.230 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 13:05:43.230 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 13:05:43.230 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 13:05:43.230 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 13:05:43.230 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 13:05:43.230 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:43.230  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:43.230  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.230 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 13:05:43.230 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 13:05:43.235  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:43.235  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.240  5877  5976 D BtGatt.GattService: registerClient() - UUID=76904ca7-9e79-4248-be44-d7cc79e6f047
,03-21 13:05:43.280  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=76904ca7-9e79-4248-be44-d7cc79e6f047, clientIf=7
,03-21 13:05:43.280 11201 11793 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 13:05:43.310  5877  5890 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 19
,03-21 13:05:43.310  5877  5972 D BtGatt.AdvertiseManager: message : 0
,03-21 13:05:43.310  5877  5972 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 13:05:43.310  5877  5972 D BtGatt.AdvertiseManager: size of list is =0
,03-21 13:05:43.315  5877  5972 D BtGatt.AdvertiseManager: starting advertising
,03-21 13:05:43.315  5877  5972 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 13:05:43.320  5877  5968 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 13:05:43.320  5877  5972 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 13:05:43.325  5877  5968 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 13:05:43.325  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 13:05:43.325  5877  5972 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 13:05:43.325 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 13:05:43.330  5877  8684 D BtGatt.GattService: stopScan() - queue size =1
,03-21 13:05:43.330  5877  5973 D BtGatt.ScanManager: filter size is 1
,03-21 13:05:43.330  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 11
,03-21 13:05:43.330  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-21 13:05:43.330  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-21 13:05:43.330  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.330  5877  5973 D BtGatt.ScanManager: stopping BLe Batch
,03-21 13:05:43.330 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,03-21 13:05:43.330 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 13:05:43.330 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-21 13:05:43.330 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 13:05:43.330 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 13:05:43.330 11201 11201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null],
03-21 13:05:43.335  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 13:05:43.335  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.335  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 13:05:43.340  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 13:05:43.340  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 13:05:43.345  5877  8684 D BtGatt.GattService: registerClient() - UUID=dbfa137f-c07d-400a-a8cb-87c4b33cf1f4
,03-21 13:05:43.385  5877  5968 D BtGatt.GattService: onClientRegistered() - UUID=dbfa137f-c07d-400a-a8cb-87c4b33cf1f4, clientIf=6,
03-21 13:05:43.385 11201 11211 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,03-21 13:05:43.385  5877  5976 D BtGatt.GattService: start scan with filters
,03-21 13:05:43.405  5877  5976 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 23
,03-21 13:05:43.405  5877  5973 D BtGatt.ScanManager: handling starting scan
03-21 13:05:43.405  5877  5973 D BtGatt.ScanManager: isFilteringSupported
03-21 13:05:43.405  5877  5973 D BluetoothAdapter: setting StandAloneBleMode
,03-21 13:05:43.410  5877  5968 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 13:05:43.410  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.410  5877  5973 D BtGatt.ScanManager: allow scan with filters
03-21 13:05:43.410  5877  5973 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 13:05:43.410  5877  5973 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-21 13:05:43.410  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 13:05:43.410  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.415  5877  5973 D BtGatt.ScanManager: Starting BLE batch scan
03-21 13:05:43.415  5877  5973 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 13:05:43.415  5877  5968 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 13:05:43.415  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.420  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 13:05:43.420  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.425 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 13:05:43.425 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 13:05:43.425 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 13:05:43.425 11201 11201 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-21 13:05:43.425 11201 11201 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 13:05:43.425 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 13:05:43.425 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:43.425 11201 11201 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 13:05:43.425 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 13:05:43.425 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:43.425 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 13:05:43.425 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-21 13:05:43.425 11201 11201 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1,
03-21 13:05:43.430 11201 11201 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 13:05:43.435 11201 11201 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 13:05:43.435 11201 11201 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 13:05:43.435 11201 11201 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-21 13:05:43.440 11201 12119 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1565),
,03-21 13:05:43.440 11201 12120 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1566),
03-21 13:05:43.440 11201 12120 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 34735
03-21 13:05:43.440 11201 12120 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,03-21 13:05:43.440 11201 12120 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 34735 (peer ID: F8:95:C7:87:3C:51)
,03-21 13:05:43.445  2873  3396 D EnterpriseController: netId is 0
03-21 13:05:43.445  2873  3396 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 13:05:43.445 11201 12120 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed,
03-21 13:05:43.445 11201 11264 I jxcore-log: DEBUG createPeerListener: forward connection
03-21 13:05:43.445 11201 11264 I jxcore-log: 
,03-21 13:05:43.455 11201 12120 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 34735,
03-21 13:05:43.455 11201 12120 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-21 13:05:43.455 11201 12120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 13:05:43.455 11201 12120 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:43.455 11201 12120 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1566)
03-21 13:05:43.455 11201 12120 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1566)
,03-21 13:05:43.460 11201 12123 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1568, name: Receiver),
,03-21 13:05:43.460 11201 12119 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 48423
,03-21 13:05:43.460 11201 12119 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-21 13:05:43.460 11201 12119 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:43.460 11201 12119 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 13:05:43.460 11201 12119 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1565)
,03-21 13:05:43.460 11201 12119 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1565)
03-21 13:05:43.465 11201 12126 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1570, name: Receiver)
,03-21 13:05:43.465 11201 12122 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1567, name: Sender)
,03-21 13:05:43.465 11201 12125 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1569, name: Sender)
,03-21 13:05:43.465 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:05:43.465 11201 11264 I jxcore-log: 
,03-21 13:05:43.465 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux,
03-21 13:05:43.465 11201 11264 I jxcore-log: 
,03-21 13:05:43.470 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:05:43.470 11201 11264 I jxcore-log: 
,03-21 13:05:43.480  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.480  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.480  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.480  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.485  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.490 11201 11264 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 13:05:43.490 11201 11264 I jxcore-log: 
,03-21 13:05:43.490 11201 11264 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 13:05:43.490 11201 11264 I jxcore-log: 
,03-21 13:05:43.530  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.530  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.530  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.535  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.535  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.535  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.535  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.535  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.540  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.540  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.540  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.540  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.540 11201 11264 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 13:05:43.540 11201 11264 I jxcore-log: 
,03-21 13:05:43.545  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.545  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.545  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.545  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.675  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.675  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.675  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.675  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.740  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.745  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.745  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 13:05:43.745  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.765 11201 11264 I jxcore-log: ok 193 server should return 200
03-21 13:05:43.765 11201 11264 I jxcore-log: 
,03-21 13:05:43.775 11201 11264 I jxcore-log: ok 194 response body should match testData
03-21 13:05:43.775 11201 11264 I jxcore-log: 
,03-21 13:05:43.790 11201 11264 I jxcore-log: # setup
03-21 13:05:43.790 11201 11264 I jxcore-log: 
,03-21 13:05:43.810  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.815  5877  6023 D IOP_DB_BT: db_query: result 1
03-21 13:05:43.815  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 13:05:43.815  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.825 11201 12122 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1567, thread name: Sender)
03-21 13:05:43.830 11201 12122 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 13:05:43.830 11201 12122 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 13:05:43.830 11201 12122 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
03-21 13:05:43.830 11201 12122 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1566)
03-21 13:05:43.830 11201 12122 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1566)
03-21 13:05:43.830 11201 12122 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@389384e9, channel: 7, state: CONNECTED
03-21 13:05:43.830 11201 12122 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@389384e9, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e84c56e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33c3c40fmSocket: android.net.LocalSocket@22b13c9c impl:android.net.LocalSocketImpl@29686a5 fd:FileDescriptor[119]
03-21 13:05:43.830 11201 12122 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22b13c9c impl:android.net.LocalSocketImpl@29686a5 fd:FileDescriptor[119]
03-21 13:05:43.830 11201 12123 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1568, thread name: Receiver): bt socket closed, read return: -1
03-21 13:05:43.830 11201 12123 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1568, name: Receiver)
,03-21 13:05:43.835  5877  6023 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 13:05:43.835  5877  6023 D IOP_DB_BT: db_query: result 1,
03-21 13:05:43.835  5877  6023 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 13:05:43.835  5877  6023 D IOP_DB_BT: db_query: result 1
,03-21 13:05:43.835 11201 12122 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@389384e9, channel: 7, state: CLOSED,
03-21 13:05:43.835 11201 12122 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@389384e9, channel: 7, state: CLOSED
,03-21 13:05:43.835 11201 12122 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
03-21 13:05:43.835 11201 12122 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-21 13:05:43.835 11201 12122 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1568
,03-21 13:05:43.835 11201 12122 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...,
03-21 13:05:43.835 11201 12122 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1567
03-21 13:05:43.835 11201 12122 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1566),
03-21 13:05:43.835 11201 12122 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1566),
03-21 13:05:43.835 11201 12122 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
03-21 13:05:43.835 11201 12122 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1567, name: Sender)
,03-21 13:05:43.875 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 13:05:43.875 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-21 13:05:43.880 11201 11264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 13:05:43.880 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 13:05:43.880 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 13:05:43.880 11201 11264 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fbbca7a, channel: 6, state: LISTENING
,03-21 13:05:43.880 11201 11264 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3fbbca7a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aea66ed, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f02922bmSocket: android.net.LocalSocket@4e38688 impl:android.net.LocalSocketImpl@3d0de821 fd:FileDescriptor[120]
03-21 13:05:43.880 11201 11264 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4e38688 impl:android.net.LocalSocketImpl@3d0de821 fd:FileDescriptor[120]
,03-21 13:05:43.880 11201 11264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 13:05:43.880 11201 12027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 13:05:43.880 11201 12027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 13:05:43.880 11201 12027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 13:05:43.885 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 13:05:43.885 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 13:05:43.885 11201 11201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 13:05:43.885 11201 11201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 13:05:43.885 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 13:05:43.885 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-21 13:05:43.885 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 13:05:43.885 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 13:05:43.885 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 13:05:43.890  5877  8684 D BtGatt.GattService: stopScan() - queue size =1,
,03-21 13:05:43.890  5877  5973 D BtGatt.ScanManager: filter size is 1,
03-21 13:05:43.890  5877  5973 D BtGatt.ScanManager: delete FilterIndex - 12
03-21 13:05:43.890  5877  5968 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 13:05:43.890  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 13:05:43.890  5877  5973 D BtGatt.ScanManager: stopping BLe Batch,
,03-21 13:05:43.895  5877  5968 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 13:05:43.895  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 13:05:43.895  5877  5973 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 13:05:43.895  5877  5968 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
,03-21 13:05:43.895  5877  5968 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 13:05:43.900  5877  5976 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 13:05:43.900 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 13:05:43.900 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-21 13:05:43.900 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 13:05:43.905 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-21 13:05:43.905 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 13:05:43.905 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:43.905 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 13:05:43.910  5877  5972 D BtGatt.AdvertiseManager: message : 1
03-21 13:05:43.910  5877  5972 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 13:05:43.910  5877  5972 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 13:05:43.910  5877  6023 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,03-21 13:05:43.910  5877  5968 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 13:05:43.910  5877  5968 D BtGatt.GattService: Client app is not null!
03-21 13:05:43.910  5877  5972 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 13:05:43.910  5877  9150 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 13:05:43.915 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 13:05:43.915 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 13:05:43.915 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 13:05:43.915 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 13:05:43.915 11201 11264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 13:05:43.915 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:43.915 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 13:05:43.915 11201 11264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 13:05:43.920 11201 11264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 13:05:43.920 11201 11264 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 13:05:43.920 11201 11264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 13:05:43.920 11201 11201 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 13:05:43.920 11201 11201 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 13:05:43.920 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 13:05:43.920 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 13:05:43.920 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 13:05:43.930 11201 11264 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 13:05:43.930 11201 11201 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 13:05:43.930 11201 11264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 13:05:43.930 11201 11264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 13:05:43.935 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 13:05:43.935 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:43.935 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 13:05:43.940 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 13:05:43.940 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 13:05:43.940 11201 11201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 13:05:43.940 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 13:05:43.940 11201 11264 I jxcore-log: 
,03-21 13:05:43.940 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:43.940 11201 11264 I jxcore-log: 
,03-21 13:05:43.945 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 13:05:43.945 11201 11264 I jxcore-log: 
,03-21 13:05:43.945 11201 12125 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1569, thread name: Sender)
,03-21 13:05:43.945 11201 12125 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
,03-21 13:05:43.945 11201 12125 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 13:05:43.945 11201 12125 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1565
03-21 13:05:43.945 11201 12125 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1565)
,03-21 13:05:43.945 11201 12125 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23162607, channel: 6, state: CONNECTED
03-21 13:05:43.945 11201 12125 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23162607, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@206e8334, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@293fe55dmSocket: android.net.LocalSocket@b052ed2 impl:android.net.LocalSocketImpl@de51ba3 fd:FileDescriptor[118]
03-21 13:05:43.945 11201 12125 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b052ed2 impl:android.net.LocalSocketImpl@de51ba3 fd:FileDescriptor[118]
03-21 13:05:43.945 11201 12126 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1570, thread name: Receiver): bt socket closed, read return: -1
03-21 13:05:43.945 11201 12125 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23162607, channel: 6, state: CLOSED
03-21 13:05:43.945 11201 12126 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1570, name: Receiver)
,03-21 13:05:43.945 11201 12125 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23162607, channel: 6, state: CLOSED
03-21 13:05:43.945 11201 12125 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 13:05:43.945 11201 12125 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
03-21 13:05:43.945 11201 12125 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1570
03-21 13:05:43.945 11201 12125 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-21 13:05:43.945 11201 12125 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1569
03-21 13:05:43.945 11201 12125 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1565)
03-21 13:05:43.945 11201 12125 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1565)
,03-21 13:05:43.945 11201 12125 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-21 13:05:43.945 11201 12125 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1569, name: Sender)
03-21 13:05:43.950 11201 11264 I jxcore-log: DEBUG createNativeListener: mux close
03-21 13:05:43.950 11201 11264 I jxcore-log: 
,03-21 13:05:43.955 11201 11264 I jxcore-log: # 52. Can do requests between peers after start and stop
03-21 13:05:43.955 11201 11264 I jxcore-log: 
,03-21 13:05:43.960 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:05:43.960 11201 11264 I jxcore-log: 
,03-21 13:05:43.960 11201 11264 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 13:05:43.960 11201 11264 I jxcore-log: 
,03-21 13:05:43.960 11201 11264 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 13:05:43.960 11201 11264 I jxcore-log: 
,03-21 13:05:44.490  5877  6023 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND,
03-21 13:05:44.490  5877  6023 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0,
,03-21 13:05:44.875 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:44.875 11201 11264 I jxcore-log: 
,03-21 13:05:44.875 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:44.875 11201 11264 I jxcore-log: 
,03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:44.885 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:44.890 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:44.895 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:44.895 11201 11264 I jxcore-log: 
,03-21 13:05:44.905 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:44.905 11201 11264 I jxcore-log: 
,03-21 13:05:44.915 11201 11264 I jxcore-log: # teardown
03-21 13:05:44.915 11201 11264 I jxcore-log: 
,03-21 13:05:44.915 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:44.915 11201 11264 I jxcore-log: 
,03-21 13:05:45.005 11201 11264 I jxcore-log: ok 195 (unnamed assert)
03-21 13:05:45.005 11201 11264 I jxcore-log: 
,03-21 13:05:45.010 11201 11264 I jxcore-log: # setup
03-21 13:05:45.010 11201 11264 I jxcore-log: 
,03-21 13:05:45.910 11201 11264 I jxcore-log: # 53. We successfully receive and replay discoveryAdvertisingStateUpdate
03-21 13:05:45.910 11201 11264 I jxcore-log: 
,03-21 13:05:45.920  3369  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 13:05:45.920  3369  3654 V NetworkStats: performPollLocked(flags=0x1)
,03-21 13:05:45.935  3369  3654 V NetworkStats: performPollLocked() took 12ms
,03-21 13:05:45.935  3369  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 13:05:45.935  3369  3655 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 13:05:45.935  3369  3655 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 13:05:46.045 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 13:05:46.045 11201 11264 I jxcore-log: 
,03-21 13:05:46.045 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 13:05:46.045 11201 11264 I jxcore-log: 
,03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 13:05:46.055 11201 11264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 13:05:46.060 11201 11264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 13:05:46.065 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 13:05:46.065 11201 11264 I jxcore-log: 
,03-21 13:05:46.065 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 13:05:46.065 11201 11264 I jxcore-log: 
,03-21 13:05:46.070 11201 11264 I jxcore-log: # teardown
03-21 13:05:46.070 11201 11264 I jxcore-log: 
,03-21 13:05:46.075 11201 11264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 13:05:46.075 11201 11264 I jxcore-log: 
,03-21 13:05:46.230 11201 11264 I jxcore-log: ok 196 (unnamed assert)
03-21 13:05:46.230 11201 11264 I jxcore-log: 
,03-21 13:05:46.235 11201 11264 I jxcore-log: # setup
03-21 13:05:46.235 11201 11264 I jxcore-log: 
,03-21 13:05:46.420 11201 11264 I jxcore-log: # 54. Test BEACONS_RETRIEVED_AND_PARSED locally
03-21 13:05:46.420 11201 11264 I jxcore-log: 
,03-21 13:05:46.675 11201 11264 I jxcore-log: # teardown
03-21 13:05:46.675 11201 11264 I jxcore-log: 
,03-21 13:05:46.905 11201 11264 I jxcore-log: ok 197 peerIdentifier should be hello
03-21 13:05:46.905 11201 11264 I jxcore-log: 
,03-21 13:05:46.905 11201 11264 I jxcore-log: ok 198 Response should be BEACONS_RETRIEVED_AND_PARSED
03-21 13:05:46.905 11201 11264 I jxcore-log: 
,03-21 13:05:46.905 11201 11264 I jxcore-log: ok 199 good beacon
03-21 13:05:46.905 11201 11264 I jxcore-log: 
,03-21 13:05:46.910 11201 11264 I jxcore-log: ok 200 good preAmble
03-21 13:05:46.910 11201 11264 I jxcore-log: 
03-21 13:05:46.910 11201 11264 I jxcore-log: ok 201 public keys match!
03-21 13:05:46.910 11201 11264 I jxcore-log: 
,03-21 13:05:46.910 11201 11264 I jxcore-log: ok 202 must return null after successful call
03-21 13:05:46.910 11201 11264 I jxcore-log: 
,03-21 13:05:46.920 11201 11264 I jxcore-log: # setup
03-21 13:05:46.920 11201 11264 I jxcore-log: 
,03-21 13:05:47.010 11201 11264 I jxcore-log: # 55. Test HTTP_BAD_RESPONSE locally
03-21 13:05:47.010 11201 11264 I jxcore-log: 
,03-21 13:05:47.155 11201 11264 I jxcore-log: # teardown
03-21 13:05:47.155 11201 11264 I jxcore-log: 
,03-21 13:05:47.340 11201 11264 I jxcore-log: ok 203 Response should be HTTP_BAD_RESPONSE
03-21 13:05:47.340 11201 11264 I jxcore-log: 
,03-21 13:05:47.345 11201 11264 I jxcore-log: ok 204 must return null after successful call
03-21 13:05:47.345 11201 11264 I jxcore-log: 
,03-21 13:05:47.355 11201 11264 I jxcore-log: # setup
03-21 13:05:47.355 11201 11264 I jxcore-log: 
,03-21 13:05:47.445 11201 11264 I jxcore-log: # 56. Test NETWORK_PROBLEM locally
03-21 13:05:47.445 11201 11264 I jxcore-log: 
,03-21 13:05:47.675 11201 11264 I jxcore-log: # teardown
03-21 13:05:47.675 11201 11264 I jxcore-log: 
,03-21 13:05:47.815  2873  3396 D EnterpriseController: netId is 0
03-21 13:05:47.815  2873  3396 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 13:05:48.855 11201 11264 I jxcore-log: ok 205 Response should be NETWORK_PROBLEM
03-21 13:05:48.855 11201 11264 I jxcore-log: 
,03-21 13:05:48.860 11201 11264 I jxcore-log: ok 206 reject reason should be: Could not establish TCP connection
03-21 13:05:48.860 11201 11264 I jxcore-log: 
,03-21 13:05:48.875 11201 11264 I jxcore-log: # setup
03-21 13:05:48.875 11201 11264 I jxcore-log: 
,03-21 13:05:49.035  5877  6023 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-21 13:05:49.035  5877  6023 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-21 13:05:49.035  5877  6023 W bt-btif : bta_dm_acl_change(), event : 1
03-21 13:05:49.035  5877  6023 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 13:05:49.035  5877  5968 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX
03-21 13:05:49.045  3728  3728 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
03-21 13:05:49.045  5877  5968 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 13:05:49.055  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 13:05:49.055  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED,
03-21 13:05:49.055  3369  3369 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-21 13:05:49.070  3369  3554 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3299cd5a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{8d498b5 5877:com.android.bluetooth/1002}
,03-21 13:05:49.075  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d6f115c
03-21 13:05:49.080  3369  3387 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-21 13:05:49.075  5877  5877 D BtConfig.SecureMode: isSecureModeOn:false
03-21 13:05:49.075  3369  5929 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-21 13:05:49.080  5877  5877 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
03-21 13:05:49.085  3728  3728 D KeyguardViewMediator: isGear1: device is not B1!
,03-21 13:05:49.095  3369  4031 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3299cd5a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:49.100 11201 11264 I jxcore-log: # 57. Test timeout locally
03-21 13:05:49.100 11201 11264 I jxcore-log: 
,03-21 13:05:49.115  3369  4389 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 13:05:49.130 10312 12202 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-21 13:05:49.135 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-21 13:05:49.135 10312 10312 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-21 13:05:49.140 10312 10312 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
03-21 13:05:49.140 10312 10312 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-21 13:05:49.145  3369  3386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3299cd5a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:49.160  3369  3386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3299cd5a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1340846d 11947:com.sec.android.app.shealth/u0a36}
,03-21 13:05:49.170  3369  3721 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3299cd5a u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3964d288 4129:com.google.android.googlequicksearchbox:search/u0a64}
,03-21 13:05:49.180  4129  4129 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-21 13:05:49.180  4129  4129 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-21 13:05:49.210  3369  4389 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:05:49.210  3369  4389 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:05:49.210  3369  4389 D BatteryService: online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
03-21 13:05:49.210  3369  4389 D BatteryService: stay LED for fully charged
03-21 13:05:49.210  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:05:49.215  3369  3369 I MotionRecognitionService: Plugged
03-21 13:05:49.215  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:05:49.215  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:05:49.215  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:05:49.215  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:05:49.215  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:05:49.215  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:05:49.225  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 13:05:49.225  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:05:49.240  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:05:49.240  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:49.240  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:49.240  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:05:49.370  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:14), CUR = 61, LCD = 0
,03-21 13:05:49.555 11201 11264 I jxcore-log: # teardown
03-21 13:05:49.555 11201 11264 I jxcore-log: 
,03-21 13:05:50.840 11201 11264 I jxcore-log: ok 207 Should be NETWORK_PROBLEM caused by timeout
03-21 13:05:50.840 11201 11264 I jxcore-log: 
,03-21 13:05:50.845 11201 11264 I jxcore-log: ok 208 reject reason should be Could not establish TCP connection
03-21 13:05:50.845 11201 11264 I jxcore-log: 
,03-21 13:05:50.860 11201 11264 I jxcore-log: # setup
03-21 13:05:50.860 11201 11264 I jxcore-log: 
,03-21 13:05:50.985 11201 11264 I jxcore-log: # 58. Call the start two times
03-21 13:05:50.985 11201 11264 I jxcore-log: 
,03-21 13:05:51.240 11201 11264 I jxcore-log: # teardown
03-21 13:05:51.240 11201 11264 I jxcore-log: 
,03-21 13:05:51.305 11201 11264 I jxcore-log: ok 209 Call start once
03-21 13:05:51.305 11201 11264 I jxcore-log: 
,03-21 13:05:51.360 11201 11264 I jxcore-log: ok 210 Response should be BEACONS_RETRIEVED_AND_PARSED
03-21 13:05:51.360 11201 11264 I jxcore-log: 
,03-21 13:05:51.360 11201 11264 I jxcore-log: ok 211 must return null after successful call.
03-21 13:05:51.360 11201 11264 I jxcore-log: 
,03-21 13:05:51.370 11201 11264 I jxcore-log: # setup
03-21 13:05:51.370 11201 11264 I jxcore-log: 
,03-21 13:05:51.530 11201 11264 I jxcore-log: # 59. Call the kill before calling the start
03-21 13:05:51.530 11201 11264 I jxcore-log: 
,03-21 13:05:51.745 11201 11264 I jxcore-log: # teardown
03-21 13:05:51.745 11201 11264 I jxcore-log: 
,03-21 13:05:51.875 11201 11264 I jxcore-log: ok 212 Should be Killed
03-21 13:05:51.875 11201 11264 I jxcore-log: 
,03-21 13:05:51.880 11201 11264 I jxcore-log: ok 213 Start after killed
03-21 13:05:51.880 11201 11264 I jxcore-log: 
,03-21 13:05:51.890 11201 11264 I jxcore-log: # setup
03-21 13:05:51.890 11201 11264 I jxcore-log: 
,03-21 13:05:51.970 11201 11264 I jxcore-log: # 60. Call the kill immediately after the start
03-21 13:05:51.970 11201 11264 I jxcore-log: 
,03-21 13:05:52.190 11201 11264 I jxcore-log: # teardown
03-21 13:05:52.190 11201 11264 I jxcore-log: 
,03-21 13:05:52.310 11201 11264 I jxcore-log: ok 214 Should be KILLED
03-21 13:05:52.310 11201 11264 I jxcore-log: 
,03-21 13:05:52.315 11201 11264 I jxcore-log: ok 215 must return null after successful kill
03-21 13:05:52.315 11201 11264 I jxcore-log: 
,03-21 13:05:52.325 11201 11264 I jxcore-log: # setup
03-21 13:05:52.325 11201 11264 I jxcore-log: 
,03-21 13:05:52.405 11201 11264 I jxcore-log: # 61. Call the kill while waiting a response from the server
03-21 13:05:52.405 11201 11264 I jxcore-log: 
,03-21 13:05:52.585 11201 11264 I jxcore-log: # teardown
03-21 13:05:52.585 11201 11264 I jxcore-log: 
,03-21 13:05:54.645 11201 11264 I jxcore-log: ok 216 Should be KILLED
03-21 13:05:54.645 11201 11264 I jxcore-log: 
,03-21 13:05:54.655 11201 11264 I jxcore-log: ok 217 must return null after successful kill
03-21 13:05:54.655 11201 11264 I jxcore-log: 
,03-21 13:05:54.680 11201 11264 I jxcore-log: # setup,
03-21 13:05:54.680 11201 11264 I jxcore-log: 
,03-21 13:05:54.790 11201 11264 I jxcore-log: # 62. Test to exceed the max content size locally
03-21 13:05:54.790 11201 11264 I jxcore-log: 
,03-21 13:05:54.980 11201 11264 I jxcore-log: # teardown
03-21 13:05:54.980 11201 11264 I jxcore-log: 
,03-21 13:05:55.180 11201 11264 I jxcore-log: ok 218 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-21 13:05:55.180 11201 11264 I jxcore-log: 
,03-21 13:05:55.190 11201 11264 I jxcore-log: ok 219 must return null after successful call
03-21 13:05:55.190 11201 11264 I jxcore-log: 
,03-21 13:05:55.205 11201 11264 I jxcore-log: # setup
03-21 13:05:55.205 11201 11264 I jxcore-log: 
,03-21 13:05:55.290 11201 11264 I jxcore-log: # 63. Close the server socket while the client is waiting a response from the server. Local test.
03-21 13:05:55.290 11201 11264 I jxcore-log: 
,03-21 13:05:55.510 11201 11264 I jxcore-log: # teardown
03-21 13:05:55.510 11201 11264 I jxcore-log: 
,03-21 13:05:55.665  3369  3866 E Watchdog: !@Sync 9 [03-21 13:05:55.667]
,03-21 13:05:57.670 11201 11264 I jxcore-log: ok 220 Should be NETWORK_PROBLEM caused closing server socket
03-21 13:05:57.670 11201 11264 I jxcore-log: 
,03-21 13:05:57.675 11201 11264 I jxcore-log: ok 221 Should be Could not establish TCP connection
03-21 13:05:57.675 11201 11264 I jxcore-log: 
,03-21 13:05:57.690 11201 11264 I jxcore-log: # setup
03-21 13:05:57.690 11201 11264 I jxcore-log: 
,03-21 13:05:57.785 11201 11264 I jxcore-log: # 64. Close the client socket while the client is waiting a response from the server. Local test.
03-21 13:05:57.785 11201 11264 I jxcore-log: 
,03-21 13:05:57.970 11201 11264 I jxcore-log: # teardown
03-21 13:05:57.970 11201 11264 I jxcore-log: 
,03-21 13:05:58.815 11201 11201 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 13:05:58.815 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false,
,03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0,
,03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 13:05:58.825 11201 11201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,03-21 13:05:59.355  3369  4031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 13:05:59.355  3369  4031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:05:59.355  3369  4031 D BatteryService: online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,03-21 13:05:59.360  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:05:59.365  3369  4031 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-21 13:05:59.365  3369  4031 D BatteryService: stay LED for fully charged,
,03-21 13:05:59.370  3369  3369 I MotionRecognitionService: Plugged,
03-21 13:05:59.370  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:05:59.370  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:05:59.370  3369  3369 D MotionRecognitionService: skip setTransmitPower. ,
,03-21 13:05:59.380  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-21 13:05:59.380  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 13:05:59.380  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:05:59.405  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 13:05:59.405  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:05:59.415  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 284 (W:14), CUR = 59, LCD = 0
,03-21 13:05:59.415  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:05:59.415  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:59.415  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:05:59.415  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:05:59.995  3369  3620 V AlarmManager: waitForAlarm result :8
,03-21 13:06:00.245 11201 11264 I jxcore-log: ok 222 Should be NETWORK_PROBLEM caused closing client socket
03-21 13:06:00.245 11201 11264 I jxcore-log: 
,03-21 13:06:00.250 11201 11264 I jxcore-log: ok 223 Should be Could not establish TCP connection
03-21 13:06:00.250 11201 11264 I jxcore-log: 
,03-21 13:06:00.270 11201 11264 I jxcore-log: # setup
03-21 13:06:00.270 11201 11264 I jxcore-log: 
,03-21 13:06:00.385 11201 11264 I jxcore-log: # 65. #generatePreambleAndBeacons bad args
03-21 13:06:00.385 11201 11264 I jxcore-log: 
,03-21 13:06:00.490 11201 11264 I jxcore-log: # teardown
03-21 13:06:00.490 11201 11264 I jxcore-log: 
,03-21 13:06:00.600 11201 11264 I jxcore-log: ok 224 publicKeysToNotify cannot be null
03-21 13:06:00.600 11201 11264 I jxcore-log: 
,03-21 13:06:00.605 11201 11264 I jxcore-log: ok 225 ecdh for local device cannot be null
03-21 13:06:00.605 11201 11264 I jxcore-log: 
,03-21 13:06:00.605 11201 11264 I jxcore-log: ok 226 milliseconds cannot be less than 0
03-21 13:06:00.605 11201 11264 I jxcore-log: 
,03-21 13:06:00.610 11201 11264 I jxcore-log: ok 227 milliseconds cannot be 0
03-21 13:06:00.610 11201 11264 I jxcore-log: 
,03-21 13:06:00.615 11201 11264 I jxcore-log: ok 228 milliseconds cannot be greater than one_day
03-21 13:06:00.615 11201 11264 I jxcore-log: 
,03-21 13:06:00.620 11201 11264 I jxcore-log: # setup
03-21 13:06:00.620 11201 11264 I jxcore-log: 
,03-21 13:06:00.710 11201 11264 I jxcore-log: # 66. #generatePreambleAndBeacons empty keys to notify
03-21 13:06:00.710 11201 11264 I jxcore-log: 
,03-21 13:06:00.825 11201 11264 I jxcore-log: # teardown
03-21 13:06:00.825 11201 11264 I jxcore-log: 
,03-21 13:06:01.035 11201 11264 I jxcore-log: ok 229 should be equal
03-21 13:06:01.035 11201 11264 I jxcore-log: 
,03-21 13:06:01.040 11201 11264 I jxcore-log: # setup
03-21 13:06:01.040 11201 11264 I jxcore-log: 
,03-21 13:06:01.175 11201 11264 I jxcore-log: # 67. #generatePreambleAndBeacons multiple keys to notify
03-21 13:06:01.175 11201 11264 I jxcore-log: 
,03-21 13:06:01.335 11201 11264 I jxcore-log: # teardown
03-21 13:06:01.335 11201 11264 I jxcore-log: 
,03-21 13:06:01.655 11201 11264 I jxcore-log: ok 230 should be equal
03-21 13:06:01.655 11201 11264 I jxcore-log: 
,03-21 13:06:01.660 11201 11264 I jxcore-log: ok 231 should be equal
03-21 13:06:01.660 11201 11264 I jxcore-log: 
03-21 13:06:01.660 11201 11264 I jxcore-log: ok 232 (unnamed assert)
03-21 13:06:01.660 11201 11264 I jxcore-log: 
,03-21 13:06:01.660 11201 11264 I jxcore-log: ok 233 should be equal
03-21 13:06:01.660 11201 11264 I jxcore-log: 
,03-21 13:06:01.665 11201 11264 I jxcore-log: # setup
03-21 13:06:01.665 11201 11264 I jxcore-log: 
,03-21 13:06:01.790 11201 11264 I jxcore-log: # 68. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-21 13:06:01.790 11201 11264 I jxcore-log: 
,03-21 13:06:01.950 11201 11264 I jxcore-log: # teardown
03-21 13:06:01.950 11201 11264 I jxcore-log: 
,03-21 13:06:02.125 11201 11264 I jxcore-log: ok 234 should throw
03-21 13:06:02.125 11201 11264 I jxcore-log: 
,03-21 13:06:02.130 11201 11264 I jxcore-log: # setup
03-21 13:06:02.130 11201 11264 I jxcore-log: 
,03-21 13:06:02.275 11201 11264 I jxcore-log: # 69. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-21 13:06:02.275 11201 11264 I jxcore-log: 
,03-21 13:06:02.430 11201 11264 I jxcore-log: # teardown
03-21 13:06:02.430 11201 11264 I jxcore-log: 
,03-21 13:06:02.585 11201 11264 I jxcore-log: ok 235 Preamble expiration must be a 64 bit integer
03-21 13:06:02.585 11201 11264 I jxcore-log: 
,03-21 13:06:02.590 11201 11264 I jxcore-log: # setup
03-21 13:06:02.590 11201 11264 I jxcore-log: 
,03-21 13:06:02.715 11201 11264 I jxcore-log: # 70. #parseBeacons expiration out of range lower
03-21 13:06:02.715 11201 11264 I jxcore-log: 
,03-21 13:06:02.855 11201 11264 I jxcore-log: # teardown
03-21 13:06:02.855 11201 11264 I jxcore-log: 
,03-21 13:06:02.935  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 13:06:03.015 11201 11264 I jxcore-log: ok 236 Expiration out of range
03-21 13:06:03.015 11201 11264 I jxcore-log: 
,03-21 13:06:03.020 11201 11264 I jxcore-log: # setup
03-21 13:06:03.020 11201 11264 I jxcore-log: 
,03-21 13:06:03.140 11201 11264 I jxcore-log: # 71. #parseBeacons expiration out of range lower
03-21 13:06:03.140 11201 11264 I jxcore-log: 
,03-21 13:06:03.275 11201 11264 I jxcore-log: # teardown
03-21 13:06:03.275 11201 11264 I jxcore-log: 
,03-21 13:06:03.420 11201 11264 I jxcore-log: ok 237 Expiration out of range
03-21 13:06:03.420 11201 11264 I jxcore-log: 
,03-21 13:06:03.435 11201 11264 I jxcore-log: # setup
03-21 13:06:03.435 11201 11264 I jxcore-log: 
,03-21 13:06:03.555 11201 11264 I jxcore-log: # 72. #parseBeacons no beacons returns null
03-21 13:06:03.555 11201 11264 I jxcore-log: 
,03-21 13:06:03.700 11201 11264 I jxcore-log: # teardown
03-21 13:06:03.700 11201 11264 I jxcore-log: 
,03-21 13:06:03.850 11201 11264 I jxcore-log: ok 238 should be equal
03-21 13:06:03.850 11201 11264 I jxcore-log: 
,03-21 13:06:03.855 11201 11264 I jxcore-log: # setup
03-21 13:06:03.855 11201 11264 I jxcore-log: 
,03-21 13:06:03.935  3369  3582 I PowerManagerService: [PWL] Off : 225s ago
,03-21 13:06:04.015 11201 11264 I jxcore-log: # 73. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-21 13:06:04.015 11201 11264 I jxcore-log: 
,03-21 13:06:04.155 11201 11264 I jxcore-log: # teardown
03-21 13:06:04.155 11201 11264 I jxcore-log: 
,03-21 13:06:04.325 11201 11264 I jxcore-log: ok 239 Malformed encrypted beacon key ID
03-21 13:06:04.325 11201 11264 I jxcore-log: 
,03-21 13:06:04.330 11201 11264 I jxcore-log: # setup
03-21 13:06:04.330 11201 11264 I jxcore-log: 
,03-21 13:06:04.505 11201 11264 I jxcore-log: # 74. #parseBeacons addressBookCallback fails decrypt
03-21 13:06:04.505 11201 11264 I jxcore-log: 
,03-21 13:06:04.625 11201 11264 I jxcore-log: # teardown
03-21 13:06:04.625 11201 11264 I jxcore-log: 
,03-21 13:06:04.875 11201 11264 I jxcore-log: ok 240 should be equal
03-21 13:06:04.875 11201 11264 I jxcore-log: 
,03-21 13:06:04.875 11201 11264 I jxcore-log: # setup
03-21 13:06:04.875 11201 11264 I jxcore-log: 
,03-21 13:06:04.950 11201 11264 I jxcore-log: # 75. #parseBeacons addressBookCallback returns no matches
03-21 13:06:04.950 11201 11264 I jxcore-log: 
,03-21 13:06:05.160 11201 11264 I jxcore-log: # teardown
03-21 13:06:05.160 11201 11264 I jxcore-log: 
,03-21 13:06:05.410 11201 11264 I jxcore-log: ok 241 should be equal
03-21 13:06:05.410 11201 11264 I jxcore-log: 
,03-21 13:06:05.410 11201 11264 I jxcore-log: ok 242 should be equal
03-21 13:06:05.410 11201 11264 I jxcore-log: 
,03-21 13:06:05.415 11201 11264 I jxcore-log: # setup
03-21 13:06:05.415 11201 11264 I jxcore-log: 
,03-21 13:06:05.630 11201 11264 I jxcore-log: # 76. #parseBeacons addressBookCallback returns spurious match
03-21 13:06:05.630 11201 11264 I jxcore-log: 
,03-21 13:06:05.800 11201 11264 I jxcore-log: # teardown
03-21 13:06:05.800 11201 11264 I jxcore-log: 
,03-21 13:06:06.110 11201 11264 I jxcore-log: ok 243 should be equal
03-21 13:06:06.110 11201 11264 I jxcore-log: 
,03-21 13:06:06.115 11201 11264 I jxcore-log: ok 244 should be equal
03-21 13:06:06.115 11201 11264 I jxcore-log: 
,03-21 13:06:06.115 11201 11264 I jxcore-log: # setup
03-21 13:06:06.115 11201 11264 I jxcore-log: 
,03-21 13:06:06.370 11201 11264 I jxcore-log: # 77. #parseBeacons addressBookCallback returns public key
03-21 13:06:06.370 11201 11264 I jxcore-log: 
,03-21 13:06:06.530 11201 11264 I jxcore-log: # teardown
03-21 13:06:06.530 11201 11264 I jxcore-log: 
,03-21 13:06:06.775 11201 11264 I jxcore-log: ok 245 right number of calls to address book
03-21 13:06:06.775 11201 11264 I jxcore-log: 
,03-21 13:06:06.780 11201 11264 I jxcore-log: ok 246 good preAmble
03-21 13:06:06.780 11201 11264 I jxcore-log: 
,03-21 13:06:06.780 11201 11264 I jxcore-log: ok 247 good unencryptedKeyId
03-21 13:06:06.780 11201 11264 I jxcore-log: 
,03-21 13:06:06.780 11201 11264 I jxcore-log: ok 248 good beacon
03-21 13:06:06.780 11201 11264 I jxcore-log: 
,03-21 13:06:06.785 11201 11264 I jxcore-log: # setup
03-21 13:06:06.785 11201 11264 I jxcore-log: 
,03-21 13:06:06.860 11201 11264 I jxcore-log: # 78. validate generatePskIdentityField
03-21 13:06:06.860 11201 11264 I jxcore-log: 
,03-21 13:06:07.005 11201 11264 I jxcore-log: # teardown
03-21 13:06:07.005 11201 11264 I jxcore-log: 
,03-21 13:06:07.105 11201 11264 I jxcore-log: ok 249 decoded buffers match
03-21 13:06:07.105 11201 11264 I jxcore-log: 
,03-21 13:06:07.110 11201 11264 I jxcore-log: # setup
03-21 13:06:07.110 11201 11264 I jxcore-log: 
,03-21 13:06:07.260 11201 11264 I jxcore-log: # 79. validate generatePskSecret
03-21 13:06:07.260 11201 11264 I jxcore-log: 
,03-21 13:06:07.400 11201 11264 I jxcore-log: # teardown
03-21 13:06:07.400 11201 11264 I jxcore-log: 
,03-21 13:06:07.520 11201 11264 I jxcore-log: ok 250 secrets match
03-21 13:06:07.520 11201 11264 I jxcore-log: 
,03-21 13:06:07.525 11201 11264 I jxcore-log: # setup
03-21 13:06:07.525 11201 11264 I jxcore-log: 
,03-21 13:06:07.610 11201 11264 I jxcore-log: # 80. Start and stop ThaliNotificationServer
03-21 13:06:07.610 11201 11264 I jxcore-log: 
,03-21 13:06:07.795 11201 11264 I jxcore-log: # teardown
03-21 13:06:07.795 11201 11264 I jxcore-log: 
,03-21 13:06:07.940 11201 11264 I jxcore-log: ok 251 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-21 13:06:07.940 11201 11264 I jxcore-log: 
,03-21 13:06:07.940 11201 11264 I jxcore-log: ok 252 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-21 13:06:07.940 11201 11264 I jxcore-log: 
,03-21 13:06:07.945 11201 11264 I jxcore-log: # setup
03-21 13:06:07.945 11201 11264 I jxcore-log: 
,03-21 13:06:08.015 11201 11264 I jxcore-log: # 81. Pass an empty array to ThaliNotificationServer.start
03-21 13:06:08.015 11201 11264 I jxcore-log: 
,03-21 13:06:08.120 11201 11264 I jxcore-log: # teardown
03-21 13:06:08.120 11201 11264 I jxcore-log: 
,03-21 13:06:08.245 11201 11264 I jxcore-log: ok 253 StartUpdateAdvertisingAndListening should not be called
03-21 13:06:08.245 11201 11264 I jxcore-log: 
,03-21 13:06:08.265 11201 11264 I jxcore-log: ok 254 ThaliMobile.StopAdvertisingAndListening should be called once
03-21 13:06:08.265 11201 11264 I jxcore-log: 
,03-21 13:06:08.320 11201 11264 I jxcore-log: ok 255 no error
03-21 13:06:08.320 11201 11264 I jxcore-log: 
,03-21 13:06:08.330 11201 11264 I jxcore-log: ok 256 should be 204
03-21 13:06:08.330 11201 11264 I jxcore-log: 
,03-21 13:06:08.335 11201 11264 I jxcore-log: # setup
03-21 13:06:08.335 11201 11264 I jxcore-log: 
,03-21 13:06:08.430 11201 11264 I jxcore-log: # 82. Pass a string to ThaliNotificationServer.start
03-21 13:06:08.430 11201 11264 I jxcore-log: 
,03-21 13:06:08.560 11201 11264 I jxcore-log: # teardown
03-21 13:06:08.560 11201 11264 I jxcore-log: 
,03-21 13:06:08.695 11201 11264 I jxcore-log: ok 257 StartUpdateAdvertisingAndListening should not be called
03-21 13:06:08.695 11201 11264 I jxcore-log: 
,03-21 13:06:08.700 11201 11264 I jxcore-log: # setup
03-21 13:06:08.700 11201 11264 I jxcore-log: 
,03-21 13:06:08.795 11201 11264 I jxcore-log: # 83. Pass an empty parameter to ThaliNotificationServer.start
03-21 13:06:08.795 11201 11264 I jxcore-log: 
,03-21 13:06:08.950 11201 11264 I jxcore-log: # teardown
03-21 13:06:08.950 11201 11264 I jxcore-log: 
,03-21 13:06:09.100 11201 11264 I jxcore-log: ok 258 StartUpdateAdvertisingAndListening should not be called
03-21 13:06:09.100 11201 11264 I jxcore-log: 
,03-21 13:06:09.105 11201 11264 I jxcore-log: # setup
03-21 13:06:09.105 11201 11264 I jxcore-log: 
,03-21 13:06:09.220 11201 11264 I jxcore-log: # 84. Make an HTTP request to /NotificationBeacons
03-21 13:06:09.220 11201 11264 I jxcore-log: 
,03-21 13:06:09.340 11201 11264 I jxcore-log: # teardown
03-21 13:06:09.340 11201 11264 I jxcore-log: 
,03-21 13:06:09.425  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 282 (W:14), CUR = 58, LCD = 0
,03-21 13:06:09.465  3369  4389 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:06:09.465  3369  4389 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:06:09.465  3369  4389 D BatteryService: online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
03-21 13:06:09.465  3369  4389 D BatteryService: stay LED for fully charged
03-21 13:06:09.465  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:06:09.470  3369  3369 I MotionRecognitionService: Plugged
03-21 13:06:09.470  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:06:09.470  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:06:09.470  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:06:09.475  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:06:09.475  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:06:09.475  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:06:09.480  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 13:06:09.480  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:06:09.495  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:06:09.495  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:09.495  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:09.495  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:06:09.535 11201 11264 I jxcore-log: ok 259 no error
03-21 13:06:09.535 11201 11264 I jxcore-log: 
,03-21 13:06:09.540 11201 11264 I jxcore-log: ok 260 should be 200
03-21 13:06:09.540 11201 11264 I jxcore-log: 
,03-21 13:06:09.540 11201 11264 I jxcore-log: ok 261 should be equal
03-21 13:06:09.540 11201 11264 I jxcore-log: 
03-21 13:06:09.540 11201 11264 I jxcore-log: ok 262 should be equal
03-21 13:06:09.540 11201 11264 I jxcore-log: 
,03-21 13:06:09.565 11201 11264 I jxcore-log: ok 263 (unnamed assert)
03-21 13:06:09.565 11201 11264 I jxcore-log: 
,03-21 13:06:09.585 11201 11264 I jxcore-log: ok 264 no error
03-21 13:06:09.585 11201 11264 I jxcore-log: 
03-21 13:06:09.585 11201 11264 I jxcore-log: ok 265 should be 204
03-21 13:06:09.585 11201 11264 I jxcore-log: 
,03-21 13:06:09.590 11201 11264 I jxcore-log: # setup
03-21 13:06:09.590 11201 11264 I jxcore-log: 
,03-21 13:06:09.705 11201 11264 I jxcore-log: # 85. Make an HTTP request to /NotificationBeacons (no keys)
03-21 13:06:09.705 11201 11264 I jxcore-log: 
,03-21 13:06:09.820 11201 11264 I jxcore-log: # teardown
03-21 13:06:09.820 11201 11264 I jxcore-log: 
,03-21 13:06:09.985 11201 11264 I jxcore-log: ok 266 error should be null
03-21 13:06:09.985 11201 11264 I jxcore-log: 
,03-21 13:06:09.990 11201 11264 I jxcore-log: ok 267 should be 204
03-21 13:06:09.990 11201 11264 I jxcore-log: 
,03-21 13:06:10.000 11201 11264 I jxcore-log: # setup
03-21 13:06:10.000 11201 11264 I jxcore-log: 
,03-21 13:06:10.050 11201 11264 I jxcore-log: # 86. Make an HTTP request to /NotificationBeaconsbefore calling start
03-21 13:06:10.050 11201 11264 I jxcore-log: 
,03-21 13:06:10.215 11201 11264 I jxcore-log: # teardown
03-21 13:06:10.215 11201 11264 I jxcore-log: 
,03-21 13:06:10.375 11201 11264 I jxcore-log: ok 268 should be 404
03-21 13:06:10.375 11201 11264 I jxcore-log: 
,03-21 13:06:10.385 11201 11264 I jxcore-log: # setup
03-21 13:06:10.385 11201 11264 I jxcore-log: 
,03-21 13:06:10.480 11201 11264 I jxcore-log: # 87. #testThaliPeerAction - test getters
03-21 13:06:10.480 11201 11264 I jxcore-log: 
,03-21 13:06:10.560 11201 11264 I jxcore-log: # teardown
03-21 13:06:10.560 11201 11264 I jxcore-log: 
,03-21 13:06:10.640 11201 11264 I jxcore-log: ok 269 getPeerIdentifier
03-21 13:06:10.640 11201 11264 I jxcore-log: 
,03-21 13:06:10.640 11201 11264 I jxcore-log: ok 270 getConnectionType
03-21 13:06:10.640 11201 11264 I jxcore-log: 
,03-21 13:06:10.645 11201 11264 I jxcore-log: ok 271 getActionType
03-21 13:06:10.645 11201 11264 I jxcore-log: 
,03-21 13:06:10.645 11201 11264 I jxcore-log: ok 272 getActionState
03-21 13:06:10.645 11201 11264 I jxcore-log: 
,03-21 13:06:10.650 11201 11264 I jxcore-log: # setup
03-21 13:06:10.650 11201 11264 I jxcore-log: 
,03-21 13:06:10.725 11201 11264 I jxcore-log: # 88. #testThaliPeerAction - start and kill
03-21 13:06:10.725 11201 11264 I jxcore-log: 
,03-21 13:06:10.820 11201 11264 I jxcore-log: # teardown
03-21 13:06:10.820 11201 11264 I jxcore-log: 
,03-21 13:06:10.885 11201 11264 I jxcore-log: ok 273 initial state
03-21 13:06:10.885 11201 11264 I jxcore-log: 
,03-21 13:06:10.895 11201 11264 I jxcore-log: ok 274 after start
03-21 13:06:10.895 11201 11264 I jxcore-log: 
,03-21 13:06:10.900 11201 11264 I jxcore-log: ok 275 after kill
03-21 13:06:10.900 11201 11264 I jxcore-log: 
,03-21 13:06:10.905 11201 11264 I jxcore-log: # setup
03-21 13:06:10.905 11201 11264 I jxcore-log: 
,03-21 13:06:11.015 11201 11264 I jxcore-log: # 89. #testThaliPeerAction - double start
03-21 13:06:11.015 11201 11264 I jxcore-log: 
,03-21 13:06:11.100 11201 11264 I jxcore-log: # teardown
03-21 13:06:11.100 11201 11264 I jxcore-log: 
,03-21 13:06:11.215 11201 11264 I jxcore-log: ok 276 should be equal
03-21 13:06:11.215 11201 11264 I jxcore-log: 
,03-21 13:06:11.220 11201 11264 I jxcore-log: # setup
03-21 13:06:11.220 11201 11264 I jxcore-log: 
,03-21 13:06:11.360 11201 11264 I jxcore-log: # 90. #testThaliPeerAction - start after kill
03-21 13:06:11.360 11201 11264 I jxcore-log: 
,03-21 13:06:11.450 11201 11264 I jxcore-log: # teardown
03-21 13:06:11.450 11201 11264 I jxcore-log: 
,03-21 13:06:11.575 11201 11264 I jxcore-log: ok 277 clean kill
03-21 13:06:11.575 11201 11264 I jxcore-log: 
,03-21 13:06:11.580 11201 11264 I jxcore-log: ok 278 should be equal
03-21 13:06:11.580 11201 11264 I jxcore-log: 
,03-21 13:06:11.585 11201 11264 I jxcore-log: # setup
03-21 13:06:11.585 11201 11264 I jxcore-log: 
,03-21 13:06:11.670 11201 11264 I jxcore-log: # 91. #testThaliPeerAction - make sure ids are unique
03-21 13:06:11.670 11201 11264 I jxcore-log: 
,03-21 13:06:11.770 11201 11264 I jxcore-log: # teardown
03-21 13:06:11.770 11201 11264 I jxcore-log: 
,03-21 13:06:11.875 11201 11264 I jxcore-log: ok 279 should not be equal
03-21 13:06:11.875 11201 11264 I jxcore-log: 
,03-21 13:06:11.880 11201 11264 I jxcore-log: # setup
03-21 13:06:11.880 11201 11264 I jxcore-log: 
,03-21 13:06:11.955 11201 11264 I jxcore-log: # 92. Test PeerConnectionInformation basics
03-21 13:06:11.955 11201 11264 I jxcore-log: 
,03-21 13:06:12.045 11201 11264 I jxcore-log: # teardown
03-21 13:06:12.045 11201 11264 I jxcore-log: 
,03-21 13:06:12.155 11201 11264 I jxcore-log: ok 280 getHostAddress works
03-21 13:06:12.155 11201 11264 I jxcore-log: 
,03-21 13:06:12.155 11201 11264 I jxcore-log: ok 281 getPortNumber works
03-21 13:06:12.155 11201 11264 I jxcore-log: 
,03-21 13:06:12.160 11201 11264 I jxcore-log: ok 282 getSuggestedTCPTimeout works
03-21 13:06:12.160 11201 11264 I jxcore-log: 
,03-21 13:06:12.165 11201 11264 I jxcore-log: # setup
03-21 13:06:12.165 11201 11264 I jxcore-log: 
,03-21 13:06:12.330 11201 11264 I jxcore-log: # 93. Test PeerDictionary basic functionality
03-21 13:06:12.330 11201 11264 I jxcore-log: 
,03-21 13:06:12.430 11201 11264 I jxcore-log: # teardown
03-21 13:06:12.430 11201 11264 I jxcore-log: 
,03-21 13:06:12.560 11201 11264 I jxcore-log: ok 283 Entry counter must be 1
03-21 13:06:12.560 11201 11264 I jxcore-log: 
,03-21 13:06:12.560 11201 11264 I jxcore-log: ok 284 Size must be 1
03-21 13:06:12.560 11201 11264 I jxcore-log: 
,03-21 13:06:12.560 11201 11264 I jxcore-log: ok 285 Entry counter must be 2
03-21 13:06:12.560 11201 11264 I jxcore-log: 
,03-21 13:06:12.565 11201 11264 I jxcore-log: ok 286 Size must be 2
03-21 13:06:12.565 11201 11264 I jxcore-log: 
,03-21 13:06:12.570 11201 11264 I jxcore-log: ok 287 Entry2 should not be found
03-21 13:06:12.570 11201 11264 I jxcore-log: 
,03-21 13:06:12.570 11201 11264 I jxcore-log: ok 288 Size must be 1
03-21 13:06:12.570 11201 11264 I jxcore-log: 
,03-21 13:06:12.575 11201 11264 I jxcore-log: ok 289 Size must be 0
03-21 13:06:12.575 11201 11264 I jxcore-log: 
,03-21 13:06:12.580 11201 11264 I jxcore-log: ok 290 entry not found must be thrown
03-21 13:06:12.580 11201 11264 I jxcore-log: 
,03-21 13:06:12.585 11201 11264 I jxcore-log: # setup
03-21 13:06:12.585 11201 11264 I jxcore-log: 
,03-21 13:06:12.710 11201 11264 I jxcore-log: # 94. Test PeerDictionary with multiple entries.
03-21 13:06:12.710 11201 11264 I jxcore-log: 
,03-21 13:06:12.835 11201 11264 I jxcore-log: # teardown
03-21 13:06:12.835 11201 11264 I jxcore-log: 
,03-21 13:06:13.625 11201 11264 I jxcore-log: ok 291 Size must be100
03-21 13:06:13.625 11201 11264 I jxcore-log: 
,03-21 13:06:13.625 11201 11264 I jxcore-log: ok 292 Entries between 20 and MAXSIZE + 20 should exist
03-21 13:06:13.625 11201 11264 I jxcore-log: 
,03-21 13:06:14.145 11201 11264 I jxcore-log: ok 293 WAITING state entry should not be removed
03-21 13:06:14.145 11201 11264 I jxcore-log: 
,03-21 13:06:14.145 11201 11264 I jxcore-log: # setup
03-21 13:06:14.145 11201 11264 I jxcore-log: 
,03-21 13:06:14.315 11201 11264 I jxcore-log: # 95. RESOLVED entries are removed before WAITING state entry.
03-21 13:06:14.315 11201 11264 I jxcore-log: 
,03-21 13:06:14.400 11201 11264 I jxcore-log: # teardown
03-21 13:06:14.400 11201 11264 I jxcore-log: 
,03-21 13:06:15.200 11201 11264 I jxcore-log: ok 294 Entries between 6 and MAXSIZE + 4 should exist
03-21 13:06:15.200 11201 11264 I jxcore-log: 
03-21 13:06:15.200 11201 11264 I jxcore-log: ok 295 Size should be MAXSIZE
03-21 13:06:15.200 11201 11264 I jxcore-log: 
03-21 13:06:15.200 11201 11264 I jxcore-log: ok 296 Size should be MAXSIZE+6
03-21 13:06:15.200 11201 11264 I jxcore-log: 
,03-21 13:06:15.200 11201 11264 I jxcore-log: # setup
03-21 13:06:15.200 11201 11264 I jxcore-log: 
,03-21 13:06:15.330 11201 11264 I jxcore-log: # 96. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
03-21 13:06:15.330 11201 11264 I jxcore-log: 
,03-21 13:06:15.430 11201 11264 I jxcore-log: # teardown
03-21 13:06:15.430 11201 11264 I jxcore-log: 
,03-21 13:06:16.235 11201 11264 I jxcore-log: ok 297 WAITING state entry should not be removed
03-21 13:06:16.235 11201 11264 I jxcore-log: 
,03-21 13:06:16.235 11201 11264 I jxcore-log: ok 298 Waiting entries between 6 and MAXSIZE + 4 should exist
03-21 13:06:16.235 11201 11264 I jxcore-log: 
03-21 13:06:16.235 11201 11264 I jxcore-log: ok 299 Size should be MAXSIZE
03-21 13:06:16.235 11201 11264 I jxcore-log: 
03-21 13:06:16.235 11201 11264 I jxcore-log: ok 300 entryCounter should be MAXSIZE+6
03-21 13:06:16.235 11201 11264 I jxcore-log: 
03-21 13:06:16.235 11201 11264 I jxcore-log: # setup
03-21 13:06:16.235 11201 11264 I jxcore-log: 
,03-21 13:06:16.315 11201 11264 I jxcore-log: # 97. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-21 13:06:16.315 11201 11264 I jxcore-log: 
,03-21 13:06:16.530 11201 11264 I jxcore-log: # teardown
03-21 13:06:16.530 11201 11264 I jxcore-log: 
,03-21 13:06:17.420 11201 11264 I jxcore-log: ok 301 Kill should be called once
03-21 13:06:17.420 11201 11264 I jxcore-log: 
03-21 13:06:17.420 11201 11264 I jxcore-log: ok 302 Size should be 100
03-21 13:06:17.420 11201 11264 I jxcore-log: 
,03-21 13:06:17.425 11201 11264 I jxcore-log: # setup
03-21 13:06:17.425 11201 11264 I jxcore-log: 
,03-21 13:06:17.550 11201 11264 I jxcore-log: # 98. #ThaliPeerPoolInterface - bad enqueues
03-21 13:06:17.550 11201 11264 I jxcore-log: 
,03-21 13:06:17.610 11201 11264 I jxcore-log: # teardown
03-21 13:06:17.610 11201 11264 I jxcore-log: 
,03-21 13:06:17.735 11201 11264 I jxcore-log: ok 303 null arg
03-21 13:06:17.735 11201 11264 I jxcore-log: 
,03-21 13:06:17.740 11201 11264 I jxcore-log: ok 304 wrong arg type
03-21 13:06:17.740 11201 11264 I jxcore-log: 
,03-21 13:06:17.745 11201 11264 I jxcore-log: ok 305 wrong state
03-21 13:06:17.745 11201 11264 I jxcore-log: 
,03-21 13:06:17.750 11201 11264 I jxcore-log: # setup
03-21 13:06:17.750 11201 11264 I jxcore-log: 
,03-21 13:06:17.870 11201 11264 I jxcore-log: # 99. #ThaliPeerPoolInterface - do not allow same object type
03-21 13:06:17.870 11201 11264 I jxcore-log: 
,03-21 13:06:17.940 11201 11264 I jxcore-log: # teardown
03-21 13:06:17.940 11201 11264 I jxcore-log: 
,03-21 13:06:18.035 11201 11264 I jxcore-log: ok 306 good enqueue
03-21 13:06:18.035 11201 11264 I jxcore-log: 
,03-21 13:06:18.040 11201 11264 I jxcore-log: ok 307 should be equal
03-21 13:06:18.040 11201 11264 I jxcore-log: 
,03-21 13:06:18.045 11201 11264 I jxcore-log: # setup
03-21 13:06:18.045 11201 11264 I jxcore-log: 
,03-21 13:06:18.140 11201 11264 I jxcore-log: # 100. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-21 13:06:18.140 11201 11264 I jxcore-log: 
,03-21 13:06:18.220 11201 11264 I jxcore-log: # teardown
03-21 13:06:18.220 11201 11264 I jxcore-log: 
,03-21 13:06:18.295 11201 11264 I jxcore-log: ok 308 good enqueue
03-21 13:06:18.295 11201 11264 I jxcore-log: 
,03-21 13:06:18.295 11201 11264 I jxcore-log: ok 309 2nd good enqueue
03-21 13:06:18.295 11201 11264 I jxcore-log: 
03-21 13:06:18.300 11201 11264 I jxcore-log: ok 310 we are in the pool
03-21 13:06:18.300 11201 11264 I jxcore-log: 
,03-21 13:06:18.300 11201 11264 I jxcore-log: ok 311 We are out of the pool
03-21 13:06:18.300 11201 11264 I jxcore-log: 
,03-21 13:06:18.305 11201 11264 I jxcore-log: ok 312 Action was killed
03-21 13:06:18.305 11201 11264 I jxcore-log: 
,03-21 13:06:18.305 11201 11264 I jxcore-log: ok 313 The original kill was called too
03-21 13:06:18.305 11201 11264 I jxcore-log: 
03-21 13:06:18.305 11201 11264 I jxcore-log: ok 314 second item is still in queue
03-21 13:06:18.305 11201 11264 I jxcore-log: 
,03-21 13:06:18.310 11201 11264 I jxcore-log: # setup
03-21 13:06:18.310 11201 11264 I jxcore-log: 
,03-21 13:06:18.425 11201 11264 I jxcore-log: # 101. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
03-21 13:06:18.425 11201 11264 I jxcore-log: 
,03-21 13:06:18.500 11201 11264 I jxcore-log: # teardown
03-21 13:06:18.500 11201 11264 I jxcore-log: 
,03-21 13:06:18.630 11201 11264 I jxcore-log: ok 315 good enqueue
03-21 13:06:18.630 11201 11264 I jxcore-log: 
,03-21 13:06:18.635 11201 11264 I jxcore-log: ok 316 first kill
03-21 13:06:18.635 11201 11264 I jxcore-log: 
,03-21 13:06:18.635 11201 11264 I jxcore-log: ok 317 second NOOP kill
03-21 13:06:18.635 11201 11264 I jxcore-log: 
,03-21 13:06:18.640 11201 11264 I jxcore-log: # setup
03-21 13:06:18.640 11201 11264 I jxcore-log: 
,03-21 13:06:18.815 11201 11264 I jxcore-log: # 102. compareBufferArrays
03-21 13:06:18.815 11201 11264 I jxcore-log: 
,03-21 13:06:18.915 11201 11264 I jxcore-log: # teardown
03-21 13:06:18.915 11201 11264 I jxcore-log: 
,03-21 13:06:18.985 11201 11264 I jxcore-log: ok 318 should throw
03-21 13:06:18.985 11201 11264 I jxcore-log: 
,03-21 13:06:18.990 11201 11264 I jxcore-log: ok 319 should throw
03-21 13:06:18.990 11201 11264 I jxcore-log: 
,03-21 13:06:18.995 11201 11264 I jxcore-log: ok 320 (unnamed assert)
03-21 13:06:18.995 11201 11264 I jxcore-log: 
,03-21 13:06:18.995 11201 11264 I jxcore-log: ok 321 (unnamed assert)
03-21 13:06:18.995 11201 11264 I jxcore-log: 
,03-21 13:06:18.995 11201 11264 I jxcore-log: ok 322 (unnamed assert)
03-21 13:06:18.995 11201 11264 I jxcore-log: 
,03-21 13:06:19.000 11201 11264 I jxcore-log: ok 323 (unnamed assert)
03-21 13:06:19.000 11201 11264 I jxcore-log: 
,03-21 13:06:19.000 11201 11264 I jxcore-log: ok 324 (unnamed assert)
03-21 13:06:19.000 11201 11264 I jxcore-log: 
,03-21 13:06:19.005 11201 11264 I jxcore-log: # setup
03-21 13:06:19.005 11201 11264 I jxcore-log: 
,03-21 13:06:19.055 11201 11264 I jxcore-log: # 103. Call start twice and get error
03-21 13:06:19.055 11201 11264 I jxcore-log: 
,03-21 13:06:19.155 11201 11264 I jxcore-log: # teardown
03-21 13:06:19.155 11201 11264 I jxcore-log: 
,03-21 13:06:19.245 11201 11264 I jxcore-log: ok 325 should throw
03-21 13:06:19.245 11201 11264 I jxcore-log: 
,03-21 13:06:19.250 11201 11264 I jxcore-log: # setup
03-21 13:06:19.250 11201 11264 I jxcore-log: 
,03-21 13:06:19.350 11201 11264 I jxcore-log: # 104. Start and make sure it runs
03-21 13:06:19.350 11201 11264 I jxcore-log: 
,03-21 13:06:19.420 11201 11264 I jxcore-log: # teardown
03-21 13:06:19.420 11201 11264 I jxcore-log: 
,03-21 13:06:19.440  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:14), CUR = 58, LCD = 0
,03-21 13:06:19.595  3369  5929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 13:06:19.595  3369  5929 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:06:19.595  3369  5929 D BatteryService: online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
03-21 13:06:19.595  3369  5929 D BatteryService: stay LED for fully charged
,03-21 13:06:19.595  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:06:19.600  3369  3369 I MotionRecognitionService: Plugged
03-21 13:06:19.600  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:06:19.600  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:06:19.600  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:06:19.605  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:06:19.605  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED,
03-21 13:06:19.605  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:06:19.615 11201 11264 I jxcore-log: # setup
03-21 13:06:19.615 11201 11264 I jxcore-log: 
,03-21 13:06:19.620  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 13:06:19.625  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:06:19.635  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:06:19.635  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:19.635  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:19.635  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:06:19.650 11201 11264 I jxcore-log: # 105. Make sure getTimeWhenRun is right after start
03-21 13:06:19.650 11201 11264 I jxcore-log: 
,03-21 13:06:19.765 11201 11264 I jxcore-log: # teardown
03-21 13:06:19.765 11201 11264 I jxcore-log: 
,03-21 13:06:19.865 11201 11264 I jxcore-log: ok 326 (unnamed assert)
03-21 13:06:19.865 11201 11264 I jxcore-log: 
,03-21 13:06:19.870 11201 11264 I jxcore-log: # setup
03-21 13:06:19.870 11201 11264 I jxcore-log: 
,03-21 13:06:19.990 11201 11264 I jxcore-log: # 106. Make sure getTimeWhenRun is -1 after function is called
03-21 13:06:19.990 11201 11264 I jxcore-log: 
,03-21 13:06:20.065 11201 11264 I jxcore-log: # teardown
03-21 13:06:20.065 11201 11264 I jxcore-log: 
,03-21 13:06:20.205 11201 11264 I jxcore-log: ok 327 should be equal
03-21 13:06:20.205 11201 11264 I jxcore-log: 
,03-21 13:06:20.215 11201 11264 I jxcore-log: # setup
03-21 13:06:20.215 11201 11264 I jxcore-log: 
,03-21 13:06:20.375 11201 11264 I jxcore-log: # 107. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
03-21 13:06:20.375 11201 11264 I jxcore-log: 
,03-21 13:06:20.505 11201 11264 I jxcore-log: # teardown
03-21 13:06:20.505 11201 11264 I jxcore-log: 
,03-21 13:06:20.630 11201 11264 I jxcore-log: ok 328 should be equal
03-21 13:06:20.630 11201 11264 I jxcore-log: 
,03-21 13:06:20.635 11201 11264 I jxcore-log: ok 329 should be equal
03-21 13:06:20.635 11201 11264 I jxcore-log: 
,03-21 13:06:20.640 11201 11264 I jxcore-log: ok 330 should throw
03-21 13:06:20.640 11201 11264 I jxcore-log: 
,03-21 13:06:20.650 11201 11264 I jxcore-log: # setup
03-21 13:06:20.650 11201 11264 I jxcore-log: 
,03-21 13:06:20.790 11201 11264 I jxcore-log: # 108. Test TransientState
03-21 13:06:20.790 11201 11264 I jxcore-log: 
,03-21 13:06:20.890 11201 11264 I jxcore-log: # teardown
03-21 13:06:20.890 11201 11264 I jxcore-log: 
,03-21 13:06:21.015 11201 11264 I jxcore-log: ok 331 should throw
03-21 13:06:21.015 11201 11264 I jxcore-log: 
,03-21 13:06:21.020 11201 11264 I jxcore-log: ok 332 should throw
03-21 13:06:21.020 11201 11264 I jxcore-log: 
,03-21 13:06:21.020 11201 11264 I jxcore-log: ok 333 should be equal
03-21 13:06:21.020 11201 11264 I jxcore-log: 
,03-21 13:06:21.025 11201 11264 I jxcore-log: ok 334 should be equal
03-21 13:06:21.025 11201 11264 I jxcore-log: 
,03-21 13:06:21.025 11201 11264 I jxcore-log: ok 335 should be equal
03-21 13:06:21.025 11201 11264 I jxcore-log: 
,03-21 13:06:21.025 11201 11264 I jxcore-log: ok 336 should be equal
03-21 13:06:21.025 11201 11264 I jxcore-log: 
,03-21 13:06:21.030 11201 11264 I jxcore-log: ok 337 (unnamed assert)
03-21 13:06:21.030 11201 11264 I jxcore-log: 
,03-21 13:06:21.030 11201 11264 I jxcore-log: ok 338 (unnamed assert)
03-21 13:06:21.030 11201 11264 I jxcore-log: 
,03-21 13:06:21.035 11201 11264 I jxcore-log: # setup
03-21 13:06:21.035 11201 11264 I jxcore-log: 
,03-21 13:06:21.115 11201 11264 I jxcore-log: # 109. No peers and empty database
03-21 13:06:21.115 11201 11264 I jxcore-log: 
,03-21 13:06:21.215 11201 11264 I jxcore-log: # teardown
03-21 13:06:21.215 11201 11264 I jxcore-log: 
,03-21 13:06:21.495 11201 11264 I jxcore-log: ok 339 verify failed
03-21 13:06:21.495 11201 11264 I jxcore-log: 
,03-21 13:06:21.495 11201 11264 I jxcore-log: ok 340 constructor called once
03-21 13:06:21.495 11201 11264 I jxcore-log: 
,03-21 13:06:21.495 11201 11264 I jxcore-log: ok 341 constructor called with right args
03-21 13:06:21.495 11201 11264 I jxcore-log: 
,03-21 13:06:21.500 11201 11264 I jxcore-log: ok 342 match start arg
03-21 13:06:21.500 11201 11264 I jxcore-log: 
,03-21 13:06:21.500 11201 11264 I jxcore-log: ok 343 start called once
03-21 13:06:21.500 11201 11264 I jxcore-log: 
03-21 13:06:21.500 11201 11264 I jxcore-log: ok 344 stop called once
03-21 13:06:21.500 11201 11264 I jxcore-log: 
,03-21 13:06:21.500 11201 11264 I jxcore-log: ok 345 stop after start
03-21 13:06:21.500 11201 11264 I jxcore-log: 
,03-21 13:06:21.505 11201 11264 I jxcore-log: # setup
03-21 13:06:21.505 11201 11264 I jxcore-log: 
,03-21 13:06:21.705 11201 11264 I jxcore-log: # 110. One peer and empty DB
03-21 13:06:21.705 11201 11264 I jxcore-log: 
,03-21 13:06:21.805 11201 11264 I jxcore-log: # teardown
03-21 13:06:21.805 11201 11264 I jxcore-log: 
,03-21 13:06:22.150 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:22.150 11201 11264 I jxcore-log: 
,03-21 13:06:22.155 11201 11264 I jxcore-log: ok 346 verify failed
03-21 13:06:22.155 11201 11264 I jxcore-log: 
,03-21 13:06:22.155 11201 11264 I jxcore-log: ok 347 constructor called once
03-21 13:06:22.155 11201 11264 I jxcore-log: 
,03-21 13:06:22.155 11201 11264 I jxcore-log: ok 348 constructor called with right args
03-21 13:06:22.155 11201 11264 I jxcore-log: 
,03-21 13:06:22.160 11201 11264 I jxcore-log: ok 349 match start arg
03-21 13:06:22.160 11201 11264 I jxcore-log: 
,03-21 13:06:22.160 11201 11264 I jxcore-log: ok 350 start called once
03-21 13:06:22.160 11201 11264 I jxcore-log: 
03-21 13:06:22.160 11201 11264 I jxcore-log: ok 351 stop called once
03-21 13:06:22.160 11201 11264 I jxcore-log: 
,03-21 13:06:22.160 11201 11264 I jxcore-log: ok 352 stop after start
03-21 13:06:22.160 11201 11264 I jxcore-log: 
,03-21 13:06:22.170 11201 11264 I jxcore-log: # setup
03-21 13:06:22.170 11201 11264 I jxcore-log: 
,03-21 13:06:22.305 11201 11264 I jxcore-log: # 111. One peer with _Local set behind current seq
03-21 13:06:22.305 11201 11264 I jxcore-log: 
,03-21 13:06:22.445 11201 11264 I jxcore-log: # teardown
03-21 13:06:22.445 11201 11264 I jxcore-log: 
,03-21 13:06:22.695 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:22.695 11201 11264 I jxcore-log: 
,03-21 13:06:22.695 11201 11264 I jxcore-log: ok 353 verify failed
03-21 13:06:22.695 11201 11264 I jxcore-log: 
03-21 13:06:22.695 11201 11264 I jxcore-log: ok 354 constructor called once
03-21 13:06:22.695 11201 11264 I jxcore-log: 
,03-21 13:06:22.695 11201 11264 I jxcore-log: ok 355 constructor called with right args
03-21 13:06:22.695 11201 11264 I jxcore-log: 
03-21 13:06:22.695 11201 11264 I jxcore-log: ok 356 match start arg
03-21 13:06:22.695 11201 11264 I jxcore-log: 
03-21 13:06:22.695 11201 11264 I jxcore-log: ok 357 start called once
03-21 13:06:22.695 11201 11264 I jxcore-log: 
03-21 13:06:22.695 11201 11264 I jxcore-log: ok 358 stop called once
03-21 13:06:22.695 11201 11264 I jxcore-log: 
03-21 13:06:22.695 11201 11264 I jxcore-log: ok 359 stop after start
03-21 13:06:22.695 11201 11264 I jxcore-log: 
,03-21 13:06:22.700 11201 11264 I jxcore-log: # setup
03-21 13:06:22.700 11201 11264 I jxcore-log: 
,03-21 13:06:22.840 11201 11264 I jxcore-log: # 112. One peer with _Local set equal to current seq
03-21 13:06:22.840 11201 11264 I jxcore-log: 
,03-21 13:06:22.945  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 13:06:22.980 11201 11264 I jxcore-log: # teardown
03-21 13:06:22.980 11201 11264 I jxcore-log: 
,03-21 13:06:23.285 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:23.285 11201 11264 I jxcore-log: 
,03-21 13:06:23.290 11201 11264 I jxcore-log: ok 360 verify failed
03-21 13:06:23.290 11201 11264 I jxcore-log: 
03-21 13:06:23.290 11201 11264 I jxcore-log: ok 361 constructor called once
03-21 13:06:23.290 11201 11264 I jxcore-log: 
,03-21 13:06:23.290 11201 11264 I jxcore-log: ok 362 constructor called with right args
03-21 13:06:23.290 11201 11264 I jxcore-log: 
03-21 13:06:23.290 11201 11264 I jxcore-log: ok 363 match start arg
03-21 13:06:23.290 11201 11264 I jxcore-log: 
03-21 13:06:23.290 11201 11264 I jxcore-log: ok 364 start called once
03-21 13:06:23.290 11201 11264 I jxcore-log: 
,03-21 13:06:23.290 11201 11264 I jxcore-log: ok 365 stop called once
03-21 13:06:23.290 11201 11264 I jxcore-log: 
03-21 13:06:23.290 11201 11264 I jxcore-log: ok 366 stop after start
03-21 13:06:23.290 11201 11264 I jxcore-log: 
,03-21 13:06:23.295 11201 11264 I jxcore-log: # setup
03-21 13:06:23.295 11201 11264 I jxcore-log: 
,03-21 13:06:23.300  3369  3609 D TimaService: TIMA: TimaService scheduler is intialized. 
,03-21 13:06:23.300  3369  3609 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-21 13:06:23.300  3369  3608 D TimaService: TimaServiceHandler.handleMessage what =1
,03-21 13:06:23.305  3369  3609 I TLC_TIMA_PKM_initialize: initializing...
03-21 13:06:23.305  3369  3609 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
03-21 13:06:23.305  3369  3609 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: root = 0, root_len = 1
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: device_id = 0x0
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: tlc_open() was called
03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: Opening MobiCore device
,03-21 13:06:23.305  3369  3609 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,03-21 13:06:23.310  3369  3609 I TZ: mc_tlc_communication: Opening the session
,03-21 13:06:23.320  3369  3609 I TZ: mc_tlc_communication: tlc_open() succeeded
,03-21 13:06:23.330  3369  3609 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-21 13:06:23.400 11201 11264 I jxcore-log: # 113. One peer with _Local set ahead of current seq (and no this should not happen)
03-21 13:06:23.400 11201 11264 I jxcore-log: 
,03-21 13:06:23.555 11201 11264 I jxcore-log: # teardown
03-21 13:06:23.555 11201 11264 I jxcore-log: 
,03-21 13:06:23.900 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:23.900 11201 11264 I jxcore-log: 
,03-21 13:06:23.905 11201 11264 I jxcore-log: ok 367 verify failed
03-21 13:06:23.905 11201 11264 I jxcore-log: 
03-21 13:06:23.905 11201 11264 I jxcore-log: ok 368 constructor called once
03-21 13:06:23.905 11201 11264 I jxcore-log: 
,03-21 13:06:23.905 11201 11264 I jxcore-log: ok 369 constructor called with right args
03-21 13:06:23.905 11201 11264 I jxcore-log: 
03-21 13:06:23.905 11201 11264 I jxcore-log: ok 370 match start arg
03-21 13:06:23.905 11201 11264 I jxcore-log: 
03-21 13:06:23.905 11201 11264 I jxcore-log: ok 371 start called once
03-21 13:06:23.905 11201 11264 I jxcore-log: 
03-21 13:06:23.905 11201 11264 I jxcore-log: ok 372 stop called once
03-21 13:06:23.905 11201 11264 I jxcore-log: 
03-21 13:06:23.905 11201 11264 I jxcore-log: ok 373 stop after start
03-21 13:06:23.905 11201 11264 I jxcore-log: 
,03-21 13:06:23.910 11201 11264 I jxcore-log: # setup
03-21 13:06:23.910 11201 11264 I jxcore-log: 
,03-21 13:06:24.015 11201 11264 I jxcore-log: # 114. Three peers, one not in DB, one behind and one ahead
03-21 13:06:24.015 11201 11264 I jxcore-log: 
,03-21 13:06:24.180 11201 11264 I jxcore-log: # teardown
03-21 13:06:24.180 11201 11264 I jxcore-log: 
,03-21 13:06:24.605 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:24.605 11201 11264 I jxcore-log: 
,03-21 13:06:24.610 11201 11264 I jxcore-log: ok 374 verify failed
03-21 13:06:24.610 11201 11264 I jxcore-log: 
03-21 13:06:24.610 11201 11264 I jxcore-log: ok 375 constructor called once
03-21 13:06:24.610 11201 11264 I jxcore-log: 
,03-21 13:06:24.610 11201 11264 I jxcore-log: ok 376 constructor called with right args
03-21 13:06:24.610 11201 11264 I jxcore-log: 
03-21 13:06:24.610 11201 11264 I jxcore-log: ok 377 match start arg
03-21 13:06:24.610 11201 11264 I jxcore-log: 
03-21 13:06:24.610 11201 11264 I jxcore-log: ok 378 start called once
03-21 13:06:24.610 11201 11264 I jxcore-log: 
03-21 13:06:24.610 11201 11264 I jxcore-log: ok 379 stop called once
03-21 13:06:24.610 11201 11264 I jxcore-log: 
03-21 13:06:24.610 11201 11264 I jxcore-log: ok 380 stop after start
03-21 13:06:24.610 11201 11264 I jxcore-log: 
,03-21 13:06:24.615 11201 11264 I jxcore-log: # setup
03-21 13:06:24.615 11201 11264 I jxcore-log: 
,03-21 13:06:24.990 11201 11264 I jxcore-log: # 115. More than maximum peers, make sure we only send maximum allowed
03-21 13:06:24.990 11201 11264 I jxcore-log: 
,03-21 13:06:25.080 11201 11264 I jxcore-log: # teardown
03-21 13:06:25.080 11201 11264 I jxcore-log: 
,03-21 13:06:25.665  3369  3866 E Watchdog: !@Sync 10 [03-21 13:06:25.668]
,03-21 13:06:25.875 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:25.875 11201 11264 I jxcore-log: 
,03-21 13:06:25.880 11201 11264 I jxcore-log: ok 381 verify failed
03-21 13:06:25.880 11201 11264 I jxcore-log: 
03-21 13:06:25.880 11201 11264 I jxcore-log: ok 382 constructor called once
03-21 13:06:25.880 11201 11264 I jxcore-log: 
03-21 13:06:25.880 11201 11264 I jxcore-log: ok 383 constructor called with right args
03-21 13:06:25.880 11201 11264 I jxcore-log: 
03-21 13:06:25.880 11201 11264 I jxcore-log: ok 384 match start arg
03-21 13:06:25.880 11201 11264 I jxcore-log: 
03-21 13:06:25.880 11201 11264 I jxcore-log: ok 385 start called once
03-21 13:06:25.880 11201 11264 I jxcore-log: 
03-21 13:06:25.880 11201 11264 I jxcore-log: ok 386 stop called once
03-21 13:06:25.880 11201 11264 I jxcore-log: 
03-21 13:06:25.880 11201 11264 I jxcore-log: ok 387 stop after start
03-21 13:06:25.880 11201 11264 I jxcore-log: 
,03-21 13:06:25.890 11201 11264 I jxcore-log: # setup
03-21 13:06:25.890 11201 11264 I jxcore-log: 
,03-21 13:06:25.990 11201 11264 I jxcore-log: # 116. two peers with empty DB, update the doc
03-21 13:06:25.990 11201 11264 I jxcore-log: 
,03-21 13:06:26.100 11201 11264 I jxcore-log: # teardown
03-21 13:06:26.100 11201 11264 I jxcore-log: 
,03-21 13:06:26.465 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:26.465 11201 11264 I jxcore-log: 
,03-21 13:06:26.505 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:26.505 11201 11264 I jxcore-log: 
,03-21 13:06:26.505 11201 11264 I jxcore-log: ok 388 verify failed
03-21 13:06:26.505 11201 11264 I jxcore-log: 
03-21 13:06:26.505 11201 11264 I jxcore-log: ok 389 constructor called once
03-21 13:06:26.505 11201 11264 I jxcore-log: 
03-21 13:06:26.505 11201 11264 I jxcore-log: ok 390 constructor called with right args
03-21 13:06:26.505 11201 11264 I jxcore-log: 
,03-21 13:06:26.505 11201 11264 I jxcore-log: ok 391 last start before stop
03-21 13:06:26.505 11201 11264 I jxcore-log: 
03-21 13:06:26.505 11201 11264 I jxcore-log: ok 392 empty first start
03-21 13:06:26.505 11201 11264 I jxcore-log: 
03-21 13:06:26.505 11201 11264 I jxcore-log: ok 393 full second start
03-21 13:06:26.505 11201 11264 I jxcore-log: 
03-21 13:06:26.505 11201 11264 I jxcore-log: ok 394 only 2 timers
03-21 13:06:26.505 11201 11264 I jxcore-log: 
,03-21 13:06:26.510 11201 11264 I jxcore-log: # setup
03-21 13:06:26.510 11201 11264 I jxcore-log: 
,03-21 13:06:26.600 11201 11264 I jxcore-log: # 117. add doc and make sure tokens refresh when they expire
03-21 13:06:26.600 11201 11264 I jxcore-log: 
,03-21 13:06:27.470 11201 11264 I jxcore-log: # teardown
03-21 13:06:27.470 11201 11264 I jxcore-log: 
,03-21 13:06:27.930 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:27.930 11201 11264 I jxcore-log: 
,03-21 13:06:28.070 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:28.070 11201 11264 I jxcore-log: 
,03-21 13:06:28.075  3369  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
03-21 13:06:28.075  3369  3609 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-21 13:06:28.090  3369  3609 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 13:06:28.095  3369  3609 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-21 13:06:28.140 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:28.140 11201 11264 I jxcore-log: 
,03-21 13:06:28.145 11201 11264 I jxcore-log: ok 395 verify failed
03-21 13:06:28.145 11201 11264 I jxcore-log: 
,03-21 13:06:28.150 11201 11264 I jxcore-log: ok 396 constructor called once
03-21 13:06:28.150 11201 11264 I jxcore-log: 
,03-21 13:06:28.155 11201 11264 I jxcore-log: ok 397 constructor called with right args
03-21 13:06:28.155 11201 11264 I jxcore-log: 
,03-21 13:06:28.155 11201 11264 I jxcore-log: ok 398 start before stop
03-21 13:06:28.155 11201 11264 I jxcore-log: 
,03-21 13:06:28.155 11201 11264 I jxcore-log: ok 399 We got at least 3 calls to start
03-21 13:06:28.155 11201 11264 I jxcore-log: 
,03-21 13:06:28.160 11201 11264 I jxcore-log: ok 400 at least 3
03-21 13:06:28.160 11201 11264 I jxcore-log: 
,03-21 13:06:28.160 11201 11264 I jxcore-log: ok 401 default 1
03-21 13:06:28.160 11201 11264 I jxcore-log: 
,03-21 13:06:28.160 11201 11264 I jxcore-log: ok 402 1 run
03-21 13:06:28.160 11201 11264 I jxcore-log: 
,03-21 13:06:28.165 11201 11264 I jxcore-log: ok 403 default 2
03-21 13:06:28.165 11201 11264 I jxcore-log: 
,03-21 13:06:28.165 11201 11264 I jxcore-log: ok 404 2 run
03-21 13:06:28.165 11201 11264 I jxcore-log: 
,03-21 13:06:28.165 11201 11264 I jxcore-log: ok 405 default 3
03-21 13:06:28.165 11201 11264 I jxcore-log: 
,03-21 13:06:28.180 11201 11264 I jxcore-log: # setup
03-21 13:06:28.180 11201 11264 I jxcore-log: 
,03-21 13:06:28.250 11201 11264 I jxcore-log: # 118. start and stop and start and stop
03-21 13:06:28.250 11201 11264 I jxcore-log: 
,03-21 13:06:28.365  3369  3554 W ProcessCpuTracker: Skipping unknown process pid 12704
,03-21 13:06:28.380 11201 11264 I jxcore-log: # teardown
03-21 13:06:28.380 11201 11264 I jxcore-log: 
,03-21 13:06:28.690 11201 11264 I jxcore-log: ok 406 start out null
03-21 13:06:28.690 11201 11264 I jxcore-log: 
,03-21 13:06:28.720 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:28.720 11201 11264 I jxcore-log: 
,03-21 13:06:28.720 11201 11264 I jxcore-log: ok 407 back to null
03-21 13:06:28.720 11201 11264 I jxcore-log: 
,03-21 13:06:28.770 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:28.770 11201 11264 I jxcore-log: 
,03-21 13:06:28.770 11201 11264 I jxcore-log: ok 408 still null
03-21 13:06:28.770 11201 11264 I jxcore-log: 
,03-21 13:06:28.770 11201 11264 I jxcore-log: ok 409 verify failed
03-21 13:06:28.770 11201 11264 I jxcore-log: 
03-21 13:06:28.770 11201 11264 I jxcore-log: ok 410 constructor called once
03-21 13:06:28.770 11201 11264 I jxcore-log: 
,03-21 13:06:28.770 11201 11264 I jxcore-log: ok 411 constructor called with right args
03-21 13:06:28.770 11201 11264 I jxcore-log: 
03-21 13:06:28.770 11201 11264 I jxcore-log: ok 412 first start before first stop
03-21 13:06:28.770 11201 11264 I jxcore-log: 
03-21 13:06:28.770 11201 11264 I jxcore-log: ok 413 first stop before second start
03-21 13:06:28.770 11201 11264 I jxcore-log: 
,03-21 13:06:28.770 11201 11264 I jxcore-log: ok 414 second start before second stop
03-21 13:06:28.770 11201 11264 I jxcore-log: 
,03-21 13:06:28.780 11201 11264 I jxcore-log: # setup
03-21 13:06:28.780 11201 11264 I jxcore-log: 
,03-21 13:06:28.875  2894  4757 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 13:06:28.880 11201 11264 I jxcore-log: # 119. two identical starts in a row
03-21 13:06:28.880 11201 11264 I jxcore-log: 
,03-21 13:06:29.020 11201 11264 I jxcore-log: # teardown
03-21 13:06:29.020 11201 11264 I jxcore-log: 
,03-21 13:06:29.365 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:29.365 11201 11264 I jxcore-log: 
,03-21 13:06:29.365 11201 11264 I jxcore-log: ok 415 verify failed
03-21 13:06:29.365 11201 11264 I jxcore-log: 
,03-21 13:06:29.365 11201 11264 I jxcore-log: ok 416 constructor called once
03-21 13:06:29.365 11201 11264 I jxcore-log: 
03-21 13:06:29.365 11201 11264 I jxcore-log: ok 417 constructor called with right args
03-21 13:06:29.365 11201 11264 I jxcore-log: 
03-21 13:06:29.370 11201 11264 I jxcore-log: ok 418 (unnamed assert)
03-21 13:06:29.370 11201 11264 I jxcore-log: 
,03-21 13:06:29.370 11201 11264 I jxcore-log: # setup
03-21 13:06:29.370 11201 11264 I jxcore-log: 
,03-21 13:06:29.440 11201 11264 I jxcore-log: # 120. two different starts in a row
03-21 13:06:29.440 11201 11264 I jxcore-log: 
,03-21 13:06:29.455  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 48, LCD = 0
,03-21 13:06:29.555 11201 11264 I jxcore-log: # teardown
03-21 13:06:29.555 11201 11264 I jxcore-log: 
,03-21 13:06:29.705  3369  3721 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:06:29.705  3369  3721 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:06:29.705  3369  3721 D BatteryService: online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
03-21 13:06:29.705  3369  3721 D BatteryService: stay LED for fully charged
03-21 13:06:29.705  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:06:29.710  3369  3369 I MotionRecognitionService: Plugged
03-21 13:06:29.710  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:06:29.710  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:06:29.710  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
03-21 13:06:29.710  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:06:29.710  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:06:29.710  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:06:29.720  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 13:06:29.720  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:06:29.735  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:06:29.735  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:29.735  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:29.735  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:06:29.815 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:29.815 11201 11264 I jxcore-log: 
,03-21 13:06:29.820 11201 11264 I jxcore-log: ok 419 verify failed
03-21 13:06:29.820 11201 11264 I jxcore-log: 
,03-21 13:06:29.820 11201 11264 I jxcore-log: ok 420 constructor called once
03-21 13:06:29.820 11201 11264 I jxcore-log: 
03-21 13:06:29.820 11201 11264 I jxcore-log: ok 421 constructor called with right args
03-21 13:06:29.820 11201 11264 I jxcore-log: 
03-21 13:06:29.820 11201 11264 I jxcore-log: ok 422 (unnamed assert)
03-21 13:06:29.820 11201 11264 I jxcore-log: 
,03-21 13:06:29.820 11201 11264 I jxcore-log: ok 423 (unnamed assert)
03-21 13:06:29.820 11201 11264 I jxcore-log: 
,03-21 13:06:29.825 11201 11264 I jxcore-log: # setup
03-21 13:06:29.825 11201 11264 I jxcore-log: 
,03-21 13:06:29.900 11201 11264 I jxcore-log: # 121. two stops and a start and two stops
03-21 13:06:29.900 11201 11264 I jxcore-log: 
,03-21 13:06:30.045 11201 11264 I jxcore-log: # teardown
03-21 13:06:30.045 11201 11264 I jxcore-log: 
,03-21 13:06:30.325 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:30.325 11201 11264 I jxcore-log: 
,03-21 13:06:30.330 11201 11264 I jxcore-log: ok 424 verify failed
03-21 13:06:30.330 11201 11264 I jxcore-log: 
,03-21 13:06:30.330 11201 11264 I jxcore-log: ok 425 constructor called once
03-21 13:06:30.330 11201 11264 I jxcore-log: 
,03-21 13:06:30.330 11201 11264 I jxcore-log: ok 426 constructor called with right args
03-21 13:06:30.330 11201 11264 I jxcore-log: 
,03-21 13:06:30.330 11201 11264 I jxcore-log: ok 427 start before stop
03-21 13:06:30.330 11201 11264 I jxcore-log: 
,03-21 13:06:30.345 11201 11264 I jxcore-log: # setup
03-21 13:06:30.345 11201 11264 I jxcore-log: 
,03-21 13:06:30.395 11201 11264 I jxcore-log: # 122. we properly enqueue requests so no then needed
03-21 13:06:30.395 11201 11264 I jxcore-log: 
,03-21 13:06:30.535 11201 11264 I jxcore-log: # teardown
03-21 13:06:30.535 11201 11264 I jxcore-log: 
,03-21 13:06:30.795 11201 11264 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-21 13:06:30.795 11201 11264 I jxcore-log: 
,03-21 13:06:30.800 11201 11264 I jxcore-log: ok 428 verify failed
03-21 13:06:30.800 11201 11264 I jxcore-log: 
,03-21 13:06:30.800 11201 11264 I jxcore-log: ok 429 constructor called once
03-21 13:06:30.800 11201 11264 I jxcore-log: 
03-21 13:06:30.800 11201 11264 I jxcore-log: ok 430 constructor called with right args
03-21 13:06:30.800 11201 11264 I jxcore-log: 
,03-21 13:06:30.800 11201 11264 I jxcore-log: ok 431 start before stop
03-21 13:06:30.800 11201 11264 I jxcore-log: 
,03-21 13:06:30.810 11201 11264 I jxcore-log: # setup
03-21 13:06:30.810 11201 11264 I jxcore-log: 
,03-21 13:06:30.915 11201 11264 I jxcore-log: # 123. test calculateSeqPointKeyId
03-21 13:06:30.915 11201 11264 I jxcore-log: 
,03-21 13:06:31.150 11201 11264 I jxcore-log: # teardown
03-21 13:06:31.150 11201 11264 I jxcore-log: 
,03-21 13:06:31.275  6112 11975 I System.out: pool-3-thread-1 calls detatch()
,03-21 13:06:31.425 11201 11264 I jxcore-log: ok 432 should be equal
03-21 13:06:31.425 11201 11264 I jxcore-log: 
,03-21 13:06:31.430 11201 11264 I jxcore-log: ok 433 should be equal
03-21 13:06:31.430 11201 11264 I jxcore-log: 
,03-21 13:06:31.435 11201 11264 I jxcore-log: # setup
03-21 13:06:31.435 11201 11264 I jxcore-log: 
,03-21 13:06:31.645 11201 11264 I jxcore-log: # 124. can create servers manager
03-21 13:06:31.645 11201 11264 I jxcore-log: 
,03-21 13:06:31.760 11201 11264 I jxcore-log: # teardown
03-21 13:06:31.760 11201 11264 I jxcore-log: 
,03-21 13:06:31.835 11201 11264 I jxcore-log: ok 434 serversManager must not be null
03-21 13:06:31.835 11201 11264 I jxcore-log: 
,03-21 13:06:31.835 11201 11264 I jxcore-log: ok 435 serversManager must be an object
03-21 13:06:31.835 11201 11264 I jxcore-log: 
,03-21 13:06:31.840 11201 11264 I jxcore-log: # setup
03-21 13:06:31.840 11201 11264 I jxcore-log: 
,03-21 13:06:31.935 11201 11264 I jxcore-log: # 125. calling stop without start causes error
03-21 13:06:31.935 11201 11264 I jxcore-log: 
,03-21 13:06:32.055 11201 11264 I jxcore-log: # teardown
03-21 13:06:32.055 11201 11264 I jxcore-log: 
,03-21 13:06:32.155 11201 11264 I jxcore-log: ok 436 We need to call start first
03-21 13:06:32.155 11201 11264 I jxcore-log: 
,03-21 13:06:32.160 11201 11264 I jxcore-log: # setup
03-21 13:06:32.160 11201 11264 I jxcore-log: 
,03-21 13:06:32.235 11201 11264 I jxcore-log: # 126. can start/stop servers manager
03-21 13:06:32.235 11201 11264 I jxcore-log: 
,03-21 13:06:32.330 11201 11264 I jxcore-log: # teardown
03-21 13:06:32.330 11201 11264 I jxcore-log: 
,03-21 13:06:32.405 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server,
03-21 13:06:32.405 11201 11264 I jxcore-log: 
,03-21 13:06:32.415 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 51604
03-21 13:06:32.415 11201 11264 I jxcore-log: 
,03-21 13:06:32.420 11201 11264 I jxcore-log: ok 437 port must be in range
03-21 13:06:32.420 11201 11264 I jxcore-log: 
,03-21 13:06:32.425 11201 11264 I jxcore-log: # setup
03-21 13:06:32.425 11201 11264 I jxcore-log: 
,03-21 13:06:32.530 11201 11264 I jxcore-log: # 127. starting twice resolves with listening port
03-21 13:06:32.530 11201 11264 I jxcore-log: 
,03-21 13:06:32.655 11201 11264 I jxcore-log: # teardown
03-21 13:06:32.655 11201 11264 I jxcore-log: 
,03-21 13:06:32.755 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:06:32.755 11201 11264 I jxcore-log: 
,03-21 13:06:32.760 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 36243
03-21 13:06:32.760 11201 11264 I jxcore-log: 
,03-21 13:06:32.765 11201 11264 I jxcore-log: ok 438 second start should return same port
03-21 13:06:32.765 11201 11264 I jxcore-log: 
,03-21 13:06:32.770 11201 11264 I jxcore-log: # setup
03-21 13:06:32.770 11201 11264 I jxcore-log: 
,03-21 13:06:32.860 11201 11264 I jxcore-log: # 128. terminateIncomingConnection will terminate a connection
03-21 13:06:32.860 11201 11264 I jxcore-log: 
,03-21 13:06:32.945 11201 11264 I jxcore-log: # teardown
03-21 13:06:32.945 11201 11264 I jxcore-log: 
,03-21 13:06:33.090 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:06:33.090 11201 11264 I jxcore-log: 
,03-21 13:06:33.095 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 36301
03-21 13:06:33.095 11201 11264 I jxcore-log: 
,03-21 13:06:33.105 11201 11264 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 13:06:33.105 11201 11264 I jxcore-log: 
,03-21 13:06:33.110 11201 11264 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 13:06:33.110 11201 11264 I jxcore-log: 
,03-21 13:06:33.110 11201 11264 I jxcore-log: DEBUG createNativeListener: new mux
03-21 13:06:33.110 11201 11264 I jxcore-log: 
,03-21 13:06:33.115 11201 11264 I jxcore-log: ok 439 we should be connected
03-21 13:06:33.115 11201 11264 I jxcore-log: 
,03-21 13:06:33.120 11201 11264 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 13:06:33.120 11201 11264 I jxcore-log: 
,03-21 13:06:33.125 11201 11264 I jxcore-log: ok 440 now we are disconnected
03-21 13:06:33.125 11201 11264 I jxcore-log: 
,03-21 13:06:33.140 11201 11264 I jxcore-log: # setup
03-21 13:06:33.140 11201 11264 I jxcore-log: 
,03-21 13:06:33.290 11201 11264 I jxcore-log: # 129. terminate an Outgoing connection will terminate the server
03-21 13:06:33.290 11201 11264 I jxcore-log: 
,03-21 13:06:33.425 11201 11264 I jxcore-log: # teardown
03-21 13:06:33.425 11201 11264 I jxcore-log: 
,03-21 13:06:33.545 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:06:33.545 11201 11264 I jxcore-log: 
,03-21 13:06:33.555 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 47400
03-21 13:06:33.555 11201 11264 I jxcore-log: 
,03-21 13:06:33.560 11201 11264 I jxcore-log: # setup
03-21 13:06:33.560 11201 11264 I jxcore-log: 
,03-21 13:06:33.625 11201 11264 I jxcore-log: # 130. terminate an Outgoing connection with wrong arguments is not harmful
03-21 13:06:33.625 11201 11264 I jxcore-log: 
,03-21 13:06:33.765 11201 11264 I jxcore-log: # teardown
03-21 13:06:33.765 11201 11264 I jxcore-log: 
,03-21 13:06:33.875 11201 11264 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 13:06:33.875 11201 11264 I jxcore-log: 
,03-21 13:06:33.885 11201 11264 I jxcore-log: DEBUG createNativeListener: listening 39423
03-21 13:06:33.885 11201 11264 I jxcore-log: 
,03-21 13:06:33.890 11201 11264 I jxcore-log: # setup
03-21 13:06:33.890 11201 11264 I jxcore-log: 
,03-21 13:06:33.965 11201 11264 I jxcore-log: # 131. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
03-21 13:06:33.965 11201 11264 I jxcore-log: 
,03-21 13:06:34.070 11201 11264 I jxcore-log: ok 441 should be in started state
03-21 13:06:34.070 11201 11264 I jxcore-log: 
,03-21 13:06:34.075 11201 11264 I jxcore-log: # teardown
03-21 13:06:34.075 11201 11264 I jxcore-log: 
,03-21 13:06:34.205 11201 11264 I jxcore-log: ok 442 peer identifier should match
03-21 13:06:34.205 11201 11264 I jxcore-log: 
,03-21 13:06:34.205 11201 11264 I jxcore-log: ok 443 host address should match
03-21 13:06:34.205 11201 11264 I jxcore-log: 
,03-21 13:06:34.210 11201 11264 I jxcore-log: ok 444 port should match
03-21 13:06:34.210 11201 11264 I jxcore-log: 
,03-21 13:06:34.220 11201 11264 I jxcore-log: ok 445 host address should be null
03-21 13:06:34.220 11201 11264 I jxcore-log: 
,03-21 13:06:34.220 11201 11264 I jxcore-log: ok 446 port should should be null
03-21 13:06:34.220 11201 11264 I jxcore-log: 
,03-21 13:06:34.225 11201 11264 I jxcore-log: # setup
03-21 13:06:34.225 11201 11264 I jxcore-log: 
,03-21 13:06:34.335 11201 11264 I jxcore-log: ok 447 should not be in started state
03-21 13:06:34.335 11201 11264 I jxcore-log: 
,03-21 13:06:34.340 11201 11264 I jxcore-log: # 132. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-21 13:06:34.340 11201 11264 I jxcore-log: 
,03-21 13:06:34.460 11201 11264 I jxcore-log: ok 448 should be in started state
03-21 13:06:34.460 11201 11264 I jxcore-log: 
,03-21 13:06:34.470 11201 11264 I jxcore-log: # teardown
03-21 13:06:34.470 11201 11264 I jxcore-log: 
,03-21 13:06:34.610 11201 11264 I jxcore-log: ok 449 USN should have changed from the first one
03-21 13:06:34.610 11201 11264 I jxcore-log: 
,03-21 13:06:34.625 11201 11264 I jxcore-log: ok 450 when receiving the second byebye, the first USN should be already set
03-21 13:06:34.625 11201 11264 I jxcore-log: 
,03-21 13:06:34.635 11201 11264 I jxcore-log: # setup
03-21 13:06:34.635 11201 11264 I jxcore-log: 
,03-21 13:06:34.740 11201 11264 I jxcore-log: ok 451 should not be in started state
03-21 13:06:34.740 11201 11264 I jxcore-log: 
,03-21 13:06:34.740 11201 11264 I jxcore-log: # 133. messages with invalid location or USN should be ignored
03-21 13:06:34.740 11201 11264 I jxcore-log: 
,03-21 13:06:34.855 11201 11264 I jxcore-log: ok 452 should be in started state
03-21 13:06:34.855 11201 11264 I jxcore-log: 
,03-21 13:06:34.860 11201 11264 I jxcore-log: # teardown
03-21 13:06:34.860 11201 11264 I jxcore-log: 
,03-21 13:06:34.970 11201 11264 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
03-21 13:06:34.970 11201 11264 I jxcore-log: 
,03-21 13:06:34.970 11201 11264 I jxcore-log: ok 453 should not have emitted with invalid port
03-21 13:06:34.970 11201 11264 I jxcore-log: 
,03-21 13:06:34.975 11201 11264 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
03-21 13:06:34.975 11201 11264 I jxcore-log: 
,03-21 13:06:34.975 11201 11264 I jxcore-log: ok 454 should not have emitted with invalid USN
03-21 13:06:34.975 11201 11264 I jxcore-log: 
,03-21 13:06:34.980 11201 11264 I jxcore-log: # setup
03-21 13:06:34.980 11201 11264 I jxcore-log: 
,03-21 13:06:35.095 11201 11264 I jxcore-log: ok 455 should not be in started state
03-21 13:06:35.095 11201 11264 I jxcore-log: 
,03-21 13:06:35.100 11201 11264 I jxcore-log: # 134. verify that Thali-specific messages are filtered correctly
03-21 13:06:35.100 11201 11264 I jxcore-log: 
,03-21 13:06:35.200 11201 11264 I jxcore-log: ok 456 should be in started state
03-21 13:06:35.200 11201 11264 I jxcore-log: 
,03-21 13:06:35.205 11201 11264 I jxcore-log: # teardown
03-21 13:06:35.205 11201 11264 I jxcore-log: 
,03-21 13:06:35.255 11201 11264 I jxcore-log: ok 457 irrelevant messages should be ignored
03-21 13:06:35.255 11201 11264 I jxcore-log: 
,03-21 13:06:35.260 11201 11264 I jxcore-log: ok 458 relevant messages should not be ignored
03-21 13:06:35.260 11201 11264 I jxcore-log: 
,03-21 13:06:35.260 11201 11264 I jxcore-log: ok 459 messages from this device should be ignored
03-21 13:06:35.260 11201 11264 I jxcore-log: 
,03-21 13:06:35.270 11201 11264 I jxcore-log: # setup
03-21 13:06:35.270 11201 11264 I jxcore-log: 
,03-21 13:06:35.355 11201 11264 I jxcore-log: ok 460 should not be in started state
03-21 13:06:35.355 11201 11264 I jxcore-log: 
,03-21 13:06:35.360 11201 11264 I jxcore-log: # 135. #startListeningForAdvertisements should fail if start not called
03-21 13:06:35.360 11201 11264 I jxcore-log: 
,03-21 13:06:35.450 11201 11264 I jxcore-log: ok 461 should be in started state
03-21 13:06:35.450 11201 11264 I jxcore-log: 
,03-21 13:06:35.450 11201 11264 I jxcore-log: # teardown
03-21 13:06:35.450 11201 11264 I jxcore-log: 
,03-21 13:06:35.565 11201 11264 I jxcore-log: ok 462 specific error should be returned
03-21 13:06:35.565 11201 11264 I jxcore-log: 
,03-21 13:06:35.565 11201 11264 I jxcore-log: # setup
03-21 13:06:35.565 11201 11264 I jxcore-log: 
,03-21 13:06:35.655 11201 11264 I jxcore-log: ok 463 should not be in started state
03-21 13:06:35.655 11201 11264 I jxcore-log: 
,03-21 13:06:35.660 11201 11264 I jxcore-log: # 136. #startUpdateAdvertisingAndListening should fail if start not called
03-21 13:06:35.660 11201 11264 I jxcore-log: 
,03-21 13:06:35.785 11201 11264 I jxcore-log: ok 464 should be in started state
03-21 13:06:35.785 11201 11264 I jxcore-log: 
,03-21 13:06:35.795 11201 11264 I jxcore-log: # teardown
03-21 13:06:35.795 11201 11264 I jxcore-log: 
,03-21 13:06:35.965 11201 11264 I jxcore-log: ok 465 specific error should be returned
03-21 13:06:35.965 11201 11264 I jxcore-log: 
,03-21 13:06:35.970 11201 11264 I jxcore-log: # setup
03-21 13:06:35.970 11201 11264 I jxcore-log: 
,03-21 13:06:36.200 11201 11264 I jxcore-log: ok 466 should not be in started state
03-21 13:06:36.200 11201 11264 I jxcore-log: 
,03-21 13:06:36.205 11201 11264 I jxcore-log: # 137. #start should fail if called twice in a row
03-21 13:06:36.205 11201 11264 I jxcore-log: 
,03-21 13:06:36.300 11201 11264 I jxcore-log: ok 467 should be in started state
03-21 13:06:36.300 11201 11264 I jxcore-log: 
,03-21 13:06:36.300 11201 11264 I jxcore-log: # teardown
03-21 13:06:36.300 11201 11264 I jxcore-log: 
,03-21 13:06:36.365 11201 11264 I jxcore-log: ok 468 specific error should be received
03-21 13:06:36.365 11201 11264 I jxcore-log: 
,03-21 13:06:36.365 11201 11264 I jxcore-log: # setup
03-21 13:06:36.365 11201 11264 I jxcore-log: 
,03-21 13:06:36.505 11201 11264 I jxcore-log: ok 469 should not be in started state
03-21 13:06:36.505 11201 11264 I jxcore-log: 
,03-21 13:06:36.510 11201 11264 I jxcore-log: # 138. should not be started after stop is called
03-21 13:06:36.510 11201 11264 I jxcore-log: 
,03-21 13:06:36.620 11201 11264 I jxcore-log: ok 470 should be in started state
03-21 13:06:36.620 11201 11264 I jxcore-log: 
,03-21 13:06:36.630 11201 11264 I jxcore-log: # teardown
03-21 13:06:36.630 11201 11264 I jxcore-log: 
,03-21 13:06:36.735 11201 11264 I jxcore-log: ok 471 should not be started
03-21 13:06:36.735 11201 11264 I jxcore-log: 
,03-21 13:06:36.740 11201 11264 I jxcore-log: ok 472 should not be listening
03-21 13:06:36.740 11201 11264 I jxcore-log: 
,03-21 13:06:36.740 11201 11264 I jxcore-log: ok 473 should not target listening
03-21 13:06:36.740 11201 11264 I jxcore-log: 
,03-21 13:06:36.745 11201 11264 I jxcore-log: ok 474 should not be advertising
03-21 13:06:36.745 11201 11264 I jxcore-log: 
,03-21 13:06:36.745 11201 11264 I jxcore-log: ok 475 should not target advertising
03-21 13:06:36.745 11201 11264 I jxcore-log: 
,03-21 13:06:36.750 11201 11264 I jxcore-log: # setup
03-21 13:06:36.750 11201 11264 I jxcore-log: 
,03-21 13:06:36.820 11201 11264 I jxcore-log: ok 476 should not be in started state
03-21 13:06:36.820 11201 11264 I jxcore-log: 
,03-21 13:06:36.820 11201 11264 I jxcore-log: # 139. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-21 13:06:36.820 11201 11264 I jxcore-log: 
,03-21 13:06:36.935 11201 11264 I jxcore-log: ok 477 should be in started state
03-21 13:06:36.935 11201 11264 I jxcore-log: 
,03-21 13:06:36.940 11201 11264 I jxcore-log: # teardown
03-21 13:06:36.940 11201 11264 I jxcore-log: 
,03-21 13:06:37.015 11201 11264 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-21 13:06:37.015 11201 11264 I jxcore-log: 
,03-21 13:06:37.020 11201 11264 I jxcore-log: ok 478 specific error should be received
03-21 13:06:37.020 11201 11264 I jxcore-log: 
,03-21 13:06:37.025 11201 11264 I jxcore-log: # setup
03-21 13:06:37.025 11201 11264 I jxcore-log: 
,03-21 13:06:37.090 11201 11264 I jxcore-log: ok 479 should not be in started state
03-21 13:06:37.090 11201 11264 I jxcore-log: 
,03-21 13:06:37.095 11201 11264 I jxcore-log: # 140. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-21 13:06:37.095 11201 11264 I jxcore-log: 
,03-21 13:06:37.270 11201 11264 I jxcore-log: ok 480 should be in started state
03-21 13:06:37.270 11201 11264 I jxcore-log: 
,03-21 13:06:37.275 11201 11264 I jxcore-log: # teardown
03-21 13:06:37.275 11201 11264 I jxcore-log: 
,03-21 13:06:37.350 11201 11264 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-21 13:06:37.350 11201 11264 I jxcore-log: 
,03-21 13:06:37.355 11201 11264 I jxcore-log: ok 481 specific error expected
03-21 13:06:37.355 11201 11264 I jxcore-log: 
,03-21 13:06:37.355 11201 11264 I jxcore-log: # setup
03-21 13:06:37.355 11201 11264 I jxcore-log: 
,03-21 13:06:37.495 11201 11264 I jxcore-log: ok 482 should not be in started state
03-21 13:06:37.495 11201 11264 I jxcore-log: 
,03-21 13:06:37.500 11201 11264 I jxcore-log: # 141. #startUpdateAdvertisingAndListening should start hosting given router object
03-21 13:06:37.500 11201 11264 I jxcore-log: 
,03-21 13:06:37.595 11201 11264 I jxcore-log: ok 483 should be in started state
03-21 13:06:37.595 11201 11264 I jxcore-log: 
,03-21 13:06:37.600 11201 11264 I jxcore-log: # teardown
03-21 13:06:37.600 11201 11264 I jxcore-log: 
,03-21 13:06:37.740  2873  3396 D EnterpriseController: netId is 0
03-21 13:06:37.740  2873  3396 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 13:06:37.765 11201 11264 I jxcore-log: ok 484 server should respond with code 200
03-21 13:06:37.765 11201 11264 I jxcore-log: 
,03-21 13:06:37.775 11201 11264 I jxcore-log: # setup
03-21 13:06:37.775 11201 11264 I jxcore-log: 
,03-21 13:06:37.915 11201 11264 I jxcore-log: ok 485 should not be in started state
03-21 13:06:37.915 11201 11264 I jxcore-log: 
,03-21 13:06:37.920 11201 11264 I jxcore-log: # 142. #stop can be called multiple times in a row
03-21 13:06:37.920 11201 11264 I jxcore-log: 
,03-21 13:06:38.455 11201 11264 I jxcore-log: ok 486 should be in started state
03-21 13:06:38.455 11201 11264 I jxcore-log: 
,03-21 13:06:38.460 11201 11264 I jxcore-log: # teardown
03-21 13:06:38.460 11201 11264 I jxcore-log: 
,03-21 13:06:39.045 11201 11264 I jxcore-log: ok 487 should be in stopped state
03-21 13:06:39.045 11201 11264 I jxcore-log: 
,03-21 13:06:39.050 11201 11264 I jxcore-log: ok 488 should still be in stopped state
03-21 13:06:39.050 11201 11264 I jxcore-log: 
,03-21 13:06:39.055 11201 11264 I jxcore-log: # setup
03-21 13:06:39.055 11201 11264 I jxcore-log: 
,03-21 13:06:39.150 11201 11264 I jxcore-log: ok 489 should not be in started state
03-21 13:06:39.150 11201 11264 I jxcore-log: 
,03-21 13:06:39.155 11201 11264 I jxcore-log: # 143. #startListeningForAdvertisements can be called multiple times in a row
03-21 13:06:39.155 11201 11264 I jxcore-log: 
,03-21 13:06:39.465 11201 11264 I jxcore-log: ok 490 should be in started state
03-21 13:06:39.465 11201 11264 I jxcore-log: 
,03-21 13:06:39.480  3369  6063 D SSRM:n  : SIOP:: AP = 280, PST = 280 (W:16), CUR = 54, LCD = 0
,03-21 13:06:39.480 11201 11264 I jxcore-log: # teardown
03-21 13:06:39.480 11201 11264 I jxcore-log: 
,03-21 13:06:39.635 11201 11264 I jxcore-log: ok 491 should be in listening state
03-21 13:06:39.635 11201 11264 I jxcore-log: 
,03-21 13:06:39.635 11201 11264 I jxcore-log: ok 492 should still be in listening state
03-21 13:06:39.635 11201 11264 I jxcore-log: 
,03-21 13:06:39.645 11201 11264 I jxcore-log: # setup
03-21 13:06:39.645 11201 11264 I jxcore-log: 
,03-21 13:06:39.785 11201 11264 I jxcore-log: ok 493 should not be in started state
03-21 13:06:39.785 11201 11264 I jxcore-log: 
,03-21 13:06:39.795 11201 11264 I jxcore-log: # 144. #stopListeningForAdvertisements can be called multiple times in a row
03-21 13:06:39.795 11201 11264 I jxcore-log: 
,03-21 13:06:39.835  3369  3387 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 13:06:39.835  3369  3387 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 13:06:39.835  3369  3387 D BatteryService: online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
03-21 13:06:39.835  3369  3387 D BatteryService: stay LED for fully charged
03-21 13:06:39.835  3369  3369 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 13:06:39.840  3369  3369 I MotionRecognitionService: Plugged
03-21 13:06:39.840  3369  3369 D MotionRecognitionService:   cableConnection= 1
03-21 13:06:39.840  3369  3369 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 13:06:39.840  3369  3369 D MotionRecognitionService: skip setTransmitPower. 
,03-21 13:06:39.840  3728  3728 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:06:39.840  3728  3728 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 13:06:39.845  3728  3728 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 13:06:39.850  5877  5877 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 13:06:39.850  5877  5974 D HeadsetStateMachine: Disconnected process message: 10
,03-21 13:06:39.865  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 13:06:39.865  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:39.865  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 13:06:39.865  3728  3728 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 13:06:39.965 11201 11264 I jxcore-log: ok 494 should be in started state
03-21 13:06:39.965 11201 11264 I jxcore-log: 
,03-21 13:06:39.975 11201 11264 I jxcore-log: # teardown
03-21 13:06:39.975 11201 11264 I jxcore-log: 
,03-21 13:06:40.115 11201 11264 I jxcore-log: ok 495 should not be in listening state
03-21 13:06:40.115 11201 11264 I jxcore-log: 
,03-21 13:06:40.115 11201 11264 I jxcore-log: ok 496 should still not be in listening state
03-21 13:06:40.115 11201 11264 I jxcore-log: 
,03-21 13:06:40.120 11201 11264 I jxcore-log: # setup
03-21 13:06:40.120 11201 11264 I jxcore-log: 
,03-21 13:06:40.305 11201 11264 I jxcore-log: ok 497 should not be in started state
03-21 13:06:40.305 11201 11264 I jxcore-log: 
,03-21 13:06:40.310 11201 11264 I jxcore-log: # 145. #stopAdvertisingAndListening can be called multiple times in a row
03-21 13:06:40.310 11201 11264 I jxcore-log: 
,03-21 13:06:40.445 11201 11264 I jxcore-log: ok 498 should be in started state
03-21 13:06:40.445 11201 11264 I jxcore-log: 
,03-21 13:06:40.450 11201 11264 I jxcore-log: # teardown
03-21 13:06:40.450 11201 11264 I jxcore-log: 
,03-21 13:06:40.635 11201 11264 I jxcore-log: ok 499 should not be in advertising state
03-21 13:06:40.635 11201 11264 I jxcore-log: 
,03-21 13:06:40.640 11201 11264 I jxcore-log: ok 500 should still not be in advertising state
03-21 13:06:40.640 11201 11264 I jxcore-log: 
,03-21 13:06:40.645 11201 11264 I jxcore-log: # setup
03-21 13:06:40.645 11201 11264 I jxcore-log: 
,03-21 13:06:40.760 11201 11264 I jxcore-log: ok 501 should not be in started state
03-21 13:06:40.760 11201 11264 I jxcore-log: 
,03-21 13:06:40.765 11201 11264 I jxcore-log: # 146. functions are run from a queue in the right order
03-21 13:06:40.765 11201 11264 I jxcore-log: 
,03-21 13:06:40.935 11201 11264 I jxcore-log: ok 502 should be in started state
03-21 13:06:40.935 11201 11264 I jxcore-log: 
,03-21 13:06:40.945 11201 11264 I jxcore-log: # teardown
03-21 13:06:40.945 11201 11264 I jxcore-log: 
,03-21 13:06:41.090 11201 11264 I jxcore-log: ok 503 call order must match
03-21 13:06:41.090 11201 11264 I jxcore-log: 
,03-21 13:06:41.095 11201 11264 I jxcore-log: # setup
03-21 13:06:41.095 11201 11264 I jxcore-log: 
,03-21 13:06:41.270 11201 11264 I jxcore-log: ok 504 should not be in started state,
03-21 13:06:41.270 11201 11264 I jxcore-log: 
,03-21 13:06:41.280 11201 11264 I jxcore-log: # 147. #ThaliPeerPoolDefault - single action
03-21 13:06:41.280 11201 11264 I jxcore-log: 
,03-21 13:06:41.370 11201 11264 I jxcore-log: # teardown
03-21 13:06:41.370 11201 11264 I jxcore-log: 
,03-21 13:06:41.500 11201 11264 I jxcore-log: ok 505 is an agent
03-21 13:06:41.500 11201 11264 I jxcore-log: 
,03-21 13:06:41.500 11201 11264 I jxcore-log: ok 506 enqueue is fine
03-21 13:06:41.500 11201 11264 I jxcore-log: 
,03-21 13:06:41.505 11201 11264 I jxcore-log: ok 507 Everything should be off the queue
03-21 13:06:41.505 11201 11264 I jxcore-log: 
,03-21 13:06:41.510 11201 11264 I jxcore-log: # setup
03-21 13:06:41.510 11201 11264 I jxcore-log: 
,03-21 13:06:41.590 11201 11264 I jxcore-log: # 148. #ThaliPeerPoolDefault - multiple actions
03-21 13:06:41.590 11201 11264 I jxcore-log: 
,03-21 13:06:41.710 11201 11264 I jxcore-log: # teardown
03-21 13:06:41.710 11201 11264 I jxcore-log: 
,03-21 13:06:41.820 11201 11264 I jxcore-log: ok 508 is an agent
03-21 13:06:41.820 11201 11264 I jxcore-log: 
,03-21 13:06:41.825 11201 11264 I jxcore-log: ok 509 first enqueue is fine
03-21 13:06:41.825 11201 11264 I jxcore-log: 
,03-21 13:06:41.830 11201 11264 I jxcore-log: ok 510 is an agent
03-21 13:06:41.830 11201 11264 I jxcore-log: 
,03-21 13:06:41.830 11201 11264 I jxcore-log: ok 511 second enqueue is fine
03-21 13:06:41.830 11201 11264 I jxcore-log: 
,03-21 13:06:41.835 11201 11264 I jxcore-log: ok 512 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-21 13:06:41.835 11201 11264 I jxcore-log: 
,03-21 13:06:41.840 11201 11264 I jxcore-log: ok 513 Queue is empty
03-21 13:06:41.840 11201 11264 I jxcore-log: 
,03-21 13:06:41.845 11201 11264 I jxcore-log: Tests Complete
03-21 13:06:41.845 11201 11264 I jxcore-log: 
,03-21 13:06:42.120 11201 11264 I jxcore-log: Total: 0	Passed: 0	Failed: 0
03-21 13:06:42.120 11201 11264 I jxcore-log: 
,03-21 13:06:42.125 11201 11264 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 13:06:42.125 11201 11264 I jxcore-log: 
,03-21 13:06:42.125 11201 11201 I chromium: [INFO:CONSOLE(86)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (86)
03-21 13:06:42.140 11201 11201 I chromium: [INFO:CONSOLE(86)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (86)
,03-21 13:06:42.485 12895 12895 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-21 13:06:42.490 12895 12895 D AndroidRuntime: CheckJNI is OFF
,03-21 13:06:42.490 12895 12895 D AndroidRuntime: readGMSProperty: start
03-21 13:06:42.490 12895 12895 D AndroidRuntime: readGMSProperty: already setted!!
03-21 13:06:42.490 12895 12895 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 13:06:42.490 12895 12895 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 13:06:42.490 12895 12895 D AndroidRuntime: readGMSProperty: end
03-21 13:06:42.490 12895 12895 D AndroidRuntime: addProductProperty: start
,03-21 13:06:42.695 12895 12895 E AffinityControl: AffinityControl: registerfunction enter
,03-21 13:06:42.720 12895 12895 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 13:06:42.735  3369  3721 D PackageManager: START PACKAGE DELETE: observer{23950440}
03-21 13:06:42.735  3369  3721 D PackageManager: pkg{<packageName>}
03-21 13:06:42.735  3369  3721 D PackageManager: user{0}
03-21 13:06:42.735  3369  3721 D PackageManager: caller{2000}
03-21 13:06:42.735  3369  3721 D PackageManager: flags{2}
03-21 13:06:42.735  3369  3721 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 13:06:42.740  3369  3721 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 13:06:42.740  3369  3721 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 13:06:42.740  3369  3721 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 13:06:42.740  3369  3721 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 13:06:42.740  3369  3588 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-21 13:06:42.740  3369  3588 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 13:06:42.740  3369  3588 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-21 13:06:42.740  3369  3588 D ApplicationPolicy: getApplicationUninstallationEnabled
03-21 13:06:42.740  3369  3588 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-21 13:06:42.745  3369  3588 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-21 13:06:42.750  3369  3554 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg
,03-21 13:06:42.755  3369  3554 I ActivityManager: Killing 11201:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-21 13:06:42.780  3369  3554 I ActivityManager:   Force finishing activity 3 ActivityRecord{2d6060a5 u0 com.test.thalitest/.MainActivity t41}
,03-21 13:06:42.785  3369  3554 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 13:06:42.790  3369  3554 D InputDispatcher: Focus left window: 11201
,03-21 13:06:42.790  2858  3012 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,03-21 13:06:42.790  2858  3632 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,03-21 13:06:42.795  3369  3554 D InputDispatcher: Focused application released
,03-21 13:06:42.795  3369  3580 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3369 uid:1000
03-21 13:06:42.795  3369  3580 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 13:06:42.795  3369  3580 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3369 uid:1000
03-21 13:06:42.795  3369  3580 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-21 13:06:42.885  3369  3588 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-21 13:06:42.890  3369  3588 W PackageSettings: Skipping PackageSetting{38afe092 com.example.hello/10691} due to missing metadata
,03-21 13:06:42.915  3369  3588 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-21 13:06:42.930  3369  3588 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
,03-21 13:06:42.950  3369  6094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 13:06:43.035  4129  4129 I art     : Explicit concurrent mark sweep GC freed 5451(325KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 6MB/8MB, paused 760us total 60.954ms
,03-21 13:06:43.080  9119  9119 I art     : Explicit concurrent mark sweep GC freed 2670(151KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 1770KB/5MB, paused 612us total 19.057ms
,03-21 13:06:43.085  3924  3924 I art     : Explicit concurrent mark sweep GC freed 1335(73KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 508us total 18.405ms
,03-21 13:06:43.090  4620  4620 I art     : Explicit concurrent mark sweep GC freed 2923(183KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 8MB/11MB, paused 1.122ms total 72.531ms
,03-21 13:06:43.090  4620  4632 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-21 13:06:43.090  3369  3588 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 13:06:43.105  4032  4032 I art     : Explicit concurrent mark sweep GC freed 2302(125KB) AllocSpace objects, 10(1489KB) LOS objects, 12% free, 56MB/64MB, paused 567us total 27.277ms
,03-21 13:06:43.120  3369  3634 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 13:06:43.125  3728  3728 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-21 13:06:43.125  4298  4715 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 13:06:43.130  4505  4505 E SamsungIME: mOCRHelper is null
,03-21 13:06:43.140 10667 10667 D LWLocationManager: getDeviceLocationId :  id = -100
03-21 13:06:43.140 10667 10667 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
,03-21 13:06:43.145  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.145  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.145  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.145  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.160 12925 12925 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.160 12925 12925 E Zygote  : v2
03-21 13:06:43.160 12925 12925 I libpersona: KNOX_SDCARD checking this for 10063
03-21 13:06:43.160 12925 12925 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:43.165 12925 12925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:06:43.165 12925 12925 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:43.170  3369  3554 I ActivityManager: Start proc 12925:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
,03-21 13:06:43.170 12925 12925 E Zygote  : accessInfo : 0
,03-21 13:06:43.170 12925 12925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 13:06:43.175  3369  3693 D TaskPersister: removeObsoleteFile: deleting file=41_task.xml
03-21 13:06:43.175  3369  3693 D TaskPersister: removeObsoleteFile: deleting file=41_task_thumbnail.png
,03-21 13:06:43.175  5632  5650 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-21 13:06:43.175  5632  5650 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
,03-21 13:06:43.195  3369  3654 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-21 13:06:43.195  3369  3654 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 13:06:43.195  3369  3654 V NetworkStats: performPollLocked(flags=0x3)
,03-21 13:06:43.200  3369  3654 V NetworkStats: performPollLocked() took 8ms
03-21 13:06:43.200  3369  3654 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 13:06:43.205 12925 12925 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:06:43.205 12925 12925 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.210  4001  4001 D RegisteredServicesCache: empty dynamic service
,03-21 13:06:43.225  3369  4389 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b976526 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{21abd567 12925:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-21 13:06:43.230  4001  4001 D RegisteredComponentCache: Collect Tech packages for Knox
,03-21 13:06:43.270  3369  3369 I art     : Explicit concurrent mark sweep GC freed 72430(5MB) AllocSpace objects, 76(1216KB) LOS objects, 33% free, 28MB/42MB, paused 2.270ms total 190.005ms
,03-21 13:06:43.270  3369  3588 I art     : WaitForGcToComplete blocked for 95.433ms for cause Explicit
,03-21 13:06:43.275 12925 12925 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-21 13:06:43.275 12925 12925 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-21 13:06:43.275 12925 12925 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,03-21 13:06:43.290  3369  3386 I ActivityManager: Killing 10087:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,03-21 13:06:43.290  7165  7165 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 21 13:06:43 GMT+01:00 2016
03-21 13:06:43.290  3369  3386 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b976526 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3a7fff3f 7165:com.samsung.klmsagent/u0a21}
,03-21 13:06:43.295  3369  5929 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-21 13:06:43.300  3369  3655 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 13:06:43.300  3369  3655 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 13:06:43.305  3369  4031 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,03-21 13:06:43.305  7165  7165 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-21 13:06:43.310  3369  3965 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-21 13:06:43.310  3369  3965 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,03-21 13:06:43.310  7165  7165 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
,03-21 13:06:43.320  3369  3965 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b976526 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{afad148 6794:com.samsung.aasaservice/1000}
,03-21 13:06:43.320  6794  6794 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,03-21 13:06:43.320  7165  7165 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-21 13:06:43.325  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.325  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.325  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.325  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.325  6794  6794 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,03-21 13:06:43.325  7165  7165 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-21 13:06:43.330  6794  6794 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
,03-21 13:06:43.330  7165 12944 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
03-21 13:06:43.330  7165 12944 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
03-21 13:06:43.330  7165 12944 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
03-21 13:06:43.330  7165 12944 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-21 13:06:43.330  7165 12944 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-21 13:06:43.330  6794  6794 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-21 13:06:43.330  6794  6794 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-21 13:06:43.330  6794  6794 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-21 13:06:43.330  6794  6794 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-21 13:06:43.330  6794  6794 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 13:06:43.330  6794  6794 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:43.330  6794  6794 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 13:06:43.330  6794  6794 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:43.330  6794  6794 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:43.330  6794  6794 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:43.330  6794  6794 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:43.330  7165 12944 I KLMS-2.5.262: : MDMBridge.getInstance()
03-21 13:06:43.330  7165 12944 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-21 13:06:43.335  7165 12944 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-21 13:06:43.345  3369  3554 I ActivityManager: Start proc 12945:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,03-21 13:06:43.345 12945 12945 E Zygote  : MountEmulatedStorage()
,03-21 13:06:43.345 12945 12945 E Zygote  : v2
03-21 13:06:43.345 12945 12945 I libpersona: KNOX_SDCARD checking this for 10042
03-21 13:06:43.345 12945 12945 I libpersona: KNOX_SDCARD not a persona
03-21 13:06:43.345 12945 12945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 13:06:43.345 12945 12945 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:43.345 12945 12945 E Zygote  : accessInfo : 0
03-21 13:06:43.345 12945 12945 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-21 13:06:43.345  3369  3554 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2ad8b829 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a436c6b 10910:com.samsung.android.sm/1000}
,03-21 13:06:43.350  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.350  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.350  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.350  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.355  7165 12944 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-21 13:06:43.360  3369  3537 D EnterpriseDeviceManagerService: Package has changed for user 0
03-21 13:06:43.360  3369  3537 W TextServicesManagerService: no available spell checker services found
03-21 13:06:43.360  3369  3537 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-21 13:06:43.360  7165 12944 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-21 13:06:43.365  7165 12944 E KLMS-2.5.262: : arr si null
,03-21 13:06:43.370 12960 12960 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.370 12960 12960 E Zygote  : v2
,03-21 13:06:43.375 12960 12960 I libpersona: KNOX_SDCARD checking this for 1000
03-21 13:06:43.375 12960 12960 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:43.375  3369  3554 I ActivityManager: Start proc 12960:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
03-21 13:06:43.375 12960 12960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:06:43.375 12960 12960 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:43.375 12960 12960 E Zygote  : accessInfo : 0
,03-21 13:06:43.380 12960 12960 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 13:06:43.380  7165 12944 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-21 13:06:43.380 12945 12945 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:06:43.385 12945 12945 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.390  7165 12944 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
03-21 13:06:43.390  7165 12944 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-21 13:06:43.390  7165 12944 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
,03-21 13:06:43.395  3369  3964 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b976526 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2c4779fd 3369:system/1000}
,03-21 13:06:43.405  3369  3721 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{1f1917ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{217a494f 12945:com.samsung.android.sdk.samsunglink/u0a42}
,03-21 13:06:43.415 12960 12960 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:06:43.415 12960 12960 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.420 12945 12945 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 13:06:43.420 12945 12945 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-21 13:06:43.430  3369  3964 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{58178dc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{211bade5 12960:com.sec.android.app.popupuireceiver/1000}
,03-21 13:06:43.430 10667 12943 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 13:06:43.445  7165 12944 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
03-21 13:06:43.445  7165 12944 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-21 13:06:43.445  7165 12944 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-21 13:06:43.445  7165 12944 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-21 13:06:43.450  7165 12944 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-21 13:06:43.450  7165 12944 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
03-21 13:06:43.450  7165 12944 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-21 13:06:43.450  7165 12944 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-21 13:06:43.455  7165  7165 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,03-21 13:06:43.460 10910 10910 I art     : Explicit concurrent mark sweep GC freed 1484(73KB) AllocSpace objects, 0(0B) LOS objects, 53% free, 1786KB/3MB, paused 237us total 16.388ms
,03-21 13:06:43.460 12960 12960 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-21 13:06:43.470  3369  3588 I art     : Explicit concurrent mark sweep GC freed 19814(1326KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 6.404ms total 196.257ms
,03-21 13:06:43.475  3369  5929 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-21 13:06:43.475  3369  4031 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-21 13:06:43.480 12960 12960 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,03-21 13:06:43.480  3369  3822 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
,03-21 13:06:43.480 12960 12960 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
,03-21 13:06:43.480 12960 12960 D PopupuiReceiver: Action package removed
,03-21 13:06:43.490  3369  3836 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{58178dc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3aa1f7be 10601:com.samsung.android.snote/u0a160}
,03-21 13:06:43.495  3369  3836 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2ad8b829 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a436c6b 10910:com.samsung.android.sm/1000}
,03-21 13:06:43.500  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.500  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.500  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.500  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.510 12977 12977 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.510 12977 12977 E Zygote  : v2
,03-21 13:06:43.515 12977 12977 I libpersona: KNOX_SDCARD checking this for 10183
03-21 13:06:43.515 12977 12977 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:43.515 12977 12977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:06:43.515 12977 12977 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:43.515 12977 12977 E Zygote  : accessInfo : 0
,03-21 13:06:43.515 12977 12977 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-21 13:06:43.515 10667 12943 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 13:06:43.515 10667 12943 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 13:06:43.515 10667 12943 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 13:06:43.520 10667 12943 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-21 13:06:43.520 10910 12976 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-21 13:06:43.520  3369  3836 I ActivityManager: Start proc 12977:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,03-21 13:06:43.525  3369  3588 D PackageManager: delete codoeFile: 
03-21 13:06:43.525  3369  3588 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
,03-21 13:06:43.530 12945 12945 I SL_DEBUG: isLoggable:: isProductShip = 1
,03-21 13:06:43.530 12945 12945 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
03-21 13:06:43.530 10763 10777 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
03-21 13:06:43.530 10763 10777 D BadgeProvider: update, [uri.query] : null
03-21 13:06:43.530 10763 10777 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 13:06:43.530  3369  3588 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-21 13:06:43.530 10763 10777 D BadgeProvider: update, [UpdateCount] : 0
,03-21 13:06:43.535  3369  3836 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2ad8b829 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a436c6b 10910:com.samsung.android.sm/1000}
03-21 13:06:43.535  3369  3588 I AASA_removePackage: UID=10011 Target=com.test.thalitest
,03-21 13:06:43.535 12977 12977 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 13:06:43.535  3369  3588 D PackageManager: result of delete: 1{23950440}
,03-21 13:06:43.535 12977 12977 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.540  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.540  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-21 13:06:43.540  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.540  3369  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.545 12895 12895 I art     : System.exit called, status: 0
03-21 13:06:43.545 12895 12895 I AndroidRuntime: VM exiting with result code 0.
,03-21 13:06:43.545  3369  3588 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 13:06:43.545  3369  3588 D PackageManager: userId{-1}
03-21 13:06:43.545  3369  3588 D PackageManager: andCode{true}
,03-21 13:06:43.555 12997 12997 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.555 12997 12997 E Zygote  : v2
03-21 13:06:43.555 12997 12997 I libpersona: KNOX_SDCARD checking this for 1000
03-21 13:06:43.555 12997 12997 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:43.555 12997 12997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 13:06:43.555 12997 12997 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:43.555 12997 12997 E Zygote  : accessInfo : 0
,03-21 13:06:43.560  3369  3836 I ActivityManager: Start proc 12997:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,03-21 13:06:43.560 12997 12997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 13:06:43.560  3369  3836 I ActivityManager: Killing 10350:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
,03-21 13:06:43.570  3369  4047 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{58178dc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1dbcc622 12977:com.samsung.android.provider.shootingmodeprovider/u0a183}
,03-21 13:06:43.585 12997 12997 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 13:06:43.585 10763 10777 D BadgeProvider: insert, [uri] : content://com.sec.badge/apps [ContentValues] : package=com.samsung.android.sm badgecount=0 class=com.samsung.android.sm.app.dashboard.SmartManagerDashBoardActivity
03-21 13:06:43.585 10763 10777 D BadgeProvider: insert, [args] : com.sec.android.provider.badge.BadgeProvider$SqlArguments@23940230
03-21 13:06:43.585 12997 12997 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.590  9747 13011 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,03-21 13:06:43.590  9747 13011 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
,03-21 13:06:43.590  9747 13011 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,03-21 13:06:43.590  9747 13011 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
03-21 13:06:43.590  2901  2901 I art     : Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 224us total 30.302ms
,03-21 13:06:43.595  9747 13011 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-21 13:06:43.595  9747 13011 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
,03-21 13:06:43.600  3369  3386 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2ad8b829 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{cc15d0f 12997:com.samsung.android.app.assistantmenu/1000}
,03-21 13:06:43.600  2901  2901 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 382us total 7.436ms
,03-21 13:06:43.610  2901  2901 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 464us total 7.448ms
,03-21 13:06:43.615  3369  3537 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 13:06:43.630 12997 12997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
,03-21 13:06:43.630 12977 12977 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-21 13:06:43.635  3369  3964 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-21 13:06:43.635  3369  3537 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 13:06:43.635  3369  3537 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 13:06:43.635  3369  3537 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 13:06:43.635  3369  3537 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-21 13:06:43.640  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.640  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.640  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.640  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.655 10763 10777 D BadgeProvider: insert, [rowId] : 4
,03-21 13:06:43.655 10763 10777 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/4
03-21 13:06:43.655 10763 10777 D BadgeProvider: sendNotify, [notify] : null
03-21 13:06:43.655 10763 10777 D BadgeProvider: insert, [sendNotify uri] : content://com.sec.badge/apps/4
03-21 13:06:43.655 13016 13016 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.655 13016 13016 E Zygote  : v2
03-21 13:06:43.655 13016 13016 I libpersona: KNOX_SDCARD checking this for 1000
03-21 13:06:43.655 13016 13016 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:43.655 13016 13016 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:06:43.655 13016 13016 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:43.655 13016 13016 E Zygote  : accessInfo : 0
03-21 13:06:43.655  4032  4032 D Launcher.Model: reloadBadges entered.
03-21 13:06:43.655 13016 13016 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 13:06:43.660  3369  4389 I ActivityManager: Start proc 13016:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
,03-21 13:06:43.660  3369  3387 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,03-21 13:06:43.670  3369  3369 D RCPManagerService: PackageReceiver onReceive()
03-21 13:06:43.670  3369  3369 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-21 13:06:43.670 13016 13016 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:06:43.670 13016 13016 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.675  3369  3369 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-21 13:06:43.675  3369  3369 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-21 13:06:43.675  3369  3369 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-21 13:06:43.680  3369  3369 I OTPFW   : ProvisionData::getAllEntries Enter
,03-21 13:06:43.680  3369  3369 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-21 13:06:43.680  3369  3369 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 13:06:43.685  3369  3369 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 13:06:43.685  3369  3537 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
03-21 13:06:43.685  3369  3537 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicy: uID is 10011
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 13:06:43.685  3369  3369 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 13:06:43.685  4032  4032 E Launcher.Model: onPackageRemoved :com.test.thalitest
03-21 13:06:43.685  3369  3369 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 13:06:43.685  3369  3369 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-21 13:06:43.685  3369  3369 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
,03-21 13:06:43.690  3369  3369 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
,03-21 13:06:43.690  3369  3590 D EnterprisePartitionManager: RCV <-
03-21 13:06:43.690  3369  3369 D EnterprisePartitionManager: RMV <-
,03-21 13:06:43.695 10763 10773 D BadgeProvider: query, [selection] : null
,03-21 13:06:43.695  3369  4776 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2ad8b829 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{a58ecfb 13016:com.sec.knox.bridge/1000}
,03-21 13:06:43.700  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.700  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.700  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.700  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.700  3369  3369 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-21 13:06:43.700  2856  3061 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
03-21 13:06:43.700  3369  3369 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-21 13:06:43.700  2856  3061 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 13:06:43.700  3369  3369 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 13:06:43.700  3369  3369 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-21 13:06:43.700  3369  3369 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-21 13:06:43.700  3369  3369 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 13:06:43.700  3369  3369 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 13:06:43.700  3369  3369 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 13:06:43.700  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:43.700  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:43.700  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:43.700  3369  3369 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-21 13:06:43.700 12945 12945 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
03-21 13:06:43.700  3369  3369 W System.err: 	at libcore.io.Posix.open(Native Method)
03-21 13:06:43.700  3369  3369 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 13:06:43.700  3369  3369 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 13:06:43.700  3369  3369 W System.err: 	... 18 more
03-21 13:06:43.700  3369  3369 E SdpManagerService: failed to get engine list
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicy: uID is 10011
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 13:06:43.705  3369  6063 D SSRM:bd : MSG_TYPE_APP_REMOVED::
,03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 13:06:43.705 12945 12945 D SecWifiDisplayUtil: Metadata value : none
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 13:06:43.705  3369  3369 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-21 13:06:43.705 13016 13016 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 13:06:43.725 13035 13035 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.725 13035 13035 E Zygote  : v2
03-21 13:06:43.725 13035 13035 I libpersona: KNOX_SDCARD checking this for 10190
03-21 13:06:43.725 13035 13035 I libpersona: KNOX_SDCARD not a persona
03-21 13:06:43.725 13035 13035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:06:43.725 13035 13035 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 13:06:43.725 13035 13035 E Zygote  : accessInfo : 0
03-21 13:06:43.730 13035 13035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 13:06:43.730 13016 13016 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,03-21 13:06:43.730  3369  4389 I ActivityManager: Start proc 13035:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
,03-21 13:06:43.735  3369  4402 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-21 13:06:43.735  3369  4402 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-21 13:06:43.740  3369  3369 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b976526 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{18ff00f 6130:com.sec.android.service.health/u0a19}
,03-21 13:06:43.740  6130  6130 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
03-21 13:06:43.740  6130  6130 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-21 13:06:43.740  6130  6130 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,03-21 13:06:43.740  3369  3369 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-21 13:06:43.740  3369  3387 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,03-21 13:06:43.760 13035 13035 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:06:43.760  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.760  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.760  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.760  3369  4389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.760 13035 13035 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.770  2856  3061 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
03-21 13:06:43.770  2856  3061 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 13:06:43.770 12945 12945 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,03-21 13:06:43.775 13050 13050 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.775 13050 13050 E Zygote  : v2
03-21 13:06:43.775 13050 13050 I libpersona: KNOX_SDCARD checking this for 10101
03-21 13:06:43.775 13050 13050 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:43.775 13050 13050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:06:43.775 13050 13050 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:43.780 13050 13050 E Zygote  : accessInfo : 0
03-21 13:06:43.780  3369  4389 I ActivityManager: Start proc 13050:com.google.android.apps.docs/u0a101 for broadcast-4 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
03-21 13:06:43.780 13050 13050 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 13:06:43.785  3369  3605 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-21 13:06:43.785  3369  3605 D UsbHostManager: displayNotification : [02h,02h,01h]
,03-21 13:06:43.790  3369  3605 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-21 13:06:43.790  3369  3605 D UsbHostManager: displayNotification : [0ah,00h,00h]
,03-21 13:06:43.790  3369  4389 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b976526 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{30cc47e9 10667:com.sec.android.widgetapp.locationwidget/u0a22}
03-21 13:06:43.790  3369  3605 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-21 13:06:43.790  3369  3605 D UsbHostManager: displayNotification : [02h,0dh,00h]
,03-21 13:06:43.790  3369  3605 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-21 13:06:43.790  3369  3605 D UsbHostManager: displayNotification : [0ah,00h,01h]
,03-21 13:06:43.795  3369  3605 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-21 13:06:43.795  3369  3605 D UsbHostManager: displayNotification : [09h,00h,00h]
,03-21 13:06:43.795  3369  3695 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-21 13:06:43.795  3369  3695 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-21 13:06:43.795  3369  3695 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,03-21 13:06:43.800 10667 10667 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-21 13:06:43.800  3369  4031 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{58178dc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{13dae9ad 13035:com.sec.android.widgetapp.tapandpay/u0a190}
,03-21 13:06:43.800  3369  5929 D ActivityManager: startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,03-21 13:06:43.805  4032  4085 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-21 13:06:43.805  4032  4085 E SQLiteLog: (6922) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-21 13:06:43.805 13050 13050 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 13:06:43.810 13050 13050 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.815  3369  4404 I ActivityManager: Killing 10439:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-21 13:06:43.815  3369  3369 W System.err: java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
,03-21 13:06:43.815  3369  3369 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 13:06:43.815  3369  3369 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 13:06:43.815  3369  3369 W System.err: 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
03-21 13:06:43.815  3369  3369 W System.err: 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
03-21 13:06:43.815  3369  3369 W System.err: 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
03-21 13:06:43.815  3369  3369 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 13:06:43.815  3369  3369 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:43.815  3369  3369 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 13:06:43.815  3369  3369 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 13:06:43.815  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:43.815  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:43.815  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:43.815  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:43.815  3369  3369 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 13:06:43.815  3369  3369 W System.err: 	at libcore.io.Posix.open(Native Method)
03-21 13:06:43.815  3369  3369 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 13:06:43.815  3369  3369 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 13:06:43.815  3369  3369 W System.err: 	... 12 more
03-21 13:06:43.815  3369  3369 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/harmony_third_party_apps.xml.tmp
03-21 13:06:43.820  3369  3369 W System.err: java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
,03-21 13:06:43.820  3369  3369 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 13:06:43.820  3369  3369 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 13:06:43.820  3369  3369 W System.err: 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
03-21 13:06:43.820  3369  3369 W System.err: 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
03-21 13:06:43.820  3369  3369 W System.err: 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
03-21 13:06:43.820  3369  3369 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 13:06:43.820  3369  3369 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:43.820  3369  3369 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 13:06:43.820  3369  3369 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 13:06:43.820  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:43.820  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:43.820  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:43.820  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:43.820  3369  3369 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 13:06:43.820  3369  3369 W System.err: 	at libcore.io.Posix.open(Native Method)
03-21 13:06:43.820  3369  3369 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 13:06:43.820  3369  3369 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 13:06:43.820  3369  3369 W System.err: 	... 12 more
03-21 13:06:43.820  3369  3369 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/harmony_third_party_apps.xml.tmp
,03-21 13:06:43.825  3369  3369 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131074) and mode_t (0) due to error (30)
,03-21 13:06:43.825  3369  3836 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{2ad8b829 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{22b20073 13050:com.google.android.apps.docs/u0a101}
,03-21 13:06:43.825  3369  3369 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: #################################################################
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: #################################################################
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:674)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at com.android.server.LpnetManagerService$DBManager.dbOpen(LpnetManagerService.java:2118)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at com.android.server.LpnetManagerService$2$1.run(LpnetManagerService.java:710)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:43.825  3369  3369 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:43.825  3369  3369 E LpnetManagerService: Exception on handling DB : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:43.825  3369  3369 E LpnetManagerService: #################################################################
03-21 13:06:43.825  3369  3369 E LpnetManagerService: Error Code : 0 (SQLITE_OK)
03-21 13:06:43.825  3369  3369 E LpnetManagerService: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:43.825  3369  3369 E LpnetManagerService: #################################################################
03-21 13:06:43.825  3369  3369 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:43.825  336,9  3369 W System.err: #################################################################
03-21 13:06:43.825  3369  3369 W System.err: Error Code : 0 (SQLITE_OK)
03-21 13:06:43.825  3369  3369 W System.err: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:43.825  3369  3369 W System.err: #################################################################
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:674)
03-21 13:06:43.825  3369  3369 W System.err: 	at com.android.server.LpnetManagerService$DBManager.dbOpen(LpnetManagerService.java:2118)
03-21 13:06:43.825  3369  3369 W System.err: 	at com.android.server.LpnetManagerService$2$1.run(LpnetManagerService.java:710)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 13:06:43.825  3369  3369 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:43.825  3369  3369 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 13:06:43.825  3369  3369 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 13:06:43.825  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:43.825  3369  3369 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:43.825  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:43.825  3369  3369 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-21 13:06:43.830  4032  4085 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
03-21 13:06:43.830  4032  4085 E AndroidRuntime: Process: com.sec.android.app.launcher, PID: 4032
03-21 13:06:43.830  4032  4085 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at com.android.launcher2.LauncherProvider.updateAppItems(LauncherProvider.java:488)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$4.run(LauncherModel.java:586)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at com.android.launcher2.LauncherModel.updateAppItems(LauncherModel.java:590)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at com.android.launcher2.MenuAppLoader.removePackage(MenuAppLoader.java:533)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at com.android.launcher2.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:2432)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:43.830  4032  4085 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 13:06:43.830  3369  3369 I ActivityManager: Killing 10499:com.samsung.android.intelligenceservice/u0a3 (adj 15): emptyCount ##31
,03-21 13:06:43.835  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.835  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.835  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.835  3369  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.840  3369  3695 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-21 13:06:43.840  3369  3695 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,03-21 13:06:43.865 13074 13074 E Zygote  : MountEmulatedStorage()
03-21 13:06:43.865 13074 13074 E Zygote  : v2
03-21 13:06:43.865 13074 13074 I libpersona: KNOX_SDCARD checking this for 1000
03-21 13:06:43.865 13074 13074 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:43.865 13074 13074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 13:06:43.865 13074 13074 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 13:06:43.870 13074 13074 E Zygote  : accessInfo : 0
,03-21 13:06:43.870 13074 13074 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 13:06:43.875 13035 13035 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,03-21 13:06:43.875 13035 13035 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,03-21 13:06:43.890 13035 13035 I TapandpayWidget:Utils: Clear T&P info.
03-21 13:06:43.890  3369  3822 I ActivityManager: Start proc 13074:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
,03-21 13:06:43.900  3369  3634 I EventHub: Removing device '/dev/input/event10' due to inotify event
03-21 13:06:43.905  3369  3822 I ActivityManager: Killing 10514:com.samsung.helphub/1000 (adj 15): emptyCount ##31
,03-21 13:06:43.910 13035 13035 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,03-21 13:06:43.935  3369  3965 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-21 13:06:43.945 13074 13074 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 13:06:43.945 13074 13074 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:43.965  3369  3634 I EventHub: Removing device '/dev/input/event7' due to inotify event
,03-21 13:06:43.965  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.965  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.965  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:43.965  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:43.975  3369  3634 I EventHub: Removing device '/dev/input/event8' due to inotify event
,03-21 13:06:44.005 13091 13091 E Zygote  : MountEmulatedStorage()
03-21 13:06:44.005 13091 13091 E Zygote  : v2
03-21 13:06:44.005 13091 13091 I libpersona: KNOX_SDCARD checking this for 10193
03-21 13:06:44.005 13091 13091 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:44.005 13091 13091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 13:06:44.005 13091 13091 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:44.010 13091 13091 E Zygote  : accessInfo : 0
,03-21 13:06:44.010 13091 13091 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 13:06:44.015  3369  3634 I EventHub: Removing device '/dev/input/event9' due to inotify event
,03-21 13:06:44.035  3369  4404 I ActivityManager: Start proc 13091:com.sec.enterprise.knox.cloudmdm.smdms/u0a193 for broadcast-4 com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver
,03-21 13:06:44.040  3369  4404 I ActivityManager: Killing 10535:com.samsung.android.bbc.bbcagent/1000 (adj 15): emptyCount ##31
,03-21 13:06:44.050 10910 10910 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,03-21 13:06:44.065  3369 13105 E DropBoxManagerService: Can't write: system_app_crash
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 13:06:44.065  3369 13105 E DropBoxManagerService: 	... 5 more
03-21 13:06:44.065  3369 13105 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop227.tmp
,03-21 13:06:44.075 13091 13091 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 13:06:44.075 13091 13091 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:44.080  3369  3964 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b976526 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3b880a5c 13074:com.sec.pcw.device/1000}
,03-21 13:06:44.090  3369  3387 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,03-21 13:06:44.095  3369  3634 I EventHub: Removing device '/dev/input/event11' due to inotify event
,03-21 13:06:44.095  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:44.095  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:44.095  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:44.095  3369  4404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:44.135 13108 13108 E Zygote  : MountEmulatedStorage()
03-21 13:06:44.135 13108 13108 E Zygote  : v2
03-21 13:06:44.135 13108 13108 I libpersona: KNOX_SDCARD checking this for 10045
03-21 13:06:44.135 13108 13108 I libpersona: KNOX_SDCARD not a persona
,03-21 13:06:44.140 13108 13108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 13:06:44.140 13108 13108 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 13:06:44.145 13108 13108 E Zygote  : accessInfo : 0
,03-21 13:06:44.145 13108 13108 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 13:06:44.150  3369  4404 I ActivityManager: Start proc 13108:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
,03-21 13:06:44.170  3369  3965 W ActivityManager:   Force finishing activity 1 com.sec.android.app.launcher/com.android.launcher2.Launcher
,03-21 13:06:44.175 13074 13074 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-21 13:06:44.175 13074 13074 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-21 13:06:44.175 13074 13074 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-21 13:06:44.180 13074 13074 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 13:06:44.180  4032  4032 D MenuAppsGridFragment: onDestroyView
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: #################################################################
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: #################################################################
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at com.android.,internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:44.185 13074 13074 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:44.185 13074 13074 D AndroidRuntime: Shutting down VM
03-21 13:06:44.185 13074 13074 E AndroidRuntime: FATAL EXCEPTION: main
03-21 13:06:44.185 13074 13074 E AndroidRuntime: Process: com.sec.pcw.device, PID: 13074
03-21 13:06:44.185 13074 13074 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.185 13074 13074 E AndroidRuntime: #################################################################
03-21 13:06:44.185 13074 13074 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.185 13074 13074 E AndroidRuntime: #################################################################
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.185 13074 13074 E AndroidRuntime: #################################################################
03-21 13:06:44.185 13074 13074 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.185 13074 13074 E AndroidRuntime: #################################################################
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 13:06:44.185 13074 13074 E AndroidRuntime:, 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 13:06:44.185 13074 13074 E AndroidRuntime: 	... 11 more
03-21 13:06:44.185  4032  4032 W Launcher.MenuAppsGrid: Trying to exit a state that hasn't been entered
03-21 13:06:44.195  4032  4085 I Process : Sending signal. PID: 4032 SIG: 9
03-21 13:06:44.200 10763 10773 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 13:06:44.200 10763 10773 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
03-21 13:06:44.205 10763 10773 E DatabaseUtils: Writing exception to parcel
03-21 13:06:44.205 10763 10773 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: #################################################################
03-21 13:06:44.205 10763 10773 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	(disk I/O error (code 6922))
03-21 13:06:44.205 10763 10773 E DatabaseUtils: #################################################################
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
03-21 13:06:44.205 10763 10773 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
03-21 13:06:44.220 13108 13108 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 13:06:44.225 13108 13108 D ActivityThread: Added TimaKeyStore provider
,03-21 13:06:44.245  3369  3721 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{58178dc u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2b3ca165 13091:com.sec.enterprise.knox.cloudmdm.smdms/u0a193}
,03-21 13:06:44.250  3369  4396 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,03-21 13:06:44.270  3369  4389 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{1f1917ae u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1b1bae3a 13108:com.osp.app.signin/u0a45}
03-21 13:06:44.270 13091 13091 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-21 13:06:44.290  3369 13125 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop228.tmp
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: Can't write: system_app_crash
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 13:06:44.290  3369 13125 E DropBoxManagerService: 	... 5 more
,03-21 13:06:44.300 13091 13091 D [0]UMC:UMCContentProvider: @onCreate
,03-21 13:06:44.300  3369  4404 I ActivityManager: Killing 10621:com.samsung.android.snote:provider/u0a160 (adj 15): emptyCount ##31
,03-21 13:06:44.305  3369  4404 I ActivityManager: Killing 10569:com.google.android.apps.plus/u0a147 (adj 15): emptyCount ##32
,03-21 13:06:44.320  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:44.320  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:44.320  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 13:06:44.320  3369  3554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 13:06:44.325 13050 13050 E PhotosPlugin: Loading PhotosPlugin
,03-21 13:06:44.350 13108 13108 I SA      : [SSP] onCreated
,03-21 13:06:44.355 13108 13108 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/samsungaccount.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 13:06:44.355 13108 13108 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/samsungaccount.db'.
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: #################################################################
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: #################################################################
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at com.msc.contentprovider.SamsungServiceProvider.onCreate(SamsungServiceProvider.java:575)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:44.355 13108 13108 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-21 13:06:44.355 13126 13126 E Zygote  : MountEmulatedStorage()
03-21 13:06:44.355 13126 13126 I libpersona: KNOX_SDCARD checking this for 10035
03-21 13:06:44.355 13126 13126 E Zygote  : v2,
03-21 13:06:44.355 13126 13126 I libpersona: KNOX_SDCARD not a persona
03-21 13:06:44.360 13108 13108 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/openData.db" with flag (131138) and mode_t (0) due to error (30)
03-21 13:06:44.360 13126 13126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 13:06:44.360 13126 13126 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/openData.db'.
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: #################################################################
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: #################################################################
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at com.msc.openprovider.OpenContentProvider.onCreate(OpenContentProvider.java:214)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Me,thod.java:372)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 13:06:44.360 13108 13108 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 13:06:44.360 13126 13126 E Zygote  : accessInfo : 0
03-21 13:06:44.365 13126 13126 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 13:06:44.375  3369  3554 I ActivityManager: Start proc 13126:com.samsung.android.app.galaxyfinder/u0a35 for broadcast-3 com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver
03-21 13:06:44.375 13074 13074 I Process : Sending signal. PID: 13074 SIG: 9
03-21 13:06:44.380 13091 13091 D [0]UMC:Core: onCreate(): 
03-21 13:06:44.380 13091 13091 D [0]UMC:Core: @isManagedProfileUser

```
