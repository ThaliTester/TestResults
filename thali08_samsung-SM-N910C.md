#### Test 625481246a7d362_thali08_samsung-SM-N910C Logs


```
--------- beginning of system
03-21 15:50:43.806  3424  4413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 15:50:43.811  3424  4413 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 15:50:43.811  3424  4413 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,03-21 15:50:43.811  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 15:50:43.816  3424  3424 I MotionRecognitionService: Plugged
03-21 15:50:43.816  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-21 15:50:43.816  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 15:50:43.816  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
03-21 15:50:43.831  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:50:43.821  3424  4413 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
03-21 15:50:43.831  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:50:43.821  3424  4413 D BatteryService: stay LED for fully charged
03-21 15:50:43.831  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 15:50:43.851  5859  5859 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 15:50:43.851  5859  5956 D HeadsetStateMachine: Disconnected process message: 10
03-21 15:50:43.861  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:50:43.861  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:50:43.861  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:50:43.861  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:50:44.281 11087 11087 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 15:50:44.281 11087 11087 D AndroidRuntime: CheckJNI is OFF
03-21 15:50:44.286 11087 11087 D AndroidRuntime: readGMSProperty: start
03-21 15:50:44.286 11087 11087 D AndroidRuntime: readGMSProperty: already setted!!
03-21 15:50:44.286 11087 11087 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 15:50:44.286 11087 11087 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 15:50:44.286 11087 11087 D AndroidRuntime: readGMSProperty: end
03-21 15:50:44.286 11087 11087 D AndroidRuntime: addProductProperty: start
03-21 15:50:44.386 11087 11087 E AffinityControl: AffinityControl: registerfunction enter
03-21 15:50:44.406 11087 11087 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 15:50:44.416  3424  4736 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 15:50:44.421  3424  4736 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 15:50:44.456  3424  4736 W ActivityManager: mDVFSHelper.acquire()
03-21 15:50:44.456  3424  4736 D FocusedStackFrame: Set to : 0
03-21 15:50:44.461  3424  4736 V WindowManager: addAppToken: AppWindowToken{dfb719f token=Token{3fdf6f3e ActivityRecord{128a73f9 u0 com.test.thalitest/.MainActivity t41}}} to stack=1 task=41 at 0
03-21 15:50:44.466  3424  4736 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:50:44.466  3424  4736 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:50:44.466  3424  4736 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:50:44.466  3424  4736 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:50:44.471  3424  3583 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 15:50:44.471  3424  3583 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 15:50:44.471  3424  3583 D SecWifiDisplayUtil: Metadata value : none
03-21 15:50:44.476  3424  3583 V WindowManager: Adding window Window{15582816 u0 d0 Starting com.test.thalitest} at 2 of 6 (after Window{a6ffba8 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher})
03-21 15:50:44.481 11109 11109 E Zygote  : MountEmulatedStorage()
03-21 15:50:44.481 11109 11109 E Zygote  : v2
03-21 15:50:44.481 11109 11109 I libpersona: KNOX_SDCARD checking this for 10011
03-21 15:50:44.481 11109 11109 I libpersona: KNOX_SDCARD not a persona
03-21 15:50:44.486 11109 11109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:50:44.486 11109 11109 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 15:50:44.486 11109 11109 E Zygote  : accessInfo : 0
03-21 15:50:44.486 11109 11109 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 15:50:44.486  3424  4736 I ActivityManager: Start proc 11109:com.test.thalitest/u0a11 for activity com.test.thalitest/.MainActivity
03-21 15:50:44.486  3424  4736 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 15:50:44.486  3424  4736 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 15:50:44.491  3424  4736 D InputDispatcher: Focused application set to: xxxx
03-21 15:50:44.491  3424  4736 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
03-21 15:50:44.491  3424  4736 D InputDispatcher: Focus left window: 4013
03-21 15:50:44.491  3424  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 15:50:44.491  3424  3583 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 15:50:44.491 11087 11087 D AndroidRuntime: Shutting down VM
03-21 15:50:44.496  2859  2859 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-21 15:50:44.511  3424  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3424 uid:1000
03-21 15:50:44.511  3424  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 15:50:44.511  3424  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3424 uid:1000
03-21 15:50:44.511  3424  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 15:50:44.516 11109 11109 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:50:44.516 11109 11109 D ActivityThread: Added TimaKeyStore provider
03-21 15:50:44.521  3424  4728 V WindowOrientationListener: setCurrentAppOrientation :-1
03-21 15:50:44.526  3424  4728 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false
03-21 15:50:44.521  3424  4728 V WindowOrientationListener: setCurrentAppOrientation enable auto rotation
03-21 15:50:44.526  3424  4728 D PowerManagerService: setKeyboardVisibility: false
03-21 15:50:44.521  3424  4728 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 15:50:44.521  3424  4728 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 15:50:44.526  3424  4728 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
03-21 15:50:44.526  3424  4728 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
03-21 15:50:44.536  3424  3581 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{15582816 u0 d0 Starting com.test.thalitest}
03-21 15:50:44.576  4013  4013 V ActivityThread: updateVisibility : ActivityRecord{3a13308f token=android.os.BinderProxy@2f3d4f61 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-21 15:50:44.601  4013  4013 D Launcher: onTrimMemory. Level: 20
03-21 15:50:44.611  2859  3084 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
03-21 15:50:44.616  2859 10805 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
03-21 15:50:44.616  3424  4728 I ActivityManager: Skip updateThumbnail for r=ActivityRecord{128a73f9 u0 com.test.thalitest/.MainActivity t41}
03-21 15:50:44.666  3424  6046 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
03-21 15:50:44.686  3424  3618 V AlarmManager: waitForAlarm result :4
03-21 15:50:44.691  3424  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e86a76d u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE} DELIVERED for app ProcessRecord{28ab6b8e 4414:com.google.android.gms.persistent/u0a14}
,03-21 15:50:44.706 11109 11109 D SecWifiDisplayUtil: Metadata value : none
,03-21 15:50:44.731  3424  4735 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 15:50:44.761 11109 11109 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-21 15:50:44.771 11109 11109 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5497-5499)
03-21 15:50:44.771 11109 11109 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 15:50:44.786 11109 11109 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6b338e6}
,03-21 15:50:44.786 11109 11109 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 15:50:44.786 11109 11109 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 15:50:44.791 11109 11140 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,03-21 15:50:44.806  3424  3733 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 15:50:44.806 11109 11109 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 15:50:44.811 11109 11109 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 15:50:44.811 11109 11109 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 15:50:44.826 11109 11109 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-21 15:50:44.831 11109 11109 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=50556 len=3379
03-21 15:50:44.831 11109 11109 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:38 off:7638088 len:1165478
,03-21 15:50:44.901 11109 11164 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-21 15:50:44.931 11109 11109 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 15:50:44.946 11109 11109 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 15:50:44.956 11109 11109 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 15:50:44.956 11109 11109 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-21 15:50:44.961 11109 11109 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-21 15:50:44.966 11109 11109 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 15:50:44.966 11109 11109 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 15:50:45.011 11109 11177 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 15:50:45.016  3424  4413 V WindowManager: Adding window Window{3159ac38 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (before Window{15582816 u0 d0 Starting com.test.thalitest})
,03-21 15:50:45.016  3424  4047 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
03-21 15:50:45.016  3424  4047 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 15:50:45.016  3424  4047 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-21 15:50:45.016  3424  3424 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-21 15:50:45.016  3424  3424 E EnterpriseSharedDevicePolicy: isSharedDeviceEnabled
03-21 15:50:45.021  3424  3424 I EnterpriseSharedDevicePolicy: isSharedDeviceEnabled in Service
,03-21 15:50:45.021  3424  3424 I EnterpriseSharedDevicePolicy: Get Result: -1
,03-21 15:50:45.021  3424  3424 I EnterpriseSharedDevicePolicy: status: false
03-21 15:50:45.021  3424  3424 I KnoxTimeoutHandler: Shared devices show user statefalse
,03-21 15:50:45.021  3424  3424 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 15:50:45.026 11109 11109 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-21 15:50:45.026 11109 11109 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-21 15:50:45.031 11109 11109 D SecWifiDisplayUtil: Metadata value : none
,03-21 15:50:45.036  2859  2859 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,03-21 15:50:45.036  3424  3451 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 15:50:45.041  3424  3451 D InputDispatcher: Focus entered window: 11109,
,03-21 15:50:45.041  3424  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3424 uid:1000,
,03-21 15:50:45.041  3424  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 15:50:45.041  3424  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3424 uid:1000
03-21 15:50:45.041  3424  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
03-21 15:50:45.041 11109 11109 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
03-21 15:50:45.041 11109 11177 I OpenGLRenderer: Initialized EGL, version 1.4,
03-21 15:50:45.046 11109 11177 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xae42fcd0 ,&mEglDisplay = 1 , &mEglConfig = -1266872048 
03-21 15:50:45.046 11109 11177 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
03-21 15:50:45.046 11109 11177 D OpenGLRenderer: Enabling debug mode 0
03-21 15:50:45.046 11109 11177 D mali_winsys: new_window_surface returns 0x3000,  [1440x2560]-format:1
,03-21 15:50:45.051 11109 11109 V ActivityThread: updateVisibility : ActivityRecord{387e136e token=android.os.BinderProxy@ac71770 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-21 15:50:45.056  3424  3957 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 15:50:45.061  3724  3724 D PanelView: There is/are notification(s) 
,03-21 15:50:45.131 11109 11109 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 15:50:45.136 11109 11109 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ac71770 time:185860
,03-21 15:50:45.136  3424  6046 D SSRM:n  : SIOP:: AP = 270, PST = 281 (W:14), CUR = 39, LCD = 0
,03-21 15:50:45.141  3424  3583 I ActivityManager: Displayed Component not be shown by security: +496ms (total +1m27s935ms)
,03-21 15:50:45.141  3424  3583 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{128a73f9 u0 com.test.thalitest/.MainActivity t41} time:185867
03-21 15:50:45.141  3424  3583 W ActivityManager: mDVFSHelper.release()
03-21 15:50:45.141  2859  3084 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
03-21 15:50:45.141  2859 10805 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,03-21 15:50:45.191 11109 11109 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 11109
,03-21 15:50:45.216  4414 11185 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 9918 seconds from now (1458571845221)
,03-21 15:50:45.231  3424  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3b493b7c u0 com.google.android.gms.gcm.ACTION_SCHEDULE} DELIVERED for app ProcessRecord{28ab6b8e 4414:com.google.android.gms.persistent/u0a14}
,03-21 15:50:45.261 11109 11109 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 15:50:45.296  4414 11145 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-21 15:50:45.301  4414 11145 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-21 15:50:45.356 11109 11182 D jxcore_app_log: JniHelper::setJavaVM(0xb449d200), pthread_self() = -1626326912
,03-21 15:50:45.366 11109 11182 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 15:50:45.366 11109 11182 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 15:50:45.366 11109 11182 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 15:50:45.366 11109 11182 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 15:50:45.366 11109 11182 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 15:50:45.366 11109 11182 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360784ff added. We now have 1 listener(s)
,03-21 15:50:45.371 11109 11182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:14:E2:C0
,03-21 15:50:45.371 11109 11182 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:50:45.371 11109 11182 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 15:50:45.376 11109 11182 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 15:50:45.376 11109 11140 W System.err: remove failed: ENOENT (No such file or directory) : /data/data/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:14:E2:C0
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 15:50:45.381 11109 11182 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1083742a added. We now have 1 listener(s)
,03-21 15:50:45.381 11109 11182 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 15:50:45.386 11109 11182 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 15:50:45.386 11109 11182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-21 15:50:45.386 11109 11182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 15:50:45.386 11109 11182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 15:50:45.386 11109 11182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 15:50:45.391 11109 11182 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 15:50:45.391 11109 11182 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:14:E2:C0
,03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:50:45.401 11109 11182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 15:50:45.401 11109 11182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 15:50:45.401 11109 11182 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-21 15:50:45.401 11109 11182 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 15:50:45.401 11109 11109 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 15:50:45.406 11109 11109 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 15:50:45.431 11109 11109 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 15:50:45.606  3424  3733 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 15:50:45.651  3424  4413 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-21 15:50:45.671  4414 11145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-21 15:50:45.671  4414 11145 I System.out: (HTTPLog)-Static: isShipBuild true
03-21 15:50:45.671  4414 11145 I System.out: (HTTPLog)-Thread-278-562886276: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-21 15:50:45.671  4414 11145 I System.out: (HTTPLog)-Thread-278-562886276: SMARTBONDING_FEATURE_ENABLED is true
03-21 15:50:45.671  4414 11145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 15:50:45.671  2871  3410 D EnterpriseController: netId is 0
03-21 15:50:45.671  2871  3410 D Netd    : getNetworkForDns: using netid 502 for uid 10014
,03-21 15:50:45.731  4414 11145 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-21 15:50:45.731  4414 11145 I qtaguid : Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4414, getuid(): 10014
,03-21 15:50:45.776  4414 11145 I qtaguid : Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 4414, getuid(): 10014
,03-21 15:50:45.921 11109 11194 W jxcore-log: Initializing JXcore engine
03-21 15:50:45.921 11109 11194 W jxcore-log: JXcore engine is ready
,03-21 15:50:45.956  4780  4780 E auditd  : In denial and Property audit_ondenial is set to 1 
,03-21 15:50:45.956  4780  4780 E audit   : type=1400 msg=audit(1458571845.956:195): avc:  denied  { ioctl } for  pid=11194 comm="Thread-1533" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-21 15:50:45.956  3424  3579 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
03-21 15:50:45.956  4780  4780 E audit   :  SEPF_SM-N910C_5.1.1_0035
03-21 15:50:45.956  4780  4780 E audit   : type=1300 msg=audit(1458571845.956:195): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=973088d8 items=0 ppid=2900 ppcomm=main pid=11194 auid=4294967295 uid=10011 gid=10011 euid=10011 suid=10011 fsuid=10011 egid=10011 sgid=10011 fsgid=10011 ses=4294967295 tty=(none) comm="Thread-1533" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 15:50:45.956  3424  3579 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.android.server.SEDenialService$AuditFileObserver.onEvent:80 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
03-21 15:50:45.956  4780  4780 E audit   : type=1320 msg=audit(1458571845.956:195): 
,03-21 15:50:45.961  3424  3579 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,03-21 15:50:45.961  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:50:45.961  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:50:45.961  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:50:45.961  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:50:45.961 11109 11194 W jxcore-log: Starting JXcore engine
,03-21 15:50:45.971 11197 11197 E Zygote  : MountEmulatedStorage()
03-21 15:50:45.971 11197 11197 E Zygote  : v2
03-21 15:50:45.971 11197 11197 I libpersona: KNOX_SDCARD checking this for 1000
03-21 15:50:45.971 11197 11197 I libpersona: KNOX_SDCARD not a persona
,03-21 15:50:45.976 11197 11197 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 15:50:45.976 11197 11197 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:50:45.976 11197 11197 E Zygote  : accessInfo : 0
03-21 15:50:45.976 11197 11197 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 15:50:45.976  3424  3574 I ActivityManager: Start proc 11197:com.samsung.android.securitylogagent/1000 for broadcast-3 com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,03-21 15:50:45.991 11197 11197 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 15:50:45.991 11197 11197 D ActivityThread: Added TimaKeyStore provider
,03-21 15:50:46.001  3424  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{155efc03 u0 samsung.intent.action.knox.DENIAL_NOTIFICATION} DELIVERED for app ProcessRecord{378c6780 11197:com.samsung.android.securitylogagent/1000}
,03-21 15:50:46.011 11109 11194 W jxcore-log: Platform android
03-21 15:50:46.011 11109 11194 W jxcore-log: 
03-21 15:50:46.011 11109 11194 W jxcore-log: Process ARCH arm
03-21 15:50:46.011 11109 11194 W jxcore-log: 
,03-21 15:50:46.016 11197 11197 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-21 15:50:46.021 11197 11197 D SecurityLogAgent:  SeDenialReceiver : File path = null
,03-21 15:50:46.021  3424  3451 I ActivityManager: Killing 10111:com.sec.android.app.soundalive/u0a59 (adj 15): emptyCount ##31
,03-21 15:50:46.076  3424  3452 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 15:50:46.091  4414 11145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 15:50:46.091  4414 11145 I qtaguid : Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4414, getuid(): 10014
,03-21 15:50:46.106 11109 11194 I jxcore-log: JXcore Cordova bridge is ready!
03-21 15:50:46.106 11109 11194 I jxcore-log: 
03-21 15:50:46.106 11109 11194 W jxcore-log: JXcore engine is started
,03-21 15:50:46.111 11109 11182 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 15:50:46.111 11109 11109 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 15:50:46.251  3424  4735 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 15:50:46.256  4414 11145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-21 15:50:46.256  4414 11145 I qtaguid : Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4414, getuid(): 10014
,03-21 15:50:46.336  3424  3733 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 15:50:46.341  4414 11145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-21 15:50:46.341  4414 11145 I qtaguid : Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4414, getuid(): 10014
,03-21 15:50:46.476  3424  4728 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 15:50:46.481  3424  4728 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-21 15:50:46.486  4414  4414 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:46.486  4414  4414 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 15:50:46.501  4414 11145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-21 15:50:46.501  4414 11145 I qtaguid : Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4414, getuid(): 10014
,03-21 15:50:46.586  3424  4413 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,03-21 15:50:46.596  4414 11145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-21 15:50:46.596  4414 11145 I qtaguid : Tagging socket 82 with tag 1000120100000000{268440065,0} uid -1, pid: 4414, getuid(): 10014
,03-21 15:50:47.471  3424  3690 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/41_task.xml.bak
,03-21 15:50:48.941  3424  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 15:50:51.736  3424  3862 E Watchdog: !@Sync 6 [03-21 15:50:51.745]
,03-21 15:50:51.906 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:50:51.906 11109 11194 I jxcore-log: 
,03-21 15:50:51.911 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:50:51.911 11109 11194 I jxcore-log: 
,03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:50:51.911 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:50:51.911 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:50:51.916 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:50:51.916 11109 11194 I jxcore-log: 
,03-21 15:50:51.916 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:50:51.916 11109 11194 I jxcore-log: 
,03-21 15:50:52.231 11109 11194 I jxcore-log: Unit Test app is loaded
03-21 15:50:52.231 11109 11194 I jxcore-log: 
,03-21 15:50:52.236 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:50:52.236 11109 11194 I jxcore-log: 
,03-21 15:50:52.241 11109 11109 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 15:50:52.241 11109 11194 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-21 15:50:52.241 11109 11194 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-21 15:50:52.241 11109 11194 I jxcore-log: 
,03-21 15:50:52.241 11109 11194 I jxcore-log: My device name is: samsung-SM-N910C
03-21 15:50:52.241 11109 11194 I jxcore-log: 
,03-21 15:50:53.921  3424  3746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 15:50:53.921  3424  3746 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 15:50:53.921  3424  3746 D BatteryService: online:4, current avg:-121, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-210
03-21 15:50:53.921  3424  3746 D BatteryService: stay LED for fully charged
03-21 15:50:53.921  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 15:50:53.926  3424  3424 I MotionRecognitionService: Plugged
,03-21 15:50:53.926  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-21 15:50:53.926  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 15:50:53.926  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-21 15:50:53.931  5859  5859 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 15:50:53.931  5859  5956 D HeadsetStateMachine: Disconnected process message: 10
03-21 15:50:53.931  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:50:53.931  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:50:53.931  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 15:50:53.931  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:50:53.931  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:50:53.931  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:50:53.931  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 15:50:54.511  3424  3591 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-21 15:50:54.521  3424  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-21 15:50:54.546 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-21 15:50:54.546 11109 11194 I jxcore-log: 
,03-21 15:50:54.751 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-21 15:50:54.751 11109 11194 I jxcore-log: 
,03-21 15:50:54.756 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-21 15:50:54.756 11109 11194 I jxcore-log: 
,03-21 15:50:54.761 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-21 15:50:54.761 11109 11194 I jxcore-log: 
,03-21 15:50:54.781 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-21 15:50:54.781 11109 11194 I jxcore-log: 
,03-21 15:50:54.786 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-21 15:50:54.786 11109 11194 I jxcore-log: 
,03-21 15:50:54.791 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-21 15:50:54.791 11109 11194 I jxcore-log: 
,03-21 15:50:55.066  2893  4824 I MMD     : [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,03-21 15:50:55.146  3424  6046 D SSRM:n  : SIOP:: AP = 310, PST = 281 (W:10), CUR = -121, LCD = 0
,03-21 15:50:55.991 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-21 15:50:55.991 11109 11194 I jxcore-log: 
,03-21 15:50:55.996 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-21 15:50:55.996 11109 11194 I jxcore-log: 
,03-21 15:50:56.001 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-21 15:50:56.001 11109 11194 I jxcore-log: 
,03-21 15:50:56.071 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-21 15:50:56.071 11109 11194 I jxcore-log: 
,03-21 15:50:56.106 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-21 15:50:56.106 11109 11194 I jxcore-log: 
,03-21 15:50:56.186 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-21 15:50:56.186 11109 11194 I jxcore-log: 
,03-21 15:50:56.186 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-21 15:50:56.186 11109 11194 I jxcore-log: 
03-21 15:50:56.191 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-21 15:50:56.191 11109 11194 I jxcore-log: 
,03-21 15:50:56.201 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-21 15:50:56.201 11109 11194 I jxcore-log: 
,03-21 15:50:56.211 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-21 15:50:56.211 11109 11194 I jxcore-log: 
,03-21 15:50:56.271 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-21 15:50:56.271 11109 11194 I jxcore-log: 
,03-21 15:50:56.276 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-21 15:50:56.276 11109 11194 I jxcore-log: 
,03-21 15:50:56.286 11109 11194 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-21 15:50:56.286 11109 11194 I jxcore-log: 
,03-21 15:50:57.401 11109 11194 I jxcore-log: TAP version 13
03-21 15:50:57.401 11109 11194 I jxcore-log: 
,03-21 15:50:57.401 11109 11194 I jxcore-log: # setup
03-21 15:50:57.401 11109 11194 I jxcore-log: 
03-21 15:50:57.401 11109 11194 I jxcore-log: # 1. calling createNativeListener directly rejects
03-21 15:50:57.401 11109 11194 I jxcore-log: 
,03-21 15:50:57.566 11109 11194 I jxcore-log: # teardown
03-21 15:50:57.566 11109 11194 I jxcore-log: 
,03-21 15:50:57.686 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:50:57.686 11109 11194 I jxcore-log: 
,03-21 15:50:57.691 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 52012
03-21 15:50:57.691 11109 11194 I jxcore-log: 
,03-21 15:50:57.696 11109 11194 I jxcore-log: ok 1 Should throw
03-21 15:50:57.696 11109 11194 I jxcore-log: 
,03-21 15:50:57.701 11109 11194 I jxcore-log: # setup
03-21 15:50:57.701 11109 11194 I jxcore-log: 
,03-21 15:50:57.851 11109 11194 I jxcore-log: # 2. emits incomingConnectionState
03-21 15:50:57.851 11109 11194 I jxcore-log: 
,03-21 15:50:58.011 11109 11194 I jxcore-log: # teardown
03-21 15:50:58.011 11109 11194 I jxcore-log: 
,03-21 15:50:58.231 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:50:58.231 11109 11194 I jxcore-log: 
,03-21 15:50:58.236 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 57245
03-21 15:50:58.236 11109 11194 I jxcore-log: 
,03-21 15:50:58.251 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:50:58.251 11109 11194 I jxcore-log: 
,03-21 15:50:58.256 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:50:58.256 11109 11194 I jxcore-log: 
,03-21 15:50:58.266 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:50:58.266 11109 11194 I jxcore-log: 
,03-21 15:50:58.276 11109 11194 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-21 15:50:58.276 11109 11194 I jxcore-log: 
,03-21 15:50:58.306 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:50:58.306 11109 11194 I jxcore-log: 
,03-21 15:50:58.306 11109 11194 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-21 15:50:58.306 11109 11194 I jxcore-log: 
,03-21 15:50:58.316 11109 11194 I jxcore-log: # setup
03-21 15:50:58.316 11109 11194 I jxcore-log: 
,03-21 15:50:58.481 11109 11194 I jxcore-log: # 3. emits routerPortConnectionFailed
03-21 15:50:58.481 11109 11194 I jxcore-log: 
,03-21 15:50:58.616 11109 11194 I jxcore-log: # teardown
03-21 15:50:58.616 11109 11194 I jxcore-log: 
,03-21 15:50:58.811 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:50:58.811 11109 11194 I jxcore-log: 
,03-21 15:50:58.811 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 56073
03-21 15:50:58.811 11109 11194 I jxcore-log: 
,03-21 15:50:58.821 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:50:58.821 11109 11194 I jxcore-log: 
,03-21 15:50:58.821 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:50:58.821 11109 11194 I jxcore-log: 
,03-21 15:50:58.826 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:50:58.826 11109 11194 I jxcore-log: 
,03-21 15:50:58.861 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:50:58.861 11109 11194 I jxcore-log: 
,03-21 15:50:58.861 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:50:58.861 11109 11194 I jxcore-log: 
,03-21 15:50:58.871 11109 11194 I jxcore-log: DEBUG createNativeListener: 
03-21 15:50:58.871 11109 11194 I jxcore-log: 
,03-21 15:50:58.876 11109 11194 I jxcore-log: ok 4 tried to connect to right port
03-21 15:50:58.876 11109 11194 I jxcore-log: 
,03-21 15:50:58.876 11109 11194 I jxcore-log: ok 5 failed due to refused connection
03-21 15:50:58.876 11109 11194 I jxcore-log: 
,03-21 15:50:58.876 11109 11194 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-21 15:50:58.876 11109 11194 I jxcore-log: 
,03-21 15:50:58.886 11109 11194 I jxcore-log: # setup
03-21 15:50:58.886 11109 11194 I jxcore-log: 
,03-21 15:50:58.891 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:50:58.891 11109 11194 I jxcore-log: 
,03-21 15:50:59.031 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:50:59.031 11109 11194 I jxcore-log: 
,03-21 15:50:59.036 11109 11194 I jxcore-log: # 4. native server connections all up
03-21 15:50:59.036 11109 11194 I jxcore-log: 
,03-21 15:50:59.041 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:50:59.041 11109 11194 I jxcore-log: 
,03-21 15:50:59.181 11109 11194 I jxcore-log: # teardown
03-21 15:50:59.181 11109 11194 I jxcore-log: 
,03-21 15:50:59.351 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:50:59.351 11109 11194 I jxcore-log: 
,03-21 15:50:59.356 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 57509
03-21 15:50:59.356 11109 11194 I jxcore-log: 
,03-21 15:50:59.371 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:50:59.371 11109 11194 I jxcore-log: 
,03-21 15:50:59.371 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:50:59.371 11109 11194 I jxcore-log: 
,03-21 15:50:59.376 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:50:59.376 11109 11194 I jxcore-log: 
,03-21 15:50:59.406 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:50:59.406 11109 11194 I jxcore-log: 
,03-21 15:50:59.411 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:50:59.411 11109 11194 I jxcore-log: 
,03-21 15:50:59.416 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:50:59.416 11109 11194 I jxcore-log: 
,03-21 15:50:59.421 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:50:59.421 11109 11194 I jxcore-log: 
,03-21 15:50:59.461 11109 11194 I jxcore-log: ok 7 Send/recvd #1 should be equal length
03-21 15:50:59.461 11109 11194 I jxcore-log: 
,03-21 15:50:59.461 11109 11194 I jxcore-log: ok 8 Send/recvd #1 should be same
03-21 15:50:59.461 11109 11194 I jxcore-log: 
,03-21 15:50:59.466 11109 11194 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-21 15:50:59.466 11109 11194 I jxcore-log: 
,03-21 15:50:59.466 11109 11194 I jxcore-log: ok 10 Send/recvd #2 should be same
03-21 15:50:59.466 11109 11194 I jxcore-log: 
,03-21 15:50:59.471 11109 11194 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-21 15:50:59.471 11109 11194 I jxcore-log: 
,03-21 15:50:59.481 11109 11194 I jxcore-log: # setup
03-21 15:50:59.481 11109 11194 I jxcore-log: 
,03-21 15:50:59.691 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:50:59.691 11109 11194 I jxcore-log: 
,03-21 15:50:59.701 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:50:59.701 11109 11194 I jxcore-log: 
,03-21 15:50:59.706 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:50:59.706 11109 11194 I jxcore-log: 
,03-21 15:50:59.716 11109 11194 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-21 15:50:59.716 11109 11194 I jxcore-log: 
,03-21 15:50:59.721 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:50:59.721 11109 11194 I jxcore-log: 
,03-21 15:50:59.916 11109 11194 I jxcore-log: # teardown
03-21 15:50:59.916 11109 11194 I jxcore-log: 
,03-21 15:50:59.996  3424  3618 V AlarmManager: waitForAlarm result :8
,03-21 15:51:00.096 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:00.096 11109 11194 I jxcore-log: 
,03-21 15:51:00.106 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 44993
03-21 15:51:00.106 11109 11194 I jxcore-log: 
,03-21 15:51:00.116 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:00.116 11109 11194 I jxcore-log: 
,03-21 15:51:00.121 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:00.121 11109 11194 I jxcore-log: 
,03-21 15:51:00.126 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:00.126 11109 11194 I jxcore-log: 
,03-21 15:51:00.141 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:00.141 11109 11194 I jxcore-log: 
,03-21 15:51:00.146 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:00.146 11109 11194 I jxcore-log: 
,03-21 15:51:00.161 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:00.161 11109 11194 I jxcore-log: 
,03-21 15:51:00.181 11109 11194 I jxcore-log: ok 12 socket shouldn't close until after stream
03-21 15:51:00.181 11109 11194 I jxcore-log: 
,03-21 15:51:00.181 11109 11194 I jxcore-log: ok 13 incoming remains open
03-21 15:51:00.181 11109 11194 I jxcore-log: 
,03-21 15:51:00.191 11109 11194 I jxcore-log: # setup
03-21 15:51:00.191 11109 11194 I jxcore-log: 
,03-21 15:51:00.381 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:00.381 11109 11194 I jxcore-log: 
,03-21 15:51:00.391 11109 11194 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-21 15:51:00.391 11109 11194 I jxcore-log: 
,03-21 15:51:00.396 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:00.396 11109 11194 I jxcore-log: 
,03-21 15:51:00.571 11109 11194 I jxcore-log: # teardown
03-21 15:51:00.571 11109 11194 I jxcore-log: 
,03-21 15:51:00.676 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:00.676 11109 11194 I jxcore-log: 
,03-21 15:51:00.686 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 53464
03-21 15:51:00.686 11109 11194 I jxcore-log: 
,03-21 15:51:00.696 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:00.696 11109 11194 I jxcore-log: 
,03-21 15:51:00.701 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:00.701 11109 11194 I jxcore-log: 
,03-21 15:51:00.706 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:00.706 11109 11194 I jxcore-log: 
,03-21 15:51:00.721 11109 11194 I jxcore-log: ok 14 we should not have gotten an error
03-21 15:51:00.721 11109 11194 I jxcore-log: 
,03-21 15:51:00.726 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:00.726 11109 11194 I jxcore-log: 
,03-21 15:51:00.736 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:00.736 11109 11194 I jxcore-log: 
,03-21 15:51:00.746 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:00.746 11109 11194 I jxcore-log: 
,03-21 15:51:00.756 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:00.756 11109 11194 I jxcore-log: 
,03-21 15:51:00.761 11109 11194 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-21 15:51:00.761 11109 11194 I jxcore-log: 
,03-21 15:51:00.766 11109 11194 I jxcore-log: ok 16 incoming is cleaned up
03-21 15:51:00.766 11109 11194 I jxcore-log: 
,03-21 15:51:00.771 11109 11194 I jxcore-log: # setup
03-21 15:51:00.771 11109 11194 I jxcore-log: 
,03-21 15:51:00.876 11109 11194 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-21 15:51:00.876 11109 11194 I jxcore-log: 
,03-21 15:51:00.971 11109 11194 I jxcore-log: # teardown
03-21 15:51:00.971 11109 11194 I jxcore-log: 
,03-21 15:51:01.061 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server,
03-21 15:51:01.061 11109 11194 I jxcore-log: 
,03-21 15:51:01.071 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 49361
03-21 15:51:01.071 11109 11194 I jxcore-log: 
,03-21 15:51:01.081 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.081 11109 11194 I jxcore-log: 
,03-21 15:51:01.086 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.086 11109 11194 I jxcore-log: 
,03-21 15:51:01.091 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.091 11109 11194 I jxcore-log: 
,03-21 15:51:01.106 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:01.106 11109 11194 I jxcore-log: 
,03-21 15:51:01.111 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:01.111 11109 11194 I jxcore-log: 
,03-21 15:51:01.126 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:01.126 11109 11194 I jxcore-log: 
,03-21 15:51:01.141 11109 11194 I jxcore-log: ok 17 stream was closed
03-21 15:51:01.141 11109 11194 I jxcore-log: 
,03-21 15:51:01.141 11109 11194 I jxcore-log: ok 18 incoming should survive
03-21 15:51:01.141 11109 11194 I jxcore-log: 
,03-21 15:51:01.146 11109 11194 I jxcore-log: ok 19 mux should have no streams
03-21 15:51:01.146 11109 11194 I jxcore-log: 
,03-21 15:51:01.151 11109 11194 I jxcore-log: # setup
03-21 15:51:01.151 11109 11194 I jxcore-log: 
,03-21 15:51:01.196 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:01.196 11109 11194 I jxcore-log: 
,03-21 15:51:01.201 11109 11194 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-21 15:51:01.201 11109 11194 I jxcore-log: 
,03-21 15:51:01.201 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:01.201 11109 11194 I jxcore-log: 
,03-21 15:51:01.316 11109 11194 I jxcore-log: # teardown
03-21 15:51:01.316 11109 11194 I jxcore-log: 
,03-21 15:51:01.426 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:01.426 11109 11194 I jxcore-log: 
,03-21 15:51:01.436 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 58738
03-21 15:51:01.436 11109 11194 I jxcore-log: 
,03-21 15:51:01.446 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.446 11109 11194 I jxcore-log: 
,03-21 15:51:01.446 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.446 11109 11194 I jxcore-log: 
,03-21 15:51:01.451 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.451 11109 11194 I jxcore-log: 
,03-21 15:51:01.461 11109 11194 I jxcore-log: ok 20 we should not have gotten an error
03-21 15:51:01.461 11109 11194 I jxcore-log: 
,03-21 15:51:01.471 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:01.471 11109 11194 I jxcore-log: 
,03-21 15:51:01.476 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:01.476 11109 11194 I jxcore-log: 
,03-21 15:51:01.486 11109 11194 I jxcore-log: ok 21 Buffers are identical
03-21 15:51:01.486 11109 11194 I jxcore-log: 
,03-21 15:51:01.491 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:01.491 11109 11194 I jxcore-log: 
,03-21 15:51:01.496 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:01.496 11109 11194 I jxcore-log: 
,03-21 15:51:01.506 11109 11194 I jxcore-log: ok 22 native server is nulled out
03-21 15:51:01.506 11109 11194 I jxcore-log: 
,03-21 15:51:01.506 11109 11194 I jxcore-log: ok 23 native server should be closed
03-21 15:51:01.506 11109 11194 I jxcore-log: 
,03-21 15:51:01.506 11109 11194 I jxcore-log: ok 24 incoming has been removed
03-21 15:51:01.506 11109 11194 I jxcore-log: 
,03-21 15:51:01.506 11109 11194 I jxcore-log: ok 25 Incoming should be done
03-21 15:51:01.506 11109 11194 I jxcore-log: 
03-21 15:51:01.506 11109 11194 I jxcore-log: ok 26 The mux object should be closed
03-21 15:51:01.506 11109 11194 I jxcore-log: 
,03-21 15:51:01.511 11109 11194 I jxcore-log: ok 27 The mux stream should be closed
03-21 15:51:01.511 11109 11194 I jxcore-log: 
,03-21 15:51:01.511 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:01.511 11109 11194 I jxcore-log: 
,03-21 15:51:01.531 11109 11194 I jxcore-log: # setup
03-21 15:51:01.531 11109 11194 I jxcore-log: 
,03-21 15:51:01.646 11109 11194 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-21 15:51:01.646 11109 11194 I jxcore-log: 
,03-21 15:51:01.771 11109 11194 I jxcore-log: # teardown
03-21 15:51:01.771 11109 11194 I jxcore-log: 
,03-21 15:51:01.871 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:01.871 11109 11194 I jxcore-log: 
,03-21 15:51:01.876 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 55005
03-21 15:51:01.876 11109 11194 I jxcore-log: 
,03-21 15:51:01.911 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.911 11109 11194 I jxcore-log: 
,03-21 15:51:01.911 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.911 11109 11194 I jxcore-log: 
,03-21 15:51:01.916 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.916 11109 11194 I jxcore-log: 
,03-21 15:51:01.916 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.916 11109 11194 I jxcore-log: 
,03-21 15:51:01.921 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.921 11109 11194 I jxcore-log: 
,03-21 15:51:01.921 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.921 11109 11194 I jxcore-log: 
,03-21 15:51:01.926 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.926 11109 11194 I jxcore-log: 
,03-21 15:51:01.931 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.931 11109 11194 I jxcore-log: 
,03-21 15:51:01.931 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.931 11109 11194 I jxcore-log: 
,03-21 15:51:01.941 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.941 11109 11194 I jxcore-log: 
,03-21 15:51:01.941 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.941 11109 11194 I jxcore-log: 
,03-21 15:51:01.941 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.941 11109 11194 I jxcore-log: 
,03-21 15:51:01.946 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.946 11109 11194 I jxcore-log: 
,03-21 15:51:01.946 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.946 11109 11194 I jxcore-log: 
,03-21 15:51:01.951 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.951 11109 11194 I jxcore-log: 
,03-21 15:51:01.951 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.951 11109 11194 I jxcore-log: 
,03-21 15:51:01.951 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.951 11109 11194 I jxcore-log: 
,03-21 15:51:01.956 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.956 11109 11194 I jxcore-log: 
,03-21 15:51:01.956 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.956 11109 11194 I jxcore-log: 
,03-21 15:51:01.961 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.961 11109 11194 I jxcore-log: 
,03-21 15:51:01.961 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.961 11109 11194 I jxcore-log: 
,03-21 15:51:01.966 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.966 11109 11194 I jxcore-log: 
,03-21 15:51:01.966 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.966 11109 11194 I jxcore-log: 
,03-21 15:51:01.966 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.966 11109 11194 I jxcore-log: 
,03-21 15:51:01.971 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.971 11109 11194 I jxcore-log: 
,03-21 15:51:01.971 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.971 11109 11194 I jxcore-log: 
,03-21 15:51:01.971 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.971 11109 11194 I jxcore-log: 
,03-21 15:51:01.976 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:01.976 11109 11194 I jxcore-log: 
,03-21 15:51:01.976 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:01.976 11109 11194 I jxcore-log: 
,03-21 15:51:01.981 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:01.981 11109 11194 I jxcore-log: 
,03-21 15:51:02.106 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.106 11109 11194 I jxcore-log: 
,03-21 15:51:02.106 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.106 11109 11194 I jxcore-log: 
,03-21 15:51:02.111 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.111 11109 11194 I jxcore-log: 
,03-21 15:51:02.111 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.111 11109 11194 I jxcore-log: 
,03-21 15:51:02.111 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.111 11109 11194 I jxcore-log: 
,03-21 15:51:02.116 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.116 11109 11194 I jxcore-log: 
,03-21 15:51:02.116 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.116 11109 11194 I jxcore-log: 
,03-21 15:51:02.116 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.116 11109 11194 I jxcore-log: 
,03-21 15:51:02.116 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.116 11109 11194 I jxcore-log: 
,03-21 15:51:02.121 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.121 11109 11194 I jxcore-log: 
,03-21 15:51:02.121 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.121 11109 11194 I jxcore-log: 
,03-21 15:51:02.126 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.126 11109 11194 I jxcore-log: 
,03-21 15:51:02.126 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.126 11109 11194 I jxcore-log: 
,03-21 15:51:02.126 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.126 11109 11194 I jxcore-log: 
,03-21 15:51:02.126 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.126 11109 11194 I jxcore-log: 
,03-21 15:51:02.131 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.131 11109 11194 I jxcore-log: 
,03-21 15:51:02.131 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.131 11109 11194 I jxcore-log: 
,03-21 15:51:02.136 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.136 11109 11194 I jxcore-log: 
,03-21 15:51:02.136 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.136 11109 11194 I jxcore-log: 
,03-21 15:51:02.136 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.136 11109 11194 I jxcore-log: 
,03-21 15:51:02.136 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.136 11109 11194 I jxcore-log: 
,03-21 15:51:02.141 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.141 11109 11194 I jxcore-log: 
,03-21 15:51:02.141 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.141 11109 11194 I jxcore-log: 
,03-21 15:51:02.146 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.146 11109 11194 I jxcore-log: 
,03-21 15:51:02.146 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.146 11109 11194 I jxcore-log: 
,03-21 15:51:02.146 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-21 15:51:02.146 11109 11194 I jxcore-log: 
03-21 15:51:02.151 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.151 11109 11194 I jxcore-log: 
,03-21 15:51:02.151 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.151 11109 11194 I jxcore-log: 
,03-21 15:51:02.151 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.151 11109 11194 I jxcore-log: 
,03-21 15:51:02.151 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.151 11109 11194 I jxcore-log: 
,03-21 15:51:02.156 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.156 11109 11194 I jxcore-log: 
,03-21 15:51:02.156 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.156 11109 11194 I jxcore-log: 
,03-21 15:51:02.156 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.156 11109 11194 I jxcore-log: 
,03-21 15:51:02.161 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.161 11109 11194 I jxcore-log: 
,03-21 15:51:02.161 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.161 11109 11194 I jxcore-log: 
,03-21 15:51:02.161 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.161 11109 11194 I jxcore-log: 
,03-21 15:51:02.161 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.161 11109 11194 I jxcore-log: 
,03-21 15:51:02.166 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.166 11109 11194 I jxcore-log: 
,03-21 15:51:02.166 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.166 11109 11194 I jxcore-log: 
,03-21 15:51:02.166 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.166 11109 11194 I jxcore-log: 
,03-21 15:51:02.171 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.171 11109 11194 I jxcore-log: 
,03-21 15:51:02.171 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.171 11109 11194 I jxcore-log: 
,03-21 15:51:02.171 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.171 11109 11194 I jxcore-log: 
,03-21 15:51:02.176 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.176 11109 11194 I jxcore-log: 
,03-21 15:51:02.176 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.176 11109 11194 I jxcore-log: 
,03-21 15:51:02.176 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.176 11109 11194 I jxcore-log: 
,03-21 15:51:02.176 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.176 11109 11194 I jxcore-log: 
,03-21 15:51:02.181 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.181 11109 11194 I jxcore-log: 
,03-21 15:51:02.186 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.186 11109 11194 I jxcore-log: 
,03-21 15:51:02.191 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.191 11109 11194 I jxcore-log: 
,03-21 15:51:02.191 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.191 11109 11194 I jxcore-log: 
,03-21 15:51:02.191 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.191 11109 11194 I jxcore-log: 
,03-21 15:51:02.191 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.191 11109 11194 I jxcore-log: 
,03-21 15:51:02.196 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.196 11109 11194 I jxcore-log: 
,03-21 15:51:02.196 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.196 11109 11194 I jxcore-log: 
,03-21 15:51:02.196 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.196 11109 11194 I jxcore-log: 
,03-21 15:51:02.201 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.201 11109 11194 I jxcore-log: 
,03-21 15:51:02.201 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.201 11109 11194 I jxcore-log: 
,03-21 15:51:02.201 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.201 11109 11194 I jxcore-log: 
,03-21 15:51:02.206 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.206 11109 11194 I jxcore-log: 
,03-21 15:51:02.206 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.206 11109 11194 I jxcore-log: 
,03-21 15:51:02.206 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.206 11109 11194 I jxcore-log: 
,03-21 15:51:02.206 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.206 11109 11194 I jxcore-log: 
,03-21 15:51:02.211 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.211 11109 11194 I jxcore-log: 
,03-21 15:51:02.211 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.211 11109 11194 I jxcore-log: 
,03-21 15:51:02.211 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.211 11109 11194 I jxcore-log: 
,03-21 15:51:02.211 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.211 11109 11194 I jxcore-log: 
,03-21 15:51:02.216 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.216 11109 11194 I jxcore-log: 
,03-21 15:51:02.216 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.216 11109 11194 I jxcore-log: 
,03-21 15:51:02.216 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.216 11109 11194 I jxcore-log: 
,03-21 15:51:02.216 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.216 11109 11194 I jxcore-log: 
,03-21 15:51:02.216 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.216 11109 11194 I jxcore-log: 
,03-21 15:51:02.221 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-21 15:51:02.221 11109 11194 I jxcore-log: 
,03-21 15:51:02.221 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.221 11109 11194 I jxcore-log: 
,03-21 15:51:02.221 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.221 11109 11194 I jxcore-log: 
,03-21 15:51:02.221 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.221 11109 11194 I jxcore-log: 
,03-21 15:51:02.221 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-21 15:51:02.221 11109 11194 I jxcore-log: 
,03-21 15:51:02.226 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.226 11109 11194 I jxcore-log: 
,03-21 15:51:02.226 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.226 11109 11194 I jxcore-log: 
,03-21 15:51:02.231 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:02.231 11109 11194 I jxcore-log: 
,03-21 15:51:02.291 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.291 11109 11194 I jxcore-log: 
,03-21 15:51:02.291 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.291 11109 11194 I jxcore-log: 
,03-21 15:51:02.291 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.291 11109 11194 I jxcore-log: 
,03-21 15:51:02.291 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.291 11109 11194 I jxcore-log: 
,03-21 15:51:02.291 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.291 11109 11194 I jxcore-log: 
,03-21 15:51:02.296 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.296 11109 11194 I jxcore-log: 
03-21 15:51:02.296 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.296 11109 11194 I jxcore-log: 
,03-21 15:51:02.296 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.296 11109 11194 I jxcore-log: 
03-21 15:51:02.296 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.296 11109 11194 I jxcore-log: 
,03-21 15:51:02.296 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.296 11109 11194 I jxcore-log: 
,03-21 15:51:02.301 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.301 11109 11194 I jxcore-log: 
,03-21 15:51:02.301 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.301 11109 11194 I jxcore-log: 
03-21 15:51:02.301 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.301 11109 11194 I jxcore-log: 
,03-21 15:51:02.301 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.301 11109 11194 I jxcore-log: 
,03-21 15:51:02.301 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.301 11109 11194 I jxcore-log: 
,03-21 15:51:02.301 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.301 11109 11194 I jxcore-log: 
03-21 15:51:02.301 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.301 11109 11194 I jxcore-log: 
,03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.306 11109 11194 I jxcore-log: 
03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.306 11109 11194 I jxcore-log: 
,03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.306 11109 11194 I jxcore-log: 
03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.306 11109 11194 I jxcore-log: 
,03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.306 11109 11194 I jxcore-log: 
03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.306 11109 11194 I jxcore-log: 
,03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.306 11109 11194 I jxcore-log: 
,03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.306 11109 11194 I jxcore-log: 
,03-21 15:51:02.306 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.306 11109 11194 I jxcore-log: 
03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.311 11109 11194 I jxcore-log: 
,03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.311 11109 11194 I jxcore-log: 
03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.311 11109 11194 I jxcore-log: 
,03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.311 11109 11194 I jxcore-log: 
,03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.311 11109 11194 I jxcore-log: 
03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.311 11109 11194 I jxcore-log: 
,03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.311 11109 11194 I jxcore-log: 
03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.311 11109 11194 I jxcore-log: 
,03-21 15:51:02.311 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.311 11109 11194 I jxcore-log: 
,03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
,03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
,03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
,03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.316 11109 11194 I jxcore-log: 
03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
,03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
,03-21 15:51:02.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.316 11109 11194 I jxcore-log: 
,03-21 15:51:02.321 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.321 11109 11194 I jxcore-log: 
03-21 15:51:02.321 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.321 11109 11194 I jxcore-log: 
03-21 15:51:02.321 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.321 11109 11194 I jxcore-log: 
,03-21 15:51:02.321 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.321 11109 11194 I jxcore-log: 
03-21 15:51:02.321 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.321 11109 11194 I jxcore-log: 
,03-21 15:51:02.321 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.321 11109 11194 I jxcore-log: 
,03-21 15:51:02.321 11109 11194 I jxcore-log: ok 28 native server is nulled out
03-21 15:51:02.321 11109 11194 I jxcore-log: 
,03-21 15:51:02.321 11109 11194 I jxcore-log: ok 29 native server should be closed
03-21 15:51:02.321 11109 11194 I jxcore-log: 
03-21 15:51:02.326 11109 11194 I jxcore-log: ok 30 incoming has been removed
03-21 15:51:02.326 11109 11194 I jxcore-log: 
03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
,03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
,03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
,03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
,03-21 15:51:02.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.326 11109 11194 I jxcore-log: 
,03-21 15:51:02.411 11109 11194 I jxcore-log: # setup
03-21 15:51:02.411 11109 11194 I jxcore-log: 
,03-21 15:51:02.556 11109 11194 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-21 15:51:02.556 11109 11194 I jxcore-log: 
,03-21 15:51:02.741 11109 11194 I jxcore-log: # teardown
03-21 15:51:02.741 11109 11194 I jxcore-log: 
,03-21 15:51:02.841 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:02.841 11109 11194 I jxcore-log: 
,03-21 15:51:02.841 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 42301
03-21 15:51:02.841 11109 11194 I jxcore-log: 
,03-21 15:51:02.851 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:02.851 11109 11194 I jxcore-log: 
,03-21 15:51:02.851 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:02.851 11109 11194 I jxcore-log: 
,03-21 15:51:02.856 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:02.856 11109 11194 I jxcore-log: 
,03-21 15:51:02.871 11109 11194 I jxcore-log: ok 31 we should not have gotten an error
03-21 15:51:02.871 11109 11194 I jxcore-log: 
,03-21 15:51:02.876 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:02.876 11109 11194 I jxcore-log: 
,03-21 15:51:02.881 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket,
03-21 15:51:02.881 11109 11194 I jxcore-log: 
,03-21 15:51:02.896 11109 11194 I jxcore-log: ok 32 Buffers are identical
03-21 15:51:02.896 11109 11194 I jxcore-log: 
,03-21 15:51:02.896 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:02.896 11109 11194 I jxcore-log: 
,03-21 15:51:02.901 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:02.901 11109 11194 I jxcore-log: 
,03-21 15:51:02.926 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:02.926 11109 11194 I jxcore-log: 
,03-21 15:51:02.926 11109 11194 I jxcore-log: ok 33 server should be fine
03-21 15:51:02.926 11109 11194 I jxcore-log: 
,03-21 15:51:02.926 11109 11194 I jxcore-log: ok 34 server should be open
03-21 15:51:02.926 11109 11194 I jxcore-log: 
,03-21 15:51:02.931 11109 11194 I jxcore-log: ok 35 incoming has been removed
03-21 15:51:02.931 11109 11194 I jxcore-log: 
,03-21 15:51:02.931 11109 11194 I jxcore-log: ok 36 The mux object should be closed
03-21 15:51:02.931 11109 11194 I jxcore-log: 
,03-21 15:51:02.931 11109 11194 I jxcore-log: ok 37 The mux stream should be closed
03-21 15:51:02.931 11109 11194 I jxcore-log: 
,03-21 15:51:02.941 11109 11194 I jxcore-log: # setup
03-21 15:51:02.941 11109 11194 I jxcore-log: 
,03-21 15:51:03.031 11109 11194 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-21 15:51:03.031 11109 11194 I jxcore-log: 
,03-21 15:51:03.146 11109 11194 I jxcore-log: # teardown
03-21 15:51:03.146 11109 11194 I jxcore-log: 
,03-21 15:51:03.261 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:03.261 11109 11194 I jxcore-log: 
,03-21 15:51:03.271 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 46639
03-21 15:51:03.271 11109 11194 I jxcore-log: 
,03-21 15:51:03.281 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:03.281 11109 11194 I jxcore-log: 
,03-21 15:51:03.281 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:03.281 11109 11194 I jxcore-log: 
,03-21 15:51:03.286 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:03.286 11109 11194 I jxcore-log: 
,03-21 15:51:03.296 11109 11194 I jxcore-log: ok 38 we should not have gotten an error
03-21 15:51:03.296 11109 11194 I jxcore-log: 
,03-21 15:51:03.301 11109 11194 I jxcore-log: DEBUG createNativeListener: new stream: 
03-21 15:51:03.301 11109 11194 I jxcore-log: 
,03-21 15:51:03.301 11109 11194 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-21 15:51:03.301 11109 11194 I jxcore-log: 
,03-21 15:51:03.311 11109 11194 I jxcore-log: ok 39 Buffers are identical
03-21 15:51:03.311 11109 11194 I jxcore-log: 
,03-21 15:51:03.316 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-21 15:51:03.316 11109 11194 I jxcore-log: 
,03-21 15:51:03.316 11109 11194 I jxcore-log: DEBUG createNativeListener: stream close:
03-21 15:51:03.316 11109 11194 I jxcore-log: 
,03-21 15:51:03.321 11109 11194 I jxcore-log: DEBUG createNativeListener: mux close
03-21 15:51:03.321 11109 11194 I jxcore-log: 
,03-21 15:51:03.326 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:03.326 11109 11194 I jxcore-log: 
,03-21 15:51:03.326 11109 11194 I jxcore-log: ok 40 server should be fine
03-21 15:51:03.326 11109 11194 I jxcore-log: 
,03-21 15:51:03.326 11109 11194 I jxcore-log: ok 41 server should be open
03-21 15:51:03.326 11109 11194 I jxcore-log: 
,03-21 15:51:03.331 11109 11194 I jxcore-log: ok 42 incoming has been removed
03-21 15:51:03.331 11109 11194 I jxcore-log: 
03-21 15:51:03.331 11109 11194 I jxcore-log: ok 43 The mux object should be closed
03-21 15:51:03.331 11109 11194 I jxcore-log: 
,03-21 15:51:03.331 11109 11194 I jxcore-log: ok 44 The mux stream should be closed
03-21 15:51:03.331 11109 11194 I jxcore-log: 
,03-21 15:51:03.341 11109 11194 I jxcore-log: # setup
03-21 15:51:03.341 11109 11194 I jxcore-log: 
,03-21 15:51:03.426 11109 11194 I jxcore-log: # 12. closeAll can close even when connections open
03-21 15:51:03.426 11109 11194 I jxcore-log: 
,03-21 15:51:03.526 11109 11194 I jxcore-log: # teardown
03-21 15:51:03.526 11109 11194 I jxcore-log: 
,03-21 15:51:03.706 11109 11194 I jxcore-log: ok 45 not possible to connect to the server anymore
03-21 15:51:03.706 11109 11194 I jxcore-log: 
,03-21 15:51:03.711 11109 11194 I jxcore-log: # setup
03-21 15:51:03.711 11109 11194 I jxcore-log: 
,03-21 15:51:03.826 11109 11194 I jxcore-log: # 13. closeAll with promise
03-21 15:51:03.826 11109 11194 I jxcore-log: 
,03-21 15:51:03.906 11109 11194 I jxcore-log: # teardown
03-21 15:51:03.906 11109 11194 I jxcore-log: 
,03-21 15:51:04.021 11109 11194 I jxcore-log: ok 46 not possible to connect to the server anymore
03-21 15:51:04.021 11109 11194 I jxcore-log: 
,03-21 15:51:04.031 11109 11194 I jxcore-log: # setup
03-21 15:51:04.031 11109 11194 I jxcore-log: 
,03-21 15:51:04.046  3424  3733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 15:51:04.051  3424  3733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 15:51:04.051  3424  3733 D BatteryService: online:4, current avg:-42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
03-21 15:51:04.051  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 15:51:04.051  3424  3733 D BatteryService: stay LED for fully charged
,03-21 15:51:04.051  3424  3424 I MotionRecognitionService: Plugged
03-21 15:51:04.056  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-21 15:51:04.056  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 15:51:04.056  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-21 15:51:04.061  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:04.061  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:04.061  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 15:51:04.076  5859  5859 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 15:51:04.076  5859  5956 D HeadsetStateMachine: Disconnected process message: 10
,03-21 15:51:04.086 11109 11194 I jxcore-log: # 14. multiplex can send data
03-21 15:51:04.086 11109 11194 I jxcore-log: 
,03-21 15:51:04.086  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 15:51:04.091  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:04.091  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:04.091  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 15:51:04.231 11109 11194 I jxcore-log: # teardown
03-21 15:51:04.231 11109 11194 I jxcore-log: 
,03-21 15:51:04.361 11109 11194 I jxcore-log: ok 47 String should be length:200
03-21 15:51:04.361 11109 11194 I jxcore-log: 
,03-21 15:51:04.371 11109 11194 I jxcore-log: # setup
03-21 15:51:04.371 11109 11194 I jxcore-log: 
,03-21 15:51:04.451 11109 11194 I jxcore-log: # 15. enqueue and run in order
03-21 15:51:04.451 11109 11194 I jxcore-log: 
,03-21 15:51:04.561 11109 11194 I jxcore-log: # teardown,
03-21 15:51:04.561 11109 11194 I jxcore-log: 
,03-21 15:51:04.776 11109 11194 I jxcore-log: ok 48 firstPromise setTimeout
03-21 15:51:04.776 11109 11194 I jxcore-log: 
,03-21 15:51:04.786 11109 11194 I jxcore-log: ok 49 firstPromise result
03-21 15:51:04.786 11109 11194 I jxcore-log: 
,03-21 15:51:04.791 11109 11194 I jxcore-log: ok 50 firstPromise testValue
03-21 15:51:04.791 11109 11194 I jxcore-log: 
,03-21 15:51:04.816  3424  3585 I PowerManagerService: [PWL] Off : 140s ago
,03-21 15:51:04.896 11109 11194 I jxcore-log: ok 51 secondPromise setTimeout
03-21 15:51:04.896 11109 11194 I jxcore-log: 
,03-21 15:51:04.911 11109 11194 I jxcore-log: ok 52 secondPromise result
03-21 15:51:04.911 11109 11194 I jxcore-log: 
,03-21 15:51:04.916 11109 11194 I jxcore-log: ok 53 secondPromise testValue
03-21 15:51:04.916 11109 11194 I jxcore-log: 
,03-21 15:51:04.921 11109 11194 I jxcore-log: ok 54 thirdPromise in promise
03-21 15:51:04.921 11109 11194 I jxcore-log: 
,03-21 15:51:04.931 11109 11194 I jxcore-log: ok 55 thirdPromise result
03-21 15:51:04.931 11109 11194 I jxcore-log: 
,03-21 15:51:04.931 11109 11194 I jxcore-log: ok 56 thirdPromise testValue
03-21 15:51:04.931 11109 11194 I jxcore-log: 
,03-21 15:51:04.946 11109 11194 I jxcore-log: # setup
03-21 15:51:04.946 11109 11194 I jxcore-log: 
,03-21 15:51:05.106 11109 11194 I jxcore-log: # 16. enqueueAtTop and run backwards
03-21 15:51:05.106 11109 11194 I jxcore-log: 
,03-21 15:51:05.171  3424  6046 D SSRM:n  : SIOP:: AP = 300, PST = 280 (W:10), CUR = -42, LCD = 0
,03-21 15:51:05.201 11109 11194 I jxcore-log: # teardown
03-21 15:51:05.201 11109 11194 I jxcore-log: 
,03-21 15:51:05.311 11109 11194 I jxcore-log: ok 57 thirdPromise - first to run
03-21 15:51:05.311 11109 11194 I jxcore-log: 
,03-21 15:51:05.311 11109 11194 I jxcore-log: ok 58 thirdPromise - in resolve
03-21 15:51:05.311 11109 11194 I jxcore-log: 
,03-21 15:51:05.316 11109 11194 I jxcore-log: ok 59 secondPromise - second to run
03-21 15:51:05.316 11109 11194 I jxcore-log: 
,03-21 15:51:05.321 11109 11194 I jxcore-log: ok 60 secondPromise - in catch
03-21 15:51:05.321 11109 11194 I jxcore-log: 
,03-21 15:51:05.321 11109 11194 I jxcore-log: ok 61 firstPromise - third to run
03-21 15:51:05.321 11109 11194 I jxcore-log: 
,03-21 15:51:05.326 11109 11194 I jxcore-log: ok 62 firstPromise - in then
03-21 15:51:05.326 11109 11194 I jxcore-log: 
,03-21 15:51:05.326 11109 11194 I jxcore-log: ok 63 testing promises
03-21 15:51:05.326 11109 11194 I jxcore-log: 
,03-21 15:51:05.331 11109 11194 I jxcore-log: # setup
03-21 15:51:05.331 11109 11194 I jxcore-log: 
,03-21 15:51:05.481 11109 11194 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-21 15:51:05.481 11109 11194 I jxcore-log: 
,03-21 15:51:05.551 11109 11194 I jxcore-log: # teardown
03-21 15:51:05.551 11109 11194 I jxcore-log: 
,03-21 15:51:05.731 11109 11194 I jxcore-log: ok 64 fourth
03-21 15:51:05.731 11109 11194 I jxcore-log: 
,03-21 15:51:05.736 11109 11194 I jxcore-log: ok 65 fourth
03-21 15:51:05.736 11109 11194 I jxcore-log: 
,03-21 15:51:05.741 11109 11194 I jxcore-log: ok 66 second
03-21 15:51:05.741 11109 11194 I jxcore-log: 
,03-21 15:51:05.741 11109 11194 I jxcore-log: ok 67 secondPromise - in then
03-21 15:51:05.741 11109 11194 I jxcore-log: 
,03-21 15:51:05.851 11109 11194 I jxcore-log: ok 68 first
03-21 15:51:05.851 11109 11194 I jxcore-log: 
,03-21 15:51:05.861 11109 11194 I jxcore-log: ok 69 firstPromise - in catch
03-21 15:51:05.861 11109 11194 I jxcore-log: 
,03-21 15:51:05.866 11109 11194 I jxcore-log: ok 70 third
03-21 15:51:05.866 11109 11194 I jxcore-log: 
,03-21 15:51:05.871 11109 11194 I jxcore-log: ok 71 thirdPromise - in then
03-21 15:51:05.871 11109 11194 I jxcore-log: 
,03-21 15:51:05.876 11109 11194 I jxcore-log: ok 72 testingPromises
03-21 15:51:05.876 11109 11194 I jxcore-log: 
,03-21 15:51:05.881 11109 11194 I jxcore-log: # setup
03-21 15:51:05.881 11109 11194 I jxcore-log: 
,03-21 15:51:05.956 11109 11194 I jxcore-log: # 18. queues handled independently
03-21 15:51:05.956 11109 11194 I jxcore-log: 
,03-21 15:51:06.131 11109 11194 I jxcore-log: # teardown
03-21 15:51:06.131 11109 11194 I jxcore-log: 
,03-21 15:51:06.326 11109 11194 I jxcore-log: ok 73 all short operations completed before the long resolves
03-21 15:51:06.326 11109 11194 I jxcore-log: 
,03-21 15:51:06.336 11109 11194 I jxcore-log: # setup
03-21 15:51:06.336 11109 11194 I jxcore-log: 
,03-21 15:51:06.406 11109 11194 I jxcore-log: # 19. basic
03-21 15:51:06.406 11109 11194 I jxcore-log: 
,03-21 15:51:06.491 11109 11194 I jxcore-log: # teardown
03-21 15:51:06.491 11109 11194 I jxcore-log: 
,03-21 15:51:06.606 11109 11194 I jxcore-log: ok 74 sane
03-21 15:51:06.606 11109 11194 I jxcore-log: 
,03-21 15:51:06.611 11109 11194 I jxcore-log: # setup
03-21 15:51:06.611 11109 11194 I jxcore-log: 
,03-21 15:51:06.671 11109 11194 I jxcore-log: # 20. another
03-21 15:51:06.671 11109 11194 I jxcore-log: 
,03-21 15:51:06.761 11109 11194 I jxcore-log: # teardown
03-21 15:51:06.761 11109 11194 I jxcore-log: 
,03-21 15:51:06.866 11109 11194 I jxcore-log: ok 75 sane
03-21 15:51:06.866 11109 11194 I jxcore-log: 
,03-21 15:51:06.871 11109 11194 I jxcore-log: # setup
03-21 15:51:06.871 11109 11194 I jxcore-log: 
,03-21 15:51:07.061 11109 11194 I jxcore-log: # 21. #startListeningForAdvertisements should fail if start not called
03-21 15:51:07.061 11109 11194 I jxcore-log: 
,03-21 15:51:07.161 11109 11194 I jxcore-log: # teardown
03-21 15:51:07.161 11109 11194 I jxcore-log: 
,03-21 15:51:07.311 11109 11194 I jxcore-log: ok 76 specific error should be returned
03-21 15:51:07.311 11109 11194 I jxcore-log: 
,03-21 15:51:07.316 11109 11194 I jxcore-log: # setup
03-21 15:51:07.316 11109 11194 I jxcore-log: 
,03-21 15:51:07.451 11109 11194 I jxcore-log: ok 77 error should be null
03-21 15:51:07.451 11109 11194 I jxcore-log: 
,03-21 15:51:07.456 11109 11194 I jxcore-log: ok 78 error should be null
03-21 15:51:07.456 11109 11194 I jxcore-log: 
,03-21 15:51:07.461 11109 11194 I jxcore-log: # 22. #startUpdateAdvertisingAndListening should fail if start not called
03-21 15:51:07.461 11109 11194 I jxcore-log: 
,03-21 15:51:07.546 11109 11194 I jxcore-log: # teardown
03-21 15:51:07.546 11109 11194 I jxcore-log: 
,03-21 15:51:07.646 11109 11194 I jxcore-log: ok 79 specific error should be returned
03-21 15:51:07.646 11109 11194 I jxcore-log: 
,03-21 15:51:07.656 11109 11194 I jxcore-log: # setup
03-21 15:51:07.656 11109 11194 I jxcore-log: 
,03-21 15:51:07.711 11109 11194 I jxcore-log: ok 80 error should be null
03-21 15:51:07.711 11109 11194 I jxcore-log: 
,03-21 15:51:07.716 11109 11194 I jxcore-log: ok 81 error should be null
03-21 15:51:07.716 11109 11194 I jxcore-log: 
,03-21 15:51:07.721 11109 11194 I jxcore-log: # 23. should be able to call #stopListeningForAdvertisements many times
03-21 15:51:07.721 11109 11194 I jxcore-log: 
,03-21 15:51:07.846 11109 11194 I jxcore-log: # teardown
03-21 15:51:07.846 11109 11194 I jxcore-log: 
,03-21 15:51:07.991 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:07.991 11109 11194 I jxcore-log: 
,03-21 15:51:07.996 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 35884
03-21 15:51:07.996 11109 11194 I jxcore-log: 
,03-21 15:51:08.001 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:08.001 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:08.001 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:08.011 11109 11194 I jxcore-log: ok 82 error should be null
03-21 15:51:08.011 11109 11194 I jxcore-log: 
,03-21 15:51:08.011 11109 11194 I jxcore-log: ok 83 error should be null
03-21 15:51:08.011 11109 11194 I jxcore-log: 
,03-21 15:51:08.011 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:08.011 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:08.011 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:08.016 11109 11194 I jxcore-log: ok 84 error should be null
03-21 15:51:08.016 11109 11194 I jxcore-log: 
,03-21 15:51:08.016 11109 11194 I jxcore-log: ok 85 error should be null
03-21 15:51:08.016 11109 11194 I jxcore-log: 
,03-21 15:51:08.026 11109 11194 I jxcore-log: # setup
03-21 15:51:08.026 11109 11194 I jxcore-log: 
,03-21 15:51:08.111 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:08.111 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:08.111 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:08.121 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:08.121 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:08.121 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:08.131 11109 11194 I jxcore-log: ok 86 error should be null
03-21 15:51:08.131 11109 11194 I jxcore-log: 
,03-21 15:51:08.136 11109 11194 I jxcore-log: ok 87 error should be null
03-21 15:51:08.136 11109 11194 I jxcore-log: 
,03-21 15:51:08.141 11109 11194 I jxcore-log: # 24. should be able to call #startListeningForAdvertisements many times
03-21 15:51:08.141 11109 11194 I jxcore-log: 
,03-21 15:51:08.246 11109 11194 I jxcore-log: # teardown
03-21 15:51:08.246 11109 11194 I jxcore-log: 
,03-21 15:51:08.381 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:08.381 11109 11194 I jxcore-log: 
,03-21 15:51:08.386 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 43973
03-21 15:51:08.386 11109 11194 I jxcore-log: 
,03-21 15:51:08.396 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-21 15:51:08.401 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:08.401 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 15:51:08.401 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-21 15:51:08.401 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 15:51:08.401 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:08.411 11109 11194 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:08.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:08.426 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:08.426 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:08.426 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:08.431 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:08.436  5859  5869 D BtGatt.GattService: registerClient() - UUID=881fd932-e3b7-4a75-82f4-e507fc78103f
,03-21 15:51:08.481  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=881fd932-e3b7-4a75-82f4-e507fc78103f, clientIf=6
,03-21 15:51:08.486 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:08.491  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:08.531  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 24
,03-21 15:51:08.546  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:08.546  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:08.546  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:08.551  5859  5955 D BtGatt.ScanManager: isFilteringSupported
,03-21 15:51:08.551  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:08.556  5859  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b338e6
,03-21 15:51:08.556 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:08.556 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:08.556 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:08.556 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:08.556 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:08.556 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 15:51:08.561 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,03-21 15:51:08.571 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-21 15:51:08.571 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 15:51:08.571 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-21 15:51:08.571 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:08.571 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:08.576 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:08.576  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:08.576  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:08.576  5859  5955 D BtGatt.ScanManager: allow scan with filters,
03-21 15:51:08.576  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:08.576  5859  5955 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,03-21 15:51:08.581  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:08.581  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:08.581  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan,
,03-21 15:51:08.581  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,03-21 15:51:08.586  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 15:51:08.586  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:08.591  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 15:51:08.591  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:08.601 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:08.601 11109 11194 I jxcore-log: 
,03-21 15:51:08.606 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:08.606 11109 11194 I jxcore-log: 
,03-21 15:51:08.606 11109 11194 I jxcore-log: ok 88 error should be null
03-21 15:51:08.606 11109 11194 I jxcore-log: 
,03-21 15:51:08.611 11109 11194 I jxcore-log: ok 89 error should be null
03-21 15:51:08.611 11109 11194 I jxcore-log: 
,03-21 15:51:08.616 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-21 15:51:08.616 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:08.616 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 15:51:08.616 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:08.616 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:08.621 11109 11194 I jxcore-log: ok 90 error should be null
03-21 15:51:08.621 11109 11194 I jxcore-log: 
,03-21 15:51:08.621 11109 11194 I jxcore-log: ok 91 error should be null
03-21 15:51:08.621 11109 11194 I jxcore-log: 
,03-21 15:51:08.631 11109 11194 I jxcore-log: # setup
03-21 15:51:08.631 11109 11194 I jxcore-log: 
,03-21 15:51:08.756 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 15:51:08.756 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:08.756 11109 11194 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-21 15:51:08.756 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 15:51:08.756 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 15:51:08.756 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:08.756 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 15:51:08.756 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 15:51:08.761 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-21 15:51:08.776  5859  5960 D BtGatt.GattService: stopScan() - queue size =1,
,03-21 15:51:08.776  5859  5955 D BtGatt.ScanManager: filter size is 1,
,03-21 15:51:08.781  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 3
,03-21 15:51:08.781  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,03-21 15:51:08.781  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:08.781  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:08.786  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 15:51:08.786  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:08.786  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-21 15:51:08.791  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 15:51:08.791  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:08.791  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:08.791 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:08.791 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:08.791 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 15:51:08.796 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
03-21 15:51:08.796 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 15:51:08.796 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:08.801 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 15:51:08.801 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,03-21 15:51:08.801 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 15:51:08.806 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:08.806 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:08.806 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:08.806 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:08.806 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:08.811 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 15:51:08.821 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 15:51:08.821 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:08.826 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:08.826 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:08.826 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:08.826 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:08.826 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:08.826 11109 11194 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 15:51:08.826 11109 11194 I jxcore-log: 
03-21 15:51:08.831 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 15:51:08.831 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:08.831 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-21 15:51:08.836 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:08.836 11109 11194 I jxcore-log: 
,03-21 15:51:08.841 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:08.841 11109 11194 I jxcore-log: 
,03-21 15:51:08.846 11109 11194 I jxcore-log: ok 92 error should be null
03-21 15:51:08.846 11109 11194 I jxcore-log: 
,03-21 15:51:08.851 11109 11194 I jxcore-log: ok 93 error should be null
03-21 15:51:08.851 11109 11194 I jxcore-log: 
,03-21 15:51:08.856 11109 11194 I jxcore-log: # 25. should be able to call #startUpdateAdvertisingAndListening many times
03-21 15:51:08.856 11109 11194 I jxcore-log: 
,03-21 15:51:08.901 11109 11194 I jxcore-log: # teardown
03-21 15:51:08.901 11109 11194 I jxcore-log: 
,03-21 15:51:08.946  3424  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 15:51:08.971 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:08.971 11109 11194 I jxcore-log: 
,03-21 15:51:08.976 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 38247
03-21 15:51:08.976 11109 11194 I jxcore-log: 
,03-21 15:51:08.991 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 38247, start advertisements: true
03-21 15:51:08.991 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:08.991 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:08.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:08.996 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-21 15:51:08.996 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:08.996 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:08.996 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:09.001  5859  5869 D BtGatt.GattService: registerClient() - UUID=3c890def-10a5-44eb-a9ec-645871b19641
,03-21 15:51:09.041  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=3c890def-10a5-44eb-a9ec-645871b19641, clientIf=6
,03-21 15:51:09.041 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:09.041  5859  5960 D BtGatt.GattService: start scan with filters
,03-21 15:51:09.066  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 25
,03-21 15:51:09.066 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:09.066 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 15:51:09.066 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:09.071 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-21 15:51:09.071  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:09.071 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:09.071  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:09.071  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:09.071 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:09.071 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:09.071 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 15:51:09.071 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:09.071 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:09.071 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:09.071 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 15:51:09.076  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:09.076  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:09.076  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:09.076  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 15:51:09.076  5859  5955 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-21 15:51:09.081  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:09.081  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:09.081  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:09.081  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:09.096  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:09.096  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:09.101  5859  5871 D BtGatt.GattService: registerClient() - UUID=3f82e074-204a-4be7-a4aa-7d875e0a6f9a,
03-21 15:51:09.101  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:09.101  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:09.146  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=3f82e074-204a-4be7-a4aa-7d875e0a6f9a, clientIf=7,
,03-21 15:51:09.146 11109 11118 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7,
,03-21 15:51:09.176  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 20
,03-21 15:51:09.181  5859  5954 D BtGatt.AdvertiseManager: message : 0
,03-21 15:51:09.186  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:09.186  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:09.186  5859  5954 D BtGatt.AdvertiseManager: starting advertising
03-21 15:51:09.186  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 15:51:09.191  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-21 15:51:09.191  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
03-21 15:51:09.191  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 15:51:09.196  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:09.196  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:09.196 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:09.196 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 15:51:09.201 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:09.201 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:09.201 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:09.201 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 15:51:09.201 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 15:51:09.201 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-21 15:51:09.201 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 15:51:09.201 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:09.201 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:09.201 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-21 15:51:09.206 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:09.206 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:09.206 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:09.206 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:09.206 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 15:51:09.206 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:09.206 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:09.206 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:09.206 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:09.206 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 15:51:09.206 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:09.211 11109 11425 D BluetoothSocket: bindListen(): myUserId = 0,
03-21 15:51:09.211 11109 11425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:09.221 11109 11425 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]},
03-21 15:51:09.221 11109 11425 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:09.221 11109 11425 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:09.221 11109 11425 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b618e91
,03-21 15:51:09.221 11109 11425 D BluetoothSocket: channel: 6
03-21 15:51:09.221 11109 11425 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:09.221 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:09.221 11109 11194 I jxcore-log: 
,03-21 15:51:09.226 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:09.226 11109 11194 I jxcore-log: 
,03-21 15:51:09.226 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:09.226 11109 11194 I jxcore-log: 
,03-21 15:51:09.231 11109 11194 I jxcore-log: ok 94 error should be null
03-21 15:51:09.231 11109 11194 I jxcore-log: 
,03-21 15:51:09.231 11109 11194 I jxcore-log: ok 95 error should be null
03-21 15:51:09.231 11109 11194 I jxcore-log: 
,03-21 15:51:09.236 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 38247, start advertisements: true
03-21 15:51:09.236 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:09.236 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:09.236 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:09.236 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:09.246 11109 11194 I jxcore-log: ok 96 error should be null
03-21 15:51:09.246 11109 11194 I jxcore-log: 
,03-21 15:51:09.246 11109 11194 I jxcore-log: ok 97 error should be null
03-21 15:51:09.246 11109 11194 I jxcore-log: 
,03-21 15:51:09.256 11109 11194 I jxcore-log: # setup
03-21 15:51:09.256 11109 11194 I jxcore-log: 
,03-21 15:51:09.461 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:09.461 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-21 15:51:09.461 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 15:51:09.466 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 15:51:09.466 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 15:51:09.466 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@372011f6, channel: 6, state: LISTENING
,03-21 15:51:09.471 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@372011f6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b618e91, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1864c9f7mSocket: android.net.LocalSocket@47d7064 impl:android.net.LocalSocketImpl@32ff82cd fd:FileDescriptor[116]
,03-21 15:51:09.471 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@47d7064 impl:android.net.LocalSocketImpl@32ff82cd fd:FileDescriptor[116]
,03-21 15:51:09.476 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 15:51:09.476 11109 11425 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 15:51:09.476 11109 11425 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 15:51:09.476 11109 11425 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:09.476 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 15:51:09.476 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 15:51:09.476 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 15:51:09.476 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 15:51:09.481 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 15:51:09.481 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-21 15:51:09.481 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 15:51:09.481 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:09.481 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:09.486  5859  5869 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:09.486  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:09.486  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 4
03-21 15:51:09.486  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:09.486  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:09.486  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:09.491  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-21 15:51:09.491  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:09.491  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-21 15:51:09.491  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:09.496  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
03-21 15:51:09.496  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:09.496  5859  5929 D BtGatt.GattService: current time is 210221241149,
03-21 15:51:09.496  5859  5929 D BtGatt.GattService: Batch record : [-108, -1, -11, -106, -76, 102, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-21 15:51:09.501  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-21 15:51:09.501  5859  5929 D ScanRecord: parseFromBytes,
03-21 15:51:09.501 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 15:51:09.501 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
03-21 15:51:09.501 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-21 15:51:09.501 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-21 15:51:09.501 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 15:51:09.501 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-21 15:51:09.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-21 15:51:09.506  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:09.506  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-21 15:51:09.506  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:09.511  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 15:51:09.511  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 15:51:09.511  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:09.511  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 15:51:09.516 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:09.516 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:09.516 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-21 15:51:09.516 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:09.516 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:09.516 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:09.516 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-21 15:51:09.516 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:09.516 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:09.516 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:09.521 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,03-21 15:51:09.521 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:09.521 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:09.521 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:09.521 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 15:51:09.526 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 15:51:09.531 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 15:51:09.531 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 15:51:09.531 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:09.531 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:09.541 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:09.541 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:09.546 11109 11194 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 15:51:09.546 11109 11194 I jxcore-log: 
03-21 15:51:09.546 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:09.546 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:09.546 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:09.551 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:09.551 11109 11194 I jxcore-log: 
03-21 15:51:09.551 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:09.551 11109 11194 I jxcore-log: 
03-21 15:51:09.551 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:09.551 11109 11194 I jxcore-log: 
03-21 15:51:09.556 11109 11194 I jxcore-log: ok 98 error should be null
03-21 15:51:09.556 11109 11194 I jxcore-log: 
03-21 15:51:09.556 11109 11194 I jxcore-log: ok 99 error should be null
03-21 15:51:09.556 11109 11194 I jxcore-log: 
03-21 15:51:09.561 11109 11194 I jxcore-log: # 26. should be able to call #stopAdvertisingAndListening many times
03-21 15:51:09.561 11109 11194 I jxcore-log: 
,03-21 15:51:09.751 11109 11194 I jxcore-log: # teardown
03-21 15:51:09.751 11109 11194 I jxcore-log: 
,03-21 15:51:09.851 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:09.851 11109 11194 I jxcore-log: 
,03-21 15:51:09.856 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 39110
03-21 15:51:09.856 11109 11194 I jxcore-log: 
,03-21 15:51:09.866 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:09.866 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:09.866 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:09.871 11109 11194 I jxcore-log: ok 100 error should be null
03-21 15:51:09.871 11109 11194 I jxcore-log: 
,03-21 15:51:09.876 11109 11194 I jxcore-log: ok 101 error should be null
03-21 15:51:09.876 11109 11194 I jxcore-log: 
,03-21 15:51:09.881 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 15:51:09.881 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:09.881 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:09.886 11109 11194 I jxcore-log: ok 102 error should be null
03-21 15:51:09.886 11109 11194 I jxcore-log: 
,03-21 15:51:09.886 11109 11194 I jxcore-log: ok 103 error should be null
03-21 15:51:09.886 11109 11194 I jxcore-log: 
,03-21 15:51:09.891 11109 11194 I jxcore-log: # setup
03-21 15:51:09.891 11109 11194 I jxcore-log: 
,03-21 15:51:10.036 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:10.041 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:10.041 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:10.046 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:10.046 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:10.046 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:10.056 11109 11194 I jxcore-log: ok 104 error should be null
03-21 15:51:10.056 11109 11194 I jxcore-log: 
,03-21 15:51:10.066 11109 11194 I jxcore-log: ok 105 error should be null
03-21 15:51:10.066 11109 11194 I jxcore-log: 
,03-21 15:51:10.076 11109 11120 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@372011f6, channel: 6, state: CLOSED
,03-21 15:51:10.081 11109 11194 I jxcore-log: # 27. #start should fail if called twice in a row
03-21 15:51:10.081 11109 11194 I jxcore-log: 
,03-21 15:51:10.181 11109 11194 I jxcore-log: # teardown
03-21 15:51:10.181 11109 11194 I jxcore-log: 
,03-21 15:51:10.311 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:10.311 11109 11194 I jxcore-log: 
,03-21 15:51:10.316 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 60828
03-21 15:51:10.316 11109 11194 I jxcore-log: 
,03-21 15:51:10.321 11109 11194 I jxcore-log: ok 106 first call should succeed
03-21 15:51:10.321 11109 11194 I jxcore-log: 
,03-21 15:51:10.326 11109 11194 I jxcore-log: ok 107 first call should succeed
03-21 15:51:10.326 11109 11194 I jxcore-log: 
,03-21 15:51:10.331 11109 11194 I jxcore-log: ok 108 specific error should be returned
03-21 15:51:10.331 11109 11194 I jxcore-log: 
,03-21 15:51:10.336 11109 11194 I jxcore-log: # setup
03-21 15:51:10.336 11109 11194 I jxcore-log: 
,03-21 15:51:10.546 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:10.546 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:10.551 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:10.556 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:10.556 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:10.556 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:10.566 11109 11194 I jxcore-log: ok 109 error should be null
03-21 15:51:10.566 11109 11194 I jxcore-log: 
,03-21 15:51:10.571 11109 11194 I jxcore-log: ok 110 error should be null
03-21 15:51:10.571 11109 11194 I jxcore-log: 
,03-21 15:51:10.576 11109 11194 I jxcore-log: # 28. does not emit duplicate discoveryAdvertisingStateUpdate
03-21 15:51:10.576 11109 11194 I jxcore-log: 
,03-21 15:51:10.781 11109 11194 I jxcore-log: # teardown
03-21 15:51:10.781 11109 11194 I jxcore-log: 
,03-21 15:51:11.156 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:11.156 11109 11194 I jxcore-log: 
,03-21 15:51:11.161 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 47172
03-21 15:51:11.161 11109 11194 I jxcore-log: 
,03-21 15:51:11.181 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 38247, start advertisements: false
03-21 15:51:11.181 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:11.181 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:11.181 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 15:51:11.181 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:11.181 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:11.181 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:11.186  5859  5960 D BtGatt.GattService: registerClient() - UUID=cf33b096-29f6-4bbd-8d96-30e2f7ef723b
,03-21 15:51:11.226  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=cf33b096-29f6-4bbd-8d96-30e2f7ef723b, clientIf=6
,03-21 15:51:11.226 11109 11118 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:11.226  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:11.241  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 26
,03-21 15:51:11.246 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 15:51:11.246 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:11.246 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:11.246  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:11.246 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-21 15:51:11.246  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:11.246 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:11.246  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:11.246 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:11.246 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:11.256 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:11.256 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:11.261 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 15:51:11.261 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:11.261 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:11.261 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:11.261  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 15:51:11.261  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:11.261  5859  5955 D BtGatt.ScanManager: allow scan with filters
,03-21 15:51:11.261  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:11.261  5859  5955 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-21 15:51:11.266  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:11.266  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:11.266  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:11.266  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:11.266  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:11.266  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:11.266 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:11.266 11109 11194 I jxcore-log: 
,03-21 15:51:11.271  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 15:51:11.271  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:11.271 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:11.271 11109 11194 I jxcore-log: 
,03-21 15:51:11.291 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 47172, start advertisements: true
,03-21 15:51:11.291 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:11.291 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-21 15:51:11.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:11.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:11.301 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-21 15:51:11.301 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-21 15:51:11.301 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 15:51:11.301 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 15:51:11.301 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 15:51:11.301 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 15:51:11.301 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 15:51:11.306  5859  5871 D BtGatt.GattService: registerClient() - UUID=8e20363d-ee73-4412-a525-abe905800873
,03-21 15:51:11.351  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=8e20363d-ee73-4412-a525-abe905800873, clientIf=7
03-21 15:51:11.356 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:11.381  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 21
,03-21 15:51:11.381  5859  5954 D BtGatt.AdvertiseManager: message : 0
,03-21 15:51:11.381  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:11.381  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:11.391  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:11.391  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:11.396  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:11.396  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:11.396  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 15:51:11.401  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:11.401  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:11.401 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:11.401 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:11.401 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:11.401 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:11.401 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:11.401 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:11.401 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 15:51:11.401 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:11.401 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:11.401 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:11.401 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:11.401 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:11.406 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 15:51:11.406 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 15:51:11.406 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 15:51:11.406 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:11.406 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:11.406 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 15:51:11.406 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:11.406 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 15:51:11.411 11109 11464 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 15:51:11.411 11109 11464 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:11.411 11109 11464 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]},
03-21 15:51:11.411 11109 11464 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:11.411 11109 11464 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:11.411 11109 11464 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@220e7ec9
,03-21 15:51:11.411 11109 11464 D BluetoothSocket: channel: 6
03-21 15:51:11.411 11109 11464 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:11.426 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:11.426 11109 11194 I jxcore-log: 
,03-21 15:51:11.431 11109 11194 I jxcore-log: ok 111 called only once
03-21 15:51:11.431 11109 11194 I jxcore-log: 
,03-21 15:51:11.431 11109 11194 I jxcore-log: ok 112 discovery state matches
03-21 15:51:11.431 11109 11194 I jxcore-log: 
,03-21 15:51:11.431 11109 11194 I jxcore-log: ok 113 advertising state matches
03-21 15:51:11.431 11109 11194 I jxcore-log: 
,03-21 15:51:11.441 11109 11194 I jxcore-log: # setup
03-21 15:51:11.441 11109 11194 I jxcore-log: 
,03-21 15:51:11.801 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:11.801 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-21 15:51:11.801 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 15:51:11.801 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-21 15:51:11.806 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 15:51:11.806 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34369ce, channel: 6, state: LISTENING
,03-21 15:51:11.806 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34369ce, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@220e7ec9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@114500efmSocket: android.net.LocalSocket@88467fc impl:android.net.LocalSocketImpl@20f73e85 fd:FileDescriptor[117],
,03-21 15:51:11.806 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@88467fc impl:android.net.LocalSocketImpl@20f73e85 fd:FileDescriptor[117]
,03-21 15:51:11.811 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 15:51:11.811 11109 11464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-21 15:51:11.811 11109 11464 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 15:51:11.811 11109 11464 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-21 15:51:11.811 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 15:51:11.811 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 15:51:11.811 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-21 15:51:11.811 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 15:51:11.816 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 15:51:11.816 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:11.816 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 15:51:11.816 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:11.816 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:11.821  5859  5869 D BtGatt.GattService: stopScan() - queue size =1,
03-21 15:51:11.821  5859  5955 D BtGatt.ScanManager: filter size is 1,
03-21 15:51:11.821  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 5
,03-21 15:51:11.821  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:11.821  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:11.821  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:11.821 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 15:51:11.821  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:11.821 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:11.821 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:11.821 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 15:51:11.821 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-21 15:51:11.821 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:11.821 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 15:51:11.826  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:11.826  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:11.826  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:11.826  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:11.826  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:11.826  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:11.826  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:11.826  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 15:51:11.826  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:11.826  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:11.831 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:11.831 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:11.831 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-21 15:51:11.831 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:11.831 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:11.831 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:11.831 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:11.831 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:11.831  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:11.831  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:11.831  5859  5929 D BtGatt.GattService: current time is 212557328524
03-21 15:51:11.831  5859  5929 D BtGatt.GattService: Batch record : [-75, -17, -96, 125, 21, 96, 1, -128, -84, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:11.831  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:11.831  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:11.831 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:11.831 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:11.831 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:11.831 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:11.831 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:11.831 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:11.831 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:11.836 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:11.836 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:11.836 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:11.836 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:11.841 11109 11194 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-21 15:51:11.841 11109 11194 I jxcore-log: 
,03-21 15:51:11.841 11109 11194 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 15:51:11.841 11109 11194 I jxcore-log: 
,03-21 15:51:11.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:11.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 15:51:11.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:11.846 11109 11194 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 15:51:11.846 11109 11194 I jxcore-log: 
,03-21 15:51:11.846 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 15:51:11.846 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:11.846 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:11.846 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:11.846 11109 11194 I jxcore-log: 
,03-21 15:51:11.851 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:11.851 11109 11194 I jxcore-log: 
,03-21 15:51:11.851 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:11.851 11109 11194 I jxcore-log: 
,03-21 15:51:11.856 11109 11194 I jxcore-log: ok 114 error should be null
03-21 15:51:11.856 11109 11194 I jxcore-log: 
,03-21 15:51:11.856 11109 11194 I jxcore-log: ok 115 error should be null
03-21 15:51:11.856 11109 11194 I jxcore-log: 
,03-21 15:51:11.861 11109 11194 I jxcore-log: # 29. does not send duplicate availability changes
03-21 15:51:11.861 11109 11194 I jxcore-log: 
,03-21 15:51:11.996 11109 11194 I jxcore-log: # teardown
03-21 15:51:11.996 11109 11194 I jxcore-log: 
,03-21 15:51:12.166 11109 11194 I jxcore-log: ok 116 should be called once
03-21 15:51:12.166 11109 11194 I jxcore-log: 
,03-21 15:51:12.171 11109 11194 I jxcore-log: ok 117 should not have been called more than once
03-21 15:51:12.171 11109 11194 I jxcore-log: 
,03-21 15:51:12.176 11109 11194 I jxcore-log: # setup
03-21 15:51:12.176 11109 11194 I jxcore-log: 
,03-21 15:51:12.306 11109 11194 I jxcore-log: ok 118 error should be null
03-21 15:51:12.306 11109 11194 I jxcore-log: 
,03-21 15:51:12.306 11109 11194 I jxcore-log: ok 119 error should be null
03-21 15:51:12.306 11109 11194 I jxcore-log: 
,03-21 15:51:12.311 11109 11194 I jxcore-log: # 30. can get the network status
03-21 15:51:12.311 11109 11194 I jxcore-log: 
,03-21 15:51:12.491 11109 11194 I jxcore-log: # teardown
03-21 15:51:12.491 11109 11194 I jxcore-log: 
,03-21 15:51:12.631 11109 11194 I jxcore-log: ok 120 network status should have certain non-empty properties
03-21 15:51:12.631 11109 11194 I jxcore-log: 
,03-21 15:51:12.636 11109 11194 I jxcore-log: # setup
03-21 15:51:12.636 11109 11194 I jxcore-log: 
,03-21 15:51:12.826 11109 11194 I jxcore-log: ok 121 error should be null
03-21 15:51:12.826 11109 11194 I jxcore-log: 
,03-21 15:51:12.826 11109 11194 I jxcore-log: ok 122 error should be null
03-21 15:51:12.826 11109 11194 I jxcore-log: 
,03-21 15:51:12.831 11109 11194 I jxcore-log: # 31. wifi peer is marked unavailable if announcements stop
03-21 15:51:12.831 11109 11194 I jxcore-log: 
,03-21 15:51:12.941 11109 11194 I jxcore-log: # teardown
03-21 15:51:12.941 11109 11194 I jxcore-log: 
,03-21 15:51:13.096 11109 11194 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-21 15:51:13.096 11109 11194 I jxcore-log: 
,03-21 15:51:13.131 11109 11194 I jxcore-log: ok 123 host address should match
03-21 15:51:13.131 11109 11194 I jxcore-log: 
,03-21 15:51:13.136 11109 11194 I jxcore-log: ok 124 port should match
03-21 15:51:13.136 11109 11194 I jxcore-log: 
,03-21 15:51:14.091 11109 11194 I jxcore-log: ok 125 host address should be null
03-21 15:51:14.091 11109 11194 I jxcore-log: 
,03-21 15:51:14.101 11109 11194 I jxcore-log: ok 126 port should should be null
03-21 15:51:14.101 11109 11194 I jxcore-log: 
,03-21 15:51:14.131 11109 11194 I jxcore-log: # setup
03-21 15:51:14.131 11109 11194 I jxcore-log: 
,03-21 15:51:14.196  3424  3452 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 15:51:14.196  3424  3452 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 15:51:14.196  3424  3452 D BatteryService: online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
03-21 15:51:14.196  3424  3452 D BatteryService: stay LED for fully charged
03-21 15:51:14.196  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 15:51:14.196  3424  3424 I MotionRecognitionService: Plugged
03-21 15:51:14.196  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-21 15:51:14.196  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 15:51:14.196  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-21 15:51:14.201  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:14.201  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:14.201  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 15:51:14.211 11109 11194 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-21 15:51:14.211 11109 11194 I jxcore-log: 
03-21 15:51:14.211  5859  5859 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 15:51:14.211  5859  5956 D HeadsetStateMachine: Disconnected process message: 10
,03-21 15:51:14.211 11109 11194 I jxcore-log: ok 127 error should be null
03-21 15:51:14.211 11109 11194 I jxcore-log: 
,03-21 15:51:14.216 11109 11194 I jxcore-log: ok 128 error should be null
03-21 15:51:14.216 11109 11194 I jxcore-log: 
,03-21 15:51:14.216 11109 11194 I jxcore-log: # 32. Can call start/stopListeningForAdvertisements
03-21 15:51:14.216 11109 11194 I jxcore-log: 
,03-21 15:51:14.221  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 15:51:14.226  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:14.226  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:14.226  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 15:51:14.321 11109 11194 I jxcore-log: # teardown
,03-21 15:51:14.321 11109 11194 I jxcore-log: 
,03-21 15:51:14.431 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 47172, start advertisements: false
,03-21 15:51:14.431 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:14.436 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 15:51:14.436 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 15:51:14.441 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:14.441 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:14.441 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:14.446  5859  5871 D BtGatt.GattService: registerClient() - UUID=c0bfd635-e806-4a44-8717-014540b0017f
,03-21 15:51:14.491  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=c0bfd635-e806-4a44-8717-014540b0017f, clientIf=6
03-21 15:51:14.491 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:14.496  5859  5869 D BtGatt.GattService: start scan with filters
,03-21 15:51:14.516  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 27
,03-21 15:51:14.521  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:14.521  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:14.521  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:14.526  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:14.526  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:14.531  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:14.531  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:14.531  5859  5955 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-21 15:51:14.531  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:14.531  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:14.531  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:14.531  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:14.536  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 15:51:14.536  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:14.536  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:14.536  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:14.541 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 15:51:14.541 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-21 15:51:14.541 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:14.541 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:14.541 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-21 15:51:14.541 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:14.541 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:14.546 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:14.546 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:14.546 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:14.546 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-21 15:51:14.546 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:14.546 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:14.546 11109 11194 I jxcore-log: ok 129 Can call startListeningForAdvertisements without error
03-21 15:51:14.546 11109 11194 I jxcore-log: 
,03-21 15:51:14.556 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:14.556 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:14.556 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 15:51:14.556 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-21 15:51:14.556  5859  5960 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:14.556  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:14.556  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 6
03-21 15:51:14.561  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:14.561  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:14.561  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:14.561  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 15:51:14.561  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:14.561  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 15:51:14.561  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:14.566  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:14.566  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:14.566 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 15:51:14.571 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:14.571 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:14.571 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 15:51:14.571 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 15:51:14.571 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:14.571 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:14.571 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:14.571 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:14.576 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-21 15:51:14.576 11109 11194 I jxcore-log: 
,03-21 15:51:14.576 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:14.576 11109 11194 I jxcore-log: 
,03-21 15:51:14.581 11109 11194 I jxcore-log: ok 130 Can call stopListeningForAdvertisements without error
03-21 15:51:14.581 11109 11194 I jxcore-log: 
,03-21 15:51:14.586 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:14.586 11109 11194 I jxcore-log: 
,03-21 15:51:14.591 11109 11194 I jxcore-log: # setup
03-21 15:51:14.591 11109 11194 I jxcore-log: 
,03-21 15:51:14.766 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:14.766 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:14.766 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:14.771 11109 11194 I jxcore-log: ok 131 Should be able to call stopListeningForAdvertisments in teardown
03-21 15:51:14.771 11109 11194 I jxcore-log: 
,03-21 15:51:14.776 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:14.776 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:14.776 11109 11194 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 15:51:14.776 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 15:51:14.776 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 15:51:14.776 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:14.776 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-21 15:51:14.781 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:14.781 11109 11194 D BluetoothLeScanner: could not find callback wrapper
03-21 15:51:14.781 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:14.786 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:14.786 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:14.786 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:14.786 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:14.786 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:14.786 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:14.786 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:14.786 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:14.796 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-21 15:51:14.806 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:14.806 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 15:51:14.806 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:14.811 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:14.811 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:14.811 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:14.816 11109 11194 I jxcore-log: ok 132 Should be able to call stopAdvertisingAndListening in teardown
03-21 15:51:14.816 11109 11194 I jxcore-log: 
,03-21 15:51:14.821 11109 11194 I jxcore-log: # 33. Calling startListeningForAdvertisements twice is NOT an error
03-21 15:51:14.821 11109 11194 I jxcore-log: 
,03-21 15:51:14.826 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:14.826 11109 11194 I jxcore-log: 
,03-21 15:51:14.906 11109 11194 I jxcore-log: # teardown
03-21 15:51:14.906 11109 11194 I jxcore-log: 
,03-21 15:51:15.106 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 47172, start advertisements: false
,03-21 15:51:15.111 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started,
,03-21 15:51:15.116 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,03-21 15:51:15.116 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
,03-21 15:51:15.131 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:15.136 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:15.136 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:15.151  5859  5960 D BtGatt.GattService: registerClient() - UUID=0dd69782-3009-42c8-b281-0fe6a9f77e0e
,03-21 15:51:15.181  3424  6046 D SSRM:n  : SIOP:: AP = 290, PST = 281 (W:10), CUR = 14, LCD = 0
,03-21 15:51:15.196  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=0dd69782-3009-42c8-b281-0fe6a9f77e0e, clientIf=6
03-21 15:51:15.196 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:15.196  5859  5869 D BtGatt.GattService: start scan with filters
,03-21 15:51:15.216  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 28
,03-21 15:51:15.216  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:15.216  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:15.216  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:15.221  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:15.221  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:15.221  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:15.221  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:15.226  5859  5955 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-21 15:51:15.226  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:15.226  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:15.226  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:15.226  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:15.231  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
,03-21 15:51:15.231  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:15.236  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
03-21 15:51:15.236  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:15.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:15.241 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:15.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-21 15:51:15.241 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:15.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 15:51:15.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:15.241 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:15.246 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:15.246 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-21 15:51:15.246 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:15.246 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:15.246 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:15.246 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK,
,03-21 15:51:15.256 11109 11194 I jxcore-log: ok 133 Can call startListeningForAdvertisements without error
03-21 15:51:15.256 11109 11194 I jxcore-log: 
,03-21 15:51:15.261 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 47172, start advertisements: false
,03-21 15:51:15.261 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:15.261 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:15.261 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:15.261 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:15.266 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:15.266 11109 11194 I jxcore-log: 
,03-21 15:51:15.266 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:15.266 11109 11194 I jxcore-log: 
,03-21 15:51:15.271 11109 11194 I jxcore-log: ok 134 Can call startListeningForAdvertisements twice without error
03-21 15:51:15.271 11109 11194 I jxcore-log: 
,03-21 15:51:15.276 11109 11194 I jxcore-log: # setup
03-21 15:51:15.276 11109 11194 I jxcore-log: 
,03-21 15:51:15.626 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:15.631 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:15.631 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,03-21 15:51:15.631 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:15.636  5859  5871 D BtGatt.GattService: stopScan() - queue size =1,
03-21 15:51:15.636  5859  5955 D BtGatt.ScanManager: filter size is 1
,03-21 15:51:15.636  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 7,
03-21 15:51:15.641  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 15:51:15.641  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:15.641  5859  5955 D BtGatt.ScanManager: stopping BLe Batch,
03-21 15:51:15.646  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-21 15:51:15.646  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:15.646  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:15.646  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 15:51:15.646  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:15.656  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-21 15:51:15.656 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:15.656 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:15.656 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:15.656 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 15:51:15.656 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 15:51:15.656 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:15.656 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:15.661 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:15.661 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:15.661 11109 11194 I jxcore-log: ok 135 Should be able to call stopListeningForAdvertisments in teardown
03-21 15:51:15.661 11109 11194 I jxcore-log: 
03-21 15:51:15.661 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 15:51:15.661 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:15.661 11109 11194 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-21 15:51:15.661 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 15:51:15.661 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 15:51:15.661 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:15.661 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 15:51:15.666 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:15.666 11109 11194 D BluetoothLeScanner: could not find callback wrapper
03-21 15:51:15.666 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:15.671 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:15.671 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:15.671 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:15.671 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:15.676 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:15.676 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:15.676 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:15.676 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 15:51:15.681 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-21 15:51:15.691 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 15:51:15.691 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:15.691 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:15.696 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-21 15:51:15.696 11109 11194 I jxcore-log: 
,03-21 15:51:15.701 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-21 15:51:15.701 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:15.701 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:15.706 11109 11194 I jxcore-log: ok 136 Should be able to call stopAdvertisingAndListening in teardown
03-21 15:51:15.706 11109 11194 I jxcore-log: 
,03-21 15:51:15.721 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:15.721 11109 11194 I jxcore-log: 
,03-21 15:51:15.726 11109 11194 I jxcore-log: # 34. Can call start/stopUpdateAdvertisingAndListening
03-21 15:51:15.726 11109 11194 I jxcore-log: 
,03-21 15:51:15.896 11109 11194 I jxcore-log: # teardown
03-21 15:51:15.896 11109 11194 I jxcore-log: 
,03-21 15:51:16.071 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-21 15:51:16.071 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:16.071 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 15:51:16.076 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:16.081 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:16.081 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:16.081 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:16.086 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:16.091  5859  5871 D BtGatt.GattService: registerClient() - UUID=1332af51-f8e0-48ef-872f-614da6fc6f9d
,03-21 15:51:16.136  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=1332af51-f8e0-48ef-872f-614da6fc6f9d, clientIf=6
03-21 15:51:16.136 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:16.136  5859  5869 D BtGatt.GattService: start scan with filters
,03-21 15:51:16.151  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 29
,03-21 15:51:16.151  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:16.151  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:16.151  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:16.156  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:16.156  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.156  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:16.156  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:16.156  5859  5955 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-21 15:51:16.161  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:16.161  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.161  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:16.161  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:16.166  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:16.166  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.166  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:16.166  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.171 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:16.171 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:16.171 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:16.171 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:16.171 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:16.171 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:16.171 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:16.171 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:16.171 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:16.171 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:16.171 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 15:51:16.171 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:16.171  5859  5871 D BtGatt.GattService: registerClient() - UUID=610a5e29-2dfe-42eb-bcc3-6791b3869a9a
,03-21 15:51:16.216  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=610a5e29-2dfe-42eb-bcc3-6791b3869a9a, clientIf=7,
03-21 15:51:16.216 11109 11118 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:16.226  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 22,
,03-21 15:51:16.226  5859  5954 D BtGatt.AdvertiseManager: message : 0,
,03-21 15:51:16.226  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:16.226  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
03-21 15:51:16.226  5859  5954 D BtGatt.AdvertiseManager: starting advertising
03-21 15:51:16.226  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 15:51:16.231  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-21 15:51:16.231  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
03-21 15:51:16.231  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:16.236  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
03-21 15:51:16.236  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 15:51:16.236 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-21 15:51:16.236 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:16.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-21 15:51:16.241 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:16.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
,03-21 15:51:16.241 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:16.241 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 15:51:16.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-21 15:51:16.241 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 15:51:16.241 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:16.241 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:16.241 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:16.241 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 15:51:16.241 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:16.241 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:16.241 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 15:51:16.241 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:16.241 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:16.241 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:16.241 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:16.241 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 15:51:16.241 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:16.241 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:16.246 11109 11532 D BluetoothSocket: bindListen(): myUserId = 0
03-21 15:51:16.246 11109 11532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 15:51:16.251 11109 11532 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-21 15:51:16.251 11109 11532 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:16.251 11109 11532 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:16.251 11109 11532 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fabc283
,03-21 15:51:16.251 11109 11532 D BluetoothSocket: channel: 6
03-21 15:51:16.251 11109 11532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 15:51:16.251 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:16.251 11109 11194 I jxcore-log: 
,03-21 15:51:16.256 11109 11194 I jxcore-log: ok 137 Can call startUpdateAdvertisingAndListening without error,
03-21 15:51:16.256 11109 11194 I jxcore-log: 
03-21 15:51:16.256 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:16.256 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 15:51:16.256 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 15:51:16.256 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 15:51:16.256 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 15:51:16.256 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35b7ec00, channel: 6, state: LISTENING
,03-21 15:51:16.256 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35b7ec00, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fabc283, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3137ac39mSocket: android.net.LocalSocket@1843e27e impl:android.net.LocalSocketImpl@2f5e03df fd:FileDescriptor[92]
03-21 15:51:16.256 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1843e27e impl:android.net.LocalSocketImpl@2f5e03df fd:FileDescriptor[92]
03-21 15:51:16.256 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 15:51:16.256 11109 11532 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 15:51:16.256 11109 11532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 15:51:16.256 11109 11532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:16.256 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 15:51:16.256 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 15:51:16.256 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 15:51:16.256 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 15:51:16.256 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:16.256 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 15:51:16.256 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:16.256 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-21 15:51:16.256 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 15:51:16.261  5859  5960 D BtGatt.GattService: stopScan() - queue size =1
,03-21 15:51:16.261  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:16.261  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 8
03-21 15:51:16.261  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 15:51:16.261  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:16.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:16.261  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:16.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 15:51:16.261 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:16.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 15:51:16.261 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 15:51:16.261  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:16.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:16.261 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 15:51:16.261  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:16.261  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:16.261  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 15:51:16.261  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:16.261  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:16.266  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:16.266  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:16.266  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:16.266  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.266  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 15:51:16.266  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:16.266  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:16.266 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 15:51:16.266 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:16.266 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 15:51:16.266 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:16.266 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:16.266 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 15:51:16.266 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:16.266 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:16.271 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:16.271 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:16.271 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:16.271 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:16.271 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:16.271 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:16.271 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:16.271 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:16.271 11109 11194 I jxcore-log: 
,03-21 15:51:16.271 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:16.271 11109 11194 I jxcore-log: 
,03-21 15:51:16.276 11109 11194 I jxcore-log: ok 138 Can call stopAdvertisingAndListening without error
03-21 15:51:16.276 11109 11194 I jxcore-log: 
,03-21 15:51:16.276 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:16.281 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:16.281 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-21 15:51:16.281 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:16.281 11109 11194 I jxcore-log: # setup
03-21 15:51:16.281 11109 11194 I jxcore-log: 
,03-21 15:51:16.286 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 15:51:16.286 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:16.286 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:16.286 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:16.286 11109 11194 I jxcore-log: 
,03-21 15:51:16.286 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:16.286 11109 11194 I jxcore-log: ,
,03-21 15:51:16.286 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:16.286 11109 11194 I jxcore-log: 
,03-21 15:51:16.461 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:16.466 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:16.471 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:16.476 11109 11194 I jxcore-log: ok 139 Should be able to call stopListeningForAdvertisments in teardown
03-21 15:51:16.476 11109 11194 I jxcore-log: 
,03-21 15:51:16.476 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:16.481 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:16.481 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:16.486 11109 11194 I jxcore-log: ok 140 Should be able to call stopAdvertisingAndListening in teardown
03-21 15:51:16.486 11109 11194 I jxcore-log: 
,03-21 15:51:16.496 11109 11194 I jxcore-log: # 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-21 15:51:16.496 11109 11194 I jxcore-log: 
,03-21 15:51:16.616 11109 11194 I jxcore-log: # teardown
03-21 15:51:16.616 11109 11194 I jxcore-log: 
,03-21 15:51:16.781 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-21 15:51:16.781 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:16.781 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 15:51:16.781 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:16.786 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:16.786 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:16.786 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:16.791 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:16.796  5859  5871 D BtGatt.GattService: registerClient() - UUID=6bc69b7e-0ec8-4f5b-b560-160c1ef00520
,03-21 15:51:16.841  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=6bc69b7e-0ec8-4f5b-b560-160c1ef00520, clientIf=6
03-21 15:51:16.841 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:16.846  5859  5869 D BtGatt.GattService: start scan with filters,
,03-21 15:51:16.871  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 30
,03-21 15:51:16.871  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:16.871  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:16.871  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:16.881  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:16.881  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.881  5859  5955 D BtGatt.ScanManager: allow scan with filters
,03-21 15:51:16.881  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:16.881  5859  5955 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
03-21 15:51:16.886  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:16.886  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.886  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan,
03-21 15:51:16.886  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:16.891  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:16.891  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:16.891 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,03-21 15:51:16.891  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:16.891  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:16.891 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:16.891 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:16.891 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:16.891 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:16.891 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:16.891 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:16.891 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:16.891 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:16.891 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:16.891 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 15:51:16.891 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 15:51:16.896  5859  5869 D BtGatt.GattService: registerClient() - UUID=a470c5bb-6104-4060-ac60-fc7c8b29c9de,
,03-21 15:51:16.941  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=a470c5bb-6104-4060-ac60-fc7c8b29c9de, clientIf=7
,03-21 15:51:16.941 11109 11118 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:16.956  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 23
,03-21 15:51:16.956  5859  5954 D BtGatt.AdvertiseManager: message : 0
,03-21 15:51:16.956  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:16.956  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:16.956  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:16.956  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:16.961  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:16.966  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:16.966  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:16.966  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:16.966  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:16.966 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:16.966 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 15:51:16.971 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:16.971 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:16.971 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:16.971 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 15:51:16.971 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 15:51:16.971 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 15:51:16.971 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 15:51:16.971 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:16.971 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:16.976 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:16.976 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:16.976 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:16.976 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:16.976 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:16.976 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 15:51:16.976 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:16.976 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:16.976 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:16.976 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:16.976 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 15:51:16.976 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:16.976 11109 11544 D BluetoothSocket: bindListen(): myUserId = 0
03-21 15:51:16.976 11109 11544 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:16.976 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:16.976 11109 11194 I jxcore-log: 
,03-21 15:51:16.981 11109 11194 I jxcore-log: ok 141 Can call startUpdateAdvertisingAndListening without error,
03-21 15:51:16.981 11109 11194 I jxcore-log: 
03-21 15:51:16.981 11109 11544 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-21 15:51:16.981 11109 11544 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:16.981 11109 11544 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 15:51:16.981 11109 11544 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8c8fefb
03-21 15:51:16.981 11109 11544 D BluetoothSocket: channel: 6
03-21 15:51:16.981 11109 11544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:16.986 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-21 15:51:16.986 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:16.986 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:16.986 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:16.986 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:16.986 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:16.986 11109 11194 I jxcore-log: 
,03-21 15:51:16.991 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:16.991 11109 11194 I jxcore-log: 
,03-21 15:51:16.991 11109 11194 I jxcore-log: ok 142 Can call startUpdateAdvertisingAndListening twice without error
03-21 15:51:16.991 11109 11194 I jxcore-log: 
,03-21 15:51:17.001 11109 11194 I jxcore-log: # setup
03-21 15:51:17.001 11109 11194 I jxcore-log: 
,03-21 15:51:17.361 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:17.366 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-21 15:51:17.366 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-21 15:51:17.366 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:17.371  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:17.371  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:17.371  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 9
03-21 15:51:17.371  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:17.371  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:17.371  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:17.376  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-21 15:51:17.376  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:17.376  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-21 15:51:17.381  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1,
,03-21 15:51:17.381  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:17.381  5859  5929 D BtGatt.GattService: current time is 218106797483
03-21 15:51:17.381  5859  5929 D BtGatt.GattService: Batch record : [-112, -47, 9, 57, -91, 126, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
,03-21 15:51:17.381  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-21 15:51:17.381  5859  5929 D ScanRecord: parseFromBytes
,03-21 15:51:17.386  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 15:51:17.391 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:17.391 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 15:51:17.391 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-21 15:51:17.391 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 15:51:17.391 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 15:51:17.391 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
,03-21 15:51:17.391 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:17.391 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-21 15:51:17.391 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:17.401 11109 11194 I jxcore-log: ok 143 Should be able to call stopListeningForAdvertisments in teardown,
03-21 15:51:17.401 11109 11194 I jxcore-log: 
,03-21 15:51:17.401 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:17.401 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-21 15:51:17.401 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 15:51:17.401 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
,03-21 15:51:17.406 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 15:51:17.406 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c673b18, channel: 6, state: LISTENING
03-21 15:51:17.406 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c673b18, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8c8fefb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2885a971mSocket: android.net.LocalSocket@38efc356 impl:android.net.LocalSocketImpl@361e8fd7 fd:FileDescriptor[92],
03-21 15:51:17.406 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38efc356 impl:android.net.LocalSocketImpl@361e8fd7 fd:FileDescriptor[92]
,03-21 15:51:17.406 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-21 15:51:17.406 11109 11544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 15:51:17.406 11109 11544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-21 15:51:17.406 11109 11544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:17.411 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 15:51:17.411 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,03-21 15:51:17.411 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
,03-21 15:51:17.411 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-21 15:51:17.411 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 15:51:17.411 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:17.411 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 15:51:17.411 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:17.416 11109 11194 D BluetoothLeScanner: could not find callback wrapper
03-21 15:51:17.416 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:17.416 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 15:51:17.416  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:17.416  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:17.416  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:17.416  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:17.421  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:17.421  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:17.421  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:17.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:17.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:17.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 15:51:17.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:17.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:17.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:17.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:17.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 15:51:17.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:17.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:17.421 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:17.421 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:17.421 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:17.421 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:17.421 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:17.426 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:17.426 11109 11194 I jxcore-log: 
,03-21 15:51:17.426 11109 11194 I jxcore-log: ok 144 Should be able to call stopAdvertisingAndListening in teardown
03-21 15:51:17.426 11109 11194 I jxcore-log: 
,03-21 15:51:17.431 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:17.436 11109 11194 I jxcore-log: # 36. peerAvailabilityChange is called
03-21 15:51:17.436 11109 11194 I jxcore-log: 
,03-21 15:51:17.436 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:17.436 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:17.436 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:17.436 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 15:51:17.436 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:17.441 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:17.441 11109 11194 I jxcore-log: 
,03-21 15:51:17.441 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:17.441 11109 11194 I jxcore-log: 
,03-21 15:51:17.626 11109 11194 I jxcore-log: # teardown,
03-21 15:51:17.626 11109 11194 I jxcore-log: 
,03-21 15:51:18.041 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-21 15:51:18.041 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:18.041 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 15:51:18.041 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:18.046 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:18.046 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:18.051 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:18.051 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:18.056  5859  5869 D BtGatt.GattService: registerClient() - UUID=b9c086ef-99f2-46b4-9f53-15f3bf97d47e
,03-21 15:51:18.101  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=b9c086ef-99f2-46b4-9f53-15f3bf97d47e, clientIf=6
03-21 15:51:18.101 11109 11118 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:18.106  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:18.131  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 31
,03-21 15:51:18.131  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:18.131  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:18.131  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:18.141  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:18.141  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:18.141  5859  5955 D BtGatt.ScanManager: allow scan with filters
,03-21 15:51:18.141  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:18.141  5859  5955 D BtGatt.ScanManager: set filter index= 10 for clientIf= 6
03-21 15:51:18.146  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:18.146  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:18.146  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan,
03-21 15:51:18.146  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:18.151  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 15:51:18.151  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:18.151 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 15:51:18.151 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:18.151 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:18.151 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:18.151 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:18.151 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:18.151 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 15:51:18.151 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:18.151 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:18.151  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:18.151 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:18.151  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:18.151 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 15:51:18.156  5859  5869 D BtGatt.GattService: registerClient() - UUID=fa97e2bb-08b8-4d3b-8ce7-c8982c45aa06
03-21 15:51:18.156 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 15:51:18.196  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=fa97e2bb-08b8-4d3b-8ce7-c8982c45aa06, clientIf=7
,03-21 15:51:18.196 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:18.211  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 24
,03-21 15:51:18.211  5859  5954 D BtGatt.AdvertiseManager: message : 0
,03-21 15:51:18.211  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:18.211  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:18.211  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:18.211  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:18.216  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:18.216  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:18.216  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:18.216  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:18.216  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:18.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 15:51:18.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 15:51:18.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:18.221 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:18.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:18.221 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:18.221 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 15:51:18.226 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 15:51:18.226 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 15:51:18.226 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:18.226 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:18.226 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:18.226 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-21 15:51:18.226 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:18.226 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:18.226 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:18.226 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 15:51:18.226 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:18.226 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:18.226 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:18.226 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:18.226 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 15:51:18.226 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:18.226 11109 11559 D BluetoothSocket: bindListen(): myUserId = 0
03-21 15:51:18.226 11109 11559 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:18.231 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:18.231 11109 11194 I jxcore-log: 
,03-21 15:51:18.231 11109 11559 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[92]}
03-21 15:51:18.231 11109 11559 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 15:51:18.231 11109 11559 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:18.231 11109 11559 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18d25273
03-21 15:51:18.231 11109 11559 D BluetoothSocket: channel: 6
03-21 15:51:18.231 11109 11559 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:18.231 11109 11194 I jxcore-log: ok 145 Can call startUpdateAdvertisingAndListeningwithout error
03-21 15:51:18.231 11109 11194 I jxcore-log: 
,03-21 15:51:18.236 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false
,03-21 15:51:18.236 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:18.236 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-21 15:51:18.236 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:18.236 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:18.236 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:18.236 11109 11194 I jxcore-log: 
,03-21 15:51:18.241 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:18.241 11109 11194 I jxcore-log: 
,03-21 15:51:18.241 11109 11194 I jxcore-log: ok 146 Can call startListeningForAdvertisements without error
03-21 15:51:18.241 11109 11194 I jxcore-log: 
,03-21 15:51:19.156  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:19.176  5859  5859 D BtGatt.ScanManager: awakened up at time 219903
,03-21 15:51:19.191  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:19.196  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:19.196  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:19.196  5859  5929 D BtGatt.GattService: current time is 219923393066
03-21 15:51:19.196  5859  5929 D BtGatt.GattService: Batch record : [-87, -118, 98, -121, 23, 64, 1, -128, -69, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:19.196  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:19.196  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:19.196  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=40:17:87:62:8A:A9, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-69, mTimestampNanos=219873572483}
03-21 15:51:19.196  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:19.201 11109 11117 D ScanRecord: parseFromBytes
,03-21 15:51:19.211  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-21 15:51:19.211  3724  3724 I PERF    : received broadcast android.intent.action.TIME_TICK
03-21 15:51:19.211  3724  3724 D KeyguardUpdateMonitor: handleTimeUpdate
,03-21 15:51:19.231  3724  3724 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-21 15:51:19.236 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1,
03-21 15:51:19.236 11109 11109 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 15:51:19.236 11109 11194 I jxcore-log: ok 147 peers must be an array
03-21 15:51:19.236 11109 11194 I jxcore-log: 
03-21 15:51:19.236 11109 11194 I jxcore-log: ok 148 peers must not be zero-length
03-21 15:51:19.236 11109 11194 I jxcore-log: 
03-21 15:51:19.236 11109 11194 I jxcore-log: ok 149 peer must have peerIdentifier
03-21 15:51:19.236 11109 11194 I jxcore-log: 
,03-21 15:51:19.246  3724  3724 D SecKeyguardClockView: HomeTimezone(): 1
,03-21 15:51:19.246 11109 11194 I jxcore-log: ok 150 peerIdentifier must be a string
03-21 15:51:19.246 11109 11194 I jxcore-log: 
,03-21 15:51:19.251 11109 11194 I jxcore-log: ok 151 peer must have peerAvailable
03-21 15:51:19.251 11109 11194 I jxcore-log: 
,03-21 15:51:19.256  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.256 11109 11194 I jxcore-log: ok 152 peer must have pleaseConnect
03-21 15:51:19.256 11109 11194 I jxcore-log: 
,03-21 15:51:19.261  3724  3724 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-21 15:51:19.271  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-21 15:51:19.301 11109 11194 I jxcore-log: # setup
03-21 15:51:19.301 11109 11194 I jxcore-log: 
,03-21 15:51:19.311  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.311  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.316  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.321  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.321  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.326  3724  3724 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.341  3724  3724 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-21 15:51:19.471 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:19.471 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 15:51:19.471 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 15:51:19.471 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:19.476  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
,03-21 15:51:19.476  5859  5955 D BtGatt.ScanManager: filter size is 1
,03-21 15:51:19.476  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 10
03-21 15:51:19.476  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:19.476 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 15:51:19.481 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:19.481 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:19.481 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-21 15:51:19.481 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 15:51:19.481  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:19.481 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:19.481  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:19.481  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:19.481 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:19.481 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 15:51:19.481 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:19.486 11109 11194 I jxcore-log: ok 153 Should be able to call stopListeningForAdvertisments in teardown
03-21 15:51:19.486 11109 11194 I jxcore-log: 
,03-21 15:51:19.486  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:19.486  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:19.486  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:19.491 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-21 15:51:19.491 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-21 15:51:19.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 15:51:19.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 15:51:19.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 15:51:19.491 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a7f15a9, channel: 6, state: LISTENING
03-21 15:51:19.491 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a7f15a9, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18d25273, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a6be72emSocket: android.net.LocalSocket@2bf5a2cf impl:android.net.LocalSocketImpl@a4b945c fd:FileDescriptor[92]
,03-21 15:51:19.491 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2bf5a2cf impl:android.net.LocalSocketImpl@a4b945c fd:FileDescriptor[92]
,03-21 15:51:19.491 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 15:51:19.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 15:51:19.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 15:51:19.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:19.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 15:51:19.491 11109 11559 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-21 15:51:19.491 11109 11559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 15:51:19.491 11109 11559 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:19.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:19.491 11109 11194 D BluetoothLeScanner: could not find callback wrapper
03-21 15:51:19.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:19.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 15:51:19.496  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:19.496  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:19.496  5859  5929 D BtGatt.GattService: current time is 220220737191
03-21 15:51:19.496  5859  5929 D BtGatt.GattService: Batch record : [-87, -118, 98, -121, 23, 64, 1, -128, -71, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:19.496  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:19.496  5859  5929 D ScanRecord: parseFromBytes
,03-21 15:51:19.496  5859  5954 D BtGatt.AdvertiseManager: message : 1
,03-21 15:51:19.496  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-21 15:51:19.496  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:19.501  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:19.501  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 15:51:19.501  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:19.501  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:19.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 15:51:19.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-21 15:51:19.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 15:51:19.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-21 15:51:19.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:19.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:19.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:19.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:19.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:19.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,03-21 15:51:19.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:19.506 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:19.506 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:19.506 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:19.511 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:19.511 11109 11194 I jxcore-log: 
,03-21 15:51:19.516 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:19.526 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:19.526 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:19.526 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-21 15:51:19.526 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 15:51:19.526 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:19.531 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-21 15:51:19.531 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:19.531 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:19.531 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:19.531 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 15:51:19.536 11109 11194 I jxcore-log: ok 154 Should be able to call stopAdvertisingAndListening in teardown
03-21 15:51:19.536 11109 11194 I jxcore-log: 
,03-21 15:51:19.546 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-21 15:51:19.546 11109 11194 I jxcore-log: 
,03-21 15:51:19.556 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:19.556 11109 11194 I jxcore-log: 
,03-21 15:51:19.556 11109 11194 I jxcore-log: # 37. Can connect to a remote peer,
03-21 15:51:19.556 11109 11194 I jxcore-log: 
,03-21 15:51:19.726 11109 11194 I jxcore-log: # teardown
03-21 15:51:19.726 11109 11194 I jxcore-log: 
,03-21 15:51:20.281 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 49302, start advertisements: true
,03-21 15:51:20.281 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:20.281 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 15:51:20.286 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:20.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:20.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:20.291 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:20.291 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:20.296  5859  5960 D BtGatt.GattService: registerClient() - UUID=f8113a6e-cc87-4750-aaac-247abbb17d8f
,03-21 15:51:20.336  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=f8113a6e-cc87-4750-aaac-247abbb17d8f, clientIf=6
,03-21 15:51:20.341 11109 11118 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:20.341  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:20.351  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 32
,03-21 15:51:20.351 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:20.351 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:20.351 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:20.351  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:20.351  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:20.351 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:20.351  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:20.351 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:20.351 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:20.351 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:20.351 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:20.351 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:20.351 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:20.351 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:20.351 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 15:51:20.356  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 15:51:20.356  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:20.356  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:20.356  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:20.356  5859  5955 D BtGatt.ScanManager: set filter index= 11 for clientIf= 6
,03-21 15:51:20.356  5859  5869 D BtGatt.GattService: registerClient() - UUID=b3f79d4c-f50f-40fd-b5c6-188296f6e801
03-21 15:51:20.356  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:20.356  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:20.361  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:20.361  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:20.361  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 15:51:20.361  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:20.361  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:20.361  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:20.401  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=b3f79d4c-f50f-40fd-b5c6-188296f6e801, clientIf=7
,03-21 15:51:20.401 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:20.431  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 25
,03-21 15:51:20.431  5859  5954 D BtGatt.AdvertiseManager: message : 0
,03-21 15:51:20.436  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
,03-21 15:51:20.436  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:20.451  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:20.451  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:20.466  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:20.471  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:20.476  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:20.476  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:20.476  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 15:51:20.481 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:20.481 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 15:51:20.501 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:20.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,03-21 15:51:20.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
,03-21 15:51:20.511 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-21 15:51:20.516 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-21 15:51:20.521 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,03-21 15:51:20.521 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 15:51:20.526 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
,03-21 15:51:20.531 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
03-21 15:51:20.531 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:20.531 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 15:51:20.531 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
,03-21 15:51:20.531 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING],
03-21 15:51:20.531 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 15:51:20.531 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:20.531 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:20.531 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 15:51:20.531 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:20.531 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 15:51:20.531 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:20.536 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:20.561 11109 11585 D BluetoothSocket: bindListen(): myUserId = 0,
,03-21 15:51:20.561 11109 11585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:20.566 11109 11585 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]},
03-21 15:51:20.566 11109 11585 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 15:51:20.566 11109 11585 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:20.566 11109 11585 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@62b9a48
,03-21 15:51:20.566 11109 11585 D BluetoothSocket: channel: 6,
03-21 15:51:20.566 11109 11585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...,
,03-21 15:51:20.571 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:20.571 11109 11194 I jxcore-log: 
,03-21 15:51:20.576 11109 11194 I jxcore-log: ok 155 Can call startUpdateAdvertisingAndListening without error
03-21 15:51:20.576 11109 11194 I jxcore-log: 
,03-21 15:51:20.581 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 49302, start advertisements: false
,03-21 15:51:20.581 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:20.586 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
,03-21 15:51:20.586 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:20.586 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:20.591 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:20.591 11109 11194 I jxcore-log: 
,03-21 15:51:20.601 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:20.601 11109 11194 I jxcore-log: 
,03-21 15:51:20.601 11109 11194 I jxcore-log: ok 156 Can call startListeningForAdvertisements without error
03-21 15:51:20.601 11109 11194 I jxcore-log: 
,03-21 15:51:21.366  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:21.376  5859  5859 D BtGatt.ScanManager: awakened up at time 222103
,03-21 15:51:21.381  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:21.391  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:21.391  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:21.391  5859  5929 D BtGatt.GattService: current time is 222115767108
03-21 15:51:21.391  5859  5929 D BtGatt.GattService: Batch record : [64, 124, 53, 111, 43, 82, 1, -128, -83, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:21.391  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:21.391  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:21.391  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=52:2B:6F:35:7C:40, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=222115942650}
03-21 15:51:21.391  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:21.391 11109 11117 D ScanRecord: parseFromBytes
03-21 15:51:21.391 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 15:51:21.391 11109 11109 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 15:51:21.411 11109 11194 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-21 15:51:21.411 11109 11194 I jxcore-log: 
,03-21 15:51:21.416 11109 11194 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-21 15:51:21.416 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 15:51:21.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,03-21 15:51:21.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,03-21 15:51:21.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-21 15:51:21.421 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-21 15:51:21.421 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
,03-21 15:51:21.426 11109 11194 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-21 15:51:21.426 11109 11592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1540)
,03-21 15:51:21.436 11109 11592 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-21 15:51:21.436 11109 11592 D BluetoothSocket: connect(): myUserId = 0
03-21 15:51:21.436 11109 11592 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:21.441  5859  5871 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 15:51:21.441  5859  6005 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:21.441  5859  6005 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15
03-21 15:51:21.441  5859  6005 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 15:51:21.441  5859  6005 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value 1
03-21 15:51:21.441 11109 11592 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
03-21 15:51:21.441  5859  6005 D IOP_DB_BT: db_query_execute: result 1
03-21 15:51:21.441  5859  6005 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 15:51:21.741  3424  3862 E Watchdog: !@Sync 7 [03-21 15:51:21.746]
,03-21 15:51:22.406  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:22.416  5859  5859 D BtGatt.ScanManager: awakened up at time 223143,
,03-21 15:51:22.421  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:22.431  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:22.431  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:22.431  5859  5929 D BtGatt.GattService: current time is 223158124067
03-21 15:51:22.431  5859  5929 D BtGatt.GattService: Batch record : [64, 124, 53, 111, 43, 82, 1, -128, -76, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
03-21 15:51:22.431  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
03-21 15:51:22.431  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:22.431  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=52:2B:6F:35:7C:40, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-76, mTimestampNanos=223108264233}
03-21 15:51:22.431  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:22.431 11109 11118 D ScanRecord: parseFromBytes
03-21 15:51:22.436 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 15:51:23.451  3424  3618 V AlarmManager: waitForAlarm result :4,
,03-21 15:51:23.461  5859  5859 D BtGatt.ScanManager: awakened up at time 224188
03-21 15:51:23.466  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:23.471  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:23.471  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:23.471  5859  5929 D BtGatt.GattService: current time is 224198011859
03-21 15:51:23.471  5859  5929 D BtGatt.GattService: Batch record : [64, 124, 53, 111, 43, 82, 1, -128, -77, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:23.471  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:23.471  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:23.476  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=52:2B:6F:35:7C:40, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=223748339484}
03-21 15:51:23.476  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:23.476 11109 11117 D ScanRecord: parseFromBytes
,03-21 15:51:23.486 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1,
,03-21 15:51:24.336  3424  4728 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 15:51:24.336  3424  4728 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 15:51:24.336  3424  4728 D BatteryService: online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,03-21 15:51:24.336  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 15:51:24.346  3424  3424 I MotionRecognitionService: Plugged
03-21 15:51:24.346  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-21 15:51:24.346  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 15:51:24.346  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-21 15:51:24.346  3424  4728 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms,
03-21 15:51:24.346  3424  4728 D BatteryService: stay LED for fully charged
,03-21 15:51:24.356  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 15:51:24.356  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:24.356  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 15:51:24.371  5859  5859 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 15:51:24.371  5859  5956 D HeadsetStateMachine: Disconnected process message: 10
,03-21 15:51:24.386  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:24.386  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:24.386  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:24.386  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 15:51:24.451  5859  6005 W bt-btif : bta_dm_acl_change(), event : 2
03-21 15:51:24.451  5859  6005 W bt-btif : bta_dm_acl_change(), event : 4
03-21 15:51:24.451  5859  6005 W bt-btif : scb return value : 1
,03-21 15:51:24.471  5859  6005 D IOP_DB_BT: db_query: id SkipSdpInfo :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:24.471  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:24.491  5859  6005 D IOP_DB_BT: db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 15:51:24.491  5859  6005 D IOP_DB_BT: db_query_add_key: key KEY_LMP_MFCT, value 15,
03-21 15:51:24.491  3424  3618 V AlarmManager: waitForAlarm result :4
03-21 15:51:24.491  5859  6005 D IOP_DB_BT: db_query_add_key: key KEY_LMP_VER, value 7:24841
03-21 15:51:24.491  5859  6005 D IOP_DB_BT: db_query_add_key: key KEY_DIR_ALL, value *
03-21 15:51:24.491  5859  6005 D IOP_DB_BT: db_query_execute: result 1
03-21 15:51:24.491  5859  6005 W bt-btif : bta_dm_acl_change(), event : 0
03-21 15:51:24.491  5859  6005 W bt-btif : info:x10
03-21 15:51:24.496  5859  5929 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-21 15:51:24.496  5859  5929 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
03-21 15:51:24.496  5859  6005 W bt-btif : bta_dm_acl_change(), event : 2
,03-21 15:51:24.496  5859  5859 D BtGatt.ScanManager: awakened up at time 225224
,03-21 15:51:24.501  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,03-21 15:51:24.506  5859  5929 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 15:51:24.511  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:24.511  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:24.511  5859  5929 D BtGatt.GattService: current time is 225237388942
03-21 15:51:24.511  5859  5929 D BtGatt.GattService: Batch record : [64, 124, 53, 111, 43, 82, 1, -128, -69, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:24.511  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:24.511  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:24.511  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=52:2B:6F:35:7C:40, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-69, mTimestampNanos=225037549859}
03-21 15:51:24.511  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:24.511 11109 11118 D ScanRecord: parseFromBytes
,03-21 15:51:24.516 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 15:51:24.521  5859  6005 W bt-sdp  : process_service_search_attr_rsp,
,03-21 15:51:24.731  5859  5929 W bt-btif : btif_dm_ssp_cfm_req_evt
,03-21 15:51:24.741  5859  5929 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,03-21 15:51:24.761  5859  5929 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 15:51:24.761  5859  5929 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-21 15:51:24.766  3424  3452 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 15:51:24.771  5859  5929 E bt-btif : check_cod: remote_cod = 0x5a020c
03-21 15:51:24.771  5859  5929 W bt-btif : btif_dm_ssp_reply: accept=1
,03-21 15:51:24.781  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 15:51:24.781  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 15:51:24.786  5859  5952 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-21 15:51:24.796  3424  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11258737 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{788546f 10059:com.android.settings/1000}
,03-21 15:51:24.801  5859  5952 D BtConfig.SecureMode: isSecureModeOn:false
03-21 15:51:24.801  5859  5952 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-21 15:51:24.801  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-21 15:51:24.801  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
03-21 15:51:24.801  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
03-21 15:51:24.801  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 15:51:24.806  3724  3724 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 15:51:24.816 10059 10059 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 15:51:24.816  3424  4010 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 15:51:24.826  3724  4776 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 15:51:24.836 10207 11614 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 15:51:24.836 10207 10207 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 15:51:24.836  3424  3451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11258737 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{207a2af8 10207:com.sec.android.automotive.drivelink/u0a102}
,03-21 15:51:24.836 10207 10207 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 15:51:24.841 10207 10207 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,03-21 15:51:24.846  3424  3746 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11258737 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{207a2af8 10207:com.sec.android.automotive.drivelink/u0a102}
,03-21 15:51:24.846  3424  4413 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 15:51:24.851 10207 11616 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 15:51:24.851 10207 10207 D [CarModeFW]: ConnectivityManager-handleMessage PAIRING_DEVICES
,03-21 15:51:24.856  3424  4735 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11258737 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{d355f8a 10373:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 15:51:24.866 10373 10373 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 15:51:24.866 10373 10373 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 15:51:24.866 10373 10373 D GMHFPReceiver: jangil::setProperties()
,03-21 15:51:24.871 10373 10373 D GMHFPReceiver: jangil::printBTStatus()
,03-21 15:51:24.871  3424  4413 D SettingsProvider: name = Wearable0001
03-21 15:51:24.871  3424  4413 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 15:51:24.871  3424  4413 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 15:51:24.871  3424  4413 D SettingsProvider: selectionArgs: false
03-21 15:51:24.871  3424  4413 D SettingsProvider: selectionArgs: 10121
03-21 15:51:24.871  3424  4413 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 15:51:24.871  3424  4413 D SettingsProvider: ret = -1
,03-21 15:51:24.876  3424  4413 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-21 15:51:24.881 10373 10373 D GMHFPReceiver: ::::::::Wearable0001::false
03-21 15:51:24.881  3424  3957 D SettingsProvider: name = Wearable0002
03-21 15:51:24.881  3424  3957 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-21 15:51:24.881  3424  3957 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 15:51:24.881  3424  3957 D SettingsProvider: selectionArgs: false
03-21 15:51:24.881  3424  3957 D SettingsProvider: selectionArgs: 10121
03-21 15:51:24.881  3424  3957 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 15:51:24.881  3424  3957 D SettingsProvider: ret = -1
,03-21 15:51:24.886  3424  3957 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-21 15:51:24.886 10373 10373 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 15:51:24.886  3724  3724 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 15:51:24.891  3424  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{11258737 u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{28ab6b8e 4414:com.google.android.gms.persistent/u0a14}
,03-21 15:51:24.906  3724  3724 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 15:51:24.966 10373 10373 D GMHFPReceiver: onServiceConnected() : 1
,03-21 15:51:24.971 10373 10373 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 15:51:24.986  5859  5929 W bt-btif : btif_dm_auth_cmpl_evt
,03-21 15:51:24.991  5859  5929 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-21 15:51:25.006  5859  6005 E bt-btm  : btm_sec_encrypt_change collision_start_time is not 0, it 2147457661
03-21 15:51:25.006  5859  6005 E bt-btm  : return here let's wait the timer is expired...
,03-21 15:51:25.016  5859  5929 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
03-21 15:51:25.021  5859  5952 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-21 15:51:25.026  3424  3959 D SecContentProvider: query(), uri = 4 selection = bluetoothLogForRemote
,03-21 15:51:25.031  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
03-21 15:51:25.031  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 15:51:25.031  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED
03-21 15:51:25.031  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
03-21 15:51:25.031  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
03-21 15:51:25.031  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,03-21 15:51:25.046  5859  5952 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10,
,03-21 15:51:25.051  3724  3724 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 15:51:25.051  3424  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa2dc0e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{788546f 10059:com.android.settings/1000}
,03-21 15:51:25.051  3424  3957 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
03-21 15:51:25.051  3724  4776 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 15:51:25.056 10059 10059 D BluetoothNotiBroadcastReceiver: onReceive
,03-21 15:51:25.056  5859  5952 D BtConfig.SecureMode: isSecureModeOn:false
,03-21 15:51:25.061 10207 11623 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 15:51:25.066  3424  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa2dc0e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{207a2af8 10207:com.sec.android.automotive.drivelink/u0a102}
,03-21 15:51:25.066 10207 10207 D [CarMode]: [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,03-21 15:51:25.066  5859  5952 D HidService: getHidService(): returning com.android.bluetooth.hid.HidService@10c0572c
,03-21 15:51:25.066  3424  3746 D SettingsProvider: name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
03-21 15:51:25.066  3424  3746 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 15:51:25.066  3424  3746 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 15:51:25.066  3424  3746 D SettingsProvider: selectionArgs: false
03-21 15:51:25.066  3424  3746 D SettingsProvider: selectionArgs: 1002
03-21 15:51:25.066  3424  3746 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 15:51:25.071  3424  3746 D SettingsProvider: ret = -1
03-21 15:51:25.071 10207 10207 D [CarMode]: [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
03-21 15:51:25.071  5859  5952 D HidService: Saved priority F8:95:C7:87:3C:51 = -1
,03-21 15:51:25.071  3424  3957 D SettingsProvider: name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
,03-21 15:51:25.071  3424  3957 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 15:51:25.071  3424  3957 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 15:51:25.071  3424  3957 D SettingsProvider: selectionArgs: false
03-21 15:51:25.071  3424  3957 D SettingsProvider: selectionArgs: 1002
03-21 15:51:25.071  3424  3957 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 15:51:25.071  3424  3957 D SettingsProvider: ret = -1
,03-21 15:51:25.071  3424  3733 D SettingsProvider: name = bluetooth_headset_priority_F8:95:C7:87:3C:51
03-21 15:51:25.071  3424  3733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-21 15:51:25.071  3424  4736 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa2dc0e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{207a2af8 10207:com.sec.android.automotive.drivelink/u0a102}
03-21 15:51:25.071  3424  3733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 15:51:25.071  3424  3733 D SettingsProvider: selectionArgs: false
,03-21 15:51:25.071  3424  3733 D SettingsProvider: selectionArgs: 1002
03-21 15:51:25.071  3424  3733 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
03-21 15:51:25.076  3424  3733 D SettingsProvider: ret = -1
03-21 15:51:25.076  5859  5952 I BluetoothBondStateMachine: StableState(): Entering Off State
03-21 15:51:25.076  3424  3733 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 15:51:25.081 10207 11626 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,03-21 15:51:25.086  3424  4736 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa2dc0e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{d355f8a 10373:com.samsung.android.app.watchmanagerstub/u0a121}
,03-21 15:51:25.086 10373 10373 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 15:51:25.086 10373 10373 D GMHFPReceiver: android.bluetooth.device.action.BOND_STATE_CHANGED
03-21 15:51:25.086 10373 10373 D GMHFPReceiver: jangil::setProperties()
,03-21 15:51:25.091 10373 10373 D GMHFPReceiver: jangil::printBTStatus()
,03-21 15:51:25.091  3424  4735 D SettingsProvider: name = Wearable0001
03-21 15:51:25.091  3424  4735 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 15:51:25.091  3424  4735 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 15:51:25.091  3424  4735 D SettingsProvider: selectionArgs: false
03-21 15:51:25.091  3424  4735 D SettingsProvider: selectionArgs: 10121
03-21 15:51:25.091  3424  4735 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 15:51:25.091  3424  4735 D SettingsProvider: ret = -1
03-21 15:51:25.091 10373 10373 D GMHFPReceiver: ::::::::Wearable0001::false
03-21 15:51:25.091  3424  3957 D SettingsProvider: name = Wearable0002
03-21 15:51:25.091  3424  3957 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 15:51:25.091  3424  3957 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 15:51:25.091  3424  3957 D SettingsProvider: selectionArgs: false
03-21 15:51:25.091  3424  3957 D SettingsProvider: selectionArgs: 10121
03-21 15:51:25.091  3424  3957 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,03-21 15:51:25.091  3424  3957 D SettingsProvider: ret = -1
03-21 15:51:25.091 10373 10373 D GMHFPReceiver: ::::::::Wearable0002::false
,03-21 15:51:25.096  3424  3835 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa2dc0e u-1 android.bluetooth.device.action.BOND_STATE_CHANGED} DELIVERED for app ProcessRecord{28ab6b8e 4414:com.google.android.gms.persistent/u0a14}
,03-21 15:51:25.191 10373 10373 D GMHFPReceiver: onServiceConnected() : 1
,03-21 15:51:25.196 10373 10373 D GMHFPReceiver: mBluetoothHeadset = true
,03-21 15:51:25.206  3424  6046 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:10), CUR = 33, LCD = 0
,03-21 15:51:25.516  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:25.526  5859  5859 D BtGatt.ScanManager: awakened up at time 226250
,03-21 15:51:25.531  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:25.536  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 15:51:25.536  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:26.551  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:26.566  5859  5859 D BtGatt.ScanManager: awakened up at time 227291
,03-21 15:51:26.571  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:26.576  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:26.576  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 15:51:27.431  5859  6005 W bt-l2cap: L2CAP - no CCB for conn rsp, LCID: 66 RCID: 67
,03-21 15:51:27.496  5859  6005 W bt-btif : new conn_srvc id:26, app_id:255
03-21 15:51:27.496  5859  6005 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-21 15:51:27.496  5859  6005 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-21 15:51:27.496 11109 11585 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@28ba9a1d,
03-21 15:51:27.501  5859  6005 W bt-btif : new conn_srvc id:26, app_id:1
,03-21 15:51:27.501  5859  6005 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
,03-21 15:51:27.501  5859  6005 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1,
,03-21 15:51:27.501  5859  6005 W bt-btif : bta_dm_pm_ssr:2, lat:1200,
,03-21 15:51:27.521  5859  5960 E BluetoothRemoteDevices: setRfcommConnected true
03-21 15:51:27.526  5859  5869 E BluetoothRemoteDevices: setRfcommConnected true
03-21 15:51:27.526 11109 11592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1540)
03-21 15:51:27.526 11109 11592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1540)
,03-21 15:51:27.531 11109 11585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-21 15:51:27.536 11109 11585 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 15:51:27.546 11109 11592 D BluetoothSocket: getInputStream(): myUserId = 0,
,03-21 15:51:27.551 11109 11585 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 15:51:27.551 11109 11592 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 15:51:27.551 11109 11592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1541)
,03-21 15:51:27.551 11109 11592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1541)
03-21 15:51:27.551 11109 11592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1540)
03-21 15:51:27.551  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:27.551 11109 11585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1542)
03-21 15:51:27.551 11109 11585 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d6a492, channel: 6, state: LISTENING
03-21 15:51:27.551  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:27.551  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:27.551  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:27.551 11109 11585 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1d6a492, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@62b9a48, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@974be63mSocket: android.net.LocalSocket@3c496a60 impl:android.net.LocalSocketImpl@2febbb19 fd:FileDescriptor[93]
03-21 15:51:27.551 11109 11585 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c496a60 impl:android.net.LocalSocketImpl@2febbb19 fd:FileDescriptor[93]
03-21 15:51:27.551 11109 11585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 15:51:27.556 11109 11650 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1541),
03-21 15:51:27.556 11109 11651 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1542)
,03-21 15:51:27.556 11109 11651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1542)
03-21 15:51:27.556 11109 11651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:27.556 11109 11651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1542)
03-21 15:51:27.556 11109 11651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1542
03-21 15:51:27.556 11109 11651 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1542),
03-21 15:51:27.556 11109 11651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:27.556  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:27.556  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:27.556  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:27.556 11109 11109 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:27.556 11109 11585 D BluetoothSocket: bindListen(): myUserId = 0
03-21 15:51:27.556  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:27.556 11109 11585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 15:51:27.556 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-21 15:51:27.556 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 15:51:27.561 11109 11651 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1542)
03-21 15:51:27.561 11109 11585 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
03-21 15:51:27.561 11109 11585 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:27.561 11109 11585 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:27.561 11109 11585 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21eaddbf
03-21 15:51:27.561 11109 11585 D BluetoothSocket: channel: 6
03-21 15:51:27.561 11109 11585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 15:51:27.561 11109 11109 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 15:51:27.566 11109 11109 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 15:51:27.566 11109 11109 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-21 15:51:27.566 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-21 15:51:27.566 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:27.566 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:27.566 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 15:51:27.566 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 15:51:27.566 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 15:51:27.566 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 15:51:27.571  5859  5954 D BtGatt.AdvertiseManager: message : 1
,03-21 15:51:27.571  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:27.571  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:27.571  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:27.571  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-21 15:51:27.571  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:27.571  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:27.576 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:27.576 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:27.576 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-21 15:51:27.576 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:27.576 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:27.576 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:27.576 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:27.576 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:27.576 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 15:51:27.576  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:27.576 11109 11650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1541)
03-21 15:51:27.576  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:27.576  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:27.576  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:27.576 11109 11650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:27.576 11109 11650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1540)
03-21 15:51:27.576 11109 11650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1540)
03-21 15:51:27.576 11109 11650 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1541)
,03-21 15:51:27.581  5859  5871 D BtGatt.GattService: registerClient() - UUID=2f617a9a-d7da-465a-b4a7-5fc3490ea442
,03-21 15:51:27.586  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:27.591  5859  5859 D BtGatt.ScanManager: awakened up at time 228315
,03-21 15:51:27.591  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:27.591  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:27.591  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:27.621  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=2f617a9a-d7da-465a-b4a7-5fc3490ea442, clientIf=7
,03-21 15:51:27.621 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:27.661  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 26
,03-21 15:51:27.661  5859  5954 D BtGatt.AdvertiseManager: message : 0
,03-21 15:51:27.671  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:27.671  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:27.686  5859  5954 D BtGatt.AdvertiseManager: starting advertising,
03-21 15:51:27.686  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:27.691  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-21 15:51:27.701  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:27.711  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 15:51:27.711  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:27.711  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 15:51:27.721 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:27.726  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:27.731  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:27.731  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 11
03-21 15:51:27.731  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:27.731  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:27.736  5859  5955 D BtGatt.ScanManager: stopping BLe Batch,
,03-21 15:51:27.741  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 15:51:27.741  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:27.741  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:27.741  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:27.741  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:27.746  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:27.756 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:27.756 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:27.756 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-21 15:51:27.756 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:27.756 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:27.756 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:27.766  5859  5960 D BtGatt.GattService: registerClient() - UUID=072f58b1-605d-47db-a520-d1aab1116948,
,03-21 15:51:27.811  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=072f58b1-605d-47db-a520-d1aab1116948, clientIf=6
03-21 15:51:27.811 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:27.811  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:27.836  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 33
,03-21 15:51:27.841 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-21 15:51:27.841  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:27.841  5859  5955 D BtGatt.ScanManager: isFilteringSupported
,03-21 15:51:27.841  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 15:51:27.841 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:27.841  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:27.841  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
,03-21 15:51:27.841  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 15:51:27.846  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:27.846  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:27.846  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:27.846  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:27.846  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:27.846  5859  5955 D BtGatt.ScanManager: set filter index= 12 for clientIf= 6
03-21 15:51:27.846  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:27.846  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:27.851  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 15:51:27.851 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:27.851 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 15:51:27.851 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 15:51:27.851 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:27.851 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 15:51:27.851 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:27.851  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:27.851  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:27.851 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:27.851 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:27.851 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
03-21 15:51:27.851  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:27.851  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:27.856  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:27.856  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:27.856  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:27.856  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:27.861  5859  5871 D BtGatt.GattService: registerClient() - UUID=3da96ac3-d7e1-40bf-8f5b-93533ca80e9e
,03-21 15:51:27.901  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=3da96ac3-d7e1-40bf-8f5b-93533ca80e9e, clientIf=7
,03-21 15:51:27.901 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:27.916  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 27
,03-21 15:51:27.916  5859  5954 D BtGatt.AdvertiseManager: message : 0
03-21 15:51:27.916  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:27.916  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:27.916  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:27.916  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:27.921  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:27.921  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:27.921  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0,
03-21 15:51:27.921  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:27.921  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 15:51:27.921 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 15:51:27.926  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
,03-21 15:51:27.931  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:27.931  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 12
03-21 15:51:27.931  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:27.931  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:27.931  5859  5955 D BtGatt.ScanManager: stopping BLe Batch,
03-21 15:51:27.931  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 15:51:27.936  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:27.936  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:27.936  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
03-21 15:51:27.936  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 15:51:27.936  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:27.936 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:27.936 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-21 15:51:27.936 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:27.936 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:27.936 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:27.941 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:27.946  5859  5871 D BtGatt.GattService: registerClient() - UUID=db918a6e-a044-4af8-afbd-ad952747ee9d,
,03-21 15:51:27.986  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=db918a6e-a044-4af8-afbd-ad952747ee9d, clientIf=6,
,03-21 15:51:27.986 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,03-21 15:51:27.991  5859  5869 D BtGatt.GattService: start scan with filters,
,03-21 15:51:28.021  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 34
,03-21 15:51:28.021  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:28.021  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:28.021  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:28.026  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:28.026  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:28.026  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:28.026  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:28.026  5859  5955 D BtGatt.ScanManager: set filter index= 13 for clientIf= 6
03-21 15:51:28.031  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:28.031  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:28.031  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:28.031  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:28.036  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:28.036  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:28.036  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:28.036  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:28.036 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
,03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:,
03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 15:51:28.041 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 15:51:28.041  5859  5954 D BtGatt.AdvertiseManager: message : 1
,03-21 15:51:28.041  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:28.041  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 15:51:28.046  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
03-21 15:51:28.046  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:28.046  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:28.051  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:28.051 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:28.051 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 15:51:28.056 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 15:51:28.056 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:28.056 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
,03-21 15:51:28.056 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:28.056 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:28.056 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:28.056 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 15:51:28.061  5859  5960 D BtGatt.GattService: registerClient() - UUID=4fe730a4-8e34-45a0-8996-1c50835520f8
,03-21 15:51:28.086 11109 11120 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34369ce, channel: 6, state: CLOSED
,03-21 15:51:28.086 11109 11120 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35b7ec00, channel: 6, state: CLOSED
,03-21 15:51:28.086 11109 11120 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c673b18, channel: 6, state: CLOSED
,03-21 15:51:28.091 11109 11120 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a7f15a9, channel: 6, state: CLOSED
,03-21 15:51:28.091 11109 11120 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d6a492, channel: 6, state: CLOSED
,03-21 15:51:28.106  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=4fe730a4-8e34-45a0-8996-1c50835520f8, clientIf=7
,03-21 15:51:28.106 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:28.116  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 28
,03-21 15:51:28.116  5859  5954 D BtGatt.AdvertiseManager: message : 0
03-21 15:51:28.116  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:28.116  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:28.116  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:28.116  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:28.121  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:28.121  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:28.121  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:28.121  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:28.121  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 15:51:28.121 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 15:51:28.126  5859  5960 D BtGatt.GattService: stopScan() - queue size =1
,03-21 15:51:28.126  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:28.126  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 13
03-21 15:51:28.126  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:28.126 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:28.126 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:28.126 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-21 15:51:28.126 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:28.126 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:28.126 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:28.126  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:28.126  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:28.126  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:28.131  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 15:51:28.131  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:28.131  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:28.131  5859  5869 D BtGatt.GattService: registerClient() - UUID=158dc1d2-bdfc-4594-b66e-ab382b692003
03-21 15:51:28.131  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:28.131  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:28.176  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=158dc1d2-bdfc-4594-b66e-ab382b692003, clientIf=6
,03-21 15:51:28.176 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:28.176  5859  5960 D BtGatt.GattService: start scan with filters
,03-21 15:51:28.196  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 35
,03-21 15:51:28.196 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 15:51:28.196 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:28.196  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:28.196  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:28.196  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:28.196 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 15:51:28.196 11109 11109 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1,
03-21 15:51:28.196 11109 11109 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:28.196 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-21 15:51:28.196 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:28.196 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:28.196 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:28.196 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-21 15:51:28.196 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:28.196 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 15:51:28.201 11109 11670 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1543)
03-21 15:51:28.201  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:28.201  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:28.201  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:28.201  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,03-21 15:51:28.201  5859  5955 D BtGatt.ScanManager: set filter index= 14 for clientIf= 6
03-21 15:51:28.201  2871  3410 D EnterpriseController: netId is 0
03-21 15:51:28.201  2871  3410 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-21 15:51:28.201  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:28.201  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:28.201  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:28.201  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:28.206  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:28.206  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:28.211  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:28.211  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:28.211 11109 11670 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 49302
03-21 15:51:28.211 11109 11670 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-21 15:51:28.211 11109 11109 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 15:51:28.211 11109 11670 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 15:51:28.216 11109 11670 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 15:51:28.216 11109 11670 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1543)
03-21 15:51:28.216 11109 11670 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1543)
,03-21 15:51:28.216 11109 11673 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1546, name: Receiver),
03-21 15:51:28.221 11109 11109 D BluetoothSocket: getOutputStream(): myUserId = 0
03-21 15:51:28.221 11109 11672 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1545, name: Sender)
,03-21 15:51:28.221 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 15:51:28.221 11109 11109 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-21 15:51:28.221 11109 11674 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1544)
,03-21 15:51:28.221 11109 11674 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35544
,03-21 15:51:28.226 11109 11674 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-21 15:51:28.226 11109 11674 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 35544 (peer ID: F8:95:C7:87:3C:51)
,03-21 15:51:28.226 11109 11674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-21 15:51:28.231 11109 11194 I jxcore-log: INFO testThaliMobileNative: 
03-21 15:51:28.231 11109 11194 I jxcore-log: 
,03-21 15:51:28.231 11109 11194 I jxcore-log: ok 157 Must have listeningPort
03-21 15:51:28.231 11109 11194 I jxcore-log: 
,03-21 15:51:28.231 11109 11194 I jxcore-log: ok 158 listeningPort must be a number
03-21 15:51:28.231 11109 11194 I jxcore-log: 
,03-21 15:51:28.231 11109 11194 I jxcore-log: ok 159 Connection must have clientPort
03-21 15:51:28.231 11109 11194 I jxcore-log: 
,03-21 15:51:28.231 11109 11194 I jxcore-log: ok 160 clientPort must be a number
03-21 15:51:28.231 11109 11194 I jxcore-log: 
,03-21 15:51:28.236 11109 11194 I jxcore-log: ok 161 Connection must have serverPort
03-21 15:51:28.236 11109 11194 I jxcore-log: 
,03-21 15:51:28.236 11109 11194 I jxcore-log: ok 162 serverPort must be a number
03-21 15:51:28.236 11109 11194 I jxcore-log: 
,03-21 15:51:28.236 11109 11194 I jxcore-log: ok 163 forward connection must have clientPort == 0
03-21 15:51:28.236 11109 11194 I jxcore-log: 
,03-21 15:51:28.236 11109 11194 I jxcore-log: ok 164 forward connection must have serverPort == 0
03-21 15:51:28.236 11109 11194 I jxcore-log: 
,03-21 15:51:28.251 11109 11194 I jxcore-log: # setup
03-21 15:51:28.251 11109 11194 I jxcore-log: 
,03-21 15:51:28.416 11109 11672 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1545, thread name: Sender),
,03-21 15:51:28.416 11109 11672 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read,
03-21 15:51:28.416 11109 11672 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read,
,03-21 15:51:28.416 11109 11672 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1543,
03-21 15:51:28.416 11109 11672 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1543)
03-21 15:51:28.416 11109 11672 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1773efd5, channel: 6, state: CONNECTED,
03-21 15:51:28.416 11109 11672 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1773efd5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@232e33ea, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f7996dbmSocket: android.net.LocalSocket@3b1e2578 impl:android.net.LocalSocketImpl@e10b451 fd:FileDescriptor[92],
03-21 15:51:28.416 11109 11672 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3b1e2578 impl:android.net.LocalSocketImpl@e10b451 fd:FileDescriptor[92],
03-21 15:51:28.421 11109 11673 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1546, thread name: Receiver): bt socket closed, read return: -1
,03-21 15:51:28.421 11109 11673 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1546, name: Receiver),
03-21 15:51:28.421  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:28.421  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:28.421  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:28.421  5859  6005 D IOP_DB_BT: db_query: result 1,
03-21 15:51:28.421 11109 11672 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1773efd5, channel: 6, state: CLOSED
03-21 15:51:28.421 11109 11672 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1773efd5, channel: 6, state: CLOSED
03-21 15:51:28.421 11109 11672 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed,
03-21 15:51:28.421 11109 11672 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...,
03-21 15:51:28.421 11109 11672 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1546
03-21 15:51:28.421 11109 11672 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-21 15:51:28.421 11109 11672 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1545
03-21 15:51:28.421 11109 11672 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1543),
,03-21 15:51:28.421 11109 11672 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1543)
03-21 15:51:28.421 11109 11672 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-21 15:51:28.426 11109 11672 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1545, name: Sender)
,03-21 15:51:28.441 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
03-21 15:51:28.441 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 15:51:28.441 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 15:51:28.441 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:28.446  5859  5871 D BtGatt.GattService: stopScan() - queue size =1,
03-21 15:51:28.446  5859  5955 D BtGatt.ScanManager: filter size is 1
,03-21 15:51:28.446  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 14,
03-21 15:51:28.446  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-21 15:51:28.446  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 15:51:28.446  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:28.446  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:28.446  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 15:51:28.451  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:28.451  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:28.451  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,03-21 15:51:28.451  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:28.456 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:28.456 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:28.456 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-21 15:51:28.456 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
03-21 15:51:28.456 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 15:51:28.456 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:28.456 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 15:51:28.456 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only,
03-21 15:51:28.456 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:28.471 11109 11194 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 15:51:28.471 11109 11194 I jxcore-log: 
,03-21 15:51:28.471 11109 11194 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 15:51:28.471 11109 11194 I jxcore-log: 
,03-21 15:51:28.471 11109 11194 I jxcore-log: ok 165 Should be able to call stopListeningForAdvertisments in teardown
03-21 15:51:28.471 11109 11194 I jxcore-log: 
,03-21 15:51:28.476  5859  6005 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
03-21 15:51:28.476  5859  6005 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-21 15:51:28.476 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:28.476 11109 11194 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:28.476 11109 11194 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1544)
,03-21 15:51:28.476 11109 11194 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1544)
03-21 15:51:28.476 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bb3a4b6, channel: 7, state: CONNECTED
,03-21 15:51:28.476 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1bb3a4b6, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2270c5b7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28cc2124mSocket: android.net.LocalSocket@16db448d impl:android.net.LocalSocketImpl@1c4d5642 fd:FileDescriptor[111]
03-21 15:51:28.476 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@16db448d impl:android.net.LocalSocketImpl@1c4d5642 fd:FileDescriptor[111]
,03-21 15:51:28.481 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bb3a4b6, channel: 7, state: CLOSED
,03-21 15:51:28.481 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bb3a4b6, channel: 7, state: CLOSED
03-21 15:51:28.481 11109 11194 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
,03-21 15:51:28.481 11109 11194 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1544)
03-21 15:51:28.481 11109 11194 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1544)
,03-21 15:51:28.481 11109 11674 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1544)
,03-21 15:51:28.481 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-21 15:51:28.486 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 15:51:28.486 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 15:51:28.486 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-21 15:51:28.486 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16420653, channel: 6, state: LISTENING
,03-21 15:51:28.486 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16420653, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21eaddbf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f3c2b90mSocket: android.net.LocalSocket@13449c89 impl:android.net.LocalSocketImpl@36de948e fd:FileDescriptor[112]
03-21 15:51:28.486 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@13449c89 impl:android.net.LocalSocketImpl@36de948e fd:FileDescriptor[112]
,03-21 15:51:28.486 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 15:51:28.486 11109 11585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 15:51:28.486 11109 11585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 15:51:28.486 11109 11585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:28.491 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 15:51:28.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 15:51:28.491 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 15:51:28.491 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 15:51:28.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 15:51:28.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:28.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-21 15:51:28.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 15:51:28.491 11109 11194 D BluetoothLeScanner: could not find callback wrapper
,03-21 15:51:28.491 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:28.491 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-21 15:51:28.496  5859  5954 D BtGatt.AdvertiseManager: message : 1
,03-21 15:51:28.496  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:28.496  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
,03-21 15:51:28.501  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1,
03-21 15:51:28.501  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 15:51:28.501  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:28.501  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:28.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:28.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:28.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-21 15:51:28.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:28.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:28.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:28.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:28.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:28.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:28.506 11109 11194 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 15:51:28.506 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:28.506 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:28.506 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:28.506 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:28.506 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:28.506 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:28.506 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:28.506 11109 11194 I jxcore-log: 
,03-21 15:51:28.511 11109 11194 I jxcore-log: ok 166 Should be able to call stopAdvertisingAndListening in teardown
03-21 15:51:28.511 11109 11194 I jxcore-log: 
,03-21 15:51:28.511 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:28.516 11109 11194 I jxcore-log: # 38. Can shift large amounts of data
03-21 15:51:28.516 11109 11194 I jxcore-log: 
,03-21 15:51:28.516 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 15:51:28.516 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:28.516 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:28.521 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-21 15:51:28.521 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:28.521 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:28.521 11109 11194 I jxcore-log: 
,03-21 15:51:28.526 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:28.526 11109 11194 I jxcore-log: 
,03-21 15:51:28.891 11109 11194 I jxcore-log: # teardown
03-21 15:51:28.891 11109 11194 I jxcore-log: 
,03-21 15:51:28.946  3424  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 15:51:29.101  5859  6005 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,03-21 15:51:29.156 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 58263, start advertisements: true
03-21 15:51:29.156 11109 11194 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectabl,e: false
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:29.156 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:29.156 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:29.156 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:29.161 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-21 15:51:29.161 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:29.161 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:29.161 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:29.161  5859  5960 D BtGatt.GattService: registerClient() - UUID=8dfbfc12-d129-4115-937c-a6bb16064170
,03-21 15:51:29.201  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=8dfbfc12-d129-4115-937c-a6bb16064170, clientIf=6
,03-21 15:51:29.206 11109 11118 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:29.206  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:29.216  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 36
,03-21 15:51:29.216 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:29.216 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:29.216 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:29.216 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:29.216 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:29.216 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:29.216 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:29.216 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:29.216 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:29.216 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:29.216 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:29.216 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 15:51:29.216  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:29.216  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:29.216  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:29.221  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
03-21 15:51:29.221  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:29.221  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:29.221  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:29.221  5859  5955 D BtGatt.ScanManager: set filter index= 15 for clientIf= 6
,03-21 15:51:29.221  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:29.221  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:29.221  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:29.221  5859  5869 D BtGatt.GattService: registerClient() - UUID=5b4dbe19-da53-487f-88dd-8961aaf55a37
03-21 15:51:29.221  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:29.226  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 15:51:29.226  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:29.226  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:29.226  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:29.266  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=5b4dbe19-da53-487f-88dd-8961aaf55a37, clientIf=7,
03-21 15:51:29.266 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:29.281  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 29,
,03-21 15:51:29.281  5859  5954 D BtGatt.AdvertiseManager: message : 0,
,03-21 15:51:29.281  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:29.281  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
03-21 15:51:29.281  5859  5954 D BtGatt.AdvertiseManager: starting advertising
03-21 15:51:29.281  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
03-21 15:51:29.286  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
03-21 15:51:29.286  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
03-21 15:51:29.286  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:29.286  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0,
,03-21 15:51:29.286  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:29.291 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING,
03-21 15:51:29.291 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:29.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:29.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-21 15:51:29.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:29.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:29.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 15:51:29.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 15:51:29.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 15:51:29.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:29.296 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:29.296 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:29.296 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:29.296 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:29.296 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-21 15:51:29.296 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 15:51:29.296 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:29.296 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:29.296 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:29.296 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:29.296 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
,03-21 15:51:29.296 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:29.296 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK,
03-21 15:51:29.301 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:29.301 11109 11194 I jxcore-log: 
03-21 15:51:29.306 11109 11194 I jxcore-log: ok 167 Can call startUpdateAdvertisingAndListening without error
03-21 15:51:29.306 11109 11194 I jxcore-log: 
,03-21 15:51:29.311 11109 11692 D BluetoothSocket: bindListen(): myUserId = 0,
03-21 15:51:29.311 11109 11692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 15:51:29.311 11109 11692 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[93]}
,03-21 15:51:29.311 11109 11692 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:29.311 11109 11692 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:29.311 11109 11692 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26336b9a
03-21 15:51:29.311 11109 11692 D BluetoothSocket: channel: 6
03-21 15:51:29.316 11109 11692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:29.316 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 58263, start advertisements: false,
03-21 15:51:29.316 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:29.316 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-21 15:51:29.316 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:29.321 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK,
,03-21 15:51:29.321 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:29.321 11109 11194 I jxcore-log: 
,03-21 15:51:29.326 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:29.326 11109 11194 I jxcore-log: 
,03-21 15:51:29.326 11109 11194 I jxcore-log: ok 168 Can call startListeningForAdvertisements without error
03-21 15:51:29.326 11109 11194 I jxcore-log: 
,03-21 15:51:30.231  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:30.241  5859  5859 D BtGatt.ScanManager: awakened up at time 230967
,03-21 15:51:30.246  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:30.251  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:30.251  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:30.251  5859  5929 D BtGatt.GattService: current time is 230979487359
03-21 15:51:30.251  5859  5929 D BtGatt.GattService: Batch record : [17, -51, -42, -86, 7, 94, 1, -128, -83, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:30.251  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:30.251  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:30.256  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=5E:07:AA:D6:CD:11, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=230929628901}
03-21 15:51:30.256  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:30.256 11109 11118 D ScanRecord: parseFromBytes
03-21 15:51:30.256 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-21 15:51:30.256 11109 11109 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-21 15:51:30.276 11109 11194 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-21 15:51:30.276 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-21 15:51:30.281 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,03-21 15:51:30.286 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-21 15:51:30.286 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-21 15:51:30.286 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-21 15:51:30.286 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-21 15:51:30.286 11109 11194 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,03-21 15:51:30.286 11109 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1548)
,03-21 15:51:30.291 11109 11700 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
03-21 15:51:30.291 11109 11700 D BluetoothSocket: connect(): myUserId = 0
03-21 15:51:30.291 11109 11700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:30.291  5859  5960 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 15:51:30.296 11109 11700 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,03-21 15:51:30.641  5859  6005 W bt-sdp  : process_service_search_attr_rsp
,03-21 15:51:31.271  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:31.281  5859  5859 D BtGatt.ScanManager: awakened up at time 232009
,03-21 15:51:31.286  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:31.296  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:31.296  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:31.296  5859  5929 D BtGatt.GattService: current time is 232020885485
03-21 15:51:31.296  5859  5929 D BtGatt.GattService: Batch record : [17, -51, -42, -86, 7, 94, 1, -128, -83, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:31.296  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:31.296  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:31.296  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=5E:07:AA:D6:CD:11, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=231921262401}
03-21 15:51:31.296  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:31.296 11109 11117 D ScanRecord: parseFromBytes
03-21 15:51:31.296 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 15:51:31.436  5859  6005 W bt-btif : new conn_srvc id:26, app_id:1
,03-21 15:51:31.436  5859  5869 E BluetoothRemoteDevices: setRfcommConnected true
,03-21 15:51:31.471 11109 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1548)
,03-21 15:51:31.471 11109 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1548),
,03-21 15:51:31.486 11109 11700 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 15:51:31.491 11109 11700 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 15:51:31.496 11109 11700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 1549)
,03-21 15:51:31.496 11109 11700 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 1549)
03-21 15:51:31.496 11109 11700 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1548)
,03-21 15:51:31.496 11109 11718 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1549)
,03-21 15:51:31.566  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.566  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.566  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.571  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:31.706  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.706  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.706  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.706  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.706 11109 11718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 1549)
,03-21 15:51:31.716 11109 11718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-21 15:51:31.721 11109 11718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1548)
03-21 15:51:31.721 11109 11718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 1548)
,03-21 15:51:31.721 11109 11109 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:31.721 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:31.721 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 15:51:31.731 11109 11109 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 15:51:31.736 11109 11109 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 15:51:31.736 11109 11718 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1549)
,03-21 15:51:31.736 11109 11109 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-21 15:51:31.736 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0,
,03-21 15:51:31.741 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:31.741 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:31.741 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 15:51:31.741 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
,03-21 15:51:31.741 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 15:51:31.741 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 15:51:31.751  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:31.751  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7,
03-21 15:51:31.751  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:31.751  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 15:51:31.751  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:31.751  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:31.756  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=7,
,03-21 15:51:31.761 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:31.761 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:31.761 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-21 15:51:31.761 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
03-21 15:51:31.761 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:31.761 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0,
03-21 15:51:31.761 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-21 15:51:31.761 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-21 15:51:31.761 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-21 15:51:31.771  5859  5871 D BtGatt.GattService: registerClient() - UUID=8879ef2d-bc81-4a7f-b863-c345fd5842c7,
,03-21 15:51:31.811  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=8879ef2d-bc81-4a7f-b863-c345fd5842c7, clientIf=7
,03-21 15:51:31.816 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:31.826  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 30
03-21 15:51:31.826  5859  5954 D BtGatt.AdvertiseManager: message : 0
,03-21 15:51:31.826  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:31.826  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:31.826  5859  5954 D BtGatt.AdvertiseManager: starting advertising
03-21 15:51:31.826  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:31.831  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:31.831  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:31.831  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:31.831  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:31.831  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:31.831 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 15:51:31.836  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
,03-21 15:51:31.836  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:31.836  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 15
03-21 15:51:31.836  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:31.836 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:31.836 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:31.836 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:31.836 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:31.836 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-21 15:51:31.836 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:31.836  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:31.836  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:31.836  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:31.841  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:31.841  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:31.841  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:31.841  5859  5960 D BtGatt.GattService: registerClient() - UUID=9bfceecd-8f42-4ef1-ae1a-c0e0eff072b1
,03-21 15:51:31.841  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=2
,03-21 15:51:31.841  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:31.841  5859  5929 D BtGatt.GattService: current time is 232569031818
03-21 15:51:31.841  5859  5929 D BtGatt.GattService: Batch record : [17, -51, -42, -86, 7, 94, 1, -128, -82, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 79, -71, 109, -85, 70, 92, 1, -128, -82, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:31.841  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:31.841  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:31.841  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:31.841  5859  5929 D ScanRecord: parseFromBytes
,03-21 15:51:31.861  5859  6005 W bt-btif : new conn_srvc id:26, app_id:255
,03-21 15:51:31.861 11109 11692 D BluetoothSocket: socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@13cca766
03-21 15:51:31.861  5859  5871 E BluetoothRemoteDevices: setRfcommConnected true
03-21 15:51:31.861 11109 11692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
,03-21 15:51:31.866 11109 11692 D BluetoothSocket: getInputStream(): myUserId = 0
,03-21 15:51:31.866 11109 11692 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 15:51:31.866 11109 11692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 1551)
03-21 15:51:31.866 11109 11692 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28088aa7, channel: 6, state: LISTENING
03-21 15:51:31.871 11109 11692 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28088aa7, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26336b9a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a0c1b54mSocket: android.net.LocalSocket@2e736afd impl:android.net.LocalSocketImpl@2e6bd3f2 fd:FileDescriptor[93]
03-21 15:51:31.871 11109 11692 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e736afd impl:android.net.LocalSocketImpl@2e6bd3f2 fd:FileDescriptor[93]
03-21 15:51:31.871 11109 11692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 15:51:31.871 11109 11724 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 1551)
,03-21 15:51:31.871 11109 11692 D BluetoothSocket: bindListen(): myUserId = 0
03-21 15:51:31.871 11109 11692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:31.871 11109 11692 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,03-21 15:51:31.871 11109 11692 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 15:51:31.871 11109 11692 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-21 15:51:31.871 11109 11692 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3da92a43
03-21 15:51:31.871 11109 11692 D BluetoothSocket: channel: 6
03-21 15:51:31.871 11109 11692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.876 11109 11724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 1551)
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.876 11109 11724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-21 15:51:31.876 11109 11724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 1551)
03-21 15:51:31.876 11109 11724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 1551
03-21 15:51:31.876 11109 11724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 1551)
03-21 15:51:31.876 11109 11724 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:31.876 11109 11724 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 1551)
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.876  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:31.881  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=9bfceecd-8f42-4ef1-ae1a-c0e0eff072b1, clientIf=6
,03-21 15:51:31.881 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:31.881  5859  5869 D BtGatt.GattService: start scan with filters
,03-21 15:51:31.896  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 37
,03-21 15:51:31.896 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:31.896  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:31.896  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-21 15:51:31.896  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 15:51:31.896 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-21 15:51:31.896  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:31.896  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:31.896  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:31.896  5859  5955 D BtGatt.ScanManager: allow scan with filters
,03-21 15:51:31.896  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:31.896  5859  5955 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
03-21 15:51:31.901  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:31.901  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:31.901  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:31.901  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:31.901  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:31.901  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:31.901  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 15:51:31.901  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:31.901  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:31.901  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:31.901  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:31.906  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=7
,03-21 15:51:31.906  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,03-21 15:51:31.906  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:31.906 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:31.906 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 15:51:31.906 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 15:51:31.906 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:31.906 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:31.906 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:31.906 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:31.906 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-21 15:51:31.906 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 15:51:31.911  5859  5871 D BtGatt.GattService: registerClient() - UUID=ec154e0e-1439-4714-b157-0e48a10d5c12
,03-21 15:51:31.956  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=ec154e0e-1439-4714-b157-0e48a10d5c12, clientIf=7
,03-21 15:51:31.956 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:31.971  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 31
,03-21 15:51:31.971  5859  5954 D BtGatt.AdvertiseManager: message : 0
03-21 15:51:31.971  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:31.971  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:31.971  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:31.976  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:31.976  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:31.976  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:31.986  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:31.986  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.986  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:31.986  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:31.986  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 15:51:31.986  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:31.986  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
,03-21 15:51:31.986 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 15:51:31.991  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
,03-21 15:51:31.991  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:31.991  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 3
03-21 15:51:31.991  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 15:51:31.991  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 15:51:31.991  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:31.996  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:31.996 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:31.996 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:31.996 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:31.996 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:31.996 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:31.996 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:31.996  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 15:51:31.996  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:31.996  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:32.001  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:32.001  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:32.001  5859  5869 D BtGatt.GattService: registerClient() - UUID=8eb7f56b-de03-456a-9015-88e8b3dd1ce7,
,03-21 15:51:32.006  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 15:51:32.006  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.006  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:32.006  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.011  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
03-21 15:51:32.011  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.011  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:32.011  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.016  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.046  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=8eb7f56b-de03-456a-9015-88e8b3dd1ce7, clientIf=6
,03-21 15:51:32.046 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:32.046  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:32.061  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 38
,03-21 15:51:32.061 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0,
,03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 15:51:32.061 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:32.061  5859  5955 D BtGatt.ScanManager: handling starting scan
,03-21 15:51:32.061  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:32.061  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:32.066  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:32.066  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:32.066  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:32.066  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:32.066  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:32.066  5859  5955 D BtGatt.ScanManager: allow scan with filters
,03-21 15:51:32.066  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:32.066  5859  5955 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
03-21 15:51:32.066  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:32.066  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:32.066  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 15:51:32.066  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
,03-21 15:51:32.066  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:32.066  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
,03-21 15:51:32.066  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:32.071  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 15:51:32.071  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:32.071  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:32.076 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:32.076 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-21 15:51:32.076 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-21 15:51:32.076 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:32.076 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:32.076 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 15:51:32.076 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:32.076 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
,03-21 15:51:32.076 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 15:51:32.076  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:32.076  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:32.081  5859  5960 D BtGatt.GattService: registerClient() - UUID=764424a4-bd26-4ebc-b0e8-d4a3155c99d1
,03-21 15:51:32.126  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=764424a4-bd26-4ebc-b0e8-d4a3155c99d1, clientIf=7
,03-21 15:51:32.126 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:32.136  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 32
,03-21 15:51:32.136  5859  5954 D BtGatt.AdvertiseManager: message : 0
03-21 15:51:32.136  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:32.136  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:32.136  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:32.136  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:32.141  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:32.141  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:32.141  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:32.141  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:32.141  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 0, TxPowerLevel: 1, isConnectable: false, Timeout: 0
03-21 15:51:32.141 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-21 15:51:32.146  5859  5960 D BtGatt.GattService: stopScan() - queue size =1
,03-21 15:51:32.146  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:32.146  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 4
,03-21 15:51:32.146  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 15:51:32.146  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:32.146  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:32.146  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:32.146 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:32.146 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:32.146 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:32.146 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:32.146 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:32.146 11109 11109 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:32.151  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
03-21 15:51:32.151  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:32.151  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:32.151  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:32.151  5859  5960 D BtGatt.GattService: registerClient() - UUID=9417c089-183c-4182-afb5-518a78816018
,03-21 15:51:32.151  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:32.191  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=9417c089-183c-4182-afb5-518a78816018, clientIf=6
,03-21 15:51:32.191 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:32.191  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:32.211  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 39
,03-21 15:51:32.211  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:32.211  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:32.211  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:32.216  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:32.216  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:32.216  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:32.216  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:32.221  5859  5955 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
03-21 15:51:32.221  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:32.221  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:32.221  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:32.221  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:32.226  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:32.226  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:32.231  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:32.231  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:32.236 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:32.236 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-21 15:51:32.236 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 15:51:32.236 11109 11109 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
,03-21 15:51:32.236 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:32.236 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:32.236 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:32.236 11109 11109 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-21 15:51:32.236 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:32.236 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-21 15:51:32.236 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-21 15:51:32.236 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-21 15:51:32.241 11109 11109 D BluetoothSocket: getInputStream(): myUserId = 0
03-21 15:51:32.246 11109 11109 D BluetoothSocket: getOutputStream(): myUserId = 0
,03-21 15:51:32.246 11109 11109 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-21 15:51:32.246 11109 11109 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
,03-21 15:51:32.251 11109 11738 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1550),
03-21 15:51:32.251 11109 11738 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54623,
03-21 15:51:32.251 11109 11738 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-21 15:51:32.251 11109 11738 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 54623 (peer ID: F8:95:C7:87:3C:51)
03-21 15:51:32.251 11109 11739 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 1552)
03-21 15:51:32.256  2871  3410 D EnterpriseController: netId is 0
,03-21 15:51:32.256  2871  3410 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-21 15:51:32.261 11109 11194 I jxcore-log: INFO testThaliMobileNative: ,
03-21 15:51:32.261 11109 11194 I jxcore-log: 
03-21 15:51:32.261 11109 11194 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-21 15:51:32.261 11109 11194 I jxcore-log: 
,03-21 15:51:32.261 11109 11738 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-21 15:51:32.266 11109 11739 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 58263,
03-21 15:51:32.266 11109 11739 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-21 15:51:32.266 11109 11739 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
,03-21 15:51:32.266 11109 11739 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 15:51:32.266 11109 11739 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 1552)
03-21 15:51:32.266 11109 11739 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 1552)
,03-21 15:51:32.271 11109 11738 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 54623,
03-21 15:51:32.271 11109 11738 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,03-21 15:51:32.271 11109 11738 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 15:51:32.271 11109 11738 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-21 15:51:32.271 11109 11738 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1550)
,03-21 15:51:32.271 11109 11738 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 1550)
,03-21 15:51:32.276 11109 11742 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1554, name: Receiver),
,03-21 15:51:32.281 11109 11741 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1553, name: Sender),
,03-21 15:51:32.281 11109 11743 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1555, name: Sender),
,03-21 15:51:32.281 11109 11744 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1556, name: Receiver)
,03-21 15:51:32.286 11109 11194 I jxcore-log: INFO testThaliMobileNative: forwardSend,
03-21 15:51:32.286 11109 11194 I jxcore-log: 
,03-21 15:51:32.291  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.291  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.291  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:32.291  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.306  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:32.306  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.306  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,03-21 15:51:32.306  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.491  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.491  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.491  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.496  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.511 11109 11194 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 15:51:32.511 11109 11194 I jxcore-log: 
,03-21 15:51:32.556  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.556  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.556  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.556  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.561 11109 11194 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 15:51:32.561 11109 11194 I jxcore-log: 
,03-21 15:51:32.626  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.626  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.631  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.631  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.641 11109 11194 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 15:51:32.641 11109 11194 I jxcore-log: 
,03-21 15:51:32.701  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.701  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.701  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.706  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.716 11109 11194 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 15:51:32.716 11109 11194 I jxcore-log: 
,03-21 15:51:32.766  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.766  5859  6005 D IOP_DB_BT: db_query: result 1
03-21 15:51:32.766  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51
03-21 15:51:32.766  5859  6005 D IOP_DB_BT: db_query: result 1
,03-21 15:51:32.771 11109 11194 I jxcore-log: INFO testThaliMobileNative: forwardData
03-21 15:51:32.771 11109 11194 I jxcore-log: 
,03-21 15:51:32.776 11109 11194 I jxcore-log: ok 169 received should match sent forward
03-21 15:51:32.776 11109 11194 I jxcore-log: 
,03-21 15:51:32.791 11109 11194 I jxcore-log: # setup
03-21 15:51:32.791 11109 11194 I jxcore-log: 
,03-21 15:51:33.231  3424  3618 V AlarmManager: waitForAlarm result :4
,03-21 15:51:33.241  5859  5859 D BtGatt.ScanManager: awakened up at time 233969
,03-21 15:51:33.251  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:33.256  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:33.256  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:33.256  5859  5929 D BtGatt.GattService: current time is 233984477360
,03-21 15:51:33.256  5859  5929 D BtGatt.GattService: Batch record : [-61, 107, -77, -40, 97, 116, 1, -128, -90, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-21 15:51:33.256  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,03-21 15:51:33.256  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:33.261  5859  5929 D BtGatt.GattService: result: ScanResult{mDevice=74:61:D8:B3:6B:C3, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[0, -8, -107, -57, -121, 60, 81]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-90, mTimestampNanos=233484630485},
03-21 15:51:33.261  5859  5929 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null],
,03-21 15:51:33.261 11109 11118 D ScanRecord: parseFromBytes
03-21 15:51:33.261 11109 11109 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
,03-21 15:51:33.686  5859  6005 D IOP_DB_BT: db_query: id DisableSniff :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 15:51:33.686  5859  6005 D IOP_DB_BT: db_query: result 1,
,03-21 15:51:33.686  5859  6005 D IOP_DB_BT: db_query: id ExtendSniffTime :: key KEY_BDADDR, value f8:95:c7:87:3c:51,
,03-21 15:51:33.686  5859  6005 D IOP_DB_BT: db_query: result 1,
03-21 15:51:33.686  5859  6177 W bt-btif : invalid rfc slot id: 14,
,03-21 15:51:33.691 11109 11744 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1556, thread name: Receiver): bt socket closed, read return: -1
03-21 15:51:33.691 11109 11744 E io.jxcore.node.OutgoingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected,
03-21 15:51:33.691 11109 11744 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-21 15:51:33.691 11109 11744 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
,03-21 15:51:33.691 11109 11744 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1550)
03-21 15:51:33.691 11109 11744 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1550)
03-21 15:51:33.691 11109 11744 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d5f3d3e, channel: 7, state: CONNECTED,
,03-21 15:51:33.691 11109 11744 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1d5f3d3e, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@222a279f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27ff80ecmSocket: android.net.LocalSocket@399fcb5 impl:android.net.LocalSocketImpl@1c8def4a fd:FileDescriptor[111]
,03-21 15:51:33.691 11109 11744 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@399fcb5 impl:android.net.LocalSocketImpl@1c8def4a fd:FileDescriptor[111]
03-21 15:51:33.691 11109 11744 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d5f3d3e, channel: 7, state: CLOSED
,03-21 15:51:33.691 11109 11744 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d5f3d3e, channel: 7, state: CLOSED
03-21 15:51:33.691 11109 11744 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 15:51:33.691 11109 11744 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-21 15:51:33.691 11109 11744 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1556
,03-21 15:51:33.691 11109 11744 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-21 15:51:33.691 11109 11744 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1555,
03-21 15:51:33.691 11109 11744 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1550)
03-21 15:51:33.706 11109 11743 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1555, thread name: Sender): Socket closed
,03-21 15:51:33.706 11109 11743 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1555, name: Sender)
03-21 15:51:33.706 11109 11744 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1550)
03-21 15:51:33.706 11109 11744 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-21 15:51:33.706 11109 11744 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1556, name: Receiver),
,03-21 15:51:34.246 11109 11741 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1553, thread name: Sender)
03-21 15:51:34.246 11109 11741 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-21 15:51:34.246 11109 11741 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-21 15:51:34.246 11109 11741 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1552
03-21 15:51:34.246 11109 11741 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1552)
03-21 15:51:34.246 11109 11741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4939ebb, channel: 6, state: CONNECTED
03-21 15:51:34.246 11109 11741 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4939ebb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cd9bfd8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a3aaf31mSocket: android.net.LocalSocket@d43b616 impl:android.net.LocalSocketImpl@32536b97 fd:FileDescriptor[92]
03-21 15:51:34.246 11109 11741 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d43b616 impl:android.net.LocalSocketImpl@32536b97 fd:FileDescriptor[92]
03-21 15:51:34.251 11109 11742 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 1554, thread name: Receiver): bt socket closed, read return: -1
03-21 15:51:34.251 11109 11742 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1554, name: Receiver)
,03-21 15:51:34.256 11109 11741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4939ebb, channel: 6, state: CLOSED,
03-21 15:51:34.256 11109 11741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4939ebb, channel: 6, state: CLOSED
03-21 15:51:34.256 11109 11741 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-21 15:51:34.256 11109 11741 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-21 15:51:34.256 11109 11741 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1554
03-21 15:51:34.256 11109 11741 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-21 15:51:34.256 11109 11741 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 1553
03-21 15:51:34.256 11109 11741 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 1552)
03-21 15:51:34.256 11109 11741 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 1552)
03-21 15:51:34.256 11109 11741 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,03-21 15:51:34.261 11109 11741 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1553, name: Sender),
,03-21 15:51:34.266 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:34.266 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 15:51:34.266 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-21 15:51:34.266 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:34.271  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:34.271  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:34.271  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 5
03-21 15:51:34.271  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:34.271  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:34.271  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
,03-21 15:51:34.276  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,03-21 15:51:34.276  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:34.276  5859  5869 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:34.276  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:34.276  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:34.276  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:34.281  3424  3618 V AlarmManager: waitForAlarm result :4
03-21 15:51:34.281  3424  3618 V AlarmManager: No more alarm at this time.nowELAPSED=235006 batch.start=260719
,03-21 15:51:34.281 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-21 15:51:34.281 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:34.281 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:34.281 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 15:51:34.281 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-21 15:51:34.281 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:34.286 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:34.286 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-21 15:51:34.286 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:34.286 11109 11194 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-21 15:51:34.286 11109 11194 I jxcore-log: 
03-21 15:51:34.286 11109 11194 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed while not in start
03-21 15:51:34.286 11109 11194 I jxcore-log: 
03-21 15:51:34.286 11109 11194 I jxcore-log: ok 170 Should be able to call stopListeningForAdvertisments in teardown
03-21 15:51:34.286 11109 11194 I jxcore-log: 
03-21 15:51:34.291 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:34.291 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-21 15:51:34.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 15:51:34.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 15:51:34.291 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 15:51:34.296 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26170184, channel: 6, state: LISTENING
03-21 15:51:34.296 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26170184, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3da92a43, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a5a0d6dmSocket: android.net.LocalSocket@7bd1da2 impl:android.net.LocalSocketImpl@37d92a33 fd:FileDescriptor[112]
03-21 15:51:34.296 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@7bd1da2 impl:android.net.LocalSocketImpl@37d92a33 fd:FileDescriptor[112]
03-21 15:51:34.296 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-21 15:51:34.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 15:51:34.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-21 15:51:34.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:34.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 15:51:34.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-21 15:51:34.296 11109 11692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 15:51:34.296 11109 11692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 15:51:34.296 11109 11692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:34.296 11109 11194 D BluetoothLeScanner: could not find callback wrapper
,03-21 15:51:34.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:34.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 15:51:34.301  5859  5954 D BtGatt.AdvertiseManager: message : 1
,03-21 15:51:34.301  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:34.301  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:34.301  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:34.306  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0,
03-21 15:51:34.306  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:34.306  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 15:51:34.306 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:34.306 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-21 15:51:34.306 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 15:51:34.306 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:34.306 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:34.306 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:34.306 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:34.306 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:34.311 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:34.311 11109 11194 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-21 15:51:34.311 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:34.311 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:34.311 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:34.311 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 15:51:34.311 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:34.311 11109 11194 I jxcore-log: 
,03-21 15:51:34.316 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:34.321 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-21 15:51:34.321 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:34.321 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:34.321 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 15:51:34.321 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 15:51:34.321 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:34.321 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:34.321 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:34.321 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:34.321 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-21 15:51:34.326 11109 11194 I jxcore-log: ok 171 Should be able to call stopAdvertisingAndListening in teardown
03-21 15:51:34.326 11109 11194 I jxcore-log: 
,03-21 15:51:34.331 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:34.331 11109 11194 I jxcore-log: 
,03-21 15:51:34.331 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:34.331 11109 11194 I jxcore-log: 
,03-21 15:51:34.331 11109 11194 I jxcore-log: # 39. #startListeningForAdvertisements should fail if start not called
03-21 15:51:34.331 11109 11194 I jxcore-log: 
,03-21 15:51:34.441  3424  4047 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 15:51:34.441  3424  4047 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4401, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 15:51:34.441  3424  4047 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
03-21 15:51:34.441  3424  4047 D BatteryService: stay LED for fully charged
03-21 15:51:34.441  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 15:51:34.446  3424  3424 I MotionRecognitionService: Plugged
,03-21 15:51:34.446  3424  3424 D MotionRecognitionService:   cableConnection= 1
03-21 15:51:34.446  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 15:51:34.446  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-21 15:51:34.451  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 15:51:34.451  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:34.451  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 15:51:34.461  5859  5859 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-21 15:51:34.461  5859  5956 D HeadsetStateMachine: Disconnected process message: 10
,03-21 15:51:34.476  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-21 15:51:34.476  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:34.476  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:34.476  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 15:51:34.546 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:34.546 11109 11194 I jxcore-log: 
,03-21 15:51:34.551 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:34.551 11109 11194 I jxcore-log: 
,03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:34.556 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:34.561 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:34.566 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:34.566 11109 11194 I jxcore-log: 
,03-21 15:51:34.566 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:34.566 11109 11194 I jxcore-log: 
,03-21 15:51:34.571 11109 11194 I jxcore-log: # teardown
03-21 15:51:34.571 11109 11194 I jxcore-log: 
,03-21 15:51:34.576 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:34.576 11109 11194 I jxcore-log: 
,03-21 15:51:34.761 11109 11194 I jxcore-log: ok 172 specific error should be returned
03-21 15:51:34.761 11109 11194 I jxcore-log: 
,03-21 15:51:34.766 11109 11194 I jxcore-log: # setup
03-21 15:51:34.766 11109 11194 I jxcore-log: 
,03-21 15:51:34.866 11109 11194 I jxcore-log: # 40. #startUpdateAdvertisingAndListening should fail if start not called
03-21 15:51:34.866 11109 11194 I jxcore-log: 
,03-21 15:51:34.996 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:34.996 11109 11194 I jxcore-log: 
,03-21 15:51:35.001 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:35.001 11109 11194 I jxcore-log: 
,03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:35.011 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:35.016 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:35.021 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:35.021 11109 11194 I jxcore-log: 
,03-21 15:51:35.021 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:35.021 11109 11194 I jxcore-log: 
,03-21 15:51:35.031 11109 11194 I jxcore-log: # teardown
03-21 15:51:35.031 11109 11194 I jxcore-log: 
,03-21 15:51:35.031 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:35.031 11109 11194 I jxcore-log: 
,03-21 15:51:35.086  5859  6005 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
03-21 15:51:35.086  5859  6005 E bt-btif : bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,03-21 15:51:35.151 11109 11194 I jxcore-log: ok 173 specific error should be returned,
03-21 15:51:35.151 11109 11194 I jxcore-log: 
,03-21 15:51:35.156 11109 11194 I jxcore-log: # setup
03-21 15:51:35.156 11109 11194 I jxcore-log: 
,03-21 15:51:35.221  3424  6046 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:12), CUR = 39, LCD = 0
,03-21 15:51:35.266 11109 11194 I jxcore-log: # 41. should be able to call #stopListeningForAdvertisements many times
03-21 15:51:35.266 11109 11194 I jxcore-log: 
,03-21 15:51:35.396 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:35.396 11109 11194 I jxcore-log: 
,03-21 15:51:35.401 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:35.401 11109 11194 I jxcore-log: 
,03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:35.411 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:35.416 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:35.416 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:35.416 11109 11194 I jxcore-log: 
,03-21 15:51:35.421 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:35.421 11109 11194 I jxcore-log: 
,03-21 15:51:35.426 11109 11194 I jxcore-log: # teardown
03-21 15:51:35.426 11109 11194 I jxcore-log: 
,03-21 15:51:35.426 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:35.426 11109 11194 I jxcore-log: 
,03-21 15:51:35.511 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:35.511 11109 11194 I jxcore-log: 
,03-21 15:51:35.516 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 38180
03-21 15:51:35.516 11109 11194 I jxcore-log: 
,03-21 15:51:35.516 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 15:51:35.516 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:35.516 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:35.521 11109 11194 I jxcore-log: ok 174 no errors
03-21 15:51:35.521 11109 11194 I jxcore-log: 
,03-21 15:51:35.526 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 15:51:35.526 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:35.526 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:35.531 11109 11194 I jxcore-log: ok 175 still no errors
03-21 15:51:35.531 11109 11194 I jxcore-log: 
,03-21 15:51:35.536 11109 11194 I jxcore-log: # setup
03-21 15:51:35.536 11109 11194 I jxcore-log: 
,03-21 15:51:35.691 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:35.696 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:35.696 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:35.701 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:35.701 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:35.706 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:35.721 11109 11194 I jxcore-log: # 42. should be able to call #startListeningForAdvertisements many times
03-21 15:51:35.721 11109 11194 I jxcore-log: 
,03-21 15:51:35.841 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:35.841 11109 11194 I jxcore-log: 
,03-21 15:51:35.846 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:35.846 11109 11194 I jxcore-log: 
,03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:35.856 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:35.861 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:35.861 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:35.861 11109 11194 I jxcore-log: 
,03-21 15:51:35.866 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:35.866 11109 11194 I jxcore-log: 
,03-21 15:51:35.871 11109 11194 I jxcore-log: # teardown
03-21 15:51:35.871 11109 11194 I jxcore-log: 
,03-21 15:51:35.871 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:35.871 11109 11194 I jxcore-log: 
,03-21 15:51:35.981 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:35.981 11109 11194 I jxcore-log: 
,03-21 15:51:35.981 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 58584
03-21 15:51:35.981 11109 11194 I jxcore-log: 
,03-21 15:51:35.991 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 58263, start advertisements: false
03-21 15:51:35.991 11109 11194 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectab,le: false
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:35.991 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:35.991 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:35.991 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-21 15:51:35.996 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:35.996 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:35.996 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-21 15:51:36.001  5859  5869 D BtGatt.GattService: registerClient() - UUID=24c07e66-a2a9-4411-8270-b97b6c544eb4
,03-21 15:51:36.041  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=24c07e66-a2a9-4411-8270-b97b6c544eb4, clientIf=6
,03-21 15:51:36.041 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
03-21 15:51:36.041  5859  5960 D BtGatt.GattService: start scan with filters
,03-21 15:51:36.061  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 40
,03-21 15:51:36.061 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:36.061 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:36.061  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:36.061  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:36.061  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:36.061 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:36.061 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:36.061 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:36.061 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:36.061 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 15:51:36.066  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 15:51:36.066  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:36.066  5859  5955 D BtGatt.ScanManager: allow scan with filters
,03-21 15:51:36.066  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:36.066  5859  5955 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
03-21 15:51:36.066 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:36.066 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:36.066 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-21 15:51:36.066 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:36.066  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:36.066  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:36.066  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:36.066 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:36.066  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:36.066 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:36.071  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 15:51:36.071  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:36.071 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:36.071 11109 11194 I jxcore-log: 
03-21 15:51:36.071  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:36.076  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:36.076 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:36.076 11109 11194 I jxcore-log: 
,03-21 15:51:36.076 11109 11194 I jxcore-log: ok 176 no errors
03-21 15:51:36.076 11109 11194 I jxcore-log: 
,03-21 15:51:36.081 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 58263, start advertisements: false
,03-21 15:51:36.081 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:36.081 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:36.081 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:36.081 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:36.086 11109 11194 I jxcore-log: ok 177 still no errors
03-21 15:51:36.086 11109 11194 I jxcore-log: 
,03-21 15:51:36.096 11109 11194 I jxcore-log: # setup
03-21 15:51:36.096 11109 11194 I jxcore-log: 
,03-21 15:51:36.286 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:36.286 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:36.291 11109 11194 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-21 15:51:36.291 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 15:51:36.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 15:51:36.291 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:36.291 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-21 15:51:36.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:36.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:36.296  5859  5960 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:36.296  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:36.296  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 6
03-21 15:51:36.296  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:36.296  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:36.296  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:36.301  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:36.301  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:36.301  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:36.301  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:36.301  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:36.316  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 15:51:36.316 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:36.316 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:36.316 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:36.316 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-21 15:51:36.316 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-21 15:51:36.316 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:36.321 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-21 15:51:36.321 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:36.321 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 15:51:36.321 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
03-21 15:51:36.321 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:36.321 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:36.321 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:36.321 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-21 15:51:36.326 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:36.331 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:36.336 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:36.336 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:36.336 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:36.336 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:36.336 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:36.336 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:36.341 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-21 15:51:36.341 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
03-21 15:51:36.341 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:36.341  3424  3574 W ProcessCpuTracker: Skipping unknown process pid 11786
,03-21 15:51:36.341 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:36.341 11109 11194 I jxcore-log: 
,03-21 15:51:36.341 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:36.341 11109 11194 I jxcore-log: 
,03-21 15:51:36.351 11109 11194 I jxcore-log: # 43. should be able to call #startUpdateAdvertisingAndListening many times
03-21 15:51:36.351 11109 11194 I jxcore-log: 
,03-21 15:51:36.556 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:36.556 11109 11194 I jxcore-log: 
,03-21 15:51:36.556 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:36.556 11109 11194 I jxcore-log: 
,03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:36.566 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:36.571 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:36.576 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:36.576 11109 11194 I jxcore-log: 
,03-21 15:51:36.576 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:36.576 11109 11194 I jxcore-log: 
,03-21 15:51:36.581 11109 11194 I jxcore-log: # teardown
03-21 15:51:36.581 11109 11194 I jxcore-log: 
,03-21 15:51:36.586 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:36.586 11109 11194 I jxcore-log: 
,03-21 15:51:36.776 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:36.776 11109 11194 I jxcore-log: 
,03-21 15:51:36.781 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 49719
03-21 15:51:36.781 11109 11194 I jxcore-log: 
,03-21 15:51:36.786 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 49719, start advertisements: true
,03-21 15:51:36.791 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-21 15:51:36.791 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-21 15:51:36.791 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:36.796 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:36.796 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:36.796 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:36.796 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:36.801  5859  5960 D BtGatt.GattService: registerClient() - UUID=21fa002c-f856-4780-94e6-47d419307db4
,03-21 15:51:36.846  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=21fa002c-f856-4780-94e6-47d419307db4, clientIf=6
03-21 15:51:36.846 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:36.846  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:36.856  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 41
,03-21 15:51:36.856  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:36.856  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:36.856  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:36.861  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
03-21 15:51:36.861  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:36.861  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:36.861  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:36.861  5859  5955 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
03-21 15:51:36.861  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:36.861  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:36.861  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:36.861  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
03-21 15:51:36.866  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
03-21 15:51:36.866  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:36.866 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:36.866 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:36.866 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:36.866 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:36.866 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:36.866 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:36.866 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:36.866 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:36.866  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:36.866  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:36.866 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:36.866 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:36.866 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-21 15:51:36.866 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:36.871  5859  5960 D BtGatt.GattService: registerClient() - UUID=7a1b0de6-55fa-4e0a-b2d9-815929d71afa
,03-21 15:51:36.911  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=7a1b0de6-55fa-4e0a-b2d9-815929d71afa, clientIf=7
,03-21 15:51:36.911 11109 11118 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:36.926  5859  5869 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 33
,03-21 15:51:36.926  5859  5954 D BtGatt.AdvertiseManager: message : 0
03-21 15:51:36.926  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:36.926  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:36.926  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:36.926  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:36.931  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:36.931  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:36.936  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:36.936  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:36.936  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:36.936 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:36.936 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 15:51:36.941 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:36.941 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:36.941 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:36.941 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 15:51:36.941 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 15:51:36.941 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 15:51:36.941 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-21 15:51:36.941 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:36.941 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:36.941 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:36.941 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:36.941 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:36.941 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:36.941 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:36.941 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 15:51:36.941 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:36.941 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:36.941 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-21 15:51:36.941 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:36.946 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 15:51:36.946 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:36.946 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:36.946 11109 11194 I jxcore-log: 
,03-21 15:51:36.951 11109 11798 D BluetoothSocket: bindListen(): myUserId = 0,
03-21 15:51:36.951 11109 11798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-21 15:51:36.951 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:36.951 11109 11194 I jxcore-log: 
,03-21 15:51:36.951 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true},
03-21 15:51:36.951 11109 11194 I jxcore-log: 
03-21 15:51:36.951 11109 11798 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
03-21 15:51:36.951 11109 11798 D BluetoothSocket: bindListen(), new LocalSocket 
,03-21 15:51:36.951 11109 11798 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:36.951 11109 11798 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c28befa
03-21 15:51:36.951 11109 11798 D BluetoothSocket: channel: 6
03-21 15:51:36.951 11109 11798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:36.956 11109 11194 I jxcore-log: ok 178 no errors
03-21 15:51:36.956 11109 11194 I jxcore-log: 
,03-21 15:51:36.961 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 49719, start advertisements: true
,03-21 15:51:36.961 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:36.961 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:36.961 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-21 15:51:36.961 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:36.961 11109 11194 I jxcore-log: ok 179 still no errors
03-21 15:51:36.961 11109 11194 I jxcore-log: 
,03-21 15:51:36.971 11109 11194 I jxcore-log: # setup
03-21 15:51:36.971 11109 11194 I jxcore-log: 
,03-21 15:51:37.181 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:37.181 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-21 15:51:37.181 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-21 15:51:37.181 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 15:51:37.181 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 15:51:37.181 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16e5acab, channel: 6, state: LISTENING
,03-21 15:51:37.186 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16e5acab, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c28befa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31a8cf08mSocket: android.net.LocalSocket@3c24c6a1 impl:android.net.LocalSocketImpl@11b3d0c6 fd:FileDescriptor[111],
,03-21 15:51:37.186 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c24c6a1 impl:android.net.LocalSocketImpl@11b3d0c6 fd:FileDescriptor[111]
,03-21 15:51:37.186 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
,03-21 15:51:37.186 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-21 15:51:37.186 11109 11798 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close,
03-21 15:51:37.186 11109 11798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-21 15:51:37.191 11109 11798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:37.191 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 15:51:37.191 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
03-21 15:51:37.191 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-21 15:51:37.191 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
03-21 15:51:37.191 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:37.191 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
03-21 15:51:37.196 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-21 15:51:37.196 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,03-21 15:51:37.196  5859  5869 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:37.201  5859  5955 D BtGatt.ScanManager: filter size is 1,
,03-21 15:51:37.201  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 7,
03-21 15:51:37.201  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
03-21 15:51:37.201  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:37.201  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:37.201  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=6
03-21 15:51:37.201  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,03-21 15:51:37.201  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:37.206  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:37.211  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:37.211  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:37.211  5859  5929 D BtGatt.GattService: current time is 237935950444
03-21 15:51:37.211  5859  5929 D BtGatt.GattService: Batch record : [82, -119, -32, 55, 24, 124, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,03-21 15:51:37.211  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:37.211  5859  5929 D ScanRecord: parseFromBytes
03-21 15:51:37.211 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-21 15:51:37.211 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:37.211 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-21 15:51:37.211 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-21 15:51:37.211 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-21 15:51:37.211 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 15:51:37.211 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 15:51:37.216  5859  5954 D BtGatt.AdvertiseManager: message : 1
03-21 15:51:37.216  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:37.216  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:37.216  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 15:51:37.216  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:37.216  5859  5929 D BtGatt.GattService: Client app is not null!
,03-21 15:51:37.221  5859  5871 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 15:51:37.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-21 15:51:37.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:37.221 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-21 15:51:37.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:37.221 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:37.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:37.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:37.221 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-21 15:51:37.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:37.221 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:37.221 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:37.221 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:37.221 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:37.221 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:37.221 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 15:51:37.226 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:37.226 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:37.226 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:37.226 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-21 15:51:37.231 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-21 15:51:37.231 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:37.231 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:37.236 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-21 15:51:37.236 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:37.236 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-21 15:51:37.236 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:37.236 11109 11194 I jxcore-log: 
,03-21 15:51:37.241 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:37.241 11109 11194 I jxcore-log: 
,03-21 15:51:37.241 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:37.241 11109 11194 I jxcore-log: 
,03-21 15:51:37.251 11109 11194 I jxcore-log: # 44. should be able to call #stopAdvertisingAndListening many times
03-21 15:51:37.251 11109 11194 I jxcore-log: 
,03-21 15:51:37.476 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:37.476 11109 11194 I jxcore-log: 
,03-21 15:51:37.481 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:37.481 11109 11194 I jxcore-log: 
,03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:37.491 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:37.491 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,03-21 15:51:37.496 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:37.496 11109 11194 I jxcore-log: 
,03-21 15:51:37.501 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:37.501 11109 11194 I jxcore-log: 
,03-21 15:51:37.506 11109 11194 I jxcore-log: # teardown
03-21 15:51:37.506 11109 11194 I jxcore-log: 
,03-21 15:51:37.506 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:37.506 11109 11194 I jxcore-log: 
,03-21 15:51:37.721 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:37.721 11109 11194 I jxcore-log: 
,03-21 15:51:37.726 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 40457
03-21 15:51:37.726 11109 11194 I jxcore-log: 
,03-21 15:51:37.731 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:37.731 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:37.731 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:37.736 11109 11194 I jxcore-log: ok 180 no errors
03-21 15:51:37.736 11109 11194 I jxcore-log: 
,03-21 15:51:37.736 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:37.741 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:37.741 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:37.746 11109 11194 I jxcore-log: ok 181 still no errors
03-21 15:51:37.746 11109 11194 I jxcore-log: 
,03-21 15:51:37.751 11109 11194 I jxcore-log: # setup
03-21 15:51:37.751 11109 11194 I jxcore-log: 
,03-21 15:51:37.961 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:37.961 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-21 15:51:37.961 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:37.966 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:37.966 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-21 15:51:37.966 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:37.981 11109 11194 I jxcore-log: # 45. can get the network status before starting
03-21 15:51:37.981 11109 11194 I jxcore-log: 
,03-21 15:51:39.246 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:39.246 11109 11194 I jxcore-log: 
,03-21 15:51:39.251 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:39.251 11109 11194 I jxcore-log: 
,03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:39.261 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:39.266 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:39.266 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:39.266 11109 11194 I jxcore-log: 
,03-21 15:51:39.271 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:39.271 11109 11194 I jxcore-log: 
,03-21 15:51:39.276 11109 11194 I jxcore-log: # teardown
03-21 15:51:39.276 11109 11194 I jxcore-log: 
,03-21 15:51:39.281 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:39.281 11109 11194 I jxcore-log: 
,03-21 15:51:39.521 11109 11194 I jxcore-log: ok 182 network status should have certain non-empty properties
03-21 15:51:39.521 11109 11194 I jxcore-log: 
,03-21 15:51:39.526 11109 11194 I jxcore-log: # setup
03-21 15:51:39.526 11109 11194 I jxcore-log: 
,03-21 15:51:39.826  5859  6005 E bt-btm  : Reset sec_bd_name and name flag. (BR/EDR link)
03-21 15:51:39.826  5859  6005 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
03-21 15:51:39.826  5859  6005 W bt-btif : bta_dm_acl_change(), event : 1
,03-21 15:51:39.826  5859  6005 W bt-btif : bta_dm_acl_change(), event : 2
03-21 15:51:39.831  5859  5929 E BluetoothRemoteDevices: aclStateChangeCallback: State:DisConnected to Device:F8:95:C7:87:3C:XX,
03-21 15:51:39.856  5859  5929 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 15:51:39.856  3724  3724 D KeyguardViewMediator: Received android.bluetooth.device.action.ACL_DISCONNECTED
,03-21 15:51:39.871  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive,
03-21 15:51:39.871  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.device.action.ACL_DISCONNECTED
03-21 15:51:39.871  3424  3424 D KnoxKeyguardUpdateMonitor: BroadcastReceiver ACTION_ACL_DISCONNECTED
,03-21 15:51:39.881  3424  3574 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ff64d96 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{365c2582 5859:com.android.bluetooth/1002}
,03-21 15:51:39.891  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6b338e6
03-21 15:51:39.896  3424  4011 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-21 15:51:39.891  5859  5859 D BtConfig.SecureMode: isSecureModeOn:false
03-21 15:51:39.891  3424  4010 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-21 15:51:39.901  3724  3724 D KeyguardViewMediator: isGear1: device is not B1!
03-21 15:51:39.901  5859  5859 I BluetoothPbapService: action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,03-21 15:51:39.906  3424  4413 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:39.906  3424  4413 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:39.906  3424  4413 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:39.906  3424  4413 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:39.931 11826 11826 E Zygote  : MountEmulatedStorage()
,03-21 15:51:39.931 11826 11826 E Zygote  : v2
03-21 15:51:39.931 11826 11826 I libpersona: KNOX_SDCARD checking this for 10036
03-21 15:51:39.931 11826 11826 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:39.931  3424  4413 I ActivityManager: Start proc 11826:com.sec.android.app.shealth/u0a36 for broadcast-3 com.sec.android.app.shealth/com.samsung.android.app.shealth.tracker.weight.receiver.TrackerWeightReceiver
03-21 15:51:39.936 11826 11826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:39.936 11826 11826 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:39.936 11826 11826 E Zygote  : accessInfo : 0
,03-21 15:51:39.936 11826 11826 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-21 15:51:39.936  3424  3959 D ActivityManager: startService callerProcessName:com.sec.android.automotive.drivelink, calleePkgName: com.sec.android.automotive.drivelink
,03-21 15:51:39.946 10207 11838 V [CarModeFW]: BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,03-21 15:51:39.951 10207 10207 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,03-21 15:51:39.951 10207 10207 D [CarModeFW]: ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,03-21 15:51:39.956 10207 10207 D [CarModeFW]: ConnectivityManager-Paired Devices list is empty
,03-21 15:51:39.956 10207 10207 E [CarMode]: [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,03-21 15:51:39.961 11826 11826 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:39.961 11826 11826 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:39.971  3424  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ff64d96 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3f7a2504 11826:com.sec.android.app.shealth/u0a36}
,03-21 15:51:39.981 11826 11826 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 15:51:40.076 11826 11826 D HealthConsole: Service for HealthDataConsole is connected
,03-21 15:51:40.081  3424  3733 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ff64d96 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3f7a2504 11826:com.sec.android.app.shealth/u0a36}
,03-21 15:51:40.101 11826 11826 D HealthConsole: Service for HealthDataConsole is connected
,03-21 15:51:40.106  3424  4735 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ff64d96 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{3f7a2504 11826:com.sec.android.app.shealth/u0a36}
,03-21 15:51:40.116  3424  3451 I ActivityManager: Killing 10086:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): emptyCount ##31
,03-21 15:51:40.121  3424  3451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3ff64d96 u0 android.bluetooth.device.action.ACL_DISCONNECTED} DELIVERED for app ProcessRecord{1b96e12 4112:com.google.android.googlequicksearchbox:search/u0a64}
,03-21 15:51:40.146  4112  4112 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-21 15:51:40.146  4112  4112 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-21 15:51:40.456 11109 11194 I jxcore-log: # 46. error returned with bad router
03-21 15:51:40.456 11109 11194 I jxcore-log: 
,03-21 15:51:40.706 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:40.706 11109 11194 I jxcore-log: 
,03-21 15:51:40.716 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:40.716 11109 11194 I jxcore-log: 
,03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:40.721 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:40.726 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:40.731 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:40.731 11109 11194 I jxcore-log: 
,03-21 15:51:40.736 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:40.736 11109 11194 I jxcore-log: 
,03-21 15:51:40.736 11109 11194 I jxcore-log: # teardown
03-21 15:51:40.736 11109 11194 I jxcore-log: 
,03-21 15:51:40.741 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:40.741 11109 11194 I jxcore-log: 
,03-21 15:51:40.881 11109 11194 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-21 15:51:40.881 11109 11194 I jxcore-log: 
,03-21 15:51:40.886 11109 11194 I jxcore-log: ok 183 specific error expected
03-21 15:51:40.886 11109 11194 I jxcore-log: 
,03-21 15:51:40.891 11109 11194 I jxcore-log: # setup
03-21 15:51:40.891 11109 11194 I jxcore-log: 
,03-21 15:51:41.996 11109 11194 I jxcore-log: # 47. all services are stopped when we call stop
03-21 15:51:41.996 11109 11194 I jxcore-log: 
,03-21 15:51:42.521 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:42.521 11109 11194 I jxcore-log: 
,03-21 15:51:42.521 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:42.521 11109 11194 I jxcore-log: 
,03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:42.531 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:42.536 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:42.541 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:42.541 11109 11194 I jxcore-log: 
,03-21 15:51:42.541 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:42.541 11109 11194 I jxcore-log: 
,03-21 15:51:42.551 11109 11194 I jxcore-log: # teardown
03-21 15:51:42.551 11109 11194 I jxcore-log: 
,03-21 15:51:42.551 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:42.551 11109 11194 I jxcore-log: 
,03-21 15:51:43.181 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:43.181 11109 11194 I jxcore-log: 
,03-21 15:51:43.186 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 40903
03-21 15:51:43.186 11109 11194 I jxcore-log: 
,03-21 15:51:43.191 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 49719, start advertisements: false
,03-21 15:51:43.196 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:43.196 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:43.196 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-21 15:51:43.196 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-21 15:51:43.196 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:43.201 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:43.201  5859  5960 D BtGatt.GattService: registerClient() - UUID=fe2d2073-3081-4a34-9495-4a320aca0a28
,03-21 15:51:43.246  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=fe2d2073-3081-4a34-9495-4a320aca0a28, clientIf=6
03-21 15:51:43.246 11109 11118 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:43.246  5859  5871 D BtGatt.GattService: start scan with filters
,03-21 15:51:43.256  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 42
,03-21 15:51:43.256  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:43.256  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:43.256  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
,03-21 15:51:43.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:43.261 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:43.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:43.261 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:43.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:43.261 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:43.261 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-21 15:51:43.266  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 15:51:43.266  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:43.266  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:43.266  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:43.266  5859  5955 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
03-21 15:51:43.271  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
03-21 15:51:43.271  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:43.271  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:43.271  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:43.271  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
03-21 15:51:43.271  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:43.276  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:43.276  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:43.281 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:43.281 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:43.281 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-21 15:51:43.281 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:43.281 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-21 15:51:43.281 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
,03-21 15:51:43.286 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-21 15:51:43.286 11109 11194 I jxcore-log: 
,03-21 15:51:43.286 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:43.286 11109 11194 I jxcore-log: 
,03-21 15:51:43.291 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 40903, start advertisements: true
,03-21 15:51:43.291 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:43.291 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:43.291 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:43.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:43.296 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-21 15:51:43.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:43.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:43.296 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
03-21 15:51:43.296 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:43.296 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:43.296 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 15:51:43.301  5859  5869 D BtGatt.GattService: registerClient() - UUID=38edfbf9-789e-45d5-ab5d-f2acad049404
,03-21 15:51:43.341  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=38edfbf9-789e-45d5-ab5d-f2acad049404, clientIf=7
,03-21 15:51:43.341 11109 11117 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:43.356  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 34
,03-21 15:51:43.356  5859  5954 D BtGatt.AdvertiseManager: message : 0
03-21 15:51:43.361  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:43.361  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:43.361  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:43.361  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:43.366  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:43.366  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:43.371  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
,03-21 15:51:43.371  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:43.371  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
03-21 15:51:43.371 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:43.371 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:43.371 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-21 15:51:43.371 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-21 15:51:43.371 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:43.371 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:43.371 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-21 15:51:43.376 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:43.376 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:43.376 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:43.376 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:43.376 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:43.376 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-21 15:51:43.376 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 15:51:43.376 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 15:51:43.376 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:43.376 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:43.376 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:43.376 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:43.376 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-21 15:51:43.381 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:43.381 11109 11194 I jxcore-log: 
03-21 15:51:43.381 11109 11888 D BluetoothSocket: bindListen(): myUserId = 0
03-21 15:51:43.381 11109 11888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:43.386 11109 11888 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,03-21 15:51:43.386 11109 11888 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:43.386 11109 11888 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:43.386 11109 11888 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@308c3352
03-21 15:51:43.386 11109 11888 D BluetoothSocket: channel: 6
03-21 15:51:43.386 11109 11888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:43.391 11109 11194 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-21 15:51:43.391 11109 11194 I jxcore-log: 
,03-21 15:51:43.401 11109 11194 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-21 15:51:43.401 11109 11194 I jxcore-log: 
,03-21 15:51:43.406 11109 11194 I jxcore-log: DEBUG createNativeListener: new mux
03-21 15:51:43.406 11109 11194 I jxcore-log: 
,03-21 15:51:43.411 11109 11194 I jxcore-log: ok 184 connection to servers manager should succeed after starting
03-21 15:51:43.411 11109 11194 I jxcore-log: 
,03-21 15:51:43.431 11109 11194 I jxcore-log: ok 185 connection to router server should succeed after starting
03-21 15:51:43.431 11109 11194 I jxcore-log: 
,03-21 15:51:43.436 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-21 15:51:43.436 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-21 15:51:43.436 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-21 15:51:43.436 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-21 15:51:43.436 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,03-21 15:51:43.436 11109 11194 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26c10623, channel: 6, state: LISTENING
03-21 15:51:43.436 11109 11194 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26c10623, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@308c3352, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32207720mSocket: android.net.LocalSocket@3edea8d9 impl:android.net.LocalSocketImpl@d16329e fd:FileDescriptor[111]
03-21 15:51:43.436 11109 11194 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3edea8d9 impl:android.net.LocalSocketImpl@d16329e fd:FileDescriptor[111]
,03-21 15:51:43.441 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-21 15:51:43.441 11109 11888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-21 15:51:43.441 11109 11888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-21 15:51:43.441 11109 11888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-21 15:51:43.441 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-21 15:51:43.441 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-21 15:51:43.441 11109 11109 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-21 15:51:43.441 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-21 15:51:43.441 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-21 15:51:43.441 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-21 15:51:43.441 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-21 15:51:43.441 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-21 15:51:43.446 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-21 15:51:43.446  5859  5871 D BtGatt.GattService: stopScan() - queue size =1,
03-21 15:51:43.446  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:43.446  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 8
,03-21 15:51:43.446  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,03-21 15:51:43.446  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
03-21 15:51:43.446  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:43.451  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:43.451  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:43.451  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
03-21 15:51:43.451  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
03-21 15:51:43.451  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,03-21 15:51:43.456  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-21 15:51:43.461 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-21 15:51:43.461 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:43.461 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
03-21 15:51:43.461 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-21 15:51:43.461 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING],
03-21 15:51:43.461 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:43.461 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-21 15:51:43.461  5859  5954 D BtGatt.AdvertiseManager: message : 1,
03-21 15:51:43.461  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:43.461  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7,
,03-21 15:51:43.466  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
03-21 15:51:43.466  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:43.466  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:43.466  5859  5960 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 15:51:43.471 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-21 15:51:43.471 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-21 15:51:43.471 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-21 15:51:43.471 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-21 15:51:43.471 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-21 15:51:43.471 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
,03-21 15:51:43.471 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-21 15:51:43.471 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-21 15:51:43.471 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 15:51:43.471 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:43.471 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-21 15:51:43.471 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-21 15:51:43.471 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-21 15:51:43.471 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:43.471 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-21 15:51:43.481 11109 11109 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-21 15:51:43.486 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-21 15:51:43.491 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-21 15:51:43.491 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-21 15:51:43.496 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-21 15:51:43.496 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-21 15:51:43.496 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-21 15:51:43.496 11109 11194 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-21 15:51:43.496 11109 11194 I jxcore-log: 
,03-21 15:51:43.501 11109 11194 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-21 15:51:43.501 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-21 15:51:43.501 11109 11194 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-21 15:51:43.506 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-21 15:51:43.506 11109 11194 I jxcore-log: 
,03-21 15:51:43.506 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:43.506 11109 11194 I jxcore-log: 
,03-21 15:51:43.506 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-21 15:51:43.506 11109 11194 I jxcore-log: 
,03-21 15:51:43.516 11109 11194 I jxcore-log: ok 186 is stopped after calling stop
03-21 15:51:43.516 11109 11194 I jxcore-log: 
,03-21 15:51:43.526 11109 11194 I jxcore-log: ok 187 connection to servers manager should fail after stopping
03-21 15:51:43.526 11109 11194 I jxcore-log: 
,03-21 15:51:43.531 11109 11194 I jxcore-log: ok 188 connection to router server should fail after stopping
03-21 15:51:43.531 11109 11194 I jxcore-log: 
,03-21 15:51:43.541 11109 11194 I jxcore-log: # setup
03-21 15:51:43.541 11109 11194 I jxcore-log: 
,03-21 15:51:44.376 11109 11194 I jxcore-log: # 48. make sure terminateConnection is properly hooked up
03-21 15:51:44.376 11109 11194 I jxcore-log: 
,03-21 15:51:44.561  3424  3451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 15:51:44.561  3424  3451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303759, invalid charger:0
03-21 15:51:44.561  3424  3451 D BatteryService: online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
03-21 15:51:44.561  3424  3424 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 15:51:44.566  3424  3451 D BatteryService: stay LED for fully charged
,03-21 15:51:44.571  3424  3424 I MotionRecognitionService: Plugged
03-21 15:51:44.571  3424  3424 D MotionRecognitionService:   cableConnection= 1,
03-21 15:51:44.571  3424  3424 D MotionRecognitionService: setPowerConnected | current backoffstate  = 0 , state =0
03-21 15:51:44.571  3424  3424 D MotionRecognitionService: skip setTransmitPower. 
,03-21 15:51:44.581  3724  3724 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-21 15:51:44.581  3724  3724 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:44.581  3724  3724 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 15:51:44.601  5859  5859 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 15:51:44.606  5859  5956 D HeadsetStateMachine: Disconnected process message: 10
,03-21 15:51:44.611  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 15:51:44.611  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:44.611  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 15:51:44.611  3724  3724 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 15:51:44.816  3424  3585 I PowerManagerService: [PWL] Off : 180s ago
,03-21 15:51:45.251  3424  6046 D SSRM:n  : SIOP:: AP = 280, PST = 281 (W:12), CUR = 39, LCD = 0
,03-21 15:51:45.261 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:45.261 11109 11194 I jxcore-log: 
,03-21 15:51:45.266 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:45.266 11109 11194 I jxcore-log: 
,03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:45.276 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:45.276 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:45.281 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:45.281 11109 11194 I jxcore-log: 
,03-21 15:51:45.281 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:45.281 11109 11194 I jxcore-log: 
,03-21 15:51:45.286 11109 11194 I jxcore-log: # teardown
03-21 15:51:45.286 11109 11194 I jxcore-log: 
,03-21 15:51:45.286 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:45.286 11109 11194 I jxcore-log: 
,03-21 15:51:45.511 11109 11194 I jxcore-log: ok 189 called with right arguments,
03-21 15:51:45.511 11109 11194 I jxcore-log: 
,03-21 15:51:45.516 11109 11194 I jxcore-log: # setup
03-21 15:51:45.516 11109 11194 I jxcore-log: 
,03-21 15:51:45.741 11109 11194 I jxcore-log: # 49. make sure terminateListener is properly hooked up
03-21 15:51:45.741 11109 11194 I jxcore-log: 
,03-21 15:51:45.926 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:45.926 11109 11194 I jxcore-log: 
,03-21 15:51:45.931 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:45.931 11109 11194 I jxcore-log: 
,03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:45.941 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:45.941 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:45.946 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:45.946 11109 11194 I jxcore-log: 
,03-21 15:51:45.951 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:45.951 11109 11194 I jxcore-log: 
,03-21 15:51:45.956 11109 11194 I jxcore-log: # teardown
03-21 15:51:45.956 11109 11194 I jxcore-log: 
,03-21 15:51:45.961 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:45.961 11109 11194 I jxcore-log: 
,03-21 15:51:46.236 11109 11194 I jxcore-log: ok 190 called with right arguments
03-21 15:51:46.236 11109 11194 I jxcore-log: 
,03-21 15:51:46.241 11109 11194 I jxcore-log: # setup
03-21 15:51:46.241 11109 11194 I jxcore-log: 
,03-21 15:51:46.376 11109 11194 I jxcore-log: # 50. make sure we actually call kill connections properly
03-21 15:51:46.376 11109 11194 I jxcore-log: 
,03-21 15:51:46.551 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:46.551 11109 11194 I jxcore-log: 
,03-21 15:51:46.551 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:46.551 11109 11194 I jxcore-log: 
,03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:46.561 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:46.566 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:46.571 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:46.571 11109 11194 I jxcore-log: 
,03-21 15:51:46.571 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:46.571 11109 11194 I jxcore-log: 
,03-21 15:51:46.576 11109 11194 I jxcore-log: # teardown
03-21 15:51:46.576 11109 11194 I jxcore-log: 
,03-21 15:51:46.581 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:46.581 11109 11194 I jxcore-log: 
,03-21 15:51:46.726 11109 11194 I jxcore-log: ok 191 specific error expected
03-21 15:51:46.726 11109 11194 I jxcore-log: 
,03-21 15:51:46.731 11109 11194 I jxcore-log: # setup
03-21 15:51:46.731 11109 11194 I jxcore-log: 
,03-21 15:51:46.886 11109 11194 I jxcore-log: # 51. thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
03-21 15:51:46.886 11109 11194 I jxcore-log: 
,03-21 15:51:47.031 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 15:51:47.031 11109 11194 I jxcore-log: 
,03-21 15:51:47.036 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 15:51:47.036 11109 11194 I jxcore-log: 
,03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 15:51:47.046 11109 11194 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 15:51:47.051 11109 11194 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 15:51:47.051 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 15:51:47.051 11109 11194 I jxcore-log: 
,03-21 15:51:47.056 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 15:51:47.056 11109 11194 I jxcore-log: 
,03-21 15:51:47.061 11109 11194 I jxcore-log: # teardown
03-21 15:51:47.061 11109 11194 I jxcore-log: 
,03-21 15:51:47.066 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 15:51:47.066 11109 11194 I jxcore-log: 
,03-21 15:51:47.231 11109 11194 I jxcore-log: DEBUG createNativeListener: creating native server
03-21 15:51:47.231 11109 11194 I jxcore-log: 
,03-21 15:51:47.236 11109 11194 I jxcore-log: DEBUG createNativeListener: listening 34610
03-21 15:51:47.236 11109 11194 I jxcore-log: 
,03-21 15:51:47.246 11109 11194 I io.jxcore.node.ConnectionHelper: start: Port number: 34610, start advertisements: true
,03-21 15:51:47.246 11109 11194 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-21 15:51:47.246 11109 11194 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:47.246 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-21 15:51:47.251 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-21 15:51:47.251 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-21 15:51:47.251 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-21 15:51:47.251 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-21 15:51:47.256  5859  5871 D BtGatt.GattService: registerClient() - UUID=9860f64e-713e-42bd-954e-2aee43876efb
,03-21 15:51:47.301  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=9860f64e-713e-42bd-954e-2aee43876efb, clientIf=6
03-21 15:51:47.301 11109 11117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,03-21 15:51:47.306  5859  5960 D BtGatt.GattService: start scan with filters
,03-21 15:51:47.331  5859  5960 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 43
,03-21 15:51:47.331  5859  5955 D BtGatt.ScanManager: handling starting scan
03-21 15:51:47.331  5859  5955 D BtGatt.ScanManager: isFilteringSupported
03-21 15:51:47.331  5859  5955 D BluetoothAdapter: setting StandAloneBleMode
03-21 15:51:47.331 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-21 15:51:47.331 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-21 15:51:47.331 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-21 15:51:47.331 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-21 15:51:47.331 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false,
03-21 15:51:47.331 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-21 15:51:47.331 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "E0:DB:10:14:E2:C0"
03-21 15:51:47.331 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-21 15:51:47.331 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 E0 DB 10 14 E2 C0
,03-21 15:51:47.331 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:47.331 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -32, -37, 16, 20, -30, -64]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-21 15:51:47.331 11109 11194 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-21 15:51:47.341  5859  5929 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,03-21 15:51:47.341  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:47.341  5859  5869 D BtGatt.GattService: registerClient() - UUID=e7f96fdb-9960-4e7c-8c25-a68a8ec1bbcc
03-21 15:51:47.341  5859  5955 D BtGatt.ScanManager: allow scan with filters
03-21 15:51:47.341  5859  5955 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
03-21 15:51:47.341  5859  5955 D BtGatt.ScanManager: set filter index= 9 for clientIf= 6
,03-21 15:51:47.341  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,03-21 15:51:47.341  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:47.341  5859  5955 D BtGatt.ScanManager: Starting BLE batch scan
03-21 15:51:47.341  5859  5955 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,03-21 15:51:47.346  5859  5929 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,03-21 15:51:47.346  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:47.346  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
03-21 15:51:47.346  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:47.381  5859  5929 D BtGatt.GattService: onClientRegistered() - UUID=e7f96fdb-9960-4e7c-8c25-a68a8ec1bbcc, clientIf=7
,03-21 15:51:47.381 11109 11118 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=7
,03-21 15:51:47.396  5859  5871 D BtGatt.GattService: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 35
,03-21 15:51:47.396  5859  5954 D BtGatt.AdvertiseManager: message : 0
03-21 15:51:47.396  5859  5954 D BtGatt.AdvertiseManager: number of adv instance running0
03-21 15:51:47.396  5859  5954 D BtGatt.AdvertiseManager: size of list is =0
,03-21 15:51:47.396  5859  5954 D BtGatt.AdvertiseManager: starting advertising
,03-21 15:51:47.396  5859  5954 D BtGatt.AdvertiseManager: isStandardAdvfalse
,03-21 15:51:47.401  5859  5929 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=7, status=0
,03-21 15:51:47.401  5859  5954 D BtGatt.AdvertiseManager: starting multi advertising
,03-21 15:51:47.401  5859  5929 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=7, status=0
03-21 15:51:47.401  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
03-21 15:51:47.401  5859  5954 D BtGatt.AdvertiseManager: clientIf: 7, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,03-21 15:51:47.401 11109 11194 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-21 15:51:47.401 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-21 15:51:47.406 11109 11194 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-21 15:51:47.406 11109 11194 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-21 15:51:47.406 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-21 15:51:47.406 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 15:51:47.406 11109 11194 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-21 15:51:47.406 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-21 15:51:47.406 11109 11194 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-21 15:51:47.406 11109 11194 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-21 15:51:47.406 11109 11194 I io.jxcore.node.ConnectionHelper: start: OK
03-21 15:51:47.406 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-21 15:51:47.406 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-21 15:51:47.406 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-21 15:51:47.406 11109 11109 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-21 15:51:47.406 11109 11109 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-21 15:51:47.406 11109 11109 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-21 15:51:47.406 11109 11109 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-21 15:51:47.406 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-21 15:51:47.406 11109 11109 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-21 15:51:47.406 11109 11109 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-21 15:51:47.406 11109 11109 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-21 15:51:47.406 11109 11109 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-21 15:51:47.411 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:47.411 11109 11194 I jxcore-log: 
,03-21 15:51:47.411 11109 11937 D BluetoothSocket: bindListen(): myUserId = 0
03-21 15:51:47.411 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-21 15:51:47.411 11109 11194 I jxcore-log: 
03-21 15:51:47.411 11109 11937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 15:51:47.416 11109 11194 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-21 15:51:47.416 11109 11194 I jxcore-log: 
,03-21 15:51:47.416 11109 11937 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
03-21 15:51:47.416 11109 11937 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 15:51:47.416 11109 11937 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 15:51:47.416 11109 11937 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@baedaaa
03-21 15:51:47.416 11109 11937 D BluetoothSocket: channel: 6
03-21 15:51:47.416 11109 11937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-21 15:51:47.421 11109 11194 I jxcore-log: Uncaught Promise Rejection: {}
03-21 15:51:47.421 11109 11194 I jxcore-log: 
,03-21 15:51:47.426 11109 11194 E jxcore-log: Trace: [TypeError: Mobile.fireIncomingConnectionToPortNumberFailed is not a function]
03-21 15:51:47.426 11109 11194 E jxcore-log:     at $3.prototype.trace@console.js:139:8
03-21 15:51:47.426 11109 11194 E jxcore-log:     at @/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:38:3
03-21 15:51:47.426 11109 11194 E jxcore-log:     at emit@events.js:98:1
03-21 15:51:47.426 11109 11194 E jxcore-log:     at handlers.reject/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/node_modules/lie/lib/index.js:128:11
03-21 15:51:47.426 11109 11194 E jxcore-log:     at nextTick@/data/data/com.test.thalitest/files/www/jxcore/node_modules/immediate/lib/index.js:61:7
03-21 15:51:47.426 11109 11194 E jxcore-log:     at $0a@node.js:917:1
03-21 15:51:47.426 11109 11194 E jxcore-log: 
03-21 15:51:47.426 11109 11194 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
03-21 15:51:47.426 11109 11194 I jxcore-log: 
,03-21 15:51:47.806 11940 11940 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-21 15:51:47.816 11940 11940 D AndroidRuntime: CheckJNI is OFF
,03-21 15:51:47.816 11940 11940 D AndroidRuntime: readGMSProperty: start
03-21 15:51:47.816 11940 11940 D AndroidRuntime: readGMSProperty: already setted!!
03-21 15:51:47.816 11940 11940 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 15:51:47.816 11940 11940 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 15:51:47.816 11940 11940 D AndroidRuntime: readGMSProperty: end
03-21 15:51:47.816 11940 11940 D AndroidRuntime: addProductProperty: start
,03-21 15:51:48.011 11940 11940 E AffinityControl: AffinityControl: registerfunction enter
,03-21 15:51:48.036 11940 11940 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 15:51:48.051  3424  3452 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 15:51:48.051  3424  3452 D PackageManager: START PACKAGE DELETE: observer{196269876}
03-21 15:51:48.051  3424  3452 D PackageManager: pkg{<packageName>}
03-21 15:51:48.051  3424  3452 D PackageManager: user{0}
03-21 15:51:48.051  3424  3452 D PackageManager: caller{2000}
03-21 15:51:48.051  3424  3452 D PackageManager: flags{2}
03-21 15:51:48.051  3424  3452 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 15:51:48.051  3424  3452 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 15:51:48.051  3424  3591 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-21 15:51:48.051  3424  3452 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 15:51:48.051  3424  3452 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 15:51:48.051  3424  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 15:51:48.051  3424  3591 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-21 15:51:48.051  3424  3591 D ApplicationPolicy: getApplicationUninstallationEnabled
03-21 15:51:48.051  3424  3591 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-21 15:51:48.051  3424  3591 D PackageManager: !@killApplicatoin: 10011, uninstall pkg
,03-21 15:51:48.061  3424  3574 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=-1: uninstall pkg,
03-21 15:51:48.061  3424  3574 I ActivityManager: Killing 11109:com.test.thalitest/u0a11 (adj 0): stop com.test.thalitest cause uninstall pkg
,03-21 15:51:48.086  3424  3574 I ActivityManager:   Force finishing activity 3 ActivityRecord{128a73f9 u0 com.test.thalitest/.MainActivity t41}
,03-21 15:51:48.091  3424  3574 D MultiWindowConverter: dismissGuide() : Before attaching the guide view, mForceDismissGuide : false
,03-21 15:51:48.096  3424  3574 D InputDispatcher: Focus left window: 11109
,03-21 15:51:48.096  2859  4148 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,03-21 15:51:48.096  2859  3084 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,03-21 15:51:48.101  3424  3574 D InputDispatcher: Focused application released
,03-21 15:51:48.101  3424  3583 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3424 uid:1000
03-21 15:51:48.101  3424  3583 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 15:51:48.101  3424  3583 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:3424 uid:1000
03-21 15:51:48.101  3424  3583 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,03-21 15:51:48.191  3424  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,03-21 15:51:48.196  3424  3591 W PackageSettings: Skipping PackageSetting{18e3c5be com.example.hello/10691} due to missing metadata
,03-21 15:51:48.211  5859  5871 D BtGatt.GattService: Binder is dead - unregistering client (6)!
,03-21 15:51:48.211  5859  5960 D BtGatt.GattService: Binder is dead - unregistering client (7)!
,03-21 15:51:48.236  3424  3591 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,03-21 15:51:48.246  5859  5871 D BtGatt.GattService: stopScan() - queue size =1
03-21 15:51:48.246  5859  5954 D BtGatt.AdvertiseManager: message : 1
,03-21 15:51:48.246  5859  5955 D BtGatt.ScanManager: filter size is 1
03-21 15:51:48.246  5859  5954 D BtGatt.AdvertiseManager: stop advertise for client 7
03-21 15:51:48.246  5859  5954 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf7
03-21 15:51:48.246  5859  5955 D BtGatt.ScanManager: delete FilterIndex - 9
,03-21 15:51:48.246  5859  5929 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
03-21 15:51:48.246  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:48.246  5859  5955 D BtGatt.ScanManager: stopping BLe Batch
03-21 15:51:48.246  5859  5954 D BtGatt.AdvertiseManager: app died - unregistering client : 7
,03-21 15:51:48.246  5859  5954 D BtGatt.GattService: unregisterClient() - clientIf=7
03-21 15:51:48.246  5859  5929 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=7, status=0
03-21 15:51:48.246  5859  5929 D BtGatt.GattService: Client app is not null!
03-21 15:51:48.246  5859  5929 E BluetoothServiceJni: An exception was thrown by callback 'btgattc_multiadv_disable_cb'.
,03-21 15:51:48.251  5859  5954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,03-21 15:51:48.256  5859  5929 E BluetoothServiceJni: android.os.DeadObjectException
03-21 15:51:48.256  5859  5929 E BluetoothServiceJni: 	at android.os.BinderProxy.transactNative(Native Method)
03-21 15:51:48.256  5859  5929 E BluetoothServiceJni: 	at android.os.BinderProxy.transact(Binder.java:511)
03-21 15:51:48.256  5859  5929 E BluetoothServiceJni: 	at android.bluetooth.IBluetoothGattCallback$Stub$Proxy.onMultiAdvertiseCallback(IBluetoothGattCallback.java:890)
03-21 15:51:48.256  5859  5929 E BluetoothServiceJni: 	at com.android.bluetooth.gatt.GattService.onAdvertiseInstanceDisabled(GattService.java:1295)
03-21 15:51:48.256  5859  5929 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
03-21 15:51:48.256  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
03-21 15:51:48.256  5859  5955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,03-21 15:51:48.256  5859  5929 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
03-21 15:51:48.256  5859  5929 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,03-21 15:51:48.261  5859  5929 D BtGatt.GattService: current time is 248985251695
03-21 15:51:48.261  5859  5929 D BtGatt.GattService: Batch record : [-68, -33, -42, -6, -120, 78, 1, -128, -68, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-21 15:51:48.261  5859  5929 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-21 15:51:48.261  5859  5929 D ScanRecord: parseFromBytes
,03-21 15:51:48.261  5859  5955 D BtGatt.ScanManager: app died, unregister client - 6
03-21 15:51:48.261  5859  5955 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-21 15:51:48.266  3424  3591 I ActivityManager: Force stopping com.test.thalitest appid=10011 user=0: pkg removed
,03-21 15:51:48.311  9080  9080 I art     : Explicit concurrent mark sweep GC freed 26756(1425KB) AllocSpace objects, 2(32KB) LOS objects, 69% free, 1812KB/5MB, paused 757us total 26.343ms
,03-21 15:51:48.316  3424  3591 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 15:51:48.316  3938  3938 I art     : Explicit concurrent mark sweep GC freed 1306(71KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.098ms total 23.254ms
,03-21 15:51:48.336  4642  4642 I art     : Explicit concurrent mark sweep GC freed 5096(337KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 8MB/11MB, paused 1.151ms total 55.527ms
,03-21 15:51:48.346  4013  4013 I art     : Explicit concurrent mark sweep GC freed 2317(125KB) AllocSpace objects, 9(1345KB) LOS objects, 12% free, 56MB/64MB, paused 571us total 50.080ms
,03-21 15:51:48.351  4642  4656 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-21 15:51:48.356  4112  4112 I art     : Explicit concurrent mark sweep GC freed 4989(293KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 6MB/8MB, paused 839us total 70.413ms
,03-21 15:51:48.356  3424  3631 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 15:51:48.361  3724  3724 D CoverUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
,03-21 15:51:48.366  4521  4521 E SamsungIME: mOCRHelper is null
,03-21 15:51:48.366  4414  4831 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 15:51:48.376 10612 10612 D LWLocationManager: getDeviceLocationId :  id = -100
,03-21 15:51:48.376 10612 10612 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-21 15:51:48.376  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.376  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.376  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.376  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:48.391 11959 11959 E Zygote  : MountEmulatedStorage()
03-21 15:51:48.391 11959 11959 E Zygote  : v2
03-21 15:51:48.391 11959 11959 I libpersona: KNOX_SDCARD checking this for 10063
03-21 15:51:48.391 11959 11959 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:48.391 11959 11959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:48.391 11959 11959 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:48.396 11959 11959 E Zygote  : accessInfo : 0
03-21 15:51:48.396  3424  3574 I ActivityManager: Start proc 11959:com.samsung.android.app.vrsetupwizardstub/u0a63 for broadcast-3 com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver
,03-21 15:51:48.396 11959 11959 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 15:51:48.396  5593  5611 W ResourceType: For resource 0x7f020570, entry index(1392) is beyond type entryCount(787)
03-21 15:51:48.396  3424  3690 D TaskPersister: removeObsoleteFile: deleting file=41_task.xml
03-21 15:51:48.396  5593  5611 W ResourceType: Failure getting entry for 0x7f020570 (t=1 e=1392) (error -75)
03-21 15:51:48.396  3424  3690 D TaskPersister: removeObsoleteFile: deleting file=41_task_thumbnail.png
,03-21 15:51:48.401  3424  3567 D EnterpriseDeviceManagerService: Package has changed for user 0
03-21 15:51:48.401  3424  3567 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-21 15:51:48.406  3424  3567 W TextServicesManagerService: no available spell checker services found
,03-21 15:51:48.421  3424  3651 V NetworkStats: removeUidsLocked() for UIDs [10011]
03-21 15:51:48.421  3424  3651 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 15:51:48.421  3424  3651 V NetworkStats: performPollLocked(flags=0x3)
,03-21 15:51:48.431  3424  3651 V NetworkStats: performPollLocked() took 8ms
,03-21 15:51:48.431  3424  3651 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 15:51:48.436  3978  3978 D RegisteredServicesCache: empty dynamic service
03-21 15:51:48.436 11959 11959 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 15:51:48.436 11959 11959 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:48.451  3424  4011 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{878401b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2e9db5b8 11959:com.samsung.android.app.vrsetupwizardstub/u0a63}
,03-21 15:51:48.456  3978  3978 D RegisteredComponentCache: Collect Tech packages for Knox
,03-21 15:51:48.481 11959 11959 D VRSetupWizardStub/PackageIntentReceiver: onReceive()
03-21 15:51:48.481 11959 11959 D VRSetupWizardStub/PackageIntentReceiver: Action Package Remove
03-21 15:51:48.481 11959 11959 D VRSetupWizardStub/PackageIntentReceiver: packagename:com.test.thalitest
,03-21 15:51:48.486  3424  3451 I ActivityManager: Killing 9971:com.google.android.apps.docs/u0a101 (adj 15): emptyCount ##31
,03-21 15:51:48.491  3424  3451 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{878401b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{31f424ec 7128:com.samsung.klmsagent/u0a21}
,03-21 15:51:48.496  7128  7128 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 21 15:51:48 GMT+01:00 2016
,03-21 15:51:48.496  3424  3746 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-21 15:51:48.506  7128  7128 I KLMS-2.5.262: : KLMSAbstractReciever(): onReceive().END.
,03-21 15:51:48.511  3424  3452 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=14, mSplitNum[1]=26, mSplitNum[2]=38, mBgSplitQueueNum=3 divideNum= 12 r.nextReceiver= 2 receivers.size=50
03-21 15:51:48.511  3424  3452 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,03-21 15:51:48.516  7128  7128 I KLMS-2.5.262: : KLMSIntentService(): onCreate()
,03-21 15:51:48.516  7128  7128 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-21 15:51:48.516  7128  7128 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-21 15:51:48.516  7128 11975 I KLMS-2.5.262: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService (has extras) }
,03-21 15:51:48.516  7128 11975 D KLMS-2.5.262: : KLMSIntentService(): PACKAGE_REMOVED
,03-21 15:51:48.516  3424  3424 I art     : Explicit concurrent mark sweep GC freed 101801(7MB) AllocSpace objects, 94(1505KB) LOS objects, 33% free, 28MB/42MB, paused 2.398ms total 203.247ms
,03-21 15:51:48.521  7128 11975 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().START
,03-21 15:51:48.521  7128 11975 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
03-21 15:51:48.521  7128 11975 I KLMS-2.5.262: : listeningToPackageRemovedforELM().START
03-21 15:51:48.521  7128 11975 I KLMS-2.5.262: : MDMBridge.getInstance()
03-21 15:51:48.521  7128 11975 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-21 15:51:48.526  3424  3591 I art     : WaitForGcToComplete blocked for 105.891ms for cause Explicit
,03-21 15:51:48.526  7128 11975 I KLMS-2.5.262: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-21 15:51:48.526  3424  3452 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{878401b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2687c247 6789:com.samsung.aasaservice/1000}
03-21 15:51:48.526  6789  6789 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
03-21 15:51:48.526  6789  6789 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-21 15:51:48.526  7128 11975 I KLMS-2.5.262: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-21 15:51:48.526  6789  6789 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:334)
03-21 15:51:48.526  6789  6789 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
03-21 15:51:48.526  6789  6789 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3509)
03-21 15:51:48.526  6789  6789 W System.err: 	at android.app.ActivityThread.access$1900(ActivityThread.java:197)
03-21 15:51:48.526  6789  6789 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1758)
03-21 15:51:48.526  6789  6789 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:48.526  6789  6789 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:48.526  6789  6789 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:48.526  6789  6789 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:48.526  6789  6789 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:48.526  6789  6789 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:48.526  6789  6789 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:48.531  7128 11975 I KLMS-2.5.262: : MDMBridge.getAllLicenseInfoFromSDK()
,03-21 15:51:48.536  3424  3652 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 15:51:48.536  3424  3652 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 15:51:48.536  7128 11975 E KLMS-2.5.262: : arr si null
,03-21 15:51:48.541  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.541  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.541  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.541  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:48.546  7128 11975 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
,03-21 15:51:48.546  7128 11975 I KLMS-2.5.262: : listeningToPackageRemovedforELM().END
,03-21 15:51:48.546  7128 11975 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().START
03-21 15:51:48.546  7128 11975 I KLMS-2.5.262: : Systemprocess(): .pkgName: com.test.thalitest
,03-21 15:51:48.556  3424  3567 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 15:51:48.561  3424  3574 I ActivityManager: Start proc 11976:com.samsung.android.sdk.samsunglink/u0a42 for broadcast-4 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,03-21 15:51:48.566 11976 11976 E Zygote  : MountEmulatedStorage()
03-21 15:51:48.566 11976 11976 E Zygote  : v2
03-21 15:51:48.566 11976 11976 I libpersona: KNOX_SDCARD checking this for 10042
03-21 15:51:48.566 11976 11976 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:48.566 11976 11976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:48.566  3424  3574 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{10c49793 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{14ac3d9a 10994:com.samsung.android.sm/1000}
03-21 15:51:48.566 11976 11976 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:48.566 11976 11976 E Zygote  : accessInfo : 0
03-21 15:51:48.566 11976 11976 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-21 15:51:48.571  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.571  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.571  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.571  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:48.596 11991 11991 E Zygote  : MountEmulatedStorage()
,03-21 15:51:48.596 11991 11991 E Zygote  : v2
03-21 15:51:48.596 11991 11991 I libpersona: KNOX_SDCARD checking this for 1000
,03-21 15:51:48.596 11991 11991 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:48.601  3424  3574 I ActivityManager: Start proc 11991:com.sec.android.app.popupuireceiver/1000 for broadcast-4 com.sec.android.app.popupuireceiver/.PopupuiReceiver
,03-21 15:51:48.601 11991 11991 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,03-21 15:51:48.601 11991 11991 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:48.606 11991 11991 E Zygote  : accessInfo : 0
,03-21 15:51:48.606 11991 11991 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 15:51:48.616 11976 11976 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:48.616 11976 11976 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:48.636 10994 10994 I art     : Explicit concurrent mark sweep GC freed 150(20KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 1735KB/3MB, paused 420us total 14.468ms
,03-21 15:51:48.641 11991 11991 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:48.641 11991 11991 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:48.706 10612 11968 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 15:51:48.721  3424  3591 I art     : Explicit concurrent mark sweep GC freed 11695(838KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.528ms total 195.800ms
03-21 15:51:48.721  3424  3451 I art     : WaitForGcToComplete blocked for 196.057ms for cause Explicit
,03-21 15:51:48.741  7128 11975 D KLMS-2.5.262: : KLMSUtility(): IsPackageExistInDevice().mAppInfoList: 322
,03-21 15:51:48.741  7128 11975 D KLMS-2.5.262: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
03-21 15:51:48.741  7128 11975 I KLMS-2.5.262: : KLMSSharedPreferences(): getNotificationAppList(): null
03-21 15:51:48.741  7128 11975 I KLMS-2.5.262: : Systemprocess(): Notification App List is Null. Remove Notification.
,03-21 15:51:48.751  7128 11975 D KLMS-2.5.262: : DataSource(): Fetched Data from data base count : 0
03-21 15:51:48.751  7128 11975 I KLMS-2.5.262: : Systemprocess(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-21 15:51:48.751  7128 11975 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemovedforKLM().END
03-21 15:51:48.751  7128 11975 I KLMS-2.5.262: : Systemprocess(): listeningToPackageRemoved().END
,03-21 15:51:48.751  7128  7128 I KLMS-2.5.262: : KLMSIntentService(): onDestroy()
,03-21 15:51:48.761 10612 11968 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 15:51:48.761 10612 11968 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 15:51:48.761 10612 11968 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 15:51:48.761 10612 11968 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-21 15:51:48.791  3424  3567 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 15:51:48.791  3424  3567 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 15:51:48.791  3424  3567 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 15:51:48.791  3424  3567 W ResourcesManager: Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,03-21 15:51:48.816  3424  3591 D PackageManager: Resopt: Clean up res: /data/app/com.test.thalitest-1/base.apk
03-21 15:51:48.816  3424  3591 D PackageManager: delete codoeFile: 
03-21 15:51:48.821  3424  3591 D AASAuninstall: userId = 0, info.removedAppID = 10011, info.uid = 10011, packageName = com.test.thalitest
03-21 15:51:48.821  3424  3591 I AASA_removePackage: UID=10011 Target=com.test.thalitest
03-21 15:51:48.821  3424  3591 D PackageManager: result of delete: 1{196269876}
,03-21 15:51:48.826 11940 11940 I art     : System.exit called, status: 0
03-21 15:51:48.826 11940 11940 I AndroidRuntime: VM exiting with result code 0.
,03-21 15:51:48.826  3424  3591 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 15:51:48.826  3424  3591 D PackageManager: userId{-1}
03-21 15:51:48.826  3424  3591 D PackageManager: andCode{true}
,03-21 15:51:48.836  9774 12007 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
03-21 15:51:48.836  9774 12007 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/data/com.test.thalitest
,03-21 15:51:48.836  9774 12007 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
03-21 15:51:48.836  9774 12007 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/media/com.test.thalitest
03-21 15:51:48.836  9774 12007 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
03-21 15:51:48.841  9774 12007 W System.err: remove failed: EACCES (Permission denied) : /storage/extSdCard/Android/obb/com.test.thalitest
,03-21 15:51:48.861  3424  3451 I art     : Explicit concurrent mark sweep GC freed 10684(631KB) AllocSpace objects, 1(2MB) LOS objects, 33% free, 25MB/37MB, paused 2.484ms total 140.038ms
03-21 15:51:48.861  3424  3451 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
03-21 15:51:48.866  3424  3452 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{878401b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1c8b121e 3424:system/1000}
,03-21 15:51:48.881  3424  3733 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{267265ec u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{3a4b7db5 11991:com.sec.android.app.popupuireceiver/1000}
,03-21 15:51:48.896  3424  4736 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{39618684 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{339aae6d 11976:com.samsung.android.sdk.samsunglink/u0a42}
,03-21 15:51:48.901  3424  3452 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{10c49793 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{14ac3d9a 10994:com.samsung.android.sm/1000}
,03-21 15:51:48.906  3424  3567 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-21 15:51:48.906  3424  3567 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-21 15:51:48.911  4013  4013 E Launcher.Model: onPackageRemoved :com.test.thalitest
,03-21 15:51:48.911  3424  3424 D RCPManagerService: PackageReceiver onReceive()
03-21 15:51:48.911  3424  3424 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-21 15:51:48.911 11991 11991 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-21 15:51:48.911  3424  3424 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-21 15:51:48.911  3424  3424 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-21 15:51:48.911  3424  3424 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10011 container id = 0
,03-21 15:51:48.916  3424  3424 I OTPFW   : ProvisionData::getAllEntries Enter
,03-21 15:51:48.916  3424  3424 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-21 15:51:48.916  3424  3452 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{10c49793 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{14ac3d9a 10994:com.samsung.android.sm/1000}
,03-21 15:51:48.921  3424  3451 D SecContentProvider2: query(), uri = -1 selection = getSealedState
,03-21 15:51:48.921  3424  3835 D SecContentProvider2: query(), uri = 15 selection = getSealedHideNotificationMessages
,03-21 15:51:48.921 11991 11991 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 0
,03-21 15:51:48.921  3424  3959 D SecContentProvider2: query(), uri = 15 selection = getCheckCoverPopupState
,03-21 15:51:48.926 11991 11991 I PopupuiReceiver_KNOX: getCheckCoverPopupState : false
03-21 15:51:48.926 11991 11991 D PopupuiReceiver: Action package removed
03-21 15:51:48.926  3424  3424 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 15:51:48.926  3424  3424 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicy: uID is 10011
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 15:51:48.926  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-21 15:51:48.926  3424  3424 D SdpManagerService:  ActionReceiver::onReceive() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 15:51:48.926  3424  3424 D SdpManagerService: ACTION_PACKAGE_REMOVED Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) } DATA= package:com.test.thalitest UID 1000 userId 0
03-21 15:51:48.926  3424  3424 D SdpManagerService: ACTION_PACKAGE_REMOVED packageName:: com.test.thalitest
03-21 15:51:48.931  3424  3957 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{267265ec u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{2e94629a 10537:com.samsung.android.snote/u0a160}
03-21 15:51:48.931  3424  3424 D EnterprisePartitionManager: SND -> {secure_fs remove_enc_dir}
03-21 15:51:48.931  3424  3593 D EnterprisePartitionManager: RCV <-
03-21 15:51:48.931  3424  3424 D EnterprisePartitionManager: RMV <-
03-21 15:51:48.931  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.936  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.936  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.936  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.941 11976 11976 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 15:51:48.941 11976 11976 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-21 15:51:48.941  3424  6077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1764 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-21 15:51:48.946  3424  3424 E EnterprisePartitionManager: Failed to send commandcom.sec.knox.container.util.DaemonConnector$DaemonArgumentException: command 'secure_fs' failed with '500 3 Command not recognized'
03-21 15:51:48.946  3424  3424 W System.err: java.io.FileNotFoundException: /data/system/users/sdp_engine_list.xml: open failed: ENOENT (No such file or directory)
03-21 15:51:48.946  3424  3424 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 15:51:48.946  3424  3424 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.getEngineListLocked(SdpManagerService.java:1514)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase$EngineListHandler.access$1100(SdpManagerService.java:1434)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.getEngineListLocked(SdpManagerService.java:1418)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SdpManagerService$SdpEngineDatabase.access$2200(SdpManagerService.java:1393)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SdpManagerService.handlePkgRemoved(SdpManagerService.java:2647)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SdpManagerService.access$2500(SdpManagerService.java:137)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SdpManagerService$ActionReceiver.onReceive(SdpManagerService.java:2719)
03-21 15:51:48.946  3424  3424 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:972)
03-21 15:51:48.946  3424  3424 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:48.946  3424  3424 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:48.946  3424  3424 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:469)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:353)
03-21 15:51:48.946  3424  3424 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:48.946  3424  3424 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:48.946  3424  3424 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:48.946  3424  3424 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-21 15:51:48.946  3424  3424 W System.err: 	at libcore.io.Posix.open(Native Method)
03-21 15:51:48.946  3424  3424 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 15:51:48.946  3424  3424 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 15:51:48.946  3424  3424 W System.err: 	... 18 more
03-21 15:51:48.946  3424  3424 E SdpManagerService: failed to get engine list
03-21 15:51:48.946  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-21 15:51:48.946  3424  6046 D SSRM:bd : MSG_TYPE_APP_REMOVED::
03-21 15:51:48.946  3424  3424 V EnterpriseBillingPolicy: uID is 10011
03-21 15:51:48.946  3424  3424 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 15:51:48.946  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 15:51:48.951  3424  3424 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 15:51:48.951  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 15:51:48.951  3424  3424 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 15:51:48.951  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 15:51:48.951  3424  3424 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-21 15:51:48.951  3424  3424 V AlarmManagerEXT: com.test.thalitest(10011) is removed.
03-21 15:51:48.951 12011 12011 E Zygote  : MountEmulatedStorage()
03-21 15:51:48.951 12011 12011 E Zygote  : v2
03-21 15:51:48.951 12011 12011 I libpersona: KNOX_SDCARD checking this for 1000
03-21 15:51:48.956 12011 12011 I libpersona: KNOX_SDCARD not a persona
03-21 15:51:48.956  3424  3957 I ActivityManager: Start proc 12011:com.samsung.android.app.assistantmenu/1000 for broadcast-4 com.samsung.android.app.assistantmenu/.AssistantMenuReceiver
,03-21 15:51:48.956 12011 12011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:48.956 12011 12011 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 15:51:48.961 12011 12011 E Zygote  : accessInfo : 0
03-21 15:51:48.961 12011 12011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 15:51:48.966  3424  3424 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{878401b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{32f13bd8 6112:com.sec.android.service.health/u0a19}
03-21 15:51:48.971  6112  6112 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
03-21 15:51:48.971  6112  6112 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
03-21 15:51:48.971  6112  6112 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
03-21 15:51:48.976 10994 12009 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
03-21 15:51:48.976  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.976  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.976  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:48.976  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:48.996 12011 12011 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:48.996 12011 12011 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:49.011 12027 12027 E Zygote  : MountEmulatedStorage()
03-21 15:51:49.011 12027 12027 E Zygote  : v2
03-21 15:51:49.011 12027 12027 I libpersona: KNOX_SDCARD checking this for 10183
03-21 15:51:49.011 12027 12027 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:49.016 12027 12027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:49.016 12027 12027 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:49.016 12027 12027 E Zygote  : accessInfo : 0
,03-21 15:51:49.016 12027 12027 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 15:51:49.016  3424  3957 I ActivityManager: Start proc 12027:com.samsung.android.provider.shootingmodeprovider/u0a183 for broadcast-4 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,03-21 15:51:49.026  3424  3746 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{10c49793 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{121f7f9b 12011:com.samsung.android.app.assistantmenu/1000}
,03-21 15:51:49.031 10707 10720 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.031 10707 10720 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,03-21 15:51:49.041 10707 10720 E DatabaseUtils: Writing exception to parcel
03-21 15:51:49.041 10707 10720 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: #################################################################
03-21 15:51:49.041 10707 10720 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	(disk I/O error (code 6922))
03-21 15:51:49.041 10707 10720 E DatabaseUtils: #################################################################
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
03-21 15:51:49.041 10707 10720 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-21 15:51:49.046  2900  2900 I art     : Explicit concurrent mark sweep GC freed 8762(372KB) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 861us total 21.979ms
,03-21 15:51:49.046  3424  3957 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{878401b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{35bf89bb 10612:com.sec.android.widgetapp.locationwidget/u0a22}
,03-21 15:51:49.051 12027 12027 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:49.051 10612 10612 D LocationWidgetApplication: getLastUiLocationId() : mLastUiLocationId = -100
03-21 15:51:49.051 12027 12027 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:49.056  2900  2900 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 387us total 9.576ms
03-21 15:51:49.056 11976 11976 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (30)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: #################################################################
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: #################################################################
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at android.app.ActivityTh,read.main(ActivityThread.java:6872)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:49.056 11976 11976 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:49.056 11976 11976 D AndroidRuntime: Shutting down VM
03-21 15:51:49.056 11976 11976 E AndroidRuntime: FATAL EXCEPTION: main
03-21 15:51:49.056 11976 11976 E AndroidRuntime: Process: com.samsung.android.sdk.samsunglink, PID: 11976
03-21 15:51:49.056 11976 11976 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.056 11976 11976 E AndroidRuntime: #################################################################
03-21 15:51:49.056 11976 11976 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.056 11976 11976 E AndroidRuntime: #################################################################
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.056 11976 11976 E AndroidRuntime: #################################################################
03-21 15:51:49.056 11976 11976 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.056 11976 11976 E AndroidRuntime: #################################################################
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPo,ol.java:206)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.056 11976 11976 E AndroidRuntime: 	... 11 more
03-21 15:51:49.061  3424  4011 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
03-21 15:51:49.066  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.066  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.066  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.066  3424  3957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.071  2900  2900 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 72% free, 1529KB/5MB, paused 483us total 9.319ms
03-21 15:51:49.081 12043 12043 E Zygote  : MountEmulatedStorage()
03-21 15:51:49.086 12043 12043 E Zygote  : v2
03-21 15:51:49.086 12043 12043 I libpersona: KNOX_SDCARD checking this for 1000
03-21 15:51:49.086 12043 12043 I libpersona: KNOX_SDCARD not a persona
03-21 15:51:49.091  3424  3957 I ActivityManager: Start proc 12043:com.sec.pcw.device/1000 for broadcast-3 com.sec.pcw.device/.receiver.SYSTEMReceiver
03-21 15:51:49.091 12043 12043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:49.091 12043 12043 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 15:51:49.091  3424  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
03-21 15:51:49.091  3424  3957 I ActivityManager: Killing 10270:com.vlingo.midas/u0a34 (adj 15): emptyCount ##31
03-21 15:51:49.091 12043 12043 E Zygote  : accessInfo : 0
03-21 15:51:49.091  3424  3603 D UsbHostManager: displayNotification : [02h,02h,01h]
03-21 15:51:49.091 12043 12043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 15:51:49.091  3424  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
03-21 15:51:49.091  3424  3603 D UsbHostManager: displayNotification : [0ah,00h,00h]
03-21 15:51:49.096  3424  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
03-21 15:51:49.096  3424  3603 D UsbHostManager: displayNotification : [02h,0dh,00h]
03-21 15:51:49.096  3424  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
03-21 15:51:49.096  3424  3603 D UsbHostManager: displayNotification : [0ah,00h,01h]
,03-21 15:51:49.101  3424  3692 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/003
03-21 15:51:49.101  3424  3603 D UsbHostManager: onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
03-21 15:51:49.101  3424  3603 D UsbHostManager: displayNotification : [09h,00h,00h]
03-21 15:51:49.101  3424  3692 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
03-21 15:51:49.101  3424  3692 D UsbSettingsManager: usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
03-21 15:51:49.106 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.106 10994 12010 E SQLiteLog: (6922) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
03-21 15:51:49.106  3424  3835 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{267265ec u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{1d2cbf38 12027:com.samsung.android.provider.shootingmodeprovider/u0a183}
03-21 15:51:49.106 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.106 10994 12010 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
03-21 15:51:49.106 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.106 10994 12010 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
03-21 15:51:49.106 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.106 10994 12010 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
03-21 15:51:49.111 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.111 10994 12010 E SQLiteLog: (6922) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
03-21 15:51:49.111 12043 12043 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:49.111 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.111 10994 12010 E SQLiteLog: (6922) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
03-21 15:51:49.111 12043 12043 D ActivityThread: Added TimaKeyStore provider
03-21 15:51:49.111 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.111 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:183)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.111 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.111 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: Error inserting name=now value=Mon Mar 21 15:51:49 GMT+01:00 2016
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:184)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.111 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.116 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.116 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.116  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:185)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.116  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.116 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.116  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.116 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.116  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.116 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.116 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error inserting name=DBVersion value=2003
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.116 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.116 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.116 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: Can't write: system_app_crash
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 15:51:49.121  3424 12063 E DropBoxManagerService: 	... 5 more
03-21 15:51:49.121  3424 12063 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop225.tmp
03-21 15:51:49.121 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.121 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: Error inserting name=UT enabled value=false
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.121 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.121 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.121 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.126 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.126 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.126 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.126 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.1.1
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.126 10994 12010 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.126 12011 12011 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2129 android.content.ContextWrapper.startService:534 android.content.ContextWrapper.startService:534 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3509 
03-21 15:51:49.126 10994 12010 E SQLiteLog: (6922) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
03-21 15:51:49.126 12066 12066 I libpersona: KNOX_SDCARD checking this for 10045
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Error inserting name=status value=successfully initialized
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	(disk I/O error (code 6922))
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: #################################################################
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.126 10994 12010 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 15:51:49.126 12066 12066 I libpersona: KNOX_SDCARD not a persona
03-21 15:51:49.126 12066 12066 E Zygote  : MountEmulatedStorage()
03-21 15:51:49.126 12066 12066 E Zygote  : v2
03-21 15:51:49.131 12066 12066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:49.131  3424  3574 I ActivityManager: Start proc 12066:com.osp.app.signin/u0a45 for broadcast-4 com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver
03-21 15:51:49.131 12066 12066 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 15:51:49.131 12066 12066 E Zygote  : accessInfo : 0
03-21 15:51:49.131 12066 12066 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 15:51:49.136  3424  3692 D UsbHostManager: usbDeviceRemoved : /dev/bus/usb/001/001
03-21 15:51:49.136  3424  3692 E UsbHostManager: usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
03-21 15:51:49.136  3424  4413 I ActivityManager: Killing 10350:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##31
,03-21 15:51:49.141  3424  4413 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{878401b u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{27ae3476 12043:com.sec.pcw.device/1000}
03-21 15:51:49.141  3424  4736 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-21 15:51:49.156 12027 12027 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: #################################################################
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: #################################################################
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:49.156 12027 12027 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:49.161 12027 12027 D AndroidRuntime: Shutting down VM
03-21 15:51:49.161 12027 12027 E AndroidRuntime: FATAL EXCEPTION: main
03-21 15:51:49.161 12027 12027 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 12027
03-21 15:51:49.161 12027 12027 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.161 12027 12027 E AndroidRuntime: #################################################################
03-21 15:51:49.161 12027 12027 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.161 12027 12027 E AndroidRuntime: #################################################################
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.161 12027 12027 E AndroidRuntime: #################################################################
03-21 15:51:49.161 12027 12027 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.161 12027 12027 E AndroidRuntime: #################################################################
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.161 12027 12027 E AndroidRuntime: 	... 11 more
03-21 15:51:49.171 12066 12066 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:49.171 12011 12082 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
03-21 15:51:49.171 12066 12066 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:49.181  3424  3631 I EventHub: Removing device '/dev/input/event10' due to inotify event
03-21 15:51:49.186  3424  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:49.186  3424  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.186  3424  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.186  3424  3835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:49.206 12011 12082 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: #################################################################
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: #################################################################
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.206 12011 12082 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 15:51:49.206 12011 12082 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.206 12011 12082 W System.err: #################################################################
03-21 15:51:49.206 12011 12082 W System.err: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.206 12011 12082 W System.err: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.206 12011 12082 W System.err: #################################################################
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.206 12011 12082 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
03-21 15:51:49.206 12011 12082 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.206 12011 12082 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 15:51:49.226 12083 12083 E Zygote  : MountEmulatedStorage()
03-21 15:51:49.226 12083 12083 E Zygote  : v2
03-21 15:51:49.226 12083 12083 I libpersona: KNOX_SDCARD checking this for 1000
03-21 15:51:49.226 12083 12083 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:49.231 12083 12083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:49.231 12083 12083 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
03-21 15:51:49.231 12083 12083 E Zygote  : accessInfo : 0
03-21 15:51:49.231 12083 12083 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 15:51:49.236  3424  3631 I EventHub: Removing device '/dev/input/event7' due to inotify event
,03-21 15:51:49.251  3424  3835 I ActivityManager: Start proc 12083:com.sec.knox.bridge/1000 for broadcast-4 com.sec.knox.bridge/.PersonaShortcutReceiver
,03-21 15:51:49.266  3424  3746 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
,03-21 15:51:49.266 12043 12043 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-21 15:51:49.266 12043 12043 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-21 15:51:49.266 12043 12043 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
03-21 15:51:49.271 12043 12043 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 15:51:49.271 10994 10994 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched),
03-21 15:51:49.276  3424  3733 V BroadcastQueue: [backgroundsplit_0] Process cur broadcast BroadcastRecord{39618684 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{48a96e4 12066:com.osp.app.signin/u0a45},
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: #################################################################
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: #################################################################
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404),
03-21 15:51:49.281 12043 12043 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:49.281 12043 12043 D AndroidRuntime: Shutting down VM,
,03-21 15:51:49.281 12043 12043 E AndroidRuntime: FATAL EXCEPTION: main,
03-21 15:51:49.281 12043 12043 E AndroidRuntime: Process: com.sec.pcw.device, PID: 12043
03-21 15:51:49.281 12043 12043 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.281 12043 12043 E AndroidRuntime: #################################################################
03-21 15:51:49.281 12043 12043 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.281 12043 12043 E AndroidRuntime: #################################################################
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6416)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at com.and,roid.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.281 12043 12043 E AndroidRuntime: #################################################################
03-21 15:51:49.281 12043 12043 E AndroidRuntime: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.281 12043 12043 E AndroidRuntime: #################################################################
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.281 12043 12043 E AndroidRuntime: 	... 11 more
03-21 15:51:49.291  3424  3631 I EventHub: Removing device '/dev/input/event8' due to inotify event
,03-21 15:51:49.311  3424  3631 I EventHub: Removing device '/dev/input/event9' due to inotify event
,03-21 15:51:49.316 12083 12083 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 15:51:49.321 11976 11976 I Process : Sending signal. PID: 11976 SIG: 9
,03-21 15:51:49.326  3424 12098 E DropBoxManagerService: Can't write: system_app_crash
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 15:51:49.326  3424 12098 E DropBoxManagerService: 	... 5 more
,03-21 15:51:49.331  3424 12098 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop226.tmp
,03-21 15:51:49.331 12083 12083 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:49.336  3424  4735 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,03-21 15:51:49.336  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.336  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.336  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.336  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:49.346  3424  3631 I EventHub: Removing device '/dev/input/event11' due to inotify event
,03-21 15:51:49.386 12099 12099 E Zygote  : MountEmulatedStorage()
03-21 15:51:49.386 12099 12099 E Zygote  : v2
03-21 15:51:49.386 12099 12099 I libpersona: KNOX_SDCARD checking this for 10190
03-21 15:51:49.386 12099 12099 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:49.386 12066 12066 I SA      : [SSP] onCreated
03-21 15:51:49.391 12099 12099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:49.391 12099 12099 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:49.391 12099 12099 E Zygote  : accessInfo : 0
03-21 15:51:49.391 12066 12066 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/samsungaccount.db" with flag (131138) and mode_t (0) due to error (30)
03-21 15:51:49.391 12099 12099 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 15:51:49.396 12066 12066 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/samsungaccount.db'.
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: #################################################################
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: #################################################################
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at com.msc.contentprovider.SamsungServiceProvider.onCreate(SamsungServiceProvider.java:575)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(,ZygoteInit.java:1404)
03-21 15:51:49.396 12066 12066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
,03-21 15:51:49.401 12066 12066 E SQLiteLog: (28) failed to open "/data/data/com.osp.app.signin/databases/openData.db" with flag (131138) and mode_t (0) due to error (30)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: Failed to open database '/data/data/com.osp.app.signin/databases/openData.db'.
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: #################################################################
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: #################################################################
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1585)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at com.msc.openprovider.OpenContentProvider.onCreate(OpenContentProvider.java:214)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1737)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:6413)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:6008)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5948)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:197)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1742)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6872)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at java.l,ang.reflect.Method.invoke(Method.java:372)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1404)
03-21 15:51:49.401 12066 12066 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1199)
03-21 15:51:49.401  3424  3574 I ActivityManager: Start proc 12099:com.sec.android.widgetapp.tapandpay/u0a190 for broadcast-4 com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider
,03-21 15:51:49.406 12027 12027 I Process : Sending signal. PID: 12027 SIG: 9
,03-21 15:51:49.411  3424  3631 I EventHub: Removing device '/dev/input/event12' due to inotify event
,03-21 15:51:49.416  2855  2855 E lowmemorykiller: Error writing /proc/12027/oom_score_adj; errno=22
,03-21 15:51:49.421 10707 10718 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-21 15:51:49.421 10707 10718 E SQLiteLog: (6922) statement aborts at 27: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,03-21 15:51:49.431  3424  3733 I ActivityManager: Killing 10389:com.samsung.helphub/1000 (adj 15): emptyCount ##31
,03-21 15:51:49.431 10707 10718 E DatabaseUtils: Writing exception to parcel
03-21 15:51:49.431 10707 10718 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 6922)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: #################################################################
03-21 15:51:49.431 10707 10718 E DatabaseUtils: Error Code : 6922 (SQLITE_IOERR_LOCK_EBADF)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: Caused By : I/O error happened due to bad file descriptor. There is possibility the partition changed to read-only.
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	(disk I/O error (code 6922))
03-21 15:51:49.431 10707 10718 E DatabaseUtils: #################################################################
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:176)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:341)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
03-21 15:51:49.431 10707 10718 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-21 15:51:49.441  3424  3733 V BroadcastQueue: [backgroundsplit_1] Process cur broadcast BroadcastRecord{10c49793 u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{13c12202 12083:com.sec.knox.bridge/1000}
03-21 15:51:49.441  3424  3451 I ActivityManager: Process com.samsung.android.sdk.samsunglink (pid 11976)(adj 13) has died(261,1531)
,03-21 15:51:49.456 12099 12099 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 15:51:49.461 12099 12099 D ActivityThread: Added TimaKeyStore provider
,03-21 15:51:49.476  3424  3631 I EventHub: Removing device '/dev/input/event13' due to inotify event
,03-21 15:51:49.486  3424 12114 E DropBoxManagerService: Can't write: system_app_crash
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:16408)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 15:51:49.486  3424 12114 E DropBoxManagerService: 	... 5 more
,03-21 15:51:49.486  3424 12114 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/dropbox/drop227.tmp
,03-21 15:51:49.496 12083 12083 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 15:51:49.496  3424  4413 V BroadcastQueue: [backgroundsplit_2] Process cur broadcast BroadcastRecord{267265ec u0 android.intent.action.PACKAGE_REMOVED} DELIVERED for app ProcessRecord{11244713 12099:com.sec.android.widgetapp.tapandpay/u0a190}
,03-21 15:51:49.501  3424  3835 I ActivityManager: Process com.samsung.android.provider.shootingmodeprovider (pid 12027)(adj 9) has died(262,1531)
,03-21 15:51:49.526  3424  3631 I EventHub: Removing device '/dev/input/event14' due to inotify event
,03-21 15:51:49.541 12066 12066 I SA      : [TPM] There is no property file
,03-21 15:51:49.546 12083 12083 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,03-21 15:51:49.551  3424  3959 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-21 15:51:49.551  3424  3959 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-21 15:51:49.551  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.556 12066 12066 I SA      : [SCU] isHaveSA() - false
03-21 15:51:49.551  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:49.551  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.556  3424  3574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:49.571 12066 12066 I SA      : [TPM] getModelProperty : null
,03-21 15:51:49.571 12066 12066 I SA      : [TPM] getCSCProperty : null
,03-21 15:51:49.576 12099 12099 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-21 15:51:49.576 12099 12099 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,03-21 15:51:49.581 12066 12066 I SA      : [DM] FLOATING AMOLED FEATURE: true
,03-21 15:51:49.581 12066 12066 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-21 15:51:49.581 12066 12066 I SA      : [DM] TFT FEATURE: false
,03-21 15:51:49.586 12066 12066 I SA      : [SUR] onReceive called
03-21 15:51:49.586 12066 12066 I SA      : [SUR] Not SA Package.. finish
,03-21 15:51:49.591 12099 12099 I TapandpayWidget:Utils: Clear T&P info.
,03-21 15:51:49.601 12118 12118 E Zygote  : MountEmulatedStorage()
03-21 15:51:49.601 12118 12118 E Zygote  : v2
03-21 15:51:49.601 12118 12118 I libpersona: KNOX_SDCARD checking this for 10035
03-21 15:51:49.601 12118 12118 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:49.601 12099 12099 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,03-21 15:51:49.606 12118 12118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:49.606 12118 12118 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:49.606 12118 12118 E Zygote  : accessInfo : 0
,03-21 15:51:49.606 12118 12118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 15:51:49.616  3424  3574 I ActivityManager: Start proc 12118:com.samsung.android.app.galaxyfinder/u0a35 for broadcast-3 com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver
,03-21 15:51:49.626  3424  3452 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.626  3424  3452 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.626  3424  3452 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 15:51:49.626  3424  3452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 15:51:49.666 12133 12133 E Zygote  : MountEmulatedStorage()
03-21 15:51:49.666 12133 12133 E Zygote  : v2
03-21 15:51:49.666 12133 12133 I libpersona: KNOX_SDCARD checking this for 10101
03-21 15:51:49.671 12133 12133 I libpersona: KNOX_SDCARD not a persona
,03-21 15:51:49.676 12118 12118 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 15:51:49.676 12133 12133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
03-21 15:51:49.676 12133 12133 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N910C_5.1.1_0035
,03-21 15:51:49.676 12118 12118 D ActivityThread: Added TimaKeyStore provider
03-21 15:51:49.676  3424  3452 I ActivityManager: Start proc 12133:com.google.android.apps.docs/u0a101 for broadcast-4 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
03-21 15:51:49.676 12133 12133 E Zygote  : accessInfo : 0
03-21 15:51:49.676 12133 12133 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 15:51:49.686  3424  3452 I ActivityManager: Killing 10334:com.android.providers.calendar/u0a47 (adj 15): emptyCount ##31

```
