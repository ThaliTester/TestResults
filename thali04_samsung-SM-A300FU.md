#### Test 79763830e108614_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-24 13:23:29.316  1016  3173 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
--------- beginning of main
08-24 13:23:29.316  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:23:29.316  1016  3173 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:23:29.316  1016  3173 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:23:29.326  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:23:29.316  1016  3173 D BatteryService: stay LED for fully charged
08-24 13:23:29.316  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 13:23:29.316  1016  1016 I MotionRecognitionService: Plugged
08-24 13:23:29.316  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:23:29.326  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:23:29.326  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-24 13:23:29.336  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 13:23:29.336  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:23:29.346  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:23:29.346  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:23:29.346  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:23:29.346  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:23:29.346  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:23:29.616  6719  6719 D AndroidRuntime: 
08-24 13:23:29.616  6719  6719 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 13:23:29.616  6719  6719 D AndroidRuntime: CheckJNI is OFF
08-24 13:23:29.626  6719  6719 D AndroidRuntime: readGMSProperty: start
08-24 13:23:29.626  6719  6719 D AndroidRuntime: readGMSProperty: already setted!!
08-24 13:23:29.626  6719  6719 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 13:23:29.626  6719  6719 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 13:23:29.626  6719  6719 D AndroidRuntime: readGMSProperty: end
08-24 13:23:29.626  6719  6719 D AndroidRuntime: addProductProperty: start
08-24 13:23:29.756  6719  6719 E AffinityControl: AffinityControl: registerfunction enter
08-24 13:23:29.776  6719  6719 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 13:23:29.796  1016  1457 E PersonaManagerService: inState():  stateMachine is null !!
08-24 13:23:29.796  1016  1457 I PersonaManagerService: PersonaId don't exist
08-24 13:23:29.796  1016  1457 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-24 13:23:29.796  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 13:23:29.816  1016  1457 W ActivityManager: mDVFSHelper.acquire()
08-24 13:23:29.826   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-24 13:23:29.826   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-24 13:23:29.836  1016  1457 D FocusedStackFrame: Set to : 0
08-24 13:23:29.836  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:23:29.836  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:23:29.836  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:23:29.836  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:23:29.846  1016  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 13:23:29.846  1016  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-24 13:23:29.856  6730  6730 E Zygote  : MountEmulatedStorage()
08-24 13:23:29.856  1016  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 13:23:29.856  1016  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 13:23:29.856  6730  6730 E Zygote  : v2
08-24 13:23:29.856  6730  6730 I libpersona: KNOX_SDCARD checking this for 10171
08-24 13:23:29.856  6730  6730 I libpersona: KNOX_SDCARD not a persona
08-24 13:23:29.856  6730  6730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:23:29.856   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-24 13:23:29.856  6730  6730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:23:29.856  1016  1457 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6730 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 13:23:29.856  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 13:23:29.856  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 13:23:29.856  6730  6730 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 13:23:29.866  1016  1457 D InputDispatcher: Focused application set to: xxxx
08-24 13:23:29.866  1016  1457 D InputDispatcher: Focus left window: 1482
08-24 13:23:29.866  6719  6719 D AndroidRuntime: Shutting down VM
08-24 13:23:29.866  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 13:23:29.876  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:23:29.886  6730  6730 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:23:29.886  6730  6730 D ActivityThread: Added TimaKeyStore provider
08-24 13:23:29.886  1016  1029 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-24 13:23:29.896  1016  1016 V ActivityManager: Display changed displayId=0
08-24 13:23:29.906  1016  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 13:23:29.916  1016  1029 D PersonaManager: isKioskContainerExistOnDevice
08-24 13:23:29.936  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-24 13:23:29.946   257  1097 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-24 13:23:29.946   257   438 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-24 13:23:29.956  1482  1482 D Launcher: onTrimMemory. Level: 20
08-24 13:23:29.956  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{3c08a633 token=android.os.BinderProxy@20856959 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 13:23:30.036  6730  6730 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-24 13:23:30.076  6719  6719 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 13:23:30.086  6730  6730 I cr.library_loader: Time to load native libraries: 19 ms (timestamps 6881-6900)
08-24 13:23:30.086  6730  6730 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-24 13:23:30.106  6730  6730 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27fbd9eb}
08-24 13:23:30.106  6730  6730 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-24 13:23:30.116  6730  6730 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 13:23:30.146  6730  6730 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-24 13:23:30.146  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:23:30.156  6730  6730 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 13:23:30.186  6730  6730 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 13:23:30.186  6730  6730 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 13:23:30.186  6730  6730 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 13:23:30.186  6730  6730 I Adreno-EGL: Local Branch: 
08-24 13:23:30.186  6730  6730 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 13:23:30.186  6730  6730 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 13:23:30.186  6730  6730 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-24 13:23:30.256   292   292 E SMD     : DCD OFF
08-24 13:23:30.276  6730  6730 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 13:23:30.296  6730  6730 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-24 13:23:30.296  6730  6730 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-24 13:23:30.306  6730  6730 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-24 13:23:30.306  6730  6730 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-24 13:23:30.406  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:23:30.416  6730  6730 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 13:23:30.426  1016  1043 W ActivityManager: Activity pause timeout for ActivityRecord{2409b1c4 u0 com.test.thalitest/.MainActivity t2}
08-24 13:23:30.426  6730  6730 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 13:23:30.426  6730  6730 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-24 13:23:30.436  6730  6730 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-24 13:23:30.446  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:23:30.446  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:23:30.576  6730  6771 D OpenGLRenderer: Render dirty regions requested: true
08-24 13:23:30.576  1016  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 13:23:30.576  1016  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 13:23:30.576  1016  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 13:23:30.576  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 13:23:30.576  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-24 13:23:30.586  6730  6758 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-24 13:23:30.586  6730  6730 V ActivityThread: updateVisibility : ActivityRecord{3854a9cb token=android.os.BinderProxy@f4359bc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-24 13:23:30.596  6730  6730 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 13:23:30.596  6730  6730 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 13:23:30.606   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-24 13:23:30.616  1016  1325 D InputDispatcher: Focus entered window: 6730
08-24 13:23:30.626  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 13:23:30.626  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:23:30.626  6730  6730 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-24 13:23:30.626  6730  6771 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 13:23:30.636  6730  6771 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-24 13:23:30.636  6730  6771 D OpenGLRenderer: Enabling debug mode 0
08-24 13:23:30.656  1016  1497 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-24 13:23:30.666  1179  1179 I StatusBar: Icon Only
08-24 13:23:30.666  1179  1179 D PanelView: There is/are notification(s) 
08-24 13:23:30.666  1016  6776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-24 13:23:30.676  1016  1048 I ActivityManager: Displayed Component not be shown by security: +752ms (total +837ms)
08-24 13:23:30.676  1016  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2409b1c4 u0 com.test.thalitest/.MainActivity t2} time:107495
08-24 13:23:30.676  1016  1048 W ActivityManager: mDVFSHelper.release()
08-24 13:23:30.686   257  1097 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-24 13:23:30.686   257   438 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-24 13:23:30.686  6730  6730 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 13:23:30.686  6730  6730 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f4359bc time:107506
08-24 13:23:30.696  1871  1871 I SamsungIME: getCurrentCandidateView
08-24 13:23:30.736  6730  6730 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6730
08-24 13:23:30.796  1871  1871 D SamsungIME: Dismiss ExpandCandiate
08-24 13:23:30.856  6730  6730 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 13:23:30.946  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 13:23:30.986  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 13:23:30.996  1871  1871 I SamsungIME: KeybaordView init() : load resources
,08-24 13:23:30.996  6730  6775 D jxcore_app_log: JniHelper::setJavaVM(0xb7f3b2b0), pthread_self() = -1202955576
,08-24 13:23:31.006  6730  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 13:23:31.006  6730  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 13:23:31.006  6730  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 13:23:31.006  6730  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 13:23:31.006  6730  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 13:23:31.006  6730  6775 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33b5def9 added. We now have 1 listener(s)
,08-24 13:23:31.016  6730  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-24 13:23:31.016  6730  6775 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 13:23:31.016  6730  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 13:23:31.016  6730  6775 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 13:23:31.016  1871  1871 I SamsungIME: getCurrentKeyboard
,08-24 13:23:31.016  1871  1871 I SamsungIME: getTextKeyboard
,08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 13:23:31.026  6730  6775 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25eea9ec added. We now have 1 listener(s)
,08-24 13:23:31.026  6730  6775 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 13:23:31.026  6730  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 13:23:31.026  6730  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 13:23:31.026  6730  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 13:23:31.026  6730  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 13:23:31.026  6730  6775 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 13:23:31.036  6730  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 13:23:31.036  6730  6775 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-24 13:23:31.046  6730  6775 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:23:31.046  6730  6775 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 13:23:31.046  6730  6775 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 13:23:31.046  6730  6775 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 13:23:31.046  1871  1871 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-24 13:23:31.046  6730  6775 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 13:23:31.046  6730  6730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:23:31.046  6730  6730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:23:31.076  6730  6730 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 13:23:31.566  6730  6785 W jxcore-log: Initializing JXcore engine
08-24 13:23:31.566  6730  6785 W jxcore-log: JXcore engine is ready
,08-24 13:23:31.626  1996  1996 E audit   : type=1400 msg=audit(1472037811.626:205): avc:  denied  { ioctl } for  pid=6785 comm="Thread-1250" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 13:23:31.626  1996  1996 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:23:31.626  1996  1996 E audit   : type=1300 msg=audit(1472037811.626:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9f9898f8 items=0 ppid=321 ppcomm=main pid=6785 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1250" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-24 13:23:31.626  1996  1996 E audit   : type=1320 msg=audit(1472037811.626:205): 
,08-24 13:23:31.636  6730  6785 W jxcore-log: Starting JXcore engine
,08-24 13:23:31.676  1016  1312 E Watchdog: !@Sync 3
,08-24 13:23:31.746  6730  6785 W jxcore-log: Platform android
08-24 13:23:31.746  6730  6785 W jxcore-log: 
08-24 13:23:31.746  6730  6785 W jxcore-log: Process ARCH arm
08-24 13:23:31.746  6730  6785 W jxcore-log: 
,08-24 13:23:31.946  6730  6785 I jxcore-log: JXcore Cordova bridge is ready!
08-24 13:23:31.946  6730  6785 I jxcore-log: 
,08-24 13:23:31.946  6730  6785 W jxcore-log: JXcore engine is started
,08-24 13:23:31.956  6730  6775 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 13:23:31.956  6730  6730 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 13:23:32.916   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 13:23:32.916   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 13:23:33.256   292   292 E SMD     : DCD OFF,
,08-24 13:23:35.016  1016  1050 I PowerManagerService: [PWL] Off : 50s ago
,08-24 13:23:35.106  1016  3363 D SSRM:n  : SIOP:: AP = 330,
,08-24 13:23:36.256   292   292 E SMD     : DCD OFF
,08-24 13:23:37.886  5617  5617 D FactoryTest: Not factory mode
,08-24 13:23:37.886  5617  5617 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-24 13:23:37.896  5617  5617 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-24 13:23:37.896  5617  5617 D MTPRx   : still no open session command from host, so toast
,08-24 13:23:37.896  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-24 13:23:37.896  5617  5617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-24 13:23:37.896  5617  5617 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114715
,08-24 13:23:37.896  1016  1457 E PersonaManagerService: inState():  stateMachine is null !!
,08-24 13:23:37.896  1016  1457 I PersonaManagerService: PersonaId don't exist
08-24 13:23:37.896  1016  1457 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-24 13:23:37.906  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 13:23:37.906  1016  1457 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:37.906  1016  1457 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 13:23:37.906  1016  1457 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-24 13:23:37.906  1016  1457 W ActivityManager: mDVFSHelper.acquire()
,08-24 13:23:37.916   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:23:37.936  1016  1457 D PersonaManager: isKioskContainerExistOnDevice
,08-24 13:23:37.936  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 13:23:37.936  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 13:23:37.936  1016  1457 D InputDispatcher: Focused application set to: xxxx
08-24 13:23:37.936  1016  1457 D InputDispatcher: Focus left window: 6730
,08-24 13:23:37.936  5617  5617 E MTPRx   : started activity for popup
,08-24 13:23:37.946  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 13:23:37.946  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 13:23:37.966  5617  5617 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-24 13:23:37.966  5617  5617 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-24 13:23:37.966  5617  5617 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 13:23:37.966  5617  5617 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 13:23:37.966  5617  5617 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 13:23:37.966  5617  5617 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 13:23:37.996  5617  5617 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-24 13:23:38.006  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 13:23:38.006  1016  1457 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-24 13:23:38.006  1016  1457 D InputDispatcher: Focused application set to: xxxx
,08-24 13:23:38.006  1016  1457 D InputDispatcher: Focus entered window: 6730
,08-24 13:23:38.006  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 13:23:38.016  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 13:23:38.016  1016  1481 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 13:23:38.026  1016  1481 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2eb16fa7 attribute=null, token = android.os.BinderProxy@9e66ab7
,08-24 13:23:38.056  5617  5617 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-24 13:23:38.066  5617  5617 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-24 13:23:38.066  5617  5617 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-24 13:23:38.086  6730  6730 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 13:23:38.086  6730  6730 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-24 13:23:38.086  6730  6730 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 13:23:38.086  6730  6730 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-24 13:23:38.096  1016  1497 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-24 13:23:38.096  1016  1497 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 13:23:38.096  1016  1497 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 13:23:38.096  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 13:23:38.096  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 13:23:38.106  6730  6730 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 13:23:38.106  6730  6730 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 13:23:38.116  6730  6730 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3cc65e78 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@c606419, 16908290=android.view.AbsSavedState$1@c606419}, android:focusedViewId=100}]}]
08-24 13:23:38.116  6730  6730 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-24 13:23:38.116  6730  6730 V ActivityThread: updateVisibility : ActivityRecord{3854a9cb token=android.os.BinderProxy@f4359bc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-24 13:23:38.116  6730  6730 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 13:23:38.116  6730  6730 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 13:23:38.116  6730  6730 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f4359bc time:114932
,08-24 13:23:38.126  1016  1496 D PersonaManager: isKioskContainerExistOnDevice
,08-24 13:23:38.916   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:39.256   292   292 E SMD     : DCD OFF
,08-24 13:23:39.376  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:23:39.376  1016  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:23:39.376  1016  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 13:23:39.376  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:23:39.376  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:23:39.376  1016  1218 D BatteryService: stay LED for fully charged
,08-24 13:23:39.376  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:23:39.386  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:23:39.386  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:23:39.386  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:23:39.386  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:23:39.396  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:23:39.396  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:23:39.406  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:23:39.406  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:23:39.406  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:39.406  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:23:39.406  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:39.886  1016  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 13:23:39.916   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:40.906  1016  1043 W ActivityManager: mDVFSHelper.release()
,08-24 13:23:40.916   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:41.916   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:42.256   292   292 E SMD     : DCD OFF
,08-24 13:23:42.916   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-24 13:23:43.186  1016  1095 V AlarmManager: waitForAlarm result :4
,08-24 13:23:43.196  1016  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-24 13:23:43.246  2024  2024 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos,
,08-24 13:23:43.276  1016  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 13:23:43.276  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-24 13:23:43.276  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:43.276  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:43.276  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.326  4808  4808 D ConnectivityManager: CallingUid : 10011, CallingPid : 4808
,08-24 13:23:43.326  1016  1457 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 13:23:43.326  1016  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-24 13:23:43.326  1016  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-24 13:23:43.326  1016  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-24 13:23:43.326  4808  6794 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-24 13:23:43.386  4808  6795 W DriveInitializer: Background init thread started
,08-24 13:23:43.416   256   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-24 13:23:43.416   256   535 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 13:23:43.416  4808  6795 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-24 13:23:43.466  2024  2024 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-24 13:23:43.506  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 13:23:43.506  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-24 13:23:43.506  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:43.516  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 13:23:43.516  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.526  4808  6795 W DriveInitializer: Background init thread ended
,08-24 13:23:43.546  1016  1325 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-24 13:23:43.546  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-24 13:23:43.616  2024  2024 I art     : Explicit concurrent mark sweep GC freed 59225(3MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 10MB/17MB, paused 1.565ms total 79.507ms
,08-24 13:23:43.636  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 13:23:43.636  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-24 13:23:43.636  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:23:43.636  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:43.636  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.646  4808  6803 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-24 13:23:43.646  4808  6803 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-24 13:23:43.696  2024  2024 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:23:43.736  1016  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:43.736  1016  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:43.736  1016  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.806  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 13:23:43.806  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-24 13:23:43.816  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:23:43.816  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 13:23:43.816  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.846  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 13:23:43.846  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-24 13:23:43.846  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:43.846  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:43.846  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.906  1016  1139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:43.906  1016  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:43.906  1016  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:43.906  1016  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.926  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:43.926  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:43.926  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:43.926  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.966  1016  3173 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:43.976  1016  3173 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:43.976  1016  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:43.976  1016  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:43.976  1016  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 13:23:43.976  1016  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 13:23:43.976  1016  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 13:23:43.976  1016  3173 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-24 13:23:43.986  1016  3173 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6807 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-24 13:23:43.996  6807  6807 E Zygote  : MountEmulatedStorage()
08-24 13:23:43.996  6807  6807 E Zygote  : v2
08-24 13:23:43.996  6807  6807 I libpersona: KNOX_SDCARD checking this for 10011
08-24 13:23:43.996  6807  6807 I libpersona: KNOX_SDCARD not a persona
,08-24 13:23:43.996  6807  6807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 13:23:43.996  6807  6807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 13:23:43.996  6807  6807 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 13:23:44.026  6807  6807 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 13:23:44.026  6807  6807 D ActivityThread: Added TimaKeyStore provider
,08-24 13:23:44.056  6807  6807 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 13:23:44.056  6807  6807 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-24 13:23:44.096  6807  6807 I MultiDex: VM with version 2.1.0 has multidex support
,08-24 13:23:44.096  6807  6807 I MultiDex: install
08-24 13:23:44.096  6807  6807 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 13:23:44.136  6807  6807 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-24 13:23:44.196  6807  6807 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
08-24 13:23:44.196  6807  6807 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2f4a3897: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-24 13:23:44.196  6807  6807 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 13:23:44.226  6807  6807 D ChimeraCfgMgr: Reading stored module config
,08-24 13:23:44.226  1016  1457 I art     : Explicit concurrent mark sweep GC freed 37545(1991KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.560ms total 155.406ms
,08-24 13:23:44.306  6730  6785 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 13:23:44.306  6730  6785 I jxcore-log: 
,08-24 13:23:44.306  6730  6785 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 13:23:44.306  6730  6785 I jxcore-log: 
,08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:23:44.316  6730  6785 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 13:23:44.316  6730  6785 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 13:23:44.316  6730  6785 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 13:23:44.316  6730  6785 I jxcore-log: 
,08-24 13:23:44.326  6730  6785 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 13:23:44.326  6730  6785 I jxcore-log: 
,08-24 13:23:44.336  6807  6825 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-24 13:23:44.346  6807  6807 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-24 13:23:44.346  6807  6807 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-24 13:23:44.426   285   285 D WVCdm   : Instantiating CDM.
,08-24 13:23:44.426   285   694 I WVCdm   : CdmEngine::OpenSession
,08-24 13:23:44.426   285   694 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-24 13:23:44.476   285   694 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-24 13:23:44.496   285   694 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-24 13:23:44.496  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-24 13:23:44.506  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:44.506  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:44.506  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:44.506  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:44.526  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:44.526  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:23:44.526  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:44.526  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:44.536  6807  6816 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-24 13:23:44.536  6807  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:44.536  6807  6816 I System.out: (HTTPLog)-Static: isShipBuild true
08-24 13:23:44.536  6807  6816 I System.out: (HTTPLog)-Thread-1224-436324360: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-24 13:23:44.536  6807  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:44.536   277   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 13:23:44.536   277   968 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:23:44.556   285   694 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-24 13:23:44.556   285   686 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-24 13:23:44.556   285   686 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-24 13:23:44.556   285   686 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-24 13:23:44.556   285   686 D WVCdm   : PrepareKeyRequest: nonce=4023928123
,08-24 13:23:44.566  2024  2024 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=68106902-0192-4228-b5e0-c4ee40e41b14
,08-24 13:23:44.576  1016  3173 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-24 13:23:44.576  1016  3173 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-24 13:23:44.586  1016  3173 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:23:44.586  1016  3173 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:44.586  1016  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:44.586  2024  2024 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:23:44.596  2024  2024 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:23:44.596  6807  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 13:23:44.596  6807  6816 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6807, getuid(): 10011
,08-24 13:23:44.626  4314  5055 I art     : Explicit concurrent mark sweep GC freed 1456(50KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 680us total 23.951ms
,08-24 13:23:44.636  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:44.646  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:44.646  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:44.646  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:44.776  2024  2194 W GCoreFlp: No location to return for getLastLocation()
,08-24 13:23:44.806  1016  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:44.806  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:44.806  1016  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:44.806  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:44.816  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:44.816  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:23:44.816  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:44.816  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:44.816  1016  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:44.816  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:23:44.816  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:44.816  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:44.836  2024  2210 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 13:23:44.846  4808  6804 D UdcContextInitService: registered all accounts: true
,08-24 13:23:44.856  2024  2224 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-24 13:23:44.866  6807  6816 I qtaguid : Untagging socket 30
,08-24 13:23:45.096  1016  1218 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-24 13:23:45.096  1016  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-24 13:23:45.096  1016  1218 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:23:45.096  1016  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:45.096  1016  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:45.116  6730  6785 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-24 13:23:45.126  6730  6785 I jxcore-log: Failed to execute UT.
08-24 13:23:45.126  6730  6785 I jxcore-log: 
08-24 13:23:45.126  6730  6785 I jxcore-log: Unit Test app is loaded
08-24 13:23:45.126  6730  6785 I jxcore-log: 
08-24 13:23:45.126  1016  3363 D SSRM:n  : SIOP:: AP = 340
,08-24 13:23:45.126  6730  6785 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 13:23:45.126  6730  6785 I jxcore-log: 
,08-24 13:23:45.136  6730  6730 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 13:23:45.146  6730  6785 I jxcore-log: My device name is: samsung-SM-A300FU
08-24 13:23:45.146  6730  6785 I jxcore-log: 
,08-24 13:23:45.266   292   292 E SMD     : DCD OFF
,08-24 13:23:45.336  6837  6837 I dex2oat : ----------------------------------------------------
08-24 13:23:45.336  6837  6837 I dex2oat : <SS>: S T A R T I N G . . .
08-24 13:23:45.336  6837  6837 I dex2oat : <SS>: Zip is absent. Canceled.
,08-24 13:23:45.336  6837  6837 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-24 13:23:45.386  6837  6837 I dex2oat : dex2oat took 44.944ms (threads: 4),
,08-24 13:23:45.396  6807  6816 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 13:23:45.396  6807  6816 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 13:23:45.396  6807  6816 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 13:23:45.396  6807  6816 I Adreno-EGL: Local Branch: 
08-24 13:23:45.396  6807  6816 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 13:23:45.396  6807  6816 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 13:23:45.396  6807  6816 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 13:23:45.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:23:45.516  6807  6816 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 13:23:45.516  6807  6816 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 13:23:45.516  6807  6816 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 13:23:45.516  6807  6816 I Adreno-EGL: Local Branch: 
08-24 13:23:45.516  6807  6816 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 13:23:45.516  6807  6816 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 13:23:45.516  6807  6816 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 13:23:45.556  6807  6816 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 13:23:45.556  6807  6816 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 13:23:45.556  6807  6816 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 13:23:45.556  6807  6816 I Adreno-EGL: Local Branch: 
08-24 13:23:45.556  6807  6816 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 13:23:45.556  6807  6816 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 13:23:45.556  6807  6816 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 13:23:45.866  1016  1028 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-24 13:23:45.866  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-24 13:23:45.866  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:45.866  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:45.866  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:45.896  2024  6806 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-24 13:23:45.896  2024  6806 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:45.896  2024  6806 I System.out: (HTTPLog)-Static: isShipBuild true
,08-24 13:23:45.896  2024  6806 I System.out: (HTTPLog)-Thread-271-746256130: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-24 13:23:45.896  2024  6806 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:45.906   277   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 13:23:45.906   277   968 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:23:45.906  2024  6806 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 13:23:45.906  2024  6806 I qtaguid : Tagging socket 57 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2024, getuid(): 10011
,08-24 13:23:45.966  2024  6806 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2024, getuid(): 10011
,08-24 13:23:46.156   285   285 I WVCdm   : CdmEngine::CloseSession,
08-24 13:23:46.156   285   285 I WVCdm   : L3 Terminate.
,08-24 13:23:46.266  2024  2224 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 13:23:46.276  2024  2224 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-24 13:23:46.286  2024  2224 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-24 13:23:45.012+0200, stopTime=2016-08-24 13:23:46.301+0200, duration=1289ms
,08-24 13:23:46.296  2024  6848 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:46.296   277   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 13:23:46.296   277   968 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:23:46.306  2024  6848 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 13:23:46.306  2024  6848 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2024, getuid(): 10011
,08-24 13:23:46.346  2024  6848 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2024, getuid(): 10011
,08-24 13:23:46.376  2024  2224 I art     : Explicit concurrent mark sweep GC freed 56480(3MB) AllocSpace objects, 8(270KB) LOS objects, 39% free, 11MB/18MB, paused 1.431ms total 77.260ms
,08-24 13:23:46.406  1016  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-24 13:23:46.616  2024  6848 I qtaguid : Untagging socket 65
,08-24 13:23:46.646  1016  1325 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 13:23:46.646  1016  1325 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-24 13:23:46.646  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.646  1016  1325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.646  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.676  2024  2224 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-24 13:23:46.736  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:46.736  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.736  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.736  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.766  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:46.766  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.766  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.766  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.816  1016  1325 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:46.816  1016  1325 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.816  1016  1325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.816  1016  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.816  2024  6856 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 13:23:46.816  2024  6854 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 13:23:46.816  1016  1457 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:46.816  1016  1457 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.816  1016  1457 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.816  1016  1457 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.846  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:46.846  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.846  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.846  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.846  2024  6856 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 13:23:46.846  2024  6854 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 13:23:46.846  1016  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:46.846  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.846  1016  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.846  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.876  1016  1139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:23:46.876  1016  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:23:46.876  1016  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:23:46.876  1016  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:23:46.876  2024  6856 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-24 13:23:46.876  2024  6854 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-24 13:23:46.876  2024  6854 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-24 13:23:46.886  2024  6854 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 13:23:46.936  1016  1457 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:23:46.976  2024  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:46.976   277   968 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 13:23:46.976   277   968 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-24 13:23:46.976  2024  6854 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 13:23:46.976  2024  6854 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2024, getuid(): 10011
,08-24 13:23:47.026  2024  6854 I qtaguid : Tagging socket 80 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2024, getuid(): 10011
,08-24 13:23:47.346  1016  1496 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:23:47.356  2024  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:47.356  2024  6854 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2024, getuid(): 10011
,08-24 13:23:47.496  1016  1481 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:23:47.506  2024  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:47.506  2024  6854 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2024, getuid(): 10011
,08-24 13:23:47.636  1016  1496 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-24 13:23:47.646  2024  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:47.646  2024  6854 I qtaguid : Tagging socket 77 with tag 11065b5800000000{285629272,0} for uid -1, pid: 2024, getuid(): 10011
,08-24 13:23:47.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:48.266   292   292 E SMD     : DCD OFF
,08-24 13:23:48.476  2024  6849 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 13:23:48.486  2024  6849 I qtaguid : Tagging socket 65 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2024, getuid(): 10011
,08-24 13:23:48.646  2024  6849 I qtaguid : Untagging socket 65
,08-24 13:23:48.656  2024  2224 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-24 13:23:48.676  1016  1457 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-24 13:23:48.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:49.426  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 13:23:49.426  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:23:49.426  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:23:49.426  1016  1028 D BatteryService: stay LED for fully charged,
,08-24 13:23:49.426  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:23:49.436  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:23:49.436  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:23:49.436  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:23:49.436  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-24 13:23:49.436  1016  1016 I MotionRecognitionService: Plugged
08-24 13:23:49.436  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:23:49.436  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:23:49.436  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:23:49.446  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:23:49.446  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:23:49.456  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:49.456  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:49.456  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:49.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:50.486  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-24 13:23:50.486  6730  6785 I jxcore-log: 
,08-24 13:23:50.846  1016  1479 I ActivityManager: Killing 6403:com.samsung.helphub/1000 (adj 15): empty #21
,08-24 13:23:50.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:23:51.266   292   292 E SMD     : DCD OFF,
,08-24 13:23:51.636  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-24 13:23:51.636  6730  6785 I jxcore-log: 
,08-24 13:23:51.666  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
08-24 13:23:51.666  6730  6785 I jxcore-log: 
,08-24 13:23:51.676  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
08-24 13:23:51.676  6730  6785 I jxcore-log: 
,08-24 13:23:51.696  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
08-24 13:23:51.696  6730  6785 I jxcore-log: 
,08-24 13:23:51.696  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-24 13:23:51.696  6730  6785 I jxcore-log: 
,08-24 13:23:51.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:23:52.926   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-24 13:23:54.266   292   292 E SMD     : DCD OFF
,08-24 13:23:55.166  1016  3363 D SSRM:n  : SIOP:: AP = 350
,08-24 13:23:55.696  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 13:23:55.696  6730  6785 I jxcore-log: 
,08-24 13:23:55.716  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 13:23:55.716  6730  6785 I jxcore-log: 
,08-24 13:23:55.726  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 13:23:55.726  6730  6785 I jxcore-log: 
,08-24 13:23:55.936  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 13:23:55.936  6730  6785 I jxcore-log: 
,08-24 13:23:56.956  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 13:23:56.956  6730  6785 I jxcore-log: 
,08-24 13:23:57.266  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 13:23:57.266  6730  6785 I jxcore-log: 
,08-24 13:23:57.266   292   292 E SMD     : DCD OFF,
,08-24 13:23:57.276  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 13:23:57.276  6730  6785 I jxcore-log: 
,08-24 13:23:57.526  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
08-24 13:23:57.526  6730  6785 I jxcore-log: 
,08-24 13:23:57.546  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
08-24 13:23:57.546  6730  6785 I jxcore-log: 
,08-24 13:23:57.556  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
08-24 13:23:57.556  6730  6785 I jxcore-log: 
,08-24 13:23:57.566  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
08-24 13:23:57.566  6730  6785 I jxcore-log: 
,08-24 13:23:57.576  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
08-24 13:23:57.576  6730  6785 I jxcore-log: 
,08-24 13:23:57.606  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
08-24 13:23:57.606  6730  6785 I jxcore-log: 
,08-24 13:23:57.706  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
08-24 13:23:57.706  6730  6785 I jxcore-log: 
,08-24 13:23:57.716  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
08-24 13:23:57.716  6730  6785 I jxcore-log: 
,08-24 13:23:57.746  6730  6785 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
08-24 13:23:57.746  6730  6785 I jxcore-log: 
,08-24 13:23:57.756  6730  6785 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED,
08-24 13:23:57.756  6730  6785 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 13:23:57.756  6730  6785 I jxcore-log: 
,08-24 13:23:59.496  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:23:59.496  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:23:59.496  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:23:59.496  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:23:59.496  1016  1497 D BatteryService: stay LED for fully charged
,08-24 13:23:59.496  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:23:59.496  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
,08-24 13:23:59.506  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:23:59.506  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:23:59.506  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:23:59.506  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:23:59.516  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 13:23:59.516  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:23:59.526  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:23:59.526  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:23:59.536  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:59.536  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:59.536  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:23:59.986  1016  1095 V AlarmManager: waitForAlarm result :8
,08-24 13:24:00.026  1016  1050 I PowerManagerService: [PWL] Off : 75s ago
,08-24 13:24:00.266   292   292 E SMD     : DCD OFF,
,08-24 13:24:01.676  1016  1312 E Watchdog: !@Sync 4,
,08-24 13:24:02.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:24:03.266   292   292 E SMD     : DCD OFF
,08-24 13:24:03.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:04.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:05.196  1016  3363 D SSRM:n  : SIOP:: AP = 330
,08-24 13:24:05.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:24:05.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:06.086  1016  2078 V SAMP_SPCM_test: CSC File load.. 
,08-24 13:24:06.096  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-24 13:24:06.096  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-24 13:24:06.096  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-24 13:24:06.096  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-24 13:24:06.096  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-24 13:24:06.096  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,08-24 13:24:06.096  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering,
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn,
08-24 13:24:06.106  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-24 13:24:06.146  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-24 13:24:06.156  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-24 13:24:06.156  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-24 13:24:06.156  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-24 13:24:06.156  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-24 13:24:06.156  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory,
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming,
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email,
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-24 13:24:06.166  1016  2078 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-24 13:24:06.196  1016  2078 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-24 13:24:06.276   292   292 E SMD     : DCD OFF
,08-24 13:24:06.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:07.926   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-24 13:24:09.276   292   292 E SMD     : DCD OFF
,08-24 13:24:09.556  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:12.276   292   292 E SMD     : DCD OFF
,08-24 13:24:15.216  1016  3363 D SSRM:n  : SIOP:: AP = 310
,08-24 13:24:15.276   292   292 E SMD     : DCD OFF
,08-24 13:24:18.276   292   292 E SMD     : DCD OFF
,08-24 13:24:19.626  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:21.276   292   292 E SMD     : DCD OFF
,08-24 13:24:22.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:23.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:24.276   292   292 E SMD     : DCD OFF
,08-24 13:24:24.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:25.236  1016  3363 D SSRM:n  : SIOP:: AP = 300,
,08-24 13:24:25.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:24:25.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:26.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:27.276   292   292 E SMD     : DCD OFF
,08-24 13:24:27.926   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-24 13:24:29.686  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:30.056  1016  1050 I PowerManagerService: [PWL] Off : 105s ago
,08-24 13:24:30.286   292   292 E SMD     : DCD OFF,
,08-24 13:24:31.676  1016  1312 E Watchdog: !@Sync 5,
,08-24 13:24:31.856  2024  3103 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:24:32.256  4808  5166 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:24:33.286   292   292 E SMD     : DCD OFF
,08-24 13:24:35.276  1016  3363 D SSRM:n  : SIOP:: AP = 300,
,08-24 13:24:36.286   292   292 E SMD     : DCD OFF
,08-24 13:24:39.286   292   292 E SMD     : DCD OFF
,08-24 13:24:39.756  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:42.286   292   292 E SMD     : DCD OFF
,08-24 13:24:45.286   292   292 E SMD     : DCD OFF
,08-24 13:24:45.316  1016  3363 D SSRM:n  : SIOP:: AP = 300,
,08-24 13:24:45.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:24:47.926   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:48.286   292   292 E SMD     : DCD OFF
,08-24 13:24:48.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:49.816  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:24:49.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:50.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:51.286   292   292 E SMD     : DCD OFF
,08-24 13:24:51.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:24:52.936   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-24 13:24:54.296   292   292 E SMD     : DCD OFF
,08-24 13:24:55.336  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:24:57.296   292   292 E SMD     : DCD OFF
,08-24 13:24:59.876  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:00.296   292   292 E SMD     : DCD OFF
,08-24 13:25:01.676  1016  1312 E Watchdog: !@Sync 6,
,08-24 13:25:03.146  1016  1095 V AlarmManager: waitForAlarm result :4
,08-24 13:25:03.146  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:25:03.146  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:25:03.166  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:25:03.166  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:25:03.176  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:25:03.176  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-24 13:25:03.176  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-24 13:25:03.176  1179  1179 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-24 13:25:03.216  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:25:03.216  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:25:03.226  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:25:03.246  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:25:03.296   292   292 E SMD     : DCD OFF
,08-24 13:25:05.056  1016  1050 I PowerManagerService: [PWL] Off : 140s ago
,08-24 13:25:05.356  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:25:05.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:25:06.296   292   292 E SMD     : DCD OFF
,08-24 13:25:09.296   292   292 E SMD     : DCD OFF
,08-24 13:25:09.946  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:12.296   292   292 E SMD     : DCD OFF
,08-24 13:25:15.296   292   292 E SMD     : DCD OFF
,08-24 13:25:15.376  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:25:17.936   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 13:25:17.936   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 13:25:18.306   292   292 E SMD     : DCD OFF
,08-24 13:25:20.016  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:25:21.306   292   292 E SMD     : DCD OFF
,08-24 13:25:24.306   292   292 E SMD     : DCD OFF
,08-24 13:25:25.416  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:25:25.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:25:27.306   292   292 E SMD     : DCD OFF
,08-24 13:25:27.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:28.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:29.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:30.076  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:25:30.306   292   292 E SMD     : DCD OFF
,08-24 13:25:30.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:31.676  1016  1312 E Watchdog: !@Sync 7
,08-24 13:25:31.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:32.936   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-24 13:25:33.306   292   292 E SMD     : DCD OFF
,08-24 13:25:35.446  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:25:36.306   292   292 E SMD     : DCD OFF
,08-24 13:25:37.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:38.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:39.316   292   292 E SMD     : DCD OFF
,08-24 13:25:39.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:25:40.146  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:40.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:41.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:42.316   292   292 E SMD     : DCD OFF
,08-24 13:25:42.936   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-24 13:25:45.056  1016  1050 I PowerManagerService: [PWL] Off : 180s ago
,08-24 13:25:45.316   292   292 E SMD     : DCD OFF
,08-24 13:25:45.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:25:45.486  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:25:48.316   292   292 E SMD     : DCD OFF
,08-24 13:25:50.206  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:25:51.316   292   292 E SMD     : DCD OFF
,08-24 13:25:52.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:53.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:54.316   292   292 E SMD     : DCD OFF
,08-24 13:25:54.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:55.506  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:25:55.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:25:56.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:25:57.316   292   292 E SMD     : DCD OFF
,08-24 13:25:57.936   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-24 13:25:59.986  1016  1095 V AlarmManager: waitForAlarm result :8
,08-24 13:26:00.266  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:00.316   292   292 E SMD     : DCD OFF
,08-24 13:26:01.676  1016  1312 E Watchdog: !@Sync 8
,08-24 13:26:03.326   292   292 E SMD     : DCD OFF
,08-24 13:26:05.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:26:05.526  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:26:06.326   292   292 E SMD     : DCD OFF
,08-24 13:26:09.326   292   292 E SMD     : DCD OFF
,08-24 13:26:10.326  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:26:12.326   292   292 E SMD     : DCD OFF
,08-24 13:26:12.936   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:13.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:14.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:15.326   292   292 E SMD     : DCD OFF,
,08-24 13:26:15.556  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:26:15.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:16.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:17.946   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-24 13:26:18.326   292   292 E SMD     : DCD OFF
,08-24 13:26:20.396  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:21.326   292   292 E SMD     : DCD OFF
,08-24 13:26:24.336   292   292 E SMD     : DCD OFF
,08-24 13:26:25.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:26:25.586  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:26:27.336   292   292 E SMD     : DCD OFF
,08-24 13:26:30.106  1016  1050 I PowerManagerService: [PWL] Off : 225s ago
,08-24 13:26:30.336   292   292 E SMD     : DCD OFF
,08-24 13:26:30.456  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:31.676  1016  1312 E Watchdog: !@Sync 9
,08-24 13:26:33.336   292   292 E SMD     : DCD OFF
,08-24 13:26:35.606  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:26:36.336   292   292 E SMD     : DCD OFF
,08-24 13:26:37.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:38.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:39.336   292   292 E SMD     : DCD OFF
,08-24 13:26:39.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:40.526  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:26:40.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:26:41.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:26:42.336   292   292 E SMD     : DCD OFF
,08-24 13:26:42.946   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-24 13:26:45.346   292   292 E SMD     : DCD OFF
,08-24 13:26:45.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:26:45.626  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:26:48.346   292   292 E SMD     : DCD OFF
,08-24 13:26:50.586  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:26:51.346   292   292 E SMD     : DCD OFF
,08-24 13:26:54.346   292   292 E SMD     : DCD OFF
,08-24 13:26:55.656  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:26:57.346   292   292 E SMD     : DCD OFF
,08-24 13:26:58.956  1016  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:26:58.956  1016  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:26:58.956  1016  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:26:58.966  1016  1086 I TLC_TIMA_PKM_initialize: initializing...
,08-24 13:26:58.966  1016  1086 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-24 13:26:58.966  1016  1086 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
08-24 13:26:58.966  1016  1086 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-24 13:26:58.966  1016  1086 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
08-24 13:26:58.966  1016  1086 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
08-24 13:26:58.966  1016  1086 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-24 13:26:58.966  1016  1086 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
08-24 13:26:58.966  1016  1086 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
08-24 13:26:58.966  1016  1086 D QSEECOMAPI: : App is not loaded in QSEE
,08-24 13:26:58.986  1016  1086 D QSEECOMAPI: : Loaded image: APP id = 12
,08-24 13:26:58.996  1016  1086 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-24 13:26:59.006  1016  1086 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-24 13:27:00.346   292   292 E SMD     : DCD OFF
,08-24 13:27:00.656  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:00.656  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:27:00.656  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:27:00.656  1016  1497 D BatteryService: stay LED for fully charged
08-24 13:27:00.656  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:27:00.656  1016  1016 I MotionRecognitionService: Plugged
08-24 13:27:00.656  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:27:00.656  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:27:00.656  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:27:00.656  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:27:00.656  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:27:00.666  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-24 13:27:00.666  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:27:00.676  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:27:00.676  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:27:00.686  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:00.686  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:27:00.686  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:27:00.906  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:27:00.906  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:27:00.906  1016  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:27:00.906  1016  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:27:01.676  1016  1312 E Watchdog: !@Sync 10
,08-24 13:27:03.346   292   292 E SMD     : DCD OFF
,08-24 13:27:05.476  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:27:05.686  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:27:06.346   292   292 E SMD     : DCD OFF
,08-24 13:27:07.946   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 13:27:07.946   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 13:27:09.356   292   292 E SMD     : DCD OFF
,08-24 13:27:10.716  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:27:12.356   292   292 E SMD     : DCD OFF
,08-24 13:27:15.356   292   292 E SMD     : DCD OFF
,08-24 13:27:15.706  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:27:18.356   292   292 E SMD     : DCD OFF
,08-24 13:27:20.106  1016  1050 I PowerManagerService: [PWL] Off : 275s ago
,08-24 13:27:20.786  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:21.356   292   292 E SMD     : DCD OFF
,08-24 13:27:22.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:23.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:24.356   292   292 E SMD     : DCD OFF
,08-24 13:27:24.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:27:25.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:27:25.736  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:27:25.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:27:26.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:27:27.356   292   292 E SMD     : DCD OFF
,08-24 13:27:27.946   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-24 13:27:30.356   292   292 E SMD     : DCD OFF
,08-24 13:27:30.846  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:31.676  1016  1312 E Watchdog: !@Sync 11
,08-24 13:27:32.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:33.366   292   292 E SMD     : DCD OFF
,08-24 13:27:33.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:34.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:35.766  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:27:35.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:27:36.366   292   292 E SMD     : DCD OFF
,08-24 13:27:36.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:27:37.946   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-24 13:27:39.366   292   292 E SMD     : DCD OFF
,08-24 13:27:40.916  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:27:42.366   292   292 E SMD     : DCD OFF
,08-24 13:27:43.426  5825  5895 I PlayCommon: [1024] com.google.android.play.a.al.e(730): Preparing logs for uploading,
08-24 13:27:43.426  5825  5895 I PlayCommon: [1024] com.google.android.play.a.al.e(732): No file ready to send
,08-24 13:27:45.366   292   292 E SMD     : DCD OFF
,08-24 13:27:45.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:27:45.796  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:27:47.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:48.366   292   292 E SMD     : DCD OFF
,08-24 13:27:48.946   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:49.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:50.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:50.976  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:27:51.366   292   292 E SMD     : DCD OFF
,08-24 13:27:51.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:27:52.956   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-24 13:27:54.366   292   292 E SMD     : DCD OFF
,08-24 13:27:55.836  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:27:57.376   292   292 E SMD     : DCD OFF
,08-24 13:28:00.376   292   292 E SMD     : DCD OFF
,08-24 13:28:01.046  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:28:01.686  1016  1312 E Watchdog: !@Sync 12
,08-24 13:28:03.376   292   292 E SMD     : DCD OFF
,08-24 13:28:05.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:28:05.856  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:28:06.376   292   292 E SMD     : DCD OFF
,08-24 13:28:07.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:08.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:28:09.376   292   292 E SMD     : DCD OFF
,08-24 13:28:09.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:28:10.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:11.106  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:28:11.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:12.376   292   292 E SMD     : DCD OFF
,08-24 13:28:12.956   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-24 13:28:15.106  1016  1050 I PowerManagerService: [PWL] Off : 330s ago
,08-24 13:28:15.376   292   292 E SMD     : DCD OFF
,08-24 13:28:15.876  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:28:18.386   292   292 E SMD     : DCD OFF
,08-24 13:28:21.176  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:28:21.386   292   292 E SMD     : DCD OFF
,08-24 13:28:24.386   292   292 E SMD     : DCD OFF
,08-24 13:28:25.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:28:25.896  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:28:27.386   292   292 E SMD     : DCD OFF
,08-24 13:28:30.386   292   292 E SMD     : DCD OFF
,08-24 13:28:31.236  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:28:31.236  1016  1457 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:28:31.236  1016  1457 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:28:31.236  1016  1457 D BatteryService: stay LED for fully charged
08-24 13:28:31.236  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:28:31.236  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:28:31.236  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:28:31.246  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:28:31.246  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:28:31.256  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:28:31.256  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:28:31.266  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:28:31.266  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:28:31.276  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:28:31.276  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:28:31.276  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:28:31.276  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:28:31.276  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:31.686  1016  1312 E Watchdog: !@Sync 13
,08-24 13:28:32.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:33.386   292   292 E SMD     : DCD OFF
,08-24 13:28:33.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:34.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:35.916  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:28:35.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:36.386   292   292 E SMD     : DCD OFF
,08-24 13:28:36.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:28:37.956   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-24 13:28:39.386   292   292 E SMD     : DCD OFF
,08-24 13:28:41.296  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:28:41.296  1016  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:28:41.296  1016  1325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:28:41.296  1016  1325 D BatteryService: stay LED for fully charged
08-24 13:28:41.296  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:28:41.306  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:28:41.306  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:28:41.306  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:28:41.306  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:28:41.306  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:28:41.306  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:28:41.326  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:28:41.326  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:28:41.336  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:28:41.336  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:28:41.336  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:41.336  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:28:41.336  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:28:42.396   292   292 E SMD     : DCD OFF
,08-24 13:28:45.396   292   292 E SMD     : DCD OFF
,08-24 13:28:45.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:28:45.946  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:28:48.396   292   292 E SMD     : DCD OFF
,08-24 13:28:51.366  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:28:51.396   292   292 E SMD     : DCD OFF,
,08-24 13:28:54.396   292   292 E SMD     : DCD OFF
,08-24 13:28:55.976  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:28:57.396   292   292 E SMD     : DCD OFF
,08-24 13:28:59.986  1016  1095 V AlarmManager: waitForAlarm result :8
,08-24 13:28:59.986  1016  1095 V AlarmManager: No more alarm at this time.nowELAPSED=436806 batch.start=1055671
,08-24 13:28:59.996  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:28:59.996  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:28:59.996  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:28:59.996  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:29:00.026  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:29:00.026  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-24 13:29:00.026  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-24 13:29:00.036  1179  1179 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-24 13:29:00.056  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:29:00.056  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:29:00.076  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:29:00.126  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:29:00.396   292   292 E SMD     : DCD OFF
,08-24 13:29:01.426  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:29:01.686  1016  1312 E Watchdog: !@Sync 14
,08-24 13:29:02.956   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 13:29:02.956   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 13:29:03.406   292   292 E SMD     : DCD OFF
,08-24 13:29:05.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:29:06.006  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:29:06.406   292   292 E SMD     : DCD OFF
,08-24 13:29:09.406   292   292 E SMD     : DCD OFF
,08-24 13:29:11.496  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:29:11.496  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:29:11.496  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:29:11.496  1016  1029 D BatteryService: stay LED for fully charged
08-24 13:29:11.496  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:29:11.496  1016  1016 I MotionRecognitionService: Plugged
08-24 13:29:11.496  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:29:11.496  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:29:11.496  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:29:11.496  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:29:11.506  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-24 13:29:11.506  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 13:29:11.506  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:29:11.526  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:29:11.526  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:29:11.526  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:29:11.526  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:11.526  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:12.406   292   292 E SMD     : DCD OFF
,08-24 13:29:15.106  1016  1050 I PowerManagerService: [PWL] Off : 390s ago
,08-24 13:29:15.406   292   292 E SMD     : DCD OFF
,08-24 13:29:16.026  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:29:18.406   292   292 E SMD     : DCD OFF
,08-24 13:29:21.406   292   292 E SMD     : DCD OFF
,08-24 13:29:21.556  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:29:21.556  1016  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:29:21.556  1016  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:29:21.556  1016  1481 D BatteryService: stay LED for fully charged
,08-24 13:29:21.556  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:29:21.566  1016  1016 I MotionRecognitionService: Plugged,
,08-24 13:29:21.566  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:29:21.566  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:29:21.566  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-24 13:29:21.566  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:29:21.566  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:29:21.576  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:29:21.576  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:29:21.586  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:29:21.586  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:29:21.586  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:29:21.586  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:29:21.586  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:22.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:23.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:24.416   292   292 E SMD     : DCD OFF
,08-24 13:29:24.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:25.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:29:25.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:26.076  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:29:26.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:27.416   292   292 E SMD     : DCD OFF
,08-24 13:29:27.956   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-24 13:29:30.416   292   292 E SMD     : DCD OFF
,08-24 13:29:31.616  1016  3173 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 13:29:31.616  1016  3173 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:29:31.616  1016  3173 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:29:31.616  1016  3173 D BatteryService: stay LED for fully charged
08-24 13:29:31.616  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 13:29:31.626  1016  1016 I MotionRecognitionService: Plugged
08-24 13:29:31.626  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:29:31.626  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:29:31.626  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:29:31.626  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:29:31.626  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:29:31.626  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:29:31.626  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:29:31.646  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-24 13:29:31.646  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:29:31.646  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:29:31.646  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:29:31.646  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:29:31.686  1016  1312 E Watchdog: !@Sync 15
,08-24 13:29:32.956   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:33.416   292   292 E SMD     : DCD OFF
,08-24 13:29:33.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:34.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:35.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:36.106  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:29:36.416   292   292 E SMD     : DCD OFF
,08-24 13:29:36.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:37.966   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-24 13:29:39.416   292   292 E SMD     : DCD OFF
,08-24 13:29:41.686  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:29:42.416   292   292 E SMD     : DCD OFF
,08-24 13:29:45.416   292   292 E SMD     : DCD OFF
,08-24 13:29:45.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:29:46.126  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:29:47.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:48.426   292   292 E SMD     : DCD OFF
,08-24 13:29:48.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:49.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:50.536   328   328 I bootchecker: bootchecker wake up!!
,08-24 13:29:50.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:29:51.426   292   292 E SMD     : DCD OFF,
,08-24 13:29:51.746  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:29:51.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:29:52.966   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-24 13:29:54.426   292   292 E SMD     : DCD OFF
,08-24 13:29:56.136  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:29:57.426   292   292 E SMD     : DCD OFF
,08-24 13:29:59.986  1016  1095 V AlarmManager: waitForAlarm result :8
,08-24 13:30:00.426   292   292 E SMD     : DCD OFF
,08-24 13:30:01.686  1016  1312 E Watchdog: !@Sync 16,
,08-24 13:30:01.806  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:30:01.806  1016  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:30:01.806  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:30:01.806  1016  1496 D BatteryService: stay LED for fully charged
,08-24 13:30:01.806  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:30:01.816  1016  1016 I MotionRecognitionService: Plugged
08-24 13:30:01.816  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:30:01.816  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:30:01.816  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:30:01.816  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:30:01.816  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:30:01.826  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:30:01.826  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:30:01.836  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:30:01.836  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:30:01.836  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:30:01.836  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:30:01.846  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:30:03.426   292   292 E SMD     : DCD OFF
,08-24 13:30:05.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:30:06.156  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:30:06.426   292   292 E SMD     : DCD OFF
,08-24 13:30:07.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:08.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:09.436   292   292 E SMD     : DCD OFF
,08-24 13:30:09.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:10.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:11.876  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:30:11.876  1016  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:30:11.876  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:30:11.876  1016  1496 D BatteryService: stay LED for fully charged
,08-24 13:30:11.876  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:30:11.876  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:30:11.876  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:30:11.886  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:30:11.886  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:30:11.886  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:30:11.886  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:30:11.896  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:30:11.896  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:30:11.906  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:30:11.906  1179  1179 D SViewCoverView: level :100 plugged : 2,
08-24 13:30:11.906  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:30:11.906  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:30:11.906  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:30:11.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 13:30:12.436   292   292 E SMD     : DCD OFF
,08-24 13:30:12.966   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-24 13:30:15.436   292   292 E SMD     : DCD OFF
,08-24 13:30:16.166  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:30:18.436   292   292 E SMD     : DCD OFF
,08-24 13:30:20.106  1016  1050 I PowerManagerService: [PWL] Off : 455s ago
,08-24 13:30:21.436   292   292 E SMD     : DCD OFF
,08-24 13:30:21.936  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:30:24.436   292   292 E SMD     : DCD OFF
,08-24 13:30:25.486  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:30:26.186  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:30:27.436   292   292 E SMD     : DCD OFF
,08-24 13:30:30.436   292   292 E SMD     : DCD OFF
,08-24 13:30:31.686  1016  1312 E Watchdog: !@Sync 17
,08-24 13:30:31.996  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:30:32.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:33.446   292   292 E SMD     : DCD OFF
,08-24 13:30:33.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:34.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:35.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:36.196  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:30:36.446   292   292 E SMD     : DCD OFF
,08-24 13:30:36.966   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 13:30:37.966   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-24 13:30:39.446   292   292 E SMD     : DCD OFF
,08-24 13:30:42.066  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:30:42.446   292   292 E SMD     : DCD OFF
,08-24 13:30:45.446   292   292 E SMD     : DCD OFF
,08-24 13:30:45.496  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:30:46.226  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:30:48.446   292   292 E SMD     : DCD OFF
,08-24 13:30:51.446   292   292 E SMD     : DCD OFF
,08-24 13:30:52.136  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:30:54.456   292   292 E SMD     : DCD OFF
,08-24 13:30:56.236  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:30:57.456   292   292 E SMD     : DCD OFF
,08-24 13:31:00.456   292   292 E SMD     : DCD OFF
,08-24 13:31:01.686  1016  1312 E Watchdog: !@Sync 18
,08-24 13:31:02.196  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:31:02.966   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 13:31:02.966   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 13:31:03.456   292   292 E SMD     : DCD OFF
,08-24 13:31:05.496  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 13:31:06.256  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:31:06.456   292   292 E SMD     : DCD OFF
,08-24 13:31:09.456   292   292 E SMD     : DCD OFF
,08-24 13:31:12.256  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:31:12.456   292   292 E SMD     : DCD OFF
,08-24 13:31:15.456   292   292 E SMD     : DCD OFF,
,08-24 13:31:16.286  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:31:18.466   292   292 E SMD     : DCD OFF
,08-24 13:31:21.466   292   292 E SMD     : DCD OFF
,08-24 13:31:22.326  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:31:24.466   292   292 E SMD     : DCD OFF
,08-24 13:31:25.496  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:31:26.296  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:31:27.466   292   292 E SMD     : DCD OFF
,08-24 13:31:27.976   333   333 I Atfwd_Daemon: Stop the daemon....,
,08-24 13:31:30.106  1016  1050 I PowerManagerService: [PWL] Off : 525s ago
,08-24 13:31:30.466   292   292 E SMD     : DCD OFF
,08-24 13:31:31.686  1016  1312 E Watchdog: !@Sync 19
,08-24 13:31:32.396  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:31:33.466   292   292 E SMD     : DCD OFF
,08-24 13:31:36.306  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:31:36.466   292   292 E SMD     : DCD OFF
,08-24 13:31:39.476   292   292 E SMD     : DCD OFF
,08-24 13:31:42.456  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:31:42.456  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:31:42.456  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:31:42.456  1016  1497 D BatteryService: stay LED for fully charged
,08-24 13:31:42.456  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:31:42.466  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:31:42.466  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:31:42.466  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:31:42.466  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:31:42.466  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:31:42.466  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:31:42.476   292   292 E SMD     : DCD OFF
,08-24 13:31:42.476  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:31:42.476  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:31:42.496  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:31:42.496  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:31:42.496  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:42.496  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:31:42.496  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:31:45.476   292   292 E SMD     : DCD OFF,
,08-24 13:31:45.496  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:31:46.326  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:31:48.476   292   292 E SMD     : DCD OFF
,08-24 13:31:51.476   292   292 E SMD     : DCD OFF
,08-24 13:31:52.526  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:31:54.476   292   292 E SMD     : DCD OFF
,08-24 13:31:56.336  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:31:57.476   292   292 E SMD     : DCD OFF
,08-24 13:31:58.956  1016  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:31:58.956  1016  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-24 13:31:58.956  1016  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:31:59.766  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:31:59.766  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:31:59.766  1016  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:31:59.766  1016  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:32:00.476   292   292 E SMD     : DCD OFF,
,08-24 13:32:01.686  1016  1312 E Watchdog: !@Sync 20
,08-24 13:32:02.586  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:32:02.586  1016  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:32:02.586  1016  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:32:02.586  1016  1479 D BatteryService: stay LED for fully charged
08-24 13:32:02.586  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:32:02.596  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:32:02.596  1016  1016 I MotionRecognitionService: Plugged
08-24 13:32:02.596  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:32:02.596  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:32:02.596  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:32:02.596  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:32:02.606  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:32:02.606  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:32:02.616  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:32:02.616  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:32:02.616  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:32:02.616  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:02.616  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:03.486   292   292 E SMD     : DCD OFF
,08-24 13:32:05.496  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:32:06.346  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:32:06.486   292   292 E SMD     : DCD OFF
,08-24 13:32:09.486   292   292 E SMD     : DCD OFF
,08-24 13:32:12.486   292   292 E SMD     : DCD OFF
,08-24 13:32:12.656  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:32:15.486   292   292 E SMD     : DCD OFF,
,08-24 13:32:16.366  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:32:18.486   292   292 E SMD     : DCD OFF
,08-24 13:32:21.486   292   292 E SMD     : DCD OFF,
,08-24 13:32:22.716  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:32:22.716  1016  1457 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:32:22.716  1016  1457 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:32:22.716  1016  1457 D BatteryService: stay LED for fully charged
08-24 13:32:22.716  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:32:22.726  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:32:22.726  1016  1016 I MotionRecognitionService: Plugged
08-24 13:32:22.726  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:32:22.726  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:32:22.726  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:32:22.726  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:32:22.736  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:32:22.736  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:32:22.746  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:32:22.746  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:32:22.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:22.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:32:22.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:32:24.496   292   292 E SMD     : DCD OFF
,08-24 13:32:25.496  1016  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-24 13:32:26.396  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:32:27.496   292   292 E SMD     : DCD OFF
,08-24 13:32:30.496   292   292 E SMD     : DCD OFF
,08-24 13:32:31.686  1016  1312 E Watchdog: !@Sync 21
,08-24 13:32:32.786  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:32:33.496   292   292 E SMD     : DCD OFF
,08-24 13:32:36.426  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:32:36.496   292   292 E SMD     : DCD OFF
,08-24 13:32:39.496   292   292 E SMD     : DCD OFF
,08-24 13:32:42.496   292   292 E SMD     : DCD OFF
,08-24 13:32:42.846  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:32:45.126  1016  1050 I PowerManagerService: [PWL] Off : 600s ago
,08-24 13:32:45.496   292   292 E SMD     : DCD OFF,
,08-24 13:32:46.456  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:32:48.506   292   292 E SMD     : DCD OFF
,08-24 13:32:51.506   292   292 E SMD     : DCD OFF
,08-24 13:32:52.906  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:32:54.506   292   292 E SMD     : DCD OFF
,08-24 13:32:56.466  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:32:57.506   292   292 E SMD     : DCD OFF
,08-24 13:33:00.506   292   292 E SMD     : DCD OFF,
,08-24 13:33:01.686  1016  1312 E Watchdog: !@Sync 22
,08-24 13:33:02.976  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:33:03.506   292   292 E SMD     : DCD OFF
,08-24 13:33:06.496  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:33:06.506   292   292 E SMD     : DCD OFF
,08-24 13:33:09.516   292   292 E SMD     : DCD OFF
,08-24 13:33:12.516   292   292 E SMD     : DCD OFF
,08-24 13:33:13.036  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:33:15.516   292   292 E SMD     : DCD OFF
,08-24 13:33:16.526  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:33:18.516   292   292 E SMD     : DCD OFF
,08-24 13:33:21.516   292   292 E SMD     : DCD OFF
,08-24 13:33:23.106  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:33:24.516   292   292 E SMD     : DCD OFF
,08-24 13:33:26.556  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:33:27.516   292   292 E SMD     : DCD OFF
,08-24 13:33:30.526   292   292 E SMD     : DCD OFF
,08-24 13:33:31.686  1016  1312 E Watchdog: !@Sync 23
,08-24 13:33:33.166  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:33:33.526   292   292 E SMD     : DCD OFF
,08-24 13:33:36.526   292   292 E SMD     : DCD OFF
,08-24 13:33:36.576  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:33:39.526   292   292 E SMD     : DCD OFF
,08-24 13:33:42.526   292   292 E SMD     : DCD OFF
,08-24 13:33:43.236  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:33:45.526   292   292 E SMD     : DCD OFF
,08-24 13:33:46.586  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:33:48.526   292   292 E SMD     : DCD OFF
,08-24 13:33:51.526   292   292 E SMD     : DCD OFF
,08-24 13:33:53.296  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:33:54.536   292   292 E SMD     : DCD OFF
,08-24 13:33:56.606  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:33:57.536   292   292 E SMD     : DCD OFF
,08-24 13:34:00.536   292   292 E SMD     : DCD OFF
,08-24 13:34:01.686  1016  1312 E Watchdog: !@Sync 24
,08-24 13:34:03.356  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:34:03.536   292   292 E SMD     : DCD OFF
,08-24 13:34:05.206  1016  1050 I PowerManagerService: [PWL] Off : 680s ago
,08-24 13:34:06.536   292   292 E SMD     : DCD OFF
,08-24 13:34:06.616  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:34:09.536   292   292 E SMD     : DCD OFF
,08-24 13:34:12.536   292   292 E SMD     : DCD OFF
,08-24 13:34:13.426  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:34:15.536   292   292 E SMD     : DCD OFF
,08-24 13:34:16.646  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:34:18.546   292   292 E SMD     : DCD OFF
,08-24 13:34:21.546   292   292 E SMD     : DCD OFF
,08-24 13:34:23.486  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:34:23.486  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:34:23.486  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:34:23.486  1016  1029 D BatteryService: stay LED for fully charged
08-24 13:34:23.496  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:34:23.496  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:34:23.496  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:34:23.496  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:34:23.496  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:34:23.496  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:34:23.496  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-24 13:34:23.506  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:34:23.506  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:34:23.516  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:34:23.516  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:34:23.526  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:34:23.526  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:34:23.526  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:24.546   292   292 E SMD     : DCD OFF
,08-24 13:34:26.676  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:34:27.546   292   292 E SMD     : DCD OFF
,08-24 13:34:30.546   292   292 E SMD     : DCD OFF
,08-24 13:34:31.696  1016  1312 E Watchdog: !@Sync 25
,08-24 13:34:33.546   292   292 E SMD     : DCD OFF
,08-24 13:34:33.556  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:34:36.546   292   292 E SMD     : DCD OFF
,08-24 13:34:36.706  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:34:39.546   292   292 E SMD     : DCD OFF
,08-24 13:34:42.556   292   292 E SMD     : DCD OFF
,08-24 13:34:43.616  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:34:43.616  1016  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:34:43.616  1016  1325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:34:43.626  1016  1325 D BatteryService: stay LED for fully charged
,08-24 13:34:43.626  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:34:43.626  1016  1016 I MotionRecognitionService: Plugged,
08-24 13:34:43.626  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:34:43.626  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:34:43.626  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:34:43.626  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:34:43.626  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-24 13:34:43.636  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:34:43.636  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:34:43.656  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:34:43.656  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:34:43.656  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:43.656  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:43.656  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:45.556   292   292 E SMD     : DCD OFF
,08-24 13:34:46.726  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:34:48.556   292   292 E SMD     : DCD OFF
,08-24 13:34:51.556   292   292 E SMD     : DCD OFF
,08-24 13:34:53.686  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 13:34:53.686  1016  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:34:53.686  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:34:53.686  1016  1325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:34:53.686  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-24 13:34:53.686  1016  1325 D BatteryService: stay LED for fully charged
08-24 13:34:53.686  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 13:34:53.686  1016  1016 I MotionRecognitionService: Plugged,
08-24 13:34:53.686  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:34:53.696  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:34:53.696  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:34:53.706  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:34:53.706  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:34:53.716  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:34:53.716  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:34:53.716  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:34:53.716  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:34:53.716  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:34:54.556   292   292 E SMD     : DCD OFF
,08-24 13:34:56.746  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:34:57.556   292   292 E SMD     : DCD OFF
,08-24 13:35:00.556   292   292 E SMD     : DCD OFF
,08-24 13:35:01.696  1016  1312 E Watchdog: !@Sync 26
,08-24 13:35:03.566   292   292 E SMD     : DCD OFF
,08-24 13:35:03.746  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:35:03.746  1016  1475 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:35:03.756  1016  1475 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:35:03.756  1016  1475 D BatteryService: stay LED for fully charged
08-24 13:35:03.756  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:35:03.756  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:35:03.756  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:35:03.756  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:35:03.756  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:35:03.766  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:35:03.766  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:35:03.776  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:35:03.776  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:35:03.786  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-24 13:35:03.786  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:35:03.786  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:35:03.786  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:03.786  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:06.566   292   292 E SMD     : DCD OFF
,08-24 13:35:06.756  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:35:09.566   292   292 E SMD     : DCD OFF
,08-24 13:35:12.566   292   292 E SMD     : DCD OFF
,08-24 13:35:13.816  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:35:13.816  1016  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:35:13.816  1016  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:35:13.816  1016  1218 D BatteryService: stay LED for fully charged
08-24 13:35:13.816  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:35:13.816  1016  1016 I MotionRecognitionService: Plugged
08-24 13:35:13.816  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:35:13.816  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:35:13.816  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:35:13.826  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:35:13.826  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:35:13.836  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:35:13.836  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:35:13.846  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:35:13.846  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:35:13.846  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:35:13.846  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:35:13.846  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:15.566   292   292 E SMD     : DCD OFF
,08-24 13:35:16.766  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:35:18.566   292   292 E SMD     : DCD OFF
,08-24 13:35:21.566   292   292 E SMD     : DCD OFF
,08-24 13:35:23.876  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:35:23.876  1016  1139 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:35:23.876  1016  1139 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:35:23.876  1016  1139 D BatteryService: stay LED for fully charged
08-24 13:35:23.876  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:35:23.876  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:35:23.876  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:35:23.886  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:35:23.886  1016  1016 I MotionRecognitionService: Plugged
08-24 13:35:23.886  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:35:23.886  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:35:23.886  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 13:35:23.886  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:35:23.906  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:35:23.906  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:35:23.906  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:35:23.906  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:35:23.906  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:35:24.566   292   292 E SMD     : DCD OFF
,08-24 13:35:26.786  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:35:27.576   292   292 E SMD     : DCD OFF
,08-24 13:35:30.216  1016  1050 I PowerManagerService: [PWL] Off : 765s ago
,08-24 13:35:30.576   292   292 E SMD     : DCD OFF
,08-24 13:35:31.696  1016  1312 E Watchdog: !@Sync 27
,08-24 13:35:33.576   292   292 E SMD     : DCD OFF
,08-24 13:35:33.936  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:35:36.576   292   292 E SMD     : DCD OFF
,08-24 13:35:36.796  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:35:39.576   292   292 E SMD     : DCD OFF
,08-24 13:35:42.576   292   292 E SMD     : DCD OFF
,08-24 13:35:44.006  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:35:45.576   292   292 E SMD     : DCD OFF
,08-24 13:35:46.826  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:35:48.576   292   292 E SMD     : DCD OFF
,08-24 13:35:51.586   292   292 E SMD     : DCD OFF
,08-24 13:35:54.066  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:35:54.586   292   292 E SMD     : DCD OFF
,08-24 13:35:56.856  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:35:57.586   292   292 E SMD     : DCD OFF
,08-24 13:36:00.586   292   292 E SMD     : DCD OFF
,08-24 13:36:01.696  1016  1312 E Watchdog: !@Sync 28
,08-24 13:36:03.586   292   292 E SMD     : DCD OFF
,08-24 13:36:04.126  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:06.586   292   292 E SMD     : DCD OFF
,08-24 13:36:06.886  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:36:09.586   292   292 E SMD     : DCD OFF
,08-24 13:36:12.596   292   292 E SMD     : DCD OFF
,08-24 13:36:14.196  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:14.196  1016  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:36:14.196  1016  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:36:14.196  1016  1479 D BatteryService: stay LED for fully charged
08-24 13:36:14.196  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:36:14.196  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:36:14.196  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:36:14.206  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:36:14.206  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-24 13:36:14.206  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:36:14.206  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:36:14.206  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:36:14.206  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:36:14.226  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:36:14.226  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:36:14.226  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:36:14.226  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:36:14.226  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:15.596   292   292 E SMD     : DCD OFF
,08-24 13:36:16.916  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:36:18.596   292   292 E SMD     : DCD OFF
,08-24 13:36:21.596   292   292 E SMD     : DCD OFF
,08-24 13:36:24.256  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:24.256  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:36:24.256  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:36:24.256  1016  1028 D BatteryService: stay LED for fully charged
08-24 13:36:24.256  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:36:24.266  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:36:24.266  1016  1016 I MotionRecognitionService: Plugged,
08-24 13:36:24.266  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:36:24.266  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:36:24.266  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-24 13:36:24.266  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:36:24.276  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:36:24.276  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:36:24.286  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:36:24.296  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:36:24.296  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:24.296  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:24.296  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:24.596   292   292 E SMD     : DCD OFF
,08-24 13:36:26.946  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:36:27.596   292   292 E SMD     : DCD OFF
,08-24 13:36:30.596   292   292 E SMD     : DCD OFF
,08-24 13:36:31.696  1016  1312 E Watchdog: !@Sync 29
,08-24 13:36:33.596   292   292 E SMD     : DCD OFF
,08-24 13:36:34.326  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:36.606   292   292 E SMD     : DCD OFF
,08-24 13:36:36.956  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:36:39.606   292   292 E SMD     : DCD OFF
,08-24 13:36:42.606   292   292 E SMD     : DCD OFF
,08-24 13:36:44.386  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:45.606   292   292 E SMD     : DCD OFF
,08-24 13:36:46.966  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:36:48.606   292   292 E SMD     : DCD OFF
,08-24 13:36:51.606   292   292 E SMD     : DCD OFF
,08-24 13:36:54.456  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:36:54.456  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:36:54.456  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-24 13:36:54.456  1016  1028 D BatteryService: stay LED for fully charged,
08-24 13:36:54.456  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:36:54.456  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:36:54.456  1016  1016 I MotionRecognitionService: Plugged,
08-24 13:36:54.456  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:36:54.466  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:36:54.466  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:36:54.466  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:36:54.466  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:36:54.466  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:36:54.486  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:36:54.486  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:36:54.486  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:54.486  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:54.486  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:36:54.606   292   292 E SMD     : DCD OFF
,08-24 13:36:56.986  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:36:57.616   292   292 E SMD     : DCD OFF
,08-24 13:36:58.956  1016  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:36:58.956  1016  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:36:58.956  1016  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:37:00.216  1016  1050 I PowerManagerService: [PWL] Off : 855s ago
,08-24 13:37:00.216  1016  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-24 13:37:00.216  1016  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-24 13:37:00.216  1016  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=1016, ws=null) (elapsedTime=1261)
,08-24 13:37:00.616   292   292 E SMD     : DCD OFF
,08-24 13:37:00.836  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:37:00.836  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:37:00.846  1016  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:37:00.846  1016  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:37:01.696  1016  1312 E Watchdog: !@Sync 30
,08-24 13:37:03.616   292   292 E SMD     : DCD OFF
,08-24 13:37:04.516  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:37:06.616   292   292 E SMD     : DCD OFF
,08-24 13:37:07.006  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:37:09.616   292   292 E SMD     : DCD OFF
,08-24 13:37:12.616   292   292 E SMD     : DCD OFF
,08-24 13:37:14.576  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 13:37:14.576  1016  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:37:14.576  1016  1325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:37:14.576  1016  1325 D BatteryService: stay LED for fully charged
08-24 13:37:14.576  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-24 13:37:14.586  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:37:14.586  1016  1016 I MotionRecognitionService: Plugged
08-24 13:37:14.586  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:37:14.586  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:37:14.586  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-24 13:37:14.586  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:37:14.596  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:37:14.596  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:37:14.606  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:37:14.606  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:37:14.606  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:37:14.616  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:37:14.616  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:37:15.616   292   292 E SMD     : DCD OFF
,08-24 13:37:17.016  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:37:18.616   292   292 E SMD     : DCD OFF
,08-24 13:37:21.626   292   292 E SMD     : DCD OFF
,08-24 13:37:24.626   292   292 E SMD     : DCD OFF
,08-24 13:37:24.646  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:37:27.056  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:37:27.626   292   292 E SMD     : DCD OFF
,08-24 13:37:30.626   292   292 E SMD     : DCD OFF
,08-24 13:37:31.696  1016  1312 E Watchdog: !@Sync 31,
,08-24 13:37:33.626   292   292 E SMD     : DCD OFF
,08-24 13:37:34.706  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:37:36.626   292   292 E SMD     : DCD OFF
,08-24 13:37:37.086  1016  3363 D SSRM:n  : SIOP:: AP = 290,
,08-24 13:37:39.626   292   292 E SMD     : DCD OFF
,08-24 13:37:42.626   292   292 E SMD     : DCD OFF
,08-24 13:37:44.766  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:37:45.636   292   292 E SMD     : DCD OFF
,08-24 13:37:47.116  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:37:48.636   292   292 E SMD     : DCD OFF
,08-24 13:37:51.636   292   292 E SMD     : DCD OFF,
,08-24 13:37:54.636   292   292 E SMD     : DCD OFF
,08-24 13:37:54.836  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:37:57.146  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:37:57.636   292   292 E SMD     : DCD OFF
,08-24 13:38:00.636   292   292 E SMD     : DCD OFF
,08-24 13:38:01.696  1016  1312 E Watchdog: !@Sync 32
,08-24 13:38:03.636   292   292 E SMD     : DCD OFF
,08-24 13:38:04.906  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:38:06.646   292   292 E SMD     : DCD OFF
,08-24 13:38:07.186  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:38:08.696  5825  5895 I PlayCommon: [1024] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 13:38:08.696  5825  5895 I PlayCommon: [1024] com.google.android.play.a.al.e(732): No file ready to send
,08-24 13:38:09.646   292   292 E SMD     : DCD OFF
,08-24 13:38:12.646   292   292 E SMD     : DCD OFF
,08-24 13:38:14.966  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:38:15.646   292   292 E SMD     : DCD OFF
,08-24 13:38:17.226  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:38:18.646   292   292 E SMD     : DCD OFF
,08-24 13:38:21.646   292   292 E SMD     : DCD OFF
,08-24 13:38:24.646   292   292 E SMD     : DCD OFF
,08-24 13:38:25.036  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:38:27.256  1016  3363 D SSRM:n  : SIOP:: AP = 280,
,08-24 13:38:27.646   292   292 E SMD     : DCD OFF
,08-24 13:38:30.656   292   292 E SMD     : DCD OFF
,08-24 13:38:31.696  1016  1312 E Watchdog: !@Sync 33
,08-24 13:38:33.656   292   292 E SMD     : DCD OFF
,08-24 13:38:35.096  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:38:35.096  1016  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:38:35.096  1016  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:38:35.096  1016  1481 D BatteryService: stay LED for fully charged
,08-24 13:38:35.096  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:38:35.106  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:38:35.106  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:38:35.106  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:38:35.106  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:38:35.106  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:38:35.106  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:38:35.116  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:38:35.116  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:38:35.126  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:38:35.126  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:38:35.136  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:35.136  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:35.136  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:35.216  1016  1050 I PowerManagerService: [PWL] Off : 950s ago
,08-24 13:38:36.656   292   292 E SMD     : DCD OFF
,08-24 13:38:37.276  1016  3363 D SSRM:n  : SIOP:: AP = 280,
,08-24 13:38:39.656   292   292 E SMD     : DCD OFF
,08-24 13:38:42.656   292   292 E SMD     : DCD OFF
,08-24 13:38:45.166  1016  3173 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:38:45.166  1016  3173 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:38:45.166  1016  3173 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:38:45.166  1016  3173 D BatteryService: stay LED for fully charged
08-24 13:38:45.166  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:38:45.166  1016  1016 I MotionRecognitionService: Plugged
08-24 13:38:45.166  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:38:45.166  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:38:45.176  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:38:45.176  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:38:45.176  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:38:45.176  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:38:45.186  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:38:45.196  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:38:45.196  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:38:45.196  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:45.196  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:45.196  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:38:45.656   292   292 E SMD     : DCD OFF
,08-24 13:38:47.296  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:38:48.656   292   292 E SMD     : DCD OFF
,08-24 13:38:51.666   292   292 E SMD     : DCD OFF
,08-24 13:38:54.666   292   292 E SMD     : DCD OFF
,08-24 13:38:55.226  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:38:57.306  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:38:57.666   292   292 E SMD     : DCD OFF
,08-24 13:39:00.666   292   292 E SMD     : DCD OFF
,08-24 13:39:01.696  1016  1312 E Watchdog: !@Sync 34
,08-24 13:39:03.666   292   292 E SMD     : DCD OFF
,08-24 13:39:05.296  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:39:06.666   292   292 E SMD     : DCD OFF
,08-24 13:39:07.316  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:39:09.666   292   292 E SMD     : DCD OFF
,08-24 13:39:12.666   292   292 E SMD     : DCD OFF
,08-24 13:39:15.356  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:39:15.366  1016  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:39:15.366  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:39:15.366  1016  1496 D BatteryService: stay LED for fully charged
,08-24 13:39:15.366  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:39:15.366  1016  1016 I MotionRecognitionService: Plugged
08-24 13:39:15.366  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:39:15.366  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:39:15.366  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:39:15.366  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:39:15.366  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:39:15.376  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:39:15.376  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:39:15.396  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-24 13:39:15.396  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:39:15.396  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:39:15.396  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:39:15.396  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:15.676   292   292 E SMD     : DCD OFF
,08-24 13:39:17.336  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:39:18.676   292   292 E SMD     : DCD OFF
,08-24 13:39:18.856  1016  1095 V AlarmManager: waitForAlarm result :4
,08-24 13:39:18.866  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:39:18.866  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:39:18.876  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:39:18.876  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:39:18.886  1016  1218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 13:39:18.886  1016  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,08-24 13:39:18.886  1016  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:39:18.886  1016  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:39:18.886  1016  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:39:18.896  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:39:18.896  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-24 13:39:18.896  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-24 13:39:18.896  1179  1179 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-24 13:39:18.916  1016  1139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:39:18.916  1016  1139 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:39:18.916  1016  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:39:18.916  1016  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:39:18.936  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:39:18.946  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:39:18.946  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:39:18.966  4808  7240 I EventLogChimeraService: Aggregate from 1472036958701 (log), 1472036958701 (data)
,08-24 13:39:18.966  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:39:19.066  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:39:19.066  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:39:19.066  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:39:19.066  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:39:19.096  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:39:19.096  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:39:19.096  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:39:19.096  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:39:19.126  1016  1218 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:39:19.126  1016  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:39:19.126  1016  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:39:19.126  1016  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:39:19.136  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:39:19.136  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-24 13:39:19.136  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:39:19.136  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 13:39:19.166  4808  7241 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-24 13:39:19.186  4808  7241 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-24 13:39:21.676   292   292 E SMD     : DCD OFF
,08-24 13:39:24.676   292   292 E SMD     : DCD OFF
,08-24 13:39:25.426  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:39:25.426  1016  1139 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-24 13:39:25.426  1016  1139 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:39:25.426  1016  1139 D BatteryService: stay LED for fully charged
08-24 13:39:25.426  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:39:25.436  1016  1016 I MotionRecognitionService: Plugged
08-24 13:39:25.436  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:39:25.436  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:39:25.436  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:39:25.436  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:39:25.436  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:39:25.446  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:39:25.446  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:39:25.456  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:39:25.456  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:39:25.466  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:39:25.466  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:25.466  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:39:27.346  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:39:27.676   292   292 E SMD     : DCD OFF
,08-24 13:39:30.676   292   292 E SMD     : DCD OFF
,08-24 13:39:31.696  1016  1312 E Watchdog: !@Sync 35
,08-24 13:39:33.676   292   292 E SMD     : DCD OFF
,08-24 13:39:35.496  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:39:36.686   292   292 E SMD     : DCD OFF
,08-24 13:39:37.376  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:39:39.686   292   292 E SMD     : DCD OFF
,08-24 13:39:42.686   292   292 E SMD     : DCD OFF
,08-24 13:39:45.556  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:39:45.686   292   292 E SMD     : DCD OFF,
,08-24 13:39:47.406  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:39:48.686   292   292 E SMD     : DCD OFF
,08-24 13:39:51.686   292   292 E SMD     : DCD OFF
,08-24 13:39:54.686   292   292 E SMD     : DCD OFF
,08-24 13:39:55.626  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:39:57.426  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:39:57.686   292   292 E SMD     : DCD OFF
,08-24 13:39:59.986  1016  1095 V AlarmManager: waitForAlarm result :8
,08-24 13:40:00.696   292   292 E SMD     : DCD OFF
,08-24 13:40:01.706  1016  1312 E Watchdog: !@Sync 36,
,08-24 13:40:03.696   292   292 E SMD     : DCD OFF
,08-24 13:40:05.686  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:40:06.696   292   292 E SMD     : DCD OFF
,08-24 13:40:07.436  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:40:09.696   292   292 E SMD     : DCD OFF
,08-24 13:40:12.696   292   292 E SMD     : DCD OFF
,08-24 13:40:15.266  1016  1050 I PowerManagerService: [PWL] Off : 1050s ago
,08-24 13:40:15.696   292   292 E SMD     : DCD OFF
,08-24 13:40:15.756  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:40:17.446  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:40:18.696   292   292 E SMD     : DCD OFF
,08-24 13:40:21.696   292   292 E SMD     : DCD OFF,
,08-24 13:40:24.706   292   292 E SMD     : DCD OFF
,08-24 13:40:25.826  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:40:25.826  1016  1475 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:40:25.826  1016  1475 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:40:25.826  1016  1475 D BatteryService: stay LED for fully charged
,08-24 13:40:25.826  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:40:25.836  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:40:25.836  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:40:25.836  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:40:25.836  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:40:25.836  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:40:25.836  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:40:25.846  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:40:25.846  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:40:25.866  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:40:25.866  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:40:25.866  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:25.866  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:25.866  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:27.456  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:40:27.706   292   292 E SMD     : DCD OFF
,08-24 13:40:30.706   292   292 E SMD     : DCD OFF
,08-24 13:40:31.706  1016  1312 E Watchdog: !@Sync 37
,08-24 13:40:33.706   292   292 E SMD     : DCD OFF
,08-24 13:40:35.896  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:40:36.706   292   292 E SMD     : DCD OFF
,08-24 13:40:37.476  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:40:39.706   292   292 E SMD     : DCD OFF
,08-24 13:40:42.706   292   292 E SMD     : DCD OFF
,08-24 13:40:45.716   292   292 E SMD     : DCD OFF,
,08-24 13:40:45.956  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:40:47.486  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:40:48.716   292   292 E SMD     : DCD OFF
,08-24 13:40:51.716   292   292 E SMD     : DCD OFF
,08-24 13:40:54.716   292   292 E SMD     : DCD OFF
,08-24 13:40:56.026  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:40:56.026  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:40:56.026  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:40:56.026  1016  1029 D BatteryService: stay LED for fully charged
,08-24 13:40:56.026  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:40:56.026  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:40:56.026  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:40:56.026  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:40:56.026  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:40:56.036  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:40:56.036  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:40:56.036  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:40:56.046  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:40:56.056  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:40:56.056  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:40:56.056  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:40:56.056  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:40:56.056  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:40:57.506  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:40:57.716   292   292 E SMD     : DCD OFF
,08-24 13:41:00.716   292   292 E SMD     : DCD OFF
,08-24 13:41:01.706  1016  1312 E Watchdog: !@Sync 38
,08-24 13:41:03.716   292   292 E SMD     : DCD OFF
,08-24 13:41:06.086  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:41:06.086  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:41:06.086  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:41:06.086  1016  1028 D BatteryService: stay LED for fully charged
08-24 13:41:06.086  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:41:06.096  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:41:06.096  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:41:06.096  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:41:06.096  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:41:06.096  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:41:06.096  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:41:06.106  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:41:06.106  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:41:06.116  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:41:06.116  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:41:06.116  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:41:06.116  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:41:06.116  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:06.716   292   292 E SMD     : DCD OFF
,08-24 13:41:07.526  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:41:09.726   292   292 E SMD     : DCD OFF
,08-24 13:41:12.726   292   292 E SMD     : DCD OFF
,08-24 13:41:15.726   292   292 E SMD     : DCD OFF
,08-24 13:41:16.156  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:41:17.556  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:41:18.726   292   292 E SMD     : DCD OFF
,08-24 13:41:21.726   292   292 E SMD     : DCD OFF
,08-24 13:41:24.726   292   292 E SMD     : DCD OFF
,08-24 13:41:26.216  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:41:27.576  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:41:27.726   292   292 E SMD     : DCD OFF
,08-24 13:41:30.726   292   292 E SMD     : DCD OFF
,08-24 13:41:31.706  1016  1312 E Watchdog: !@Sync 39
,08-24 13:41:33.736   292   292 E SMD     : DCD OFF
,08-24 13:41:36.276  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:41:36.286  1016  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:41:36.286  1016  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 13:41:36.286  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 13:41:36.286  1016  1479 D BatteryService: stay LED for fully charged
,08-24 13:41:36.286  1016  1016 I MotionRecognitionService: Plugged,
08-24 13:41:36.286  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:41:36.286  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:41:36.286  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-24 13:41:36.296  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:41:36.296  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:41:36.296  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:41:36.296  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:41:36.316  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:41:36.316  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:41:36.316  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:41:36.316  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:41:36.316  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:36.736   292   292 E SMD     : DCD OFF
,08-24 13:41:37.596  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:41:39.736   292   292 E SMD     : DCD OFF
,08-24 13:41:42.736   292   292 E SMD     : DCD OFF
,08-24 13:41:45.736   292   292 E SMD     : DCD OFF
,08-24 13:41:46.346  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 13:41:46.346  1016  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:41:46.346  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:41:46.346  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:41:46.346  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:41:46.346  1016  1496 D BatteryService: stay LED for fully charged
08-24 13:41:46.346  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 13:41:46.346  1016  1016 I MotionRecognitionService: Plugged
08-24 13:41:46.346  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:41:46.356  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:41:46.356  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:41:46.356  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:41:46.356  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:41:46.376  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:41:46.376  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:41:46.376  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:41:46.376  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:46.376  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:47.606  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:41:48.736   292   292 E SMD     : DCD OFF
,08-24 13:41:51.736   292   292 E SMD     : DCD OFF
,08-24 13:41:54.746   292   292 E SMD     : DCD OFF
,08-24 13:41:56.416  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 13:41:56.416  1016  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:41:56.416  1016  1325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-24 13:41:56.416  1016  1325 D BatteryService: stay LED for fully charged
08-24 13:41:56.416  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 13:41:56.416  1016  1016 I MotionRecognitionService: Plugged,
08-24 13:41:56.416  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:41:56.426  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:41:56.426  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:41:56.426  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:41:56.426  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:41:56.436  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:41:56.436  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:41:56.446  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:41:56.446  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:41:56.446  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:56.446  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:41:56.446  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:41:57.626  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:41:57.746   292   292 E SMD     : DCD OFF
,08-24 13:41:58.956  1016  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:41:58.956  1016  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-24 13:41:58.956  1016  1085 D TimaService: TimaServiceHandler.handleMessage what =1
,08-24 13:41:59.306  1016  1042 I UsageStatsService: User[0] Flushing usage stats to disk
,08-24 13:41:59.346  1016  1102 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,08-24 13:41:59.346  1016  1102 I ApplicationUsage: Updating Usage Statistics in DB @ 1472038919356
,08-24 13:41:59.356  1016  1102 I ApplicationPolicy: updateDataUsageMap
,08-24 13:41:59.766  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:41:59.766  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:41:59.766  1016  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:41:59.766  1016  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:41:59.796  1016  1102 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,08-24 13:41:59.796  1016  1102 I NetworkDataUsageDb: ::isTableExists: Table exists 
,08-24 13:41:59.806  1016  1102 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1472038919823
,08-24 13:42:00.266  1016  1050 I PowerManagerService: [PWL] Off : 1155s ago
,08-24 13:42:00.746   292   292 E SMD     : DCD OFF,
,08-24 13:42:01.706  1016  1312 E Watchdog: !@Sync 40
,08-24 13:42:03.746   292   292 E SMD     : DCD OFF
,08-24 13:42:06.476  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:42:06.746   292   292 E SMD     : DCD OFF
,08-24 13:42:07.666  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:42:09.746   292   292 E SMD     : DCD OFF
,08-24 13:42:12.746   292   292 E SMD     : DCD OFF
,08-24 13:42:15.746   292   292 E SMD     : DCD OFF
,08-24 13:42:16.536  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:42:16.536  1016  1475 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:42:16.536  1016  1475 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:42:16.536  1016  1475 D BatteryService: stay LED for fully charged
08-24 13:42:16.536  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:42:16.546  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:42:16.546  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:42:16.546  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:42:16.546  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:42:16.546  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:42:16.546  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:42:16.556  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:42:16.556  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:42:16.566  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:42:16.566  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:42:16.566  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:42:16.566  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:42:16.566  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:17.676  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:42:18.756   292   292 E SMD     : DCD OFF
,08-24 13:42:21.756   292   292 E SMD     : DCD OFF
,08-24 13:42:24.756   292   292 E SMD     : DCD OFF
,08-24 13:42:26.596  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:42:26.596  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:42:26.596  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:42:26.596  1016  1029 D BatteryService: stay LED for fully charged
08-24 13:42:26.596  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:42:26.606  1016  1016 I MotionRecognitionService: Plugged
08-24 13:42:26.606  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:42:26.606  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:42:26.606  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:42:26.606  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:42:26.606  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:42:26.616  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:42:26.616  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:42:26.626  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:42:26.626  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:42:26.626  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-24 13:42:26.626  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:42:26.626  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:27.686  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:42:27.756   292   292 E SMD     : DCD OFF
,08-24 13:42:30.756   292   292 E SMD     : DCD OFF,
,08-24 13:42:31.706  1016  1312 E Watchdog: !@Sync 41
,08-24 13:42:33.756   292   292 E SMD     : DCD OFF
,08-24 13:42:36.666  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:42:36.666  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:42:36.666  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:42:36.666  1016  1028 D BatteryService: stay LED for fully charged
,08-24 13:42:36.666  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:42:36.666  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:42:36.666  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:42:36.676  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:42:36.676  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:42:36.676  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:42:36.676  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:42:36.686  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:42:36.686  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:42:36.696  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:42:36.696  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:42:36.706  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:42:36.706  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:36.706  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:36.756   292   292 E SMD     : DCD OFF
,08-24 13:42:37.706  1016  3363 D SSRM:n  : SIOP:: AP = 280
,08-24 13:42:39.756   292   292 E SMD     : DCD OFF
,08-24 13:42:42.766   292   292 E SMD     : DCD OFF
,08-24 13:42:45.766   292   292 E SMD     : DCD OFF,
,08-24 13:42:46.726  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:42:46.726  1016  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:42:46.726  1016  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:42:46.726  1016  1479 D BatteryService: stay LED for fully charged
,08-24 13:42:46.736  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:42:46.736  1016  1016 I MotionRecognitionService: Plugged
08-24 13:42:46.736  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:42:46.736  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:42:46.736  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:42:46.736  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:42:46.736  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:42:46.746  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:42:46.746  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:42:46.756  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:42:46.756  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:42:46.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:46.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:42:46.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:47.716  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:42:48.766   292   292 E SMD     : DCD OFF
,08-24 13:42:51.766   292   292 E SMD     : DCD OFF
,08-24 13:42:54.766   292   292 E SMD     : DCD OFF
,08-24 13:42:56.796  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:42:56.796  1016  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:42:56.796  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:42:56.796  1016  1496 D BatteryService: stay LED for fully charged
08-24 13:42:56.796  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:42:56.796  1016  1016 I MotionRecognitionService: Plugged
08-24 13:42:56.796  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:42:56.796  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:42:56.796  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:42:56.806  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:42:56.806  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:42:56.806  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:42:56.806  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:42:56.826  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:42:56.826  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:42:56.826  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:56.826  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:42:56.826  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:42:57.736  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:42:57.766   292   292 E SMD     : DCD OFF
,08-24 13:43:00.766   292   292 E SMD     : DCD OFF,
,08-24 13:43:01.706  1016  1312 E Watchdog: !@Sync 42,
,08-24 13:43:03.776   292   292 E SMD     : DCD OFF
,08-24 13:43:06.776   292   292 E SMD     : DCD OFF,
,08-24 13:43:06.856  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:43:06.856  1016  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:43:06.856  1016  1325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:43:06.856  1016  1325 D BatteryService: stay LED for fully charged
,08-24 13:43:06.856  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-24 13:43:06.866  1016  1016 I MotionRecognitionService: Plugged
08-24 13:43:06.866  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:43:06.866  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:43:06.866  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:43:06.866  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:43:06.866  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:43:06.876  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:43:06.876  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:43:06.886  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:43:06.886  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:43:06.886  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:06.886  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:06.886  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:07.756  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:43:08.786  5825  5895 I PlayCommon: [1024] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-24 13:43:08.786  5825  5895 I PlayCommon: [1024] com.google.android.play.a.al.e(732): No file ready to send
,08-24 13:43:09.776   292   292 E SMD     : DCD OFF
,08-24 13:43:12.776   292   292 E SMD     : DCD OFF,
,08-24 13:43:15.776   292   292 E SMD     : DCD OFF
,08-24 13:43:16.926  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-24 13:43:16.926  1016  1139 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-24 13:43:16.926  1016  1139 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:43:16.926  1016  1139 D BatteryService: stay LED for fully charged
08-24 13:43:16.926  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-24 13:43:16.926  1016  1016 I MotionRecognitionService: Plugged
08-24 13:43:16.926  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:43:16.926  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:43:16.926  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:43:16.926  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:43:16.926  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:43:16.936  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:43:16.946  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:43:16.956  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:43:16.956  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:43:16.956  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:16.956  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:16.956  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:17.766  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:43:18.776   292   292 E SMD     : DCD OFF
,08-24 13:43:21.786   292   292 E SMD     : DCD OFF
,08-24 13:43:24.786   292   292 E SMD     : DCD OFF
,08-24 13:43:26.986  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:43:26.986  1016  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:43:26.986  1016  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 13:43:26.986  1016  1481 D BatteryService: stay LED for fully charged
08-24 13:43:26.986  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:43:26.996  1016  1016 I MotionRecognitionService: Plugged
08-24 13:43:26.996  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:43:26.996  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:43:26.996  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:43:26.996  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-24 13:43:26.996  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:43:27.006  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:43:27.006  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:43:27.016  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-24 13:43:27.016  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:43:27.016  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:27.016  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:27.016  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:27.786  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:43:27.786   292   292 E SMD     : DCD OFF
,08-24 13:43:30.786   292   292 E SMD     : DCD OFF,
,08-24 13:43:31.706  1016  1312 E Watchdog: !@Sync 43,
,08-24 13:43:33.786   292   292 E SMD     : DCD OFF
,08-24 13:43:36.786   292   292 E SMD     : DCD OFF
,08-24 13:43:37.066  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:43:37.066  1016  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:43:37.066  1016  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:43:37.066  1016  1481 D BatteryService: stay LED for fully charged
08-24 13:43:37.066  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:43:37.066  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:43:37.066  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:43:37.066  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:43:37.066  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:43:37.076  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:43:37.076  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:43:37.076  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:43:37.076  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:43:37.096  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 13:43:37.096  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:43:37.096  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:37.096  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:37.096  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:37.796  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:43:39.786   292   292 E SMD     : DCD OFF
,08-24 13:43:42.786   292   292 E SMD     : DCD OFF
,08-24 13:43:45.796   292   292 E SMD     : DCD OFF
,08-24 13:43:47.126  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:43:47.816  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:43:48.796   292   292 E SMD     : DCD OFF
,08-24 13:43:50.276  1016  1050 I PowerManagerService: [PWL] Off : 1265s ago
,08-24 13:43:51.796   292   292 E SMD     : DCD OFF
,08-24 13:43:54.796   292   292 E SMD     : DCD OFF
,08-24 13:43:57.196  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:43:57.196  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:43:57.196  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:43:57.196  1016  1028 D BatteryService: stay LED for fully charged
,08-24 13:43:57.196  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:43:57.196  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:43:57.196  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:43:57.206  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:43:57.206  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:43:57.206  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-24 13:43:57.206  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:43:57.216  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:43:57.216  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:43:57.226  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:43:57.226  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:43:57.226  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:57.226  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:43:57.226  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:43:57.796   292   292 E SMD     : DCD OFF
,08-24 13:43:57.826  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:44:00.796   292   292 E SMD     : DCD OFF
,08-24 13:44:01.706  1016  1312 E Watchdog: !@Sync 44,
,08-24 13:44:03.796   292   292 E SMD     : DCD OFF
,08-24 13:44:06.806   292   292 E SMD     : DCD OFF
,08-24 13:44:07.256  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:44:07.836  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:44:09.806   292   292 E SMD     : DCD OFF,
,08-24 13:44:12.806   292   292 E SMD     : DCD OFF
,08-24 13:44:15.806   292   292 E SMD     : DCD OFF
,08-24 13:44:17.326  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:44:17.856  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:44:18.806   292   292 E SMD     : DCD OFF
,08-24 13:44:21.806   292   292 E SMD     : DCD OFF
,08-24 13:44:24.806   292   292 E SMD     : DCD OFF
,08-24 13:44:27.386  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:44:27.396  1016  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:44:27.396  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:44:27.396  1016  1496 D BatteryService: stay LED for fully charged
,08-24 13:44:27.396  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:44:27.396  1016  1016 I MotionRecognitionService: Plugged,
08-24 13:44:27.396  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:44:27.396  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:44:27.396  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:44:27.406  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:44:27.406  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:44:27.416  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:44:27.416  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:44:27.426  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:44:27.426  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:44:27.426  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:44:27.426  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:44:27.426  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:44:27.816   292   292 E SMD     : DCD OFF
,08-24 13:44:27.866  1016  3363 D SSRM:n  : SIOP:: AP = 290
,08-24 13:44:30.816   292   292 E SMD     : DCD OFF
,08-24 13:44:31.706  1016  1312 E Watchdog: !@Sync 45
,08-24 13:44:33.816   292   292 E SMD     : DCD OFF
,08-24 13:44:36.816   292   292 E SMD     : DCD OFF
,08-24 13:44:37.456  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:44:37.456  1016  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:44:37.456  1016  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:44:37.456  1016  1479 D BatteryService: stay LED for fully charged
,08-24 13:44:37.456  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:44:37.456  1016  1016 I MotionRecognitionService: Plugged
08-24 13:44:37.466  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:44:37.466  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:44:37.466  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:44:37.466  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-24 13:44:37.466  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:44:37.476  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:44:37.476  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:44:37.486  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:44:37.486  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:44:37.486  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:44:37.486  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:44:37.486  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,08-24 13:44:37.886  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:44:39.816   292   292 E SMD     : DCD OFF
,08-24 13:44:42.816   292   292 E SMD     : DCD OFF
,08-24 13:44:45.816   292   292 E SMD     : DCD OFF
,08-24 13:44:47.526  1016  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:44:47.526  1016  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:44:47.526  1016  1325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:44:47.526  1016  1325 D BatteryService: stay LED for fully charged
08-24 13:44:47.526  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:44:47.526  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:44:47.526  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-24 13:44:47.526  1016  1016 I MotionRecognitionService: Plugged
08-24 13:44:47.526  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:44:47.526  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:44:47.526  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:44:47.546  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:44:47.546  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:44:47.556  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:44:47.556  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:44:47.556  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:44:47.556  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:44:47.556  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:44:47.896  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:44:48.816   292   292 E SMD     : DCD OFF
,08-24 13:44:51.826   292   292 E SMD     : DCD OFF
,08-24 13:44:54.826   292   292 E SMD     : DCD OFF
,08-24 13:44:57.586  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:44:57.826   292   292 E SMD     : DCD OFF
,08-24 13:44:57.926  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:45:00.826   292   292 E SMD     : DCD OFF
,08-24 13:45:01.706  1016  1312 E Watchdog: !@Sync 46
,08-24 13:45:03.826   292   292 E SMD     : DCD OFF
,08-24 13:45:06.826   292   292 E SMD     : DCD OFF
,08-24 13:45:07.646  1016  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 13:45:07.646  1016  1475 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:45:07.646  1016  1475 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:45:07.646  1016  1475 D BatteryService: stay LED for fully charged
08-24 13:45:07.646  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-24 13:45:07.656  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 13:45:07.656  1016  1016 I MotionRecognitionService: Plugged
08-24 13:45:07.656  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:45:07.656  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-24 13:45:07.656  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-24 13:45:07.656  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:45:07.666  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 13:45:07.666  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:45:07.676  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:45:07.676  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:45:07.676  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:45:07.676  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:07.676  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:07.946  1016  3363 D SSRM:n  : SIOP:: AP = 270,
,08-24 13:45:09.826   292   292 E SMD     : DCD OFF
,08-24 13:45:12.836   292   292 E SMD     : DCD OFF
,08-24 13:45:15.836   292   292 E SMD     : DCD OFF
,08-24 13:45:17.716  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:45:17.716  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:45:17.716  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:45:17.716  1016  1029 D BatteryService: stay LED for fully charged
08-24 13:45:17.716  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:45:17.726  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:45:17.726  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:45:17.726  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:45:17.726  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:45:17.726  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:45:17.726  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:45:17.736  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:45:17.736  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:45:17.756  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-24 13:45:17.756  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:45:17.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:45:17.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:45:17.756  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:17.956  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:45:18.836   292   292 E SMD     : DCD OFF
,08-24 13:45:21.836   292   292 E SMD     : DCD OFF
,08-24 13:45:24.836   292   292 E SMD     : DCD OFF
,08-24 13:45:27.786  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:45:27.836   292   292 E SMD     : DCD OFF,
,08-24 13:45:27.966  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:45:30.836   292   292 E SMD     : DCD OFF
,08-24 13:45:31.706  1016  1312 E Watchdog: !@Sync 47
,08-24 13:45:33.846   292   292 E SMD     : DCD OFF
,08-24 13:45:36.846   292   292 E SMD     : DCD OFF
,08-24 13:45:37.846  1016  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:45:37.846  1016  1139 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:45:37.846  1016  1139 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:45:37.846  1016  1139 D BatteryService: stay LED for fully charged
08-24 13:45:37.846  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:45:37.856  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:45:37.856  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:45:37.856  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:45:37.856  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:45:37.856  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:45:37.856  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:45:37.866  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:45:37.866  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:45:37.876  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:45:37.886  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:45:37.886  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:37.886  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:45:37.886  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:37.986  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:45:39.846   292   292 E SMD     : DCD OFF
,08-24 13:45:42.846   292   292 E SMD     : DCD OFF
,08-24 13:45:45.276  1016  1050 I PowerManagerService: [PWL] Off : 1380s ago
,08-24 13:45:45.846   292   292 E SMD     : DCD OFF
,08-24 13:45:47.906  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:45:47.916  1016  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:45:47.916  1016  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:45:47.916  1016  1481 D BatteryService: stay LED for fully charged
08-24 13:45:47.916  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:45:47.916  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:45:47.916  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:45:47.916  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:45:47.916  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:45:47.916  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 13:45:47.926  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:45:47.926  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:45:47.926  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:45:47.946  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:45:47.946  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 13:45:47.946  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:47.946  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:45:47.946  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:45:47.996  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:45:48.846   292   292 E SMD     : DCD OFF
,08-24 13:45:51.846   292   292 E SMD     : DCD OFF
,08-24 13:45:54.846   292   292 E SMD     : DCD OFF
,08-24 13:45:57.856   292   292 E SMD     : DCD OFF
,08-24 13:45:57.976  1016  1457 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:45:58.006  1016  3363 D SSRM:n  : SIOP:: AP = 270,
,08-24 13:46:00.856   292   292 E SMD     : DCD OFF
,08-24 13:46:01.706  1016  1312 E Watchdog: !@Sync 48
,08-24 13:46:03.856   292   292 E SMD     : DCD OFF
,08-24 13:46:06.856   292   292 E SMD     : DCD OFF
,08-24 13:46:08.026  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:46:08.046  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 13:46:08.046  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:46:08.046  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:46:08.046  1016  1028 D BatteryService: stay LED for fully charged
08-24 13:46:08.046  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:46:08.046  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:46:08.056  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
08-24 13:46:08.056  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 13:46:08.056  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:46:08.056  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 13:46:08.056  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:46:08.066  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 13:46:08.066  3178  3280 D HeadsetStateMachine: Disconnected process message: 10,
,08-24 13:46:08.076  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:46:08.076  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:46:08.076  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:08.076  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:46:08.076  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:09.856   292   292 E SMD     : DCD OFF
,08-24 13:46:12.856   292   292 E SMD     : DCD OFF
,08-24 13:46:15.856   292   292 E SMD     : DCD OFF
,08-24 13:46:18.036  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:46:18.116  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:46:18.856   292   292 E SMD     : DCD OFF
,08-24 13:46:21.866   292   292 E SMD     : DCD OFF
,08-24 13:46:24.866   292   292 E SMD     : DCD OFF
,08-24 13:46:27.866   292   292 E SMD     : DCD OFF
,08-24 13:46:28.076  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:46:28.176  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:46:30.866   292   292 E SMD     : DCD OFF
,08-24 13:46:31.706  1016  1312 E Watchdog: !@Sync 49,
,08-24 13:46:33.866   292   292 E SMD     : DCD OFF
,08-24 13:46:36.866   292   292 E SMD     : DCD OFF
,08-24 13:46:38.086  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:46:38.246  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:46:38.246  1016  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:46:38.246  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 13:46:38.246  1016  1496 D BatteryService: stay LED for fully charged
08-24 13:46:38.246  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:46:38.256  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:46:38.256  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:46:38.256  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:46:38.256  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:46:38.256  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:46:38.256  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:46:38.266  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:46:38.266  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:46:38.286  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:46:38.286  1179  1179 D SViewCoverView: level :100 plugged : 2,
08-24 13:46:38.286  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:46:38.286  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:46:38.286  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:39.876   292   292 E SMD     : DCD OFF
,08-24 13:46:42.876   292   292 E SMD     : DCD OFF
,08-24 13:46:45.876   292   292 E SMD     : DCD OFF
,08-24 13:46:48.096  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:46:48.316  1016  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:46:48.876   292   292 E SMD     : DCD OFF
,08-24 13:46:51.876   292   292 E SMD     : DCD OFF
,08-24 13:46:54.876   292   292 E SMD     : DCD OFF
,08-24 13:46:57.876   292   292 E SMD     : DCD OFF
,08-24 13:46:58.126  1016  3363 D SSRM:n  : SIOP:: AP = 270
,08-24 13:46:58.376  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 13:46:58.376  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 13:46:58.376  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 13:46:58.376  1016  1497 D BatteryService: stay LED for fully charged
08-24 13:46:58.376  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 13:46:58.386  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 13:46:58.386  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 13:46:58.386  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 13:46:58.386  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 13:46:58.386  1016  1016 I MotionRecognitionService: Plugged
,08-24 13:46:58.386  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 13:46:58.396  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 13:46:58.396  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 13:46:58.406  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 13:46:58.416  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 13:46:58.416  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:58.416  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 13:46:58.416  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 13:46:58.676  1016  1095 V AlarmManager: waitForAlarm result :4
,08-24 13:46:58.676  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-24 13:46:58.676  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 13:46:58.686  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 13:46:58.686  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 13:46:58.696  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:46:58.696  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-24 13:46:58.696  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-24 13:46:58.696  1179  1179 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-24 13:46:58.716  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:46:58.716  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:46:58.736  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:46:58.756  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 13:46:58.956  1016  1086 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-24 13:46:58.956  1016  1085 D TimaService: TimaServiceHandler.handleMessage what =1
08-24 13:46:58.956  1016  1086 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-24 13:46:59.046  1016  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-24 13:46:59.046  1016  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,08-24 13:46:59.056  1016  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
08-24 13:46:59.056  1016  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,08-24 13:46:59.226  1016  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,08-24 13:46:59.376  1016  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,08-24 13:46:59.376  1016  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,08-24 13:46:59.626  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 13:46:59.626  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:46:59.626  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 13:46:59.626  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,08-24 13:46:59.986  1016  1095 V AlarmManager: waitForAlarm result :8
,08-24 13:47:00.846  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-24 13:47:00.846  1016  1086 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-24 13:47:00.856  1016  1086 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-24 13:47:00.856  1016  1086 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,TIME-OUT KILL (timeout was 1400000ms),08-24 13:47:00.876   292   292 E SMD     : DCD OFF
08-24 13:47:01.176  7444  7444 D AndroidRuntime: 
08-24 13:47:01.176  7444  7444 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 13:47:01.176  7444  7444 D AndroidRuntime: CheckJNI is OFF
08-24 13:47:01.176  7444  7444 D AndroidRuntime: readGMSProperty: start
08-24 13:47:01.176  7444  7444 D AndroidRuntime: readGMSProperty: already setted!!
08-24 13:47:01.176  7444  7444 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 13:47:01.176  7444  7444 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 13:47:01.176  7444  7444 D AndroidRuntime: readGMSProperty: end
08-24 13:47:01.176  7444  7444 D AndroidRuntime: addProductProperty: start
08-24 13:47:01.296  7444  7444 E AffinityControl: AffinityControl: registerfunction enter
08-24 13:47:01.316  7444  7444 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 13:47:01.326  1016  1457 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-24 13:47:01.326  1016  1457 D PackageManager: START PACKAGE DELETE: observer{596759161}
08-24 13:47:01.326  1016  1457 D PackageManager: pkg{<packageName>}
08-24 13:47:01.326  1016  1457 D PackageManager: user{0}
08-24 13:47:01.326  1016  1457 D PackageManager: caller{2000}
08-24 13:47:01.326  1016  1457 D PackageManager: flags{2}
08-24 13:47:01.326  1016  1457 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-24 13:47:01.326  1016  1457 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-24 13:47:01.326  1016  1457 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 13:47:01.326  1016  1457 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 13:47:01.336  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-24 13:47:01.336  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 13:47:01.336  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-24 13:47:01.336  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-24 13:47:01.336  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-24 13:47:01.336  1016  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
08-24 13:47:01.356  1016  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-24 13:47:01.356  1016  1043 I ActivityManager: Killing 6730:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
08-24 13:47:01.436  1016  1057 W PackageSettings: Skipping PackageSetting{2750e77b com.example.hello/10168} due to missing metadata
08-24 13:47:01.436  1016  1479 I WindowState: WIN DEATH: Window{2c296224 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:47:01.436   257   438 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
08-24 13:47:01.436   257   441 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
08-24 13:47:01.446  1016  1479 D InputDispatcher: Focus left window: 6730
08-24 13:47:01.456   257  1039 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
08-24 13:47:01.456  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 13:47:01.456  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:47:01.466  1016  1043 I ActivityManager:   Force finishing activity ActivityRecord{2409b1c4 u0 com.test.thalitest/.MainActivity t2}
08-24 13:47:01.486  1016  1043 D InputDispatcher: Focused application released
08-24 13:47:01.486  1016  1043 D FocusedStackFrame: Set to : 0
08-24 13:47:01.486  1016  1043 W ActivityManager: mDVFSHelper.acquire()
08-24 13:47:01.496  1016  1043 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-24 13:47:01.496  1016  1325 W ActivityManager: Spurious death for ProcessRecord{15cdabbe 6730:com.test.thalitest/u0a171}, curProc for 6730: null
08-24 13:47:01.496  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
08-24 13:47:01.516  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-24 13:47:01.546  1482  1482 D Launcher: onRestart, Launcher: 131911430
08-24 13:47:01.566  2636  2636 I art     : Explicit concurrent mark sweep GC freed 19470(1111KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 803us total 46.087ms
08-24 13:47:01.576  1016  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 13:47:01.586  2024  2210 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 13:47:01.586  1871  1871 E SamsungIME: mOCRHelper is null
08-24 13:47:01.596  4808  4808 I art     : Explicit concurrent mark sweep GC freed 24526(1509KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 12MB/17MB, paused 1.344ms total 90.108ms
08-24 13:47:01.596  1451  1451 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 13:47:01.606  1016  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-24 13:47:01.606  1016  1124 V NetworkStats: performPollLocked(flags=0x3)
08-24 13:47:01.606  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 13:47:01.616  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 13:47:01.616  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 13:47:01.626  1016  1124 V NetworkStats: performPollLocked() took 20ms
08-24 13:47:01.636  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 13:47:01.636  1016  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-24 13:47:01.636  1016  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-24 13:47:01.636  1016  1042 W TextServicesManagerService: no available spell checker services found
08-24 13:47:01.636  1482  1482 D Launcher: onStart, Launcher: 131911430
08-24 13:47:01.636  1482  1482 D Launcher.HomeView: onStart
08-24 13:47:01.636  1482  1482 D Launcher: onResume, Launcher: 131911430
08-24 13:47:01.646  1016  1325 D SettingsProvider: name = kids_home_mode
08-24 13:47:01.646  1016  1325 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 13:47:01.646  1016  1325 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 13:47:01.646  1016  1325 D SettingsProvider: selectionArgs: false
08-24 13:47:01.646  1016  1325 D SettingsProvider: selectionArgs: 10006
08-24 13:47:01.646  1016  1325 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 13:47:01.646  1016  1325 D SettingsProvider: ret = -1
08-24 13:47:01.646  1482  1482 D Launcher.HomeView: onResume
08-24 13:47:01.646  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 24 13:47:01 GMT+02:00 2016
08-24 13:47:01.646  1016  3173 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-24 13:47:01.646  1016  3173 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-24 13:47:01.646  1016  3173 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:47:01.646  1016  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 13:47:01.646  1016  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-24 13:47:01.656  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
08-24 13:47:01.656  1441  1441 D RegisteredServicesCache: empty dynamic service
08-24 13:47:01.656  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-24 13:47:01.656  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-24 13:47:01.666  1016  1496 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-24 13:47:01.666  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:01.666  1016  1496 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-24 13:47:01.666  1482  1482 D MenuAppsGridFragment: onResume
08-24 13:47:01.666  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-24 13:47:01.676  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-24 13:47:01.676  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
08-24 13:47:01.676  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
08-24 13:47:01.676  6643  6643 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-24 13:47:01.686  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:01.706  1016  1028 D ActivityManager: handle home activity for 0
08-24 13:47:01.706  1016  1028 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-24 13:47:01.706  1016  1028 D KnoxTimeoutHandler: post home show event for user 0
08-24 13:47:01.706  1016  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 13:47:01.706  1016  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 13:47:01.706  1016  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 13:47:01.706  1016  1481 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-24 13:47:01.706  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-24 13:47:01.706  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:47:01.706  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 13:47:01.706  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-24 13:47:01.706  1482  1482 D Launcher.HomeView: onPause
08-24 13:47:01.706  6643  6643 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-24 13:47:01.706  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-24 13:47:01.706  1016  1312 E Watchdog: !@Sync 50
08-24 13:47:01.706  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-24 13:47:01.716  2849  2849 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-24 13:47:01.716  1016  1218 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-24 13:47:01.716  1016  1218 D SecContentProvider2: mCursor = null
08-24 13:47:01.726  6643  6643 D elm:15121: ElmAgentService : onCreate()
08-24 13:47:01.726  6643  7459 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-24 13:47:01.726  6643  7459 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-24 13:47:01.726  6643  7459 D elm:15121: MDMBridge.getInstance()
08-24 13:47:01.726  6643  7459 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-24 13:47:01.736  2849  2849 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-24 13:47:01.736  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 13:47:01.736  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 13:47:01.736  1016  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-24 13:47:01.736  1016  1496 I TactileAssist: enable value -1
08-24 13:47:01.736  1016  1496 I TactileAssist: internal enable value -1
08-24 13:47:01.736  1016  1496 I TactileAssist: intensity value -1
08-24 13:47:01.736  1016  1496 I TactileAssist: saveAppList value true
08-24 13:47:01.736  6643  7459 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-24 13:47:01.756  1016  1016 I art     : Explicit concurrent mark sweep GC freed 78685(7MB) AllocSpace objects, 249(3MB) LOS objects, 33% free, 24MB/37MB, paused 3.065ms total 236.078ms
08-24 13:47:01.756  1016  1057 I art     : WaitForGcToComplete blocked for 210.393ms for cause Explicit
08-24 13:47:01.756  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.756  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.756  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.756  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.766  1016  1496 I TactileAssist: List of disabled apps :
08-24 13:47:01.766   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
08-24 13:47:01.766  2849  7458 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-24 13:47:01.776  7460  7460 E Zygote  : MountEmulatedStorage()
08-24 13:47:01.776  7460  7460 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:47:01.776  7460  7460 E Zygote  : v2
08-24 13:47:01.776  7460  7460 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:01.776  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:01.776  7460  7460 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:47:01.776  7460  7460 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:47:01.776  1016  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7460 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 13:47:01.776  7460  7460 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 13:47:01.786  1016  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-24 13:47:01.786  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.786  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.786  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.786  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.796  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:01.796  7472  7472 E Zygote  : MountEmulatedStorage()
08-24 13:47:01.796  7472  7472 E Zygote  : v2
08-24 13:47:01.796  7472  7472 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:47:01.796  7472  7472 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:01.796  7472  7472 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:47:01.806  7472  7472 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:47:01.806  7472  7472 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 13:47:01.806  1016  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 13:47:01.806  1016  1139 D InputDispatcher: Focus entered window: 1482
08-24 13:47:01.806  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 13:47:01.806  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 13:47:01.806  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-24 13:47:01.806  1016  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7472 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 13:47:01.816  2849  7458 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-24 13:47:01.816  2849  7458 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-24 13:47:01.816  6643  6643 D elm:15121: ElmAgentService : onDestroy().
08-24 13:47:01.826  1016  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 13:47:01.836  7460  7460 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:01.836  1016  1325 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-24 13:47:01.836  7460  7460 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:01.836  2849  7458 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-24 13:47:01.846  7472  7472 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:01.846  7472  7472 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:01.856  1016  1325 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6730 uid 10171
08-24 13:47:01.856  1016  7491 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-24 13:47:01.856  1871  1871 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-24 13:47:01.896  1016  1457 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-24 13:47:01.896  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.896  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.896  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.896  1016  1457 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.916  7493  7493 E Zygote  : MountEmulatedStorage()
08-24 13:47:01.916  7493  7493 I libpersona: KNOX_SDCARD checking this for 10048
08-24 13:47:01.916  7493  7493 E Zygote  : v2
08-24 13:47:01.916  7493  7493 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:01.916  7493  7493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:47:01.916  1016  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-24 13:47:01.916  7493  7493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:47:01.916  7472  7472 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
08-24 13:47:01.916  7493  7493 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-24 13:47:01.926  1016  1457 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7493 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-24 13:47:01.926  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:01.926  2849  7458 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-24 13:47:01.926  1016  1048 W ActivityManager: mDVFSHelper.release()
08-24 13:47:01.926  1016  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d373c2f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1518749
08-24 13:47:01.936  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:01.936  7460  7460 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-24 13:47:01.936  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-24 13:47:01.936  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-24 13:47:01.936  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:47:01.936  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 13:47:01.936  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-24 13:47:01.946  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-24 13:47:01.946  1016  1016 D RCPManagerService: PackageReceiver onReceive()
08-24 13:47:01.946  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-24 13:47:01.946  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.946  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.946  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.946  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:01.946  1016  3173 D SecContentProvider2: uri = -1 selection = getSealedState
08-24 13:47:01.946  1016  3173 D SecContentProvider2: mCursor = null
08-24 13:47:01.946  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-24 13:47:01.946  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-24 13:47:01.946  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
08-24 13:47:01.946  2849  7458 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-24 13:47:01.946  7472  7472 I PopupuiReceiver_KNOX: getSealedState : true
08-24 13:47:01.956  1016  1218 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-24 13:47:01.956  1016  1218 D SecContentProvider2: mCursor = null
08-24 13:47:01.956  2849  7458 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-24 13:47:01.956  7472  7472 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-24 13:47:01.956  7508  7508 E Zygote  : MountEmulatedStorage()
08-24 13:47:01.956  7508  7508 I libpersona: KNOX_SDCARD checking this for 1000
08-24 13:47:01.956  7508  7508 E Zygote  : v2
08-24 13:47:01.956  7508  7508 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:01.956  7508  7508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:47:01.966  1016  1497 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-24 13:47:01.966  1016  1497 D SecContentProvider2: mCursor = null
08-24 13:47:01.966  7472  7472 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-24 13:47:01.966  7472  7472 D PopupuiReceiver: Action package removed
08-24 13:47:01.966  7508  7508 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:47:01.966  7508  7508 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 13:47:01.966  7493  7493 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:01.966  7493  7493 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:01.976  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
08-24 13:47:01.976  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-24 13:47:01.976  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:01.986  1016  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 13:47:01.986  1016  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 13:47:01.986  1016  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 13:47:01.996  1016  1479 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 13:47:01.996  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.006  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-24 13:47:02.016  7508  7508 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:02.016  7508  7508 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:02.016  1016  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-24 13:47:02.016  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.016  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.016  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.016  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.026  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.036  7524  7524 E Zygote  : MountEmulatedStorage()
08-24 13:47:02.036  7524  7524 E Zygote  : v2
08-24 13:47:02.036  7524  7524 I libpersona: KNOX_SDCARD checking this for 10145
08-24 13:47:02.036  7524  7524 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:02.036  7524  7524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:47:02.036  1016  1481 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7524 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 13:47:02.036  7524  7524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:47:02.036  7524  7524 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 13:47:02.036  7493  7493 D Compatibility: onReceive() it will make start service
08-24 13:47:02.046  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.046  1016  1481 I ActivityManager: Killing 6465:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-24 13:47:02.046  1016  3173 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-24 13:47:02.046  1016  3173 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-24 13:47:02.056  1016  3173 W ActivityManager: userId = 0, bbcId = -10000
08-24 13:47:02.056  1016  3173 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 13:47:02.056  1016  3173 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
08-24 13:47:02.066  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.066  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-24 13:47:02.066  1016  1057 I art     : Explicit concurrent mark sweep GC freed 14450(928KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 4.026ms total 295.332ms
08-24 13:47:02.076  7524  7524 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:02.076  7508  7508 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 13:47:02.076  7524  7524 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:02.076  7493  7534 D Compatibility: onHandleIntent()
08-24 13:47:02.076  7493  7534 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-24 13:47:02.076  1016  1479 I ActivityManager: Killing 6496:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-24 13:47:02.076  7493  7534 D Compatibility: found: 2
08-24 13:47:02.096  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-24 13:47:02.096  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.096  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.096  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.096  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.096  7493  7534 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-24 13:47:02.096  7508  7508 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-24 13:47:02.106  7493  7534 D Compatibility: skipping ResolveInfo{5ca7aa9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-24 13:47:02.106  7493  7534 D Compatibility: considering ResolveInfo{304be82e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-24 13:47:02.106  7493  7534 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-24 13:47:02.106  7493  7534 D Compatibility: enabling receiver ResolveInfo{32a40fcf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-24 13:47:02.106  7541  7541 E Zygote  : MountEmulatedStorage()
08-24 13:47:02.106  7541  7541 E Zygote  : v2
08-24 13:47:02.106  7541  7541 I libpersona: KNOX_SDCARD checking this for 10052
08-24 13:47:02.106  7541  7541 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:02.106  7541  7541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:47:02.106  7541  7541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:47:02.116  7541  7541 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 13:47:02.116  1016  1457 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-24 13:47:02.116  1016  1457 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-24 13:47:02.116  7493  7534 D Compatibility: enabling receiver ResolveInfo{15c5fd5c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-24 13:47:02.116  1016  1479 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7541 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-24 13:47:02.126  7493  7534 D Compatibility: enabling receiver ResolveInfo{29a71865 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-24 13:47:02.126  1016  1028 D PersonaManager: isKioskContainerExistOnDevice
08-24 13:47:02.136  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-24 13:47:02.136  7493  7534 D Compatibility: enabling receiver ResolveInfo{28b2593a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-24 13:47:02.136  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.136  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.136  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.136  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.136  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 13:47:02.146  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.146  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-24 13:47:02.146  1016  1057 D PackageManager: delete codoeFile: 
08-24 13:47:02.156  7493  7534 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-24 13:47:02.156  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.156  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-24 13:47:02.156  7541  7541 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 13:47:02.156  7541  7541 D ActivityThread: Added TimaKeyStore provider
08-24 13:47:02.156  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-24 13:47:02.156  1016  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-24 13:47:02.166  1016  1057 D PackageManager: result of delete: 1{596759161}
08-24 13:47:02.166  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 13:47:02.166  7557  7557 E Zygote  : MountEmulatedStorage()
08-24 13:47:02.166  7557  7557 E Zygote  : v2
08-24 13:47:02.166  7557  7557 I libpersona: KNOX_SDCARD checking this for 10087
08-24 13:47:02.166  7557  7557 I libpersona: KNOX_SDCARD not a persona
08-24 13:47:02.166  7557  7557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 13:47:02.166  7444  7444 D AndroidRuntime: Shutting down VM
08-24 13:47:02.176  7557  7557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 13:47:02.176  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 13:47:02.176  1016  1057 D PackageManager: userId{-1}
08-24 13:47:02.176  1016  1057 D PackageManager: andCode{true}
08-24 13:47:02.176  1016  1479 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7557 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a

```
