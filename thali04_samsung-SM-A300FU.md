#### Test 82337235c8e499b_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-23 13:40:28.198  1016  6300 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 13:40:28.198  1016  6300 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 13:40:28.198  1016  6300 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 13:40:28.198  1016  6300 D BatteryService: stay LED for fully charged
08-23 13:40:28.198  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-23 13:40:28.208  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 13:40:28.208  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 13:40:28.208  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 13:40:28.208  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-23 13:40:28.218  3166  3166 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 13:40:28.218  3166  3269 D HeadsetStateMachine: Disconnected process message: 10
08-23 13:40:28.218  1016  1016 I MotionRecognitionService: Plugged
08-23 13:40:28.218  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-23 13:40:28.228  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 13:40:28.228  1173  1173 D SViewCoverView: level :100 plugged : 2
08-23 13:40:28.238  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 13:40:28.238  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 13:40:28.238  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 13:40:28.568  6675  6675 D AndroidRuntime: 
08-23 13:40:28.568  6675  6675 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:40:28.568  6675  6675 D AndroidRuntime: CheckJNI is OFF
08-23 13:40:28.568  6675  6675 D AndroidRuntime: readGMSProperty: start
08-23 13:40:28.568  6675  6675 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:40:28.568  6675  6675 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:40:28.568  6675  6675 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:40:28.568  6675  6675 D AndroidRuntime: readGMSProperty: end
08-23 13:40:28.568  6675  6675 D AndroidRuntime: addProductProperty: start
08-23 13:40:28.698  6675  6675 E AffinityControl: AffinityControl: registerfunction enter
08-23 13:40:28.728  6675  6675 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 13:40:28.738  1016  1483 E PersonaManagerService: inState():  stateMachine is null !!
08-23 13:40:28.738  1016  1483 I PersonaManagerService: PersonaId don't exist
08-23 13:40:28.738  1016  1483 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 13:40:28.748  1016  1483 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 13:40:28.758  1016  1483 W ActivityManager: mDVFSHelper.acquire()
08-23 13:40:28.758   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-23 13:40:28.768   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-23 13:40:28.778  1016  1483 D FocusedStackFrame: Set to : 0
08-23 13:40:28.778  1016  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:28.778  1016  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:28.778  1016  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:28.778  1016  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:28.788  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 13:40:28.788  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 13:40:28.798  6686  6686 E Zygote  : MountEmulatedStorage()
08-23 13:40:28.798  6686  6686 I libpersona: KNOX_SDCARD checking this for 10171
08-23 13:40:28.798  6686  6686 E Zygote  : v2
08-23 13:40:28.798  6686  6686 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:28.798  6686  6686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:28.798  1016  1483 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6686 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 13:40:28.798  1016  1483 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 13:40:28.798  1016  1483 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 13:40:28.798  1016  1483 D InputDispatcher: Focused application set to: xxxx
08-23 13:40:28.798  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 13:40:28.798  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 13:40:28.798  1016  1483 D InputDispatcher: Focus left window: 1484
08-23 13:40:28.808   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-23 13:40:28.808  6675  6675 D AndroidRuntime: Shutting down VM
08-23 13:40:28.808  6686  6686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:28.808  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 13:40:28.808  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:28.808  6686  6686 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 13:40:28.828  6686  6686 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:28.828  6686  6686 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:28.828  1016  1446 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 13:40:28.838  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 13:40:28.838  1016  1016 V ActivityManager: Display changed displayId=0
08-23 13:40:28.858  1016  1446 D PersonaManager: isKioskContainerExistOnDevice
08-23 13:40:28.868  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 13:40:28.898   258   446 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-23 13:40:28.898   258  1154 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-23 13:40:28.898  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{2aaf6130 token=android.os.BinderProxy@3551a70c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 13:40:28.908  1484  1484 D Launcher: onTrimMemory. Level: 20
08-23 13:40:28.968  6686  6686 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-23 13:40:29.008  6675  6675 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 13:40:29.018  6686  6686 I cr.library_loader: Time to load native libraries: 6 ms (timestamps 6960-6966)
08-23 13:40:29.018  6686  6686 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 13:40:29.038  6686  6686 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c8d5e88}
08-23 13:40:29.038  6686  6686 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 13:40:29.058  6686  6686 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 13:40:29.098  6686  6686 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-23 13:40:29.098  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:40:29.098  6686  6686 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 13:40:29.138  6686  6686 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 13:40:29.138  6686  6686 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 13:40:29.138  6686  6686 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 13:40:29.138  6686  6686 I Adreno-EGL: Local Branch: 
08-23 13:40:29.138  6686  6686 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 13:40:29.138  6686  6686 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 13:40:29.138  6686  6686 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-23 13:40:29.218   288   288 E SMD     : DCD OFF
08-23 13:40:29.238  6686  6686 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:40:29.248  6686  6686 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-23 13:40:29.248  6686  6686 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-23 13:40:29.258  6686  6686 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-23 13:40:29.258  6686  6686 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-23 13:40:29.358  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{18825334 u0 com.test.thalitest/.MainActivity t2}
08-23 13:40:29.388  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:40:29.398  6686  6686 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 13:40:29.408  6686  6686 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 13:40:29.408  6686  6686 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-23 13:40:29.418  6686  6686 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-23 13:40:29.418  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:40:29.418  6686  6686 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:40:29.538  6686  6727 D OpenGLRenderer: Render dirty regions requested: true
08-23 13:40:29.548  1016  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 13:40:29.548  1016  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 13:40:29.548  1016  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 13:40:29.548  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 13:40:29.548  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 13:40:29.548  6686  6714 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-23 13:40:29.558  6686  6686 V ActivityThread: updateVisibility : ActivityRecord{173ac0e8 token=android.os.BinderProxy@2bcdb385 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 13:40:29.558  6686  6686 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 13:40:29.558  6686  6686 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 13:40:29.568   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-23 13:40:29.578  1016  6300 D InputDispatcher: Focus entered window: 6686
08-23 13:40:29.588  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 13:40:29.588  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:29.588  6686  6686 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 13:40:29.588  6686  6727 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 13:40:29.588  6686  6727 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-23 13:40:29.588  6686  6727 D OpenGLRenderer: Enabling debug mode 0
08-23 13:40:29.618  1016  1483 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 13:40:29.618  1173  1173 I StatusBar: Icon Only
08-23 13:40:29.618  1173  1173 D PanelView: There is/are notification(s) 
08-23 13:40:29.618  1016  6732 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 13:40:29.638  1016  1046 I ActivityManager: Displayed Component not be shown by security: +779ms (total +857ms)
08-23 13:40:29.638  1016  1046 W ActivityManager: mDVFSHelper.release()
08-23 13:40:29.638  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{18825334 u0 com.test.thalitest/.MainActivity t2} time:107582
08-23 13:40:29.648   258  1154 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-23 13:40:29.648  6686  6686 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 13:40:29.648  6686  6686 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bcdb385 time:107592
08-23 13:40:29.648   258   442 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-23 13:40:29.648  1833  1833 I SamsungIME: getCurrentCandidateView
08-23 13:40:29.688  6686  6686 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6686
08-23 13:40:29.738  1833  1833 D SamsungIME: Dismiss ExpandCandiate
,08-23 13:40:29.828  6686  6686 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:40:29.898  1833  1833 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 13:40:29.938  1833  1833 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 13:40:29.948  1833  1833 I SamsungIME: KeybaordView init() : load resources
,08-23 13:40:29.968  6686  6731 D jxcore_app_log: JniHelper::setJavaVM(0xb799c2b0), pthread_self() = -1208833640
,08-23 13:40:29.978  1833  1833 I SamsungIME: getCurrentKeyboard
08-23 13:40:29.978  1833  1833 I SamsungIME: getTextKeyboard
,08-23 13:40:29.978  6686  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:40:29.978  6686  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:40:29.978  6686  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:40:29.978  6686  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:40:29.978  6686  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:40:29.978  6686  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1380e37e added. We now have 1 listener(s)
,08-23 13:40:29.988  6686  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-23 13:40:29.988  6686  6731 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 13:40:29.988  6686  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 13:40:29.988  6686  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:40:29.998  1833  1833 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 13:40:29.998  6686  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbb87f5 added. We now have 1 listener(s)
,08-23 13:40:29.998  6686  6731 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:40:30.008  6686  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:40:30.008  6686  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 13:40:30.008  6686  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:40:30.008  6686  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:40:30.008  6686  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:40:30.008  6686  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:40:30.018  6686  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-23 13:40:30.018  6686  6731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:40:30.018  6686  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:40:30.018  6686  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:40:30.018  6686  6731 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 13:40:30.018  6686  6731 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 13:40:30.028  6686  6686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:40:30.028  6686  6686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:40:30.058  6686  6686 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:40:30.268  1016  1314 E Watchdog: !@Sync 3
,08-23 13:40:30.628  6686  6741 W jxcore-log: Initializing JXcore engine
08-23 13:40:30.628  6686  6741 W jxcore-log: JXcore engine is ready
,08-23 13:40:30.678  1970  1970 E audit   : type=1400 msg=audit(1471952430.678:205): avc:  denied  { ioctl } for  pid=6741 comm="Thread-1230" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 13:40:30.678  1970  1970 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:30.678  1970  1970 E audit   : type=1300 msg=audit(1471952430.678:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9dd048f8 items=0 ppid=304 ppcomm=main pid=6741 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1230" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 13:40:30.678  1970  1970 E audit   : type=1320 msg=audit(1471952430.678:205): 
,08-23 13:40:30.688  6686  6741 W jxcore-log: Starting JXcore engine
,08-23 13:40:30.798  6686  6741 W jxcore-log: Platform android
08-23 13:40:30.798  6686  6741 W jxcore-log: 
08-23 13:40:30.798  6686  6741 W jxcore-log: Process ARCH arm
08-23 13:40:30.798  6686  6741 W jxcore-log: 
,08-23 13:40:30.998  6686  6741 I jxcore-log: JXcore Cordova bridge is ready!,
08-23 13:40:30.998  6686  6741 I jxcore-log: 
08-23 13:40:30.998  6686  6741 W jxcore-log: JXcore engine is started
,08-23 13:40:31.008  6686  6731 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,08-23 13:40:31.008  6686  6686 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:40:31.038  6686  6741 E jxcore  : Error!: missing name after . operator
08-23 13:40:31.038  6686  6741 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:40:31.038  6686  6686 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 13:40:31.038  6686  6686 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:40:31.048  1016  6300 D FocusedStackFrame: Set to : 0
08-23 13:40:31.048  1016  6300 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 13:40:31.048  1016  6300 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 13:40:31.048  1016  6300 D InputDispatcher: Focused application set to: xxxx
08-23 13:40:31.048  1016  6300 D InputDispatcher: Focus left window: 6686
08-23 13:40:31.048  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 13:40:31.048  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:31.058  1016  6300 I ActivityManager: Killing 6352:com.samsung.helphub/1000 (adj 15): empty #21
,08-23 13:40:31.068  6686  6686 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 13:40:31.068  6686  6731 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
08-23 13:40:31.068  6686  6686 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:40:31.068  6686  6686 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:40:31.068  6686  6686 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:40:31.068  6686  6686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:40:31.068  6686  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:40:31.068  6686  6686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1380e37e removed from the list
08-23 13:40:31.068  6686  6686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:40:31.068  6686  6686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbb87f5 removed from the list
08-23 13:40:31.068  6686  6686 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:40:31.068  6686  6686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 13:40:31.068  6686  6686 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:40:31.078   258   442 I SurfaceFlinger: id=13 Removed NainActivit (6/8),
08-23 13:40:31.078   258   446 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-23 13:40:31.088  1016  1330 W ActivityManager: mDVFSHelper.acquire()
,08-23 13:40:31.088  1016  1330 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-23 13:40:31.108  1484  1484 D Launcher: onRestart, Launcher: 13360647
,08-23 13:40:31.108  1484  1484 D Launcher: onStart, Launcher: 13360647
08-23 13:40:31.108  1484  1484 D Launcher.HomeView: onStart
,08-23 13:40:31.108  1484  1484 D Launcher: onResume, Launcher: 13360647
,08-23 13:40:31.108  1016  6300 D SettingsProvider: name = kids_home_mode
08-23 13:40:31.108  1016  6300 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 13:40:31.108  1016  6300 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 13:40:31.108  1016  6300 D SettingsProvider: selectionArgs: false
08-23 13:40:31.108  1016  6300 D SettingsProvider: selectionArgs: 10006
08-23 13:40:31.108  1016  6300 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 13:40:31.108  1016  6300 D SettingsProvider: ret = -1
08-23 13:40:31.108  1484  1484 D Launcher.HomeView: onResume
,08-23 13:40:31.118  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 13:40:31.128  1484  1484 D MenuAppsGridFragment: onResume
,08-23 13:40:31.128  1016  1330 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
08-23 13:40:31.128  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-23 13:40:31.128  1016  1330 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
08-23 13:40:31.128  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-23 13:40:31.128  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.128  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.128  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-23 13:40:31.138  1016  1330 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.138  1016  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.138  1016  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
08-23 13:40:31.138  1016  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-23 13:40:31.138  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.138  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.138  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.138  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.148  6745  6745 E Zygote  : MountEmulatedStorage()
08-23 13:40:31.148  6745  6745 E Zygote  : v2
08-23 13:40:31.148  6745  6745 I libpersona: KNOX_SDCARD checking this for 10039
08-23 13:40:31.148  6745  6745 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:31.158  6745  6745 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:31.158  1016  1330 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6745 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-23 13:40:31.158  1016  1457 D ActivityManager: handle home activity for 0
08-23 13:40:31.158  1016  1457 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-23 13:40:31.158  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 13:40:31.158  1016  1457 D KnoxTimeoutHandler: post home show event for user 0
08-23 13:40:31.158  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-23 13:40:31.158  1016  1457 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 13:40:31.158  1016  1457 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 13:40:31.158  1016  1457 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 13:40:31.158  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-23 13:40:31.158  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 13:40:31.158  1484  1484 D Launcher.HomeView: onPause
08-23 13:40:31.158  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 13:40:31.158  6745  6745 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:31.158  6745  6745 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:31.168  1016  1041 W ActivityManager: userId = 0, bbcId = -10000,
08-23 13:40:31.168  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.168  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-23 13:40:31.168  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.168  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.168  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
08-23 13:40:31.168  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,08-23 13:40:31.178  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.178  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.178  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.178  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.188  6760  6760 E Zygote  : MountEmulatedStorage()
08-23 13:40:31.188  6760  6760 E Zygote  : v2
08-23 13:40:31.188  6760  6760 I libpersona: KNOX_SDCARD checking this for 10089
08-23 13:40:31.188  6760  6760 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:31.188  6760  6760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:31.188  6760  6760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:31.198  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6760 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-23 13:40:31.198  6760  6760 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-23 13:40:31.198  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.198  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.198  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-23 13:40:31.198  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,08-23 13:40:31.198  6745  6745 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:31.198  6745  6745 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:31.198  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.198  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.198  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.198  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.218   304   304 I art     : Explicit concurrent mark sweep GC freed 8679(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 665us total 25.519ms
,08-23 13:40:31.218  6760  6760 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:31.218  6760  6760 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:31.238   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.980ms
,08-23 13:40:31.258   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.226ms
,08-23 13:40:31.268  6775  6775 E Zygote  : MountEmulatedStorage()
,08-23 13:40:31.268  6775  6775 E Zygote  : v2
08-23 13:40:31.268  6775  6775 I libpersona: KNOX_SDCARD checking this for 10139
08-23 13:40:31.268  6775  6775 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:31.268  6775  6775 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:31.268  6775  6775 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 13:40:31.268  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6775 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,08-23 13:40:31.268  6775  6775 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:31.288  1016  1507 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.288  1016  1507 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1484, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-23 13:40:31.288  1016  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.288  1016  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-23 13:40:31.288  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.288  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.288  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-23 13:40:31.298  2552  2552 D Recents_RecreateReceiver: onReceive by home
,08-23 13:40:31.298  1016  1482 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.298  1016  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.298  1016  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-23 13:40:31.298  1016  1482 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,08-23 13:40:31.298  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.298  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.298  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.298  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.298   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-23 13:40:31.308  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 13:40:31.308  6775  6775 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:31.308  6775  6775 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:31.308  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 13:40:31.318  6745  6745 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 13:40:31.318  1016  6300 D InputDispatcher: Focus entered window: 1484
,08-23 13:40:31.318  6745  6745 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:40:31.318  6745  6745 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:31.318  6745  6745 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 13:40:31.318  6745  6745 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 13:40:31.318  6745  6745 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 13:40:31.318  6745  6745 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 13:40:31.318  6760  6760 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:31.318  6760  6760 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-23 13:40:31.318  1484  1484 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 13:40:31.318  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 13:40:31.318  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 13:40:31.318  6790  6790 E Zygote  : MountEmulatedStorage()
,08-23 13:40:31.318  6790  6790 E Zygote  : v2
08-23 13:40:31.318  6790  6790 I libpersona: KNOX_SDCARD checking this for 10084
08-23 13:40:31.318  6790  6790 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:31.318  6790  6790 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:31.328  6790  6790 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 13:40:31.328  1016  1482 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6790 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-23 13:40:31.338  6743  6743 D AndroidRuntime: 
08-23 13:40:31.338  6743  6743 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:40:31.338  6790  6790 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-23 13:40:31.338  6743  6743 D AndroidRuntime: CheckJNI is OFF
08-23 13:40:31.338  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{2aaf6130 token=android.os.BinderProxy@3551a70c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-23 13:40:31.338  6743  6743 D AndroidRuntime: readGMSProperty: start
08-23 13:40:31.338  6743  6743 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:40:31.338  6743  6743 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:40:31.338  6743  6743 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:40:31.338  6743  6743 D AndroidRuntime: readGMSProperty: end
08-23 13:40:31.338  6743  6743 D AndroidRuntime: addProductProperty: start
08-23 13:40:31.338  1484  1484 D Launcher.HomeView: onStop
,08-23 13:40:31.348  1016  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 13:40:31.348  1173  1173 I StatusBar: Icon Only
08-23 13:40:31.348  1173  1173 D PanelView: There is/are notification(s) 
,08-23 13:40:31.348  1016  6799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 13:40:31.358  1833  1833 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-23 13:40:31.358  6686  6686 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-23 13:40:31.368  6790  6790 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:31.368  6790  6790 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:31.378  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-23 13:40:31.378  6775  6775 V TaskCloserActivity: TaskCloserActivity enter()
,08-23 13:40:31.388  1484  1484 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3551a70c time:109332
,08-23 13:40:31.398  6775  6775 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-23 13:40:31.398  6790  6790 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 13:40:31.398  1016  1250 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.398  1016  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.398  1016  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-23 13:40:31.398  1016  1250 I ActivityManager: Killing 6384:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-23 13:40:31.418  1016  1446 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.418  1016  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.418  1016  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
08-23 13:40:31.418  1016  1446 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,08-23 13:40:31.418  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.418  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.418  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.418  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.438  6817  6817 E Zygote  : MountEmulatedStorage(),
08-23 13:40:31.438  6817  6817 E Zygote  : v2
08-23 13:40:31.438  6817  6817 I libpersona: KNOX_SDCARD checking this for 10135,
08-23 13:40:31.438  6817  6817 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:31.438  1016  1446 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6817 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,08-23 13:40:31.438  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:31.438  1016  1446 I ActivityManager: Killing 6413:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-23 13:40:31.438  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:31.438  1016  1046 W ActivityManager: mDVFSHelper.release()
,08-23 13:40:31.438  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3cc7ca26 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:109388
,08-23 13:40:31.438  1016  1446 I ActivityManager: Killing 6444:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-23 13:40:31.438  6817  6817 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:31.468  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:31.468  6817  6817 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:31.478  6743  6743 E AffinityControl: AffinityControl: registerfunction enter
,08-23 13:40:31.478  1016  1250 D PersonaManager: isKioskContainerExistOnDevice
,08-23 13:40:31.488  6817  6817 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-23 13:40:31.488  6817  6817 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 13:40:31.488  6817  6817 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 13:40:31.488  6817  6817 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-23 13:40:31.488  6817  6817 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 13:40:31.508  6743  6743 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:40:31.528  1016  1457 I ActivityManager: Killing 6483:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-23 13:40:31.538  1016  1028 D PackageManager: START PACKAGE DELETE: observer{543421655}
08-23 13:40:31.538  1016  1028 D PackageManager: pkg{<packageName>}
08-23 13:40:31.538  1016  1028 D PackageManager: user{0}
08-23 13:40:31.538  1016  1028 D PackageManager: caller{2000}
08-23 13:40:31.538  1016  1028 D PackageManager: flags{2}
08-23 13:40:31.538  1016  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 13:40:31.538  1016  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 13:40:31.538  1016  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 13:40:31.538  1016  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 13:40:31.538  1016  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 13:40:31.538  1016  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 13:40:31.538  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 13:40:31.538  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 13:40:31.538  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 13:40:31.538  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 13:40:31.538  1016  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-23 13:40:31.548  6745  6745 D NearbySource: Nearby Source Create!
08-23 13:40:31.548  6745  6745 D NearbyContext: Nearby Context Create!
,08-23 13:40:31.558  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-23 13:40:31.558  1016  1041 I ActivityManager: Killing 6686:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 13:40:31.588   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-23 13:40:31.588   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 13:40:31.588  6745  6745 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-23 13:40:31.588  6745  6745 D SLinkSource: Samsung link source created
,08-23 13:40:31.628  1016  1055 W PackageSettings: Skipping PackageSetting{2d0f34d8 com.example.hello/10168} due to missing metadata
,08-23 13:40:31.668  1016  1482 W ActivityManager: Spurious death for ProcessRecord{3472f1c4 6686:com.test.thalitest/u0a171}, curProc for 6686: null
,08-23 13:40:31.678  1016  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-23 13:40:31.688  1016  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 13:40:31.738  1833  1833 E SamsungIME: mOCRHelper is null
,08-23 13:40:31.748  2623  2623 I art     : Explicit concurrent mark sweep GC freed 18625(1075KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.392ms total 54.482ms
,08-23 13:40:31.758  1460  1460 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 13:40:31.768  1016  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 13:40:31.778  1016  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-23 13:40:31.778  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:40:31.778  1016  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-23 13:40:31.798  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 13:40:31.798  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 13:40:31.808  1016  1124 V NetworkStats: performPollLocked() took 26ms
08-23 13:40:31.808  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 13:40:31.808  1016  1457 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 13:40:31.808  4677  4677 I art     : Explicit concurrent mark sweep GC freed 4916(287KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 12MB/16MB, paused 1.228ms total 128.557ms
,08-23 13:40:31.818  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-23 13:40:31.828  1441  1441 D RegisteredServicesCache: empty dynamic service
,08-23 13:40:31.838  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 13:40:31.848  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-23 13:40:31.848  6745  6836 D ContactProvider: getAllContactInfoList Start
,08-23 13:40:31.848   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 13:40:31.848   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 13:40:31.878  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:40:31.878  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 13:40:31.908  1016  1016 I art     : Explicit concurrent mark sweep GC freed 53016(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 2.757ms total 216.802ms
,08-23 13:40:31.908  1016  1055 I art     : WaitForGcToComplete blocked for 200.503ms for cause Explicit
,08-23 13:40:31.948  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-23 13:40:31.948  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 13:40:31.958  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 13:40:31.958  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 13:40:31.958  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-23 13:40:31.958  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-23 13:40:31.958  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-23 13:40:32.028  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 13:40:32.028  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 13:40:32.028  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 13:40:32.028  1016  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-23 13:40:32.028  1016  3346 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 13:40:32.028  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 13:40:32.038  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-23 13:40:32.068  1016  1055 I art     : Explicit concurrent mark sweep GC freed 13522(838KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 3.217ms total 160.521ms
,08-23 13:40:32.068  1016  1028 I art     : WaitForGcToComplete blocked for 315.972ms for cause Explicit
,08-23 13:40:32.108  1016  1055 D PackageManager: delete codoeFile: 
,08-23 13:40:32.118  1016  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-23 13:40:32.118  1016  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-23 13:40:32.118  1016  1055 D PackageManager: result of delete: 1{543421655}
,08-23 13:40:32.118  6743  6743 D AndroidRuntime: Shutting down VM
,08-23 13:40:32.128  1016  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 13:40:32.128  1016  1055 D PackageManager: userId{-1}
08-23 13:40:32.128  1016  1055 D PackageManager: andCode{true}
,08-23 13:40:32.128  1016  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 13:40:32.218   288   288 E SMD     : DCD OFF
,08-23 13:40:32.228  1016  1028 I art     : Explicit concurrent mark sweep GC freed 5472(277KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.492ms total 157.536ms
,08-23 13:40:32.228  1016  1077 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-23 13:40:32.228  1016  1077 D SecContentProvider2: mCursor = null
08-23 13:40:32.228  2011  2210 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:40:32.228  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 13:40:32.228  1016  1040 W TextServicesManagerService: no available spell checker services found
08-23 13:40:32.228  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-23 13:40:32.238  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.238  1016  6838 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-23 13:40:32.248  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.248  6745  6745 D GalleryCacheReady: Receive : home resume
,08-23 13:40:32.248  1016  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:32.248  1016  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:32.248  1016  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-23 13:40:32.248  6006  6006 D Mms/UIEventReceiver: ui event
,08-23 13:40:32.258  1016  1456 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-23 13:40:32.258  1016  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:32.258  1016  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:32.258  1016  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-23 13:40:32.258  6775  6775 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-23 13:40:32.258  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.268  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.278  2815  2815 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 13:40:32 GMT+02:00 2016
,08-23 13:40:32.278  1016  1483 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-23 13:40:32.278  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-23 13:40:32.278  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:32.278  1016  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:32.278  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 13:40:32.288  2815  2815 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-23 13:40:32.288  1016  1077 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-23 13:40:32.288  1016  1077 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-23 13:40:32.288  6591  6591 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-23 13:40:32.298  2815  2815 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 13:40:32.298  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-23 13:40:32.298  2815  2815 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 13:40:32.298  1016  1250 I TactileAssist: enable value -1
08-23 13:40:32.298  1016  1250 I TactileAssist: internal enable value -1
08-23 13:40:32.298  1016  1250 I TactileAssist: intensity value -1
08-23 13:40:32.298  1016  1250 I TactileAssist: saveAppList value true
,08-23 13:40:32.298  1016  1250 I TactileAssist: List of disabled apps :
,08-23 13:40:32.298  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.298  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.298  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.298  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.308  2815  2815 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 13:40:32.308  2815  6841 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-23 13:40:32.318  6842  6842 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.318  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6842 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 13:40:32.318  6842  6842 E Zygote  : v2
08-23 13:40:32.318  6842  6842 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:32.318  6842  6842 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:32.318  6842  6842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:32.318  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-23 13:40:32.318  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.318  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.318  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.318  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.328  2815  6841 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-23 13:40:32.328  2815  6841 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-23 13:40:32.328  2815  6841 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-23 13:40:32.328  6743  6743 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-23 13:40:32.338  6842  6842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:32.338  6842  6842 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.348  6851  6851 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.348  6851  6851 E Zygote  : v2
08-23 13:40:32.348  6851  6851 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:32.348  6851  6851 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:32.348  6851  6851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.348  1016  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6851 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 13:40:32.358  6851  6851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:32.358  6851  6851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:32.358  1016  6838 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-23 13:40:32.358  1016  6838 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:32.358  1016  6838 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-23 13:40:32.358  1016  6838 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:32.358  1016  6838 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-23 13:40:32.368  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-23 13:40:32.368  6591  6591 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-23 13:40:32.368  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.368  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.368  6591  6591 D elm:15121: ElmAgentService : onCreate()
,08-23 13:40:32.368  6591  6863 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-23 13:40:32.378  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-23 13:40:32.378  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.378  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.378  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.378  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.378  6591  6863 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-23 13:40:32.378  6591  6863 D elm:15121: MDMBridge.getInstance()
08-23 13:40:32.378  6591  6863 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 13:40:32.378  6591  6863 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 13:40:32.388  6873  6873 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.388  6873  6873 E Zygote  : v2
08-23 13:40:32.388  6873  6873 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:32.388  6873  6873 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:32.388  6873  6873 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.388  6851  6851 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.388  6851  6851 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.388  6842  6842 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:32.388  6873  6873 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:32.398  6842  6842 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:32.398  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6873 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 13:40:32.398  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.398  6745  6836 D ContactProvider: getAllContactInfoList End
08-23 13:40:32.408  1016  6838 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-23 13:40:32.408  6745  6836 I syncContacts: thread: 1213, sync time = 685
,08-23 13:40:32.408  6873  6873 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.408  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.408  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.408  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.408  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.408  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 13:40:32.408  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:40:32.408  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 13:40:32.408  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.418  2815  6841 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-23 13:40:32.418  6884  6884 E Zygote  : MountEmulatedStorage()
,08-23 13:40:32.418  6884  6884 E Zygote  : v2
08-23 13:40:32.418  6884  6884 I libpersona: KNOX_SDCARD checking this for 10048
08-23 13:40:32.418  6884  6884 I libpersona: KNOX_SDCARD not a persona,
08-23 13:40:32.418  6884  6884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.428  1016  6838 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6884 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-23 13:40:32.428  6884  6884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:32.428  6884  6884 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-23 13:40:32.428  6851  6851 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-23 13:40:32.438  6873  6873 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.438  6873  6873 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.438  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.438  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.448  2815  6841 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-23 13:40:32.448  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 13:40:32.448  6591  6591 D elm:15121: ElmAgentService : onDestroy().
08-23 13:40:32.448  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 13:40:32.448  1016  1483 D SecContentProvider2: uri = -1 selection = getSealedState
08-23 13:40:32.448  1016  1483 D SecContentProvider2: mCursor = null
08-23 13:40:32.448  6851  6851 I PopupuiReceiver_KNOX: getSealedState : true
08-23 13:40:32.448  1016  1507 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-23 13:40:32.448  1016  1507 D SecContentProvider2: mCursor = null
08-23 13:40:32.448  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:32.448  2815  6841 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-23 13:40:32.448  6851  6851 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-23 13:40:32.448  1016  1456 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-23 13:40:32.448  1016  1456 D SecContentProvider2: mCursor = null
,08-23 13:40:32.448  6851  6851 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-23 13:40:32.448  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 13:40:32.448  6851  6851 D PopupuiReceiver: Action package removed
08-23 13:40:32.448  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 13:40:32.458  1016  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-23 13:40:32.458  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 13:40:32.458  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 13:40:32.458  2815  2815 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 13:40:32.458  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.458  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.458  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.458  1016  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.458  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 13:40:32.458  6884  6884 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.458  6884  6884 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.468  6904  6904 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.468  6904  6904 E Zygote  : v2
08-23 13:40:32.468  6904  6904 I libpersona: KNOX_SDCARD checking this for 10145
08-23 13:40:32.468  6904  6904 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:32.468  1016  1330 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6904 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 13:40:32.478  1016  1330 I ActivityManager: Killing 6514:com.osp.app.signin/u0a36 (adj 15): empty #21
08-23 13:40:32.478  6904  6904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.478  6904  6904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:32.488  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-23 13:40:32.488  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-23 13:40:32.488  6904  6904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.498  6842  6842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-23 13:40:32.498  1016  1456 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-23 13:40:32.498  1016  1456 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-23 13:40:32.498  6873  6873 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 13:40:32.498  6873  6873 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 13:40:32.498  6873  6873 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-23 13:40:32.508  6873  6873 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30),
,08-23 13:40:32.508  1016  1456 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:32.508  1016  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 13:40:32.508  1016  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-23 13:40:32.508  6873  6873 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 13:40:32.508  6873  6873 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 13:40:32.508  6904  6904 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.508  6904  6904 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:32.508  6873  6873 D AndroidRuntime: Shutting down VM
08-23 13:40:32.518  6873  6873 E AndroidRuntime: FATAL EXCEPTION: main
08-23 13:40:32.518  6873  6873 E AndroidRuntime: Process: com.sec.pcw.device, PID: 6873
08-23 13:40:32.518  6873  6873 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-23 13:40:32.518  6873  6873 E AndroidRuntime: 	... 11 more
08-23 13:40:32.518  1016  6838 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-23 13:40:32.518  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.518  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.518  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.518  1016  6838 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.518  6884  6884 D Compatibility: onReceive() it will make start service
08-23 13:40:32.518  6842  6919 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 13:40:32.528  6842  6919 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:32.528  6842  6919 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:40:32.528  6842  6919 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-23 13:40:32.528  6842  6919 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-23 13:40:32.528  6842  6919 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:40:32.538  6920  6920 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.538  6920  6920 E Zygote  : v2
08-23 13:40:32.538  6920  6920 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:32.538  6920  6920 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:32.538  1016  6838 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6920 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 13:40:32.538  6920  6920 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:32.548  6920  6920 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:32.548  1016  1457 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-23 13:40:32.548  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
08-23 13:40:32.548  1016  1457 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-23 13:40:32.548  1016  1457 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:32.548  1016  1457 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:32.548  1016  1457 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
08-23 13:40:32.548  6920  6920 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:32.548  1016  1507 I ActivityManager: Killing 6530:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-23 13:40:32.558  1016  1446 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-23 13:40:32.558  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.558  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.558  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.558  1016  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop176.tmp: open failed: EROFS (Read-only file system)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 13:40:32.558  1016  6928 E DropBoxManagerService: 	... 5 more
08-23 13:40:32.568  6884  6927 D Compatibility: onHandleIntent()
08-23 13:40:32.568  6884  6927 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-23 13:40:32.568  6884  6927 D Compatibility: found: 2
08-23 13:40:32.568  6920  6920 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:32.568  6920  6920 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:32.578  6884  6927 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-23 13:40:32.578  6884  6927 D Compatibility: skipping ResolveInfo{14e35d6e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-23 13:40:32.578  6884  6927 D Compatibility: considering ResolveInfo{1c5a7c0f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-23 13:40:32.578  6884  6927 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-23 13:40:32.578  6884  6927 D Compatibility: enabling receiver ResolveInfo{26ed949c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-23 13:40:32.588  6939  6939 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.588  6939  6939 I libpersona: KNOX_SDCARD checking this for 10052
08-23 13:40:32.588  6939  6939 E Zygote  : v2

```
