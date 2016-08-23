#### Test 821470463bd5c99_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-23 08:43:47.031  1016  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 08:43:47.031  1016  1133 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
--------- beginning of main
08-23 08:43:47.041  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 08:43:47.031  1016  1133 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 08:43:47.041  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 08:43:47.031  1016  1133 D BatteryService: stay LED for fully charged
08-23 08:43:47.031  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 08:43:47.041  1016  1016 I MotionRecognitionService: Plugged
08-23 08:43:47.041  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-23 08:43:47.041  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 08:43:47.041  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-23 08:43:47.051  3161  3161 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 08:43:47.051  3161  3272 D HeadsetStateMachine: Disconnected process message: 10
08-23 08:43:47.071  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 08:43:47.071  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 08:43:47.071  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:43:47.371  6810  6810 D AndroidRuntime: 
08-23 08:43:47.371  6810  6810 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 08:43:47.371  6810  6810 D AndroidRuntime: CheckJNI is OFF
08-23 08:43:47.371  6810  6810 D AndroidRuntime: readGMSProperty: start
08-23 08:43:47.371  6810  6810 D AndroidRuntime: readGMSProperty: already setted!!
08-23 08:43:47.371  6810  6810 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 08:43:47.371  6810  6810 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 08:43:47.371  6810  6810 D AndroidRuntime: readGMSProperty: end
08-23 08:43:47.371  6810  6810 D AndroidRuntime: addProductProperty: start
08-23 08:43:47.511  6810  6810 E AffinityControl: AffinityControl: registerfunction enter
08-23 08:43:47.531  6810  6810 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 08:43:47.551  1016  1491 E PersonaManagerService: inState():  stateMachine is null !!
08-23 08:43:47.551  1016  1491 I PersonaManagerService: PersonaId don't exist
08-23 08:43:47.551  1016  1491 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 08:43:47.551  1016  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 08:43:47.571  1016  1491 W ActivityManager: mDVFSHelper.acquire()
08-23 08:43:47.581   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-23 08:43:47.581   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-23 08:43:47.591  1016  1491 D FocusedStackFrame: Set to : 0
08-23 08:43:47.591  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:43:47.591  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:43:47.591  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:43:47.591  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:43:47.601  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 08:43:47.601  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 08:43:47.611  6821  6821 E Zygote  : MountEmulatedStorage()
08-23 08:43:47.611  6821  6821 E Zygote  : v2
08-23 08:43:47.611  6821  6821 I libpersona: KNOX_SDCARD checking this for 10171
08-23 08:43:47.611  6821  6821 I libpersona: KNOX_SDCARD not a persona
08-23 08:43:47.611  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 08:43:47.611  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 08:43:47.611  6821  6821 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:43:47.611  1016  1491 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6821 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 08:43:47.611  1016  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 08:43:47.611  1016  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 08:43:47.611  6821  6821 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:43:47.611  6821  6821 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 08:43:47.611   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-23 08:43:47.621  1016  1491 D InputDispatcher: Focused application set to: xxxx
08-23 08:43:47.621  1016  1491 D InputDispatcher: Focus left window: 1479
08-23 08:43:47.621  6810  6810 D AndroidRuntime: Shutting down VM
08-23 08:43:47.621  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 08:43:47.621  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 08:43:47.641  6821  6821 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:43:47.641  6821  6821 D ActivityThread: Added TimaKeyStore provider
08-23 08:43:47.641  1016  3839 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 08:43:47.641  1016  1016 V ActivityManager: Display changed displayId=0
08-23 08:43:47.661  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 08:43:47.671  1016  3839 D PersonaManager: isKioskContainerExistOnDevice
08-23 08:43:47.681  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 08:43:47.701   257   451 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-23 08:43:47.711   257   455 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-23 08:43:47.711  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{26753221 token=android.os.BinderProxy@2239c177 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 08:43:47.711  1479  1479 D Launcher: onTrimMemory. Level: 20
08-23 08:43:47.781  6821  6821 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-23 08:43:47.801  6821  6821 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6923-6925)
08-23 08:43:47.801  6821  6821 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 08:43:47.821  6821  6821 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17d9d0e0}
08-23 08:43:47.831  6810  6810 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-23 08:43:47.831  6821  6821 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 08:43:47.841  6821  6821 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 08:43:47.871  6821  6821 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 08:43:47.871  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:43:47.881  6821  6821 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 08:43:47.921  6821  6821 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 08:43:47.921  6821  6821 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 08:43:47.921  6821  6821 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 08:43:47.921  6821  6821 I Adreno-EGL: Local Branch: 
08-23 08:43:47.921  6821  6821 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 08:43:47.921  6821  6821 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 08:43:47.921  6821  6821 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 08:43:48.001  6821  6821 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 08:43:48.011   294   294 E SMD     : DCD OFF
,08-23 08:43:48.031  6821  6821 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 08:43:48.031  6821  6821 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 08:43:48.041  6821  6821 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 08:43:48.041  6821  6821 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 08:43:48.161  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:43:48.171  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{2aa1381f u0 com.test.thalitest/.MainActivity t2}
,08-23 08:43:48.181  6821  6821 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 08:43:48.191  6821  6821 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-23 08:43:48.191  6821  6821 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-23 08:43:48.191  6821  6821 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 08:43:48.201  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:43:48.201  6821  6821 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:43:48.331  6821  6861 D OpenGLRenderer: Render dirty regions requested: true
,08-23 08:43:48.331  1016  1231 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 08:43:48.331  1016  1231 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 08:43:48.331  1016  1231 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 08:43:48.331  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 08:43:48.331  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 08:43:48.341  6821  6848 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-23 08:43:48.341  6821  6821 V ActivityThread: updateVisibility : ActivityRecord{157f3f40 token=android.os.BinderProxy@e59077d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 08:43:48.351  6821  6821 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-23 08:43:48.351  6821  6821 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-23 08:43:48.361   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-23 08:43:48.381  1016  1478 D InputDispatcher: Focus entered window: 6821
,08-23 08:43:48.381  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 08:43:48.381  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 08:43:48.381  6821  6821 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 08:43:48.381  6821  6861 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 08:43:48.391  6821  6861 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-23 08:43:48.391  6821  6861 D OpenGLRenderer: Enabling debug mode 0
,08-23 08:43:48.411  1016  1377 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 08:43:48.421  1177  1177 I StatusBar: Icon Only,
08-23 08:43:48.421  1016  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 08:43:48.421  1177  1177 D PanelView: There is/are notification(s) 
,08-23 08:43:48.431  1016  1046 I ActivityManager: Displayed Component not be shown by security: +754ms (total +837ms)
,08-23 08:43:48.431  1016  1046 W ActivityManager: mDVFSHelper.release()
08-23 08:43:48.431  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2aa1381f u0 com.test.thalitest/.MainActivity t2} time:107554
,08-23 08:43:48.431   257   737 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-23 08:43:48.441   257   455 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-23 08:43:48.441  6821  6821 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-23 08:43:48.441  6821  6821 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e59077d time:107567
,08-23 08:43:48.451  1827  1827 I SamsungIME: getCurrentCandidateView
,08-23 08:43:48.491  6821  6821 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6821
,08-23 08:43:48.541  1827  1827 D SamsungIME: Dismiss ExpandCandiate
,08-23 08:43:48.701  6821  6821 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 08:43:48.751  1827  1827 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 08:43:48.791  1827  1827 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 08:43:48.791  6821  6865 D jxcore_app_log: JniHelper::setJavaVM(0xb7a3c2b0), pthread_self() = -1208188600
,08-23 08:43:48.801  6821  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 08:43:48.801  6821  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 08:43:48.801  6821  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 08:43:48.801  6821  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 08:43:48.801  6821  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 08:43:48.801  6821  6865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62cd096 added. We now have 1 listener(s)
,08-23 08:43:48.801  1827  1827 I SamsungIME: KeybaordView init() : load resources
08-23 08:43:48.801  6821  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
08-23 08:43:48.801  6821  6865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 08:43:48.811  6821  6865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:43:48.811  6821  6865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 08:43:48.811  6821  6865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71fc9ed added. We now have 1 listener(s)
,08-23 08:43:48.811  6821  6865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:43:48.821  6821  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 08:43:48.821  6821  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 08:43:48.821  6821  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 08:43:48.821  6821  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 08:43:48.821  6821  6865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 08:43:48.821  6821  6865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-23 08:43:48.821  6821  6865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-23 08:43:48.831  1827  1827 I SamsungIME: getCurrentKeyboard
08-23 08:43:48.831  1827  1827 I SamsungIME: getTextKeyboard
,08-23 08:43:48.831  6821  6865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:43:48.831  6821  6865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:43:48.831  6821  6865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 08:43:48.831  6821  6865 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 08:43:48.841  6821  6865 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 08:43:48.841  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:43:48.841  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:43:48.861  1827  1827 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 08:43:48.871  6821  6821 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 08:43:48.971  1016  1304 E Watchdog: !@Sync 3
,08-23 08:43:49.391  6821  6874 W jxcore-log: Initializing JXcore engine
08-23 08:43:49.391  6821  6874 W jxcore-log: JXcore engine is ready
,08-23 08:43:49.451  1879  1879 E audit   : type=1400 msg=audit(1471934629.441:205): avc:  denied  { ioctl } for  pid=6874 comm="Thread-1255" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-23 08:43:49.451  1879  1879 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:43:49.451  1879  1879 E audit   : type=1300 msg=audit(1471934629.441:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f3048f8 items=0 ppid=317 ppcomm=main pid=6874 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1255" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 08:43:49.451  1879  1879 E audit   : type=1320 msg=audit(1471934629.441:205): 
,08-23 08:43:49.461  6821  6874 W jxcore-log: Starting JXcore engine
,08-23 08:43:49.561  6821  6874 W jxcore-log: Platform android
08-23 08:43:49.561  6821  6874 W jxcore-log: 
08-23 08:43:49.571  6821  6874 W jxcore-log: Process ARCH arm
08-23 08:43:49.571  6821  6874 W jxcore-log: 
,08-23 08:43:49.771  6821  6874 I jxcore-log: JXcore Cordova bridge is ready!
08-23 08:43:49.771  6821  6874 I jxcore-log: 
,08-23 08:43:49.781  6821  6874 W jxcore-log: JXcore engine is started
,08-23 08:43:49.781  6821  6865 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 08:43:49.781  6821  6821 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 08:43:50.721   331   331 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-23 08:43:50.721   331   331 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 08:43:51.011   294   294 E SMD     : DCD OFF,
,08-23 08:43:53.811  1016  1048 I PowerManagerService: [PWL] Off : 50s ago,
,08-23 08:43:53.941  1016  3385 D SSRM:n  : SIOP:: AP = 300
,08-23 08:43:54.011   294   294 E SMD     : DCD OFF,
,08-23 08:43:55.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 08:43:56.391  5697  5697 D FactoryTest: Not factory mode
,08-23 08:43:56.391  5697  5697 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-23 08:43:56.391  5697  5697 D MTPRx   : DRIVER_TIME_OUT 60s lapsed,
08-23 08:43:56.391  5697  5697 D MTPRx   : still no open session command from host, so toast
08-23 08:43:56.391  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-23 08:43:56.391  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-23 08:43:56.391  5697  5697 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115515,
08-23 08:43:56.391  1016  1029 E PersonaManagerService: inState():  stateMachine is null !!
08-23 08:43:56.391  1016  1029 I PersonaManagerService: PersonaId don't exist
08-23 08:43:56.391  1016  1029 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false,
,08-23 08:43:56.401  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-23 08:43:56.401  1016  1029 W ActivityManager: userId = 0, bbcId = -10000,
08-23 08:43:56.401  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:43:56.401  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,08-23 08:43:56.401  1016  1029 W ActivityManager: mDVFSHelper.acquire()
,08-23 08:43:56.421  1016  1029 D PersonaManager: isKioskContainerExistOnDevice
,08-23 08:43:56.431  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 08:43:56.431  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 08:43:56.431  1016  1029 D InputDispatcher: Focused application set to: xxxx
,08-23 08:43:56.431  1016  1029 D InputDispatcher: Focus left window: 6821
,08-23 08:43:56.431  5697  5697 E MTPRx   : started activity for popup
,08-23 08:43:56.431  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 08:43:56.431  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 08:43:56.461  5697  5697 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-23 08:43:56.461  5697  5697 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-23 08:43:56.461  5697  5697 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 08:43:56.461  5697  5697 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 08:43:56.461  5697  5697 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 08:43:56.461  5697  5697 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 08:43:56.481  5697  5697 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-23 08:43:56.501  1016  1510 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 08:43:56.501  1016  1510 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 08:43:56.501  1016  1510 D InputDispatcher: Focused application set to: xxxx
,08-23 08:43:56.501  1016  1510 D InputDispatcher: Focus entered window: 6821
,08-23 08:43:56.511  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 08:43:56.511  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 08:43:56.511  1016  1328 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 08:43:56.511  1016  1328 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9aa61ce attribute=null, token = android.os.BinderProxy@b68751e
,08-23 08:43:56.551  5697  5697 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-23 08:43:56.551  5697  5697 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-23 08:43:56.551  5697  5697 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-23 08:43:56.581  6821  6821 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 08:43:56.581  6821  6821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-23 08:43:56.581  6821  6821 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 08:43:56.581  6821  6821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-23 08:43:56.581  1016  3839 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 08:43:56.581  1016  3839 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 08:43:56.581  1016  3839 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 08:43:56.581  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 08:43:56.581  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 08:43:56.601  6821  6821 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 08:43:56.601  6821  6821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 08:43:56.601  6821  6821 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d2d6109 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@308fb336, 16908290=android.view.AbsSavedState$1@308fb336}, android:focusedViewId=100}]}]
08-23 08:43:56.601  6821  6821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 08:43:56.601  6821  6821 V ActivityThread: updateVisibility : ActivityRecord{157f3f40 token=android.os.BinderProxy@e59077d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 08:43:56.601  6821  6821 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 08:43:56.601  6821  6821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 08:43:56.601  6821  6821 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e59077d time:115724
,08-23 08:43:56.611  1016  1478 D PersonaManager: isKioskContainerExistOnDevice
,08-23 08:43:56.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:43:57.011   294   294 E SMD     : DCD OFF
,08-23 08:43:57.091  1016  3831 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 08:43:57.091  1016  3831 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 08:43:57.091  1016  3831 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-23 08:43:57.091  1016  3831 D BatteryService: stay LED for fully charged
08-23 08:43:57.091  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 08:43:57.091  1016  1016 I MotionRecognitionService: Plugged
,08-23 08:43:57.091  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 08:43:57.101  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 08:43:57.101  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 08:43:57.101  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 08:43:57.101  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 08:43:57.111  3161  3161 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 08:43:57.111  3161  3272 D HeadsetStateMachine: Disconnected process message: 10
,08-23 08:43:57.121  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:43:57.131  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 08:43:57.131  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:43:57.641  1016  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-23 08:43:57.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:43:58.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 08:43:59.401  1016  1041 W ActivityManager: mDVFSHelper.release(),
,08-23 08:43:59.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:43:59.991  1016  1094 V AlarmManager: waitForAlarm result :8
,08-23 08:44:00.011   294   294 E SMD     : DCD OFF
,08-23 08:44:00.731   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-23 08:44:00.881  1016  1094 V AlarmManager: waitForAlarm result :4
,08-23 08:44:00.881  1016  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-23 08:44:00.901  1940  1940 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-23 08:44:00.911  1016  1016 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-23 08:44:00.911  1016  1016 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-23 08:44:00.911  1016  1016 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-23 08:44:00.911  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 08:44:00.911  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 08:44:00.921  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 08:44:00.931  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 08:44:00.941  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 08:44:00.941  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-23 08:44:00.941  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,08-23 08:44:00.951  1016  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:00.951  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-23 08:44:00.951  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:00.951  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:00.951  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:00.971  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 08:44:00.971  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 08:44:00.971  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 08:44:01.001  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 08:44:01.031  4870  4870 D ConnectivityManager: CallingUid : 10011, CallingPid : 4870
,08-23 08:44:01.031  1016  1491 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 08:44:01.031  1016  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-23 08:44:01.031  1016  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-23 08:44:01.031  1016  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-23 08:44:01.031  4870  6884 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 08:44:01.081  4870  6885 W DriveInitializer: Background init thread started
,08-23 08:44:01.121   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-23 08:44:01.121   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:01.131  4870  6885 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-23 08:44:01.181  1016  1510 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:01.181  1016  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.MonitorService; callingUser = 0; userId(target) = 0
,08-23 08:44:01.181  1016  1510 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:01.181  1016  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:01.181  1016  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.201  1940  1940 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-23 08:44:01.241  4870  6885 W DriveInitializer: Background init thread ended
,08-23 08:44:01.251  1016  1510 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:01.251  1016  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,08-23 08:44:01.251  1016  1510 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:01.261  1016  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 08:44:01.261  1016  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.341  1016  1328 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:01.341  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:01.341  1016  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:01.341  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.351  1016  3840 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:01.351  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:01.351  1016  3840 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:01.351  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.361  1940  1940 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 08:44:01.461  1016  1231 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 08:44:01.461  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 08:44:01.461  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:01.461  1016  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:01.461  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.471  1940  1940 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 08:44:01.471  1940  1940 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 08:44:01.491  1016  3831 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:01.491  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:01.491  1016  3831 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:01.491  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.521  1016  1491 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 08:44:01.531  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-23 08:44:01.531  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:01.531  1016  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:01.531  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.531  1940  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:01.541   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:01.541   277  1001 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 08:44:01.541  1940  6894 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 08:44:01.541  1940  6894 I qtaguid : Tagging socket 63 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1940, getuid(): 10011
,08-23 08:44:01.581  1940  6894 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1940, getuid(): 10011
,08-23 08:44:01.921  1016  1329 I art     : Explicit concurrent mark sweep GC freed 40690(2MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.543ms total 174.319ms
,08-23 08:44:01.931  1940  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:01.931   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:01.931   277  1001 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 08:44:01.941  1016  1510 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:01.941  1016  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-23 08:44:01.941  1940  6894 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 08:44:01.941  1940  6894 I qtaguid : Tagging socket 68 with tag 1000120300000000{268440067,0} for uid -1, pid: 1940, getuid(): 10011
,08-23 08:44:01.941  1016  1510 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:01.941  1016  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:01.941  1016  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:01.961  1016  1329 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-23 08:44:01.961  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-23 08:44:01.971  1940  6894 I qtaguid : Tagging socket 71 with tag 1000120300000000{268440067,0} for uid -1, pid: 1940, getuid(): 10011
,08-23 08:44:01.981  1940  1940 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 08:44:02.001  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:02.001  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:02.001  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.081  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:02.081  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-23 08:44:02.091  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:02.091  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:02.091  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.121  4870  6901 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-23 08:44:02.121  4870  6901 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-23 08:44:02.201  1016  1328 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:02.201  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-23 08:44:02.201  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:02.201  1016  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:02.201  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.211  1940  6894 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:02.211  1940  6894 I qtaguid : Tagging socket 68 with tag 1000120300000000{268440067,0} for uid -1, pid: 1940, getuid(): 10011
,08-23 08:44:02.241  1016  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:02.251  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:02.251  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:02.251  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.291  1016  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:02.291  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:02.291  1016  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:02.291  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.301  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:02.301  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:02.301  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:02.301  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:02.311  6904  6904 E Zygote  : MountEmulatedStorage(),
08-23 08:44:02.311  6904  6904 E Zygote  : v2
08-23 08:44:02.311  6904  6904 I libpersona: KNOX_SDCARD checking this for 10011
08-23 08:44:02.311  6904  6904 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:02.321  6904  6904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 08:44:02.321  1016  1133 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6904 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-23 08:44:02.321  6904  6904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:02.321  6904  6904 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 08:44:02.341  1016  1231 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:02.341  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:02.341  1016  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:02.341  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.361  6904  6904 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:02.361  6904  6904 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:02.381  6904  6904 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-23 08:44:02.381  6904  6904 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 08:44:02.401  1016  3839 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:02.401  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:02.401  1016  3839 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:02.401  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.421  1940  6894 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-23 08:44:02.421  6904  6904 I MultiDex: VM with version 2.1.0 has multidex support
,08-23 08:44:02.421  6904  6904 I MultiDex: install
08-23 08:44:02.421  6904  6904 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 08:44:02.421  1016  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:02.421  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:02.421  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 08:44:02.421  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.431  1940  6894 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,08-23 08:44:02.451  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:02.451  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 08:44:02.451  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:02.451  6904  6904 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 08:44:02.511  6904  6904 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 08:44:02.521  6904  6904 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dd52b9c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 08:44:02.521  6904  6904 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 08:44:02.531  6904  6904 D ChimeraCfgMgr: Reading stored module config
,08-23 08:44:02.581  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 08:44:02.581  6821  6874 I jxcore-log: 
,08-23 08:44:02.581  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 08:44:02.581  6821  6874 I jxcore-log: 
,08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:02.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:44:02.591  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 08:44:02.591  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 08:44:02.591  6821  6874 I jxcore-log: 
,08-23 08:44:02.591  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 08:44:02.591  6821  6874 I jxcore-log: 
,08-23 08:44:02.601  6904  6919 I art     : Background sticky concurrent mark sweep GC freed 22983(1093KB) AllocSpace objects, 2(32KB) LOS objects, 2% free, 7MB/7MB, paused 7.663ms total 50.539ms
,08-23 08:44:02.631  6904  6904 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 08:44:02.631  6904  6904 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 08:44:02.641  6904  6922 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-23 08:44:02.681  6904  6919 I art     : Background partial concurrent mark sweep GC freed 1235(232KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 7.622ms total 62.940ms
,08-23 08:44:02.721   282   699 D WVCdm   : Instantiating CDM.
,08-23 08:44:02.731   282  1014 I WVCdm   : CdmEngine::OpenSession
08-23 08:44:02.731   282  1014 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-23 08:44:02.751   282  1014 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-23 08:44:02.771   282  1014 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-23 08:44:02.831  6904  6912 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-23 08:44:02.831   282  1014 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-23 08:44:02.831  6904  6912 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 08:44:02.831  6904  6912 I System.out: (HTTPLog)-Static: isShipBuild true
08-23 08:44:02.831  6904  6912 I System.out: (HTTPLog)-Thread-1231-722324825: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 08:44:02.831  6904  6912 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:02.831   282   679 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-23 08:44:02.831   282   679 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-23 08:44:02.831   282   679 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-23 08:44:02.831   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:02.831   277  1001 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 08:44:02.841   282   679 D WVCdm   : PrepareKeyRequest: nonce=4268403805
,08-23 08:44:02.841  6904  6912 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 08:44:02.841  6904  6912 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6904, getuid(): 10011
,08-23 08:44:03.011   294   294 E SMD     : DCD OFF
,08-23 08:44:03.041  1016  3419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 08:44:03.091  6904  6912 I qtaguid : Untagging socket 30
,08-23 08:44:03.321  6821  6874 D ExecuteNativeTests: Running unit tests
,08-23 08:44:03.411  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:03.411  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 added. We now have 2 listener(s)
,08-23 08:44:03.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 08:44:03.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:03.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 08:44:03.421  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:03.421  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 added. We now have 2 listener(s)
08-23 08:44:03.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:03.421  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 08:44:03.421  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:03.431  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:44:03.431  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 08:44:03.431  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 08:44:03.431  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:03.431  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 08:44:03.431  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 08:44:03.431  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 08:44:03.431  6821  6874 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-23 08:44:03.431  6821  6874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 08:44:03.431  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 08:44:03.431  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 08:44:03.431  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 08:44:03.431  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 08:44:03.441  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.441  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.441  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:03.441  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 removed from the list
08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.441  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 removed from the list
,08-23 08:44:03.441  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:03.441  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.441  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.441  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.441  6821  6874 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-23 08:44:03.441  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.441  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.441  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.441  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.441  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.441  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.441  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.441  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.441  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.451  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 08:44:03.451  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.451  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.451  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.451  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.451  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.451  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.451  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.451  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.451  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.451  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.451  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.451  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.451  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.451  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.451  6821  6874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 08:44:03.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:03.461  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:44:03.461  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:03.461  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:44:03.461  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:03.461  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:44:03.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:44:03.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:44:03.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 08:44:03.471  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:03.471  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 08:44:03.471  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:03.471  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 08:44:03.481  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 08:44:03.481  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-23 08:44:03.491  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-23 08:44:03.491  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 08:44:03.491  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 08:44:03.491  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 08:44:03.501  3161  3273 D BtGatt.GattService: registerClient() - UUID=0b2d1b59-1c4d-447e-bbe3-37f59a303721
,08-23 08:44:03.541  3161  3263 D BtGatt.GattService: onClientRegistered() - UUID=0b2d1b59-1c4d-447e-bbe3-37f59a303721, clientIf=6
,08-23 08:44:03.551  6821  6832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 08:44:03.551  3161  3171 D BtGatt.GattService: start scan with filters
,08-23 08:44:03.551  3161  3270 D BtGatt.ScanManager: handling starting scan
,08-23 08:44:03.551  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 08:44:03.551  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 08:44:03.551  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 08:44:03.551  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 08:44:03.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:03.561  3161  3270 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:03.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 08:44:03.561  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:03.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 08:44:03.571  6821  6874 I io.jxcore.node.ConnectionHelper: start: OK,
,08-23 08:44:03.571  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 08:44:03.571  6821  6874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 08:44:03.571  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 08:44:03.571  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 08:44:03.571  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 08:44:03.571  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 08:44:03.571  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:44:03.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 08:44:03.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 08:44:03.571  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-23 08:44:03.571  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 08:44:03.581  3161  3169 D BtGatt.GattService: stopScan() - queue size =1
08-23 08:44:03.581  3161  3273 D BtGatt.GattService: unregisterClient() - clientIf=6
08-23 08:44:03.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:44:03.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 08:44:03.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 08:44:03.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 08:44:03.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 08:44:03.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 08:44:03.581  3161  3263 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 08:44:03.581  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.581  3161  3270 D BtGatt.ScanManager: allow scan with filters
08-23 08:44:03.581  3161  3270 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 08:44:03.581  3161  3270 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-23 08:44:03.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 08:44:03.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-23 08:44:03.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 08:44:03.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 08:44:03.591  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:03.591  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.591  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.591  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:03.591  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:03.591  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 08:44:03.591  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
,08-23 08:44:03.591  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:03.591  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.591  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.591  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.591  6821  6874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 08:44:03.591  3161  3263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-23 08:44:03.591  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.591  3161  3270 D BtGatt.ScanManager: Starting BLE batch scan,
08-23 08:44:03.591  3161  3270 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 08:44:03.591  3161  3263 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-23 08:44:03.591  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.591  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:03.601  3161  3263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 08:44:03.601  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:03.601  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:44:03.601  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-23 08:44:03.601  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:44:03.601  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:03.601  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:44:03.601  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:44:03.601  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:44:03.601  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 08:44:03.611  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:03.611  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:03.621  3161  3270 D BtGatt.ScanManager: filter size is 1
08-23 08:44:03.621  3161  3270 D BtGatt.ScanManager: delete FilterIndex - 3
,08-23 08:44:03.621  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 08:44:03.621  3161  3263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 08:44:03.621  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.621  3161  3270 D BtGatt.ScanManager: stopping BLe Batch
,08-23 08:44:03.631  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 08:44:03.631  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 08:44:03.631  3161  3263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-23 08:44:03.631  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.631  3161  3270 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 08:44:03.631  3161  3263 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 08:44:03.631  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.631  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 08:44:03.631  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 08:44:03.631  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 08:44:03.641  3161  3169 D BtGatt.GattService: registerClient() - UUID=c380e9ab-e80c-45d5-b174-8859741ae500
,08-23 08:44:03.671  6930  6930 I dex2oat : ----------------------------------------------------
08-23 08:44:03.671  6930  6930 I dex2oat : <SS>: S T A R T I N G . . .
08-23 08:44:03.671  6930  6930 I dex2oat : <SS>: Zip is absent. Canceled.
,08-23 08:44:03.671  6930  6930 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-23 08:44:03.681  3161  3263 D BtGatt.GattService: onClientRegistered() - UUID=c380e9ab-e80c-45d5-b174-8859741ae500, clientIf=6
,08-23 08:44:03.681  6821  6830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 08:44:03.681  3161  3273 D BtGatt.GattService: start scan with filters
,08-23 08:44:03.681  3161  3270 D BtGatt.ScanManager: handling starting scan
,08-23 08:44:03.691  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 08:44:03.691  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 08:44:03.691  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 08:44:03.691  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 08:44:03.691  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:03.691  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:03.691  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 08:44:03.691  3161  3263 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 08:44:03.691  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.691  3161  3270 D BtGatt.ScanManager: allow scan with filters
08-23 08:44:03.691  3161  3270 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 08:44:03.691  3161  3270 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-23 08:44:03.691  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 08:44:03.701  3161  3263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 08:44:03.701  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.701  3161  3270 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 08:44:03.701  3161  3270 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 08:44:03.701  6821  6874 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 08:44:03.701  3161  3263 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 08:44:03.701  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.701  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.701  6821  6874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 08:44:03.701  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.701  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 08:44:03.701  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.701  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 08:44:03.701  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 08:44:03.701  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:44:03.701  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 08:44:03.701  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 08:44:03.711  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 08:44:03.711  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 08:44:03.711  3161  3171 D BtGatt.GattService: stopScan() - queue size =1
,08-23 08:44:03.711  3161  3169 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 08:44:03.711  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 08:44:03.711  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 08:44:03.711  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 08:44:03.711  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 08:44:03.711  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 08:44:03.711  3161  3263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 08:44:03.711  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.711  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:03.711  3161  3270 D BtGatt.ScanManager: filter size is 1
08-23 08:44:03.711  3161  3270 D BtGatt.ScanManager: delete FilterIndex - 4
,08-23 08:44:03.711  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 08:44:03.711  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 08:44:03.711  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 08:44:03.711  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 08:44:03.721  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:03.721  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.721  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.721  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:03.721  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.721  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.721  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.721  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.721  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.721  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.721  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.721  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.721  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.721  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.721  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.721  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:03.721  6821  6874 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 08:44:03.721  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:03.721  3161  3263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 08:44:03.721  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.721  3161  3270 D BtGatt.ScanManager: stopping BLe Batch
,08-23 08:44:03.731  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:03.731  3161  3263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 08:44:03.731  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.731  3161  3270 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 08:44:03.741  3161  3263 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 08:44:03.741  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:03.741  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:44:03.741  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 08:44:03.741  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 08:44:03.741  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:03.741  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 08:44:03.741  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 08:44:03.741  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:44:03.741  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:03.751  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 08:44:03.751  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:03.751  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 08:44:03.761  6930  6930 I dex2oat : dex2oat took 81.058ms (threads: 4)
,08-23 08:44:03.761  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 08:44:03.761  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 08:44:03.761  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 08:44:03.761  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 08:44:03.761  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 08:44:03.771  3161  3273 D BtGatt.GattService: registerClient() - UUID=fc47ff31-ae26-436f-bde0-7fad8a3c9301
,08-23 08:44:03.781  6904  6912 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 08:44:03.781  6904  6912 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 08:44:03.781  6904  6912 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 08:44:03.781  6904  6912 I Adreno-EGL: Local Branch: 
08-23 08:44:03.781  6904  6912 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 08:44:03.781  6904  6912 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 08:44:03.781  6904  6912 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 08:44:03.811  3161  3263 D BtGatt.GattService: onClientRegistered() - UUID=fc47ff31-ae26-436f-bde0-7fad8a3c9301, clientIf=6
,08-23 08:44:03.811  6821  6832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 08:44:03.811  3161  3171 D BtGatt.GattService: start scan with filters
,08-23 08:44:03.811  3161  3270 D BtGatt.ScanManager: handling starting scan
,08-23 08:44:03.811  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 08:44:03.811  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 08:44:03.811  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 08:44:03.811  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 08:44:03.821  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:03.821  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:03.821  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 08:44:03.821  3161  3263 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-23 08:44:03.821  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.821  3161  3270 D BtGatt.ScanManager: allow scan with filters
08-23 08:44:03.821  3161  3270 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 08:44:03.821  3161  3270 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-23 08:44:03.821  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 08:44:03.821  3161  3263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-23 08:44:03.821  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.821  3161  3270 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 08:44:03.821  3161  3270 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 08:44:03.831  6821  6874 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 08:44:03.831  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.831  6821  6874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 08:44:03.831  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.831  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 08:44:03.831  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 08:44:03.831  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 08:44:03.831  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:44:03.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 08:44:03.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 08:44:03.831  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 08:44:03.831  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 08:44:03.831  3161  3169 D BtGatt.GattService: stopScan() - queue size =1
,08-23 08:44:03.831  3161  3273 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 08:44:03.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 08:44:03.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 08:44:03.831  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 08:44:03.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 08:44:03.831  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 08:44:03.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:03.841  3161  3263 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 08:44:03.841  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 08:44:03.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 08:44:03.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 08:44:03.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 08:44:03.841  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 08:44:03.841  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:03.841  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:03.841  3161  3263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-23 08:44:03.841  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.841  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.841  6821  6874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 08:44:03.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.841  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.841  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:03.841  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.841  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.841  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.851  3161  3270 D BtGatt.ScanManager: filter size is 1
,08-23 08:44:03.851  3161  3270 D BtGatt.ScanManager: delete FilterIndex - 5
,08-23 08:44:03.851  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-23 08:44:03.851  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.851  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.851  6821  6874 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-23 08:44:03.851  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.851  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.851  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.851  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.851  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.851  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:03.851  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.851  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.851  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.851  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.851  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.851  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.851  3161  3263 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-23 08:44:03.851  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.851  3161  3270 D BtGatt.ScanManager: stopping BLe Batch
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.851  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.851  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 08:44:03.851  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.851  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.851  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.851  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.851  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.851  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.851  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.851  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.851  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.851  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.851  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.851  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.851  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.861  6821  6874 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-23 08:44:03.861  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 08:44:03.861  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.861  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.861  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.861  6821  6874 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
08-23 08:44:03.861  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.861  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.861  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.861  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.861  6904  6912 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-23 08:44:03.861  6904  6912 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 08:44:03.861  6904  6912 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 08:44:03.861  6904  6912 I Adreno-EGL: Local Branch: 
08-23 08:44:03.861  6904  6912 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 08:44:03.861  6904  6912 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 08:44:03.861  6904  6912 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 08:44:03.861  3161  3263 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 08:44:03.861  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:03.861  3161  3270 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,08-23 08:44:03.861  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 08:44:03.861  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-23 08:44:03.861  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 08:44:03.861  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.861  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.861  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.861  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.861  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list,
08-23 08:44:03.861  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.861  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.861  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.871  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.871  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 08:44:03.871  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.871  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.871  6821  6874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:44:03.871  6821  6874 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 08:44:03.871  3161  3263 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 08:44:03.871  3161  3263 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:03.871  6821  6874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:44:03.871  6821  6874 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
,08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 08:44:03.871  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 08:44:03.871  6821  6874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 08:44:03.871  6821  6874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 08:44:03.871  6821  6874 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 08:44:03.871  6821  6874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:44:03.871  6821  6874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...,
08-23 08:44:03.871  6821  6874 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 08:44:03.871  6821  6874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:44:03.871  6821  6874 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 08:44:03.871  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 08:44:03.881  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 08:44:03.881  6821  6874 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 08:44:03.881  6821  6874 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:44:03.881  6821  6874 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 08:44:03.881  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 08:44:03.881  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.881  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.881  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.881  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.881  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-23 08:44:03.881  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.881  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.881  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.881  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.881  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.881  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 08:44:03.881  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.881  6821  6939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1319
08-23 08:44:03.881  6821  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1319)
,08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.881  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.881  6821  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1319)
08-23 08:44:03.881  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.881  6821  6874 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-23 08:44:03.891  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.891  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.891  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.891  6821  6874 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-23 08:44:03.891  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.891  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.891  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 08:44:03.891  6821  6874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 08:44:03.891  6821  6874 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 08:44:03.891  6821  6874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 08:44:03.891  6821  6874 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 08:44:03.891  6821  6874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 08:44:03.891  6821  6874 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 08:44:03.891  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.891  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.891  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
,08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.891  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.891  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.891  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.891  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.891  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.901  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.901  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.901  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
,08-23 08:44:03.901  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.901  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.901  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.901  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.901  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.901  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.901  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 08:44:03.901  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.901  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:03.901  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 08:44:03.901  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.901  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 08:44:03.901  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.901  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.901  6821  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-23 08:44:03.901  6821  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 08:44:03.911  6821  6821 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 08:44:03.911  6821  6821 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 08:44:03.911  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:03.911  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.911  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:03.911  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:03.911  6821  6821 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 08:44:03.911  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:03.911  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.911  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.911  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.911  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.911  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.911  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.911  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.911  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.911  6904  6912 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 08:44:03.911  6904  6912 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 08:44:03.911  6904  6912 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 08:44:03.911  6904  6912 I Adreno-EGL: Local Branch: 
08-23 08:44:03.911  6904  6912 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 08:44:03.911  6904  6912 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 08:44:03.911  6904  6912 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-23 08:44:03.911  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.911  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.911  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.911  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.911  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.911  6821  6874 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-23 08:44:03.911  6821  6874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 08:44:03.911  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 08:44:03.911  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.911  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 08:44:03.911  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.911  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.911  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.911  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
,08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:03.911  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.911  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 08:44:03.911  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.911  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.911  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-23 08:44:03.911  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 08:44:03.911  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.911  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.921  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.921  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.921  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.921  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.921  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.921  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.921  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.921  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.921  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.921  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.921  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.921  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.921  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.921  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:03.921  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:03.921  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:03.921  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.921  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.921  6821  6874 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f09d727 not in the list
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.921  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
08-23 08:44:03.921  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:03.921  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.921  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:03.921  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:03.921  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:03.921  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:03.921  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e8add4 not in the list
,08-23 08:44:03.921  6821  6874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 08:44:03.921  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 08:44:03.921  6821  6874 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 08:44:03.921  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 08:44:03.921  6821  6874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 08:44:03.921  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-23 08:44:03.931  6821  6874 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 08:44:03.931  6821  6874 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 08:44:03.931  6821  6874 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 08:44:03.931  6821  6874 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-23 08:44:03.931  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:03.931  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c490496 added. We now have 2 listener(s)
08-23 08:44:03.931  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:03.931  6821  6874 D BluetoothAdapter: enable(),
,08-23 08:44:03.931  6821  6874 D BluetoothAdapter: enable(): BT is already enabled..!,
,08-23 08:44:03.951  1016  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 08:44:03.951  1016  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 08:44:03.951  1016  1491 D SecContentProvider2: mCursor = null
08-23 08:44:03.951  1016  1491 D WifiService: setWifiEnabled: true pid=6821, uid=10171
,08-23 08:44:03.961  1016  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-23 08:44:03.961  1016  1491 W WifiService: Failed getting userId using ActivityManagerNative
08-23 08:44:03.961  1016  1491 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 08:44:03.961  1016  1491 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 08:44:03.961  1016  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 08:44:03.961  1016  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 08:44:03.961  1016  1491 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 08:44:03.961  1016  1491 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 08:44:03.971  1016  1491 D SettingsProvider: name = wifi_on
,08-23 08:44:03.971  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:03.971  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c80d817 added. We now have 3 listener(s)
08-23 08:44:03.971  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:03.971  1016  3385 D SSRM:n  : SIOP:: AP = 320
,08-23 08:44:03.971  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:44:03.971  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d7d3404 added. We now have 4 listener(s)
08-23 08:44:03.971  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:03.971  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:44:03.971  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3408ded added. We now have 5 listener(s)
08-23 08:44:03.971  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:03.981  1016  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 08:44:03.981  1016  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 08:44:03.981  1016  1491 D SecContentProvider2: mCursor = null
,08-23 08:44:03.981  1016  1491 D SettingsProvider: name = wifi_on
,08-23 08:44:03.981  1016  1491 D WifiService: setWifiEnabled: false pid=6821, uid=10171
,08-23 08:44:03.991  1016  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-23 08:44:03.991  1389  1389 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 08:44:03.991  1389  1389 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-23 08:44:03.991  1389  1389 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 08:44:03.991  1389  1389 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 08:44:04.001  6821  6874 D BluetoothAdapter: disable()
,08-23 08:44:04.001  1016  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 08:44:04.011  1016  1510 D SettingsProvider: name = bluetooth_on
,08-23 08:44:04.011  1016  1125 E WifiNative-wlan0: do suspend true
,08-23 08:44:04.021  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:04.021  3161  3260 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-23 08:44:04.021  3161  3260 D BluetoothAdapterProperties: Setting state to 13
08-23 08:44:04.021  3161  3260 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 08:44:04.021  3161  3260 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 08:44:04.021  3161  3260 D BluetoothAdapterService: updateAdapterState state is 13
,08-23 08:44:04.021  1016  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:04.021  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 08:44:04.021  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:04.021  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.021  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:04.021  3161  3161 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-23 08:44:04.021  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:04.021  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:44:04.021  3161  3260 D BluetoothAdapterService: Autoconnection is available 
,08-23 08:44:04.021  3161  3260 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-23 08:44:04.031  3161  3260 D BluetoothAdapterService: terminating service from this receiver
08-23 08:44:04.031  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.031  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 08:44:04.031  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 08:44:04.031  3161  3161 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@270215d2, channel: 19, state: LISTENING
08-23 08:44:04.031  3161  3161 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@270215d2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d3ed17a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7bb5da0mSocket: android.net.LocalSocket@2b0dcd59 impl:android.net.LocalSocketImpl@3547bd1e fd:FileDescriptor[74]
,08-23 08:44:04.031  3161  3161 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b0dcd59 impl:android.net.LocalSocketImpl@3547bd1e fd:FileDescriptor[74]
,08-23 08:44:04.031  1016  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 08:44:04.031  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.031  1016  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.031  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.031  3161  3260 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 08:44:04.031  3161  3260 D BluetoothAdapterProperties: mDiscovering is false
,08-23 08:44:04.031  1016  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 08:44:04.031  3161  3260 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
,08-23 08:44:04.041  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:04.041  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-23 08:44:04.041  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:04.041  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-23 08:44:04.061  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-23 08:44:04.061  1827  1827 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 08:44:04.061  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 08:44:04.061  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:04.061  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-23 08:44:04.061  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:04.061  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:04.071  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:04.071  1016  3831 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:04.071  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 08:44:04.071  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 08:44:04.081  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:04.081  1016  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 08:44:04.081  1016  3831 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 08:44:04.081  1016  3839 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 08:44:04.081  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 08:44:04.081  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:04.081  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:04.081  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:44:04.081  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.081  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 08:44:04.081  3161  3263 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 08:44:04.081  3161  3263 D BluetoothAdapterProperties: Scan Mode:20
,08-23 08:44:04.091  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:04.091  3161  3260 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 08:44:04.091  3161  3260 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-23 08:44:04.091  3320  3320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 08:44:04.091  1016  1478 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 08:44:04.091  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 08:44:04.101  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.101  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.101  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 08:44:04.101  3161  3260 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-23 08:44:04.101  3161  3260 E bt-btif : BTA got event 0x1a1c
,08-23 08:44:04.101  3161  5181 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-23 08:44:04.101  3161  3260 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-23 08:44:04.101  3161  3286 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-23 08:44:04.101  3161  3286 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-23 08:44:04.111  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:44:04.111  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:04.111  3161  3286 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:44:04.111  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:04.111  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:04.111  3320  3320 D BluetoothPbap: Proxy object disconnected
08-23 08:44:04.111  3320  3320 D PbapServerProfile: Bluetooth service disconnected
,08-23 08:44:04.111  3161  3161 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e5ed9ff, channel: 5, state: LISTENING
,08-23 08:44:04.111  3161  3161 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e5ed9ff, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ee8d2b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f08b3ccmSocket: android.net.LocalSocket@1944e615 impl:android.net.LocalSocketImpl@9ae8d2a fd:FileDescriptor[76]
08-23 08:44:04.111  3161  3161 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1944e615 impl:android.net.LocalSocketImpl@9ae8d2a fd:FileDescriptor[76]
,08-23 08:44:04.121  3161  3161 I BtOppRfcommListener: stopping Accept Thread
08-23 08:44:04.121  3161  3161 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26d1171b, channel: 12, state: LISTENING
08-23 08:44:04.121  3161  3161 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26d1171b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b14085d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35f340b8mSocket: android.net.LocalSocket@1c9ace91 impl:android.net.LocalSocketImpl@2e0051f6 fd:FileDescriptor[80]
08-23 08:44:04.121  3161  3161 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c9ace91 impl:android.net.LocalSocketImpl@2e0051f6 fd:FileDescriptor[80]
,08-23 08:44:04.121  3161  5181 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 08:44:04.131  3161  3161 V BluetoothOppManager: cleanUp...
,08-23 08:44:04.131  3320  3320 D DockEventReceiver: finishStartingService: stopping service
,08-23 08:44:04.141  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:04.141  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:04.141  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-23 08:44:04.141  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 08:44:04.151  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.151  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.151  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.151  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.161  6947  6947 E Zygote  : MountEmulatedStorage()
,08-23 08:44:04.161  6947  6947 E Zygote  : v2
08-23 08:44:04.161  6947  6947 I libpersona: KNOX_SDCARD checking this for 10055
08-23 08:44:04.161  6947  6947 I libpersona: KNOX_SDCARD not a persona,
,08-23 08:44:04.161  6947  6947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:04.161  1016  1328 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6947 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 08:44:04.171  6947  6947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:04.171  6947  6947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:04.211  6947  6947 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:04.211  6947  6947 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:04.221  4337  4355 I art     : Explicit concurrent mark sweep GC freed 1516(52KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 699us total 32.781ms
,08-23 08:44:04.221  1940  6903 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:04.231   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:04.231   277  1001 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 08:44:04.231  1940  6903 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
08-23 08:44:04.231  1940  6903 I qtaguid : Tagging socket 74 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1940, getuid(): 10011
,08-23 08:44:04.241  6947  6947 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-23 08:44:04.271  6947  6947 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-23 08:44:04.271  6947  6947 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-23 08:44:04.271  6947  6947 D UserAnalysis: Create SecureDbHelper
,08-23 08:44:04.281  6947  6947 D IntelligenceServiceApplication: onCreate()
,08-23 08:44:04.281  1016  1328 I ActivityManager: Killing 6518:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-23 08:44:04.281  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-23 08:44:04.291  6947  6947 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-23 08:44:04.291  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.291  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.291  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.291  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.301  6966  6966 E Zygote  : MountEmulatedStorage()
,08-23 08:44:04.301  6966  6966 E Zygote  : v2
08-23 08:44:04.301  6966  6966 I libpersona: KNOX_SDCARD checking this for 10105
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:44:04.301  6966  6966 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:04.301  1016  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6966 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:04.301  3161  3286 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:44:04.301  3161  3286 W bt-btif : ag scb idx 1 not allocated
08-23 08:44:04.301  3161  3286 W bt-btif : ag scb idx 2 not allocated
08-23 08:44:04.301  3161  3286 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 08:44:04.301  3161  3340 I bt_userial_mct: exiting userial_read_thread
08-23 08:44:04.301  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-23 08:44:04.301  3161  3340 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-23 08:44:04.301  3161  3263 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 08:44:04.301  6966  6966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:04.301  3161  3288 I bt_vendor: hw_epilog_process
08-23 08:44:04.301  3161  3263 D bt_userial_mct: userial_close
08-23 08:44:04.301  3161  3263 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-23 08:44:04.311  6947  6947 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,08-23 08:44:04.311  6966  6966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 08:44:04.311  6966  6966 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 08:44:04.311  6947  6947 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-23 08:44:04.321  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:04.331  6966  6966 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:04.411  6821  6821 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 08:44:04.431   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 08:44:04.431   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:04.431  6966  6986 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 08:44:04.431   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 08:44:04.431   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:04.431  6966  6986 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 08:44:04.441   282   282 I WVCdm   : CdmEngine::CloseSession
,08-23 08:44:04.451   282   282 I WVCdm   : L3 Terminate.
,08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.k.d(PG:583)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.581  6966  6966 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:04.581  6966  6966 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:04.591  3161  3263 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 08:44:04.591  1016  1478 I ActivityManager: Killing 6412:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-23 08:44:04.591  3161  3263 I bt_vendor: bluetooth satus is on
08-23 08:44:04.591  3161  3263 I bt_vendor: bt-vendor : resetting BT status
08-23 08:44:04.591  3161  3263 I bt_vendor: Starting hciattach daemon
08-23 08:44:04.591  3161  3263 I bt_vendor: try to set false
08-23 08:44:04.591  3161  3263 I bt_vendor: Starting hciattach daemon
08-23 08:44:04.591  3161  3263 I bt_vendor: try to set false
08-23 08:44:04.591  3161  3263 I bt_vendor: cleanup
08-23 08:44:04.591  3161  3286 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 08:44:04.591  3161  3263 I GKI_LINUX: GKI_exit_task 0 done
08-23 08:44:04.591  3161  3263 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 08:44:04.591  3161  3260 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 08:44:04.591  3161  3260 D BtConfig.SecureMode: isSecureModeOn:false
08-23 08:44:04.591  3161  3260 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-23 08:44:04.591  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 08:44:04.591  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 08:44:04.591  3161  3260 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-23 08:44:04.591  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-23 08:44:04.601  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:04.601  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-23 08:44:04.601  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.601  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.601  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.601  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-23 08:44:04.611  3161  3161 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 08:44:04.611  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 08:44:04.611  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 08:44:04.611  3161  3161 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 08:44:04.611  3161  3161 D BtGatt.GattService: stop()
08-23 08:44:04.611  3161  3161 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 08:44:04.611  3161  3260 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-23 08:44:04.611  1016  3840 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:04.611  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-23 08:44:04.611  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.611  1016  3840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.611  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.611  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:04.611  1389  1389 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
08-23 08:44:04.611  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 08:44:04.611  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 08:44:04.611  3161  3260 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-23 08:44:04.611  1016  1124 D WifiP2pService: InactiveState{ what=147461 }
08-23 08:44:04.611  1016  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
08-23 08:44:04.611  1016  1124 D WifiP2pService: DefaultState{ what=147461 }
08-23 08:44:04.611  1016  1124 D WifiP2pService: InactiveState{ what=143375 }
08-23 08:44:04.611  1016  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-23 08:44:04.611   277  1005 D CommandListener: Clearing all IP addresses on wlan0
08-23 08:44:04.611  1016  1231 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:04.611  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 08:44:04.621  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.621  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.621  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.621  1940  3066 V NativeCrypto: Read error: ssl=0xb7f43be8: I/O error during system call, Connection timed out
08-23 08:44:04.621  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-23 08:44:04.621  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-23 08:44:04.621  3161  3260 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-23 08:44:04.621  1940  6903 I qtaguid : Untagging socket 74
08-23 08:44:04.621  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:04.621  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-23 08:44:04.621  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:04.621  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.621  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:44:04.621  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.621  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-23 08:44:04.621  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.621  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:04.631  1940  3066 V NativeCrypto: SSL shutdown failed: ssl=0xb7f43be8: I/O error during system call, Broken pipe
08-23 08:44:04.631  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-23 08:44:04.631  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 08:44:04.631  1016  1124 D WifiP2pService: InactiveState{ what=131204 }
08-23 08:44:04.631  1016  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-23 08:44:04.631  3161  3260 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-23 08:44:04.631  1016  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:04.631  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-23 08:44:04.631  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.631  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.631  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.631  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-23 08:44:04.631  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 08:44:04.631  1940  3066 E GCM     : Wifi connection closed with errorCode 20
08-23 08:44:04.631  3161  3260 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:04.641  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.641  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:04.641  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.651  1016  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-23 08:44:04.651  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 08:44:04.651  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:04.651  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-23 08:44:04.651  1016  1149 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:04.651  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:04.651  1016  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 08:44:04.651  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-23 08:44:04.651  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.651  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.651  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.651  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 08:44:04.651  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:04.661  3161  3260 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-23 08:44:04.661  1016  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:04.661  1016  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 08:44:04.661  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.661  1016  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.661  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:04.661  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-23 08:44:04.661  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 08:44:04.661  3161  3260 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 08:44:04.661  1016  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-23 08:44:04.661  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.661  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:04.661  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.661  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 08:44:04.661  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 08:44:04.661  1016  1124 D WifiP2pService: P2pDisablingState
,08-23 08:44:04.661  2201  2201 I Hs20UtilService: Starting #8
,08-23 08:44:04.671  2201  2217 I Hs20UtilService: Message received 5007
,08-23 08:44:04.671  1016  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:04.671  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 08:44:04.671  6966  6993 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 08:44:04.671  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-23 08:44:04.671  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 08:44:04.671  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-23 08:44:04.681  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.681  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:04.681  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:04.681  1016  1377 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:04.681  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:04.681  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 08:44:04.681  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-23 08:44:04.681  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 08:44:04.681  1016  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-23 08:44:04.681  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 08:44:04.681  3161  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 08:44:04.681  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-23 08:44:04.681  3161  3260 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 08:44:04.681  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-23 08:44:04.681  3161  3260 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 08:44:04.681  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-23 08:44:04.681  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-23 08:44:04.681  1016  1046 D WifiDisplayController: disconnect
08-23 08:44:04.681  1016  1125 E WifiNative-wlan0: do suspend true
08-23 08:44:04.681  1016  1124 D WifiP2pService: p2p socket connection lost
08-23 08:44:04.681  3161  3161 D HeadsetService: Received stop request...Stopping profile...,
08-23 08:44:04.681  1016  1046 D WifiDisplayController: updateConnection
,08-23 08:44:04.681  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 08:44:04.691  1940  6903 W GLSUser : [AppCertManager] IOException while requesting key: 
08-23 08:44:04.691  1940  6903 W GLSUser : java.net.SocketTimeoutException: failed to connect to android.clients.google.com/216.58.209.78 (port 443) after 30000ms: isConnected failed: ETIMEDOUT (Connection timed out)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at libcore.io.IoBridge.isConnected(IoBridge.java:236)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at java.net.Socket.connect(Socket.java:882)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at dja.a(:com.google.android.gms:233)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at dxt.a(:com.google.android.gms:263)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at dxl.a(:com.google.android.gms:113)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at jch.run(:com.google.android.gms:17)
08-23 08:44:04.691  1940  6903 W GL,SUser : 	at java.lang.Thread.run(Thread.java:818)
08-23 08:44:04.691  1940  6903 W GLSUser : Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
08-23 08:44:04.691  1940  6903 W GLSUser : 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
08-23 08:44:04.691  1940  6903 W GLSUser : 	... 32 more
08-23 08:44:04.681  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 08:44:04.691  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 08:44:04.681  1016  1124 D WifiP2pService: P2pDisabledState
08-23 08:44:04.691  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:04.691  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-23 08:44:04.691  1016  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
08-23 08:44:04.691  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 08:44:04.691  1016  1124 D WifiP2pService: DefaultState{ what=143375 }
08-23 08:44:04.691  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-23 08:44:04.691  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-23 08:44:04.691  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:04.691  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 08:44:04.691  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-23 08:44:04.701  1016  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 08:44:04.701  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 08:44:04.701  3161  3161 D A2dpService: Received stop request...Stopping profile...
08-23 08:44:04.701  3161  3277 D A2dpStateMachine: Exit Disconnected: -1
08-23 08:44:04.701  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:04.701  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:04.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.701  3320  3320 D HeadsetProfile: Bluetooth service disconnected
,08-23 08:44:04.701  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:04.701  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-12ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:04.701  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-23 08:44:04.701  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:04.701  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-23 08:44:04.701  1016  1716 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:04.701  1016  1716 I qtaguid : Tagging socket 370 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
,08-23 08:44:04.701  1016  1716 I qtaguid : Untagging socket 370
08-23 08:44:04.701  1016  1716 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:04.711  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 08:44:04.711  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 08:44:04.711  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 08:44:04.711  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-23 08:44:04.711  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-23 08:44:04.711  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 08:44:04.711  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:04.711  1016  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-23 08:44:04.711  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.711  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.711  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.711  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.731   277  1005 D CommandListener: Clearing all IP addresses on wlan0
08-23 08:44:04.731  7004  7004 I libpersona: KNOX_SDCARD checking this for 10064
08-23 08:44:04.731   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:04.731  7004  7004 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:04.731   277  1001 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-23 08:44:04.731  1016  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-23 08:44:04.731  7004  7004 E Zygote  : MountEmulatedStorage()
08-23 08:44:04.731  1016  1127 V NetworkStats: updateIfacesLocked()
08-23 08:44:04.731  7004  7004 E Zygote  : v2
08-23 08:44:04.731  1016  1127 V NetworkStats: performPollLocked(flags=0x1)
08-23 08:44:04.731  7004  7004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:04.731  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.731  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:04.731  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:04.741  1016  1491 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7004 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-23 08:44:04.741  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-23 08:44:04.741  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-23 08:44:04.741  7004  7004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:04.741  7004  7004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:04.741  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:04.741  1016  1127 V NetworkStats: performPollLocked() took 7ms
08-23 08:44:04.741  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
08-23 08:44:04.741  1389  1389 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-23 08:44:04.741  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 08:44:04.751  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:04.751  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:04.751  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.751  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.751  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.751  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:04.751  3161  3161 D HidService: Received stop request...Stopping profile...
08-23 08:44:04.751  3161  3161 D HidService: Stopping Bluetooth HidService
08-23 08:44:04.751  3161  3161 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 08:44:04.751  3161  3161 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-23 08:44:04.751  3161  3161 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 08:44:04.751  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:04.751  1016  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-23 08:44:04.751  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-23 08:44:04.751  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 08:44:04.751  3320  3320 D BluetoothA2dp: Proxy object disconnected
08-23 08:44:04.751  3320  3320 D A2dpProfile: Bluetooth service disconnected
,08-23 08:44:04.751  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:04.751  1016  1125 D SecContentProvider2: mCursor = null
08-23 08:44:04.751  1177  1699 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-23 08:44:04.761  1016  1716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 08:44:04.761  4870  6884 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-23 08:44:04.761  1016  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 08:44:04.761  1016  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 08:44:04.761  1016  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-23 08:44:04.761  1444  1444 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 08:44:04.761  1016  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-23 08:44:04.761  1444  1444 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 08:44:04.761  1016  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-23 08:44:04.761  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:04.761  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 08:44:04.761  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:04.761  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.761  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.761  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:04.771  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:04.771  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-23 08:44:04.771  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0),
08-23 08:44:04.771  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-23 08:44:04.771  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:04.771  1177  1177 D HotspotTile: onReceive : 0, 0
,08-23 08:44:04.771  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.771  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.771  1016  1329 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:04.771  3161  3161 D HealthService: Received stop request...Stopping profile...
08-23 08:44:04.771  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:04.771  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:04.781  3320  3320 D BluetoothInputDevice: Proxy object disconnected
08-23 08:44:04.781  3320  3320 D HidProfile: Bluetooth service disconnected
,08-23 08:44:04.781  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.781  1016  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:04.781  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-23 08:44:04.781  7004  7004 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:04.781  1016  1328 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:04.781  7004  7004 D ActivityThread: Added TimaKeyStore provider
08-23 08:44:04.781  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
08-23 08:44:04.781  1016  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-23 08:44:04.781  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:04.781  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:44:04.781  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.781  1016  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:04.781  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:04.781  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.781  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:44:04.781  1016  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-23 08:44:04.781  1016  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-23 08:44:04.781  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:04.781  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:04.781  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 08:44:04.791  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-23 08:44:04.791  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:04.791  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:04.791  3161  3161 D PanService: Received stop request...Stopping profile...
08-23 08:44:04.791  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:04.791  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.791  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:44:04.791  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-23 08:44:04.791  1016  1128 D Tethering: MasterInitialState.processMessage what=3
,08-23 08:44:04.791  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.791  1016  1122 V NetworkStats: updateIfacesLocked()
08-23 08:44:04.791  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-23 08:44:04.801  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:04.801  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-23 08:44:04.801  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-23 08:44:04.801  1016  1122 V NetworkStats: performPollLocked() took 5ms
,08-23 08:44:04.801  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.801  3320  3320 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 08:44:04.801  3320  3320 D PanProfile: Bluetooth service disconnected
08-23 08:44:04.801  3161  3161 D BluetoothMapService: Received stop request...Stopping profile...
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:04.801  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.801  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:04.801  1389  1389 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 08:44:04.801  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-23 08:44:04.811  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:04.811  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.811  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.811  1016  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-23 08:44:04.811  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.811  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:04.811  3161  3161 D SapService: Received stop request...Stopping profile...
,08-23 08:44:04.811  3161  3161 D SapService: Stopping Bluetooth SapService
08-23 08:44:04.811  3161  3161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:04.811  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.811  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:04.821  3320  3320 D BluetoothMap: Proxy object disconnected
08-23 08:44:04.821  3320  3320 D MapProfile: Bluetooth service disconnected
,08-23 08:44:04.821  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-23 08:44:04.821  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:04.821  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 08:44:04.821  3320  3320 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-23 08:44:04.821  3320  3320 D SapProfile: Bluetooth service disconnected
,08-23 08:44:04.821  7004  7004 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 08:44:04.821  3161  3161 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 08:44:04.821  3161  3161 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 08:44:04.821  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-23 08:44:04.821  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:04.821  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-23 08:44:04.821  3161  3161 D BluetoothA2dp: Proxy object disconnected
08-23 08:44:04.821  3161  3161 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-23 08:44:04.831  3161  3278 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 08:44:04.831  3161  3161 I GKI_LINUX: GKI_exit_task 2 done
08-23 08:44:04.831  3161  3161 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 08:44:04.831  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-23 08:44:04.831  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:04.831  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:04.831  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-23 08:44:04.831  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:04.831  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:04.831  3161  3161 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 08:44:04.831  3161  3161 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 08:44:04.831  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-23 08:44:04.831  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:04.831  3161  3161 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:04.831  3161  3161 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 08:44:04.831  3161  3161 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-23 08:44:04.831  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-23 08:44:04.831  3161  3161 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-23 08:44:04.831  3161  3161 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-23 08:44:04.831  3161  3161 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-23 08:44:04.831  3161  3161 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-23 08:44:04.831  3161  3161 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-23 08:44:04.831  3161  3260 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-23 08:44:04.831  3161  3260 D BluetoothAdapterProperties: Setting state to 10
08-23 08:44:04.831  3161  3260 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 08:44:04.831  3161  3260 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 08:44:04.831  3161  3260 D BluetoothAdapterService: updateAdapterState state is 10
,08-23 08:44:04.841  3161  3260 D BluetoothAdapterService: Autoconnection is available 
08-23 08:44:04.841  3161  3260 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-23 08:44:04.841  3161  3260 I BluetoothAdapterState: Entering OffState
08-23 08:44:04.841  1428  3271 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.841  1428  3271 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.841  6821  6830 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 08:44:04.841  6821  6830 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 08:44:04.841  6821  6830 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-23 08:44:04.841  6821  6830 D BluetoothLeAdvertiser: Exit stop advertising
08-23 08:44:04.841  6821  6830 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-23 08:44:04.841  6821  6830 D BluetoothLeScanner: Exiting stopAllScan
,08-23 08:44:04.841  1940  2155 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.841  1940  2155 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.851  7004  7004 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 08:44:04.851  1444  3318 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.851  1444  3318 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.851  3320  3331 D Bluetoothsap: onBluetoothStateChange: up=false
,08-23 08:44:04.851  3320  3331 D Bluetoothsap: Unbinding service...
,08-23 08:44:04.851  1437  1460 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.851  1437  1460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.851  3320  3331 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 08:44:04.861  3161  3169 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 08:44:04.861  7004  7004 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 08:44:04.861  3320  3334 D BluetoothMap: onBluetoothStateChange: up=false
,08-23 08:44:04.861  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.861  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 08:44:04.861  3161  3171 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.861  3161  3171 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.861  3320  3331 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.861  3320  3331 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.871  3320  3334 D BluetoothPbap: onBluetoothStateChange: up=false
,08-23 08:44:04.871  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 08:44:04.871  6966  6976 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.871  6966  6976 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.881  1389  1389 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 08:44:04.881  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-23 08:44:04.881  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-23 08:44:04.881  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 08:44:04.881  1177  1195 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:04.881  1177  1195 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:04.881  3320  3331 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-23 08:44:04.881  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-23 08:44:04.891  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-23 08:44:04.901  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:04.901  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-23 08:44:04.901  1389  1389 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-23 08:44:04.901  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-23 08:44:04.901  1389  1389 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-23 08:44:04.901  1389  1389 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-23 08:44:04.901  1389  1389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-23 08:44:04.901  1389  1389 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-23 08:44:04.901  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:04.901  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:04.901  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:04.901  1016  1128 D Tethering: InitialState.processMessage what=4
,08-23 08:44:04.901  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 08:44:04.901  1016  1128 E Tethering: No numeric data
08-23 08:44:04.901  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-23 08:44:04.901  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:04.901  1177  1177 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:04.911  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 08:44:04.911  1177  1702 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:04.911  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:04.911  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-23 08:44:04.911  1177  1177 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:04.911  1016  1329 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 08:44:04.911  1177  1177 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF,
08-23 08:44:04.911  1016  1231 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-23 08:44:04.911  7004  7004 D FileShare-Client: Outbound.stopDelayTimer - 
08-23 08:44:04.911  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-23 08:44:04.911  1177  1702 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:04.911  1827  1827 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 08:44:04.911  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:04.911  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:04.911  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:04.911  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:04.911  1940  2190 D BluetoothAdapter: 625864005: getState() :  mService = null. Returning STATE_OFF,
08-23 08:44:04.911  1940  2190 D BluetoothAdapter: 625864005: getState() :  mService = null. Returning STATE_OFF
,08-23 08:44:04.921  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:04.921  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:04.921  3161  3263 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-23 08:44:04.921  3161  3161 I GKI_LINUX: GKI_exit_task 1 done
08-23 08:44:04.921  1016  1329 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
08-23 08:44:04.921  3161  3161 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-23 08:44:04.921  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.921  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.921  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:04.921  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:04.921  3161  3161 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 08:44:04.921  3161  3161 I art     : System.exit called, status: 0
08-23 08:44:04.921  3161  3161 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 08:44:04.931  7026  7026 E Zygote  : MountEmulatedStorage()
08-23 08:44:04.931  7026  7026 I libpersona: KNOX_SDCARD checking this for 10065
08-23 08:44:04.931  7026  7026 E Zygote  : v2
08-23 08:44:04.931  7026  7026 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:04.931  7026  7026 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:04.931  1016  1329 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7026 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:44:04.941  1016  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:44:04.941  1016  1128 D Tethering: clearTetheredNotification()
,08-23 08:44:04.941  7026  7026 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:04.941  1016  1328 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 08:44:04.941  7026  7026 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:04.941  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.941  1016  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:04.941  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:04.951  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 08:44:04.951  1177  1177 D HotspotTile: updateTetherState():false, false
,08-23 08:44:04.951  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.951  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-23 08:44:04.951  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:04.951  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:04.951  1016  3831 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:04.951  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 08:44:04.951  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:04.951  1016  1122 V NetworkStats: performPollLocked() took 4ms
08-23 08:44:04.951  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:04.951  1016  3831 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:04.951  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 08:44:04.951  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:04.961   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb72b77c8
08-23 08:44:04.961   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-23 08:44:04.961   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-23 08:44:04.961   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1221887864)
,08-23 08:44:04.961  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-23 08:44:04.961  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:04.961  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 08:44:04.961  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
08-23 08:44:04.971  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 08:44:04.971  7026  7026 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:04.971  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 08:44:04.971  7026  7026 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:04.981  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 08:44:04.981  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 08:44:04.981  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:04.981  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 08:44:04.981  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:04.981  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-23 08:44:04.981  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:04.981  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:04.991  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:04.991  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:04.991  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:04.991  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:04.991  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 08:44:04.991  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:05.001  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:05.001  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:05.001  1016  3831 I ActivityManager: Process com.android.bluetooth (pid 3161)(adj 0) has died(28,708)
,08-23 08:44:05.001  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 08:44:05.001  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:05.001  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:05.001  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:05.011  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-23 08:44:05.011  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:05.011  7026  7026 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 08:44:05.011  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 08:44:05.011  1444  1444 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-23 08:44:05.011  1444  1444 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-23 08:44:05.011   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-23 08:44:05.011   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-23 08:44:05.011   271   302 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1221887864) wakelock released: 1, error no: 0
08-23 08:44:05.011   271   302 I rmt_storage: 
,08-23 08:44:05.021   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb72b77c8
,08-23 08:44:05.031  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.031  1016  3839 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-23 08:44:05.031  1016  3839 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:05.031  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-23 08:44:05.031  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:05.031  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:05.031  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:05.031  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:05.041  7056  7056 E Zygote  : MountEmulatedStorage(),
08-23 08:44:05.041  7056  7056 E Zygote  : v2
08-23 08:44:05.041  1016  3839 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7056 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-23 08:44:05.041  7056  7056 I libpersona: KNOX_SDCARD checking this for 10102
08-23 08:44:05.041  7056  7056 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:05.041  1016  3839 I ActivityManager: Killing 6549:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-23 08:44:05.041  7056  7056 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:05.051  7056  7056 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:05.051  7056  7056 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 08:44:05.061  1389  1389 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 08:44:05.081  7056  7056 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:05.081  7056  7056 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:05.091  7056  7056 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 08:44:05.101  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:05.101  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:05.101  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-23 08:44:05.101  1389  1389 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-23 08:44:05.201  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-23 08:44:05.201  1016  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 08:44:05.211  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:05.211  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-23 08:44:05.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:05.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:05.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:05.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:05.211  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:05.211  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-23 08:44:05.211  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 08:44:05.221  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:05.221  1940  2190 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:44:05.221  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:05.221  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:05.221  1177  1177 D HotspotTile: onReceive : 1, 0
,08-23 08:44:05.231  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:05.281  1016  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:05.281  1016  1016 I ApplicationPolicy: updateDataUsageMap
,08-23 08:44:05.301  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:05.301  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:05.301  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:05.331  1016  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:05.341  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.341  1016  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 08:44:05.341  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:05.341  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-23 08:44:05.361  1016  1377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:05.361  1016  1377 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.361  1016  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:05.361  1016  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:05.371  7056  7084 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-23 08:44:05.371  7056  7084 I Babel_SMS: MmsConfig.loadMmsSettings
,08-23 08:44:05.371  7056  7084 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-23 08:44:05.371  7056  7084 I Babel_SMS: MmsConfig.loadFromDatabase
,08-23 08:44:05.391  7056  7084 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-23 08:44:05.391  7056  7084 I Babel_SMS: MmsConfig.loadFromResources
,08-23 08:44:05.401  1016  1478 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 08:44:05.401  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 08:44:05.401  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.401  7056  7084 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-23 08:44:05.401  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:05.401  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:05.401  7056  7084 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-23 08:44:05.411  1940  1940 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=a37d19d7-8d22-4f3e-a40f-66e443f4145d
,08-23 08:44:05.441  1016  1478 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-23 08:44:05.441  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-23 08:44:05.441  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.441  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:05.441  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 08:44:05.461  7056  7056 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:44:05.461  7056  7056 I Babel_Crash: startup - clean
,08-23 08:44:05.511  1016  1329 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 08:44:05.511  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:05.511  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.511  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.511  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:05.511  2201  2201 I Hs20UtilService: Starting #9
,08-23 08:44:05.521  2201  2217 I Hs20UtilService: Message received 5007
,08-23 08:44:05.521  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 08:44:05.521  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 08:44:05.521  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 08:44:05.521  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 08:44:05.521  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:05.521  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 08:44:05.521  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:05.531  1016  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 08:44:05.531  1016  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:05.531  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.531  7056  7056 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 08:44:05.531  1016  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.531  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:05.531  2201  2201 I Hs20UtilService: Starting #10
,08-23 08:44:05.541  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:05.541  7056  7056 W AudioCapabilities: Unsupported mime audio/evrc
,08-23 08:44:05.541  7056  7056 W AudioCapabilities: Unsupported mime audio/qcelp
,08-23 08:44:05.541  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 08:44:05.541  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 08:44:05.541  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 08:44:05.541  7056  7056 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-23 08:44:05.541  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 08:44:05.541  7056  7056 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-23 08:44:05.551  7056  7056 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-23 08:44:05.551  7056  7056 W AudioCapabilities: Unsupported mime audio/x-ima
,08-23 08:44:05.551  7056  7056 W AudioCapabilities: Unsupported mime audio/qcelp
,08-23 08:44:05.561  7056  7056 W AudioCapabilities: Unsupported mime audio/evrc
,08-23 08:44:05.561  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.561  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.561  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.561  1940  2153 W GCoreFlp: No location to return for getLastLocation()
,08-23 08:44:05.571  7056  7056 W VideoCapabilities: Unsupported mime video/wvc1
,08-23 08:44:05.571  7056  7056 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-23 08:44:05.581  7056  7056 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-23 08:44:05.591  7056  7056 W VideoCapabilities: Unsupported mime video/wvc1
08-23 08:44:05.591  7056  7056 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-23 08:44:05.591  7056  7056 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
08-23 08:44:05.591  7056  7056 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-23 08:44:05.611  7056  7056 W VideoCapabilities: Unsupported mime video/mp43
,08-23 08:44:05.631  7056  7056 W VideoCapabilities: Unsupported mime video/sorenson
,08-23 08:44:05.641  7056  7056 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-23 08:44:05.651  7056  7056 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-23 08:44:05.671  1016  1043 D Tethering: interfaceRemoved wlan0
,08-23 08:44:05.671  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-23 08:44:05.681  7056  7056 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 08:44:05.681  7056  7056 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 08:44:05.691  7056  7056 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 08:44:05.691  7056  7056 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 08:44:05.701  1940  2195 I art     : Explicit concurrent mark sweep GC freed 90008(4MB) AllocSpace objects, 21(788KB) LOS objects, 40% free, 11MB/19MB, paused 1.476ms total 116.648ms
,08-23 08:44:05.701  7056  7056 I vclib   : onServiceConnected
,08-23 08:44:05.731  1016  3839 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:05.731  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.731  1016  3839 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:05.731  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:05.731  1016  3840 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 08:44:05.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:05.731  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.731  1016  3840 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:05.731  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:05.741  1016  1478 I ActivityManager: Killing 6601:com.samsung.android.sm/1000 (adj 15): empty #21
,08-23 08:44:05.741  1016  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:05.741  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.741  1016  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 08:44:05.751  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 08:44:05.751  4870  7022 D UdcContextInitService: registered all accounts: true
,08-23 08:44:05.761  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.761  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.761  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.761  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.761  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.761  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.771  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.771  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.771  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.771  1940  2177 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 08:44:05.781  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.781  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.781  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.781  1016  1043 D Tethering: interfaceRemoved p2p0
08-23 08:44:05.781  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-23 08:44:05.781  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.781  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.781  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.791  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.791  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.791  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.791  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.791  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.791  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.791  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.791  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.791  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.801  1940  2195 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-23 08:44:05.801  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.801  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.801  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.801  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.801  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.801  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.811  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.811  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.811  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.811  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:05.811  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.811  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:05.811  3320  3320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 08:44:05.811  1016  3840 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 08:44:05.811  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 08:44:05.821  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:05.821  1016  3840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:05.821  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 08:44:05.831  3320  3320 D DockEventReceiver: finishStartingService: stopping service
,08-23 08:44:05.831  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:05.831  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:05.831  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-23 08:44:05.841  1016  1478 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-23 08:44:05.841  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:05.841  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:05.841  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:05.841  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:05.861  7090  7090 E Zygote  : MountEmulatedStorage()
,08-23 08:44:05.861  1016  1478 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7090 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-23 08:44:05.861  7090  7090 E Zygote  : v2
08-23 08:44:05.861  7090  7090 I libpersona: KNOX_SDCARD checking this for 1002
08-23 08:44:05.861  7090  7090 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:05.861  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 08:44:05.861  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:05.861  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:05.891  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:05.891  7090  7090 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:05.911  1016  1329 I ActivityManager: Killing 6577:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-23 08:44:05.911  7090  7090 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-23 08:44:05.911  7090  7090 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 08:44:05.931  1940  2195 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-23 08:44:05.951  7090  7090 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-23 08:44:05.961  1940  2195 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding GattService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding HeadsetService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding A2dpService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding HidService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding HealthService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding PanService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding SapService
,08-23 08:44:05.991  7090  7090 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-23 08:44:06.001  7090  7090 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-23 08:44:06.001  7090  7090 D BtSettings.ProfileConfig: Adding SapClientService
,08-23 08:44:06.001  7090  7090 D BtSettings.ProfileConfig: Adding HidDevService
,08-23 08:44:06.001  7090  7090 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-23 08:44:06.001  1016  3839 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-23 08:44:06.001  1016  3839 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.001  1016  3839 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.001  1016  3839 D SettingsProvider: selectionArgs: false
08-23 08:44:06.001  1016  3839 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.001  1016  3839 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.001  1016  3839 D SettingsProvider: ret = -1
,08-23 08:44:06.001  1016  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-23 08:44:06.001  1016  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.001  1016  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.001  1016  1133 D SettingsProvider: selectionArgs: false
08-23 08:44:06.001  1016  1133 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.001  1016  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.001  1016  1133 D SettingsProvider: ret = -1
,08-23 08:44:06.001  1016  1377 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-23 08:44:06.001  1016  1377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.001  1016  1377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.001  1016  1377 D SettingsProvider: selectionArgs: false
08-23 08:44:06.001  1016  1377 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.001  1016  1377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.001  1016  1377 D SettingsProvider: ret = -1
08-23 08:44:06.011  1016  1231 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-23 08:44:06.011  1016  1231 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.011  1016  1231 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.011  1016  1231 D SettingsProvider: selectionArgs: false
08-23 08:44:06.011  1016  1231 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.011  1016  1231 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.011  1016  1231 D SettingsProvider: ret = -1
,08-23 08:44:06.011  1016  1510 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-23 08:44:06.011  1016  1510 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.011  1016  1510 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 08:44:06.011  1016  1510 D SettingsProvider: selectionArgs: false
08-23 08:44:06.011  1016  1510 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:06.011  1016  1510 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.011  1016  1510 D SettingsProvider: ret = -1
,08-23 08:44:06.011  1016  3840 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-23 08:44:06.011  1016  3840 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.011  1016  3840 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.011  1016  3840 D SettingsProvider: selectionArgs: false
08-23 08:44:06.011  1016  3840 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.011  1016  3840 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.011  1016  3840 D SettingsProvider: ret = -1
,08-23 08:44:06.011  1016  1329 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:06.011  1016  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.011  1016  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.011  1016  1329 D SettingsProvider: selectionArgs: false
,08-23 08:44:06.011  1016  1329 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.011  1016  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.011  1016  1329 D SettingsProvider: ret = -1
,08-23 08:44:06.011  1016  1491 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-23 08:44:06.011  1016  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.011  1016  1094 V AlarmManager: waitForAlarm result :4
08-23 08:44:06.011  1016  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.011  1016  1491 D SettingsProvider: selectionArgs: false
08-23 08:44:06.011  1016  1491 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.011  1016  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.011  1016  1491 D SettingsProvider: ret = -1
,08-23 08:44:06.011  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:06.011  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 08:44:06.011  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.011  1016  1028 D SettingsProvider: selectionArgs: false
08-23 08:44:06.011  1016  1028 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.011  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.011  1016  1028 D SettingsProvider: ret = -1
08-23 08:44:06.011   294   294 E SMD     : DCD OFF
,08-23 08:44:06.021  1016  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:06.021  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.021  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.021  1016  1478 D SettingsProvider: selectionArgs: false
08-23 08:44:06.021  1016  1478 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.021  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.021  1016  1478 D SettingsProvider: ret = -1
08-23 08:44:06.021  1016  1328 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-23 08:44:06.021  1016  1328 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.021  1016  1328 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:06.021  1016  1328 D SettingsProvider: selectionArgs: false
,08-23 08:44:06.021  1016  1328 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.021  1016  1328 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.021  1016  1328 D SettingsProvider: ret = -1
08-23 08:44:06.021  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-23 08:44:06.021  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:06.021  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 08:44:06.021  1016  1029 D SettingsProvider: selectionArgs: false
08-23 08:44:06.021  1016  1029 D SettingsProvider: selectionArgs: 1002
08-23 08:44:06.021  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:06.021  1016  1029 D SettingsProvider: ret = -1
,08-23 08:44:06.031  1016  3831 I ActivityManager: Killing 6651:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-23 08:44:06.031  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 08:44:06.031  1016  3840 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:06.031  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 08:44:06.031  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:06.031  1016  3840 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:06.031  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:06.041  1940  7107 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 08:44:06.041  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 08:44:06.041  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:06.041  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:06.041  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:06.061  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:06.061  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:06.061  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-23 08:44:06.201  1016  1133 I art     : Explicit concurrent mark sweep GC freed 53123(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.491ms total 159.995ms
,08-23 08:44:06.201  1016  1231 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:06.211  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:06.211  1016  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 08:44:06.211  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:06.211  1016  1510 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 08:44:06.211  1016  1510 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:06.221  1016  1510 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:06.221  1016  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:06.221  1016  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:06.221  2201  2201 I Hs20UtilService: Starting #11
,08-23 08:44:06.221  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:06.221  1016  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:06.221  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 08:44:06.221  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-23 08:44:06.221  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 08:44:06.221  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 08:44:06.221  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:06.221  1016  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:06.221  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:06.231  1016  1231 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 08:44:06.231  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.231  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.231  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.231  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.241  1940  7107 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-23 08:44:06.251  7110  7110 E Zygote  : MountEmulatedStorage()
,08-23 08:44:06.251  7110  7110 E Zygote  : v2
08-23 08:44:06.251  7110  7110 I libpersona: KNOX_SDCARD checking this for 1000
08-23 08:44:06.251  7110  7110 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.251  7110  7110 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 08:44:06.251  1016  1231 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7110 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 08:44:06.251  7110  7110 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:06.261  7110  7110 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.271   317   317 I art     : Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 26.228ms
08-23 08:44:06.271  7110  7110 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:06.281  7110  7110 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.291   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 16.465ms
,08-23 08:44:06.311  7110  7110 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 08:44:06.311   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.388ms
,08-23 08:44:06.311  7110  7110 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 08:44:06.311  7110  7110 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-23 08:44:06.321  7110  7110 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-23 08:44:06.321  7110  7110 I PCWCLIENTTRACE_PushUtil: sales region : global
08-23 08:44:06.321  7110  7110 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-23 08:44:06.321  7110  7110 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:06.331  1016  3831 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-23 08:44:06.331  7110  7125 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-23 08:44:06.331  1016  3831 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-23 08:44:06.341  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-23 08:44:06.341  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.341  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.341  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.341  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.351  1745  1745 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 08:44:06.361  7127  7127 E Zygote  : MountEmulatedStorage()
,08-23 08:44:06.361  7127  7127 E Zygote  : v2
08-23 08:44:06.361  7127  7127 I libpersona: KNOX_SDCARD checking this for 10121
08-23 08:44:06.361  7127  7127 I libpersona: KNOX_SDCARD not a persona,
08-23 08:44:06.361  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7127 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-23 08:44:06.361  7127  7127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 08:44:06.361  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
08-23 08:44:06.361  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.361  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.361  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.361  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.361  7127  7127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:06.361  7127  7127 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 08:44:06.391  7142  7142 E Zygote  : MountEmulatedStorage()
08-23 08:44:06.391  7127  7127 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:06.391  7142  7142 I libpersona: KNOX_SDCARD checking this for 10001
08-23 08:44:06.391  7142  7142 E Zygote  : v2
08-23 08:44:06.391  7142  7142 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.391  7142  7142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:06.391  7127  7127 D ActivityThread: Added TimaKeyStore provider,
,08-23 08:44:06.391  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7142 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-23 08:44:06.391  7142  7142 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:06.391  7142  7142 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.401  1016  3831 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-23 08:44:06.401  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.401  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.401  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.401  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.411  2604  2686 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-23 08:44:06.411  7142  7142 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:06.411  7142  7142 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.421  7157  7157 E Zygote  : MountEmulatedStorage()
08-23 08:44:06.421  7157  7157 E Zygote  : v2
08-23 08:44:06.421  7157  7157 I libpersona: KNOX_SDCARD checking this for 10031
08-23 08:44:06.421  7157  7157 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.421  7157  7157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:06.421  7127  7127 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:44:06.421  7127  7127 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 08:44:06.421  7127  7127 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 08:44:06.421  7157  7157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:06.421  1016  3831 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7157 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-23 08:44:06.421  7157  7157 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.431  1745  1745 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-23 08:44:06.431  1745  1745 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-23 08:44:06.431  1745  1745 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-23 08:44:06.431  1745  1745 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-23 08:44:06.431  7127  7127 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:06.441  7127  7127 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-23 08:44:06.441  1745  1745 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 08:44:06.441  1745  1745 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-23 08:44:06.441  1016  1133 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-23 08:44:06.441  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.441  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.441  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.441  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.441  7157  7157 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-23 08:44:06.441  7157  7157 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.451  7172  7172 E Zygote  : MountEmulatedStorage()
,08-23 08:44:06.451  7172  7172 E Zygote  : v2
08-23 08:44:06.451  7172  7172 I libpersona: KNOX_SDCARD checking this for 10077,
08-23 08:44:06.461  7172  7172 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.461  7172  7172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:06.461  1016  1133 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7172 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:44:06.461  7172  7172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:06.461  7172  7172 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.471  7127  7127 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-23 08:44:06.471  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-23 08:44:06.471  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.471  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.471  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.471  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.471  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-23 08:44:06.481  7185  7185 E Zygote  : MountEmulatedStorage()
08-23 08:44:06.481  7185  7185 I libpersona: KNOX_SDCARD checking this for 10141
08-23 08:44:06.481  7185  7185 E Zygote  : v2
08-23 08:44:06.481  7185  7185 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.481  7185  7185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:06.491  7185  7185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:06.491  7185  7185 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.491  1016  1328 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7185 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,08-23 08:44:06.491  7172  7172 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:06.491  1016  1328 I ActivityManager: Killing 6667:com.osp.app.signin/u0a36 (adj 15): empty #21,
08-23 08:44:06.501  7172  7172 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.511  7157  7157 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-23 08:44:06.511  7185  7185 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:06.521  7185  7185 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.521  1016  1329 I ActivityManager: Killing 6683:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-23 08:44:06.531  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-23 08:44:06.541  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.541  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.541  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.541  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.541  2824  7204 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-23 08:44:06.541  2824  7204 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-23 08:44:06.541  2824  7204 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable,
,08-23 08:44:06.551  2824  7204 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-23 08:44:06.551  2824  7204 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-23 08:44:06.551  7185  7185 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-23 08:44:06.551  7185  7185 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:44:06.551  7185  7185 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 08:44:06.551  7185  7185 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 08:44:06.551  7205  7205 E Zygote  : MountEmulatedStorage(),
08-23 08:44:06.551  7205  7205 E Zygote  : v2
08-23 08:44:06.551  7205  7205 I libpersona: KNOX_SDCARD checking this for 10032
08-23 08:44:06.551  7205  7205 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.551  1016  1328 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7205 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:44:06.561  7205  7205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:06.561  7205  7205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:06.561  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-23 08:44:06.561  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.561  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.561  7205  7205 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-23 08:44:06.561  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.561  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.581  7214  7214 E Zygote  : MountEmulatedStorage()
,08-23 08:44:06.581  7214  7214 E Zygote  : v2
08-23 08:44:06.581  7214  7214 I libpersona: KNOX_SDCARD checking this for 1000
08-23 08:44:06.581  7214  7214 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.581  7214  7214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:06.581  7214  7214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:06.581  7214  7214 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.581  1016  1029 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7214 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 08:44:06.581  1016  1029 I ActivityManager: Killing 6627:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-23 08:44:06.601  1016  1328 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:06.611  7205  7205 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:06.611  7205  7205 D ActivityThread: Added TimaKeyStore provider
08-23 08:44:06.611  7214  7214 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:06.611  7214  7214 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.631  1016  1328 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:06.661  7214  7214 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-23 08:44:06.681  7205  7238 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-23 08:44:06.681  7205  7238 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-23 08:44:06.691  7205  7205 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-23 08:44:06.691  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-23 08:44:06.691  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.691  1016  1510 D RCPManagerService: exchangeData() failure , invalid userId
08-23 08:44:06.691  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.691  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.691  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.701  7205  7238 D SPPClientService: PushLog.txt file is not deleted.
,08-23 08:44:06.701  7205  7238 D SPPClientService: PushLog.txt file is not deleted.
08-23 08:44:06.701  7205  7238 D SPPClientService: ============PushLog. stop!
,08-23 08:44:06.711  7242  7242 E Zygote  : MountEmulatedStorage(),
08-23 08:44:06.711  7242  7242 E Zygote  : v2
,08-23 08:44:06.711  1016  1029 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7242 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-23 08:44:06.711  1016  1029 I ActivityManager: Killing 6702:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-23 08:44:06.711  7242  7242 I libpersona: KNOX_SDCARD checking this for 10036
08-23 08:44:06.711  7242  7242 I libpersona: KNOX_SDCARD not a persona,
08-23 08:44:06.711  1016  3831 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-23 08:44:06.711  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-23 08:44:06.711  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:06.711  1016  3831 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-23 08:44:06.711  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-23 08:44:06.721  7242  7242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:06.721  7242  7242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:06.721  7242  7242 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:06.741  7242  7242 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:06.741  7242  7242 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.751  1016  1328 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:06.791  7205  7256 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-23 08:44:06.821  7242  7242 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@371fb0c8
,08-23 08:44:06.831  7242  7242 I SA      : [SSP] onCreated
,08-23 08:44:06.841  7214  7214 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-23 08:44:06.841  1016  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-23 08:44:06.841  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.841  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.841  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.841  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.851  7214  7214 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-23 08:44:06.851  7242  7242 I SA      : [TPM] There is no property file,
,08-23 08:44:06.851  7214  7214 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:06.851  7214  7214 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,08-23 08:44:06.851  7214  7214 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-23 08:44:06.851  7214  7214 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-23 08:44:06.851  7242  7242 I SA      : [SCU] isHaveSA() - false
,08-23 08:44:06.861  1016  3840 D RCPManagerService: exchangeData() failure , invalid userId
08-23 08:44:06.861  7264  7264 E Zygote  : MountEmulatedStorage()
08-23 08:44:06.861  7264  7264 I libpersona: KNOX_SDCARD checking this for 10068
08-23 08:44:06.861  7264  7264 E Zygote  : v2
08-23 08:44:06.861  7264  7264 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:06.861  7242  7242 I SA      : [TPM] getModelProperty : null
08-23 08:44:06.861  7242  7242 I SA      : [TPM] getCSCProperty : null
08-23 08:44:06.861  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:06.861  7242  7242 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-23 08:44:06.861  7242  7242 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-23 08:44:06.861  1016  1491 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7264 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-23 08:44:06.861  7242  7242 I SA      : [DM] TFT FEATURE: false
08-23 08:44:06.861  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-23 08:44:06.861  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:06.861  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.861  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-23 08:44:06.861  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.861  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.861  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.871  7242  7242 I SA      : [DM] init START
,08-23 08:44:06.871  1016  1133 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:06.881  7276  7276 E Zygote  : MountEmulatedStorage()
,08-23 08:44:06.881  7276  7276 E Zygote  : v2
08-23 08:44:06.881  7276  7276 I libpersona: KNOX_SDCARD checking this for 10008
,08-23 08:44:06.881  7276  7276 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:06.881  7276  7276 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 08:44:06.881  1016  1328 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7276 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-23 08:44:06.881  1016  1328 I ActivityManager: Killing 6147:com.android.mms/u0a41 (adj 15): empty #21
08-23 08:44:06.891  7276  7276 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:06.891  7276  7276 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-23 08:44:06.901  1016  1510 D CountryDetector: No listener is left
,08-23 08:44:06.901  7242  7242 I SA      : [DM] This device is not a Vodafone
,08-23 08:44:06.911  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:06.911  7264  7264 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:06.911  7242  7242 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-23 08:44:06.911  7242  7242 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-23 08:44:06.911  7242  7242 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-23 08:44:06.911  7242  7242 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-23 08:44:06.911  7242  7242 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-23 08:44:06.911  7242  7242 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-23 08:44:06.921  7242  7242 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-23 08:44:06.921  7242  7242 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-23 08:44:06.921  7242  7242 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-23 08:44:06.921  7242  7242 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-23 08:44:06.921  7242  7242 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-23 08:44:06.931  1016  1478 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-23 08:44:06.931  7276  7276 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-23 08:44:06.931  7276  7276 D ActivityThread: Added TimaKeyStore provider
08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-23 08:44:06.931  7242  7242 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-23 08:44:06.941  7242  7242 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-23 08:44:06.941  7242  7242 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-23 08:44:06.941  7242  7242 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-23 08:44:06.941  7242  7242 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-23 08:44:06.941  7242  7242 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-23 08:44:06.941  7242  7242 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-23 08:44:06.951  7242  7242 I SA      : [SCU] isHaveSA() - false
08-23 08:44:06.951  7242  7242 I SA      : support phone number id : false
08-23 08:44:06.951  7242  7242 I SA      : [DM] Supports Ref Jpn : true
,08-23 08:44:06.951  7242  7242 I SA      : [DM] init END
08-23 08:44:06.951  7242  7242 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-23 08:44:06.951  7242  7242 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-23 08:44:06.951  7242  7242 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-23 08:44:06.951  7264  7264 D BadgeProvider: onCreate
08-23 08:44:06.951  7264  7264 D BadgeProvider: DatabaseHelper
,08-23 08:44:06.961  1016  1377 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-23 08:44:06.961  1016  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-23 08:44:06.961  1016  1377 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:06.961  1016  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:06.961  1016  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 08:44:06.961  1016  3831 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-23 08:44:06.961  7242  7242 I SA      : [SLFUCHKMGR] constructor called
08-23 08:44:06.961  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.961  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.961  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:06.961  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:06.971  1016  3840 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:06.991  7264  7285 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-23 08:44:06.991  7302  7302 E Zygote  : MountEmulatedStorage()
08-23 08:44:06.991  7302  7302 I libpersona: KNOX_SDCARD checking this for 10110
08-23 08:44:06.991  7302  7302 E Zygote  : v2
08-23 08:44:06.991  7302  7302 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:06.991  7302  7302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:07.001  7302  7302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:07.001  7302  7302 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-23 08:44:07.001  7242  7242 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-23 08:44:07.011  7242  7242 I SA      : [OR] == isSIMCardReady false ==,
,08-23 08:44:07.011  7242  7242 I SA      : [SCU] == networkStateCheck == false
,08-23 08:44:07.011  7242  7242 I SA      : [OR] onReceive END
,08-23 08:44:07.021  7302  7302 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 08:44:07.021  7302  7302 D ActivityThread: Added TimaKeyStore provider,
,08-23 08:44:07.031  1016  1133 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 08:44:07.031  1016  3831 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7302 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 08:44:07.031  1016  1133 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 08:44:07.031  1016  1133 D SecContentProvider2: mCursor = null
,08-23 08:44:07.031  1016  1231 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-23 08:44:07.031  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-23 08:44:07.031  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:07.031  1016  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:07.031  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 08:44:07.041  1016  1133 D WifiService: setWifiEnabled: true pid=6821, uid=10171,
08-23 08:44:07.041  1016  1133 W ActivityManager: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 08:44:07.041  1016  1133 W WifiService: Failed getting userId using ActivityManagerNative
08-23 08:44:07.041  1016  1133 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 08:44:07.041  1016  1133 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 08:44:07.041  1016  1133 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
,08-23 08:44:07.041  1016  1133 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 08:44:07.041  1016  1133 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 08:44:07.041  1016  1133 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-23 08:44:07.041  1016  1133 D SettingsProvider: name = wifi_on
,08-23 08:44:07.041  7056  7300 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-23 08:44:07.041  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-23 08:44:07.051   317   317 I art     : Explicit concurrent mark sweep GC freed 8679(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 660us total 20.984ms
,08-23 08:44:07.051  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:07.051  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:07.051  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:07.051  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:07.051  1016  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-23 08:44:07.071   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 658us total 17.008ms
,08-23 08:44:07.081   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.477ms,
,08-23 08:44:07.101  7319  7319 E Zygote  : MountEmulatedStorage()
08-23 08:44:07.101  7319  7319 E Zygote  : v2
08-23 08:44:07.101  7319  7319 I libpersona: KNOX_SDCARD checking this for 10009
08-23 08:44:07.101  1016  1029 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7319 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-23 08:44:07.101  7319  7319 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:07.101  1016  1029 I ActivityManager: Killing 6744:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-23 08:44:07.101  1016  1029 I ActivityManager: Killing 6727:com.sec.esdk.elm/u0a90 (adj 15): empty #22,
08-23 08:44:07.101  7319  7319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:07.101  1016  1029 I ActivityManager: Killing 6558:com.android.calendar/u0a131 (adj 15): empty #21
,08-23 08:44:07.111  7319  7319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:07.111  7319  7319 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 08:44:07.111  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:07.121  1016  1377 I ActivityManager: Killing 6759:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-23 08:44:07.131  7264  7285 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-23 08:44:07.131  7264  7285 D BadgeProvider: sendNotify, [notify] : null
08-23 08:44:07.131  7264  7285 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-23 08:44:07.131  7264  7285 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-23 08:44:07.131  7264  7285 D BadgeProvider: update, [UpdateCount] : 1
,08-23 08:44:07.151  1016  1329 I ActivityManager: Killing 6090:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-23 08:44:07.161  1016  3840 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 08:44:07.161  1016  3840 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 08:44:07.161  1016  3840 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 08:44:07.161  1016  3840 D BatteryService: stay LED for fully charged
08-23 08:44:07.161  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 08:44:07.161  7319  7319 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:07.161  2942  2942 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 08:44:07 GMT+02:00 2016
08-23 08:44:07.161  1016  1016 I MotionRecognitionService: Plugged
08-23 08:44:07.161  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-23 08:44:07.171  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 08:44:07.171  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 08:44:07.171  1479  1479 D Launcher.Model: reloadBadges entered.
08-23 08:44:07.171  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 08:44:07.171  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-23 08:44:07.171  7319  7319 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:07.181  1016  1329 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-23 08:44:07.181  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 08:44:07.181  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:07.181  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:07.181  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 08:44:07.191  2942  2942 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 08:44:07.201  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:44:07.211  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 08:44:07.211  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:44:07.211  2942  2942 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 08:44:07.221  2942  2942 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 08:44:07.231  2942  2942 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 08:44:07.231  2942  7334 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 08:44:07.231  2942  7334 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-23 08:44:07.231  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-23 08:44:07.241  1016  1029 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-23 08:44:07.241  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-23 08:44:07.241  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-23 08:44:07.241  2942  7334 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-23 08:44:07.251  2942  7334 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-23 08:44:07.251  2942  2942 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 08:44:07.321  1016  1491 I ActivityManager: Killing 5909:com.android.vending/u0a26 (adj 15): empty #21
,08-23 08:44:07.331  1016  3839 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:07.331  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 08:44:07.341  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:07.341  1016  3839 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:07.341  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:07.351  1016  3831 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 08:44:07.351  4870  7339 I iu.SyncManager: SYNC; picasa accounts
,08-23 08:44:07.371  4870  4870 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-23 08:44:07.481   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-23 08:44:07.481   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:07.481  7302  7346 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-23 08:44:07.481   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-23 08:44:07.481   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:07.481  7302  7346 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-23 08:44:07.491  1016  1043 D Tethering: interfaceAdded wlan0
,08-23 08:44:07.491  1016  1128 E Tethering: No numeric data
,08-23 08:44:07.491  1016  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-23 08:44:07.491  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-23 08:44:07.491  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:07.501  1016  1128 D Tethering: clearTetheredNotification()
,08-23 08:44:07.501  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 08:44:07.501  1177  1177 D HotspotTile: updateTetherState():false, false
08-23 08:44:07.501  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:07.501  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 08:44:07.501  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:07.501   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-23 08:44:07.501   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 08:44:07.501  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:07.501  7302  7347 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
08-23 08:44:07.501  1016  1122 V NetworkStats: performPollLocked() took 8ms
08-23 08:44:07.501  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:07.501  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:07.501  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:07.501  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:07.511  1016  1128 D Tethering: InitialState.processMessage what=4
,08-23 08:44:07.511   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-23 08:44:07.511   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:07.511  1016  1128 E Tethering: No numeric data
08-23 08:44:07.511  7302  7347 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
08-23 08:44:07.511  1016  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:44:07.511  1016  1128 D Tethering: clearTetheredNotification()
,08-23 08:44:07.511  1016  1043 D Tethering: interfaceAdded p2p0
,08-23 08:44:07.511  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-23 08:44:07.511  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
08-23 08:44:07.511  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:07.511  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-23 08:44:07.511  1177  1177 D HotspotTile: updateTetherState():false, false
,08-23 08:44:07.511  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-23 08:44:07.511   277  1005 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-23 08:44:07.511  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-23 08:44:07.511  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:07.511  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:07.511   277  1005 D SoftapController: Softap fwReload - Ok
,08-23 08:44:07.511  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 08:44:07.521   277  1005 D CommandListener: Setting iface cfg
08-23 08:44:07.521   277  1005 D CommandListener: Trying to bring down wlan0
,08-23 08:44:07.521  1016  1122 V NetworkStats: performPollLocked() took 7ms
08-23 08:44:07.521  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:07.521   277  1005 D CommandListener: Clearing all IP addresses on wlan0
,08-23 08:44:07.521  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:07.521  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:07.521  1016  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-23 08:44:07.531  1016  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-23 08:44:07.531  1016  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-23 08:44:07.531  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 08:44:07.531  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 08:44:07.531  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:07.531  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:07.531  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-23 08:44:07.531  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:07.541  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-23 08:44:07.541  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 08:44:07.541  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-23 08:44:07.541  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:07.541  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:07.541  1177  1177 D HotspotTile: onReceive : 2, 0
,08-23 08:44:07.541  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:07.541  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:07.551  7302  7302 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 08:44:07.551  7302  7302 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 08:44:07.551  7302  7302 I GAv4    :   adb logcat -s GAv4
,08-23 08:44:07.571  7302  7302 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 08:44:07.571  1016  1231 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 08:44:07.581  7349  7349 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-23 08:44:07.581  7349  7349 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-23 08:44:07.581  7349  7349 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-23 08:44:07.581  7302  7302 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 08:44:07.591  7302  7352 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,08-23 08:44:07.601  7349  7349 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-23 08:44:07.601   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7349
08-23 08:44:07.601   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
,08-23 08:44:07.601  7349  7349 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-23 08:44:07.601  7349  7349 I wpa_supplicant: ssSupport state is = 1
08-23 08:44:07.601  7349  7349 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-23 08:44:07.601  7349  7349 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-23 08:44:07.601   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7349
,08-23 08:44:07.601   364   364 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-23 08:44:07.731   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:07.781   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-23 08:44:07.791  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-23 08:44:07.831  7302  7302 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-23 08:44:07.851  7349  7349 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 08:44:07.851  1016  1329 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 08:44:07.851  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-23 08:44:07.851  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:07.851  1016  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:07.851  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-23 08:44:07.861  7302  7302 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6978-6980)
08-23 08:44:07.861  7302  7302 I cr.library_loader: Expected native library version number "", actual native library version number "",
,08-23 08:44:07.861  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-23 08:44:07.861   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7349
08-23 08:44:07.861   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 08:44:07.861  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 08:44:07.861  7349  7349 I wpa_supplicant: ssSupport state is = 1
,08-23 08:44:07.871  7349  7349 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-23 08:44:07.871  7349  7349 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:07.871  7349  7349 E wpa_supplicant: SIM READ ERROR
08-23 08:44:07.871  7349  7349 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:07.871  7349  7349 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:07.871  7349  7349 E wpa_supplicant: SIM READ ERROR
08-23 08:44:07.871  7349  7349 I wpa_supplicant: Blacklist: Clear (all) 
08-23 08:44:07.871  7349  7349 I wpa_supplicant: wpa_default_ap_write_once
08-23 08:44:07.871  7349  7349 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 08:44:07.871  7349  7349 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:07.871  7349  7349 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-23 08:44:07.871  7349  7349 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:07.871  7349  7349 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-23 08:44:07.871  7349  7349 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 08:44:07.871  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:07.871  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:07.871  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:07.891  7302  7302 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30f576a3}
,08-23 08:44:07.891  7302  7302 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 08:44:07.891  7302  7302 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 08:44:07.901  7302  7302 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 08:44:07.911  7302  7302 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:44:07.911  7302  7302 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 08:44:07.921  7302  7302 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 08:44:07.921  7302  7302 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 08:44:07.921  7302  7302 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 08:44:07.921  7302  7302 I Adreno-EGL: Local Branch: 
08-23 08:44:07.921  7302  7302 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 08:44:07.921  7302  7302 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 08:44:07.921  7302  7302 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 08:44:07.931  7349  7349 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-23 08:44:07.991  7302  7381 W cr.media: Requires BLUETOOTH permission
,08-23 08:44:07.991  7302  7302 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 08:44:08.001  7302  7302 I NSApplication: Starting up...
,08-23 08:44:08.001  1016  1328 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 08:44:08.001  1016  3831 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-23 08:44:08.011  1016  3840 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-23 08:44:08.011  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:08.011  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:08.011  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:08.011  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:08.021  1016  3840 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7386 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-23 08:44:08.021  7386  7386 E Zygote  : MountEmulatedStorage()
08-23 08:44:08.021  7386  7386 E Zygote  : v2
08-23 08:44:08.021  7386  7386 I libpersona: KNOX_SDCARD checking this for 10117
08-23 08:44:08.021  7386  7386 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:08.021  7386  7386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:08.031  7386  7386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:08.031  7386  7386 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 08:44:08.041  1016  1028 I ActivityManager: Killing 7004:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-23 08:44:08.051  7386  7386 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:08.051  7386  7386 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:08.051  1940  2195 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-23 08:44:08.061  1940  2195 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-23 08:44:08.071  7386  7386 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 08:44:08.111  7349  7349 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-23 08:44:08.111  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-23 08:44:08.121  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-23 08:44:08.121   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7349
08-23 08:44:08.121   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 08:44:08.121  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 08:44:08.121  7349  7349 I wpa_supplicant: ssSupport state is = 1
,08-23 08:44:08.131  7349  7349 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 08:44:08.131  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-23 08:44:08.141  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-23 08:44:08.141   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7349
08-23 08:44:08.141   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 08:44:08.141  7349  7349 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-23 08:44:08.141  7349  7349 I wpa_supplicant: ssSupport state is = 1
08-23 08:44:08.141  7349  7349 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:08.141  7349  7349 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:08.141  7349  7349 E wpa_supplicant: SIM READ ERROR
08-23 08:44:08.141  7349  7349 I wpa_supplicant: wpa_default_ap_write_once
08-23 08:44:08.141  7349  7349 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 08:44:08.141  7349  7349 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 08:44:08.141  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-23 08:44:08.141  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-23 08:44:08.141  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 08:44:08.141  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-23 08:44:08.141  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-23 08:44:08.141  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 08:44:08.221  7349  7349 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-23 08:44:08.221  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-23 08:44:08.321  7349  7349 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-23 08:44:08.321  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-23 08:44:08.321  7349  7349 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 08:44:08.421  1016  1377 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-23 08:44:08.431  1016  1377 I ActivityManager: Killing 7026:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-23 08:44:08.431  1016  1377 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:08.431  1016  1377 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:08.431  1016  1377 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:08.431  1016  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:08.431  1016  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:08.441  2201  2201 I Hs20UtilService: Starting #12
,08-23 08:44:08.441  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 08:44:08.441  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 08:44:08.441  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
08-23 08:44:08.441  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 08:44:08.441  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:08.501  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-23 08:44:08.501  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-23 08:44:08.501  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 08:44:08.531  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-23 08:44:08.531  1016  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 08:44:08.541  7349  7349 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-23 08:44:08.541  7349  7349 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:08.541  7349  7349 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:08.541  7349  7349 E wpa_supplicant: SIM READ ERROR,
08-23 08:44:08.541  7349  7349 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 08:44:08.551  7349  7349 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-23 08:44:08.561  7349  7349 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-23 08:44:08.561  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:08.561  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 08:44:08.561  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:08.561  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:08.561  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:08.571  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:08.571  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 08:44:08.571  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:08.571  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:08.571  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-23 08:44:08.571  1177  1177 D HotspotTile: onReceive : 3, 0
08-23 08:44:08.571  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:08.571  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:08.571  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:08.571  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:44:08.571  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:08.571  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:08.571  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:08.581  1016  1231 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:08.571  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:44:08.581  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 08:44:08.571  1016  1125 D WifiConfigStore: Loading config and enabling all networks 
08-23 08:44:08.581  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:08.581  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:08.581  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:08.581  2201  2201 I Hs20UtilService: Starting #13
08-23 08:44:08.581  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:08.581  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 08:44:08.581  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 08:44:08.581  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 08:44:08.581  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 08:44:08.581  1016  1125 E WifiConfigStore: Not a HS20,
,08-23 08:44:08.581  1016  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 08:44:08.591  1016  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-23 08:44:08.591  1016  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-23 08:44:08.591  7349  7349 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-23 08:44:08.591  7349  7349 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-23 08:44:08.591  7349  7349 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 08:44:08.591  7349  7349 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 08:44:08.591  7349  7349 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-23 08:44:08.591  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-23 08:44:08.591  7349  7349 I wpa_supplicant: First Scan Start
08-23 08:44:08.591  7349  7349 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 08:44:08.601  1016  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-23 08:44:08.601  1016  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 08:44:08.601  1016  1125 I WifiNative-HAL: startHal
08-23 08:44:08.601  1016  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d67488c
08-23 08:44:08.601  1016  1125 I WifiNative-HAL: Could not start hal
,08-23 08:44:08.601  7056  7056 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:44:08.601  1016  1125 E WifiNative-wlan0: do suspend true
,08-23 08:44:08.601  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-23 08:44:08.601  1016  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-23 08:44:08.601  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,08-23 08:44:08.601  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:08.601  1016  1148 I WifiNative-HAL: startHal
08-23 08:44:08.601  1016  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9eb329bc
08-23 08:44:08.601  1016  1148 I WifiNative-HAL: Could not start hal
08-23 08:44:08.601  1016  1148 E WifiScanningService: could not start HAL
08-23 08:44:08.601  1016  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-23 08:44:08.601  1016  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 08:44:08.601  1016  1125 E WifiNative-wlan0: invaild command id : 215
,08-23 08:44:08.601  1016  1016 D RttService: SCAN_AVAILABLE : 3,
08-23 08:44:08.611  1016  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:08.611   277  1005 D CommandListener: Setting iface cfg
08-23 08:44:08.611   277  1005 D CommandListener: Trying to bring up p2p0
,08-23 08:44:08.611  1016  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 08:44:08.611  1016  1124 D WifiP2pService: P2pEnablingState
08-23 08:44:08.611  1016  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-23 08:44:08.611  1016  1124 D WifiP2pService: P2p socket connection successful
08-23 08:44:08.611  1016  1124 D WifiP2pService: P2pEnabledState
,08-23 08:44:08.611  1016  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-23 08:44:08.611  1016  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-23 08:44:08.611  1016  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 08:44:08.611  1016  1125 E WifiNative-wlan0: invaild command id : 215
,08-23 08:44:08.611  1016  1127 E ConnectivityService: updateNetworkInfo()
,08-23 08:44:08.611  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-23 08:44:08.611  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-23 08:44:08.611  7349  7349 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-23 08:44:08.611  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 08:44:08.611  1016  1046 D WifiDisplayController: disconnect
08-23 08:44:08.611  1016  1046 D WifiDisplayController: updateConnection
,08-23 08:44:08.611  7349  7349 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-23 08:44:08.611  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 08:44:08.611  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 08:44:08.611  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-23 08:44:08.611  7349  7349 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-23 08:44:08.611  1016  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 08:44:08.611  1016  1125 E WifiStateMachine: Failed to set frequency band 0
08-23 08:44:08.611  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 08:44:08.621  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:08.621  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:08.621  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:44:08.621  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-23 08:44:08.621  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 08:44:08.621  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 08:44:08.621  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-23 08:44:08.621  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 08:44:08.621  1016  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-23 08:44:08.621  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:08.621  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:08.621  1016  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-23 08:44:08.621  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 08:44:08.621  1016  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-23 08:44:08.621  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  secondary type: null
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  wps: 0
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  grpcapab: 0
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  devcapab: 0
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  status: 3
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  wfdInfo: null
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-23 08:44:08.621  1016  1046 D WifiDisplayController:  SConnectInfo : null
,08-23 08:44:08.621  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 08:44:08.621  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:08.621  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 08:44:08.621  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:08.631  1016  1133 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-23 08:44:08.631  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:08.631  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:08.631  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:08.631  1016  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:08.641  1016  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-23 08:44:08.641  7415  7415 E Zygote  : MountEmulatedStorage()
,08-23 08:44:08.641  7415  7415 E Zygote  : v2
08-23 08:44:08.641  7415  7415 I libpersona: KNOX_SDCARD checking this for 10064
08-23 08:44:08.641  7415  7415 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:08.641  7415  7415 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:08.641  1016  1133 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7415 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:44:08.641  1016  1124 D WifiP2pService: InactiveState,
08-23 08:44:08.641  1016  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-23 08:44:08.641  1016  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 08:44:08.651  7349  7349 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 08:44:08.651  1016  1124 D WifiP2pService: InactiveState{ what=143376 },
08-23 08:44:08.651  1016  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 08:44:08.651  7415  7415 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:08.651  7415  7415 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:08.671  7415  7415 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:08.671  7415  7415 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:08.681  7415  7415 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 08:44:08.691  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 08:44:08.691  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 08:44:08.721  7415  7415 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 08:44:08.721  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-23 08:44:08.721  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:08.721  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:08.721  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:08.721  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:08.741   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:08.741  7430  7430 E Zygote  : MountEmulatedStorage()
,08-23 08:44:08.741  7430  7430 E Zygote  : v2
08-23 08:44:08.741  7430  7430 I libpersona: KNOX_SDCARD checking this for 10065
08-23 08:44:08.741  7430  7430 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:08.741  1016  1328 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7430 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-23 08:44:08.741  1016  1328 I ActivityManager: Killing 6947:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-23 08:44:08.741  7430  7430 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:08.741  7430  7430 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:08.751  7430  7430 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:08.761  7430  7430 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:08.761  7430  7430 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:08.791  7430  7430 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 08:44:08.801  1016  1491 I ActivityManager: Killing 7090:com.android.bluetooth/1002 (adj 15): empty #21
,08-23 08:44:09.021   294   294 E SMD     : DCD OFF,
,08-23 08:44:09.191  1016  1231 I ActivityManager: Killing 6966:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-23 08:44:09.741   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:09.851  7349  7349 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
08-23 08:44:09.851  7349  7349 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-23 08:44:09.851  1016  7411 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-23 08:44:09.851  7349  7349 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-23 08:44:09.851  7349  7349 I wpa_supplicant: Trying to associate with  'G700'
08-23 08:44:09.851  7349  7349 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-23 08:44:09.861  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-23 08:44:09.881  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:09.881  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:09.981  7349  7349 E wpa_supplicant: Cmd 35605 not handled
,08-23 08:44:09.981  7349  7349 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 08:44:09.981  7349  7349 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-23 08:44:09.981  7349  7349 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-23 08:44:09.981  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-23 08:44:09.981  7349  7349 I wpa_supplicant: Associated with F4.99.3E
,08-23 08:44:09.981  7349  7349 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 08:44:09.981  7349  7349 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-23 08:44:09.981  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-23 08:44:09.981  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:09.981  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:09.981  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:09.981  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 08:44:09.981  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-23 08:44:09.981  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:09.981  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:09.981  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-23 08:44:09.981  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:09.981  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 08:44:09.981  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-23 08:44:09.981  7349  7349 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 08:44:09.981  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 08:44:09.981  7349  7349 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-23 08:44:09.991  7349  7349 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-23 08:44:09.991  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-23 08:44:09.991  1016  1128 E Tethering: No numeric data
,08-23 08:44:09.991  7349  7349 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:44:09.991  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
08-23 08:44:09.991  1016  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-23 08:44:09.991  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 08:44:09.991  1016  1128 D Tethering: clearTetheredNotification()
08-23 08:44:09.991  1177  1177 D HotspotTile: updateTetherState():false, false
08-23 08:44:09.991  7349  7349 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-23 08:44:09.991  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 08:44:09.991  7349  7349 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-23 08:44:09.991  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:09.991  7349  7349 I wpa_supplicant: Blacklist: Clear (temp) 
08-23 08:44:09.991  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-23 08:44:09.991  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 08:44:09.991  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:09.991  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-23 08:44:09.991  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 08:44:10.001  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:10.001  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:10.001  1016  1122 V NetworkStats: performPollLocked() took 10ms
08-23 08:44:10.001  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:10.001  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-23 08:44:10.001  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:10.011  1016  1125 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-23 08:44:10.011  1016  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-23 08:44:10.011  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:10.011  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:10.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.021  1016  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-23 08:44:10.021  1016  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-23 08:44:10.021  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:10.021  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:44:10.021  1016  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 08:44:10.021  1016  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 08:44:10.021  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 08:44:10.021  1016  1491 W ActivityManager: userId = 0, bbcId = -10000,
08-23 08:44:10.021  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:10.021  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:10.021  2201  2201 I Hs20UtilService: Starting #14
,08-23 08:44:10.021  2201  2217 I Hs20UtilService: Message received 5007
,08-23 08:44:10.031  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 08:44:10.031  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 08:44:10.031  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 08:44:10.031  1016  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 08:44:10.031  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 08:44:10.031  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:10.031  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 08:44:10.031  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:10.041   277  1005 D CommandListener: Setting iface cfg,
,08-23 08:44:10.041  1016  1125 E WifiStateMachine: Start Dhcp Watchdog 2,
,08-23 08:44:10.051  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 08:44:10.051  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:10.051  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 08:44:10.051  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:10.051  1016  1133 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 08:44:10.051  1016  1133 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-23 08:44:10.051  1016  1133 D SecContentProvider2: mCursor = null
,08-23 08:44:10.061  1016  1133 D WifiService: setWifiEnabled: false pid=6821, uid=10171
,08-23 08:44:10.061  1016  1133 D SettingsProvider: name = wifi_on
,08-23 08:44:10.071  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:10.071  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 08:44:10.071  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.071  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.071  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.071  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.081  1016  1125 E WifiNative-wlan0: do suspend false
,08-23 08:44:10.081  1016  1124 D WifiP2pService: InactiveState{ what=143375 },
08-23 08:44:10.081  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 08:44:10.081  1016  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-23 08:44:10.081  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:10.091  1016  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 08:44:10.101  1016  1125 E WifiNative-wlan0: do suspend true
,08-23 08:44:10.121  1016  1124 D WifiP2pService: InactiveState{ what=143375 },
,08-23 08:44:10.121  1016  1124 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-23 08:44:10.131   277  1005 D CommandListener: Clearing all IP addresses on wlan0
08-23 08:44:10.131  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:10.131  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 08:44:10.131  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.131  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.131  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.131  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.131  1016  1127 E ConnectivityService: updateNetworkInfo(),
08-23 08:44:10.131  1016  1124 D WifiP2pService: InactiveState{ what=131204 }
08-23 08:44:10.131  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:10.131  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:44:10.131  1016  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 08:44:10.131  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-23 08:44:10.131   277  1005 E Netd    : no such netId 503
08-23 08:44:10.131  1016  1124 D WifiP2pService: P2pEnabledState{ what=131204 },
08-23 08:44:10.141  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 08:44:10.141  1016  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-23 08:44:10.141  1016  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-23 08:44:10.141  1016  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
,08-23 08:44:10.141  1016  1127 V NetworkStats: updateIfacesLocked()
,08-23 08:44:10.141  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:10.141  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:10.141  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.141  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.141  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.141  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.141  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
,08-23 08:44:10.141  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:10.151  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:10.151  1016  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-23 08:44:10.151  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-23 08:44:10.151  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:10.151  1016  1016 D RttService: SCAN_AVAILABLE : 1,
08-23 08:44:10.151  1016  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 08:44:10.151  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:44:10.161  1016  3839 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:10.161  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 08:44:10.161  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-23 08:44:10.161  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 08:44:10.161  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 08:44:10.161  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:10.161  1016  1127 V NetworkStats: performPollLocked() took 9ms
08-23 08:44:10.161  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:10.161  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-23 08:44:10.161  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:10.161  2201  2201 I Hs20UtilService: Starting #15
08-23 08:44:10.161  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-23 08:44:10.161  1016  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-23 08:44:10.161  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-23 08:44:10.161  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
,08-23 08:44:10.161  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:10.161  1016  1046 D WifiDisplayController: disconnect
08-23 08:44:10.161  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:10.161  1016  1046 D WifiDisplayController: updateConnection
08-23 08:44:10.161  1016  7447 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:10.161  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-23 08:44:10.161  1016  7447 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-23 08:44:10.161  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 08:44:10.161  1016  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-23 08:44:10.161  1016  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-23 08:44:10.161  1016  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-23 08:44:10.161  1016  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-23 08:44:10.161  1016  1127 E ConnectivityService: updateNetworkInfo()
,08-23 08:44:10.161  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:10.161  2201  2217 I Hs20UtilService: Message received 5007
,08-23 08:44:10.171  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 08:44:10.171  1016  1124 D WifiP2pService: P2pDisablingState
08-23 08:44:10.171  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 08:44:10.171  1016  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-23 08:44:10.171  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-23 08:44:10.171  1016  1124 D WifiP2pService: p2p socket connection lost
08-23 08:44:10.171  1016  1124 D WifiP2pService: P2pDisabledState
,08-23 08:44:10.171  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 08:44:10.171  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:10.171  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 08:44:10.171  1016  1125 E WifiNative-wlan0: do suspend true
08-23 08:44:10.171  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-23 08:44:10.171  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 08:44:10.171  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-23 08:44:10.171  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 08:44:10.171  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 08:44:10.181  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 08:44:10.181  1016  3831 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 08:44:10.181  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 08:44:10.191  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 08:44:10.191  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 08:44:10.191  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 08:44:10.191  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 08:44:10.191  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:10.191  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 08:44:10.191  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:10.201  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 08:44:10.201  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-23 08:44:10.201  7415  7415 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 08:44:10.201  1016  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-23 08:44:10.201  7430  7430 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-23 08:44:10.201  1016  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-23 08:44:10.211   277  1005 D CommandListener: Clearing all IP addresses on wlan0
,08-23 08:44:10.211  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:10.211  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 08:44:10.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.211  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.221  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 08:44:10.221  7349  7349 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-23 08:44:10.221  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:10.221  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 08:44:10.221  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.221  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.231  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.231  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.231  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:10.231  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 08:44:10.231  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.231  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.231  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:10.231  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:10.231  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:10.231  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:10.231  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:10.231  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-23 08:44:10.241  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 08:44:10.241  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:10.241  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:10.241  1016  3831 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:10.241  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:10.241  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:10.241  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:44:10.241  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:10.241  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:44:10.241  1016  3831 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:10.241  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:10.241  1177  1177 D HotspotTile: onReceive : 0, 0
,08-23 08:44:10.241  2201  2201 I Hs20UtilService: Starting #16
,08-23 08:44:10.241  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:10.241  2201  2217 I Hs20UtilService: Message received 5007
,08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:10.241  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:10.241  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:10.241  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:10.241  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 08:44:10.241  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 08:44:10.251  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 08:44:10.251  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 08:44:10.251  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:10.251  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-23 08:44:10.251  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:10.251  1016  3839 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 08:44:10.251  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:10.251  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:10.251  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:10.251  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:10.261  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 08:44:10.261  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 08:44:10.261  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 08:44:10.261  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 08:44:10.271  2201  2201 I Hs20UtilService: Starting #17
,08-23 08:44:10.271  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:10.291  7450  7450 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-23 08:44:10.291  7450  7450 I dhcpcd  : version 5.5.6 starting,
,08-23 08:44:10.301  7450  7450 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-23 08:44:10.341  7450  7450 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-23 08:44:10.341  7450  7450 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-23 08:44:10.341  7450  7450 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-23 08:44:10.341  7450  7450 I dhcpcd  : bssid match,
,08-23 08:44:10.341  7450  7450 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-23 08:44:10.391  7349  7349 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 08:44:10.401  7450  7450 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-23 08:44:10.431  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-23 08:44:10.431  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 08:44:10.431  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-23 08:44:10.431  7349  7349 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-23 08:44:10.451  7349  7349 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-23 08:44:10.451  7349  7349 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-23 08:44:10.451  7349  7349 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-23 08:44:10.451  7349  7349 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-23 08:44:10.451  7349  7349 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-23 08:44:10.451  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 08:44:10.451  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:10.451  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:10.451  1016  1128 D Tethering: InitialState.processMessage what=4
,08-23 08:44:10.461  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 08:44:10.461  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-23 08:44:10.461  1016  1128 E Tethering: No numeric data
,08-23 08:44:10.461  1016  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-23 08:44:10.461  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:10.461  1016  1128 D Tethering: clearTetheredNotification()
08-23 08:44:10.461  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-23 08:44:10.461  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:10.461  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-23 08:44:10.461  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 08:44:10.471  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 08:44:10.471  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:10.471  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:10.471  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 08:44:10.471  1177  1177 D HotspotTile: updateTetherState():false, false
,08-23 08:44:10.471  1016  1122 V NetworkStats: performPollLocked() took 8ms
,08-23 08:44:10.471  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:10.471  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:10.471  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:10.491  7450  7450 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-23 08:44:10.741   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-23 08:44:10.791  7349  7349 I wpa_supplicant: Blacklist: Clear (all) ,
,08-23 08:44:10.871  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 08:44:10.871  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:10.871  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:10.871  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 08:44:10.871  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:10.871  1016  1043 D Tethering: interfaceStatusChanged wlan0, false,
08-23 08:44:10.871  7349  7349 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-23 08:44:10.981  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-23 08:44:10.981  1016  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 08:44:10.991  7056  7056 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:44:11.001  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:11.001  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
,08-23 08:44:11.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:11.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:11.001  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 08:44:11.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:11.001  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:11.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:11.001  1177  1177 D HotspotTile: onReceive : 1, 0
08-23 08:44:11.001  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:11.001  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-23 08:44:11.001  1940  2190 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:44:11.011  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:11.011  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:11.011  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:11.011  1016  1510 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:11.011  1016  1510 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:11.011  1016  1510 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:11.011  1016  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:11.011  1016  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:11.011  2201  2201 I Hs20UtilService: Starting #18
,08-23 08:44:11.011  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:11.021  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 08:44:11.021  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 08:44:11.021  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 08:44:11.021  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 08:44:11.251  1016  1231 I ActivityManager: Killing 7110:com.sec.pcw.device/1000 (adj 15): empty #21
,08-23 08:44:11.701   277   999 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-23 08:44:11.701  1016  1043 D Tethering: interfaceRemoved wlan0
,08-23 08:44:11.711  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-23 08:44:12.021   294   294 E SMD     : DCD OFF,
,08-23 08:44:12.071  1016  1043 D Tethering: interfaceRemoved p2p0
08-23 08:44:12.071  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-23 08:44:12.891  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-23 08:44:13.061  6821  6874 D BluetoothAdapter: enable()
,08-23 08:44:13.081  1016  1231 W ActivityManager: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-23 08:44:13.081  1016  1231 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-23 08:44:13.081  1016  1231 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 08:44:13.081  1016  1231 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 08:44:13.081  1016  1231 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-23 08:44:13.081  1016  1231 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-23 08:44:13.081  1016  1231 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-23 08:44:13.081  1016  1231 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-23 08:44:13.081  1016  1231 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-23 08:44:13.081  1016  1231 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:13.081  1016  1231 D SettingsProvider: name = bluetooth_on
,08-23 08:44:13.091  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-23 08:44:13.091  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-23 08:44:13.101  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-23 08:44:13.101  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-23 08:44:13.101  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:13.101  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:13.101  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:13.101  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:13.121  7480  7480 E Zygote  : MountEmulatedStorage()
,08-23 08:44:13.121  7480  7480 E Zygote  : v2
08-23 08:44:13.121  7480  7480 I libpersona: KNOX_SDCARD checking this for 1002
08-23 08:44:13.121  7480  7480 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:13.131  7480  7480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:13.131  7480  7480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:13.131  7480  7480 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-23 08:44:13.131  1016  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7480 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-23 08:44:13.161  7480  7480 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:13.161  7480  7480 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:13.181  7480  7480 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-23 08:44:13.181  7480  7480 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 08:44:13.201  7480  7480 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-23 08:44:13.241  7480  7480 D BtSettings.ProfileConfig: Adding GattService
,08-23 08:44:13.241  7480  7480 D BtSettings.ProfileConfig: Adding HeadsetService
,08-23 08:44:13.241  7480  7480 D BtSettings.ProfileConfig: Adding A2dpService
,08-23 08:44:13.241  7480  7480 D BtSettings.ProfileConfig: Adding HidService
,08-23 08:44:13.241  7480  7480 D BtSettings.ProfileConfig: Adding HealthService
,08-23 08:44:13.251  7480  7480 D BtSettings.ProfileConfig: Adding PanService
,08-23 08:44:13.251  7480  7480 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-23 08:44:13.251  7480  7480 D BtSettings.ProfileConfig: Adding SapService
,08-23 08:44:13.251  7480  7480 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-23 08:44:13.251  7480  7480 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-23 08:44:13.251  7480  7480 D BtSettings.ProfileConfig: Adding SapClientService
,08-23 08:44:13.251  7480  7480 D BtSettings.ProfileConfig: Adding HidDevService
,08-23 08:44:13.251  7480  7480 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-23 08:44:13.251  1016  1329 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-23 08:44:13.251  1016  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.251  1016  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 08:44:13.251  1016  1329 D SettingsProvider: selectionArgs: false
08-23 08:44:13.251  1016  1329 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:13.261  1016  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 08:44:13.261  1016  1329 D SettingsProvider: ret = -1
,08-23 08:44:13.261  1016  1328 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-23 08:44:13.261  1016  1328 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.261  1016  1328 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.261  1016  1328 D SettingsProvider: selectionArgs: false
,08-23 08:44:13.261  1016  1328 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:13.261  1016  1328 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.261  1016  1328 D SettingsProvider: ret = -1
,08-23 08:44:13.261  1016  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-23 08:44:13.261  1016  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.261  1016  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.261  1016  1133 D SettingsProvider: selectionArgs: false
08-23 08:44:13.261  1016  1133 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:13.261  1016  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.261  1016  1133 D SettingsProvider: ret = -1
,08-23 08:44:13.261  1016  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-23 08:44:13.261  1016  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.261  1016  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.261  1016  1491 D SettingsProvider: selectionArgs: false
08-23 08:44:13.261  1016  1491 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:13.261  1016  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 08:44:13.261  1016  1491 D SettingsProvider: ret = -1
08-23 08:44:13.261  1016  3831 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-23 08:44:13.261  1016  3831 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-23 08:44:13.261  1016  3831 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-23 08:44:13.261  1016  3831 D SettingsProvider: selectionArgs: false,
,08-23 08:44:13.261  1016  3831 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.261  1016  3831 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.261  1016  3831 D SettingsProvider: ret = -1
08-23 08:44:13.261  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-23 08:44:13.261  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.261  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.261  1016  1029 D SettingsProvider: selectionArgs: false
08-23 08:44:13.261  1016  1029 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.261  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 08:44:13.261  1016  1029 D SettingsProvider: ret = -1
08-23 08:44:13.261  1016  1231 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-23 08:44:13.261  1016  1231 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.261  1016  1231 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.261  1016  1231 D SettingsProvider: selectionArgs: false
08-23 08:44:13.261  1016  1231 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.261  1016  1231 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.261  1016  1231 D SettingsProvider: ret = -1
,08-23 08:44:13.261  1016  3840 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-23 08:44:13.261  1016  3840 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.261  1016  3840 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.261  1016  3840 D SettingsProvider: selectionArgs: false
08-23 08:44:13.261  1016  3840 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.271  1016  3840 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.271  1016  3840 D SettingsProvider: ret = -1
08-23 08:44:13.271  1016  3839 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:13.271  1016  3839 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.271  1016  3839 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.271  1016  3839 D SettingsProvider: selectionArgs: false
08-23 08:44:13.271  1016  3839 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.271  1016  3839 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.271  1016  3839 D SettingsProvider: ret = -1
08-23 08:44:13.271  1016  1510 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:13.271  1016  1510 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 08:44:13.271  1016  1510 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.271  1016  1510 D SettingsProvider: selectionArgs: false
08-23 08:44:13.271  1016  1510 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.271  1016  1510 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.271  1016  1510 D SettingsProvider: ret = -1
08-23 08:44:13.271  1016  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-23 08:44:13.271  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 08:44:13.271  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.271  1016  1478 D SettingsProvider: selectionArgs: false
08-23 08:44:13.271  1016  1478 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.271  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.271  1016  1478 D SettingsProvider: ret = -1
08-23 08:44:13.271  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-23 08:44:13.271  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 08:44:13.271  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.271  1016  1028 D SettingsProvider: selectionArgs: false
08-23 08:44:13.271  1016  1028 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.271  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.271  1016  1028 D SettingsProvider: ret = -1
,08-23 08:44:13.281  7480  7480 D BluetoothAdapterState: make,
,08-23 08:44:13.291  7480  7480 I bluedroid: init,
08-23 08:44:13.291  7480  7495 I BluetoothAdapterState: Entering OffState
,08-23 08:44:13.291  7480  7480 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 08:44:13.291  7480  7480 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf,
08-23 08:44:13.291  7480  7480 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 08:44:13.291  7480  7480 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-23 08:44:13.291  7480  7480 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-23 08:44:13.291  7480  7480 I bluedroid: get_profile_interface socket,
08-23 08:44:13.291  7480  7480 I bluedroid: get_profile_interface map_client
08-23 08:44:13.291  7480  7498 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-23 08:44:13.291  7480  7480 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-23 08:44:13.301  7480  7498 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-23 08:44:13.301  7480  7498 E BluetoothServiceJni: populateRssiValuesNative
,08-23 08:44:13.301  7480  7498 I bluedroid: getModelRssiValues
,08-23 08:44:13.301  7480  7498 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-23 08:44:13.301  7480  7498 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 08:44:13.301  1016  1016 D SettingsProvider: name = bluetooth_name
,08-23 08:44:13.301  7480  7498 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 08:44:13.301  7480  7480 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:13.301  1016  1478 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-23 08:44:13.301  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.311  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:13.311  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:13.311  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.311  7480  7493 I bluedroid: config_hci_snoop_log
,08-23 08:44:13.311  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-23 08:44:13.311  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-23 08:44:13.311  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-23 08:44:13.311  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-23 08:44:13.311  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 08:44:13.321  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:13.321  7480  7480 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-23 08:44:13.321  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:13.321  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-23 08:44:13.321  7480  7495 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-23 08:44:13.321  7480  7495 D BluetoothAdapterProperties: Setting state to 11
08-23 08:44:13.321  7480  7495 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 08:44:13.321  7480  7495 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 08:44:13.321  7480  7495 D BluetoothAdapterService: updateAdapterState state is 11
08-23 08:44:13.331  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-23 08:44:13.331  7480  7495 D BluetoothAdapterService: Autoconnection is available 
08-23 08:44:13.331  7480  7495 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-23 08:44:13.331  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:13.331  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-23 08:44:13.331  7480  7495 D BluetoothSecureManager: getInstant: null
08-23 08:44:13.331  7480  7495 D BluetoothSecureManager: calling getMethod for getService
08-23 08:44:13.331  7480  7495 D BluetoothSecureManager: calling getService
,08-23 08:44:13.331  7480  7495 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@e84dbf8
,08-23 08:44:13.331  1016  1029 D BluetoothSecureManagerService: isSecureModeEnabled
,08-23 08:44:13.331  1016  1029 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-23 08:44:13.331  7480  7495 D BtConfig.SecureMode: isSecureModeOn:false
08-23 08:44:13.331  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-23 08:44:13.331  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-23 08:44:13.331  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-23 08:44:13.341  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-23 08:44:13.341  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-23 08:44:13.341  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 08:44:13.341  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:13.341  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-23 08:44:13.341  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-23 08:44:13.341  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-23 08:44:13.341  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-23 08:44:13.341  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-23 08:44:13.341  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-23 08:44:13.341  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-23 08:44:13.341  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-23 08:44:13.341  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:13.341  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:13.341  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-23 08:44:13.341  1016  3840 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 08:44:13.341  1016  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 08:44:13.341  1827  1827 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 08:44:13.351  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-23 08:44:13.351  7480  7495 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-23 08:44:13.351  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:13.351  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
08-23 08:44:13.351  7480  7495 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:13.351  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-23 08:44:13.351  7480  7495 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:13.351  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-23 08:44:13.351  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 08:44:13.351  1016  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:13.351  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:13.351  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-23 08:44:13.351  7480  7495 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-23 08:44:13.351  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-23 08:44:13.351  7480  7495 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-23 08:44:13.351  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:13.351  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.351  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:13.351  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:13.361  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:13.371  7480  7495 D BluetoothBondStateMachine: make
,08-23 08:44:13.371  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 08:44:13.371  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 08:44:13.371  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-23 08:44:13.371  7480  7500 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 08:44:13.371  1016  1377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:13.371  1016  1377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.371  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:13.371  1016  1377 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.371  1016  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:13.371  1016  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.381  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 08:44:13.381  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 08:44:13.381  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 08:44:13.381  7480  7480 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 08:44:13.381  7480  7480 D BtGatt.GattService: Received start request. Starting profile...
08-23 08:44:13.381  7480  7480 D BtGatt.GattService: start()
08-23 08:44:13.381  7480  7480 D BtGatt.GattService: start()
08-23 08:44:13.381  7480  7480 I bluedroid: get_profile_interface gatt
,08-23 08:44:13.381  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:13.381  7480  7480 D BtGatt.AdvertiseManager: advertise manager created
,08-23 08:44:13.381  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:13.381  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-23 08:44:13.381  1016  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:13.381  1016  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.391  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:13.391  1016  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.391  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.391  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 08:44:13.391  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:13.391  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:13.391  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:13.391  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:13.391  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 08:44:13.391  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 08:44:13.391  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-23 08:44:13.401  7505  7505 E Zygote  : MountEmulatedStorage()
08-23 08:44:13.401  7505  7505 E Zygote  : v2
08-23 08:44:13.401  7505  7505 I libpersona: KNOX_SDCARD checking this for 10055
08-23 08:44:13.401  7505  7505 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:13.401  7505  7505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:13.411  1016  1029 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7505 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 08:44:13.411  7505  7505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:13.411  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.411  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:13.411  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.411  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 08:44:13.411  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.411  7505  7505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:13.421  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-23 08:44:13.421  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:13.421  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-23 08:44:13.421  1016  3831 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:13.421  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.421  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.421  1016  3831 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.421  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.421  7480  7480 D BtGatt.GattService: mStartError = false
08-23 08:44:13.421  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:13.421  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-23 08:44:13.421  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 08:44:13.421  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-23 08:44:13.421  1016  1231 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:13.421  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-23 08:44:13.421  7480  7480 D HeadsetService: Received start request. Starting profile...
08-23 08:44:13.421  7480  7480 D HeadsetService: start()
,08-23 08:44:13.421  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.421  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.421  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.431  7480  7480 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 08:44:13.431  7480  7480 D HeadsetStateMachine: make
,08-23 08:44:13.431  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-23 08:44:13.431  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 08:44:13.431  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 08:44:13.431  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:13.431  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.431  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.431  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.431  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.431  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 08:44:13.431  7480  7480 E HeadsetStateMachine: # of Max HF connection is 2
08-23 08:44:13.431  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:13.431  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:13.431  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:13.431  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.441  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.441  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.441  1016  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-23 08:44:13.441  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:13.441  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-23 08:44:13.441  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-23 08:44:13.441  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 08:44:13.441  7505  7505 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:13.441  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.441  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 08:44:13.441  7505  7505 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:13.441  1016  3831 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:13.441  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.441  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.441  1016  3831 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.441  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:13.441  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:13.441  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 08:44:13.441  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-23 08:44:13.441  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 08:44:13.441  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 08:44:13.441  7480  7495 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-23 08:44:13.451  1016  1510 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-23 08:44:13.451  1016  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-23 08:44:13.451  1016  1510 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:13.451  1016  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:13.451  1016  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 08:44:13.451  7480  7480 I bluedroid: get_profile_interface handsfree
,08-23 08:44:13.471  7480  7480 I DualScoManager: Instantiating Dual Sco Manager
08-23 08:44:13.471  7480  7480 I DualScoManager: Set HeadsetServiceHelper
,08-23 08:44:13.471  7505  7505 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-23 08:44:13.471  7480  7480 D BluetoothAtMessage: createCMTIContentObservers
08-23 08:44:13.471  1016  1028 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-23 08:44:13.471  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:13.471  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:13.471  1016  1028 D SettingsProvider: selectionArgs: false
08-23 08:44:13.471  1016  1028 D SettingsProvider: selectionArgs: 1002
08-23 08:44:13.471  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:13.471  1016  1028 D SettingsProvider: ret = -1
08-23 08:44:13.481  7480  7518 D HeadsetStateMachine: Enter Disconnected: -2
,08-23 08:44:13.481  7480  7480 D HeadsetService: mStartError = false
08-23 08:44:13.481  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:13.481  7480  7518 D HeadsetStateMachine: Clear mHeadsetBrsf
08-23 08:44:13.481  7480  7518 D HeadsetStateMachine: map size, before remove : 0
08-23 08:44:13.481  7480  7518 D HeadsetStateMachine: map size, after remove: 0
,08-23 08:44:13.481  7480  7480 D A2dpService: Received start request. Starting profile...
08-23 08:44:13.481  7480  7480 D A2dpService: start()
08-23 08:44:13.481  7480  7480 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 08:44:13.481  7480  7480 I bluedroid: get_profile_interface avrcp
,08-23 08:44:13.491  7480  7480 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-23 08:44:13.491  7480  7480 D Avrcp   : Initialize Media Controller
08-23 08:44:13.491  7480  7480 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-23 08:44:13.491  7480  7480 E Avrcp   : getActiveSessions
08-23 08:44:13.491  7480  7480 D Avrcp   : pick active media Controller
08-23 08:44:13.491  7480  7480 D Avrcp   : Get the active Media Controller 
,08-23 08:44:13.511  7480  7480 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-23 08:44:13.511  7505  7505 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-23 08:44:13.511  7480  7522 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-23 08:44:13.511  7505  7505 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-23 08:44:13.511  7505  7505 D UserAnalysis: Create SecureDbHelper
08-23 08:44:13.511  7480  7480 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 08:44:13.511  7480  7480 D A2dpStateMachine: make
,08-23 08:44:13.511  7480  7480 I bluedroid: get_profile_interface a2dp
08-23 08:44:13.511  7480  7524 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-23 08:44:13.511  7480  7480 E bt-btif : warning : media task started media_task_refcnt 1 
,08-23 08:44:13.521  7480  7480 D A2dpService: mStartError = false
08-23 08:44:13.521  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:13.521  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-23 08:44:13.521  7480  7523 D A2dpStateMachine: Enter Disconnected: -2
08-23 08:44:13.521  7480  7480 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 08:44:13.521  7505  7505 D IntelligenceServiceApplication: onCreate()
,08-23 08:44:13.521  7480  7480 D HidService: Received start request. Starting profile...
08-23 08:44:13.521  7480  7480 D HidService: start()
08-23 08:44:13.521  7480  7480 I bluedroid: get_profile_interface hidhost
08-23 08:44:13.521  7480  7480 D HidService: setHidService(): set to: null
08-23 08:44:13.521  7480  7480 D HidService: mStartError = false
08-23 08:44:13.521  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:13.521  7480  7480 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-23 08:44:13.521  7480  7480 D HealthService: Received start request. Starting profile...
08-23 08:44:13.521  7480  7480 D HealthService: start()
,08-23 08:44:13.531  7480  7480 I bluedroid: get_profile_interface health
08-23 08:44:13.531  7480  7480 D HealthService: mStartError = false
08-23 08:44:13.531  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:13.531  7480  7480 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 08:44:13.531  1016  3831 I ActivityManager: Killing 7127:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-23 08:44:13.531  7480  7480 D PanService: Received start request. Starting profile...
08-23 08:44:13.531  7480  7480 D PanService: start()
08-23 08:44:13.531  7480  7480 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 08:44:13.531  7480  7480 I bluedroid: get_profile_interface pan
,08-23 08:44:13.531  7480  7480 D PanService: mStartError = false
08-23 08:44:13.531  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:13.531  7480  7522 D BluetoothMediaBrowser: no now playing list
,08-23 08:44:13.541  7480  7522 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-23 08:44:13.541  7480  7480 D BluetoothMapService: Received start request. Starting profile...
08-23 08:44:13.541  7480  7480 D BluetoothMapService: start()
,08-23 08:44:13.541  7480  7480 D BluetoothMapService: mStartError = false
,08-23 08:44:13.541  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:13.541  7480  7480 D HeadsetStateMachine: Try to query the phonestate on bind
,08-23 08:44:13.541  1428  1455 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 08:44:13.541  7505  7505 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-23 08:44:13.541  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-23 08:44:13.541  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-23 08:44:13.541  1428  1455 I Telecom : BluetoothPhoneService: Result of Message : true
08-23 08:44:13.541  7480  7480 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-23 08:44:13.551  1016  1377 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-23 08:44:13.551  7505  7505 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-23 08:44:13.551  7480  7480 D SapService: Received start request. Starting profile...
08-23 08:44:13.551  7480  7480 D SapService: start()
08-23 08:44:13.551  7480  7480 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-23 08:44:13.551  7480  7480 I bluedroid: get_profile_interface sap
08-23 08:44:13.551  7480  7480 D SapService: mStartError = false
08-23 08:44:13.551  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:13.551  7480  7480 D HeadsetStateMachine: Proxy object connected
,08-23 08:44:13.551  7480  7480 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-23 08:44:13.551  7480  7480 D HeadsetPhoneState: sendDeviceDataStateChanged
08-23 08:44:13.551  7480  7518 D HeadsetStateMachine: Disconnected process message: 11
,08-23 08:44:13.551  7480  7480 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-23 08:44:13.551  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-23 08:44:13.551  7480  7518 D HeadsetStateMachine: Disconnected process message: 18
08-23 08:44:13.551  7480  7480 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 08:44:13.551  7480  7480 D BluetoothA2dp: Proxy object connected
08-23 08:44:13.551  7480  7480 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-23 08:44:13.551  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-23 08:44:13.551  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-23 08:44:13.551  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-23 08:44:13.551  7480  7518 D HeadsetStateMachine: Disconnected process message: 10
08-23 08:44:13.551  7480  7518 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-23 08:44:13.551  7480  7518 D HeadsetStateMachine: Disconnected process message: 11
08-23 08:44:13.551  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-23 08:44:13.551  1016  3831 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-23 08:44:13.551  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:13.551  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:13.551  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:13.551  1016  3831 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:13.561  7505  7505 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-23 08:44:13.571  7529  7529 E Zygote  : MountEmulatedStorage()
08-23 08:44:13.571  7529  7529 E Zygote  : v2
08-23 08:44:13.571  7529  7529 I libpersona: KNOX_SDCARD checking this for 10105
08-23 08:44:13.571  7529  7529 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:13.571  7529  7529 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:13.571  7529  7529 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:13.571  1016  3831 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7529 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-23 08:44:13.571  7529  7529 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 08:44:13.591  7529  7529 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:13.601  7529  7529 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:13.621  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-23 08:44:13.621  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-23 08:44:13.621  7480  7495 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-23 08:44:13.621  7480  7495 I bluedroid: enable
,08-23 08:44:13.621  7480  7546 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 08:44:13.621  7480  7495 I bt_hci_bdroid: init
,08-23 08:44:13.621  7480  7495 I bt_vendor: bt-vendor : init
,08-23 08:44:13.621  7480  7495 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 08:44:13.621  7480  7495 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-23 08:44:13.621  7480  7495 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-23 08:44:13.621  7480  7495 D bt_userial_mct: userial_init
,08-23 08:44:13.621  7480  7495 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 08:44:13.631  7480  7495 I bt_vendor: Starting hciattach daemon
08-23 08:44:13.631  7480  7495 I bt_vendor: try to set false
,08-23 08:44:13.631  7480  7495 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-23 08:44:13.631  7480  7495 I bt_vendor: Starting hciattach daemon
08-23 08:44:13.631  7480  7495 I bt_vendor: try to set true
,08-23 08:44:13.651  7550  7550 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-23 08:44:13.701  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-23 08:44:13.711  7558  7558 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-23 08:44:13.731  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-23 08:44:13.731  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-23 08:44:13.741  7566  7566 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 08:44:13.751  7567  7567 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-23 08:44:13.771   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
,08-23 08:44:13.771   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:13.771  7529  7565 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 08:44:13.781   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-23 08:44:13.781   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:44:13.791  7529  7565 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.k.d(PG:583)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.e.b(PG:170)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.File.exists(File.java:363)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:13.941  7529  7529 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:13.941  7529  7529 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:13.951  1016  1029 I ActivityManager: Killing 7142:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-23 08:44:13.951  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-23 08:44:13.951  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 08:44:13.991  7529  7578 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-23 08:44:14.001  7579  7579 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-23 08:44:14.001  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-23 08:44:14.011  1016  3385 D SSRM:n  : SIOP:: AP = 320
,08-23 08:44:14.031  7480  7495 I bt_vendor: bluetooth satus is on
,08-23 08:44:14.031  7480  7548 D bt_userial_mct: userial_open(port:0)
08-23 08:44:14.031  7480  7548 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-23 08:44:14.031  7480  7548 I bt_vendor: Done intiailizing UART
,08-23 08:44:14.041  7480  7548 I bt_vendor: Done intiailizing UART
,08-23 08:44:14.041  7480  7548 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-23 08:44:14.041  7480  7548 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-23 08:44:14.041  7480  7584 D bt_userial_mct: Entering userial_read_thread()
,08-23 08:44:14.161  1016  1328 I art     : Explicit concurrent mark sweep GC freed 69533(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.384ms total 147.372ms
,08-23 08:44:14.161  1016  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_SAP
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_BTIF
08-23 08:44:14.161  7480  7546 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-23 08:44:14.161  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.161  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:14.161  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-23 08:44:14.261  7480  7546 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-23 08:44:14.261  7480  7546 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4127ed1 
,08-23 08:44:14.261  7480  7546 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4127ed1 
,08-23 08:44:14.281  7480  7498 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-23 08:44:14.281  7480  7498 E bt-btif : Calling BTA_HhEnable
,08-23 08:44:14.281  7480  7498 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-23 08:44:14.281  7480  7498 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-23 08:44:14.281  7480  7498 E BluetoothServiceJni: populateRssiValuesNative
08-23 08:44:14.281  7480  7498 I bluedroid: getModelRssiValues
08-23 08:44:14.281  7480  7498 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-23 08:44:14.281  7480  7498 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 08:44:14.281  7480  7498 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 08:44:14.281  1016  1016 D SettingsProvider: name = bluetooth_name
,08-23 08:44:14.281  7480  7498 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 08:44:14.281  7480  7498 D BluetoothAdapterProperties: Scan Mode:20
08-23 08:44:14.281  7480  7498 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 08:44:14.291  7480  7498 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-23 08:44:14.291  7480  7498 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-23 08:44:14.291  7480  7498 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-23 08:44:14.291  7480  7498 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-23 08:44:14.291  7480  7498 E bt-btif : btif_sock_init: !vhci_init
08-23 08:44:14.291  7480  7498 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-23 08:44:14.291  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:14.291  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:14.291  7480  7498 D IOP_DB_BT: db_open: db_open : handle 3025498128l, read 13894 bytes onto local cache
,08-23 08:44:14.291  7480  7498 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-23 08:44:14.291  7480  7584 E bt_mct  : hci lib postload completed
08-23 08:44:14.291  7480  7498 D IOP_DB_BT: db_query: result 1
,08-23 08:44:14.291  7480  7498 I         : iop_db_open: iop_db_open status 0
,08-23 08:44:14.291  7480  7498 D bte_conf: Device ID record 1 : primary
,08-23 08:44:14.291  7480  7498 D bte_conf:   vendorId            = 0075
,08-23 08:44:14.291  7480  7498 D bte_conf:   vendorIdSource      = 0001
08-23 08:44:14.291  7480  7498 D bte_conf:   product             = 0100
08-23 08:44:14.291  7480  7498 D bte_conf:   version             = 0200
,08-23 08:44:14.291  7480  7498 D bte_conf:   clientExecutableURL = 
08-23 08:44:14.291  7480  7498 D bte_conf:   serviceDescription  = 
08-23 08:44:14.291  7480  7498 D bte_conf:   documentationURL    = 
08-23 08:44:14.291  7480  7498 D bte_conf: bte_load_did_conf no section named DID2.
,08-23 08:44:14.301  7480  7495 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-23 08:44:14.301  7480  7498 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 08:44:14.301  7480  7495 D BluetoothAdapterProperties: ScanMode =  20
08-23 08:44:14.301  7480  7495 D BluetoothAdapterProperties: State =  11
,08-23 08:44:14.301  1016  1133 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 08:44:14.301  7480  7495 D BluetoothAdapterProperties: Setting state to 12
,08-23 08:44:14.301  7480  7495 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 08:44:14.301  1016  1231 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-23 08:44:14.301  1016  1231 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:14.301  1016  1231 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 08:44:14.301  1016  1231 D SettingsProvider: selectionArgs: false
08-23 08:44:14.301  1016  1231 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:14.301  1016  1231 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:14.301  1016  1231 D SettingsProvider: ret = -1
,08-23 08:44:14.301  7480  7495 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-23 08:44:14.311  7480  7495 D BluetoothAdapterService: updateAdapterState state is 12
,08-23 08:44:14.311  1016  3840 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:14.311  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.311  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:14.311  1016  3840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.311  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.321  7480  7498 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 08:44:14.321  7480  7498 D BluetoothAdapterProperties: Scan Mode:21
08-23 08:44:14.321  7480  7498 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:14.321  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:14.321  7480  7495 D BluetoothAdapterService: Autoconnection is available 
08-23 08:44:14.321  7480  7495 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-23 08:44:14.321  7480  7495 D BluetoothAdapterService: starting service from this receiver
,08-23 08:44:14.321  1016  3840 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:14.321  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.321  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:14.321  1016  3840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.321  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.321  7480  7495 I BluetoothAdapterState: Entering On State from state = 11
,08-23 08:44:14.331  1428  7001 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:14.331  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:14.331  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:14.331  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.331  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.331  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.331  1428  7001 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:14.331  7480  7488 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 08:44:14.331  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:14.331  1428  3271 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:14.331  1428  3271 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:14.331  1016  1045 D BluetoothPan: Binding service...
08-23 08:44:14.331  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 08:44:14.331  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.331  7480  7480 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-23 08:44:14.331  6821  7109 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 08:44:14.331  6821  7109 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 08:44:14.331  1940  1954 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:14.331  1940  1954 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:14.331  1428  1462 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:14.341  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:14.341  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:14.341  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.341  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.341  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.341  1428  1462 E BluetoothHeadset: BluetoothHeadset service is binded
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:14.341  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:14.341  7529  7545 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:14.341  7529  7545 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:14.341  1444  1475 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:14.341  1444  1475 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:14.341  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-23 08:44:14.341  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:14.341  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 08:44:14.341  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:14.341  3320  3331 D Bluetoothsap: onBluetoothStateChange: up=true
08-23 08:44:14.341  3320  3331 D Bluetoothsap: Binding service...
,08-23 08:44:14.341  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:14.341  7480  7480 I BluetoothPbapService: Handler(): got msg=1
,08-23 08:44:14.351  1016  1377 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 08:44:14.351  3320  3331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-23 08:44:14.351  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 08:44:14.351  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-23 08:44:14.351  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.351  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.351  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.351  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.351  3320  3331 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-23 08:44:14.351  7480  7493 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:14.351  7480  7493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 08:44:14.351  3320  7108 D BluetoothPan: Binding service...
,08-23 08:44:14.351  3320  3320 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-23 08:44:14.351  3320  3320 D SapProfile: Bluetooth service connected
08-23 08:44:14.351  3320  3320 D Bluetoothsap: getConnectedDevices()
08-23 08:44:14.351  7480  7591 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-23 08:44:14.361  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 08:44:14.361  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.361  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.361  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.361  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.361  3320  3320 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 08:44:14.361  3320  3320 D PanProfile: Bluetooth service connected
,08-23 08:44:14.361  1437  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:14.361  1437  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 08:44:14.361  3320  3334 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 08:44:14.361  7480  7591 D BluetoothSocket: bindListen(): myUserId = 0
08-23 08:44:14.361  7480  7591 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:44:14.361  3320  3334 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:14.361  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 08:44:14.361  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.361  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.361  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.361  7480  7591 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-23 08:44:14.361  7480  7591 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 08:44:14.361  7480  7591 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 08:44:14.361  7480  7591 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1db549a5
,08-23 08:44:14.361  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 08:44:14.361  7480  7591 D BluetoothSocket: channel: 19
,08-23 08:44:14.361  7480  7591 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-23 08:44:14.371  3320  7108 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:14.371  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:14.371  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:14.371  3320  3320 D BluetoothA2dp: Proxy object connected
08-23 08:44:14.371  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.371  3320  3320 D A2dpProfile: Bluetooth service connected
08-23 08:44:14.371  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.371  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.371  3320  7108 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:14.371  3320  3334 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 08:44:14.371  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-23 08:44:14.371  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.371  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.371  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.371  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.371  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 08:44:14.371  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:14.371  3320  7108 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:14.371  3320  7108 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 08:44:14.371  3320  3320 D HeadsetProfile: Bluetooth service connected
,08-23 08:44:14.371  1428  1462 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:14.371  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:14.371  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:14.371  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.371  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:14.381  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.381  1428  1462 E BluetoothHeadset: BluetoothHeadset service is binded
08-23 08:44:14.381  3320  7108 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 08:44:14.381  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-23 08:44:14.381  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.381  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.381  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.381  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 08:44:14.381  3320  3320 D BluetoothMap: Proxy object connected
08-23 08:44:14.381  3320  3320 D MapProfile: Bluetooth service connected
,08-23 08:44:14.381  3320  3320 D BluetoothMap: getConnectedDevices()
,08-23 08:44:14.381  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 08:44:14.381  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:14.381  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-23 08:44:14.381  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 08:44:14.381  1016  1016 D BluetoothA2dp: Proxy object connected
,08-23 08:44:14.381  1444  1692 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:14.381  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:14.381  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:14.381  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.381  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:14.381  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.391  1444  1692 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:14.391  1177  1186 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 08:44:14.391  3320  3320 D BluetoothPbap: Proxy object connected
08-23 08:44:14.391  3320  3320 D PbapServerProfile: Bluetooth service connected
08-23 08:44:14.391  1177  1186 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:14.391  3320  3331 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 08:44:14.391  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-23 08:44:14.391  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.391  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.391  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:14.391  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.391  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-23 08:44:14.391  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 08:44:14.391  3320  3320 D BluetoothInputDevice: Proxy object connected
08-23 08:44:14.391  3320  3320 D HidProfile: Bluetooth service connected
,08-23 08:44:14.391  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:14.391  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
,08-23 08:44:14.401  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 08:44:14.401  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-23 08:44:14.401  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@5a3b1, true
,08-23 08:44:14.401  1428  1428 D BluetoothHeadset: registerMessageListener
,08-23 08:44:14.401  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 08:44:14.401  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:14.401  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-23 08:44:14.401  1827  1827 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 08:44:14.411  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
08-23 08:44:14.411  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:14.411  1016  3839 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 08:44:14.411  1016  1329 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-23 08:44:14.411  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 08:44:14.411  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:14.411  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:14.411  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.421  7480  7590 D HeadsetService: registerMessageListener
,08-23 08:44:14.421  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.421  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:14.421  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:14.421  3320  3320 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-23 08:44:14.421  3320  3320 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-23 08:44:14.421  3320  3320 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-23 08:44:14.421  3320  3320 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-23 08:44:14.421  7480  7590 D HeadsetService: registerMessageListener
,08-23 08:44:14.421  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-23 08:44:14.421  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-23 08:44:14.421  7480  7518 D HeadsetStateMachine: Disconnected process message: 70
,08-23 08:44:14.421  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:14.421  7480  7518 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3d3ed17a
,08-23 08:44:14.421  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:14.421  7480  7593 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-23 08:44:14.431  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-23 08:44:14.431  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
08-23 08:44:14.431  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-23 08:44:14.431  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-23 08:44:14.431  7480  7593 D BluetoothSocket: bindListen(): myUserId = 0
08-23 08:44:14.431  7480  7593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:44:14.431  7480  7593 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-23 08:44:14.431  7480  7593 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 08:44:14.431  7480  7593 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 08:44:14.431  7480  7593 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ee8d2b
,08-23 08:44:14.431  7480  7593 D BluetoothSocket: channel: 5
,08-23 08:44:14.431  7480  7518 D HeadsetStateMachine: Disconnected process message: 9
,08-23 08:44:14.431  7480  7518 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-23 08:44:14.431  3320  3320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 08:44:14.441  1016  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 08:44:14.441  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.441  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.441  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:14.441  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 08:44:14.441   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-23 08:44:14.441   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-23 08:44:14.441   282   282 V voice   : voice_set_parameters: exit with code(-2)
,08-23 08:44:14.441   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-23 08:44:14.441   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-23 08:44:14.441   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-23 08:44:14.441   282   282 V audio_hw_primary: adev_set_parameters: exit
08-23 08:44:14.441  7480  7518 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-23 08:44:14.451  3320  3320 D DockEventReceiver: finishStartingService: stopping service
,08-23 08:44:14.451  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:14.451  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:14.451  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-23 08:44:14.471  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:14.471  7480  7480 D BtConfig.SecureMode: isSecureModeOn:false
,08-23 08:44:14.471  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:14.471  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.471  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:14.471  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:14.471  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:14.481  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 08:44:14.481  1016  1231 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:14.481  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 08:44:14.481  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:14.481  1016  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:14.481  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:14.501  1016  3840 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-23 08:44:14.501  1940  7599 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 08:44:14.501  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 08:44:14.501  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:14.501  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:14.501  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:14.501  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:14.511  7480  7603 D BluetoothSocket: bindListen(): myUserId = 0
,08-23 08:44:14.511  7480  7603 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:44:14.521  7480  7603 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-23 08:44:14.521  7480  7603 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 08:44:14.521  7480  7603 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 08:44:14.521  7480  7603 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b14085d
,08-23 08:44:14.521  7480  7603 D BluetoothSocket: channel: 12
08-23 08:44:14.521  7480  7603 I BtOppRfcommListener: Accept thread started.
,08-23 08:44:14.521  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:14.521  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:14.521  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:14.521  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:14.531  1940  7599 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-23 08:44:15.021   294   294 E SMD     : DCD OFF,
,08-23 08:44:16.091  6821  6874 D BluetoothAdapter: disable()
,08-23 08:44:16.091  1016  1028 D SettingsProvider: name = bluetooth_on
,08-23 08:44:16.101  7480  7495 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-23 08:44:16.101  7480  7495 D BluetoothAdapterProperties: Setting state to 13
08-23 08:44:16.101  7480  7495 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 08:44:16.101  7480  7495 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 08:44:16.101  7480  7495 D BluetoothAdapterService: updateAdapterState state is 13
08-23 08:44:16.101  1016  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:16.101  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 08:44:16.101  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:16.111  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:16.111  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:16.111  7480  7495 D BluetoothAdapterService: Autoconnection is available 
,08-23 08:44:16.111  7480  7495 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-23 08:44:16.111  7480  7495 D BluetoothAdapterService: terminating service from this receiver
,08-23 08:44:16.111  7480  7480 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-23 08:44:16.111  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-23 08:44:16.111  7480  7480 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@270215d2, channel: 19, state: LISTENING,
08-23 08:44:16.111  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
08-23 08:44:16.111  7480  7480 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@270215d2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1db549a5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30f576a3mSocket: android.net.LocalSocket@7bb5da0 impl:android.net.LocalSocketImpl@2b0dcd59 fd:FileDescriptor[74]
08-23 08:44:16.111  7480  7480 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@7bb5da0 impl:android.net.LocalSocketImpl@2b0dcd59 fd:FileDescriptor[74]
,08-23 08:44:16.121  1177  1177 D BluetoothTile:  onBluetoothStateChange:,
,08-23 08:44:16.121  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 08:44:16.121  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:16.121  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-23 08:44:16.121  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:16.121  1827  1827 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-23 08:44:16.121  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:16.131  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:16.131  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 08:44:16.131  1016  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 08:44:16.131  1016  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 08:44:16.131  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:16.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:16.141  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:16.141  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 08:44:16.141  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:16.141  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 08:44:16.141  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:16.141  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:16.141  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:16.141  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 08:44:16.141  7480  7495 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 08:44:16.141  7480  7495 D BluetoothAdapterProperties: mDiscovering is false
,08-23 08:44:16.141  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 08:44:16.141  1016  1478 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 08:44:16.151  7480  7495 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-23 08:44:16.151  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:16.151  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:16.151  3320  3320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 08:44:16.151  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:16.151  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-23 08:44:16.151  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:16.151  6821  6821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-23 08:44:16.151  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:16.161  1016  3840 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 08:44:16.161  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 08:44:16.161  7480  7498 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-23 08:44:16.161  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:16.161  7480  7498 D BluetoothAdapterProperties: Scan Mode:20
08-23 08:44:16.161  1016  3840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:16.161  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 08:44:16.171  3320  3320 D BluetoothPbap: Proxy object disconnected
,08-23 08:44:16.171  3320  3320 D PbapServerProfile: Bluetooth service disconnected
,08-23 08:44:16.171  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:16.171  7480  7495 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 08:44:16.171  7480  7495 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-23 08:44:16.171  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:16.171  7480  7495 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-23 08:44:16.171  7480  7495 E bt-btif : cmd socket is not created
,08-23 08:44:16.171  7480  7495 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-23 08:44:16.181  7480  7546 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-23 08:44:16.181  7480  7603 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-23 08:44:16.181  7480  7546 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-23 08:44:16.181  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 08:44:16.181  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:16.181  7480  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:44:16.191  3320  3320 D DockEventReceiver: finishStartingService: stopping service
,08-23 08:44:16.191  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:16.201  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:16.201  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-23 08:44:16.201  7480  7480 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3547bd1e, channel: 5, state: LISTENING
,08-23 08:44:16.201  7480  7480 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3547bd1e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ee8d2b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e5ed9ffmSocket: android.net.LocalSocket@3f08b3cc impl:android.net.LocalSocketImpl@1944e615 fd:FileDescriptor[76]
,08-23 08:44:16.201  7480  7480 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f08b3cc impl:android.net.LocalSocketImpl@1944e615 fd:FileDescriptor[76]
,08-23 08:44:16.201  7480  7480 I BtOppRfcommListener: stopping Accept Thread
,08-23 08:44:16.201  7480  7480 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9ae8d2a, channel: 12, state: LISTENING
,08-23 08:44:16.201  7480  7480 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9ae8d2a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b14085d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@26d1171bmSocket: android.net.LocalSocket@35f340b8 impl:android.net.LocalSocketImpl@1c9ace91 fd:FileDescriptor[79]
08-23 08:44:16.201  7480  7480 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35f340b8 impl:android.net.LocalSocketImpl@1c9ace91 fd:FileDescriptor[79]
,08-23 08:44:16.201  7480  7603 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 08:44:16.211  7480  7480 V BluetoothOppManager: cleanUp...
,08-23 08:44:16.221  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 08:44:16.221  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:44:16.381  7480  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:44:16.381  7480  7546 W bt-btif : HC lib lpm enable=0 return
08-23 08:44:16.381  7480  7584 I bt_userial_mct: exiting userial_read_thread
,08-23 08:44:16.381  7480  7546 W bt-btif : ag scb idx 2 not allocated
08-23 08:44:16.381  7480  7584 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 08:44:16.381  7480  7498 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 08:44:16.381  7480  7548 I bt_vendor: hw_epilog_process
,08-23 08:44:16.381  7480  7498 D bt_userial_mct: userial_close
08-23 08:44:16.381  7480  7498 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-23 08:44:16.381  7480  7546 E bt-btif : BTA AG is already disabled, ignoring ...
,08-23 08:44:17.221  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 08:44:17.221  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 08:44:17.221  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 08:44:17.221  1016  1029 D BatteryService: stay LED for fully charged
08-23 08:44:17.221  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 08:44:17.231  1016  1016 I MotionRecognitionService: Plugged
,08-23 08:44:17.231  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 08:44:17.231  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 08:44:17.231  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 08:44:17.231  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 08:44:17.231  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 08:44:17.251  7480  7480 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 08:44:17.251  7480  7518 D HeadsetStateMachine: Disconnected process message: 10
,08-23 08:44:17.261  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:44:17.261  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:44:17.261  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:44:17.281  7480  7498 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-23 08:44:17.281  7480  7498 I bt_vendor: bluetooth satus is on
08-23 08:44:17.281  7480  7498 I bt_vendor: bt-vendor : resetting BT status
08-23 08:44:17.281  7480  7498 I bt_vendor: Starting hciattach daemon
08-23 08:44:17.281  7480  7498 I bt_vendor: try to set false
,08-23 08:44:17.281  7480  7498 I bt_vendor: Starting hciattach daemon
,08-23 08:44:17.281  7480  7498 I bt_vendor: try to set false
,08-23 08:44:17.281  7480  7498 I bt_vendor: cleanup
,08-23 08:44:17.281  7480  7546 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 08:44:17.281  7480  7498 I GKI_LINUX: GKI_exit_task 0 done
,08-23 08:44:17.281  7480  7498 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-23 08:44:17.291  7480  7495 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 08:44:17.291  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-23 08:44:17.291  7480  7495 D BtConfig.SecureMode: isSecureModeOn:false,
08-23 08:44:17.291  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-23 08:44:17.291  7480  7495 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-23 08:44:17.291  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:17.291  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 08:44:17.291  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-23 08:44:17.291  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
08-23 08:44:17.291  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-23 08:44:17.291  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:17.291  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-23 08:44:17.291  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-23 08:44:17.291  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 08:44:17.301  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:17.291  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 08:44:17.301  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 08:44:17.291  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-23 08:44:17.291  7480  7480 D BtGatt.DebugUtils: handleDebugAction() action=null,
08-23 08:44:17.301  7480  7480 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 08:44:17.301  7480  7480 D BtGatt.GattService: stop(),
08-23 08:44:17.301  7480  7480 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 08:44:17.301  1016  1478 W ActivityManager: userId = 0, bbcId = -10000,
,08-23 08:44:17.301  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.301  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:17.301  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 08:44:17.301  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
08-23 08:44:17.301  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-23 08:44:17.301  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:17.301  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:17.301  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.301  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-23 08:44:17.301  7480  7480 D HeadsetService: Received stop request...Stopping profile...,
08-23 08:44:17.311  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-23 08:44:17.311  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:17.311  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-23 08:44:17.311  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:17.311  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:17.311  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-23 08:44:17.311  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:17.311  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.311  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:17.311  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-23 08:44:17.311  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 08:44:17.311  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-23 08:44:17.311  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-23 08:44:17.311  1016  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:17.311  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-23 08:44:17.311  3320  3320 D HeadsetProfile: Bluetooth service disconnected
,08-23 08:44:17.311  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:17.311  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.311  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:17.321  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-23 08:44:17.321  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-23 08:44:17.321  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 08:44:17.321  1016  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:17.321  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-23 08:44:17.321  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:17.321  1016  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.321  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:17.321  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-23 08:44:17.321  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:17.321  7480  7495 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:17.321  1016  1510 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:17.321  1016  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 08:44:17.321  1016  1510 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:17.321  1016  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.321  1016  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:17.321  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-23 08:44:17.321  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 08:44:17.321  7480  7495 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-23 08:44:17.321  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:17.321  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 08:44:17.321  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:17.321  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.321  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:17.331  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-23 08:44:17.331  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 08:44:17.331  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-23 08:44:17.331  7480  7495 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 08:44:17.331  7480  7495 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 08:44:17.331  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-23 08:44:17.331  7480  7495 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 08:44:17.331  7480  7480 D A2dpService: Received stop request...Stopping profile...
08-23 08:44:17.331  7480  7523 D A2dpStateMachine: Exit Disconnected: -1
,08-23 08:44:17.331  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:17.331  1016  1016 D BluetoothA2dp: Proxy object disconnected
,08-23 08:44:17.331  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 08:44:17.331  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-23 08:44:17.331  7480  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:17.331  7480  7480 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-23 08:44:17.331  7480  7480 D HidService: Received stop request...Stopping profile...
08-23 08:44:17.331  7480  7480 D HidService: Stopping Bluetooth HidService
08-23 08:44:17.331  7480  7480 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 08:44:17.331  7480  7480 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-23 08:44:17.331  7480  7480 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 08:44:17.331  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:17.331  3320  3320 D BluetoothA2dp: Proxy object disconnected
08-23 08:44:17.331  3320  3320 D A2dpProfile: Bluetooth service disconnected
,08-23 08:44:17.341  3320  3320 D BluetoothInputDevice: Proxy object disconnected
08-23 08:44:17.341  3320  3320 D HidProfile: Bluetooth service disconnected
,08-23 08:44:17.341  7480  7480 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 08:44:17.341  7480  7480 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-23 08:44:17.341  7480  7480 D HealthService: Received stop request...Stopping profile...,
08-23 08:44:17.341  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:17.341  7480  7480 D PanService: Received stop request...Stopping profile...
08-23 08:44:17.341  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
08-23 08:44:17.341  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-23 08:44:17.341  7480  7480 D BluetoothMapService: Received stop request...Stopping profile...
,08-23 08:44:17.351  3320  3320 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 08:44:17.351  3320  3320 D PanProfile: Bluetooth service disconnected
,08-23 08:44:17.351  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:17.351  7480  7480 D SapService: Received stop request...Stopping profile...
08-23 08:44:17.351  7480  7480 D SapService: Stopping Bluetooth SapService
08-23 08:44:17.351  7480  7480 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a04aee3
,08-23 08:44:17.351  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-23 08:44:17.351  7480  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:17.351  7480  7480 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-23 08:44:17.351  7480  7480 D BluetoothA2dp: Proxy object disconnected
08-23 08:44:17.351  7480  7480 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-23 08:44:17.351  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-23 08:44:17.351  7480  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:17.351  7480  7480 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:17.351  7480  7524 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 08:44:17.361  3320  3320 D BluetoothMap: Proxy object disconnected
08-23 08:44:17.361  3320  3320 D MapProfile: Bluetooth service disconnected
08-23 08:44:17.361  3320  3320 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-23 08:44:17.361  3320  3320 D SapProfile: Bluetooth service disconnected
,08-23 08:44:17.361  7480  7480 I GKI_LINUX: GKI_exit_task 2 done
08-23 08:44:17.361  7480  7480 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 08:44:17.361  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-23 08:44:17.361  7480  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:17.361  7480  7480 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
08-23 08:44:17.361  7480  7480 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-23 08:44:17.361  7480  7480 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 08:44:17.361  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-23 08:44:17.361  7480  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:17.361  7480  7480 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:17.361  7480  7480 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-23 08:44:17.361  7480  7480 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 08:44:17.361  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-23 08:44:17.361  7480  7480 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 08:44:17.361  7480  7480 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-23 08:44:17.361  7480  7480 E BluetoothAdapterService(168079075): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-23 08:44:17.361  7480  7480 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-23 08:44:17.361  7480  7480 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-23 08:44:17.361  7480  7495 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-23 08:44:17.361  7480  7495 D BluetoothAdapterProperties: Setting state to 10
08-23 08:44:17.361  7480  7495 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-23 08:44:17.361  7480  7495 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 08:44:17.361  7480  7495 D BluetoothAdapterService: updateAdapterState state is 10
,08-23 08:44:17.361  7480  7495 D BluetoothAdapterService: Autoconnection is available ,
08-23 08:44:17.361  7480  7495 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-23 08:44:17.361  7480  7495 I BluetoothAdapterState: Entering OffState
08-23 08:44:17.371  7480  7493 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 08:44:17.371  1428  1455 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:17.371  1428  1455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.371  6821  6830 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:17.371  6821  6830 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 08:44:17.371  6821  6830 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-23 08:44:17.371  6821  6830 D BluetoothLeAdvertiser: Exit stop advertising
08-23 08:44:17.371  6821  6830 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-23 08:44:17.371  6821  6830 D BluetoothLeScanner: Exiting stopAllScan
,08-23 08:44:17.371  1940  1954 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 08:44:17.371  1940  1954 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.371  7529  7537 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:17.371  7529  7537 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.371  1444  3318 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 08:44:17.371  1444  3318 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.371  3320  7108 D Bluetoothsap: onBluetoothStateChange: up=false
08-23 08:44:17.371  3320  7108 D Bluetoothsap: Unbinding service...
,08-23 08:44:17.371  7480  7488 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 08:44:17.371  7480  7488 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.381  1437  1460 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 08:44:17.381  1437  1460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.381  3320  3334 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 08:44:17.381  3320  3331 D BluetoothMap: onBluetoothStateChange: up=false
,08-23 08:44:17.381  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 08:44:17.381  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.381  3320  3334 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-23 08:44:17.381  3320  3334 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-23 08:44:17.381  3320  7108 D BluetoothPbap: onBluetoothStateChange: up=false
,08-23 08:44:17.381  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-23 08:44:17.381  1177  1624 D BluetoothAdapter: onBluetoothStateChange: up=false
08-23 08:44:17.381  1177  1624 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-23 08:44:17.381  3320  3331 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-23 08:44:17.391  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-23 08:44:17.391  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-23 08:44:17.401  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:17.401  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-23 08:44:17.401  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-23 08:44:17.401  1177  1177 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:17.401  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 08:44:17.401  1177  1702 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
,08-23 08:44:17.401  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:17.401  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-23 08:44:17.401  1177  1702 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:17.411  7480  7498 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-23 08:44:17.411  1177  1177 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:17.411  1177  1177 D BluetoothAdapter: 522825987: getState() :  mService = null. Returning STATE_OFF
,08-23 08:44:17.411  1016  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 08:44:17.411  1827  1827 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 08:44:17.411  7480  7480 I GKI_LINUX: GKI_exit_task 1 done
08-23 08:44:17.411  7480  7480 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-23 08:44:17.411  7480  7480 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 08:44:17.411  1016  1328 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 08:44:17.411  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 08:44:17.411  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:17.411  1940  2190 D BluetoothAdapter: 625864005: getState() :  mService = null. Returning STATE_OFF
08-23 08:44:17.411  1940  2190 D BluetoothAdapter: 625864005: getState() :  mService = null. Returning STATE_OFF
,08-23 08:44:17.411  7480  7480 I art     : System.exit called, status: 0
08-23 08:44:17.411  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:17.411  7480  7480 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 08:44:17.411  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:17.411  1016  1329 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:17.411  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 08:44:17.421  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:17.421  1016  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:17.421  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:17.421  3320  3320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 08:44:17.421  1016  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-23 08:44:17.421  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 08:44:17.421  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:17.421  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:17.421  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 08:44:17.431  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-23 08:44:17.431  3320  3320 D DockEventReceiver: finishStartingService: stopping service
,08-23 08:44:17.431  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:17.451  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:17.451  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-23 08:44:17.451  1016  1478 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 08:44:17.461  1016  1478 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-23 08:44:17.461  1016  1478 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-23 08:44:17.461  1016  1478 W BroadcastQueue: android.os.TransactionTooLargeException
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-23 08:44:17.461  1016  1478 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 08:44:17.461  1016  1478 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-23 08:44:17.461  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:17.461  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:17.461  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:17.461  1016  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:17.481  7619  7619 E Zygote  : MountEmulatedStorage(),
08-23 08:44:17.481  7619  7619 I libpersona: KNOX_SDCARD checking this for 1002
08-23 08:44:17.481  7619  7619 E Zygote  : v2
08-23 08:44:17.481  7619  7619 I libpersona: KNOX_SDCARD not a persona,
08-23 08:44:17.481  7619  7619 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:17.481  1016  1478 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7619 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-23 08:44:17.481  7619  7619 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:17.481  7619  7619 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:17.501  7619  7619 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:17.501  7619  7619 D ActivityThread: Added TimaKeyStore provider,
,08-23 08:44:17.511  7619  7619 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-23 08:44:17.511  7619  7619 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 08:44:17.531  7619  7619 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding GattService
,08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding HeadsetService
08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding A2dpService
,08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding HidService
08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding HealthService
08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding PanService
,08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding SapService
08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding SapClientService
08-23 08:44:17.561  7619  7619 D BtSettings.ProfileConfig: Adding HidDevService,
08-23 08:44:17.561  7619  7619 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-23 08:44:17.571  1016  1510 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-23 08:44:17.571  1016  1510 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.571  1016  1510 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.571  1016  1510 D SettingsProvider: selectionArgs: false
08-23 08:44:17.571  1016  1510 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.571  1016  1510 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.571  1016  1510 D SettingsProvider: ret = -1
,08-23 08:44:17.571  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-23 08:44:17.571  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.571  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.571  1016  1029 D SettingsProvider: selectionArgs: false
08-23 08:44:17.571  1016  1029 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.571  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.571  1016  1029 D SettingsProvider: ret = -1
,08-23 08:44:17.571  1016  1328 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-23 08:44:17.571  1016  1328 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.571  1016  1328 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.571  1016  1328 D SettingsProvider: selectionArgs: false
08-23 08:44:17.571  1016  1328 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.571  1016  1328 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.571  1016  1328 D SettingsProvider: ret = -1
,08-23 08:44:17.571  1016  1329 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-23 08:44:17.571  1016  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.571  1016  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.571  1016  1329 D SettingsProvider: selectionArgs: false
08-23 08:44:17.571  1016  1329 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.571  1016  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.571  1016  1329 D SettingsProvider: ret = -1
,08-23 08:44:17.571  1016  1377 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-23 08:44:17.571  1016  1377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.571  1016  1377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.571  1016  1377 D SettingsProvider: selectionArgs: false
,08-23 08:44:17.571  1016  1377 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.571  1016  1377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 08:44:17.571  1016  1377 D SettingsProvider: ret = -1
,08-23 08:44:17.571  1016  3840 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-23 08:44:17.571  1016  3840 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.571  1016  3840 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.571  1016  3840 D SettingsProvider: selectionArgs: false
08-23 08:44:17.571  1016  3840 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.571  1016  3840 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.571  1016  3840 D SettingsProvider: ret = -1
,08-23 08:44:17.571  1016  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-23 08:44:17.571  1016  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.581  1016  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 08:44:17.581  1016  1491 D SettingsProvider: selectionArgs: false
08-23 08:44:17.581  1016  1491 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.581  1016  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.581  1016  1491 D SettingsProvider: ret = -1
,08-23 08:44:17.581  1016  3839 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-23 08:44:17.581  1016  3839 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-23 08:44:17.581  1016  3839 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.581  1016  3839 D SettingsProvider: selectionArgs: false
08-23 08:44:17.581  1016  3839 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:17.581  1016  3839 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.581  1016  3839 D SettingsProvider: ret = -1
,08-23 08:44:17.581  1016  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:17.581  1016  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.581  1016  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.581  1016  1133 D SettingsProvider: selectionArgs: false
08-23 08:44:17.581  1016  1133 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.581  1016  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.581  1016  1133 D SettingsProvider: ret = -1
,08-23 08:44:17.581  1016  1231 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:17.581  1016  1231 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.581  1016  1231 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.581  1016  1231 D SettingsProvider: selectionArgs: false
08-23 08:44:17.581  1016  1231 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.581  1016  1231 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.581  1016  1231 D SettingsProvider: ret = -1
,08-23 08:44:17.581  1016  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-23 08:44:17.581  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.581  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.581  1016  1478 D SettingsProvider: selectionArgs: false
08-23 08:44:17.581  1016  1478 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.581  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.581  1016  1478 D SettingsProvider: ret = -1
,08-23 08:44:17.581  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-23 08:44:17.581  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:17.581  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:17.581  1016  1028 D SettingsProvider: selectionArgs: false,
08-23 08:44:17.581  1016  1028 D SettingsProvider: selectionArgs: 1002
08-23 08:44:17.581  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:17.581  1016  1028 D SettingsProvider: ret = -1
,08-23 08:44:17.591  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 08:44:17.591  1016  3840 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:17.591  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 08:44:17.591  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:17.591  1016  3840 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:17.591  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:17.601  1940  7635 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 08:44:17.601  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 08:44:17.611  1016  1329 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:17.611  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:17.611  1016  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:17.611  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:17.621  1940  7635 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-23 08:44:18.031   294   294 E SMD     : DCD OFF
,08-23 08:44:18.821  1016  1048 I PowerManagerService: [PWL] Off : 75s ago
,08-23 08:44:18.821  1016  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-23 08:44:18.821  1016  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-23 08:44:18.821  1016  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=14033)
,08-23 08:44:18.981  1016  1304 E Watchdog: !@Sync 4
,08-23 08:44:19.101  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 08:44:19.101  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:20.741   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 08:44:21.031   294   294 E SMD     : DCD OFF,
,08-23 08:44:21.741   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 08:44:22.101  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:44:22.101  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28b0deb3 added. We now have 6 listener(s)
,08-23 08:44:22.101  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:22.111  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:44:22.111  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@289b8c70 added. We now have 7 listener(s)
,08-23 08:44:22.111  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:22.111  6821  6874 I System.out: IsBluetoothEnabled
,08-23 08:44:22.111  6821  6874 D BluetoothAdapter: disable()
,08-23 08:44:22.111  1016  1029 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-23 08:44:22.121  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:22.121  6821  6874 D BluetoothAdapter: enable()
,08-23 08:44:22.121  1016  1329 W ActivityManager: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-23 08:44:22.121  1016  1329 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-23 08:44:22.121  1016  1329 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 08:44:22.121  1016  1329 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 08:44:22.121  1016  1329 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-23 08:44:22.121  1016  1329 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-23 08:44:22.121  1016  1329 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-23 08:44:22.121  1016  1329 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-23 08:44:22.121  1016  1329 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:22.121  1016  1329 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:22.131  1016  1329 D SettingsProvider: name = bluetooth_on,
,08-23 08:44:22.141  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-23 08:44:22.141  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:22.141  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-23 08:44:22.141  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-23 08:44:22.181  7619  7619 D BluetoothAdapterState: make
,08-23 08:44:22.191  7619  7619 I bluedroid: init
,08-23 08:44:22.191  7619  7641 I BluetoothAdapterState: Entering OffState,
08-23 08:44:22.191  7619  7619 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 08:44:22.191  7619  7619 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 08:44:22.191  7619  7619 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 08:44:22.191  7619  7619 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-23 08:44:22.191  7619  7619 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-23 08:44:22.191  7619  7619 I bluedroid: get_profile_interface socket
08-23 08:44:22.191  7619  7619 I bluedroid: get_profile_interface map_client
,08-23 08:44:22.191  7619  7644 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-23 08:44:22.201  7619  7619 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-23 08:44:22.201  7619  7644 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-23 08:44:22.201  7619  7644 E BluetoothServiceJni: populateRssiValuesNative
08-23 08:44:22.201  7619  7644 I bluedroid: getModelRssiValues
08-23 08:44:22.201  7619  7644 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-23 08:44:22.201  7619  7644 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 08:44:22.201  7619  7619 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-23 08:44:22.211  7619  7644 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 08:44:22.211  1016  1016 D SettingsProvider: name = bluetooth_name
,08-23 08:44:22.211  1016  1328 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-23 08:44:22.211  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.211  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:22.211  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:22.211  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.211  7619  7628 I bluedroid: config_hci_snoop_log
,08-23 08:44:22.211  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 08:44:22.221  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-23 08:44:22.221  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-23 08:44:22.221  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-23 08:44:22.221  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 08:44:22.221  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:22.221  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-23 08:44:22.221  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-23 08:44:22.231  7619  7619 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-23 08:44:22.231  7619  7641 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-23 08:44:22.231  7619  7641 D BluetoothAdapterProperties: Setting state to 11
08-23 08:44:22.231  7619  7641 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 08:44:22.231  7619  7641 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 08:44:22.231  7619  7641 D BluetoothAdapterService: updateAdapterState state is 11
,08-23 08:44:22.231  7619  7641 D BluetoothAdapterService: Autoconnection is available 
08-23 08:44:22.231  7619  7641 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-23 08:44:22.231  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:22.231  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-23 08:44:22.241  7619  7641 D BluetoothSecureManager: getInstant: null
,08-23 08:44:22.241  7619  7641 D BluetoothSecureManager: calling getMethod for getService
08-23 08:44:22.241  7619  7641 D BluetoothSecureManager: calling getService
,08-23 08:44:22.241  7619  7641 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@179d7f36
,08-23 08:44:22.241  1016  1028 D BluetoothSecureManagerService: isSecureModeEnabled
08-23 08:44:22.241  1016  1028 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-23 08:44:22.241  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-23 08:44:22.241  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:22.241  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-23 08:44:22.241  7619  7641 D BtConfig.SecureMode: isSecureModeOn:false
08-23 08:44:22.241  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-23 08:44:22.241  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-23 08:44:22.241  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-23 08:44:22.251  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-23 08:44:22.251  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
08-23 08:44:22.251  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-23 08:44:22.251  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-23 08:44:22.251  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-23 08:44:22.251  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:22.251  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-23 08:44:22.251  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-23 08:44:22.251  1016  3840 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 08:44:22.251  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-23 08:44:22.251  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-23 08:44:22.251  1016  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-23 08:44:22.251  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:22.251  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-23 08:44:22.251  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:22.261  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-23 08:44:22.261  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-23 08:44:22.261  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 08:44:22.261  7619  7641 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-23 08:44:22.261  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:22.261  1827  1827 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 08:44:22.261  7619  7641 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:22.261  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-23 08:44:22.261  1016  1377 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:22.261  1016  1377 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-23 08:44:22.261  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-23 08:44:22.261  7619  7641 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:22.261  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 08:44:22.261  1016  1377 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:22.261  1016  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:22.261  1016  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 08:44:22.261  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:22.261  7619  7641 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-23 08:44:22.261  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-23 08:44:22.261  7619  7641 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-23 08:44:22.261  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:22.261  7619  7641 D BluetoothBondStateMachine: make
,08-23 08:44:22.271  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-23 08:44:22.271  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-23 08:44:22.271  7619  7641 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-23 08:44:22.271  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:22.271  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-23 08:44:22.271  7619  7647 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 08:44:22.271  1016  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:22.271  1016  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-23 08:44:22.271  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:22.271  1016  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:22.271  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.271  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-23 08:44:22.271  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-23 08:44:22.271  7619  7641 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-23 08:44:22.271  7619  7619 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 08:44:22.271  7619  7619 D BtGatt.GattService: Received start request. Starting profile...
08-23 08:44:22.271  7619  7619 D BtGatt.GattService: start()
08-23 08:44:22.271  7619  7619 D BtGatt.GattService: start()
08-23 08:44:22.271  7619  7619 I bluedroid: get_profile_interface gatt
,08-23 08:44:22.271  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:22.271  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-23 08:44:22.271  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
08-23 08:44:22.271  7619  7619 D BtGatt.AdvertiseManager: advertise manager created
,08-23 08:44:22.281  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:22.281  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:22.281  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.281  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-23 08:44:22.281  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-23 08:44:22.281  7619  7641 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-23 08:44:22.281  1016  1231 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:22.281  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.291  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:22.291  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:22.291  7619  7619 D BtGatt.GattService: mStartError = false
08-23 08:44:22.291  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
,08-23 08:44:22.291  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.291  7619  7619 D HeadsetService: Received start request. Starting profile...
08-23 08:44:22.291  7619  7619 D HeadsetService: start()
,08-23 08:44:22.291  7619  7619 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 08:44:22.291  7619  7619 D HeadsetStateMachine: make
,08-23 08:44:22.301  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-23 08:44:22.301  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-23 08:44:22.301  7619  7641 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-23 08:44:22.301  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-23 08:44:22.301  7619  7619 E HeadsetStateMachine: # of Max HF connection is 2
08-23 08:44:22.301  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.301  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:22.301  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:22.301  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.311  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-23 08:44:22.311  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-23 08:44:22.311  7619  7641 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-23 08:44:22.311  1016  3840 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-23 08:44:22.311  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.311  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:22.311  1016  3840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:22.311  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 08:44:22.311  1016  1231 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:22.311  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.311  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:22.311  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:22.311  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.321  1016  1329 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-23 08:44:22.321  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.321  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:22.321  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:22.321  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-23 08:44:22.321  7619  7619 I bluedroid: get_profile_interface handsfree
08-23 08:44:22.321  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-23 08:44:22.321  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-23 08:44:22.321  7619  7641 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-23 08:44:22.321  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:22.321  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.321  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:22.321  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:22.321  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.331  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:22.331  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-23 08:44:22.331  7619  7641 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-23 08:44:22.331  1016  3839 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:22.331  1016  3839 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.331  1016  3839 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:22.331  1016  3839 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:22.331  1016  3839 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.331  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-23 08:44:22.331  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-23 08:44:22.331  7619  7641 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-23 08:44:22.331  1016  3840 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:22.331  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 08:44:22.341  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:22.341  1016  3840 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:22.341  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:22.341  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:22.341  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-23 08:44:22.341  7619  7619 I DualScoManager: Instantiating Dual Sco Manager
08-23 08:44:22.341  7619  7619 I DualScoManager: Set HeadsetServiceHelper
,08-23 08:44:22.341  7619  7619 D BluetoothAtMessage: createCMTIContentObservers
,08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-23 08:44:22.341  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-23 08:44:22.341  7619  7641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-23 08:44:22.341  7619  7641 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-23 08:44:22.341  7619  7641 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-23 08:44:22.341  1016  1478 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-23 08:44:22.341  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:22.351  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:22.351  1016  1478 D SettingsProvider: selectionArgs: false,
08-23 08:44:22.351  1016  1478 D SettingsProvider: selectionArgs: 1002
,08-23 08:44:22.351  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:22.351  1016  1478 D SettingsProvider: ret = -1
,08-23 08:44:22.351  7619  7650 D HeadsetStateMachine: Enter Disconnected: -2
,08-23 08:44:22.351  7619  7619 D HeadsetService: mStartError = false
08-23 08:44:22.351  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
,08-23 08:44:22.351  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-23 08:44:22.351  7619  7650 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-23 08:44:22.351  7619  7650 D HeadsetStateMachine: map size, before remove : 0
08-23 08:44:22.351  7619  7650 D HeadsetStateMachine: map size, after remove: 0
,08-23 08:44:22.351  7619  7619 D A2dpService: Received start request. Starting profile...
08-23 08:44:22.351  7619  7619 D A2dpService: start()
,08-23 08:44:22.361  7619  7619 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-23 08:44:22.361  7619  7619 I bluedroid: get_profile_interface avrcp
,08-23 08:44:22.361  7619  7619 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 08:44:22.361  7619  7619 D Avrcp   : Initialize Media Controller
08-23 08:44:22.361  7619  7619 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-23 08:44:22.361  7619  7619 E Avrcp   : getActiveSessions
08-23 08:44:22.361  7619  7619 D Avrcp   : pick active media Controller
08-23 08:44:22.361  7619  7619 D Avrcp   : Get the active Media Controller 
,08-23 08:44:22.381  7619  7619 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-23 08:44:22.381  7619  7619 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 08:44:22.381  7619  7619 D A2dpStateMachine: make
,08-23 08:44:22.381  7619  7654 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-23 08:44:22.391  7619  7619 I bluedroid: get_profile_interface a2dp
,08-23 08:44:22.391  7619  7656 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 08:44:22.391  7619  7619 E bt-btif : warning : media task started media_task_refcnt 1 
,08-23 08:44:22.391  7619  7619 D A2dpService: mStartError = false
08-23 08:44:22.391  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
,08-23 08:44:22.391  7619  7619 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 08:44:22.391  7619  7655 D A2dpStateMachine: Enter Disconnected: -2
08-23 08:44:22.391  7619  7619 D HidService: Received start request. Starting profile...
08-23 08:44:22.391  7619  7619 D HidService: start()
08-23 08:44:22.391  7619  7619 I bluedroid: get_profile_interface hidhost
08-23 08:44:22.391  7619  7619 D HidService: setHidService(): set to: null
08-23 08:44:22.391  7619  7619 D HidService: mStartError = false
08-23 08:44:22.391  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
,08-23 08:44:22.391  7619  7619 D HeadsetStateMachine: Try to query the phonestate on bind
08-23 08:44:22.391  1428  3271 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 08:44:22.391  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-23 08:44:22.391  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-23 08:44:22.391  1428  3271 I Telecom : BluetoothPhoneService: Result of Message : true
,08-23 08:44:22.391  7619  7619 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-23 08:44:22.401  7619  7619 D HealthService: Received start request. Starting profile...
08-23 08:44:22.401  7619  7619 D HealthService: start()
,08-23 08:44:22.401  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 08:44:22.401  7619  7619 I bluedroid: get_profile_interface health
,08-23 08:44:22.401  7619  7619 D HealthService: mStartError = false
08-23 08:44:22.401  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
08-23 08:44:22.401  7619  7619 D HeadsetStateMachine: Proxy object connected
,08-23 08:44:22.411  7619  7619 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 08:44:22.411  7619  7619 D PanService: Received start request. Starting profile...
08-23 08:44:22.411  7619  7619 D PanService: start()
08-23 08:44:22.411  7619  7619 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 08:44:22.411  7619  7654 D BluetoothMediaBrowser: no now playing list
08-23 08:44:22.411  7619  7619 I bluedroid: get_profile_interface pan
08-23 08:44:22.411  7619  7654 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-23 08:44:22.411  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 08:44:22.411  7619  7619 D PanService: mStartError = false
08-23 08:44:22.411  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
08-23 08:44:22.411  7619  7619 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-23 08:44:22.411  7619  7650 D HeadsetStateMachine: Disconnected process message: 11
,08-23 08:44:22.411  7619  7619 D BluetoothMapService: Received start request. Starting profile...
,08-23 08:44:22.411  7619  7619 D BluetoothMapService: start()
,08-23 08:44:22.411  7619  7619 D BluetoothMapService: mStartError = false
,08-23 08:44:22.411  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
08-23 08:44:22.411  7619  7619 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-23 08:44:22.411  7619  7619 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-23 08:44:22.421  7619  7650 D HeadsetStateMachine: Disconnected process message: 18
,08-23 08:44:22.421  7619  7619 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-23 08:44:22.421  7619  7619 D SapService: Received start request. Starting profile...
,08-23 08:44:22.421  7619  7619 D SapService: start()
08-23 08:44:22.421  7619  7619 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-23 08:44:22.421  7619  7619 I bluedroid: get_profile_interface sap
08-23 08:44:22.421  7619  7619 D SapService: mStartError = false
08-23 08:44:22.421  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
,08-23 08:44:22.421  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-23 08:44:22.421  7619  7619 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 08:44:22.421  7619  7619 D BluetoothA2dp: Proxy object connected
08-23 08:44:22.421  7619  7619 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-23 08:44:22.421  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-23 08:44:22.421  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-23 08:44:22.421  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-23 08:44:22.421  7619  7650 D HeadsetStateMachine: Disconnected process message: 10
08-23 08:44:22.421  7619  7650 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 08:44:22.421  7619  7650 D HeadsetStateMachine: Disconnected process message: 11
,08-23 08:44:22.421  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-23 08:44:22.441  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-23 08:44:22.441  7619  7619 E BluetoothAdapterService(849502105): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-23 08:44:22.451  7619  7641 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-23 08:44:22.451  7619  7641 I bluedroid: enable
,08-23 08:44:22.451  7619  7641 I bt_hci_bdroid: init
,08-23 08:44:22.451  7619  7641 I bt_vendor: bt-vendor : init
,08-23 08:44:22.451  7619  7641 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 08:44:22.451  7619  7641 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 08:44:22.451  7619  7641 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,08-23 08:44:22.451  7619  7641 D bt_userial_mct: userial_init
08-23 08:44:22.451  7619  7641 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 08:44:22.451  7619  7641 I bt_vendor: Starting hciattach daemon
08-23 08:44:22.451  7619  7641 I bt_vendor: try to set false
,08-23 08:44:22.451  7619  7641 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 08:44:22.451  7619  7641 I bt_vendor: Starting hciattach daemon
08-23 08:44:22.451  7619  7641 I bt_vendor: try to set true
,08-23 08:44:22.461  7619  7660 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-23 08:44:22.471  7664  7664 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-23 08:44:22.511  7670  7670 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-23 08:44:22.521  7671  7671 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-23 08:44:22.531  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-23 08:44:22.541  7674  7674 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-23 08:44:22.551  7675  7675 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-23 08:44:22.561  7676  7676 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-23 08:44:22.741   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:22.901  7679  7679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-23 08:44:22.911  7680  7680 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-23 08:44:22.961  7619  7641 I bt_vendor: bluetooth satus is on,
08-23 08:44:22.961  7619  7662 D bt_userial_mct: userial_open(port:0)
08-23 08:44:22.961  7619  7662 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-23 08:44:22.961  7619  7662 I bt_vendor: Done intiailizing UART,
,08-23 08:44:22.961  7619  7662 I bt_vendor: Done intiailizing UART,
08-23 08:44:22.961  7619  7662 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-23 08:44:22.961  7619  7662 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-23 08:44:22.971  7619  7682 D bt_userial_mct: Entering userial_read_thread()
,08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_BTM
,08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_PAN
,08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_SAP
08-23 08:44:22.971  7619  7660 I         : BTE_InitTraceLevels -- TRC_SDP
,08-23 08:44:22.981  7619  7660 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 08:44:22.981  7619  7660 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 08:44:22.981  7619  7660 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 08:44:22.981  7619  7660 I         : BTE_InitTraceLevels -- TRC_BTIF
08-23 08:44:22.981  7619  7660 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-23 08:44:23.051  1016  3419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 08:44:23.071  7619  7660 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-23 08:44:23.071  7619  7660 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4121ed1 
,08-23 08:44:23.071  7619  7660 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4121ed1 
,08-23 08:44:23.091  7619  7644 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-23 08:44:23.091  7619  7644 E bt-btif : Calling BTA_HhEnable
,08-23 08:44:23.091  7619  7644 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-23 08:44:23.091  7619  7644 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-23 08:44:23.091  7619  7644 E BluetoothServiceJni: populateRssiValuesNative
08-23 08:44:23.091  7619  7644 I bluedroid: getModelRssiValues
,08-23 08:44:23.091  7619  7644 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-23 08:44:23.091  7619  7644 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-23 08:44:23.101  7619  7644 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-23 08:44:23.101  1016  1016 D SettingsProvider: name = bluetooth_name,
,08-23 08:44:23.101  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:23.111  7619  7644 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-23 08:44:23.111  7619  7644 D BluetoothAdapterProperties: Scan Mode:20
08-23 08:44:23.111  7619  7644 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 08:44:23.111  7619  7644 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-23 08:44:23.111  7619  7644 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-23 08:44:23.111  7619  7644 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-23 08:44:23.111  7619  7644 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-23 08:44:23.111  7619  7644 E bt-btif : btif_sock_init: !vhci_init
08-23 08:44:23.111  7619  7644 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-23 08:44:23.111  7619  7644 D IOP_DB_BT: db_open: db_open : handle 3027611664l, read 13894 bytes onto local cache
08-23 08:44:23.111  7619  7644 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-23 08:44:23.111  7619  7644 D IOP_DB_BT: db_query: result 1
08-23 08:44:23.111  7619  7644 I         : iop_db_open: iop_db_open status 0
,08-23 08:44:23.111  7619  7644 D bte_conf: Device ID record 1 : primary
08-23 08:44:23.111  7619  7644 D bte_conf:   vendorId            = 0075
08-23 08:44:23.111  7619  7644 D bte_conf:   vendorIdSource      = 0001
08-23 08:44:23.111  7619  7644 D bte_conf:   product             = 0100
,08-23 08:44:23.111  7619  7644 D bte_conf:   version             = 0200
08-23 08:44:23.111  7619  7644 D bte_conf:   clientExecutableURL = 
08-23 08:44:23.111  7619  7644 D bte_conf:   serviceDescription  = 
08-23 08:44:23.111  7619  7644 D bte_conf:   documentationURL    = 
,08-23 08:44:23.111  7619  7644 D bte_conf: bte_load_did_conf no section named DID2.
,08-23 08:44:23.111  7619  7644 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 08:44:23.111  7619  7641 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-23 08:44:23.111  7619  7641 D BluetoothAdapterProperties: ScanMode =  20
,08-23 08:44:23.121  7619  7682 E bt_mct  : hci lib postload completed
,08-23 08:44:23.121  7619  7641 D BluetoothAdapterProperties: State =  11
,08-23 08:44:23.121  1016  1328 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-23 08:44:23.121  7619  7641 D BluetoothAdapterProperties: Setting state to 12
,08-23 08:44:23.121  7619  7641 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-23 08:44:23.131  7619  7644 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-23 08:44:23.131  7619  7644 D BluetoothAdapterProperties: Scan Mode:21
08-23 08:44:23.131  7619  7644 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 08:44:23.131  1016  3839 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-23 08:44:23.131  1016  3839 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:23.131  1016  3839 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:23.131  1016  3839 D SettingsProvider: selectionArgs: false
08-23 08:44:23.131  1016  3839 D SettingsProvider: selectionArgs: 1002
08-23 08:44:23.131  1016  3839 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:23.131  1016  3839 D SettingsProvider: ret = -1
,08-23 08:44:23.131  7619  7641 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-23 08:44:23.131  7619  7641 D BluetoothAdapterService: updateAdapterState state is 12
,08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:23.131  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:23.131  1016  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:23.131  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.131  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:23.131  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:23.131  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.141  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:23.141  7619  7641 D BluetoothAdapterService: Autoconnection is available 
,08-23 08:44:23.141  7619  7641 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-23 08:44:23.141  7619  7641 D BluetoothAdapterService: starting service from this receiver
08-23 08:44:23.141  1016  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:23.151  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.151  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:23.151  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.151  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.151  7619  7641 I BluetoothAdapterState: Entering On State from state = 11
,08-23 08:44:23.151  1428  7001 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:23.161  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-23 08:44:23.161  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:23.161  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:23.161  7619  7619 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-23 08:44:23.171  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.171  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.171  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.171  1428  7001 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:23.171  1428  1455 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.171  1428  1455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 08:44:23.171  1016  1045 D BluetoothPan: Binding service...
,08-23 08:44:23.171  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:23.171  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:44:23.171  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-23 08:44:23.171  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3da51be9 added. We now have 8 listener(s)
08-23 08:44:23.171  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:23.171  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-23 08:44:23.171  6821  6832 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.171  6821  6832 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:23.181  1940  2192 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.181  1940  2192 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:23.181  1428  1462 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:23.181  7619  7619 I BluetoothPbapService: Handler(): got msg=1
,08-23 08:44:23.181  1016  1329 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-23 08:44:23.181  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:23.181  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:23.181  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:23.181  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.181  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.181  1016  1231 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-23 08:44:23.181  1428  1462 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:23.181  1016  1231 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 08:44:23.181  1016  1231 D SecContentProvider2: mCursor = null
,08-23 08:44:23.181  1016  1231 D WifiService: setWifiEnabled: false pid=6821, uid=10171
,08-23 08:44:23.181  1016  1231 D SettingsProvider: name = wifi_on
,08-23 08:44:23.191  7529  7545 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.191  7529  7545 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:23.191  7619  7687 V BluetoothPbapService: PBAP Service initSocket try: 0
08-23 08:44:23.191  1444  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 08:44:23.191  1444  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:23.191  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-23 08:44:23.191  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-23 08:44:23.191  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-23 08:44:23.191  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:23.191  3320  3334 D Bluetoothsap: onBluetoothStateChange: up=true
08-23 08:44:23.191  3320  3334 D Bluetoothsap: Binding service...
,08-23 08:44:23.191  3320  3334 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-23 08:44:23.191  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-23 08:44:23.191  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.191  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.191  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.191  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.191  3320  3334 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-23 08:44:23.201  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:23.201  3320  7108 D BluetoothPan: Binding service...
,08-23 08:44:23.201  7619  7687 D BluetoothSocket: bindListen(): myUserId = 0
08-23 08:44:23.201  7619  7687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:44:23.201  1016  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-23 08:44:23.201  1016  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-23 08:44:23.201  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 08:44:23.201  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-23 08:44:23.201  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.201  1016  1478 D SecContentProvider2: mCursor = null
08-23 08:44:23.201  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.201  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.201  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.201  3320  3320 D Bluetoothsap: BluetoothSAP Proxy object connected
08-23 08:44:23.201  1016  1478 D WifiService: setWifiEnabled: true pid=6821, uid=10171
08-23 08:44:23.201  3320  3320 D SapProfile: Bluetooth service connected
08-23 08:44:23.201  1016  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 08:44:23.201  3320  3320 D Bluetoothsap: getConnectedDevices()
,08-23 08:44:23.201  1016  1478 W WifiService: Failed getting userId using ActivityManagerNative
08-23 08:44:23.201  1016  1478 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6821, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-23 08:44:23.201  1016  1478 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-23 08:44:23.201  1016  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-23 08:44:23.201  1016  1478 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-23 08:44:23.201  1016  1478 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-23 08:44:23.201  1016  1478 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-23 08:44:23.201  1016  1478 D SettingsProvider: name = wifi_on
08-23 08:44:23.201  1016  2020 V SAMP_SPCM_test: CSC File load.. 
,08-23 08:44:23.201  7619  7687 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-23 08:44:23.201  7619  7687 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 08:44:23.201  7619  7687 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 08:44:23.201  7619  7687 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ee8d2b
,08-23 08:44:23.201  7619  7687 D BluetoothSocket: channel: 19
08-23 08:44:23.201  7619  7687 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-23 08:44:23.211  1437  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-23 08:44:23.211  1437  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 08:44:23.211  3320  3334 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 08:44:23.211  1016  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-23 08:44:23.211  3320  3320 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 08:44:23.221  3320  3320 D PanProfile: Bluetooth service connected
,08-23 08:44:23.221  3320  3334 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-23 08:44:23.221  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 08:44:23.261  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation,
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi,
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-23 08:44:23.271  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-23 08:44:23.271  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location,
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 08:44:23.271  1016  2020 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-23 08:44:23.281  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.281  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.281  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.281  1016  2020 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-23 08:44:23.281  1016  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:23.281  1016  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:23.281  1016  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:23.281  1016  2020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:23.281  3320  7108 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:23.281  3320  3320 D BluetoothA2dp: Proxy object connected
,08-23 08:44:23.281  3320  3320 D A2dpProfile: Bluetooth service connected
,08-23 08:44:23.291  7690  7690 E Zygote  : MountEmulatedStorage()
,08-23 08:44:23.291  7690  7690 E Zygote  : v2
08-23 08:44:23.291  7690  7690 I libpersona: KNOX_SDCARD checking this for 1000
08-23 08:44:23.291  7690  7690 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:23.301  1016  2020 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 08:44:23.301  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:23.301  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:23.301  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.301  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.301  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-23 08:44:23.301  7690  7690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 08:44:23.301  3320  3320 D HeadsetProfile: Bluetooth service connected
08-23 08:44:23.301  3320  7108 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:23.301  3320  3331 D BluetoothMap: onBluetoothStateChange: up=true
08-23 08:44:23.301  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-23 08:44:23.301  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.301  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.301  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.301  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.301  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.301  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-23 08:44:23.301  3320  3334 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.301  3320  3334 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:23.301  3320  3320 D BluetoothMap: Proxy object connected
08-23 08:44:23.301  3320  3320 D MapProfile: Bluetooth service connected
08-23 08:44:23.301  3320  3320 D BluetoothMap: getConnectedDevices()
,08-23 08:44:23.301  7690  7690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:23.311  1428  1455 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:23.311  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:23.311  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:23.311  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.311  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.311  7690  7690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 08:44:23.311  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-23 08:44:23.311  1428  1455 E BluetoothHeadset: BluetoothHeadset service is binded
08-23 08:44:23.311  3320  3331 D BluetoothPbap: onBluetoothStateChange: up=true
,08-23 08:44:23.331  7690  7690 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:23.331  7690  7690 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:23.461  1016  1045 I art     : Explicit concurrent mark sweep GC freed 27163(1537KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.497ms total 148.344ms
08-23 08:44:23.461  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-23 08:44:23.461  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.461  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.461  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.461  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.461  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 08:44:23.461  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:23.471  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-23 08:44:23.471  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.471  1016  1016 D BluetoothA2dp: Proxy object connected
,08-23 08:44:23.471  3320  3320 D BluetoothPbap: Proxy object connected
,08-23 08:44:23.471  3320  3320 D PbapServerProfile: Bluetooth service connected
,08-23 08:44:23.471  1444  3319 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-23 08:44:23.471  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-23 08:44:23.471  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-23 08:44:23.471  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.471  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.471  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.481  1444  3319 E BluetoothHeadset: BluetoothHeadset service is binded
,08-23 08:44:23.481  7619  7627 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 08:44:23.481  7619  7628 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.481  7619  7628 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:23.481  1177  2061 D BluetoothAdapter: onBluetoothStateChange: up=true
08-23 08:44:23.481  1177  2061 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-23 08:44:23.481  3320  3331 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 08:44:23.481  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-23 08:44:23.481  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.481  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.481  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.481  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.481  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt,
08-23 08:44:23.481  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-23 08:44:23.481  7690  7690 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 08:44:23.481  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:23.481  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-23 08:44:23.481  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-23 08:44:23.491  3320  3320 D BluetoothInputDevice: Proxy object connected
08-23 08:44:23.491  3320  3320 D HidProfile: Bluetooth service connected,
,08-23 08:44:23.491  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@62cd096, true
08-23 08:44:23.491  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-23 08:44:23.491  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-23 08:44:23.491  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:23.491  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-23 08:44:23.491  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:23.491  1428  1428 D BluetoothHeadset: registerMessageListener
,08-23 08:44:23.491  1827  1827 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-23 08:44:23.491  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:23.501  1177  1702 D BluetoothTile:  handleUpdatestate:false name:null
,08-23 08:44:23.501  1016  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:23.501  1016  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.501  7619  7627 D HeadsetService: registerMessageListener
,08-23 08:44:23.511  7619  7627 D HeadsetService: registerMessageListener
08-23 08:44:23.511  3320  3320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:44:23.511  7619  7650 D HeadsetStateMachine: Disconnected process message: 70
08-23 08:44:23.511  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:23.511  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:23.511  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:23.511  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:23.511  7619  7650 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3fd76588
08-23 08:44:23.511  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-23 08:44:23.511  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-23 08:44:23.521  3320  3320 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-23 08:44:23.521  1016  1231 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-23 08:44:23.521  3320  3320 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-23 08:44:23.521  3320  3320 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-23 08:44:23.521  3320  3320 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-23 08:44:23.521  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-23 08:44:23.521  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-23 08:44:23.521  7619  7714 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-23 08:44:23.521  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-23 08:44:23.521  1016  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-23 08:44:23.521  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-23 08:44:23.531  7619  7650 D HeadsetStateMachine: Disconnected process message: 9
,08-23 08:44:23.531  7619  7650 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-23 08:44:23.531  7619  7714 D BluetoothSocket: bindListen(): myUserId = 0
08-23 08:44:23.531  7619  7714 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:44:23.541  7619  7714 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-23 08:44:23.541  7619  7714 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 08:44:23.541  7619  7714 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 08:44:23.541  7619  7714 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ed5db21
,08-23 08:44:23.541  3320  3320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 08:44:23.541  7619  7714 D BluetoothSocket: channel: 5
08-23 08:44:23.541  1016  1328 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-23 08:44:23.541  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.541   282   699 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-23 08:44:23.541   282   699 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-23 08:44:23.541   282   699 V voice   : voice_set_parameters: exit with code(-2)
08-23 08:44:23.541   282   699 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-23 08:44:23.541   282   699 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-23 08:44:23.541   282   699 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-23 08:44:23.541   282   699 V audio_hw_primary: adev_set_parameters: exit
08-23 08:44:23.541  7619  7650 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-23 08:44:23.541  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:23.541  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.541  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-23 08:44:23.551  1016  1043 D Tethering: interfaceAdded wlan0
,08-23 08:44:23.551  3320  3320 D DockEventReceiver: finishStartingService: stopping service
,08-23 08:44:23.551  1016  1128 E Tethering: No numeric data
,08-23 08:44:23.551  1016  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 08:44:23.551  1016  1128 D Tethering: clearTetheredNotification()
,08-23 08:44:23.551  3320  3320 D BluetoothNotiBroadcastReceiver: onReceive
,08-23 08:44:23.551  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
08-23 08:44:23.551  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.551  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:23.551  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:23.561  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 08:44:23.561  1177  1177 D HotspotTile: updateTetherState():false, false
,08-23 08:44:23.561  1016  1122 V NetworkStats: performPollLocked() took 5ms
,08-23 08:44:23.561  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:23.561  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:23.561  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-23 08:44:23.561  1016  1128 D Tethering: InitialState.processMessage what=4
,08-23 08:44:23.561  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.561  1016  1128 E Tethering: No numeric data
,08-23 08:44:23.561  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:44:23.561  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
08-23 08:44:23.561  1016  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:44:23.561  1016  1128 D Tethering: clearTetheredNotification()
,08-23 08:44:23.561  1016  2020 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-23 08:44:23.561  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 08:44:23.561  1177  1177 D HotspotTile: updateTetherState():false, false
,08-23 08:44:23.561  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
08-23 08:44:23.561  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.571  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 08:44:23.571  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-23 08:44:23.571  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:23.571  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 08:44:23.571  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 08:44:23.571  1016  1043 D Tethering: interfaceAdded p2p0
,08-23 08:44:23.571  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.571  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-23 08:44:23.571  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.571   277  1005 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-23 08:44:23.571  1016  1122 V NetworkStats: performPollLocked() took 7ms
08-23 08:44:23.571  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.571   277  1005 D SoftapController: Softap fwReload - Ok
,08-23 08:44:23.571   277  1005 D CommandListener: Setting iface cfg
08-23 08:44:23.571   277  1005 D CommandListener: Trying to bring down wlan0
,08-23 08:44:23.571   277  1005 D CommandListener: Clearing all IP addresses on wlan0
,08-23 08:44:23.581  1016  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-23 08:44:23.581  1016  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-23 08:44:23.591  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.591  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:23.591  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:23.591  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-23 08:44:23.591  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:23.591  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:23.591  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:23.591  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:23.591  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:23.591  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-23 08:44:23.591  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-23 08:44:23.601  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:23.601  1177  1177 D HotspotTile: onReceive : 2, 0
,08-23 08:44:23.601  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:23.601  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:23.601  7619  7619 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
08-23 08:44:23.601  7619  7619 D BtConfig.SecureMode: isSecureModeOn:false
,08-23 08:44:23.601  1016  1231 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-23 08:44:23.601  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.611  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.611  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.611  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-23 08:44:23.621  7718  7718 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-23 08:44:23.621  7718  7718 I wpa_supplicant: Successfully initialized wpa_supplicant
08-23 08:44:23.621  7718  7718 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-23 08:44:23.631  1940  1940 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-23 08:44:23.631  1016  1016 I ActivityManager: Killing 7157:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-23 08:44:23.631  1016  3840 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:23.631  1016  3840 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-23 08:44:23.631  1016  3840 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.631  1016  3840 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:23.631  1016  3840 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:23.641  7718  7718 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-23 08:44:23.641   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7718
08-23 08:44:23.641   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-23 08:44:23.641  7718  7718 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-23 08:44:23.641  7718  7718 I wpa_supplicant: ssSupport state is = 1
08-23 08:44:23.641  7718  7718 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-23 08:44:23.641  7718  7718 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-23 08:44:23.641   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7718
08-23 08:44:23.641   364   364 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-23 08:44:23.641  1940  7724 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-23 08:44:23.641  1016  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-23 08:44:23.641  1940  1940 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-23 08:44:23.651  1016  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:23.651  1016  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:23.651  1016  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:23.651  1016  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:23.661  1016  1377 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:23.661  1016  1377 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:23.661  1016  1377 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.661  1016  1377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:23.661  1016  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:23.661  2201  2201 I Hs20UtilService: Starting #19
,08-23 08:44:23.661  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:23.661  7619  7727 D BluetoothSocket: bindListen(): myUserId = 0
08-23 08:44:23.671  7619  7727 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:44:23.671  7619  7727 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-23 08:44:23.671  7619  7727 D BluetoothSocket: bindListen(), new LocalSocket 
08-23 08:44:23.671  7619  7727 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-23 08:44:23.671  7619  7727 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b14085d
,08-23 08:44:23.671  7619  7727 D BluetoothSocket: channel: 12
08-23 08:44:23.671  7619  7727 I BtOppRfcommListener: Accept thread started.
,08-23 08:44:23.671  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-23 08:44:23.671  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 08:44:23.671  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
08-23 08:44:23.671  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-23 08:44:23.681  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 08:44:23.681  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:23.681  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:23.681  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:23.691  1940  7724 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-23 08:44:23.741   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:23.791   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-23 08:44:23.791  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-23 08:44:23.841  7718  7718 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 08:44:23.841  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 08:44:23.851  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-23 08:44:23.851   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7718
08-23 08:44:23.851   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-23 08:44:23.851  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-23 08:44:23.851  7718  7718 I wpa_supplicant: ssSupport state is = 1
08-23 08:44:23.851  7718  7718 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:23.851  7718  7718 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:23.851  7718  7718 E wpa_supplicant: SIM READ ERROR,
08-23 08:44:23.851  7718  7718 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:23.851  7718  7718 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:23.851  7718  7718 E wpa_supplicant: SIM READ ERROR
08-23 08:44:23.851  7718  7718 I wpa_supplicant: Blacklist: Clear (all) ,
08-23 08:44:23.851  7718  7718 I wpa_supplicant: wpa_default_ap_write_once
08-23 08:44:23.851  7718  7718 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 08:44:23.851  7718  7718 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:23.851  7718  7718 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-23 08:44:23.851  7718  7718 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-23 08:44:23.851  7718  7718 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-23 08:44:23.851  7718  7718 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-23 08:44:23.851  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-23 08:44:23.851  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:23.851  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:23.951  7718  7718 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-23 08:44:24.021  1016  3385 D SSRM:n  : SIOP:: AP = 300,
,08-23 08:44:24.031   294   294 E SMD     : DCD OFF
,08-23 08:44:24.111  7718  7718 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-23 08:44:24.111  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 08:44:24.121  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-23 08:44:24.121   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7718
08-23 08:44:24.121   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-23 08:44:24.121  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-23 08:44:24.121  7718  7718 I wpa_supplicant: ssSupport state is = 1
,08-23 08:44:24.131  7718  7718 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-23 08:44:24.131  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-23 08:44:24.141  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-23 08:44:24.141   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7718
08-23 08:44:24.141   364   364 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-23 08:44:24.141  7718  7718 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-23 08:44:24.141  7718  7718 I wpa_supplicant: ssSupport state is = 1,
08-23 08:44:24.141  7718  7718 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-23 08:44:24.141  7718  7718 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:24.141  7718  7718 E wpa_supplicant: SIM READ ERROR
08-23 08:44:24.141  7718  7718 I wpa_supplicant: wpa_default_ap_write_once
08-23 08:44:24.141  7718  7718 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-23 08:44:24.141  7718  7718 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 08:44:24.151  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-23 08:44:24.151  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-23 08:44:24.151  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-23 08:44:24.151  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-23 08:44:24.151  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-23 08:44:24.151  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-23 08:44:24.251  7718  7718 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-23 08:44:24.251  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-23 08:44:24.291  7718  7718 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-23 08:44:24.291  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-23 08:44:24.291  7718  7718 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 08:44:24.301  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-23 08:44:24.301  1016  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-23 08:44:24.301  7718  7718 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-23 08:44:24.311  7718  7718 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-23 08:44:24.311  7718  7718 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-23 08:44:24.311  7718  7718 E wpa_supplicant: SIM READ ERROR,
08-23 08:44:24.311  7718  7718 I wpa_supplicant: Blacklist: Clear (all) 
,08-23 08:44:24.331  7718  7718 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-23 08:44:24.341  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-23 08:44:24.341  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:24.341  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-23 08:44:24.341  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:24.341  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:24.341  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:24.341  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-23 08:44:24.341  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-23 08:44:24.341  1177  1702 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-23 08:44:24.351  7718  7718 I wpa_supplicant: Skip scan - bUseNetwork false
,08-23 08:44:24.351  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-23 08:44:24.351  1177  1177 D HotspotTile: onReceive : 3, 0
,08-23 08:44:24.351  1016  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-23 08:44:24.361  3320  3320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:24.361  6821  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:24.361  1016  1125 E WifiConfigStore: Not a HS20
,08-23 08:44:24.361  1016  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 08:44:24.361  6821  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:24.361  1016  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:24.361  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:24.371  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:24.371  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:24.371  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:24.371  1016  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-23 08:44:24.371  2201  2201 I Hs20UtilService: Starting #20
,08-23 08:44:24.371  2201  2217 I Hs20UtilService: Message received 5011
,08-23 08:44:24.371  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 08:44:24.381  6616  6616 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-23 08:44:24.381  6616  6616 D SecurityLogAgent: StateMachine : Current State = 1
08-23 08:44:24.381  1016  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-23 08:44:24.381  6616  6616 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-23 08:44:24.381  7718  7718 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-23 08:44:24.381  7718  7718 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-23 08:44:24.381  7718  7718 I wpa_supplicant: reset timer : RESET_TIMER 0
08-23 08:44:24.381  7718  7718 I wpa_supplicant: P2P: Current p2p state = IDLE
08-23 08:44:24.381  7718  7718 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-23 08:44:24.381  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-23 08:44:24.381  7718  7718 I wpa_supplicant: First Scan Start
,08-23 08:44:24.381  7718  7718 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 08:44:24.381  1016  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-23 08:44:24.381  1016  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 08:44:24.381  1016  1125 I WifiNative-HAL: startHal
08-23 08:44:24.381  1016  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d67488c
08-23 08:44:24.381  1016  1125 I WifiNative-HAL: Could not start hal
,08-23 08:44:24.381  7056  7056 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:44:24.391  1016  1125 E WifiNative-wlan0: do suspend true
,08-23 08:44:24.391  1016  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-23 08:44:24.391  1016  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-23 08:44:24.391   277  1005 D CommandListener: Setting iface cfg,
08-23 08:44:24.391   277  1005 D CommandListener: Trying to bring up p2p0
,08-23 08:44:24.391  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 08:44:24.391  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-23 08:44:24.391  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:24.391  1016  1124 D WifiP2pService: P2pEnablingState
,08-23 08:44:24.391  1016  1148 I WifiNative-HAL: startHal
08-23 08:44:24.391  1016  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-23 08:44:24.391  1016  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9eb329bc
,08-23 08:44:24.391  1016  1124 D WifiP2pService: P2p socket connection successful
08-23 08:44:24.391  1016  1148 I WifiNative-HAL: Could not start hal
08-23 08:44:24.391  1016  1124 D WifiP2pService: P2pEnabledState
,08-23 08:44:24.391  1016  1148 E WifiScanningService: could not start HAL,
08-23 08:44:24.391  1016  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-23 08:44:24.391  1016  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:24.391  1016  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 08:44:24.391  1016  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
08-23 08:44:24.391  1016  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 08:44:24.391  1016  1125 E WifiNative-wlan0: invaild command id : 215
,08-23 08:44:24.391  1016  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
,08-23 08:44:24.391  1016  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-23 08:44:24.401  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-23 08:44:24.391  1016  1125 E WifiNative-wlan0: invaild command id : 215
08-23 08:44:24.401  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-23 08:44:24.391  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:24.401  1016  1046 D WifiDisplayController: disconnect
08-23 08:44:24.391  7718  7718 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-23 08:44:24.401  1016  1046 D WifiDisplayController: updateConnection
,08-23 08:44:24.401  7718  7718 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-23 08:44:24.401  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-23 08:44:24.401  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-23 08:44:24.401  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 08:44:24.401  7718  7718 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-23 08:44:24.401  1016  1125 E WifiStateMachine: Failed to set frequency band 0
08-23 08:44:24.401  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:24.401  1016  1125 D SecContentProvider2: mCursor = null
08-23 08:44:24.401  1016  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-23 08:44:24.401  1016  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-23 08:44:24.401  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:44:24.401  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-23 08:44:24.401  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-23 08:44:24.401  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-23 08:44:24.401  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-23 08:44:24.401  1016  1510 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 08:44:24.411  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-23 08:44:24.411  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-23 08:44:24.411  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 08:44:24.411  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 08:44:24.411  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:24.411  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:24.411  1016  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-23 08:44:24.411  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 08:44:24.411  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:24.411  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 08:44:24.411  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  secondary type: null
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  wps: 0
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  grpcapab: 0
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  devcapab: 0
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  status: 3
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  wfdInfo: null
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-23 08:44:24.411  1016  1046 D WifiDisplayController:  SConnectInfo : null
,08-23 08:44:24.411  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:24.421  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 08:44:24.421  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-23 08:44:24.421  7415  7415 D FileShare-Client: Outbound.stopDelayTimer - 
,08-23 08:44:24.431  7430  7430 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-23 08:44:24.431  1016  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-23 08:44:24.431  1016  1124 D WifiP2pService: InactiveState
,08-23 08:44:24.431  1016  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-23 08:44:24.431  1016  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 08:44:24.431  7718  7718 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-23 08:44:24.441  1016  1124 D WifiP2pService: InactiveState{ what=143376 },
08-23 08:44:24.441  1016  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-23 08:44:24.561  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-23 08:44:24.561  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-23 08:44:24.561  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-23 08:44:24.741   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:25.231  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:25.231  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:25.231  6821  6874 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-23 08:44:25.241  6821  6874 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 08:44:25.241  6821  6874 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d2d6109 Bundle[{}]
,08-23 08:44:25.241  6821  6874 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 08:44:25.241  6821  6874 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 08:44:25.241  6821  6874 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 08:44:25.241  6821  6874 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 08:44:25.241  6821  6874 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 08:44:25.251  6821  6874 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 08:44:25.251  6821  6874 I System.out: Running OutgoingSocketThread
,08-23 08:44:25.251  6821  7735 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1350)
,08-23 08:44:25.261  6821  7735 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47161
,08-23 08:44:25.261  6821  7735 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 08:44:25.571  7718  7718 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
08-23 08:44:25.571  7718  7718 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-23 08:44:25.571  7718  7718 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-23 08:44:25.571  7718  7718 I wpa_supplicant: Trying to associate with  'G700'
08-23 08:44:25.571  7718  7718 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-23 08:44:25.571  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-23 08:44:25.571  1016  7732 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-23 08:44:25.591  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:25.591  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:25.691  7718  7718 E wpa_supplicant: Cmd 35605 not handled
,08-23 08:44:25.691  7718  7718 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 08:44:25.691  7718  7718 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-23 08:44:25.691  7718  7718 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-23 08:44:25.691  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-23 08:44:25.691  7718  7718 I wpa_supplicant: Associated with F4.99.3E
08-23 08:44:25.691  7718  7718 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-23 08:44:25.691  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-23 08:44:25.691  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-23 08:44:25.691  7718  7718 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-23 08:44:25.691  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-23 08:44:25.691  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:25.691  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 08:44:25.691  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-23 08:44:25.691  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:25.691  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-23 08:44:25.691  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-23 08:44:25.701  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-23 08:44:25.701  7718  7718 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-23 08:44:25.701  7718  7718 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-23 08:44:25.701  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-23 08:44:25.701  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-23 08:44:25.701  7718  7718 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-23 08:44:25.701  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-23 08:44:25.701  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-23 08:44:25.701  7718  7718 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:44:25.701  7718  7718 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-23 08:44:25.701  7718  7718 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-23 08:44:25.701  7718  7718 I wpa_supplicant: Blacklist: Clear (temp) 
08-23 08:44:25.701  7718  7718 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-23 08:44:25.701  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-23 08:44:25.701  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-23 08:44:25.701  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:25.701  1016  1125 D SecContentProvider2: mCursor = null
08-23 08:44:25.711  1016  1128 E Tethering: No numeric data
,08-23 08:44:25.711  1016  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 08:44:25.711  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-23 08:44:25.711  1016  1128 D Tethering: clearTetheredNotification()
,08-23 08:44:25.711  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:25.711  1016  1125 D SecContentProvider2: mCursor = null
08-23 08:44:25.711  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
08-23 08:44:25.711  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:25.711  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:25.711  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-23 08:44:25.711  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-23 08:44:25.711  1177  1177 D HotspotTile: updateTetherState():false, false
,08-23 08:44:25.721  1016  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-23 08:44:25.721  1016  1122 V NetworkStats: performPollLocked() took 8ms
,08-23 08:44:25.721  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:25.721  1016  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-23 08:44:25.731  1016  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-23 08:44:25.731  1016  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-23 08:44:25.731  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:25.731  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 08:44:25.731  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:25.731  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:25.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:25.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:25.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:25.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:25.731  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:25.731  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:25.741  1016  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 08:44:25.741  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:25.741  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 08:44:25.741   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-23 08:44:25.741  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:25.741  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:25.741  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:25.741  2201  2201 I Hs20UtilService: Starting #21
,08-23 08:44:25.751  2201  2217 I Hs20UtilService: Message received 5007
,08-23 08:44:25.751  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 08:44:25.751  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-23 08:44:25.751  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-23 08:44:25.751  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-23 08:44:25.751  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-23 08:44:25.751  3320  3320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-23 08:44:25.751  3320  3841 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-23 08:44:25.761  1016  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 08:44:25.771   277  1005 D CommandListener: Setting iface cfg,
,08-23 08:44:25.771  1016  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-23 08:44:25.781  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-23 08:44:25.781  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:25.791  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:25.791  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-23 08:44:25.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:25.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:25.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:25.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:25.801  1016  1125 E WifiNative-wlan0: do suspend false
,08-23 08:44:25.801  1016  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-23 08:44:25.801  1016  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-23 08:44:25.801  1016  1125 D SecContentProvider2: mCursor = null
,08-23 08:44:25.811  1016  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 08:44:26.021  7738  7738 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 08:44:26.021  7738  7738 I dhcpcd  : version 5.5.6 starting
,08-23 08:44:26.031  7738  7738 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-23 08:44:26.081  7738  7738 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-23 08:44:26.081  7738  7738 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-23 08:44:26.081  7738  7738 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-23 08:44:26.081  7738  7738 I dhcpcd  : bssid match
08-23 08:44:26.081  7738  7738 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-23 08:44:26.151  7738  7738 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-23 08:44:26.231  7738  7738 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-23 08:44:26.251  6821  6874 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1351)
08-23 08:44:26.251  6821  6874 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1351)
,08-23 08:44:26.261  6821  6874 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1356)
,08-23 08:44:26.261  6821  6874 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-23 08:44:26.261  6821  6874 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1357)
,08-23 08:44:26.261  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.261  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d04106e added. We now have 2 listener(s)
,08-23 08:44:26.271  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 08:44:26.271  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:26.271  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.271  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.271  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ad0b30f added. We now have 9 listener(s)
08-23 08:44:26.271  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.271  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 08:44:26.271  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:26.291  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
,08-23 08:44:26.301  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:26.301  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 08:44:26.301  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.301  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1caa8da5 added. We now have 3 listener(s)
,08-23 08:44:26.301  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:26.301  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e64c57a added. We now have 10 listener(s)
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.311  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:26.311  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:26.311  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.311  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d04106e removed from the list
08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ad0b30f removed from the list
08-23 08:44:26.311  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.311  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.311  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ad0b30f not in the list
,08-23 08:44:26.311  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e64c57a removed from the list
,08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 08:44:26.311  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:26.311  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1caa8da5 removed from the list
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6f712b added. We now have 2 listener(s),
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.311  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15307988 added. We now have 9 listener(s)
08-23 08:44:26.311  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.321  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 08:44:26.331  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:26.341  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:26.341  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:44:26.341  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:44:26.341  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.341  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25e9bf46 added. We now have 3 listener(s),
08-23 08:44:26.341  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:26.341  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:26.341  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 08:44:26.341  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:26.341  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.341  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.341  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f1f507 added. We now have 10 listener(s)
08-23 08:44:26.341  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.341  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:26.341  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:44:26.341  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 08:44:26.341  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:44:26.341  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 08:44:26.351  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 08:44:26.361  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 08:44:26.361  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 08:44:26.361  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 08:44:26.361  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 08:44:26.361  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 08:44:26.371  7619  7713 D BtGatt.GattService: registerClient() - UUID=bc51287c-2853-4c68-b270-00387d97ee15
,08-23 08:44:26.411  7619  7644 D BtGatt.GattService: onClientRegistered() - UUID=bc51287c-2853-4c68-b270-00387d97ee15, clientIf=6,
08-23 08:44:26.411  6821  7109 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-23 08:44:26.411  7619  7645 D BtGatt.GattService: start scan with filters
08-23 08:44:26.411  7619  7649 D BtGatt.ScanManager: handling starting scan
,08-23 08:44:26.411  7619  7649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a25f99
08-23 08:44:26.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-23 08:44:26.421  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 08:44:26.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 08:44:26.421  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 08:44:26.421  7619  7644 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 08:44:26.421  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.421  7619  7649 D BtGatt.ScanManager: allow scan with filters
08-23 08:44:26.421  7619  7649 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-23 08:44:26.421  7619  7649 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-23 08:44:26.421  7619  7644 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-23 08:44:26.421  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:26.421  7619  7649 D BtGatt.ScanManager: Starting BLE batch scan
08-23 08:44:26.421  7619  7649 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-23 08:44:26.421  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 08:44:26.421  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:26.421  7619  7644 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-23 08:44:26.421  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.421  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 08:44:26.431  7619  7644 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-23 08:44:26.431  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.431  6821  6874 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 08:44:26.431  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:26.431  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 08:44:26.431  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.431  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 08:44:26.431  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 08:44:26.431  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:44:26.431  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 08:44:26.431  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 08:44:26.431  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 08:44:26.431  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 08:44:26.431  7619  7712 D BtGatt.GattService: stopScan() - queue size =1
,08-23 08:44:26.441  7619  7649 D BtGatt.ScanManager: filter size is 1
08-23 08:44:26.441  7619  7649 D BtGatt.ScanManager: delete FilterIndex - 3
08-23 08:44:26.441  7619  7628 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 08:44:26.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 08:44:26.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 08:44:26.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 08:44:26.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 08:44:26.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 08:44:26.441  7619  7644 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 08:44:26.441  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.441  7619  7649 D BtGatt.ScanManager: stopping BLe Batch
,08-23 08:44:26.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:26.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 08:44:26.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 08:44:26.441  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 08:44:26.441  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:26.441  7619  7644 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-23 08:44:26.441  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.441  7619  7649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-23 08:44:26.441  7619  7644 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 08:44:26.441  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.451  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 08:44:26.451  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:26.451  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:26.461  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-23 08:44:26.461  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:26.461  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.461  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.461  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.461  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6f712b removed from the list
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.461  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15307988 removed from the list
08-23 08:44:26.461  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop,
08-23 08:44:26.461  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.461  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.461  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.461  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15307988 not in the list
08-23 08:44:26.461  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.461  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.461  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f1f507 removed from the list
08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.461  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.461  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:26.461  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.461  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25e9bf46 removed from the list
08-23 08:44:26.461  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.461  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@212edaa3 added. We now have 2 listener(s)
,08-23 08:44:26.471  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 08:44:26.471  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:26.471  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.471  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.471  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a2f1a0 added. We now have 9 listener(s)
,08-23 08:44:26.471  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.471  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 08:44:26.471  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:26.481  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:26.481  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:26.481  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:44:26.481  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.481  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74b711e added. We now have 3 listener(s)
,08-23 08:44:26.481  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:26.481  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:26.481  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 08:44:26.481  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:26.481  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.481  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.481  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca7dff added. We now have 10 listener(s)
08-23 08:44:26.481  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.481  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:26.481  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:26.481  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:44:26.481  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:44:26.481  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:44:26.481  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 08:44:26.491  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 08:44:26.491  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 08:44:26.491  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 08:44:26.491  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 08:44:26.491  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 08:44:26.491  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 08:44:26.501  7619  7627 D BtGatt.GattService: registerClient() - UUID=b733906e-ff4d-4f50-bcca-11d01ef62069
,08-23 08:44:26.541  7619  7644 D BtGatt.GattService: onClientRegistered() - UUID=b733906e-ff4d-4f50-bcca-11d01ef62069, clientIf=6
,08-23 08:44:26.541  6821  6832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 08:44:26.541  7619  7712 D BtGatt.GattService: start scan with filters
,08-23 08:44:26.541  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 08:44:26.541  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-23 08:44:26.541  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-23 08:44:26.541  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 08:44:26.551  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:26.551  7619  7649 D BtGatt.ScanManager: handling starting scan
,08-23 08:44:26.551  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:26.551  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 08:44:26.551  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 08:44:26.561  7619  7644 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 08:44:26.561  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.561  7619  7649 D BtGatt.ScanManager: allow scan with filters
08-23 08:44:26.561  7619  7649 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 08:44:26.561  7619  7649 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-23 08:44:26.561  7619  7644 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
,08-23 08:44:26.561  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.561  7619  7649 D BtGatt.ScanManager: Starting BLE batch scan
08-23 08:44:26.561  7619  7649 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-23 08:44:26.561  7619  7644 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-23 08:44:26.561  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.561  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:26.561  6821  6874 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-23 08:44:26.561  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:26.561  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:26.561  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.561  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 08:44:26.561  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@212edaa3 removed from the list
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:26.561  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a2f1a0 removed from the list,
08-23 08:44:26.561  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:26.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:26.561  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 08:44:26.561  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 08:44:26.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:26.561  7619  7644 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 08:44:26.561  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-23 08:44:26.561  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a2f1a0 not in the list
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:44:26.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 08:44:26.561  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 08:44:26.561  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 08:44:26.571  7619  7645 D BtGatt.GattService: stopScan() - queue size =1
08-23 08:44:26.571  7619  7627 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 08:44:26.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:44:26.571  7619  7649 D BtGatt.ScanManager: filter size is 1
08-23 08:44:26.571  7619  7649 D BtGatt.ScanManager: delete FilterIndex - 4
,08-23 08:44:26.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 08:44:26.571  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 08:44:26.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 08:44:26.571  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 08:44:26.571  7619  7644 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-23 08:44:26.571  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.571  7619  7649 D BtGatt.ScanManager: stopping BLe Batch
,08-23 08:44:26.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 08:44:26.571  7619  7644 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-23 08:44:26.571  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.571  7619  7649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 08:44:26.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 08:44:26.571  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 08:44:26.571  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 08:44:26.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:26.581  7619  7644 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-23 08:44:26.581  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.581  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 08:44:26.581  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:26.581  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 08:44:26.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:26.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.581  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca7dff removed from the list
08-23 08:44:26.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.581  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.581  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74b711e removed from the list
,08-23 08:44:26.581  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.581  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3052fb1b added. We now have 2 listener(s)
,08-23 08:44:26.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 08:44:26.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:26.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.581  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.581  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db954b8 added. We now have 9 listener(s)
08-23 08:44:26.581  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.581  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 08:44:26.591  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:44:26.591  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:44:26.591  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:44:26.591  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 08:44:26.591  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:26.601  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.601  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e4685f6 added. We now have 3 listener(s)
,08-23 08:44:26.601  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:26.601  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 08:44:26.601  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 08:44:26.601  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.601  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:44:26.601  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@331c2df7 added. We now have 10 listener(s)
08-23 08:44:26.601  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:26.601  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 08:44:26.601  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:44:26.601  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 08:44:26.601  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:44:26.601  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 08:44:26.611  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 08:44:26.611  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 08:44:26.611  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 08:44:26.611  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 08:44:26.611  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 08:44:26.611  6821  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 08:44:26.621  1016  1125 E WifiNative-wlan0: do suspend true
,08-23 08:44:26.621  7619  7712 D BtGatt.GattService: registerClient() - UUID=0f612c2e-3e91-4baf-8509-69768fa6823c
,08-23 08:44:26.641  1016  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-23 08:44:26.641  1016  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-23 08:44:26.651  1016  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 08:44:26.651  1016  1125 E WifiStateMachine: VerifyingLinkState enter
,08-23 08:44:26.651  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:26.651  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:26.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:26.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:26.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:26.651  1016  1127 E ConnectivityService: updateNetworkInfo()
,08-23 08:44:26.651  1016  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-23 08:44:26.651  1016  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-23 08:44:26.671  7619  7644 D BtGatt.GattService: onClientRegistered() - UUID=0f612c2e-3e91-4baf-8509-69768fa6823c, clientIf=6
,08-23 08:44:26.671  6821  6830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-23 08:44:26.671  7619  7628 D BtGatt.GattService: start scan with filters
08-23 08:44:26.671  1016  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-23 08:44:26.671  1016  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-23 08:44:26.671  1016  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-23 08:44:26.671  1016  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-23 08:44:26.671  1016  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-23 08:44:26.671  7619  7649 D BtGatt.ScanManager: handling starting scan
08-23 08:44:26.671  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 08:44:26.671  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 08:44:26.671  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 08:44:26.671  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 08:44:26.681  7619  7644 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-23 08:44:26.681  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.681  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:26.681  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:26.681  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.681  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:26.681  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.681  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.691  7619  7649 D BtGatt.ScanManager: allow scan with filters
08-23 08:44:26.691  7619  7649 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-23 08:44:26.691  7619  7649 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-23 08:44:26.691  1016  3831 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-23 08:44:26.691  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-23 08:44:26.691  7619  7644 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-23 08:44:26.691  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.691  7619  7649 D BtGatt.ScanManager: Starting BLE batch scan
08-23 08:44:26.691  7619  7649 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-23 08:44:26.691  1016  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-23 08:44:26.701  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 08:44:26.701  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 08:44:26.701  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 08:44:26.701  1016  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-23 08:44:26.701  1016  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-23 08:44:26.701  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:26.701  1016  3831 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:26.701  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:26.701  1016  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-23 08:44:26.711  7619  7644 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-23 08:44:26.711  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.711  1016  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 08:44:26.711  1016  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-23 08:44:26.711  1016  1127 D ConnectivityService: LTETest block dns file not exists
,08-23 08:44:26.711  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 08:44:26.711  1016  1127 V NetworkStats: updateIfacesLocked()
08-23 08:44:26.711  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.711  1016  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-23 08:44:26.711  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:26.711  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:26.711  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 08:44:26.721  2201  2201 I Hs20UtilService: Starting #22
,08-23 08:44:26.721  7619  7644 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-23 08:44:26.721  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.721  1016  1127 V NetworkStats: performPollLocked() took 4ms
08-23 08:44:26.721  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:26.721  1016  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 08:44:26.721  2201  2217 I Hs20UtilService: Message received 5007
08-23 08:44:26.721  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:26.721  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-23 08:44:26.721  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.721  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.721  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.721  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:26.721  1016  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 08:44:26.721  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-23 08:44:26.731  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
08-23 08:44:26.731  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,08-23 08:44:26.731  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:26.731  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 08:44:26.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.731  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:26.741  1016  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-23 08:44:26.741  1016  1127 E ConnectivityService: updateNetworkInfo()
08-23 08:44:26.741  1016  1127 E ConnectivityService: updateNetworkInfo()
,08-23 08:44:26.741  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.741  1016  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-23 08:44:26.741  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.741  1016  1127 V NetworkStats: updateIfacesLocked()
08-23 08:44:26.741  1016  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-23 08:44:26.751  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:26.751  1016  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:26.751  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:26.751  1016  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.751  1016  1127 V NetworkStats: performPollLocked() took 7ms
,08-23 08:44:26.751  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.751  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-23 08:44:26.751  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:26.751  1016  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-23 08:44:26.751  1016  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-23 08:44:26.751  1016  7736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:26.751  1016  7736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-23 08:44:26.751  1016  7736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:44:26.751  1016  7736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-23 08:44:26.761  3320  3320 I NearbySettings: MountReceiver.onReceive - Keep current state
08-23 08:44:26.761  1016  7736 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:26.761  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:26.761  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:26.761  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:26.761   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:26.761   277  1001 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-23 08:44:26.761  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.761  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.761  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 08:44:26.761  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.761  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3052fb1b removed from the list
08-23 08:44:26.761  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.761  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db954b8 removed from the list
08-23 08:44:26.761  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:26.761  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 08:44:26.761  1016  1127 D ConnectivityService:    accepting network in place of null
,08-23 08:44:26.761  1016  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-23 08:44:26.761  1444  1444 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-23 08:44:26.761  1444  1444 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 08:44:26.761  1016  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-23 08:44:26.771  1016  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-23 08:44:26.771  1016  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-23 08:44:26.771  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.771  1016  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 08:44:26.771  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 08:44:26.771  1016  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-23 08:44:26.771  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.771  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 08:44:26.771  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-23 08:44:26.771  1016  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-23 08:44:26.771  1016  1128 D Tethering: MasterInitialState.processMessage what=3
,08-23 08:44:26.771  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:26.771  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.771  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.771  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db954b8 not in the list
08-23 08:44:26.771  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:44:26.771  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-23 08:44:26.771  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 08:44:26.771  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 08:44:26.771  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 08:44:26.771  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-23 08:44:26.771  1016  1122 V NetworkStats: updateIfacesLocked()
08-23 08:44:26.771  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.771  1016  1122 V NetworkStats: performPollLocked(flags=0x1)
08-23 08:44:26.771  4870  6884 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 08:44:26.771  1177  1699 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 08:44:26.771  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:26.771  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:26.781  7619  7627 D BtGatt.GattService: stopScan() - queue size =1
,08-23 08:44:26.781  7619  7649 D BtGatt.ScanManager: filter size is 1
08-23 08:44:26.781  7619  7649 D BtGatt.ScanManager: delete FilterIndex - 5
,08-23 08:44:26.781  7619  7644 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-23 08:44:26.781  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.781  7619  7649 D BtGatt.ScanManager: stopping BLe Batch
,08-23 08:44:26.781  7619  7645 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-23 08:44:26.781  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.781  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.781  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-23 08:44:26.781  1016  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-23 08:44:26.781  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 08:44:26.781  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 08:44:26.781  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.781  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-23 08:44:26.781  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-23 08:44:26.781  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-23 08:44:26.781  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:26.781  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:44:26.781  1016  1122 V NetworkStats: performPollLocked() took 12ms
08-23 08:44:26.781  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 08:44:26.781  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 08:44:26.781  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 08:44:26.781  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 08:44:26.781  7619  7644 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-23 08:44:26.781  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-23 08:44:26.781  7619  7649 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-23 08:44:26.781  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 08:44:26.781  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.791  7619  7644 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-23 08:44:26.791  7619  7644 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-23 08:44:26.791  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 08:44:26.791  6821  6874 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 08:44:26.791  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-23 08:44:26.791  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:26.791  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:26.791  1016  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:26.791  1016  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:26.791  1016  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:26.791  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.791  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:26.791  1016  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 08:44:26.801  1016  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:26.801  2201  2201 I Hs20UtilService: Starting #23
08-23 08:44:26.801  2201  2217 I Hs20UtilService: Message received 5007
,08-23 08:44:26.801  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:26.801  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.801  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 08:44:26.801  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:26.801  6821  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:44:26.801  6821  6821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 08:44:26.801  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:26.801  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.801  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@331c2df7 removed from the list
08-23 08:44:26.801  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.801  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.801  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.801  3320  3320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-23 08:44:26.801  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.801  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e4685f6 removed from the list
08-23 08:44:26.801  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.801  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bdbb293 added. We now have 2 listener(s)
,08-23 08:44:26.801  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-23 08:44:26.811  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-23 08:44:26.811  3320  3320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-23 08:44:26.811  3320  3320 I NearbySettings: MountReceiver.onReceive - Keep current state
08-23 08:44:26.811  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-23 08:44:26.811  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:44:26.811  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.811  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.811  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da602d0 added. We now have 9 listener(s)
08-23 08:44:26.811  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:44:26.811  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 08:44:26.811  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:44:26.821  1016  3831 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-23 08:44:26.821  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-23 08:44:26.821  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:26.821  1016  3831 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:26.821  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-23 08:44:26.821  2201  2201 I Hs20UtilService: Starting #24
,08-23 08:44:26.821  2201  2217 I Hs20UtilService: Message received 5007
08-23 08:44:26.821  3320  3320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:44:26.821  6821  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:44:26.831  3320  3320 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-23 08:44:26.831  6821  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:44:26.831  6821  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:44:26.831  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:44:26.831  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32445dce added. We now have 3 listener(s)
08-23 08:44:26.831  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:44:26.831  6821  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:44:26.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-23 08:44:26.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 08:44:26.831  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:44:26.841  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:44:26.841  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1704e4ef added. We now have 10 listener(s)
08-23 08:44:26.841  1016  3840 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-23 08:44:26.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:44:26.841  6821  6874 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.841  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.841  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bdbb293 removed from the list
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.841  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da602d0 removed from the list
08-23 08:44:26.841  6821  6874 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:44:26.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:44:26.841  1016  3831 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-23 08:44:26.841  1016  3831 D SecContentProvider2: mCursor = null
08-23 08:44:26.841  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.841  1016  1478 D SecContentProvider2: uri = 15 selection = getToastGravity
08-23 08:44:26.841  1016  1478 D SecContentProvider2: mCursor = null
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 08:44:26.841  1016  1028 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-23 08:44:26.841  1016  1028 D SecContentProvider2: mCursor = null,
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:44:26.841  6821  6874 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da602d0 not in the list
08-23 08:44:26.841  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 08:44:26.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.841  1016  1377 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-23 08:44:26.841  1016  1377 D SecContentProvider2: mCursor = null
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:44:26.841  6821  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1704e4ef removed from the list
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:44:26.841  6821  6874 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:44:26.841  6821  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:44:26.841  6821  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:44:26.841  6821  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32445dce removed from the list
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 08:44:26.841  6821  6874 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-23 08:44:26.851  1016  1328 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-23 08:44:26.851  1016  1328 D SecContentProvider2: mCursor = null
08-23 08:44:26.851  1016  3831 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-23 08:44:26.851  1016  3831 D SecContentProvider2: mCursor = null
,08-23 08:44:26.851  6821  7774 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1364, name: My test thread name)
08-23 08:44:26.851  6821  7774 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1364, thread name: My test thread name)
08-23 08:44:26.851  6821  7774 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1364, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-23 08:44:26.861  6821  7775 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1366, name: My test thread name),
08-23 08:44:26.861  6821  7775 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1366, thread name: My test thread name)
08-23 08:44:26.861  6821  7775 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1366, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-23 08:44:26.861  6821  6874 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-23 08:44:26.861  6821  6874 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 08:44:26.861  6821  6874 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-23 08:44:26.861  6821  6874 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-23 08:44:26.861  6821  6874 D com.test.thalitest.ThaliTestRunner: Total duration: 23445 ms
,08-23 08:44:26.861  6821  6874 I jxcore-log: Total number of executed tests:  80
08-23 08:44:26.861  6821  6874 I jxcore-log: 
08-23 08:44:26.861  6821  6874 I jxcore-log: Number of passed tests:  80
08-23 08:44:26.861  6821  6874 I jxcore-log: 
08-23 08:44:26.861  6821  6874 I jxcore-log: Number of failed tests:  0
08-23 08:44:26.861  6821  6874 I jxcore-log: 
08-23 08:44:26.861  6821  6874 I jxcore-log: Number of ignored tests:  0
08-23 08:44:26.861  6821  6874 I jxcore-log: 
08-23 08:44:26.861  6821  6874 I jxcore-log: Total duration:  23445
08-23 08:44:26.861  6821  6874 I jxcore-log: 
08-23 08:44:26.861  6821  6874 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 08:44:26.861  6821  6874 I jxcore-log: 
,08-23 08:44:26.861  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.861  6821  6874 I jxcore-log: 
08-23 08:44:26.871  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.871  6821  6874 I jxcore-log: 
08-23 08:44:26.871  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.871  6821  6874 I jxcore-log: 
08-23 08:44:26.871  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.871  6821  6874 I jxcore-log: 
08-23 08:44:26.871  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.871  6821  6874 I jxcore-log: 
08-23 08:44:26.871  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.871  6821  6874 I jxcore-log: 
,08-23 08:44:26.871  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.871  6821  6874 I jxcore-log: 
,08-23 08:44:26.871  6821  6821 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
,08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
,08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
,08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
,08-23 08:44:26.881  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 08:44:26.881  6821  6874 I jxcore-log: 
08-23 08:44:26.891  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 08:44:26.891  6821  6874 I jxcore-log: 
,08-23 08:44:26.891  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 08:44:26.891  6821  6874 I jxcore-log: 
08-23 08:44:26.891  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-23 08:44:26.891  6821  6874 I jxcore-log: 
08-23 08:44:26.891  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 08:44:26.891  6821  6874 I jxcore-log: 
,08-23 08:44:26.891  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 08:44:26.891  6821  6874 I jxcore-log: 
08-23 08:44:26.891  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:44:26.891  6821  6874 I jxcore-log: 
,08-23 08:44:26.901  1016  3840 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-23 08:44:26.901  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 08:44:26.951  6821  6821 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-23 08:44:26.951  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 08:44:26.951  6821  6874 I jxcore-log: 
,08-23 08:44:27.031   294   294 E SMD     : DCD OFF,
,08-23 08:44:27.081  6821  6821 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-23 08:44:27.081  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 08:44:27.081  6821  6874 I jxcore-log: 
,08-23 08:44:27.141  7777  7777 D AndroidRuntime: ,
08-23 08:44:27.141  7777  7777 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 08:44:27.141  7777  7777 D AndroidRuntime: CheckJNI is OFF,
08-23 08:44:27.141  7777  7777 D AndroidRuntime: readGMSProperty: start
08-23 08:44:27.141  7777  7777 D AndroidRuntime: readGMSProperty: already setted!!
08-23 08:44:27.141  7777  7777 D AndroidRuntime: propertySet: couldn't set property (it is from app),
08-23 08:44:27.141  7777  7777 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 08:44:27.141  7777  7777 D AndroidRuntime: readGMSProperty: end
08-23 08:44:27.141  7777  7777 D AndroidRuntime: addProductProperty: start
,08-23 08:44:27.271  1016  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:27.271  7777  7777 E AffinityControl: AffinityControl: registerfunction enter
,08-23 08:44:27.291  1016  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 08:44:27.291  1016  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 08:44:27.291  1016  1491 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 08:44:27.291  1016  1491 D BatteryService: stay LED for fully charged
08-23 08:44:27.291  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-23 08:44:27.301  6821  6821 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 08:44:27.301  7777  7777 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 08:44:27.311  6821  6874 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,08-23 08:44:27.311  6821  6874 I jxcore-log: 
,08-23 08:44:27.321  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 08:44:27.321  1016  1029 D PackageManager: START PACKAGE DELETE: observer{868804072}
08-23 08:44:27.321  1016  1029 D PackageManager: pkg{<packageName>}
08-23 08:44:27.321  1016  1029 D PackageManager: user{0}
,08-23 08:44:27.321  1016  1029 D PackageManager: caller{2000}
08-23 08:44:27.321  1016  1029 D PackageManager: flags{2}
08-23 08:44:27.321  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 08:44:27.321  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 08:44:27.321  1016  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 08:44:27.321  1016  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 08:44:27.321  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-23 08:44:27.321  1016  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 08:44:27.321  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 08:44:27.321  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 08:44:27.321  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 08:44:27.331  1016  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-23 08:44:27.341  1016  1016 I MotionRecognitionService: Plugged
08-23 08:44:27.341  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 08:44:27.351  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 08:44:27.351  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 08:44:27.351  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 08:44:27.351  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 08:44:27.361  7619  7619 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 08:44:27.361  7619  7650 D HeadsetStateMachine: Disconnected process message: 10
,08-23 08:44:27.371  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-23 08:44:27.371  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 08:44:27.371  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 08:44:27.421  1016  1055 W PackageSettings: Skipping PackageSetting{194b9130 com.example.hello/10168} due to missing metadata
,08-23 08:44:27.461  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 08:44:27.461  6821  6821 D AndroidRuntime: Shutting down VM
,08-23 08:44:27.471  6821  6821 E AndroidRuntime: FATAL EXCEPTION: main
08-23 08:44:27.471  6821  6821 E AndroidRuntime: Process: com.test.thalitest, PID: 6821
08-23 08:44:27.471  6821  6821 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } in io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@125d6022
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:943)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: Caused by: java.lang.SecurityException: ConnectivityService: Neither user 10171 nor current process has android.permission.ACCESS_NETWORK_STATE.
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1540)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1493)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.net.IConnectivityManager$Stub$Proxy.getActiveNetworkInfo(IConnectivityManager.java:1297)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.net.ConnectivityManager.getActiveNetworkInfo(ConnectivityManager.java:748)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor.updateConnectivityInfo(ConnectivityMonitor.java:152)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver.onReceive(ConnectivityMonitor.java:225)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
08-23 08:44:27.471  6821  6821 E AndroidRuntime: 	... 8 more
,08-23 08:44:27.471  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.471  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.471  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.471  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:27.471  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:27.481  7787  7787 E Zygote  : MountEmulatedStorage()
,08-23 08:44:27.481  7787  7787 E Zygote  : v2
08-23 08:44:27.481  7787  7787 I libpersona: KNOX_SDCARD checking this for 1000
08-23 08:44:27.481  7787  7787 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:27.491  7787  7787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:27.491  1016  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7787 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 08:44:27.491  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-23 08:44:27.491  1016  1041 I ActivityManager: Killing 6821:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-23 08:44:27.491  7787  7787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:27.491  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{2aa1381f u0 com.test.thalitest/.MainActivity t2}
,08-23 08:44:27.491  7787  7787 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 08:44:27.491  1016  1510 W ActivityManager: Can't find mystery application for Crash from pid=6821 uid=10171: android.os.BinderProxy@3c06c401
,08-23 08:44:27.501  1016  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-23 08:44:27.501  1016  1055 I ActivityManager:   Force finishing activity ActivityRecord{2aa1381f u0 com.test.thalitest/.MainActivity t2 f}
08-23 08:44:27.501  1016  1055 W ActivityManager: Duplicate finish request for ActivityRecord{2aa1381f u0 com.test.thalitest/.MainActivity t2 f}
,08-23 08:44:27.511  1016  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 08:44:27.531  7787  7787 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:27.531  7787  7787 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:27.541  1016  1041 D InputDispatcher: Focus left window: 6821
,08-23 08:44:27.541   257  2620 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-23 08:44:27.551  2703  2703 I art     : Explicit concurrent mark sweep GC freed 21944(1217KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 801us total 34.891ms
,08-23 08:44:27.551   257   737 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-23 08:44:27.571  1016  3831 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 08:44:27.571  1016  3831 D SecContentProvider2: mCursor = null
,08-23 08:44:27.581  1016  1041 D InputDispatcher: Focused application released
,08-23 08:44:27.581  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 08:44:27.581  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 08:44:27.581  1016  1041 D FocusedStackFrame: Set to : 0
,08-23 08:44:27.581  1016  1041 W ActivityManager: mDVFSHelper.acquire()
,08-23 08:44:27.591  1016  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-23 08:44:27.591  4870  4870 I art     : Explicit concurrent mark sweep GC freed 23133(1412KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 12MB/21MB, paused 1.433ms total 84.101ms
,08-23 08:44:27.621  1479  1479 D Launcher: onRestart, Launcher: 919164479
,08-23 08:44:27.631  1016  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 08:44:27.641  1827  1827 E SamsungIME: mOCRHelper is null
,08-23 08:44:27.641  7787  7787 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 08:44:27.641  7787  7787 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 08:44:27.641  7787  7787 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-23 08:44:27.641  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-23 08:44:27.651  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 08:44:27.651  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 08:44:27.651  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 08:44:27.651  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-23 08:44:27.651  1479  1479 D Launcher: onStart, Launcher: 919164479
08-23 08:44:27.651  1479  1479 D Launcher.HomeView: onStart
,08-23 08:44:27.651  1479  1479 D Launcher: onResume, Launcher: 919164479
,08-23 08:44:27.651  1016  1478 D SettingsProvider: name = kids_home_mode
08-23 08:44:27.651  1016  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 08:44:27.651  1016  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 08:44:27.651  1016  1478 D SettingsProvider: selectionArgs: false
08-23 08:44:27.651  1016  1478 D SettingsProvider: selectionArgs: 10006
08-23 08:44:27.651  1016  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 08:44:27.651  1016  1478 D SettingsProvider: ret = -1
,08-23 08:44:27.651  1479  1479 D Launcher.HomeView: onResume
,08-23 08:44:27.671  1437  1437 D PersonaManager: isKioskContainerExistOnDevice,
,08-23 08:44:27.681  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-23 08:44:27.691  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-23 08:44:27.711  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 08:44:27.711  1016  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-23 08:44:27.711  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:27.711  1016  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-23 08:44:27.711  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 08:44:27.711  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 08:44:27.721  1016  1122 V NetworkStats: performPollLocked() took 7ms
08-23 08:44:27.721  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:27.721  1437  1437 D RegisteredServicesCache: empty dynamic service
,08-23 08:44:27.721  1479  1479 D MenuAppsGridFragment: onResume
,08-23 08:44:27.731  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 08:44:27.731  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 08:44:27.741  7787  7787 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-23 08:44:27.741  7787  7787 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-23 08:44:27.741  7787  7787 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-23 08:44:27.741  7787  7787 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:27.741  1016  3840 D ActivityManager: handle home activity for 0
08-23 08:44:27.741  1016  3840 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-23 08:44:27.741  1016  3840 D KnoxTimeoutHandler: post home show event for user 0
08-23 08:44:27.741  1016  3840 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 08:44:27.741  1016  3840 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 08:44:27.741  1016  3840 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 08:44:27.751  1479  1479 D Launcher.HomeView: onPause
,08-23 08:44:27.751  1016  1377 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-23 08:44:27.751  1016  1377 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-23 08:44:27.751  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 08:44:27.751  1016  1040 E libprocessgroup: failed to kill 1 processes for processgroup 6821
,08-23 08:44:27.771  1016  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-23 08:44:27.801  1745  1745 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 08:44:27.801  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-23 08:44:27.801  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.801  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.801  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.801  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:27.821  7806  7806 E Zygote  : MountEmulatedStorage(),
,08-23 08:44:27.831  7806  7806 E Zygote  : v2
08-23 08:44:27.831  7806  7806 I libpersona: KNOX_SDCARD checking this for 10121
08-23 08:44:27.831  7806  7806 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:27.831  7806  7806 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 08:44:27.831  7806  7806 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:27.841  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:27.841  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7806 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-23 08:44:27.841  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:27.841  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-23 08:44:27.841  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-23 08:44:27.841  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
08-23 08:44:27.841  1437  1437 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 08:44:27.841  7806  7806 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 08:44:27.851  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 08:44:27.851  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 08:44:27.851  1437  1437 D PersonaManager: isKioskContainerExistOnDevice
,08-23 08:44:27.851  1016  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-23 08:44:27.851  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 08:44:27.851  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-23 08:44:27.851  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 08:44:27.851  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 08:44:27.861  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 08:44:27.861  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 08:44:27.861  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 08:44:27.861  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 08:44:27.861   317   317 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 34.594ms
,08-23 08:44:27.871  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-23 08:44:27.871  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.871  2604  2686 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 16
08-23 08:44:27.871  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.871  1016  1377 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 08:44:27.871  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:27.871  1016  1377 D SecContentProvider2: mCursor = null
08-23 08:44:27.871  1016  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:27.881  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 08:44:27.881  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 08:44:27.881   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 17.461ms
,08-23 08:44:27.891  7806  7806 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:27.891  7806  7806 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:27.901   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.404ms
,08-23 08:44:27.911  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 08:44:27.911  1016  1040 W TextServicesManagerService: no available spell checker services found
08-23 08:44:27.911  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-23 08:44:27.911  7821  7821 E Zygote  : MountEmulatedStorage(),
08-23 08:44:27.911  7821  7821 E Zygote  : v2
08-23 08:44:27.911  7821  7821 I libpersona: KNOX_SDCARD checking this for 10031
08-23 08:44:27.911  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 08:44:27.911  7821  7821 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:27.911  7821  7821 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:27.911  1016  1491 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7821 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-23 08:44:27.921  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 08:44:27.921  7821  7821 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 08:44:27.921  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 08:44:27.921  7821  7821 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 08:44:27.921  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 08:44:27.921  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 08:44:27.921  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-23 08:44:27.921  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 08:44:27.921  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-23 08:44:27.921  1745  1745 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-23 08:44:27.921  1016  3385 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-23 08:44:27.921  1745  1745 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1,
08-23 08:44:27.921  1745  1745 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-23 08:44:27.921  1745  1745 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-23 08:44:27.921  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 08:44:27.921  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 08:44:27.921  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 08:44:27.931  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-23 08:44:27.931  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:27.931  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-23 08:44:27.931  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-23 08:44:27.941  1016  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-23 08:44:27.951  7806  7806 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:44:27.951  7806  7806 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 08:44:27.951  7806  7806 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 08:44:27.961  1745  1745 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-23 08:44:27.961  1745  1745 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-23 08:44:27.961  7821  7821 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 08:44:27.961  7821  7821 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:27.971   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-23 08:44:27.971  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 08:44:27.981  1016  1478 D InputDispatcher: Focus entered window: 1479
,08-23 08:44:27.981  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 08:44:27.981  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 08:44:27.981  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 08:44:27.991  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 08:44:28.001  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-23 08:44:28.001  1016  1377 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-23 08:44:28.001  1016  1377 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-23 08:44:28.001  1479  1479 D Launcher.HomeView: onStop
08-23 08:44:28.001  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{26753221 token=android.os.BinderProxy@2239c177 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-23 08:44:28.001  1016  1377 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:28.011  1016  1377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:28.011  1016  1377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-23 08:44:28.011  1016  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 08:44:28.011  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-23 08:44:28.011  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-23 08:44:28.011  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 08:44:28.011  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-23 08:44:28.011  7806  7806 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:28.021  1016  7837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 08:44:28.021  1016  1029 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6821 uid 10171
,08-23 08:44:28.021  7806  7806 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-23 08:44:28.031  7806  7806 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-23 08:44:28.031  1827  1827 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 08:44:28.041  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-23 08:44:28.041  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.041  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.041  1016  1055 I art     : Explicit concurrent mark sweep GC freed 77643(5MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 7.790ms total 392.747ms
08-23 08:44:28.041  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.041  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.041  1016  3839 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:28.051  1016  1377 D RCPManagerService: exchangeData() failure , invalid userId
,08-23 08:44:28.061  7841  7841 E Zygote  : MountEmulatedStorage()
,08-23 08:44:28.061  7841  7841 I libpersona: KNOX_SDCARD checking this for 10001
08-23 08:44:28.061  7841  7841 E Zygote  : v2
08-23 08:44:28.061  7841  7841 I libpersona: KNOX_SDCARD not a persona
08-23 08:44:28.061  7841  7841 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:28.061  7841  7841 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:28.061  7841  7841 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-23 08:44:28.061  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7841 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:44:28.071  1177  1177 I StatusBar: Icon Only
08-23 08:44:28.071  1016  1231 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-23 08:44:28.071  1177  1177 D PanelView: There is/are notification(s) 
08-23 08:44:28.071  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-23 08:44:28.071  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:28.071  1016  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:28.071  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-23 08:44:28.081  1016  1041 W ActivityManager: mDVFSHelper.release()
,08-23 08:44:28.091  7841  7841 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:28.091  7841  7841 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:28.091  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{352a03a8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147218
,08-23 08:44:28.101  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-23 08:44:28.121  7056  7856 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-23 08:44:28.121  7056  7856 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 08:44:28.121  7056  7856 I System.out: (HTTPLog)-Static: isShipBuild true
08-23 08:44:28.121  7056  7856 I System.out: (HTTPLog)-Thread-1271-308109346: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 08:44:28.121  7056  7856 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 08:44:28.121   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:28.121   277  1001 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-23 08:44:28.131  7319  7319 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-23 08:44:28.131  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:28.141  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:28.151  1940  2177 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 08:44:28.171  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:28.171  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 08:44:28.171  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:44:28.171  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 08:44:28.171  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:28.181  7205  7205 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-23 08:44:28.181  2824  7861 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-23 08:44:28.181  2824  7861 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-23 08:44:28.181  2824  7861 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-23 08:44:28.181  7242  7242 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-23 08:44:28.181  7242  7242 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-23 08:44:28.181  7242  7242 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-23 08:44:28.191  7056  7856 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 08:44:28.191  7242  7242 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-23 08:44:28.191  7242  7242 I SA      : [OR] == isSIMCardReady false ==
08-23 08:44:28.201  1016  1055 D PackageManager: delete codoeFile: 
,08-23 08:44:28.211  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:28.211  7242  7242 I SA      : [SCU] == networkStateCheck == true
,08-23 08:44:28.211  7242  7242 I SA      : [DM] getCountryCodeFromCSC : PL
08-23 08:44:28.211  7242  7242 I SA      : isChinaCountryCode : false
08-23 08:44:28.211  7242  7242 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-23 08:44:28.211  7242  7242 I SA      : [OR] == networkStateCheck true ==
,08-23 08:44:28.211  1016  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-23 08:44:28.211  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:28.221  1016  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-23 08:44:28.221  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 08:44:28.221  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 08:44:28.221  1016  1055 D PackageManager: result of delete: 1{868804072}
,08-23 08:44:28.221  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 08:44:28.221  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 08:44:28.221  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 08:44:28.231  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 08:44:28.231  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 08:44:28.231  7242  7242 I SA      : [OR] GetMyCountryZoneTask
,08-23 08:44:28.231  7242  7242 I SA      : [OR] onReceive END
08-23 08:44:28.231  1016  7736 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 08:44:28.241  7214  7214 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:44:28.241  7214  7214 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-23 08:44:28.241  7214  7214 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-23 08:44:28.241  2824  7861 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-23 08:44:28.241  7214  7214 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
08-23 08:44:28.241  2824  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
08-23 08:44:28.241  2824  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
08-23 08:44:28.241  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-23 08:44:28.241  2824  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-23 08:44:28.241  2824  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
08-23 08:44:28.241  1016  1231 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-23 08:44:28.241  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
08-23 08:44:28.241  2824  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
08-23 08:44:28.241  2824  7861 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
08-23 08:44:28.251  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:28.251  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 08:44:28.251  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:28.251  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
08-23 08:44:28.251  2824  7861 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
08-23 08:44:28.251  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-23 08:44:28.251  7242  7865 I SA      : [SRS] prepareGetMyCountryZone
08-23 08:44:28.261  7777  7777 D AndroidRuntime: Shutting down VM
08-23 08:44:28.271  7056  7856 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-23 08:44:28.271  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-23 08:44:28.271  1016  1328 I ActivityManager: Killing 7264:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-23 08:44:28.271  1016  1329 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-23 08:44:28.271  1016  1329 D SecContentProvider2: mCursor = null
,08-23 08:44:28.281  1016  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 08:44:28.281  1016  1055 D PackageManager: userId{-1}
08-23 08:44:28.281  1016  1055 D PackageManager: andCode{true}
,08-23 08:44:28.281  1016  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 08:44:28.281  2824  7861 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-23 08:44:28.281  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.281  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.281  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.281  1016  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.291  7868  7868 E Zygote  : MountEmulatedStorage()
08-23 08:44:28.291  7868  7868 E Zygote  : v2
08-23 08:44:28.291  7868  7868 I libpersona: KNOX_SDCARD checking this for 10003
08-23 08:44:28.291  7868  7868 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:28.291  7868  7868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:28.301  7868  7868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 08:44:28.301  1016  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7868 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 08:44:28.301  7868  7868 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 08:44:28.311  1016  7736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 06:44:28 GMT], X-Android-Received-Millis=[1471934668316], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471934668277]}
08-23 08:44:28.311  1016  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-23 08:44:28.311  1016  7736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 08:44:28.311  1016  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-23 08:44:28.311  1016  7736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-23 08:44:28.311  1016  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-23 08:44:28.311  1016  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-23 08:44:28.311  1016  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 08:44:28.311  1177  1699 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 08:44:28.311  4870  6884 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 08:44:28.311  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
,08-23 08:44:28.311  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-23 08:44:28.311  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-23 08:44:28.311  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-23 08:44:28.311  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-23 08:44:28.311  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-23 08:44:28.321  2824  7861 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-23 08:44:28.321  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-23 08:44:28.321  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-23 08:44:28.321  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-23 08:44:28.331  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-23 08:44:28.331  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-23 08:44:28.331  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:28.331  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:28.331  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-23 08:44:28.331  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-23 08:44:28.331  7868  7868 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:28.331  7868  7868 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:28.341  7242  7865 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-23 08:44:28.341  7242  7865 I SA      : [SSP] query invoked
,08-23 08:44:28.351  7242  7865 I SA      : [TPMU] GetMccFromDB : null
08-23 08:44:28.351  7242  7865 I SA      : [SCU] getMccFromPreferece mcc = 260
08-23 08:44:28.351  7242  7865 I SA      : [LBE] isSupportCheckDomainRegion : false
08-23 08:44:28.351  7242  7865 I SA      : [TPM] isNoProxy(default) : true
,08-23 08:44:28.361  1016  1510 D PersonaManager: isKioskContainerExistOnDevice
,08-23 08:44:28.361  7242  7865 E File    : fail readDirectory() errno=2
,08-23 08:44:28.371  1016  1328 I ActivityManager: Killing 7276:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-23 08:44:28.401   254   254 E lowmemorykiller: Error writing /proc/7276/oom_score_adj; errno=22
,08-23 08:44:28.401  1016  3840 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-23 08:44:28.401  1016  3840 W ActivityManager: ProcessRecord{bbc8302 7276:com.sec.android.fotaclient/u0a8} is already killed
,08-23 08:44:28.401  1016  3840 I ActivityManager: Existing provider com.sec.android.fotaclient/.log.MasterLogProvider is crashing; detaching ProcessRecord{4ba9413 7214:com.sec.android.diagmonagent/1000}
,08-23 08:44:28.401  1016  3840 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-23 08:44:28.401  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 08:44:28.401  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.401  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.401  1016  3840 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.421  7886  7886 E Zygote  : MountEmulatedStorage()
08-23 08:44:28.421  7886  7886 E Zygote  : v2
08-23 08:44:28.421  7886  7886 I libpersona: KNOX_SDCARD checking this for 10008
08-23 08:44:28.421  7886  7886 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:28.421  7886  7886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:28.431  7886  7886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:28.431  7886  7886 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-23 08:44:28.431  1016  3840 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7886 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:44:28.471  7777  7777 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 08:44:28.471  7886  7886 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 08:44:28.481  7886  7886 D ActivityThread: Added TimaKeyStore provider
,08-23 08:44:28.501  1479  1479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2239c177 time:147628
,08-23 08:44:28.531  1016  1133 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-23 08:44:28.531  1016  1133 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-23 08:44:28.531  1016  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-23 08:44:28.531  1016  1133 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-23 08:44:28.531  1016  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-23 08:44:28.541  1016  1231 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 08:44:28.541  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 08:44:28.541  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:28.541  1016  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 08:44:28.541  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 08:44:28.551  4870  4870 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 08:44:28.551   277  1001 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-23 08:44:28.551   277  1001 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-23 08:44:28.551  7319  7319 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-23 08:44:28.561  7319  7319 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: exit::IDLE
08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-23 08:44:28.561  7319  7319 D InitializeManagerStateMachine: entry::SUCCESS
08-23 08:44:28.561  7319  7319 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-23 08:44:28.571  7319  7319 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-23 08:44:28.571  7319  7319 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-23 08:44:28.571  7319  7319 D InitializeManagerStateMachine: exit::SUCCESS
08-23 08:44:28.571  7319  7319 D InitializeManagerStateMachine: entry::IDLE
,08-23 08:44:28.571  1016  1329 I ActivityManager: Killing 6904:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-23 08:44:28.581  7886  7886 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-23 08:44:28.581  4870  7339 I iu.UploadsManager: num queued entries: 0
,08-23 08:44:28.581  4870  7339 I iu.UploadsManager: num updated entries: 0
,08-23 08:44:28.581  4870  7339 I iu.SyncManager: NEXT; no task
,08-23 08:44:28.591  7886  7886 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-23 08:44:28.601  7886  7886 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-23 08:44:28.601  7886  7886 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-23 08:44:28.601  1016  1231 I ActivityManager: Killing 7690:com.samsung.android.sm/1000 (adj 15): empty #21
,08-23 08:44:28.611  1016  1029 I ActivityManager: Killing 7505:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-23 08:44:28.621  2942  2942 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 08:44:28 GMT+02:00 2016
,08-23 08:44:28.621  1016  1328 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 08:44:28.621  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:28.621  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-23 08:44:28.621  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:28.621  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 08:44:28.631  2942  2942 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 08:44:28.631  1016  1133 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,08-23 08:44:28.631  2942  2942 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 08:44:28.631  2942  2942 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 08:44:28.641  2942  2942 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 08:44:28.641  2942  7906 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 08:44:28.641  2942  7906 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-23 08:44:28.641  2942  2942 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 08:44:28 GMT+02:00 2016
,08-23 08:44:28.641  1016  3831 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-23 08:44:28.641  1016  3831 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 08:44:28.651  1016  3831 W ActivityManager: userId = 0, bbcId = -10000
08-23 08:44:28.651  1016  3831 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 08:44:28.651  1016  3831 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 08:44:28.651  2942  7906 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-23 08:44:28.651  2942  2942 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 08:44:28.651  2942  7906 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-23 08:44:28.651  1016  3839 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-23 08:44:28.651  1016  3839 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-23 08:44:28.651  1016  3839 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-23 08:44:28.651  2942  7906 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-23 08:44:28.661  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.661  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.661  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.661  1016  3839 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.661  2942  7906 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30),
,08-23 08:44:28.661  2942  7906 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:171)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.uploadRequestLog(NetworkChangeOperations.java:81)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.doNetworkJob(NetworkChangeOperations.java:57)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.StateImplV2.networkChangeListener(StateImplV2.java:240)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:222)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:28.661  2942  7906 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:171)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.uploadRequestLog(NetworkChangeOperations.java:81)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.doNetworkJob(NetworkChangeOperations.java:57)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.StateImplV2.networkChangeListener(StateImplV2.java:240)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:222)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-23 08:44:28.671  2942  7906 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 08:44:28.671  2942  7906 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-23 08:44:28.671  2942  7906 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-23 08:44:28.671  7907  7907 E Zygote  : MountEmulatedStorage(),
08-23 08:44:28.671  7907  7907 E Zygote  : v2
08-23 08:44:28.671  7907  7907 I libpersona: KNOX_SDCARD checking this for 10090
08-23 08:44:28.671  7907  7907 I libpersona: KNOX_SDCARD not a persona,
08-23 08:44:28.671  2942  7906 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END,
,08-23 08:44:28.681  1016  3839 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7907 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-23 08:44:28.681  7907  7907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:28.681  7907  7907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 08:44:28.681  7907  7907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 08:44:28.681  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-23 08:44:28.691  1016  1491 I TactileAssist: enable value -1
08-23 08:44:28.691  1016  1491 I TactileAssist: internal enable value -1
08-23 08:44:28.691  1016  1491 I TactileAssist: intensity value -1
08-23 08:44:28.691  1016  1491 I TactileAssist: saveAppList value true
,08-23 08:44:28.691  1016  1491 I TactileAssist: List of disabled apps :
08-23 08:44:28.691  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.691  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.691  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 08:44:28.691  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 08:44:28.711  7922  7922 E Zygote  : MountEmulatedStorage()
08-23 08:44:28.711  7922  7922 E Zygote  : v2
08-23 08:44:28.711  7922  7922 I libpersona: KNOX_SDCARD checking this for 1000
08-23 08:44:28.711  7922  7922 I libpersona: KNOX_SDCARD not a persona
,08-23 08:44:28.711  7922  7922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 08:44:28.721  7922  7922 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 08:44:28.721  7922  7922 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
