#### Test 79763830cfa9ed9_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
,08-26 15:42:22.236  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:42:22.236  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:42:22.236  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:42:22.236  1017  1030 D BatteryService: stay LED for fully charged
08-26 15:42:22.236  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-26 15:42:22.246  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:42:22.246  1017  1017 I MotionRecognitionService: Plugged
08-26 15:42:22.246  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:42:22.246  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:42:22.246  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:42:22.246  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:42:22.256  3175  3175 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:42:22.256  3175  3276 D HeadsetStateMachine: Disconnected process message: 10
08-26 15:42:22.276  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:42:22.276  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:42:22.276  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:42:22.516  6779  6779 D AndroidRuntime: 
08-26 15:42:22.516  6779  6779 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:42:22.516  6779  6779 D AndroidRuntime: CheckJNI is OFF
08-26 15:42:22.526  6779  6779 D AndroidRuntime: readGMSProperty: start
08-26 15:42:22.526  6779  6779 D AndroidRuntime: readGMSProperty: already setted!!
08-26 15:42:22.526  6779  6779 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 15:42:22.526  6779  6779 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 15:42:22.526  6779  6779 D AndroidRuntime: readGMSProperty: end
08-26 15:42:22.526  6779  6779 D AndroidRuntime: addProductProperty: start
08-26 15:42:22.646  6779  6779 E AffinityControl: AffinityControl: registerfunction enter
08-26 15:42:22.676  6779  6779 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 15:42:22.686  1017  1029 E PersonaManagerService: inState():  stateMachine is null !!
08-26 15:42:22.686  1017  1029 I PersonaManagerService: PersonaId don't exist
08-26 15:42:22.686  1017  1029 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 15:42:22.686  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:22.706  1017  1029 W ActivityManager: mDVFSHelper.acquire()
08-26 15:42:22.706   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-26 15:42:22.716   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-26 15:42:22.716  1017  1029 D FocusedStackFrame: Set to : 0
08-26 15:42:22.726  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:22.726  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:22.726  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:22.726  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:22.726  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 15:42:22.726  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 15:42:22.736  6792  6792 E Zygote  : MountEmulatedStorage()
08-26 15:42:22.736  6792  6792 E Zygote  : v2
08-26 15:42:22.736  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 15:42:22.736  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 15:42:22.736  6792  6792 I libpersona: KNOX_SDCARD checking this for 10171
08-26 15:42:22.736  6792  6792 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:22.736   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 15:42:22.736  6792  6792 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:22.736  1017  1029 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6792 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 15:42:22.736  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 15:42:22.736  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:22.746  6792  6792 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:22.746  6792  6792 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 15:42:22.756  1017  1029 D InputDispatcher: Focused application set to: xxxx
08-26 15:42:22.756  1017  1029 D InputDispatcher: Focus left window: 1479
08-26 15:42:22.756  6779  6779 D AndroidRuntime: Shutting down VM
08-26 15:42:22.766  6792  6792 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:22.766  6792  6792 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:22.766  1017  1140 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 15:42:22.776  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 15:42:22.776  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:42:22.776  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:42:22.786  1017  1017 V ActivityManager: Display changed displayId=0
08-26 15:42:22.796  1017  1140 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:42:22.806  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 15:42:22.826   258  2022 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-26 15:42:22.826   258   439 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-26 15:42:22.836  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{25fe3b2f token=android.os.BinderProxy@1f2c2da1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 15:42:22.836  1479  1479 D Launcher: onTrimMemory. Level: 20
08-26 15:42:22.936   288   288 E SMD     : DCD OFF
08-26 15:42:22.936  6792  6792 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 15:42:22.956  6779  6779 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 15:42:22.996  6792  6792 I cr.library_loader: Time to load native libraries: 10 ms (timestamps 6901-6911)
,08-26 15:42:22.996  6792  6792 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 15:42:23.016  6792  6792 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15fc0c62}
08-26 15:42:23.016  6792  6792 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 15:42:23.016  6792  6792 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 15:42:23.056  6792  6792 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 15:42:23.056  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:23.066  6792  6792 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 15:42:23.106  6792  6792 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:23.106  6792  6792 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:23.106  6792  6792 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:23.106  6792  6792 I Adreno-EGL: Local Branch: 
08-26 15:42:23.106  6792  6792 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:23.106  6792  6792 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:23.106  6792  6792 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:23.206  6792  6792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 15:42:23.216  6792  6792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 15:42:23.216  6792  6792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 15:42:23.226  6792  6792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 15:42:23.226  6792  6792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 15:42:23.296  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{1f87f6f8 u0 com.test.thalitest/.MainActivity t2}
,08-26 15:42:23.336  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:23.346  6792  6792 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 15:42:23.356  6792  6792 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-26 15:42:23.356  6792  6792 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 15:42:23.366  6792  6792 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 15:42:23.376  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:23.376  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:23.476  6792  6832 D OpenGLRenderer: Render dirty regions requested: true
,08-26 15:42:23.476  1017  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 15:42:23.476  1017  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:42:23.476  1017  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 15:42:23.476  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:42:23.486  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 15:42:23.486  6792  6819 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 15:42:23.486  6792  6792 V ActivityThread: updateVisibility : ActivityRecord{18c163c2 token=android.os.BinderProxy@6e28d37 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 15:42:23.496  6792  6792 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 15:42:23.496  6792  6792 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 15:42:23.506   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 15:42:23.516  1017  1337 D InputDispatcher: Focus entered window: 6792
,08-26 15:42:23.516  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 15:42:23.516  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:42:23.516  6792  6792 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 15:42:23.516  6792  6832 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 15:42:23.526  6792  6832 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-26 15:42:23.526  6792  6832 D OpenGLRenderer: Enabling debug mode 0
,08-26 15:42:23.536  1017  4967 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 15:42:23.546  1178  1178 I StatusBar: Icon Only,
08-26 15:42:23.546  1017  6836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-26 15:42:23.546  1178  1178 D PanelView: There is/are notification(s) 
,08-26 15:42:23.566  1017  1047 I ActivityManager: Displayed Component not be shown by security: +763ms (total +838ms)
,08-26 15:42:23.566  1017  1047 W ActivityManager: mDVFSHelper.release()
08-26 15:42:23.566  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f87f6f8 u0 com.test.thalitest/.MainActivity t2} time:107481
,08-26 15:42:23.566  6792  6792 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 15:42:23.566  6792  6792 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6e28d37 time:107485
08-26 15:42:23.566   258   439 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 15:42:23.566   258   437 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 15:42:23.596  1918  1918 I SamsungIME: getCurrentCandidateView
,08-26 15:42:23.646  6792  6792 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6792
,08-26 15:42:23.696  1918  1918 D SamsungIME: Dismiss ExpandCandiate
,08-26 15:42:23.836  6792  6792 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 15:42:23.896  1918  1918 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 15:42:23.916  6792  6838 D jxcore_app_log: JniHelper::setJavaVM(0xb783e2b0), pthread_self() = -1210276504
,08-26 15:42:23.926  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 15:42:23.926  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 15:42:23.926  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 15:42:23.926  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 15:42:23.926  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 15:42:23.926  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a321628 added. We now have 1 listener(s)
,08-26 15:42:23.926  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-26 15:42:23.936  6792  6838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 15:42:23.936  6792  6838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:42:23.936  6792  6838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:42:23.936  1918  1918 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 15:42:23.946  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@163b3227 added. We now have 1 listener(s)
,08-26 15:42:23.946  6792  6838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:23.956  1918  1918 I SamsungIME: KeybaordView init() : load resources
,08-26 15:42:23.956  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:42:23.956  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 15:42:23.956  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 15:42:23.956  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 15:42:23.956  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 15:42:23.956  6792  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:23.956  6792  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-26 15:42:23.966  6792  6838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:23.966  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:23.966  6792  6838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-26 15:42:23.966  6792  6838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:23.966  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:23.976  6792  6838 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 15:42:23.976  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:23.986  1918  1918 I SamsungIME: getCurrentKeyboard
08-26 15:42:23.986  1918  1918 I SamsungIME: getTextKeyboard
,08-26 15:42:24.006  6792  6792 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 15:42:24.006  1918  1918 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 15:42:24.346  1017  1302 E Watchdog: !@Sync 3
,08-26 15:42:24.486  6792  6845 W jxcore-log: Initializing JXcore engine
08-26 15:42:24.486  6792  6845 W jxcore-log: JXcore engine is ready
,08-26 15:42:24.546  2028  2028 E audit   : type=1400 msg=audit(1472218944.546:205): avc:  denied  { ioctl } for  pid=6845 comm="Thread-1265" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 15:42:24.546  2028  2028 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:24.546  2028  2028 E audit   : type=1300 msg=audit(1472218944.546:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f3be8f8 items=0 ppid=303 ppcomm=main pid=6845 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1265" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 15:42:24.546  2028  2028 E audit   : type=1320 msg=audit(1472218944.546:205): 
,08-26 15:42:24.556  6792  6845 W jxcore-log: Starting JXcore engine
,08-26 15:42:24.666  6792  6845 W jxcore-log: Platform android
08-26 15:42:24.666  6792  6845 W jxcore-log: 
08-26 15:42:24.666  6792  6845 W jxcore-log: Process ARCH arm
08-26 15:42:24.666  6792  6845 W jxcore-log: 
,08-26 15:42:24.866  6792  6845 I jxcore-log: JXcore Cordova bridge is ready!
08-26 15:42:24.866  6792  6845 I jxcore-log: 
,08-26 15:42:24.866  6792  6845 W jxcore-log: JXcore engine is started
,08-26 15:42:24.876  6792  6838 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 15:42:24.876  6792  6792 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 15:42:24.946   320   320 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 15:42:24.946   320   320 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:42:25.936   288   288 E SMD     : DCD OFF,
,08-26 15:42:28.396  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-26 15:42:28.656  1017  3347 D SSRM:n  : SIOP:: AP = 340
,08-26 15:42:28.936   288   288 E SMD     : DCD OFF,
,08-26 15:42:29.946   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:30.206  5623  5623 D FactoryTest: Not factory mode
,08-26 15:42:30.206  5623  5623 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 15:42:30.206  5623  5623 D MTPRx   : DRIVER_TIME_OUT 60s lapsed,
08-26 15:42:30.206  5623  5623 D MTPRx   : still no open session command from host, so toast
,08-26 15:42:30.206  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-26 15:42:30.206  5623  5623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 15:42:30.206  5623  5623 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114129
,08-26 15:42:30.216  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-26 15:42:30.216  1017  1030 I PersonaManagerService: PersonaId don't exist
08-26 15:42:30.216  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 15:42:30.216  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-26 15:42:30.216  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:30.216  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:30.216  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 15:42:30.226  1017  1030 W ActivityManager: mDVFSHelper.acquire()
,08-26 15:42:30.236  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:42:30.246  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:30.246  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:42:30.246  1017  1030 D InputDispatcher: Focused application set to: xxxx
08-26 15:42:30.246  1017  1030 D InputDispatcher: Focus left window: 6792
,08-26 15:42:30.246  5623  5623 E MTPRx   : started activity for popup
,08-26 15:42:30.246  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:42:30.246  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:42:30.276  5623  5623 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 15:42:30.276  5623  5623 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-26 15:42:30.276  5623  5623 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:42:30.276  5623  5623 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:42:30.276  5623  5623 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:42:30.276  5623  5623 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:30.316  5623  5623 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 15:42:30.326  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:42:30.326  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 15:42:30.326  1017  1029 D InputDispatcher: Focused application set to: xxxx
,08-26 15:42:30.326  1017  1029 D InputDispatcher: Focus entered window: 6792
,08-26 15:42:30.326  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 15:42:30.336  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:42:30.336  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 15:42:30.336  1017  1030 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1da8742b attribute=null, token = android.os.BinderProxy@f4d863b
,08-26 15:42:30.376  5623  5623 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 15:42:30.376  5623  5623 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 15:42:30.376  5623  5623 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 15:42:30.406  6792  6792 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 15:42:30.406  6792  6792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 15:42:30.406  6792  6792 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 15:42:30.406  6792  6792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 15:42:30.406  1017  1489 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 15:42:30.406  1017  1489 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:42:30.406  1017  1489 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 15:42:30.406  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:42:30.406  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 15:42:30.416  6792  6792 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:42:30.416  6792  6792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 15:42:30.426  6792  6792 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6e28d37 time:114340
,08-26 15:42:30.426  6792  6792 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a849de3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@35f627c8, 16908290=android.view.AbsSavedState$1@35f627c8}, android:focusedViewId=100}]}]
08-26 15:42:30.426  6792  6792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 15:42:30.426  6792  6792 V ActivityThread: updateVisibility : ActivityRecord{18c163c2 token=android.os.BinderProxy@6e28d37 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 15:42:30.426  6792  6792 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 15:42:30.426  6792  6792 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 15:42:30.436  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:42:30.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:31.936   288   288 E SMD     : DCD OFF,
,08-26 15:42:31.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:32.296  1017  1347 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:42:32.296  1017  1347 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:42:32.296  1017  1347 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:42:32.296  1017  1347 D BatteryService: stay LED for fully charged
08-26 15:42:32.296  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:42:32.306  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:42:32.306  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:42:32.306  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:42:32.306  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:42:32.306  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:42:32.306  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:42:32.316  3175  3175 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:42:32.316  3175  3276 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:42:32.336  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:32.336  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:32.336  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:32.776  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-26 15:42:32.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:33.226  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-26 15:42:33.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:34.936   288   288 E SMD     : DCD OFF,
,08-26 15:42:34.956   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:42:36.086  1017  1095 V AlarmManager: waitForAlarm result :4
08-26 15:42:36.086  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.116  1987  1987 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 15:42:36.196  4746  4746 D ConnectivityManager: CallingUid : 10011, CallingPid : 4746
08-26 15:42:36.196  1987  1987 I art     : Explicit concurrent mark sweep GC freed 52307(3MB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 10MB/17MB, paused 1.218ms total 66.499ms
,08-26 15:42:36.196  1017  1029 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:42:36.196  1017  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-26 15:42:36.196  1017  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-26 15:42:36.196  1017  1130 D ConnectivityService: apparently satisfied.  currentScore=60
,08-26 15:42:36.206  4746  6853 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 15:42:36.226  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:36.226  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.226  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:36.226  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:36.226  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.276  4746  6854 W DriveInitializer: Background init thread started
,08-26 15:42:36.316   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 15:42:36.316   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:36.316  4746  6854 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 15:42:36.356  1987  1987 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-26 15:42:36.406  1017  1337 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:36.406  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.406  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:36.406  1017  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:36.406  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.446  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:36.446  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.446  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:36.446  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:36.446  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:36.446  4746  6854 W DriveInitializer: Background init thread ended
,08-26 15:42:36.456  1017  1475 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-26 15:42:36.456  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.476  4746  6863 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-26 15:42:36.476  4746  6863 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 15:42:36.506  1987  1987 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:42:36.556  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:36.556  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:36.556  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.736  1017  1476 I art     : Explicit concurrent mark sweep GC freed 37590(2MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.427ms total 146.544ms
,08-26 15:42:36.756  1017  1140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:36.756  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.756  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:36.756  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:36.756  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.786  1017  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:36.796  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.796  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:36.796  1017  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:36.796  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.846  1017  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:36.856  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:36.856  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:36.856  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.916  1017  1140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:36.916  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:36.926  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:36.926  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.996  1017  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:36.996  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:36.996  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:36.996  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:36.996  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:42:36.996  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.996  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.996  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:37.016  6868  6868 E Zygote  : MountEmulatedStorage()
,08-26 15:42:37.016  6868  6868 E Zygote  : v2
08-26 15:42:37.016  6868  6868 I libpersona: KNOX_SDCARD checking this for 10011,
08-26 15:42:37.016  6868  6868 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:37.016  6868  6868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:37.016  6868  6868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:37.026  1017  1477 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6868 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 15:42:37.026  6868  6868 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:37.056  6868  6868 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 15:42:37.056  6868  6868 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:37.076  6868  6868 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 15:42:37.076  6868  6868 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 15:42:37.116  6868  6868 I MultiDex: VM with version 2.1.0 has multidex support
08-26 15:42:37.116  6868  6868 I MultiDex: install
08-26 15:42:37.116  6868  6868 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 15:42:37.146  6868  6868 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 15:42:37.206  6868  6868 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 15:42:37.206  6868  6868 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e2b02be: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 15:42:37.206  6868  6868 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 15:42:37.236  6868  6868 D ChimeraCfgMgr: Reading stored module config
,08-26 15:42:37.246  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 15:42:37.256  1017  4967 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:37.256  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.256  1017  4967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.256  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.286  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:37.286  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:37.286  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.286  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.306  6868  6881 I art     : Background sticky concurrent mark sweep GC freed 24588(1173KB) AllocSpace objects, 2(32KB) LOS objects, 2% free, 7MB/7MB, paused 5.247ms total 62.171ms
,08-26 15:42:37.326  1987  1987 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c54ea563-42bb-4d3b-9d82-f4eec74db1b1
,08-26 15:42:37.336  1017  4967 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 15:42:37.336  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 15:42:37.346  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:37.346  1017  4967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.346  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.356  1987  1987 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:42:37.356  1987  1987 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-26 15:42:37.356  6868  6868 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 15:42:37.356  6868  6868 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 15:42:37.356  6868  6885 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 15:42:37.376  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:37.376  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.376  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.376  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.376  6868  6881 W art     : Suspending all threads took: 9.991ms
,08-26 15:42:37.386  6868  6881 I art     : Background partial concurrent mark sweep GC freed 1136(214KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 14.334ms total 67.516ms
,08-26 15:42:37.456   283   283 D WVCdm   : Instantiating CDM.
,08-26 15:42:37.456   283   685 I WVCdm   : CdmEngine::OpenSession
,08-26 15:42:37.456   283   685 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 15:42:37.466  6392  6403 I art     : Explicit concurrent mark sweep GC freed 1415(60KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 976us total 24.055ms,
,08-26 15:42:37.486   283   685 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 15:42:37.506   283   685 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-26 15:42:37.566   283   685 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 15:42:37.566   283   704 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-26 15:42:37.566   283   704 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-26 15:42:37.566   283   704 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-26 15:42:37.576  6868  6876 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 15:42:37.576  6868  6876 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:37.576  6868  6876 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 15:42:37.576  6868  6876 I System.out: (HTTPLog)-Thread-1244-901097907: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 15:42:37.576  6868  6876 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:37.576   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:37.576   277   961 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 15:42:37.576   283   704 D WVCdm   : PrepareKeyRequest: nonce=645439255,
,08-26 15:42:37.586  1987  2154 W GCoreFlp: No location to return for getLastLocation()
,08-26 15:42:37.616  1017  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:37.616  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.616  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.616  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.616  1017  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:37.616  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.626  1017  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:37.626  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.626  6868  6876 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:42:37.626  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 15:42:37.626  6792  6845 I jxcore-log: 
08-26 15:42:37.626  6868  6876 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6868, getuid(): 10011
,08-26 15:42:37.626  1017  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:37.626  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:37.626  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 15:42:37.626  6792  6845 I jxcore-log: 
,08-26 15:42:37.626  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.626  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:37.636  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:37.636  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:37.646  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:42:37.646  6792  6845 I jxcore-log: 
,08-26 15:42:37.646  4746  6864 D UdcContextInitService: registered all accounts: true
,08-26 15:42:37.646  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:42:37.646  6792  6845 I jxcore-log: 
,08-26 15:42:37.666  1987  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 15:42:37.676  1987  2176 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 15:42:37.806  1017  1140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:37.806  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-26 15:42:37.806  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.806  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.806  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:37.876  1017  3378 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:42:37.896  6868  6876 I qtaguid : Untagging socket 30
,08-26 15:42:37.936   288   288 E SMD     : DCD OFF
,08-26 15:42:37.956  1017  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:37.976  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.976  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:37.976  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.046  1017  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:38.046  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.046  1017  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:38.046  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.086  1987  2176 I art     : Explicit concurrent mark sweep GC freed 53698(3MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.423ms total 108.755ms
,08-26 15:42:38.106  1017  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:38.106  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.106  1017  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:38.106  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.106  1987  6899 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-26 15:42:38.106  1987  6897 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:42:38.116  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:38.116  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.116  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:38.116  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.146  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:38.146  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.146  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:38.146  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.156  1017  1488 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 15:42:38.156  1987  6899 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-26 15:42:38.156  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 15:42:38.156  1987  6897 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:42:38.156  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:38.156  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:38.156  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.156  1017  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:38.156  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.156  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:38.156  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.186  1017  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:38.186  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.186  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:38.186  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.186  1987  6899 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:42:38.186  1987  6897 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:42:38.186  1987  6897 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-26 15:42:38.196  1987  6897 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 15:42:38.256  1017  1347 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:42:38.296  1017  1347 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 15:42:38.296  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 15:42:38.296  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.296  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:38.296  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:38.326  1987  6897 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 15:42:38.326  1987  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:38.326  1987  6897 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 15:42:38.326  1987  6897 I System.out: (HTTPLog)-Thread-277-124955142: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-26 15:42:38.326  1987  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:38.326   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:38.326   277   961 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 15:42:38.336  1987  6897 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:42:38.336  1987  6897 I qtaguid : Tagging socket 69 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1987, getuid(): 10011
,08-26 15:42:38.386  1987  6897 I qtaguid : Tagging socket 72 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1987, getuid(): 10011
,08-26 15:42:38.446  6792  6845 D executeNativeTests: Running unit tests
,08-26 15:42:38.526  6903  6903 I dex2oat : ----------------------------------------------------
08-26 15:42:38.526  6903  6903 I dex2oat : <SS>: S T A R T I N G . . .
08-26 15:42:38.526  6903  6903 I dex2oat : <SS>: Zip is absent. Canceled.
,08-26 15:42:38.526  6903  6903 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 15:42:38.546  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:42:38.546  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 added. We now have 2 listener(s)
,08-26 15:42:38.556  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:42:38.556  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:38.556  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:42:38.556  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:38.556  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 added. We now have 2 listener(s)
08-26 15:42:38.556  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:38.556  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:42:38.556  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:38.566  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:38.566  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:38.566  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:38.566  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:38.576  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:38.576  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 15:42:38.576  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:38.576  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 15:42:38.576  6792  6845 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 15:42:38.576  6792  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:38.576  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:38.576  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:38.576  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 15:42:38.576  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:38.576  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:42:38.576  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:38.576  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.576  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.576  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:38.576  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:42:38.576  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 removed from the list
08-26 15:42:38.576  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.576  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 removed from the list
08-26 15:42:38.576  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.576  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.576  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.576  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.586  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:38.586  6792  6845 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 15:42:38.586  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.586  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.586  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:38.586  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.586  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.586  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
,08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.586  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.586  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:38.586  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.586  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.586  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.586  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.586  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.586  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:38.596  6903  6903 I dex2oat : dex2oat took 66.766ms (threads: 4)
,08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:38.596  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.596  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.596  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.596  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.596  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.596  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.596  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.596  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.596  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.596  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.596  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.596  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.596  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.596  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.596  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.596  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.596  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.596  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.596  6792  6845 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:38.606  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:38.606  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:38.606  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:38.606  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:38.606  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:38.606  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:38.606  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:38.606  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:38.606  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:38.616  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:38.616  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 15:42:38.616  6868  6876 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:38.616  6868  6876 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:38.616  6868  6876 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:38.616  6868  6876 I Adreno-EGL: Local Branch: 
08-26 15:42:38.616  6868  6876 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:38.616  6868  6876 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:38.616  6868  6876 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 15:42:38.616  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:38.626  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:38.626  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:42:38.636  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 15:42:38.636  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 15:42:38.636  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:42:38.636  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:38.636  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 15:42:38.656  3175  3349 D BtGatt.GattService: registerClient() - UUID=d81e458c-6ad3-4c47-bdc0-2c28be987c8f
,08-26 15:42:38.676  1017  3347 D SSRM:n  : SIOP:: AP = 370
,08-26 15:42:38.696  3175  3270 D BtGatt.GattService: onClientRegistered() - UUID=d81e458c-6ad3-4c47-bdc0-2c28be987c8f, clientIf=6
,08-26 15:42:38.706  6792  6803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:38.706  3175  3348 D BtGatt.GattService: start scan with filters
,08-26 15:42:38.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:42:38.706  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:38.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:38.706  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:38.706  3175  3275 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:38.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:38.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:42:38.706  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:38.706  3175  3275 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:38.716  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:38.716  1017  1029 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:42:38.716  6792  6845 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:38.726  3175  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:38.726  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.726  3175  3275 D BtGatt.ScanManager: allow scan with filters
08-26 15:42:38.726  3175  3275 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:42:38.726  3175  3275 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 15:42:38.726  3175  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:42:38.726  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.726  3175  3275 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:38.726  3175  3275 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:38.726  3175  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:42:38.726  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.726  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.726  6792  6845 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:38.726  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.726  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:38.726  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.726  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:38.726  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:38.726  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:38.726  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:38.726  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:38.726  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:38.726  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:38.736  3175  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-26 15:42:38.736  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.736  3175  3184 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:38.746  3175  3275 D BtGatt.ScanManager: filter size is 1
08-26 15:42:38.746  3175  3349 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 15:42:38.746  3175  3275 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:38.746  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:38.746  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:42:38.746  3175  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:38.746  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:38.746  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.746  3175  3275 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:38.746  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:38.746  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:38.746  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:38.746  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.746  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:38.746  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.746  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.746  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.746  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.746  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.746  1987  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:38.746  1987  6897 I qtaguid : Tagging socket 69 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1987, getuid(): 10011
,08-26 15:42:38.746  6792  6845 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 15:42:38.746  3175  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:42:38.746  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.756  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:38.756  3175  3275 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:38.756  3175  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:42:38.756  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:38.756  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:38.766  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:38.766  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:38.766  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:38.766  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:38.766  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:38.766  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:38.766  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:42:38.766  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:38.766  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:38.766  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:38.776  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:38.776  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:38.776  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:42:38.776  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:38.776  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:42:38.776  3175  3349 D BtGatt.GattService: registerClient() - UUID=81903acc-7809-4a60-be63-8d35bfacd6ff
,08-26 15:42:38.806  6868  6876 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:38.806  6868  6876 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:38.806  6868  6876 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:38.806  6868  6876 I Adreno-EGL: Local Branch: 
08-26 15:42:38.806  6868  6876 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:38.806  6868  6876 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:38.806  6868  6876 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:38.826  3175  3270 D BtGatt.GattService: onClientRegistered() - UUID=81903acc-7809-4a60-be63-8d35bfacd6ff, clientIf=6
,08-26 15:42:38.826  6792  6800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:38.826  3175  3348 D BtGatt.GattService: start scan with filters
,08-26 15:42:38.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:42:38.826  3175  3275 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:38.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:38.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 15:42:38.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:38.826  3175  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:38.826  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.826  3175  3275 D BtGatt.ScanManager: allow scan with filters
,08-26 15:42:38.826  3175  3275 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:42:38.826  3175  3275 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 15:42:38.836  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:38.836  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:38.836  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:42:38.836  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:38.836  6792  6845 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:38.836  3175  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:42:38.836  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.836  3175  3275 D BtGatt.ScanManager: Starting BLE batch scan,
08-26 15:42:38.836  3175  3275 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
08-26 15:42:38.846  3175  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 15:42:38.846  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.846  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:38.846  6792  6845 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:38.846  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:42:38.846  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:38.846  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:38.846  3175  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:42:38.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:38.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:38.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-26 15:42:38.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:38.846  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:38.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:38.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:38.846  3175  3184 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:38.846  6868  6876 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:38.846  6868  6876 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:38.846  6868  6876 I Adreno-EGL: Build Date: 04/06/15 Mon,
08-26 15:42:38.846  6868  6876 I Adreno-EGL: Local Branch: 
08-26 15:42:38.846  6868  6876 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:38.846  6868  6876 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:38.846  6868  6876 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 15:42:38.846  3175  3275 D BtGatt.ScanManager: filter size is 1
08-26 15:42:38.846  3175  3275 D BtGatt.ScanManager: delete FilterIndex - 4
08-26 15:42:38.856  3175  3349 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:42:38.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:38.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:38.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:38.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:38.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:42:38.856  3175  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,08-26 15:42:38.856  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.856  3175  3275 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:42:38.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:38.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:38.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:38.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:38.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:38.856  3175  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:42:38.856  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.856  3175  3275 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:38.856  3175  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:42:38.856  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.866  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-26 15:42:38.866  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 15:42:38.866  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.866  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:38.866  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:38.866  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.866  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:38.866  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:38.866  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.866  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.866  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.866  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.866  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.866  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.866  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.866  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.866  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:38.866  6792  6845 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 15:42:38.866  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:38.876  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:38.876  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:38.876  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:38.876  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:38.876  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:38.876  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:38.876  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 15:42:38.876  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:38.876  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:38.876  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:42:38.886  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:38.886  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:38.886  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:38.886  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:42:38.886  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:38.886  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:42:38.906  3175  3348 D BtGatt.GattService: registerClient() - UUID=1abc0036-eb31-40ec-bc15-717c5c6e9745
,08-26 15:42:38.916  1017  4967 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:42:38.936  1987  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:38.936  1987  6897 I qtaguid : Tagging socket 69 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1987, getuid(): 10011
,08-26 15:42:38.946  3175  3270 D BtGatt.GattService: onClientRegistered() - UUID=1abc0036-eb31-40ec-bc15-717c5c6e9745, clientIf=6
,08-26 15:42:38.946  6792  6803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:38.946  3175  3185 D BtGatt.GattService: start scan with filters
,08-26 15:42:38.946  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:42:38.946  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:38.946  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:38.946  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:38.946  3175  3275 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:38.946  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:38.946  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:42:38.946  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:38.956  3175  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 15:42:38.956  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.956  3175  3275 D BtGatt.ScanManager: allow scan with filters
08-26 15:42:38.956  3175  3275 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:42:38.956  3175  3275 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 15:42:38.956  3175  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:42:38.956  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:38.956  3175  3275 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 15:42:38.956  3175  3275 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:38.956  3175  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:42:38.956  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.956  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:38.956  3175  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:42:38.956  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.966  6792  6845 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:38.966  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.966  6792  6845 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:38.966  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.966  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:38.966  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:38.966  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:38.966  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:38.966  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:38.966  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:38.966  3175  3348 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:38.966  3175  3275 D BtGatt.ScanManager: filter size is 1
,08-26 15:42:38.966  3175  3275 D BtGatt.ScanManager: delete FilterIndex - 5
08-26 15:42:38.966  3175  3185 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:38.966  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:38.966  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:42:38.966  3175  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:42:38.966  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.966  3175  3275 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:38.966  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:38.966  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:38.976  3175  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:42:38.976  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.976  3175  3275 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:38.976  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:38.976  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:38.976  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:38.976  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.976  6792  6845 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:38.976  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.976  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.976  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.976  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.976  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:38.976  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.976  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.976  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.976  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.976  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.976  3175  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:42:38.976  3175  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:38.976  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.976  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.976  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.976  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.976  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.976  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:38.976  6792  6845 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 15:42:38.976  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.976  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.976  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.976  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.976  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:38.976  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.976  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.976  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.976  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.976  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.976  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.976  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.976  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.976  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:38.986  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-26 15:42:38.986  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.986  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.986  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.986  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:38.986  1987  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:38.986  6792  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 15:42:38.986  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.986  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.986  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.986  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.986   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:38.986   277   961 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 15:42:38.986  1987  6866 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.986  1987  6866 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1987, getuid(): 10011
,08-26 15:42:38.986  6792  6845 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 15:42:38.986  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:38.986  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.986  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.986  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.986  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.986  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.986  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.986  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:38.996  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:38.996  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:38.996  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:38.996  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:38.996  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:38.996  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:38.996  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.996  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.996  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
,08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:38.996  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:38.996  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.996  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:38.996  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:38.996  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:38.996  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:38.996  6792  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:38.996  6792  6845 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 15:42:38.996  6792  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:38.996  6792  6845 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:38.996  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:38.996  6792  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-26 15:42:38.996  6792  6845 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:38.996  6792  6845 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 15:42:38.996  6792  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:38.996  6792  6845 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 15:42:38.996  6792  6845 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
08-26 15:42:38.996  6792  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:38.996  6792  6845 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:38.996  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
,08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:39.006  6792  6915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1329)
,08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:39.006  6792  6845 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.006  6792  6916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1329
,08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 15:42:39.006  6792  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:39.006  6792  6845 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 15:42:39.006  6792  6845 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 15:42:39.006  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.006  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.006  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.006  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.006  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.006  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.006  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.016  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:39.016  6792  6915 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.016  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.016  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.016  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.016  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.016  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.016  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.016  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.016  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.016  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.016  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.016  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.016  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.016  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.016  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-26 15:42:39.026  6792  6915 D BluetoothSocket: connect(): myUserId = 0
08-26 15:42:39.026  6792  6915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 15:42:39.026  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:39.026  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.026  1987  6866 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1987, getuid(): 10011
,08-26 15:42:39.026  6792  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 15:42:39.026  6792  6792 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:39.026  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.026  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.026  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.026  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.026  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.026  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.026  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:39.026  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.026  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.026  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.026  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.026  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.026  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:39.026  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:39.026  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:39.026  3175  3348 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:39.026  6792  6845 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-26 15:42:39.026  6792  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:39.026  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:39.026  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:39.036  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.036  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.036  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.036  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.036  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.036  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.036  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.036  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.036  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.036  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.036  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.036  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.036  1017  1337 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-26 15:42:39.036  6792  6915 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.036  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.036  6792  6917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 15:42:39.036  6792  6917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 15:42:39.036  6792  6792 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-26 15:42:39.036  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.036  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.036  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.036  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.036  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.036  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.036  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.036  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.036  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.036  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.036  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.036  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.036  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.036  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
,08-26 15:42:39.046  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:39.046  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:39.046  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:39.046  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:39.046  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.046  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.046  6792  6845 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27ad3d1 not in the list
08-26 15:42:39.046  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.046  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:39.046  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.046  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:39.046  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:39.046  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:39.046  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:39.046  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:39.046  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:39.046  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f7c0e36 not in the list
08-26 15:42:39.046  1987  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:39.046  1987  6897 I qtaguid : Tagging socket 69 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1987, getuid(): 10011
,08-26 15:42:39.046  6792  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:39.046  6792  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 15:42:39.046  6792  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-26 15:42:39.046  6792  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 15:42:39.046  6792  6845 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 15:42:39.046  6792  6845 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 15:42:39.046  6792  6845 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing,
,08-26 15:42:39.046  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:39.046  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e412a28 added. We now have 2 listener(s)
08-26 15:42:39.046  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:39.046  6792  6845 D BluetoothAdapter: enable()
,08-26 15:42:39.056  6792  6845 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 15:42:39.056  1017  4967 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-26 15:42:39.056  1017  4967 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:39.056  1017  4967 D SecContentProvider2: mCursor = null
08-26 15:42:39.056  1017  4967 D WifiService: setWifiEnabled: true pid=6792, uid=10171
,08-26 15:42:39.056  1017  4967 W ActivityManager: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-26 15:42:39.066  1017  4967 W WifiService: Failed getting userId using ActivityManagerNative,
08-26 15:42:39.066  1017  4967 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:39.066  1017  4967 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:42:39.066  1017  4967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:42:39.066  1017  4967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:42:39.066  1017  4967 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:42:39.066  1017  4967 W WifiService: 	,at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:39.066  1017  4967 D SettingsProvider: name = wifi_on
08-26 15:42:39.066  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:39.066  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f875341 added. We now have 3 listener(s)
08-26 15:42:39.066  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:39.066  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:42:39.076  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d4270e6 added. We now have 4 listener(s)
08-26 15:42:39.076  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-26 15:42:39.076  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:42:39.076  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b945627 added. We now have 5 listener(s)
08-26 15:42:39.076  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:39.076  1017  1475 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:42:39.076  1017  1475 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:39.076  1017  1475 D SecContentProvider2: mCursor = null
,08-26 15:42:39.076  1017  1475 D WifiService: setWifiEnabled: false pid=6792, uid=10171
,08-26 15:42:39.076  1017  1475 D SettingsProvider: name = wifi_on
,08-26 15:42:39.086  1017  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 15:42:39.086  6792  6845 D BluetoothAdapter: disable()
08-26 15:42:39.086  1017  2754 D SettingsProvider: name = bluetooth_on
08-26 15:42:39.086  1382  1382 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:42:39.086  1382  1382 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 15:42:39.096  1382  1382 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 15:42:39.096  1382  1382 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 15:42:39.096  3175  3266 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 15:42:39.096  3175  3266 D BluetoothAdapterProperties: Setting state to 13
08-26 15:42:39.096  3175  3266 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 15:42:39.096  1017  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:39.096  3175  3266 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:39.096  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 15:42:39.096  3175  3266 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 15:42:39.096  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.096  1017  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.096  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.106  3175  3175 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 15:42:39.106  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:39.106  3175  3175 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fa8b304, channel: 19, state: LISTENING
,08-26 15:42:39.106  3175  3175 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3fa8b304, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b62826c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a77a0edmSocket: android.net.LocalSocket@3c45eb22 impl:android.net.LocalSocketImpl@35b5a9b3 fd:FileDescriptor[74]
08-26 15:42:39.106  3175  3175 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c45eb22 impl:android.net.LocalSocketImpl@35b5a9b3 fd:FileDescriptor[74]
,08-26 15:42:39.106  3175  3266 D BluetoothAdapterService: Autoconnection is available 
08-26 15:42:39.106  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 15:42:39.106  3175  3266 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 15:42:39.106  3175  3266 D BluetoothAdapterService: terminating service from this receiver
08-26 15:42:39.106  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:39.106  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.106  1017  2754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.106  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.106  3175  3266 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 15:42:39.106  3175  3266 D BluetoothAdapterProperties: mDiscovering is false
,08-26 15:42:39.106  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:39.106  1017  1477 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 15:42:39.106  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
08-26 15:42:39.106  3175  3266 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 15:42:39.116  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:42:39.116  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:42:39.116  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:39.116  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:39.116  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:39.116  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:39.116  1178  1178 D BluetoothTile:  getBluetoothState : 13
08-26 15:42:39.116  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:39.116  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:39.116  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:39.126  1918  1918 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:39.126  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:39.126  1017  1128 E WifiNative-wlan0: do suspend true
,08-26 15:42:39.126  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:39.126  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:42:39.126  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:39.126  1017  1337 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:42:39.126  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:39.126  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:39.136  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:42:39.136  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:39.136  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:39.136  1017  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:39.136  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 15:42:39.136  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:39.136  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:39.146  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:39.146  1017  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:39.146  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:39.146  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:39.146  3175  3270 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:42:39.146  3175  3270 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:42:39.146  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:39.156  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:39.156  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:39.156  3175  3266 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 15:42:39.156  3175  3266 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 15:42:39.156  1017  1337 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 15:42:39.156  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:39.156  3175  3266 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 15:42:39.156  3175  3266 E bt-btif : cmd socket is not created
,08-26 15:42:39.156  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.156  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:39.156  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-26 15:42:39.156  6792  6915 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@234e27d, channel: -1, state: INIT
,08-26 15:42:39.156  3175  3292 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 15:42:39.156  3175  3292 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 15:42:39.156  3175  3266 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 15:42:39.156  6792  6915 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@234e27d, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3734b572, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18e62dc3mSocket: android.net.LocalSocket@23c51640 impl:android.net.LocalSocketImpl@3d322979 fd:FileDescriptor[107],
08-26 15:42:39.156  6792  6915 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23c51640 impl:android.net.LocalSocketImpl@3d322979 fd:FileDescriptor[107],
,08-26 15:42:39.156  6792  6915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1329)
08-26 15:42:39.166  3066  3066 D BluetoothPbap: Proxy object disconnected
08-26 15:42:39.166  3066  3066 D PbapServerProfile: Bluetooth service disconnected
08-26 15:42:39.166  3175  5122 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:42:39.166  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:39.166  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:39.166  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:39.166  3175  3292 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 15:42:39.166  3175  3175 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b7ffb70, channel: 5, state: LISTENING
,08-26 15:42:39.176  3175  3175 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b7ffb70, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2836a035, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cba5ee9mSocket: android.net.LocalSocket@257b976e impl:android.net.LocalSocketImpl@2ad72e0f fd:FileDescriptor[76]
08-26 15:42:39.176  3175  3175 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@257b976e impl:android.net.LocalSocketImpl@2ad72e0f fd:FileDescriptor[76]
08-26 15:42:39.176  3175  3175 I BtOppRfcommListener: stopping Accept Thread
,08-26 15:42:39.176  3175  3175 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c415e9c, channel: 12, state: LISTENING
08-26 15:42:39.176  3175  3175 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c415e9c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c3ef317, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b5100a5mSocket: android.net.LocalSocket@344dbc7a impl:android.net.LocalSocketImpl@34e29c2b fd:FileDescriptor[79]
08-26 15:42:39.176  3175  3175 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@344dbc7a impl:android.net.LocalSocketImpl@34e29c2b fd:FileDescriptor[79]
,08-26 15:42:39.176  3175  5122 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 15:42:39.176  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:39.176  3175  3175 V BluetoothOppManager: cleanUp...
,08-26 15:42:39.176  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:39.176  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
08-26 15:42:39.186  1017  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 15:42:39.186  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:39.186  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:39.186  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:39.186  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:39.196  6923  6923 E Zygote  : MountEmulatedStorage()
08-26 15:42:39.196  6923  6923 I libpersona: KNOX_SDCARD checking this for 10055
08-26 15:42:39.196  6923  6923 E Zygote  : v2
08-26 15:42:39.196  6923  6923 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:39.196  6923  6923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:39.196  1017  1489 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6923 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-26 15:42:39.196  6923  6923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:39.196  6923  6923 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:39.236  6923  6923 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:39.236  6923  6923 D ActivityThread: Added TimaKeyStore provider,
,08-26 15:42:39.266  6923  6923 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 15:42:39.276   283   283 I WVCdm   : CdmEngine::CloseSession
,08-26 15:42:39.276   283   283 I WVCdm   : L3 Terminate.
,08-26 15:42:39.296  6923  6923 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 15:42:39.296  6923  6923 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 15:42:39.296  6923  6923 D UserAnalysis: Create SecureDbHelper
,08-26 15:42:39.306  6923  6923 D IntelligenceServiceApplication: onCreate()
,08-26 15:42:39.306  1017  4967 I ActivityManager: Killing 6459:com.samsung.helphub/1000 (adj 15): empty #21
,08-26 15:42:39.316  1017  1475 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 15:42:39.316  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:39.316  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:39.316  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:39.316  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:39.316  6923  6923 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 15:42:39.336  6942  6942 E Zygote  : MountEmulatedStorage()
,08-26 15:42:39.336  6942  6942 I libpersona: KNOX_SDCARD checking this for 10105
08-26 15:42:39.336  6942  6942 E Zygote  : v2
08-26 15:42:39.336  6942  6942 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:39.336  6942  6942 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:39.336  6942  6942 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:39.336  6942  6942 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 15:42:39.346  1017  1475 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6942 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-26 15:42:39.346  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 15:42:39.346  6923  6923 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 15:42:39.356  6923  6923 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 15:42:39.356  6942  6942 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:39.356  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:39.356  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:39.356  3175  3292 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 15:42:39.366  6942  6942 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:39.366  3175  3341 I bt_userial_mct: exiting userial_read_thread
08-26 15:42:39.366  3175  3341 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 15:42:39.366  3175  3270 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-26 15:42:39.366  3175  3294 I bt_vendor: hw_epilog_process
08-26 15:42:39.366  3175  3270 D bt_userial_mct: userial_close
08-26 15:42:39.366  3175  3270 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 15:42:39.366  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:39.366  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:39.366  3175  3292 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:39.366  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:39.366  3175  3292 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 15:42:39.366  3175  3292 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:39.366  3175  3292 W bt-btif : ag scb idx 1 not allocated
08-26 15:42:39.366  3175  3292 W bt-btif : ag scb idx 2 not allocated
08-26 15:42:39.366  3175  3292 E bt-btif : BTA AG is already disabled, ignoring ...
,08-26 15:42:39.486   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 15:42:39.496   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 15:42:39.496  6942  6961 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 15:42:39.506   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 15:42:39.506   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:39.516  6942  6961 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 15:42:39.526  6792  6792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:42:39.666  3175  3270 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 15:42:39.666  3175  3270 I bt_vendor: bluetooth satus is on
08-26 15:42:39.666  3175  3270 I bt_vendor: bt-vendor : resetting BT status
08-26 15:42:39.666  3175  3270 I bt_vendor: Starting hciattach daemon
08-26 15:42:39.666  3175  3270 I bt_vendor: try to set false
,08-26 15:42:39.666  3175  3270 I bt_vendor: Starting hciattach daemon
08-26 15:42:39.666  3175  3270 I bt_vendor: try to set false
,08-26 15:42:39.666  3175  3270 I bt_vendor: cleanup
,08-26 15:42:39.666  3175  3292 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-26 15:42:39.666  3175  3270 I GKI_LINUX: GKI_exit_task 0 done
08-26 15:42:39.666  3175  3270 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 15:42:39.666  3175  3266 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-26 15:42:39.666  3175  3266 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:42:39.666  3175  3266 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 15:42:39.666  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 15:42:39.666  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 15:42:39.666  3175  3266 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 15:42:39.666  1017  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 15:42:39.666  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 15:42:39.666  1017  1347 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:39.666  1017  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.666  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:39.676  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:42:39.676  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 15:42:39.676  3175  3175 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 15:42:39.676  3175  3175 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 15:42:39.676  3175  3266 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 15:42:39.676  3175  3175 D BtGatt.GattService: stop()
08-26 15:42:39.676  1017  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:39.676  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 15:42:39.676  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.676  1017  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.676  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:39.676  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:39.676  3175  3175 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 15:42:39.676  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:39.676  3175  3266 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:39.676  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:39.676  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:39.676  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:39.676  6942  6942 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.676  6942  6942 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.676  6942  6942 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.676  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.686  6942  6942 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.686  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.686  6942  6942 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.686  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.686  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.686  6942  6942 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.686  6942  6942 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.686  6942  6942 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:39.686  6942  6942 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:39.686  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 15:42:39.686  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:39.686  3175  3175 D HeadsetService: Received stop request...Stopping profile...
08-26 15:42:39.686  3175  3266 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 15:42:39.696  1017  1495 I ActivityManager: Killing 6492:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-26 15:42:39.696  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:39.696  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 15:42:39.696  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.696  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.696  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.696  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 15:42:39.696  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:42:39.696  3175  3266 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 15:42:39.696  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 15:42:39.696  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:39.696  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 15:42:39.696  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.696  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.696  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.696  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:39.706  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 15:42:39.706  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:42:39.706  3066  3066 D HeadsetProfile: Bluetooth service disconnected
08-26 15:42:39.706  3175  3266 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-26 15:42:39.706  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 15:42:39.706  1017  2754 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:39.706  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 15:42:39.706  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.706  1017  2754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.706  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.706  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 15:42:39.706  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.706  1017  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:39.706  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.706  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 15:42:39.706  3175  3266 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.716  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.716  1017  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.716  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:42:39.716  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 15:42:39.716  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:39.716  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 15:42:39.716  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.716  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.716  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:39.716  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:39.716  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:42:39.716  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:42:39.716  3175  3266 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:42:39.716  3175  3266 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:42:39.716  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 15:42:39.716  3175  3266 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 15:42:39.716  3175  3175 D A2dpService: Received stop request...Stopping profile...
08-26 15:42:39.726  3175  3282 D A2dpStateMachine: Exit Disconnected: -1
08-26 15:42:39.736  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:39.736  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:39.736  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 15:42:39.736  3066  3066 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:39.736  3066  3066 D A2dpProfile: Bluetooth service disconnected
08-26 15:42:39.736  3175  3175 D HidService: Received stop request...Stopping profile...
08-26 15:42:39.736  3175  3175 D HidService: Stopping Bluetooth HidService
08-26 15:42:39.736  3175  3175 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:42:39.736  3175  3175 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 15:42:39.736  3175  3175 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:42:39.736  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:39.736  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 15:42:39.736  3175  3175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:39.736  3175  3175 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 15:42:39.736  3175  3175 D HealthService: Received stop request...Stopping profile...
08-26 15:42:39.746  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:39.746  3066  3066 D BluetoothInputDevice: Proxy object disconnected
08-26 15:42:39.746  3066  3066 D HidProfile: Bluetooth service disconnected
08-26 15:42:39.746  3175  3175 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 15:42:39.746  3175  3175 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:42:39.746  3175  3175 D PanService: Received stop request...Stopping profile...
08-26 15:42:39.746  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:39.746  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:39.746  3175  3175 D BluetoothMapService: Received stop request...Stopping profile...
08-26 15:42:39.746  3066  3066 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:39.746  3066  3066 D PanProfile: Bluetooth service disconnected
08-26 15:42:39.756  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:39.756  3175  3175 D SapService: Received stop request...Stopping profile...
08-26 15:42:39.756  3175  3175 D SapService: Stopping Bluetooth SapService
08-26 15:42:39.756  3175  3175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:39.756  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-26 15:42:39.756  3175  3175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:39.756  3175  3175 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 15:42:39.756  3175  3175 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:39.756  3175  3175 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 15:42:39.756  6942  6968 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-26 15:42:39.756  3175  3283 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 15:42:39.766  3175  3175 I GKI_LINUX: GKI_exit_task 2 done,
08-26 15:42:39.766  3175  3175 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 15:42:39.766  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 15:42:39.766  3175  3175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:39.766  3175  3175 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.766  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 15:42:39.766  3175  3175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.766  3175  3175 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.766  3175  3175 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:42:39.766  3175  3175 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 15:42:39.766  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 15:42:39.766  3175  3175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.766  3175  3175 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:39.766  3175  3175 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:42:39.766  3175  3175 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 15:42:39.766  3066  3066 D BluetoothMap: Proxy object disconnected
,08-26 15:42:39.766  3066  3066 D MapProfile: Bluetooth service disconnected
08-26 15:42:39.766  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 15:42:39.766  3066  3066 D SapProfile: Bluetooth service disconnected
08-26 15:42:39.766  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 15:42:39.766  3175  3175 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 15:42:39.766  3175  3175 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 15:42:39.766  3175  3175 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 15:42:39.766  3175  3175 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 15:42:39.766  3175  3175 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 15:42:39.766  3175  3266 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 15:42:39.766  3175  3266 D BluetoothAdapterProperties: Setting state to 10
08-26 15:42:39.766  3175  3266 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 15:42:39.766  3175  3266 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:39.766  3175  3266 D BluetoothAdapterService: updateAdapterState state is 10
08-26 15:42:39.766  3175  3266 D BluetoothAdapterService: Autoconnection is available 
08-26 15:42:39.766  3175  3266 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 15:42:39.766  3175  3266 I BluetoothAdapterState: Entering OffState
08-26 15:42:39.766  3175  3185 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:39.766  3066  3074 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:39.776  6792  6800 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:39.776  6792  6800 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:39.776  6792  6800 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 15:42:39.776  6792  6800 D BluetoothLeAdvertiser: Exit stop advertising
,08-26 15:42:39.776  6792  6800 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 15:42:39.776  6792  6800 D BluetoothLeScanner: Exiting stopAllScan
,08-26 15:42:39.776  3066  3076 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 15:42:39.776  3066  3076 D Bluetoothsap: Unbinding service...
08-26 15:42:39.776  3066  3074 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:39.776  3066  3074 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:39.776  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:39.776  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:39.776  1439  2457 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:39.776  1439  2457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:39.776  1416  1437 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:39.776  1416  1437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:39.776  3066  3076 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 15:42:39.776  3066  3074 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 15:42:39.786  3175  3349 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:39.786  3175  3349 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:39.786  1178  2021 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:39.786  1178  2021 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:39.786  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:42:39.786  1987  2161 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:39.786  1987  2161 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:39.786  3066  3076 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 15:42:39.786  1017  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:39.786  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:39.786  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:39.786  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:39.796  1426  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:39.796  1426  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:39.796  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 15:42:39.796  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:42:39.806  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:39.806  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-26 15:42:39.806  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:42:39.806  1178  1178 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:39.806  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:42:39.806  1178  1757 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:39.816  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:39.816  1178  1178 D BluetoothTile:  getBluetoothState : 10
08-26 15:42:39.816  1178  1757 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:39.816  1178  1178 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:39.816  1178  1178 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:39.816  1918  1918 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:39.816  1017  2754 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:39.816  1987  2163 D BluetoothAdapter: 817837635: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:39.816  1987  2163 D BluetoothAdapter: 817837635: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:39.816  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:39.816  1017  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:39.816  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:39.816  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:42:39.816  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:39.826  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:39.826  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:42:39.826  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:39.826  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:39.826  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:39.826  3175  3270 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 15:42:39.826  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:39.826  3175  3175 I GKI_LINUX: GKI_exit_task 1 done
08-26 15:42:39.826  3175  3175 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 15:42:39.826  1017  1495 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:42:39.826  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:39.826  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:39.826  1017  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:39.826  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:39.826  3175  3175 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 15:42:39.836  3175  3175 I art     : System.exit called, status: 0
,08-26 15:42:39.836  3175  3175 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 15:42:39.836  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:39.846  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:39.846  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:39.846  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 15:42:39.856  1382  1382 I wpa_supplicant: nl80211: Received scan results (7 BSSes)
,08-26 15:42:39.856  1017  1127 D WifiP2pService: InactiveState{ what=147461 }
08-26 15:42:39.856  1017  1127 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-26 15:42:39.856  1017  1127 D WifiP2pService: DefaultState{ what=147461 }
08-26 15:42:39.856  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
08-26 15:42:39.856  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:42:39.856   277   967 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:39.866  1987  3007 V NativeCrypto: Read error: ssl=0xb7d351d8: I/O error during system call, Connection timed out
08-26 15:42:39.866  1987  6866 V NativeCrypto: SSL handshake aborted: ssl=0xb7e94b68: I/O error during system call, Connection timed out
08-26 15:42:39.866  1987  6866 I qtaguid : Untagging socket 66
08-26 15:42:39.866  1987  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:39.866  1987  6866 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 15:42:39.866  1987  6866 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1987, getuid(): 10011
,08-26 15:42:39.866  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:42:39.866  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:39.866  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-26 15:42:39.866  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-26 15:42:39.866  1987  3007 V NativeCrypto: SSL shutdown failed: ssl=0xb7d351d8: I/O error during system call, Broken pipe
,08-26 15:42:39.866  1987  3007 E GCM     : Wifi connection closed with errorCode 20
,08-26 15:42:39.866  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:39.866  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:42:39.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:39.876  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 15:42:39.876  1017  4967 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-26 15:42:39.876  1987  6866 I qtaguid : Untagging socket 66
,08-26 15:42:39.886  1017  1127 D WifiP2pService: InactiveState{ what=131204 }
,08-26 15:42:39.886  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:39.886  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:39.886  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:39.886  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 15:42:39.886  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:39.886  1987  6897 D Uploader: Network request failed class javax.net.ssl.SSLException(Read error: ssl=0xb7e1e180: I/O error during system call, Connection timed out)
08-26 15:42:39.886  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-26 15:42:39.886  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.886  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED,
08-26 15:42:39.886  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.886  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.886  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 15:42:39.886  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-14ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:39.886  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-14ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:39.886  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 15:42:39.886  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:39.886  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-26 15:42:39.886  1017  1736 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:39.896  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-26 15:42:39.896  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:39.896  1017  1736 I qtaguid : Tagging socket 350 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,08-26 15:42:39.896  1017  1736 I qtaguid : Untagging socket 350
08-26 15:42:39.896  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:39.896  1017  1736 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:39.896  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-26 15:42:39.906  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 15:42:39.916  1017  1127 D WifiP2pService: P2pDisablingState
,08-26 15:42:39.916  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 15:42:39.916  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 15:42:39.916  1017  1127 D WifiP2pService: p2p socket connection lost
,08-26 15:42:39.916  1017  1127 D WifiP2pService: P2pDisabledState
,08-26 15:42:39.916  1987  6866 W GLSUser : [AppCertManager] IOException while requesting key: 
,08-26 15:42:39.916  1987  6866 W GLSUser : java.net.ConnectException: failed to connect to android.clients.google.com/172.217.20.142 (port 443) after 30000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at java.net.Socket.connect(Socket.java:882)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
,08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at dja.a(:com.google.android.gms:233)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at dxt.a(:com.google.android.gms:263)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
08-26 15:42:39.916  1987  6866 W GLSUser : 	,at dxl.a(:com.google.android.gms:113)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at jch.run(:com.google.android.gms:17)
08-26 15:42:39.916  1987  6866 W GLSUser : ,	at java.lang.Thread.run(Thread.java:818)
08-26 15:42:39.916  1987  6866 W GLSUser : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at libcore.io.Posix.connect(Native Method)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
08-26 15:42:39.916  1987  6866 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-26 15:42:39.916  1987  6866 W GLSUser : 	... 30 more
08-26 15:42:39.916  1017  1128 E WifiNative-wlan0: do suspend true
08-26 15:42:39.916  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 15:42:39.916  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-26 15:42:39.926  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:39.926  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:39.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:39.926  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:39.926  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 15:42:39.926  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 15:42:39.926  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:39.926  1017  1047 D WifiDisplayController: disconnect
08-26 15:42:39.926  1017  1047 D WifiDisplayController: updateConnection
08-26 15:42:39.926  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:39.926  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 15:42:39.926  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:39.926  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:39.926  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 15:42:39.926  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:39.926  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 15:42:39.926  1017  1347 I ActivityManager: Process com.android.bluetooth (pid 3175)(adj 0) has died(29,714)
,08-26 15:42:39.936  1017  2754 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:39.936  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:39.946  1987  2176 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory,
,08-26 15:42:39.946  1987  2176 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.,
,08-26 15:42:39.956  1987  2176 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 15:42:37.890+0200, stopTime=2016-08-26 15:42:39.961+0200, duration=2071ms
,08-26 15:42:39.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:39.956  1987  6988 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,08-26 15:42:39.966   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:39.966   277   961 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-26 15:42:39.966   277   967 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:39.966   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:39.966   277   961 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 15:42:39.966  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-26 15:42:39.966  1017  1130 V NetworkStats: updateIfacesLocked()
08-26 15:42:39.966  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:39.966  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:39.966  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:39.966  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:39.976  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 15:42:39.976  1017  1130 V NetworkStats: performPollLocked() took 4ms
08-26 15:42:39.976  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 15:42:39.976  1382  1382 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-26 15:42:39.976  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:39.976  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 15:42:39.976  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:42:39.976  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-26 15:42:39.976  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 15:42:39.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.976  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:39.976  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:39.986  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:39.986  1017  1128 D SecContentProvider2: mCursor = null
08-26 15:42:39.986  1017  1736 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:39.986  1178  1732 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 15:42:39.986  4746  6853 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 15:42:39.986  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 15:42:39.986  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:42:39.986  1017  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:39.986  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:39.986  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 15:42:39.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:39.986  1017  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 15:42:39.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:39.986  1439  1439 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:42:39.986  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 15:42:39.986  1439  1439 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:39.986  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:39.986  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 15:42:39.986  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:39.996  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 15:42:39.996  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:39.996  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:39.996  1178  1178 D HotspotTile: onReceive : 0, 0
08-26 15:42:39.996  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 15:42:40.006  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:40.006  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:40.006  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:40.006  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:40.006  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:40.006  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:40.006  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:40.006  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 15:42:40.006  1017  1131 D Tethering: MasterInitialState.processMessage what=3
08-26 15:42:40.006  1017  1125 V NetworkStats: updateIfacesLocked()
08-26 15:42:40.006  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.006  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:40.006  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:40.006  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:40.006  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-26 15:42:40.006  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:42:40.006  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:42:40.006  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 15:42:40.006  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 15:42:40.006  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 15:42:40.016  1017  1125 V NetworkStats: performPollLocked() took 5ms
08-26 15:42:40.016  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.016  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 15:42:40.016  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 15:42:40.016  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:42:40.016  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:40.016  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:42:40.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.016  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 15:42:40.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.016  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:40.016  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:40.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:40.026  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.026  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:40.036  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 15:42:40.046  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:40.046  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-26 15:42:40.046  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.046  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:40.046  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:40.046  1987  1987 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-26 15:42:40.066  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 15:42:40.086  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.086  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.086  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.086  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.096  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.096  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.096  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.096  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:40.096  1987  2176 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 15:42:40.096  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.096  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.106  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.116  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.116  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.116  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.116  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.116  1987  6998 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-26 15:42:40.116  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:40.116  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.126  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.126  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.126  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.126  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.126  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.126  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:40.136  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:40.136  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.136  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:40.136  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:40.136  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.136  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.136  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.136  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.136  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.146  1017  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:40.146  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:40.146  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.146  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.146  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:40.146  1654  1654 I Hs20UtilService: Starting #8
,08-26 15:42:40.146  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.146  1654  1703 I Hs20UtilService: Message received 5007
,08-26 15:42:40.146  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:42:40.156  1439  1439 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:40.156  1382  1382 I wpa_supplicant: Blacklist: Clear (all) 
08-26 15:42:40.156  1017  2754 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:40.156  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:40.156  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 15:42:40.156  1439  1439 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:40.156  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.156  1017  2754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:40.156  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:40.156  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:40.156  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:40.156  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:40.156  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:40.166  1987  6998 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 15:42:40.166  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.166  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:40.166  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-26 15:42:40.166  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 15:42:40.166  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.176  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:40.176  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.176  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.186  7010  7010 E Zygote  : MountEmulatedStorage()
08-26 15:42:40.186  7010  7010 I libpersona: KNOX_SDCARD checking this for 10102
08-26 15:42:40.186  7010  7010 E Zygote  : v2
08-26 15:42:40.186  7010  7010 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:40.186  7010  7010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:40.186  1017  1476 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7010 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 15:42:40.186  7010  7010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:40.186  7010  7010 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:40.196  1382  1382 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 15:42:40.196  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:40.196  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:40.196  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:40.206  7010  7010 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:40.206  7010  7010 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:40.216  1382  1382 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 15:42:40.216  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:40.216  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:40.216  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:40.216  1382  1382 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 15:42:40.216  1382  1382 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 15:42:40.216  1382  1382 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:40.216  1382  1382 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 15:42:40.216  1017  1131 D Tethering: InitialState.processMessage what=4
08-26 15:42:40.216  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:40.216  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:40.216  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:40.216  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:40.216  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:40.216  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:40.216  1017  1131 E Tethering: No numeric data
,08-26 15:42:40.216  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:40.216  1017  1131 D Tethering: clearTetheredNotification()
,08-26 15:42:40.226  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:40.226  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.226  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:40.226  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 15:42:40.226  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:42:40.226  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:40.226  1017  1125 V NetworkStats: performPollLocked() took 4ms
,08-26 15:42:40.226  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:40.226  7010  7010 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 15:42:40.226  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:40.226  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:40.276   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb79417c8
08-26 15:42:40.276   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-26 15:42:40.276   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 15:42:40.276   271   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1215032008)
,08-26 15:42:40.316   271   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-26 15:42:40.316   271   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 15:42:40.316   271   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1215032008) wakelock released: 1, error no: 0
08-26 15:42:40.316   271   347 I rmt_storage: 
,08-26 15:42:40.316   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb79417c8
,08-26 15:42:40.446  7010  7030 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 15:42:40.446  7010  7030 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 15:42:40.446  7010  7030 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-26 15:42:40.446  7010  7030 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 15:42:40.466  7010  7030 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-26 15:42:40.466  7010  7030 I Babel_SMS: MmsConfig.loadFromResources
,08-26 15:42:40.476  7010  7030 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 15:42:40.476  7010  7030 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-26 15:42:40.476  1382  1382 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:40.486  1017  1477 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-26 15:42:40.486  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 15:42:40.486  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:40.486  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:40.486  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:42:40.506  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:40.506  7010  7010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:40.506  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-26 15:42:40.516  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:40.516  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:40.526  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:40.526  7010  7010 I Babel_Crash: startup - clean
,08-26 15:42:40.526  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:40.526  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:40.546  1382  1382 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 15:42:40.546  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:40.546  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:40.546  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:40.556  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 15:42:40.556  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:40.556  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:40.556  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:40.556  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:40.556  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:40.556  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 15:42:40.556  1017  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 15:42:40.556  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.556  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:40.556  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:40.556  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.576  7033  7033 E Zygote  : MountEmulatedStorage()
08-26 15:42:40.576  7033  7033 E Zygote  : v2
08-26 15:42:40.576  7033  7033 I libpersona: KNOX_SDCARD checking this for 10064
08-26 15:42:40.576  7033  7033 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:40.576  7033  7033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:40.576  7033  7033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:40.576  7033  7033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:40.586  1017  1489 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7033 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:40.586  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 15:42:40.586  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 15:42:40.586  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:40.586  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:40.586  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:40.586  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:40.586  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:40.586  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:40.586  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:40.586  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 15:42:40.596  1987  2163 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:40.596  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:40.596  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:40.596  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-26 15:42:40.596  1178  1178 D HotspotTile: onReceive : 1, 0
08-26 15:42:40.596  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:40.596  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:40.606  7033  7033 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:40.606  7033  7033 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:40.626  7010  7010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:40.626  7010  7010 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 15:42:40.626  7010  7010 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 15:42:40.626  7033  7033 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 15:42:40.626  7010  7010 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 15:42:40.626  7010  7010 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 15:42:40.636  7010  7010 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 15:42:40.636  7010  7010 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 15:42:40.636  7010  7010 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 15:42:40.636  7010  7010 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 15:42:40.646  7010  7010 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 15:42:40.646  7010  7010 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 15:42:40.646  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:40.656  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 15:42:40.656  7010  7010 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 15:42:40.656  7010  7010 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 15:42:40.656  7010  7010 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 15:42:40.666  7010  7010 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 15:42:40.666  7010  7010 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 15:42:40.666  7010  7010 W VideoCapabilities: Unsupported mime video/mp43
,08-26 15:42:40.676  7010  7010 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 15:42:40.676  7010  7010 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 15:42:40.696  7033  7033 D FileShare-Client: Outbound.stopDelayTimer - ,
08-26 15:42:40.696  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 15:42:40.696  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:40.696  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.696  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:40.696  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.706  7010  7010 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 15:42:40.706  7048  7048 E Zygote  : MountEmulatedStorage()
,08-26 15:42:40.706  7048  7048 E Zygote  : v2
08-26 15:42:40.706  7048  7048 I libpersona: KNOX_SDCARD checking this for 10065
08-26 15:42:40.706  7048  7048 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:40.716  7048  7048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:40.716  7048  7048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:40.716  7048  7048 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:40.716  1017  1030 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7048 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:40.736  7010  7010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
08-26 15:42:40.736  7010  7010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 15:42:40.736   303   303 I art     : Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 23.628ms
08-26 15:42:40.736  7010  7010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:40.746  7048  7048 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:40.746  7048  7048 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:40.746  7010  7010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:40.756  1017  1337 I ActivityManager: Killing 6536:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 15:42:40.756  7010  7010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:40.756   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.581ms
08-26 15:42:40.756  7010  7010 I vclib   : onServiceConnected
,08-26 15:42:40.776   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.760ms
,08-26 15:42:40.776  7048  7048 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:40.786  1017  1347 I ActivityManager: Killing 6523:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 15:42:40.786  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:40.786  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:40.786  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.786  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.786  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:40.786  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:42:40.796  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:40.796  1654  1654 I Hs20UtilService: Starting #9
,08-26 15:42:40.796  1654  1703 I Hs20UtilService: Message received 5007
08-26 15:42:40.796  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:40.796  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:40.796  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:40.796  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:40.796  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:40.806  1017  4967 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:40.806  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:40.806  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.806  1017  4967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.816  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:40.816  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:40.816  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:40.816  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:40.816  1654  1654 I Hs20UtilService: Starting #10
,08-26 15:42:40.816  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:40.816  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:40.826  1017  1475 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:40.826  1017  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.826  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.936  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.936  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.936  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-26 15:42:40.946   288   288 E SMD     : DCD OFF
,08-26 15:42:40.946  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.946  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.946  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.946  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.946  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.956  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.956  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.956  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:40.956  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.956  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.956  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.956  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.956  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.956  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.966  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:40.966  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:40.966  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.966  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:40.966  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.966  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.966  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:40.966  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.966  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.976  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:40.976  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.976  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.976  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:40.976  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.976  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.976  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:40.976  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:40.976  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:40.986  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 15:42:40.986  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.986  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:40.986  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:40.986  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:40.996  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7063 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:42:40.996  7063  7063 E Zygote  : MountEmulatedStorage()
08-26 15:42:40.996  7063  7063 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:40.996  7063  7063 E Zygote  : v2
08-26 15:42:40.996  7063  7063 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:40.996  7063  7063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:41.006  7063  7063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.006  7063  7063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 15:42:41.026  7063  7063 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.026  7063  7063 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.056  7063  7063 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 15:42:41.056  7063  7063 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 15:42:41.056  7063  7063 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 15:42:41.076  7063  7063 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-26 15:42:41.076  7063  7063 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 15:42:41.076  7063  7063 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 15:42:41.076  7063  7063 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:41.076  1017  1477 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-26 15:42:41.076  1017  1477 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
08-26 15:42:41.076  7063  7078 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 15:42:41.076  1017  1477 I ActivityManager: Killing 6576:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 15:42:41.086  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 15:42:41.096  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.096  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.096  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.096  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.106  7080  7080 E Zygote  : MountEmulatedStorage()
08-26 15:42:41.106  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7080 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:41.106  7080  7080 E Zygote  : v2
08-26 15:42:41.106  7080  7080 I libpersona: KNOX_SDCARD checking this for 10001
08-26 15:42:41.106  7080  7080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:41.106  7080  7080 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:41.116  7080  7080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.116  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 15:42:41.116  7080  7080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:41.116  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.116  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.116  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.116  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.116  1779  1779 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:41.136  7088  7088 E Zygote  : MountEmulatedStorage()
08-26 15:42:41.136  7088  7088 E Zygote  : v2
08-26 15:42:41.136  7088  7088 I libpersona: KNOX_SDCARD checking this for 10031
08-26 15:42:41.136  7088  7088 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:41.136  7088  7088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:41.136  1017  1477 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7088 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-26 15:42:41.146  7088  7088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.146  7088  7088 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:41.146  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 15:42:41.146  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.146  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.146  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.146  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.156  7080  7080 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.156  2473  2482 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-26 15:42:41.156  7080  7080 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.166  7104  7104 E Zygote  : MountEmulatedStorage()
,08-26 15:42:41.166  7104  7104 E Zygote  : v2
08-26 15:42:41.166  7104  7104 I libpersona: KNOX_SDCARD checking this for 10121
08-26 15:42:41.166  7104  7104 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:41.166  7104  7104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 15:42:41.166  7104  7104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:41.166  1017  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7104 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 15:42:41.176  7104  7104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:41.176  1779  1779 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-26 15:42:41.176  1779  1779 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-26 15:42:41.176  1779  1779 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-26 15:42:41.176  1779  1779 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:41.196  1779  1779 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:41.196  7088  7088 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.196  7088  7088 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.196  1779  1779 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 15:42:41.206  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 15:42:41.206  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.206  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.206  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.206  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.216  7104  7104 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.216  7104  7104 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.226  7125  7125 E Zygote  : MountEmulatedStorage()
08-26 15:42:41.226  7125  7125 E Zygote  : v2
08-26 15:42:41.226  7125  7125 I libpersona: KNOX_SDCARD checking this for 10077
08-26 15:42:41.226  7125  7125 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:41.226  7125  7125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:41.226  7125  7125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 15:42:41.226  1017  1476 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7125 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:41.226  7125  7125 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-26 15:42:41.236  1017  1044 D Tethering: interfaceRemoved wlan0
08-26 15:42:41.236  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
08-26 15:42:41.246  7125  7125 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.246  7125  7125 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.256  7088  7088 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 15:42:41.266  1017  1476 I ActivityManager: Killing 6622:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 15:42:41.266  7104  7104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:41.266  7104  7104 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 15:42:41.266  7104  7104 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:41.276  1017  1140 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 15:42:41.286  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.286  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.286  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.286  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.286  2757  7140 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-26 15:42:41.296  2757  7140 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 15:42:41.296  7104  7104 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:41.296  2757  7140 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-26 15:42:41.296  2757  7140 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-26 15:42:41.296  2757  7140 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 15:42:41.306  7141  7141 E Zygote  : MountEmulatedStorage()
08-26 15:42:41.306  7141  7141 I libpersona: KNOX_SDCARD checking this for 10032
08-26 15:42:41.306  7141  7141 E Zygote  : v2
08-26 15:42:41.306  7141  7141 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:41.306  7141  7141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:41.306  1017  1140 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7141 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:41.306  7141  7141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.306  7141  7141 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-26 15:42:41.316  7104  7104 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 15:42:41.326  7104  7104 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-26 15:42:41.326  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 15:42:41.326  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.326  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.326  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.326  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.336  1017  1044 D Tethering: interfaceRemoved p2p0
08-26 15:42:41.336  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 15:42:41.346  7141  7141 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:41.346  7141  7141 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.346  7157  7157 E Zygote  : MountEmulatedStorage()
08-26 15:42:41.346  7157  7157 E Zygote  : v2
08-26 15:42:41.346  7157  7157 I libpersona: KNOX_SDCARD checking this for 10141
08-26 15:42:41.346  7157  7157 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:41.346  7157  7157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:41.346  1017  1029 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7157 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-26 15:42:41.346  7157  7157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.346  7157  7157 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:41.356  1017  1029 I ActivityManager: Killing 6641:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 15:42:41.376  1017  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 15:42:41.376  1017  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.376  1017  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.376  1017  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.376  1017  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.376  7157  7157 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.376  7157  7157 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.386  7173  7173 E Zygote  : MountEmulatedStorage()
,08-26 15:42:41.386  7173  7173 E Zygote  : v2
08-26 15:42:41.386  7173  7173 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:41.386  7173  7173 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:41.386  7173  7173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 15:42:41.396  1017  1495 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-26 15:42:41.396  1017  1495 I ActivityManager: Killing 6655:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-26 15:42:41.396  7173  7173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.396  7173  7173 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 15:42:41.416  7157  7157 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-26 15:42:41.416  7157  7157 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:41.416  7157  7157 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:41.416  7157  7157 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 15:42:41.426  7173  7173 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.426  7173  7173 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.436  7141  7188 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 15:42:41.436  7141  7188 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 15:42:41.436  7141  7141 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 15:42:41.436  1017  1347 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 15:42:41.446  1017  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.446  1017  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.446  1017  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.446  1017  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.446  7141  7188 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:42:41.446  7141  7188 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:42:41.446  7141  7188 D SPPClientService: ============PushLog. stop!
,08-26 15:42:41.456  7190  7190 E Zygote  : MountEmulatedStorage(),
08-26 15:42:41.456  7190  7190 E Zygote  : v2
08-26 15:42:41.456  7190  7190 I libpersona: KNOX_SDCARD checking this for 10036
08-26 15:42:41.456  7190  7190 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:41.456  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:41.466  1017  1347 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7190 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:41.466  1017  1347 I ActivityManager: Killing 6589:com.android.providers.calendar/u0a37 (adj 15): empty #21,
,08-26 15:42:41.466  1017  1489 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 15:42:41.466  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:41.466  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-26 15:42:41.466  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 15:42:41.466  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:41.466  1017  1489 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 15:42:41.466  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-26 15:42:41.486  7173  7173 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
08-26 15:42:41.486  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:41.496  7190  7190 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.526  7141  7198 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 15:42:41.536  7190  7190 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3ba0c60a
,08-26 15:42:41.546  7190  7190 I SA      : [SSP] onCreated
,08-26 15:42:41.556  7190  7190 I SA      : [TPM] There is no property file
,08-26 15:42:41.556  7190  7190 I SA      : [SCU] isHaveSA() - false
,08-26 15:42:41.566  7190  7190 I SA      : [TPM] getModelProperty : null
,08-26 15:42:41.566  7190  7190 I SA      : [TPM] getCSCProperty : null
,08-26 15:42:41.566  7190  7190 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-26 15:42:41.566  7190  7190 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 15:42:41.566  7190  7190 I SA      : [DM] TFT FEATURE: false
,08-26 15:42:41.566  7190  7190 I SA      : [DM] init START
,08-26 15:42:41.566  7190  7190 I SA      : [DM] This device is not a Vodafone
,08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 15:42:41.576  7190  7190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 15:42:41.576  7190  7190 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 15:42:41.586  7190  7190 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 15:42:41.596  7190  7190 I SA      : [SCU] isHaveSA() - false
08-26 15:42:41.596  7190  7190 I SA      : support phone number id : false
08-26 15:42:41.596  7190  7190 I SA      : [DM] Supports Ref Jpn : true
,08-26 15:42:41.596  7190  7190 I SA      : [DM] init END
,08-26 15:42:41.596  7190  7190 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 15:42:41.596  7190  7190 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 15:42:41.596  7190  7190 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 15:42:41.616  7173  7173 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 15:42:41.626  7173  7173 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 15:42:41.626  7173  7173 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:41.626  7173  7173 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 15:42:41.626  7173  7173 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 15:42:41.626  7173  7173 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 15:42:41.646  1017  1337 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 15:42:41.646  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.646  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.646  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.646  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.656  7212  7212 E Zygote  : MountEmulatedStorage()
,08-26 15:42:41.656  7212  7212 E Zygote  : v2
08-26 15:42:41.656  7212  7212 I libpersona: KNOX_SDCARD checking this for 10008
08-26 15:42:41.656  7212  7212 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:41.656  7212  7212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:41.656  1017  1337 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7212 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:41.666  1017  1337 I ActivityManager: Killing 6681:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-26 15:42:41.666  7212  7212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.666  7212  7212 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 15:42:41.686  7212  7212 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.686  7212  7212 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.696  7190  7190 I SA      : [SLFUCHKMGR] constructor called
,08-26 15:42:41.706  7190  7190 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 15:42:41.706  7190  7190 I SA      : [OR] == isSIMCardReady false ==
,08-26 15:42:41.736  7190  7190 I SA      : [SCU] == networkStateCheck == false
,08-26 15:42:41.736  7190  7190 I SA      : [OR] onReceive END
,08-26 15:42:41.736  1017  2754 I ActivityManager: Killing 6085:com.android.mms/u0a41 (adj 15): empty #21
,08-26 15:42:41.746  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:41.756  1017  1489 I ActivityManager: Killing 6701:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-26 15:42:41.756  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:41.766  2875  2875 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 15:42:41 GMT+02:00 2016
,08-26 15:42:41.766  1017  1495 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 15:42:41.766  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 15:42:41.766  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:41.766  1017  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:41.766  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 15:42:41.766  2875  2875 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 15:42:41.776  2875  2875 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 15:42:41.776  2875  2875 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 15:42:41.776  2875  2875 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 15:42:41.776  2875  7228 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 15:42:41.786  2875  7228 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:41.786  1017  1030 D CountryDetector: No listener is left
,08-26 15:42:41.786  2875  7228 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 15:42:41.786  2875  7228 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-26 15:42:41.786  2875  2875 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 15:42:41.806  1017  4967 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 15:42:41.806  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 15:42:41.806  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:41.806  1017  4967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:41.806  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:42:41.816  1017  2754 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 15:42:41.816  1017  2754 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.816  1017  2754 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.816  1017  2754 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.816  1017  2754 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.836  7232  7232 E Zygote  : MountEmulatedStorage()
,08-26 15:42:41.836  1017  1488 D RCPManagerService: exchangeData() failure , invalid userId
08-26 15:42:41.836  7232  7232 E Zygote  : v2
08-26 15:42:41.836  7232  7232 I libpersona: KNOX_SDCARD checking this for 10110
08-26 15:42:41.836  7232  7232 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:41.836  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:41.836  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:41.836  1017  2754 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7232 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:41.846  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:41.846  1017  1140 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 15:42:41.846  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-26 15:42:41.846  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:41.846  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:41.846  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:42:41.846  7010  7230 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 15:42:41.856   303   303 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 675us total 20.659ms
,08-26 15:42:41.856  1017  1477 I ActivityManager: Killing 6718:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 15:42:41.866  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.866  7232  7232 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:41.876   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 660us total 16.744ms
,08-26 15:42:41.886   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.339ms
,08-26 15:42:41.886  1017  4967 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:41.906  1017  1475 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:41.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:41.956  1017  1475 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 15:42:41.966  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.966  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.966  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:41.966  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:41.976  7253  7253 E Zygote  : MountEmulatedStorage()
,08-26 15:42:41.976  7253  7253 E Zygote  : v2
08-26 15:42:41.976  7253  7253 I libpersona: KNOX_SDCARD checking this for 10068
08-26 15:42:41.976  7253  7253 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:41.976  7253  7253 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 15:42:41.986  1017  1475 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7253 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-26 15:42:41.986  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:41.986  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-26 15:42:41.986  7253  7253 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:41.986  7253  7253 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 15:42:41.996  7253  7253 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:41.996  7253  7253 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:42.016  1017  1337 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:42.016  7253  7253 D BadgeProvider: onCreate
,08-26 15:42:42.016  7253  7253 D BadgeProvider: DatabaseHelper
,08-26 15:42:42.026  1017  1347 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:42.036  7253  7261 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 15:42:42.036  1017  1489 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:42.046  1017  1337 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 15:42:42.046  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:42.046  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:42.046  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:42.046  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:42.056  1017  1337 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7269 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
08-26 15:42:42.056  1017  1337 I ActivityManager: Killing 6733:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-26 15:42:42.056  1017  1337 I ActivityManager: Killing 6545:com.android.calendar/u0a131 (adj 15): empty #22
,08-26 15:42:42.066  7269  7269 E Zygote  : MountEmulatedStorage()
08-26 15:42:42.066  7269  7269 I libpersona: KNOX_SDCARD checking this for 10009
08-26 15:42:42.066  7269  7269 E Zygote  : v2
08-26 15:42:42.066  7269  7269 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:42.066  7269  7269 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:42.066  7269  7269 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:42.066  7269  7269 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 15:42:42.066  1479  1479 D Launcher.Model: reloadBadges entered.
08-26 15:42:42.066  7253  7261 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 15:42:42.066  7253  7261 D BadgeProvider: sendNotify, [notify] : null
08-26 15:42:42.066  7253  7261 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 15:42:42.066  7253  7261 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 15:42:42.066  7253  7261 D BadgeProvider: update, [UpdateCount] : 1
,08-26 15:42:42.086  7269  7269 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:42.096  7269  7269 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:42.126  1017  4967 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:42:42.126  1017  4967 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 15:42:42.126  1017  4967 D SecContentProvider2: mCursor = null
,08-26 15:42:42.126  1017  4967 D WifiService: setWifiEnabled: true pid=6792, uid=10171
,08-26 15:42:42.126  1017  4967 W ActivityManager: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:42:42.126  1017  4967 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:42:42.126  1017  4967 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:42.126  1017  4967 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:42:42.126  1017  4967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:42:42.126  1017  4967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:42:42.126  1017  4967 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:42:42.126  1017  4967 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:42.126  1017  4967 D SettingsProvider: name = wifi_on
,08-26 15:42:42.166  1017  1337 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:42.166  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 15:42:42.176  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:42.176  1017  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:42.176  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 15:42:42.186  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:42.206  4746  7288 I iu.SyncManager: SYNC; picasa accounts
,08-26 15:42:42.226  1017  1489 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:42.236  4746  4746 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 15:42:42.246  1017  1495 I art     : Explicit concurrent mark sweep GC freed 60515(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.567ms total 171.130ms
,08-26 15:42:42.286  1017  1488 I ActivityManager: Killing 6032:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-26 15:42:42.296  1987  2176 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-26 15:42:42.306  1987  2176 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-26 15:42:42.346  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-26 15:42:42.346  1017  1477 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 15:42:42.346  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 15:42:42.346  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 15:42:42.356  1017  1337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:42:42.356  1017  1337 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:42:42.356  1017  1337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:42:42.356  1017  1337 D BatteryService: stay LED for fully charged
08-26 15:42:42.356  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:42:42.366  1017  1017 I MotionRecognitionService: Plugged
08-26 15:42:42.366  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:42:42.366  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:42:42.366  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:42:42.366  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:42:42.366  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:42:42.396  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:42.396  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:42.396  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:42.416   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/,
08-26 15:42:42.416   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 15:42:42.416  7232  7293 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 15:42:42.426   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:42.426   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:42.426  7232  7293 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:42.446   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 15:42:42.446   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:42.446  7232  7300 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,08-26 15:42:42.446   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:42.446   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:42.446  7232  7300 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:42.466  7232  7232 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 15:42:42.466  7232  7232 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 15:42:42.466  7232  7232 I GAv4    :   adb logcat -s GAv4
,08-26 15:42:42.486  7232  7232 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:42.486  1017  1337 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:42.496  7232  7232 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:42.496  7232  7302 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:42.576  1017  1044 D Tethering: interfaceAdded wlan0
,08-26 15:42:42.576  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:42.576  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:42.576  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:42.586  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:42.586  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:42.586  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:42.586   277   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 15:42:42.586  1017  1131 E Tethering: No numeric data
08-26 15:42:42.586   277   967 D SoftapController: Softap fwReload - Ok
08-26 15:42:42.586  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:42.586  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:42:42.586  1017  1131 D Tethering: InitialState.processMessage what=4
,08-26 15:42:42.586  1017  1044 D Tethering: interfaceAdded p2p0,
08-26 15:42:42.586  1017  1131 E Tethering: No numeric data
08-26 15:42:42.586  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 15:42:42.586   277   967 D CommandListener: Setting iface cfg
08-26 15:42:42.586   277   967 D CommandListener: Trying to bring down wlan0
,08-26 15:42:42.586  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:42.586  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:42.586   277   967 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:42.596  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:42:42.596  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:42.596  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:42.596  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 15:42:42.596  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 15:42:42.596  1017  1131 D Tethering: clearTetheredNotification()
,08-26 15:42:42.596  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:42.596  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 15:42:42.596  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 15:42:42.596  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 15:42:42.606  1017  1125 V NetworkStats: performPollLocked() took 12ms
08-26 15:42:42.606  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:42.606  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:42.606  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:42.606  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 15:42:42.606  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:42.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:42.606  1178  1178 D HotspotTile: onReceive : 2, 0
08-26 15:42:42.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:42.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:42.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:42.606  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:42.606  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 15:42:42.616  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:42.616  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:42.616  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:42.616  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:42.616  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 15:42:42.616  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:42.616  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:42.616  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:42.616  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:42.616  1017  1125 V NetworkStats: performPollLocked() took 4ms
,08-26 15:42:42.616  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:42.616  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:42.616  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:42.656  7305  7305 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 15:42:42.656  7305  7305 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 15:42:42.656  7305  7305 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 15:42:42.696  7305  7305 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 15:42:42.696   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7305
08-26 15:42:42.696   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 15:42:42.696  7305  7305 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 15:42:42.696  7305  7305 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:42.696  7305  7305 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 15:42:42.696  7305  7305 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 15:42:42.706   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7305
08-26 15:42:42.706   386   386 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-26 15:42:42.786  1017  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:42.786  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:42.786  1017  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:42.786  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 15:42:42.816  7232  7232 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 15:42:42.836  7232  7232 I cr.library_loader: Time to load native libraries: 5 ms (timestamps 6752-6757)
08-26 15:42:42.836  7232  7232 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 15:42:42.866  7232  7232 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a77a0ed}
08-26 15:42:42.866  7232  7232 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 15:42:42.866  7232  7232 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 15:42:42.876   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-26 15:42:42.876  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-26 15:42:42.886  7232  7232 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-26 15:42:42.886  7232  7232 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:42.886  7232  7232 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-26 15:42:42.896  7232  7232 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:42.896  7232  7232 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:42.896  7232  7232 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:42.896  7232  7232 I Adreno-EGL: Local Branch: 
08-26 15:42:42.896  7232  7232 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:42.896  7232  7232 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:42.896  7232  7232 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:42.926  7305  7305 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 15:42:42.926  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 15:42:42.946  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 15:42:42.946   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7305
08-26 15:42:42.946   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 15:42:42.946  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 15:42:42.946  7305  7305 I wpa_supplicant: ssSupport state is = 1
,08-26 15:42:42.946  7305  7305 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:42.946  7305  7305 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:42.946  7305  7305 E wpa_supplicant: SIM READ ERROR
08-26 15:42:42.946  7305  7305 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:42.946  7305  7305 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:42.946  7305  7305 E wpa_supplicant: SIM READ ERROR
08-26 15:42:42.946  7305  7305 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:42.946  7305  7305 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:42:42.946  7305  7305 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:42.946  7305  7305 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:42.946  7305  7305 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 15:42:42.946  7305  7305 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:42.946  7305  7305 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 15:42:42.946  7305  7305 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-26 15:42:42.946  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:42.946  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:42.946  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:42.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:42.966  7232  7232 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 15:42:42.976  7232  7334 W cr.media: Requires BLUETOOTH permission
,08-26 15:42:42.976  7232  7232 I NSApplication: Starting up...
,08-26 15:42:42.976  1017  1140 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:42.986  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:42.986  7305  7305 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 15:42:42.986  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 15:42:42.986  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:42.986  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:42.986  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:42.986  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:43.006  7339  7339 E Zygote  : MountEmulatedStorage(),
08-26 15:42:43.006  7339  7339 E Zygote  : v2
08-26 15:42:43.006  7339  7339 I libpersona: KNOX_SDCARD checking this for 10117
08-26 15:42:43.006  7339  7339 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:43.006  1017  1477 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7339 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-26 15:42:43.006  7339  7339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:43.006  1017  1477 I ActivityManager: Killing 5834:com.android.vending/u0a26 (adj 15): empty #21
,08-26 15:42:43.016  7339  7339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:43.016  7339  7339 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:43.036  7339  7339 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:43.036  7339  7339 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:43.056  7339  7339 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:42:43.176  7305  7305 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 15:42:43.176  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-26 15:42:43.196  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 15:42:43.196   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7305
08-26 15:42:43.196   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 15:42:43.196  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 15:42:43.196  7305  7305 I wpa_supplicant: ssSupport state is = 1,
,08-26 15:42:43.196  7305  7305 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 15:42:43.196  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 15:42:43.216  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 15:42:43.216   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7305
08-26 15:42:43.216   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 15:42:43.216  7305  7305 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 15:42:43.216  7305  7305 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:43.216  7305  7305 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 15:42:43.216  7305  7305 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:43.216  7305  7305 E wpa_supplicant: SIM READ ERROR
08-26 15:42:43.216  7305  7305 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:42:43.216  7305  7305 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:43.216  7305  7305 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-26 15:42:43.216  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:43.216  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:43.216  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:43.216  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:43.216  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:43.216  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:43.276  7305  7305 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 15:42:43.276  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 15:42:43.336  7305  7305 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 15:42:43.336  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 15:42:43.336  7305  7305 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:42:43.346  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 15:42:43.356  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 15:42:43.356  7305  7305 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 15:42:43.356  7305  7305 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:43.356  7305  7305 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:43.356  7305  7305 E wpa_supplicant: SIM READ ERROR
08-26 15:42:43.356  7305  7305 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:43.406  7305  7305 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 15:42:43.446  1017  1475 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 15:42:43.446  1017  1475 I ActivityManager: Killing 6923:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21,
,08-26 15:42:43.456  7305  7305 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:42:43.456  1017  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:42:43.456  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:43.456  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:43.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:43.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:43.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:43.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:43.466  1017  1128 E WifiConfigStore: Not a HS20
,08-26 15:42:43.466  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:43.466  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 15:42:43.466  1017  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 15:42:43.466  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:43.466  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:43.466  1178  1178 D HotspotTile: onReceive : 3, 0
,08-26 15:42:43.466  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:43.466  1017  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:43.466  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:43.466  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:43.476  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:43.476  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:43.476  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:43.476  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:43.476  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:43.476  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:43.476  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:43.476  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:43.476  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:43.476  1654  1654 I Hs20UtilService: Starting #11
,08-26 15:42:43.476  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:43.476  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:43.476  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:43.476  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:43.476  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:43.486  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 15:42:43.496  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-26 15:42:43.496  7305  7305 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 15:42:43.496  7305  7305 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 15:42:43.496  7305  7305 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:42:43.496  7305  7305 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 15:42:43.496  7305  7305 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 15:42:43.496  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 15:42:43.496  7305  7305 I wpa_supplicant: First Scan Start
,08-26 15:42:43.496  7305  7305 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 15:42:43.496  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-26 15:42:43.496  7010  7010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:43.496  1017  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:43.496  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:43.496  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:42:43.496  1017  1128 I WifiNative-HAL: startHal
08-26 15:42:43.496  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9d68688c
08-26 15:42:43.496  1017  1128 I WifiNative-HAL: Could not start hal
,08-26 15:42:43.496  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:43.496  1017  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:43.496  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:43.506  1654  1654 I Hs20UtilService: Starting #12
,08-26 15:42:43.506  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:43.506  1017  1128 E WifiNative-wlan0: do suspend true
,08-26 15:42:43.506  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 15:42:43.506  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 15:42:43.506  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-26 15:42:43.506  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 15:42:43.506  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:43.506  1017  1150 I WifiNative-HAL: startHal
08-26 15:42:43.506  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9df149bc
08-26 15:42:43.506  1017  1150 I WifiNative-HAL: Could not start hal
08-26 15:42:43.506  1017  1150 E WifiScanningService: could not start HAL
08-26 15:42:43.506  1017  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:43.506  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:43.506  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:43.506  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:43.506  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:43.506   277   967 D CommandListener: Setting iface cfg
08-26 15:42:43.506   277   967 D CommandListener: Trying to bring up p2p0
,08-26 15:42:43.506  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 15:42:43.506  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:42:43.506  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:43.506  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-26 15:42:43.516  1017  1127 D WifiP2pService: P2pEnablingState
08-26 15:42:43.516  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 15:42:43.516  1017  1127 D WifiP2pService: P2p socket connection successful
08-26 15:42:43.516  1017  1127 D WifiP2pService: P2pEnabledState
,08-26 15:42:43.516  7305  7305 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-26 15:42:43.516  7305  7305 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:42:43.516  7305  7305 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 15:42:43.516  1017  1128 E WifiStateMachine: Failed to set frequency band 0
,08-26 15:42:43.516  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:43.516  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:43.526  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:43.526  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:43.526  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 15:42:43.526  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-26 15:42:43.526  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 15:42:43.526  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 15:42:43.526  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:43.526  1017  1047 D WifiDisplayController: disconnect
08-26 15:42:43.526  1017  1047 D WifiDisplayController: updateConnection
08-26 15:42:43.526  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 15:42:43.526  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:43.526  1017  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:43.536  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:43.536  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:43.536  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:43.536  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-26 15:42:43.536  1654  1654 I Hs20UtilService: Starting #13
08-26 15:42:43.536  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:43.536  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:42:43.536  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:43.536  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-26 15:42:43.536  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 15:42:43.536  1017  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:43.536  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:43.536  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 15:42:43.536  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:43.536  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-26 15:42:43.536  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:43.536  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:43.536  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:43.546  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:43.546  1017  1127 D WifiP2pService: DeviceAddress: 0a:76:28
,08-26 15:42:43.546  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:43.546  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:43.546  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:43.546  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  secondary type: null
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  wps: 0
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  grpcapab: 0
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  devcapab: 0
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  status: 3
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  wfdInfo: null
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-26 15:42:43.546  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-26 15:42:43.556  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:43.566  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 15:42:43.566  1017  1127 D WifiP2pService: InactiveState
,08-26 15:42:43.566  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-26 15:42:43.566  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:42:43.566  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:43.566  7305  7305 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 15:42:43.566  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-26 15:42:43.566  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-26 15:42:43.566  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:42:43.566  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:43.566  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:43.566  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:43.566  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:43.576  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 15:42:43.576  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:43.576  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:43.576  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:43.576  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:43.576  7033  7033 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:43.576  7048  7048 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:43.946   288   288 E SMD     : DCD OFF
,08-26 15:42:43.956  1017  1347 I ActivityManager: Killing 6942:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-26 15:42:43.956   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:44.656  7305  7305 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
08-26 15:42:44.656  7305  7305 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 15:42:44.656  7305  7305 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 15:42:44.656  7305  7305 I wpa_supplicant: Trying to associate with  'G700'
08-26 15:42:44.656  7305  7305 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 15:42:44.656  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 15:42:44.656  1017  7361 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 15:42:44.676  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-26 15:42:44.676  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:44.766  7305  7305 E wpa_supplicant: Cmd 35605 not handled
,08-26 15:42:44.766  7305  7305 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 15:42:44.766  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 15:42:44.766  7305  7305 I wpa_supplicant: Associated with F4.99.3E
,08-26 15:42:44.766  7305  7305 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 15:42:44.766  7305  7305 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 15:42:44.766  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:44.766  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:44.766  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:44.766  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:44.776  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 15:42:44.776  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 15:42:44.776  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
08-26 15:42:44.776  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:42:44.776  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 15:42:44.776  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-26 15:42:44.776  1017  1131 E Tethering: No numeric data
08-26 15:42:44.776  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-26 15:42:44.776  1017  1131 D Tethering: clearTetheredNotification()
,08-26 15:42:44.776  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:42:44.786  1017  1128 D SecContentProvider2: mCursor = null
08-26 15:42:44.786  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:44.786  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:44.786  7305  7305 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 15:42:44.786  7305  7305 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 15:42:44.786  7305  7305 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 15:42:44.786  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:44.786  7305  7305 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:42:44.786  7305  7305 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 15:42:44.786  7305  7305 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 15:42:44.786  7305  7305 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 15:42:44.786  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:44.786  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 15:42:44.786  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:44.786  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:42:44.786  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 15:42:44.786  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:44.786  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-26 15:42:44.786  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 15:42:44.796  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:44.796  1017  1125 V NetworkStats: performPollLocked() took 12ms
08-26 15:42:44.796  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:44.796  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:44.796  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:44.796  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:44.806  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 15:42:44.806  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 15:42:44.816  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:44.816  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:44.816  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:44.816  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:44.816  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:44.816  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:44.816  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 15:42:44.816  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-26 15:42:44.816  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:42:44.816  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 15:42:44.816  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:44.826  1017  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:44.826  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:44.826  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:44.826  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:44.826  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:44.826  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,08-26 15:42:44.826  1654  1654 I Hs20UtilService: Starting #14
,08-26 15:42:44.826  1654  1703 I Hs20UtilService: Message received 5007
,08-26 15:42:44.826  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:44.826  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:44.836  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:44.836  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:44.836  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 15:42:44.836  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:44.836  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:44.846   277   967 D CommandListener: Setting iface cfg
,08-26 15:42:44.856  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 15:42:44.856  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:42:44.856  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:44.866  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:42:44.866  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-26 15:42:44.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:44.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:44.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:44.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:44.866  1017  1128 E WifiNative-wlan0: do suspend false
,08-26 15:42:44.876  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-26 15:42:44.876  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:42:44.876  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-26 15:42:44.876  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:44.956   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 15:42:45.086  7369  7369 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 15:42:45.096  7369  7369 I dhcpcd  : version 5.5.6 starting,
,08-26 15:42:45.096  7369  7369 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 15:42:45.156  7369  7369 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-26 15:42:45.156  7369  7369 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 15:42:45.156  7369  7369 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-26 15:42:45.156  7369  7369 I dhcpcd  : bssid match,
,08-26 15:42:45.156  7369  7369 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-26 15:42:45.176  1017  1495 I ActivityManager: Killing 7063:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 15:42:45.176  1017  1489 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 15:42:45.176  1017  1489 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:45.176  1017  1489 D SecContentProvider2: mCursor = null
,08-26 15:42:45.176  1017  1489 D WifiService: setWifiEnabled: false pid=6792, uid=10171
,08-26 15:42:45.176  1017  1489 D SettingsProvider: name = wifi_on
,08-26 15:42:45.186  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:45.196  1017  1128 E WifiNative-wlan0: do suspend true
,08-26 15:42:45.206  7369  7369 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-26 15:42:45.206  7369  7369 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-26 15:42:45.226  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
08-26 15:42:45.226  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:42:45.226   277   967 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:45.236  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:45.236  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:45.236  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.236  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:45.236  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.236  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:45.246  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:42:45.246  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:45.246  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:42:45.246  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
08-26 15:42:45.246   277   967 E Netd    : no such netId 503
,08-26 15:42:45.246  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:42:45.256  1017  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)',
08-26 15:42:45.256  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 15:42:45.256  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-26 15:42:45.256  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 15:42:45.256  1017  1130 V NetworkStats: updateIfacesLocked()
08-26 15:42:45.256  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:45.256  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:45.266  1017  1130 V NetworkStats: performPollLocked() took 13ms
08-26 15:42:45.266  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:45.266  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:45.266  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:45.266  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.266  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.266  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.266  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:45.276  1017  1127 D WifiP2pService: InactiveState{ what=131204 }
08-26 15:42:45.276  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 15:42:45.276  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 15:42:45.276  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-26 15:42:45.276  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:45.276  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-26 15:42:45.276  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:45.276  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 15:42:45.276  1017  7367 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:45.276  1017  7367 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 15:42:45.276  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 15:42:45.276  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 15:42:45.276  1017  2754 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:45.276  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:42:45.276  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:45.276  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:45.276  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 15:42:45.276  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:42:45.276  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:45.276  1017  2754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:45.276  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:45.286  1654  1654 I Hs20UtilService: Starting #15
,08-26 15:42:45.286  1654  1703 I Hs20UtilService: Message received 5007
08-26 15:42:45.286  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:45.286  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:45.286  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:45.286  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:45.286  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 15:42:45.286  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:42:45.296  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-26 15:42:45.296  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 15:42:45.296  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 15:42:45.296  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:45.296  1017  1047 D WifiDisplayController: disconnect
08-26 15:42:45.296  1017  1047 D WifiDisplayController: updateConnection
08-26 15:42:45.296  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:45.296  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:45.296  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 15:42:45.296  1017  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:45.296  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 15:42:45.296  1017  1127 D WifiP2pService: P2pDisablingState
,08-26 15:42:45.296  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-26 15:42:45.296  1017  1127 D WifiP2pService: p2p socket connection lost
08-26 15:42:45.306  1017  1128 E WifiNative-wlan0: do suspend true
08-26 15:42:45.306  1017  1127 D WifiP2pService: P2pDisabledState
,08-26 15:42:45.306  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 15:42:45.306  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:45.306  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:45.306  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:45.316  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-26 15:42:45.316  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:45.316  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:45.316  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:45.326  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:45.326  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:45.326  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,08-26 15:42:45.326  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:45.326  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:45.326  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 15:42:45.336  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-26 15:42:45.336   277   967 D CommandListener: Clearing all IP addresses on wlan0,
,08-26 15:42:45.336  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:45.336  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:45.336  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:45.336  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:45.336  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:45.336  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:45.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:45.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.336  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:45.346  7305  7305 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
08-26 15:42:45.346  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:42:45.346  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:45.356  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:45.356  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:45.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.356  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:45.356  7033  7033 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:45.356  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:45.356  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:45.366  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:45.366  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:45.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:45.366  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:45.366  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 15:42:45.366  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:45.366  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:45.366  1178  1178 D HotspotTile: onReceive : 0, 0
,08-26 15:42:45.366  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:45.366  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:45.366  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:45.366  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:45.366  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:45.376  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:45.376  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:45.376  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:45.376  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:45.376  7048  7048 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:45.386  1017  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:45.386  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:45.386  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:45.386  1017  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:45.386  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:45.386  1654  1654 I Hs20UtilService: Starting #16
,08-26 15:42:45.386  1654  1703 I Hs20UtilService: Message received 5007
,08-26 15:42:45.386  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:42:45.386  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:45.396  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:45.396  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-26 15:42:45.396  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
08-26 15:42:45.396  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:45.396  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:45.406  1017  1337 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:45.406  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:45.406  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:45.406  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:45.406  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:45.406  1654  1654 I Hs20UtilService: Starting #17,
08-26 15:42:45.406  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:45.406  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:45.416  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:45.416  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:45.416  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:45.476  7305  7305 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:45.556  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:45.556  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:45.556  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:45.556  7305  7305 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 15:42:45.576  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:45.576  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:45.576  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:45.586  1017  1131 D Tethering: InitialState.processMessage what=4
08-26 15:42:45.586  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:45.586  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:45.586  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:45.586  7305  7305 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-26 15:42:45.586  7305  7305 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED,
08-26 15:42:45.586  7305  7305 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 15:42:45.586  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:45.586  1017  1131 E Tethering: No numeric data
08-26 15:42:45.586  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:45.586  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:42:45.586  7305  7305 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:45.586  7305  7305 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 15:42:45.586  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:45.596  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:45.596  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:45.596  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:45.596  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 15:42:45.596  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:45.596  1017  1125 V NetworkStats: performPollLocked() took 6ms
,08-26 15:42:45.596  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:45.596  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:45.596  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:45.596  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:45.596  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:45.766  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:45.766  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:45.766  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:45.796  7305  7305 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:45.856  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 15:42:45.856  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:45.856  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:45.866  7305  7305 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-26 15:42:45.976  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 15:42:45.976  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:42:45.976  7010  7010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:45.976  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:42:45.976  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 15:42:45.976  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:45.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:45.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 15:42:45.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:45.986  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 15:42:45.976  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:45.986  1178  1178 D HotspotTile: onReceive : 1, 0
,08-26 15:42:45.976  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 15:42:45.986  1987  2163 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:45.986  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:45.986  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:45.996  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:45.996  1017  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:45.996  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:45.996  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:45.996  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:45.996  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:45.996  1654  1654 I Hs20UtilService: Starting #18
,08-26 15:42:45.996  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:46.006  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:46.006  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 15:42:46.006  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:46.006  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:46.626  1017  1044 D Tethering: interfaceRemoved wlan0
,08-26 15:42:46.626  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 15:42:46.746  1017  1044 D Tethering: interfaceRemoved p2p0
,08-26 15:42:46.746  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 15:42:46.946   288   288 E SMD     : DCD OFF,
,08-26 15:42:47.566  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 15:42:48.176  6792  6845 D BluetoothAdapter: enable()
,08-26 15:42:48.186  1017  1347 W ActivityManager: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:42:48.186  1017  1347 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 15:42:48.186  1017  1347 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:48.186  1017  1347 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:42:48.186  1017  1347 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 15:42:48.186  1017  1347 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 15:42:48.186  1017  1347 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 15:42:48.186  1017  1347 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:48.186  1017  1347 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:42:48.186  1017  1347 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:48.196  1017  1347 D SettingsProvider: name = bluetooth_on,
,08-26 15:42:48.196  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:42:48.196  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:48.196  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 15:42:48.196  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 15:42:48.206  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.206  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.206  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:48.206  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.226  7401  7401 E Zygote  : MountEmulatedStorage(),
08-26 15:42:48.226  7401  7401 E Zygote  : v2
08-26 15:42:48.226  7401  7401 I libpersona: KNOX_SDCARD checking this for 1002
08-26 15:42:48.226  7401  7401 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:48.226  7401  7401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:48.226  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7401 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 15:42:48.226  7401  7401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 15:42:48.226  7401  7401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:48.256  7401  7401 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:48.256  7401  7401 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:48.276  7401  7401 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 15:42:48.276  7401  7401 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:48.306  7401  7401 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding GattService
,08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding HidService
08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding HealthService
08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding PanService
,08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding SapService
08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding SapClientService
08-26 15:42:48.336  7401  7401 D BtSettings.ProfileConfig: Adding HidDevService
08-26 15:42:48.336  7401  7401 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 15:42:48.336  1017  4967 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 15:42:48.336  1017  4967 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.336  1017  4967 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.336  1017  4967 D SettingsProvider: selectionArgs: false
08-26 15:42:48.336  1017  4967 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.336  1017  4967 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.336  1017  4967 D SettingsProvider: ret = -1
,08-26 15:42:48.336  1017  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 15:42:48.336  1017  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:48.336  1017  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.336  1017  1475 D SettingsProvider: selectionArgs: false
08-26 15:42:48.336  1017  1475 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.336  1017  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.336  1017  1475 D SettingsProvider: ret = -1
,08-26 15:42:48.336  1017  1140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 15:42:48.336  1017  1140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:48.336  1017  1140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.336  1017  1140 D SettingsProvider: selectionArgs: false
08-26 15:42:48.336  1017  1140 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.336  1017  1140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.336  1017  1140 D SettingsProvider: ret = -1
,08-26 15:42:48.336  1017  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 15:42:48.336  1017  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.336  1017  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:42:48.336  1017  1495 D SettingsProvider: selectionArgs: false
08-26 15:42:48.336  1017  1495 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.336  1017  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.336  1017  1495 D SettingsProvider: ret = -1
,08-26 15:42:48.346  1017  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 15:42:48.346  1017  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:48.346  1017  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.346  1017  1489 D SettingsProvider: selectionArgs: false
08-26 15:42:48.346  1017  1489 D SettingsProvider: selectionArgs: 1002
,08-26 15:42:48.346  1017  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:42:48.346  1017  1489 D SettingsProvider: ret = -1
08-26 15:42:48.346  1017  1488 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 15:42:48.346  1017  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.346  1017  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:42:48.346  1017  1488 D SettingsProvider: selectionArgs: false
08-26 15:42:48.346  1017  1488 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.346  1017  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.346  1017  1488 D SettingsProvider: ret = -1
08-26 15:42:48.346  1017  2754 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 15:42:48.346  1017  2754 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.346  1017  2754 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:42:48.346  1017  2754 D SettingsProvider: selectionArgs: false
08-26 15:42:48.346  1017  2754 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.346  1017  2754 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.346  1017  2754 D SettingsProvider: ret = -1
,08-26 15:42:48.346  1017  1476 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-26 15:42:48.346  1017  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.346  1017  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.346  1017  1476 D SettingsProvider: selectionArgs: false
,08-26 15:42:48.346  1017  1476 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.346  1017  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:42:48.346  1017  1476 D SettingsProvider: ret = -1
,08-26 15:42:48.346  1017  1337 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:48.346  1017  1337 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.346  1017  1337 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.346  1017  1337 D SettingsProvider: selectionArgs: false
08-26 15:42:48.346  1017  1337 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.346  1017  1337 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.346  1017  1337 D SettingsProvider: ret = -1
,08-26 15:42:48.346  1017  1347 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:48.346  1017  1347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.346  1017  1347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:42:48.346  1017  1347 D SettingsProvider: selectionArgs: false
08-26 15:42:48.346  1017  1347 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.346  1017  1347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.346  1017  1347 D SettingsProvider: ret = -1
,08-26 15:42:48.346  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 15:42:48.346  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:48.356  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.356  1017  1030 D SettingsProvider: selectionArgs: false
08-26 15:42:48.356  1017  1030 D SettingsProvider: selectionArgs: 1002
,08-26 15:42:48.356  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:42:48.356  1017  1030 D SettingsProvider: ret = -1
,08-26 15:42:48.356  1017  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 15:42:48.356  1017  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.356  1017  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:48.356  1017  1477 D SettingsProvider: selectionArgs: false
08-26 15:42:48.356  1017  1477 D SettingsProvider: selectionArgs: 1002
08-26 15:42:48.356  1017  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.356  1017  1477 D SettingsProvider: ret = -1
,08-26 15:42:48.366  7401  7401 D BluetoothAdapterState: make
,08-26 15:42:48.376  7401  7401 I bluedroid: init
,08-26 15:42:48.376  7401  7401 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 15:42:48.376  7401  7416 I BluetoothAdapterState: Entering OffState
08-26 15:42:48.376  7401  7401 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 15:42:48.376  7401  7401 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 15:42:48.376  7401  7401 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 15:42:48.376  7401  7401 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-26 15:42:48.376  7401  7401 I bluedroid: get_profile_interface socket
08-26 15:42:48.376  7401  7401 I bluedroid: get_profile_interface map_client
,08-26 15:42:48.376  7401  7401 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 15:42:48.376  7401  7419 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 15:42:48.386  7401  7419 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 15:42:48.386  7401  7419 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:42:48.386  7401  7419 I bluedroid: getModelRssiValues
08-26 15:42:48.386  7401  7419 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:42:48.386  7401  7419 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:42:48.386  1017  1017 D SettingsProvider: name = bluetooth_name
,08-26 15:42:48.386  7401  7419 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
08-26 15:42:48.386  7401  7401 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:48.386  1017  1347 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
08-26 15:42:48.386  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.396  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.396  1017  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.396  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:48.396  7401  7409 I bluedroid: config_hci_snoop_log
,08-26 15:42:48.396  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-26 15:42:48.396  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-26 15:42:48.406  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 15:42:48.406  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 15:42:48.406  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:42:48.406  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:48.406  7401  7401 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-26 15:42:48.406  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:48.406  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 15:42:48.416  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:42:48.416  7401  7416 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 15:42:48.416  7401  7416 D BluetoothAdapterProperties: Setting state to 11
,08-26 15:42:48.416  7401  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:42:48.416  7401  7416 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 15:42:48.416  7401  7416 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 15:42:48.416  7401  7416 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:42:48.416  7401  7416 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 15:42:48.416  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:48.416  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-26 15:42:48.426  7401  7416 D BluetoothSecureManager: getInstant: null
08-26 15:42:48.426  7401  7416 D BluetoothSecureManager: calling getMethod for getService
08-26 15:42:48.426  7401  7416 D BluetoothSecureManager: calling getService
,08-26 15:42:48.426  7401  7416 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1ffec5ba
,08-26 15:42:48.426  1017  1489 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 15:42:48.426  1017  1489 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-26 15:42:48.426  7401  7416 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:42:48.426  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 15:42:48.426  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:42:48.426  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:48.426  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 15:42:48.426  1178  1178 D BluetoothTile:  getBluetoothState : 11
08-26 15:42:48.426  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 15:42:48.426  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 15:42:48.426  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:42:48.426  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 15:42:48.426  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:42:48.426  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 15:42:48.426  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:42:48.426  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 15:42:48.426  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:42:48.426  1918  1918 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 15:42:48.426  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 15:42:48.426  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:48.436  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 15:42:48.436  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:48.436  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
08-26 15:42:48.436  7401  7416 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 15:42:48.436  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-26 15:42:48.436  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:48.436  7401  7416 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:48.436  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:48.436  7401  7416 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:48.436  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:48.436  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:48.436  7401  7416 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:48.436  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:42:48.436  7401  7416 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 15:42:48.436  1017  1488 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:48.436  1017  1347 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:48.436  1017  2754 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:48.436  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.446  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:42:48.446  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.446  1017  2754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:48.446  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:48.446  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:48.446  7401  7416 D BluetoothBondStateMachine: make
,08-26 15:42:48.446  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:48.446  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:48.456  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 15:42:48.456  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 15:42:48.456  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 15:42:48.456  7401  7422 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 15:42:48.456  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:48.456  1017  4967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:48.456  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-26 15:42:48.456  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.456  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.456  1017  4967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.456  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:48.456  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:42:48.456  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:42:48.456  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 15:42:48.456  7401  7401 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:42:48.456  7401  7401 D BtGatt.GattService: Received start request. Starting profile...
08-26 15:42:48.456  7401  7401 D BtGatt.GattService: start()
08-26 15:42:48.456  7401  7401 D BtGatt.GattService: start()
08-26 15:42:48.456  7401  7401 I bluedroid: get_profile_interface gatt
08-26 15:42:48.456  1017  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 15:42:48.456  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:48.456  7401  7401 D BtGatt.AdvertiseManager: advertise manager created
,08-26 15:42:48.466  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.466  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.466  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:48.466  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.476  1017  1489 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7424 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-26 15:42:48.476  7424  7424 E Zygote  : MountEmulatedStorage()
,08-26 15:42:48.476  7424  7424 E Zygote  : v2
08-26 15:42:48.476  7424  7424 I libpersona: KNOX_SDCARD checking this for 10055
08-26 15:42:48.476  7424  7424 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:48.476  7424  7424 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:48.486  1017  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:48.486  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.486  7424  7424 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:48.486  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.486  1017  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.486  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-26 15:42:48.486  7424  7424 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:48.486  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 15:42:48.486  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:42:48.486  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:48.486  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:48.486  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:42:48.486  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.486  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.486  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:48.496  7401  7401 D BtGatt.GattService: mStartError = false
08-26 15:42:48.496  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:48.496  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 15:42:48.496  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:48.496  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:42:48.496  7401  7401 D HeadsetService: Received start request. Starting profile...
08-26 15:42:48.496  7401  7401 D HeadsetService: start()
,08-26 15:42:48.496  1017  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:48.496  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.496  7401  7401 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 15:42:48.506  7401  7401 D HeadsetStateMachine: make
,08-26 15:42:48.506  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.506  1017  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.506  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:48.506  7401  7401 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 15:42:48.506  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 15:42:48.506  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:42:48.506  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:42:48.516  1017  4967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:48.516  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.516  7424  7424 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:48.516  7424  7424 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:48.516  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.516  1017  4967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.516  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:48.516  1017  1489 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 15:42:48.516  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.516  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.516  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.516  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 15:42:48.516  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 15:42:48.516  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:42:48.516  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:42:48.526  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:48.526  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.526  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.526  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.526  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:48.526  1017  1337 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 15:42:48.526  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.526  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:48.526  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:48.526  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.526  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.526  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 15:42:48.526  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:48.526  1017  1337 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:48.526  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.526  7401  7401 I bluedroid: get_profile_interface handsfree
,08-26 15:42:48.536  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:48.536  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.536  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:42:48.536  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 15:42:48.536  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:48.536  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.536  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.536  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:48.536  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:48.536  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:48.536  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:42:48.536  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:42:48.536  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:42:48.536  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:42:48.536  7401  7416 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 15:42:48.556  7401  7401 I DualScoManager: Instantiating Dual Sco Manager
,08-26 15:42:48.556  7401  7401 I DualScoManager: Set HeadsetServiceHelper
,08-26 15:42:48.556  7401  7401 D BluetoothAtMessage: createCMTIContentObservers
,08-26 15:42:48.556  7424  7424 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 15:42:48.556  1017  1495 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 15:42:48.556  1017  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:48.556  1017  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:42:48.556  1017  1495 D SettingsProvider: selectionArgs: false
,08-26 15:42:48.556  1017  1495 D SettingsProvider: selectionArgs: 1002
,08-26 15:42:48.556  1017  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:48.556  1017  1495 D SettingsProvider: ret = -1
,08-26 15:42:48.566  7401  7435 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 15:42:48.566  7401  7401 D HeadsetService: mStartError = false
08-26 15:42:48.566  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:48.566  7401  7401 D A2dpService: Received start request. Starting profile...
08-26 15:42:48.566  7401  7401 D A2dpService: start()
,08-26 15:42:48.566  7401  7435 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 15:42:48.566  7401  7401 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 15:42:48.566  7401  7435 D HeadsetStateMachine: map size, before remove : 0
08-26 15:42:48.566  7401  7435 D HeadsetStateMachine: map size, after remove: 0
08-26 15:42:48.566  7401  7401 I bluedroid: get_profile_interface avrcp
,08-26 15:42:48.576  7401  7401 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:42:48.576  7401  7401 D Avrcp   : Initialize Media Controller
,08-26 15:42:48.576  7401  7401 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 15:42:48.576  7401  7401 E Avrcp   : getActiveSessions
08-26 15:42:48.576  7401  7401 D Avrcp   : pick active media Controller
08-26 15:42:48.576  7401  7401 D Avrcp   : Get the active Media Controller 
,08-26 15:42:48.586  7424  7424 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 15:42:48.586  7424  7424 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 15:42:48.586  7424  7424 D UserAnalysis: Create SecureDbHelper
,08-26 15:42:48.596  7401  7401 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 15:42:48.596  7401  7444 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 15:42:48.596  7424  7424 D IntelligenceServiceApplication: onCreate()
,08-26 15:42:48.596  7401  7401 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 15:42:48.596  7401  7401 D A2dpStateMachine: make
,08-26 15:42:48.606  1017  1495 I ActivityManager: Killing 7080:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 15:42:48.606  7401  7401 I bluedroid: get_profile_interface a2dp
,08-26 15:42:48.606  7401  7446 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 15:42:48.606  7401  7401 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 15:42:48.606  7424  7424 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 15:42:48.606  7401  7401 D A2dpService: mStartError = false
08-26 15:42:48.606  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:48.606  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-26 15:42:48.606  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 15:42:48.606  7401  7445 D A2dpStateMachine: Enter Disconnected: -2
08-26 15:42:48.606  7401  7401 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 15:42:48.616  7424  7424 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 15:42:48.616  7401  7401 D HidService: Received start request. Starting profile...
08-26 15:42:48.616  7401  7401 D HidService: start()
08-26 15:42:48.616  7401  7401 I bluedroid: get_profile_interface hidhost
08-26 15:42:48.616  7401  7401 D HidService: setHidService(): set to: null
08-26 15:42:48.616  7401  7401 D HidService: mStartError = false
08-26 15:42:48.616  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:48.616  7401  7401 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 15:42:48.616  7401  7401 D HealthService: Received start request. Starting profile...
08-26 15:42:48.616  7401  7401 D HealthService: start()
08-26 15:42:48.616  7401  7444 D BluetoothMediaBrowser: no now playing list
08-26 15:42:48.616  7401  7444 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 15:42:48.616  7401  7401 I bluedroid: get_profile_interface health
,08-26 15:42:48.616  7401  7401 D HealthService: mStartError = false
08-26 15:42:48.616  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:48.616  7401  7401 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 15:42:48.616  1416  1437 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 15:42:48.616  1416  1416 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 15:42:48.616  1416  1416 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 15:42:48.616  1416  1437 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 15:42:48.626  7401  7401 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 15:42:48.626  7401  7401 D PanService: Received start request. Starting profile...
,08-26 15:42:48.626  7401  7401 D PanService: start()
08-26 15:42:48.626  7401  7401 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:42:48.626  7401  7401 I bluedroid: get_profile_interface pan
,08-26 15:42:48.626  7401  7401 D PanService: mStartError = false
08-26 15:42:48.626  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:48.626  7401  7401 D HeadsetStateMachine: Proxy object connected
,08-26 15:42:48.626  7401  7401 D BluetoothMapService: Received start request. Starting profile...
,08-26 15:42:48.626  7401  7401 D BluetoothMapService: start()
08-26 15:42:48.626  7424  7424 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 15:42:48.626  7401  7401 D BluetoothMapService: mStartError = false
,08-26 15:42:48.626  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:48.626  7401  7401 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-26 15:42:48.626  7401  7435 D HeadsetStateMachine: Disconnected process message: 11
,08-26 15:42:48.626  7401  7401 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 15:42:48.636  7401  7401 D SapService: Received start request. Starting profile...
,08-26 15:42:48.636  7401  7401 D SapService: start(),
,08-26 15:42:48.636  7401  7401 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 15:42:48.636  7401  7401 I bluedroid: get_profile_interface sap
08-26 15:42:48.636  7401  7401 D SapService: mStartError = false
08-26 15:42:48.636  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:48.636  7401  7401 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 15:42:48.636  7401  7401 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 15:42:48.636  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-26 15:42:48.636  7401  7401 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:42:48.636  7401  7401 D BluetoothA2dp: Proxy object connected
08-26 15:42:48.636  7401  7401 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 15:42:48.636  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true,
08-26 15:42:48.636  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 15:42:48.636  7401  7435 D HeadsetStateMachine: Disconnected process message: 18
08-26 15:42:48.636  7401  7435 D HeadsetStateMachine: Disconnected process message: 10
08-26 15:42:48.636  7401  7435 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 15:42:48.636  7401  7435 D HeadsetStateMachine: Disconnected process message: 11
08-26 15:42:48.636  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 15:42:48.636  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 15:42:48.636  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 15:42:48.646  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:48.646  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:48.646  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.646  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:48.656  7451  7451 E Zygote  : MountEmulatedStorage()
08-26 15:42:48.656  7451  7451 I libpersona: KNOX_SDCARD checking this for 10105
08-26 15:42:48.656  7451  7451 E Zygote  : v2
08-26 15:42:48.656  7451  7451 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:48.656  7451  7451 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:48.656  1017  1477 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7451 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 15:42:48.656  7451  7451 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:48.656  7451  7451 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:48.676  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 15:42:48.676  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 15:42:48.686  7451  7451 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:48.686  7451  7451 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:48.686  7401  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 15:42:48.686  7401  7416 I bluedroid: enable
,08-26 15:42:48.686  7401  7416 I bt_hci_bdroid: init
,08-26 15:42:48.686  7401  7467 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 15:42:48.696  7401  7416 I bt_vendor: bt-vendor : init
,08-26 15:42:48.696  7401  7416 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 15:42:48.696  7401  7416 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 15:42:48.696  7401  7416 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 15:42:48.696  7401  7416 D bt_userial_mct: userial_init
08-26 15:42:48.696  7401  7416 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 15:42:48.696  7401  7416 I bt_vendor: Starting hciattach daemon
08-26 15:42:48.696  7401  7416 I bt_vendor: try to set false
,08-26 15:42:48.696  7401  7416 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-26 15:42:48.696  7401  7416 I bt_vendor: Starting hciattach daemon
08-26 15:42:48.696  7401  7416 I bt_vendor: try to set true
,08-26 15:42:48.706  1017  3347 D SSRM:n  : SIOP:: AP = 370
,08-26 15:42:48.726  7472  7472 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 15:42:48.766  7480  7480 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 15:42:48.776  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 15:42:48.796  7483  7483 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:42:48.806  7484  7484 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 15:42:48.806  7485  7485 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:42:48.816  7488  7488 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 15:42:48.846   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 15:42:48.846   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:48.846  7451  7486 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 15:42:48.846   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 15:42:48.846   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:48.846  7451  7486 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177,)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.m,ap.m.q.a(PG:8698)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:48.996  7451  7451 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:48.996  7451  7451 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:49.006  1017  2754 I ActivityManager: Killing 7088:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-26 15:42:49.006  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 15:42:49.016  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:49.056  7451  7500 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 15:42:49.076  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-26 15:42:49.086  1017  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:49.086  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.086  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:49.086  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.086  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 15:42:49.156  7401  7416 I bt_vendor: bluetooth satus is on
,08-26 15:42:49.156  7401  7470 D bt_userial_mct: userial_open(port:0)
08-26 15:42:49.156  7401  7470 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 15:42:49.156  7401  7470 I bt_vendor: Done intiailizing UART
,08-26 15:42:49.156  7401  7470 I bt_vendor: Done intiailizing UART
08-26 15:42:49.156  7401  7470 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-26 15:42:49.156  7401  7470 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:42:49.156  7401  7467 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 15:42:49.166  7401  7506 D bt_userial_mct: Entering userial_read_thread()
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 15:42:49.166  7401  7467 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 15:42:49.256  7401  7467 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 15:42:49.256  7401  7467 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa426bed1 
,08-26 15:42:49.256  7401  7467 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa426bed1 
,08-26 15:42:49.276  7401  7419 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 15:42:49.276  7401  7419 E bt-btif : Calling BTA_HhEnable
,08-26 15:42:49.276  7401  7419 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 15:42:49.286  7401  7419 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-26 15:42:49.286  7401  7419 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:42:49.286  7401  7419 I bluedroid: getModelRssiValues
08-26 15:42:49.286  7401  7419 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:42:49.286  7401  7419 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:42:49.286  7401  7419 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 15:42:49.286  1017  1017 D SettingsProvider: name = bluetooth_name
,08-26 15:42:49.286  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:49.296  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:49.296  7401  7419 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:42:49.296  7401  7419 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:42:49.296  7401  7419 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:42:49.296  7401  7419 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-26 15:42:49.296  7401  7419 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-26 15:42:49.296  7401  7419 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-26 15:42:49.296  7401  7419 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 15:42:49.296  7401  7419 E bt-btif : btif_sock_init: !vhci_init
,08-26 15:42:49.296  7401  7419 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 15:42:49.306  7401  7506 E bt_mct  : hci lib postload completed
,08-26 15:42:49.306  7401  7419 D IOP_DB_BT: db_open: db_open : handle 3027898384l, read 13894 bytes onto local cache
,08-26 15:42:49.306  7401  7419 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 15:42:49.306  7401  7419 D IOP_DB_BT: db_query: result 1
08-26 15:42:49.306  7401  7419 I         : iop_db_open: iop_db_open status 0
,08-26 15:42:49.306  7401  7419 D bte_conf: Device ID record 1 : primary
,08-26 15:42:49.306  7401  7419 D bte_conf:   vendorId            = 0075
,08-26 15:42:49.306  7401  7419 D bte_conf:   vendorIdSource      = 0001
08-26 15:42:49.306  7401  7419 D bte_conf:   product             = 0100
08-26 15:42:49.306  7401  7419 D bte_conf:   version             = 0200
08-26 15:42:49.306  7401  7419 D bte_conf:   clientExecutableURL = 
08-26 15:42:49.306  7401  7419 D bte_conf:   serviceDescription  = 
08-26 15:42:49.306  7401  7419 D bte_conf:   documentationURL    = 
08-26 15:42:49.306  7401  7419 D bte_conf: bte_load_did_conf no section named DID2.
08-26 15:42:49.306  7401  7419 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 15:42:49.316  7401  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 15:42:49.316  7401  7416 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:42:49.316  7401  7416 D BluetoothAdapterProperties: State =  11
,08-26 15:42:49.316  1017  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:42:49.316  7401  7416 D BluetoothAdapterProperties: Setting state to 12
08-26 15:42:49.316  7401  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 15:42:49.316  7401  7419 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:42:49.316  7401  7419 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:42:49.316  7401  7419 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:42:49.326  1017  1140 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 15:42:49.326  1017  1140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:49.326  1017  1140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:49.326  1017  1140 D SettingsProvider: selectionArgs: false
08-26 15:42:49.326  1017  1140 D SettingsProvider: selectionArgs: 1002
08-26 15:42:49.326  1017  1140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:49.326  1017  1140 D SettingsProvider: ret = -1
08-26 15:42:49.326  7401  7416 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 15:42:49.326  7401  7416 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 15:42:49.326  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:49.326  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.326  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.326  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:49.336  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:49.336  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:49.336  7401  7416 D BluetoothAdapterService: Autoconnection is available 
08-26 15:42:49.336  7401  7416 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 15:42:49.336  7401  7416 D BluetoothAdapterService: starting service from this receiver
,08-26 15:42:49.336  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:49.336  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.346  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:49.346  7401  7420 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.346  7401  7420 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:49.346  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.346  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.346  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.346  3066  3076 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:42:49.346  7401  7416 I BluetoothAdapterState: Entering On State from state = 11
,08-26 15:42:49.346  3066  3076 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:49.346  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 15:42:49.346  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.356  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.356  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.356  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:49.356  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:49.366  3066  3066 D BluetoothA2dp: Proxy object connected
08-26 15:42:49.366  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:49.366  3066  3066 D A2dpProfile: Bluetooth service connected
,08-26 15:42:49.366  1416  1425 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:49.366  7401  7401 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 15:42:49.366  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:42:49.366  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:49.376  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.376  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.376  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.376  1416  1425 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:42:49.376  6792  6800 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:42:49.376  6792  6800 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:49.376  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:49.376  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:42:49.376  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:42:49.376  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:42:49.376  3066  3074 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 15:42:49.376  3066  3074 D Bluetoothsap: Binding service...
,08-26 15:42:49.386  7401  7401 I BluetoothPbapService: Handler(): got msg=1
,08-26 15:42:49.386  3066  3074 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 15:42:49.386  1017  1337 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:42:49.386  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 15:42:49.386  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.386  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.386  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.386  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.386  3066  3074 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-26 15:42:49.386  3066  3076 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.386  3066  3076 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:49.386  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.386  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:49.386  1017  1046 D BluetoothPan: Binding service...
08-26 15:42:49.386  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:42:49.386  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.396  1416  3290 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,08-26 15:42:49.396  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:42:49.396  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:42:49.396  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.396  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.396  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.396  7401  7511 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 15:42:49.396  1416  3290 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:42:49.396  1439  1685 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.396  1439  1685 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:49.396  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 15:42:49.396  1416  1437 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.396  1416  1437 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:49.396  3066  3066 D SapProfile: Bluetooth service connected
08-26 15:42:49.396  3066  3066 D Bluetoothsap: getConnectedDevices()
08-26 15:42:49.396  3066  3074 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:42:49.396  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:42:49.396  7401  7511 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:42:49.396  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 15:42:49.396  7401  7511 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:42:49.396  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 15:42:49.396  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.396  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.396  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.406  3066  3066 D BluetoothMap: Proxy object connected
,08-26 15:42:49.406  3066  3076 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 15:42:49.406  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 15:42:49.406  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.406  7401  7511 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-26 15:42:49.406  7401  7511 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:42:49.406  7401  7511 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:42:49.406  7401  7511 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@101a3f1f
,08-26 15:42:49.406  7401  7511 D BluetoothSocket: channel: 19
08-26 15:42:49.406  7401  7511 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-26 15:42:49.406  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.406  3066  3066 D MapProfile: Bluetooth service connected
08-26 15:42:49.406  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.406  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.406  3066  3066 D BluetoothMap: getConnectedDevices()
,08-26 15:42:49.406  7401  7409 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:42:49.406  1178  1851 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.406  1178  1851 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:49.416  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:42:49.416  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 15:42:49.416  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:42:49.416  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.416  1017  1017 D BluetoothA2dp: Proxy object connected
08-26 15:42:49.416  1416  1425 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:49.416  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:42:49.416  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:49.416  3066  3066 D BluetoothInputDevice: Proxy object connected
08-26 15:42:49.416  3066  3066 D HidProfile: Bluetooth service connected
,08-26 15:42:49.416  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.416  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.416  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.416  1416  1425 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:42:49.416  3066  3076 D BluetoothPan: Binding service...
,08-26 15:42:49.416  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:42:49.416  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.416  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.416  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.416  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 15:42:49.416  3066  3066 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:42:49.416  3066  3066 D PanProfile: Bluetooth service connected
,08-26 15:42:49.426  3066  3076 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:49.426  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:42:49.426  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:49.426  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.426  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.426  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.426  3066  3076 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:42:49.426  1987  1997 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.426  1987  1997 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:49.426  3066  3066 D HeadsetProfile: Bluetooth service connected
08-26 15:42:49.426  7451  7469 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.426  7451  7469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:49.426  3066  3074 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 15:42:49.426  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-26 15:42:49.426  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.426  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.426  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:49.426  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.436  3066  3066 D BluetoothPbap: Proxy object connected
08-26 15:42:49.436  3066  3066 D PbapServerProfile: Bluetooth service connected
,08-26 15:42:49.436  1439  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:49.436  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:42:49.436  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:49.436  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.436  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.436  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.436  1439  1449 E BluetoothHeadset: BluetoothHeadset service is binded,
08-26 15:42:49.436  1426  1802 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:49.436  1426  1802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:49.436  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 15:42:49.436  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:42:49.436  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:49.436  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
,08-26 15:42:49.436  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:42:49.446  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:42:49.446  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:42:49.446  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:49.456  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:49.456  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:49.456  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-26 15:42:49.456  1416  1416 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@f791c4b, true
,08-26 15:42:49.456  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:49.456  1416  1416 D BluetoothHeadset: registerMessageListener
,08-26 15:42:49.456  1918  1918 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:49.456  1017  1489 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:49.456  1017  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 15:42:49.456  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:49.466  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:49.466  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:49.466  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 15:42:49.466  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:49.466  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 15:42:49.466  7401  7409 D HeadsetService: registerMessageListener
,08-26 15:42:49.466  7401  7409 D HeadsetService: registerMessageListener
,08-26 15:42:49.476  7401  7513 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 15:42:49.476  7401  7435 D HeadsetStateMachine: Disconnected process message: 70
,08-26 15:42:49.476  7401  7435 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@b62826c
08-26 15:42:49.476  1416  1416 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 15:42:49.476  1416  1416 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:42:49.476  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.476  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:49.476  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.476  1416  1416 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 15:42:49.476  1416  1416 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 15:42:49.476  1416  1416 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 15:42:49.486  3066  3066 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-26 15:42:49.486  3066  3066 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-26 15:42:49.486  3066  3066 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-26 15:42:49.486  7401  7435 D HeadsetStateMachine: Disconnected process message: 9
08-26 15:42:49.486  3066  3066 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 15:42:49.486  7401  7435 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 15:42:49.486  7401  7513 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:42:49.486  7401  7513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:42:49.486  7401  7513 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-26 15:42:49.486  7401  7513 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:42:49.486  7401  7513 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:42:49.486  7401  7513 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2836a035
,08-26 15:42:49.486  7401  7513 D BluetoothSocket: channel: 5
,08-26 15:42:49.496   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 15:42:49.496   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 15:42:49.496   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-26 15:42:49.496   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-26 15:42:49.496   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 15:42:49.496   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 15:42:49.496   283   283 V audio_hw_primary: adev_set_parameters: exit
,08-26 15:42:49.496  7401  7435 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 15:42:49.496  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:49.496  1017  1337 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:42:49.496  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.496  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.496  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.496  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:49.516  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:49.516  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:49.526  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:49.526  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 15:42:49.526  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:49.526  7401  7401 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:42:49.526  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:49.536  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.536  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.536  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:49.536  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:49.556  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:49.556  1017  1337 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:49.556  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.556  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.556  1017  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:49.556  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.566  1017  1475 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:42:49.566  1987  7522 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 15:42:49.566  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:49.576  1017  2754 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:49.576  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.576  1017  2754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:49.576  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.586  7401  7523 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:42:49.586  7401  7523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:42:49.586  7401  7523 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-26 15:42:49.586  7401  7523 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:42:49.586  7401  7523 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:42:49.586  7401  7523 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c3ef317
08-26 15:42:49.586  7401  7523 D BluetoothSocket: channel: 12
08-26 15:42:49.586  7401  7523 I BtOppRfcommListener: Accept thread started.
,08-26 15:42:49.596  1017  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:49.596  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.596  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:49.596  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.606  1987  7522 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 15:42:49.946   288   288 E SMD     : DCD OFF
,08-26 15:42:51.206  6792  6845 D BluetoothAdapter: disable()
,08-26 15:42:51.206  1017  1477 D SettingsProvider: name = bluetooth_on
,08-26 15:42:51.216  7401  7416 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 15:42:51.216  7401  7416 D BluetoothAdapterProperties: Setting state to 13
08-26 15:42:51.216  7401  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 15:42:51.216  7401  7416 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:51.216  7401  7416 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 15:42:51.216  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.216  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.216  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:51.216  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.216  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.216  7401  7401 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-26 15:42:51.216  7401  7416 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:42:51.216  7401  7416 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 15:42:51.216  7401  7416 D BluetoothAdapterService: terminating service from this receiver
08-26 15:42:51.216  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.216  7401  7401 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3fa8b304, channel: 19, state: LISTENING
08-26 15:42:51.216  7401  7401 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3fa8b304, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@101a3f1f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a77a0edmSocket: android.net.LocalSocket@3c45eb22 impl:android.net.LocalSocketImpl@35b5a9b3 fd:FileDescriptor[74]
08-26 15:42:51.216  7401  7401 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c45eb22 impl:android.net.LocalSocketImpl@35b5a9b3 fd:FileDescriptor[74]
,08-26 15:42:51.226  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.226  1017  2754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.226  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:51.226  7401  7416 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 15:42:51.226  7401  7416 D BluetoothAdapterProperties: mDiscovering is false
,08-26 15:42:51.226  1017  1337 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:42:51.226  7401  7416 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 15:42:51.226  3066  3066 D BluetoothPbap: Proxy object disconnected
08-26 15:42:51.226  3066  3066 D PbapServerProfile: Bluetooth service disconnected
,08-26 15:42:51.236  7401  7419 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:42:51.236  7401  7419 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:42:51.236  7401  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 15:42:51.236  7401  7416 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 15:42:51.236  7401  7416 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 15:42:51.236  7401  7416 E bt-btif : cmd socket is not created
,08-26 15:42:51.236  7401  7416 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 15:42:51.236  7401  7523 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 15:42:51.236  7401  7467 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 15:42:51.236  7401  7467 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 15:42:51.236  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:51.236  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.236  7401  7467 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 15:42:51.246  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.246  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:51.256  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:51.256  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:51.256  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:51.256  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:51.266  6792  6792 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.266  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:51.266  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.266  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-26 15:42:51.276  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:42:51.276  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.276  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-26 15:42:51.276  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-26 15:42:51.276  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:51.276  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:51.276  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:42:51.286  1017  1140 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:51.286  1017  1337 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:51.286  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:42:51.286  1918  1918 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:51.286  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.286  7401  7401 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cba5ee9, channel: 5, state: LISTENING
,08-26 15:42:51.286  7401  7401 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cba5ee9, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2836a035, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@257b976emSocket: android.net.LocalSocket@2ad72e0f impl:android.net.LocalSocketImpl@3c415e9c fd:FileDescriptor[76]
,08-26 15:42:51.296  7401  7401 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ad72e0f impl:android.net.LocalSocketImpl@3c415e9c fd:FileDescriptor[76]
,08-26 15:42:51.296  7401  7401 I BtOppRfcommListener: stopping Accept Thread
08-26 15:42:51.296  7401  7401 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b5100a5, channel: 12, state: LISTENING
08-26 15:42:51.296  7401  7401 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b5100a5, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c3ef317, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@344dbc7amSocket: android.net.LocalSocket@34e29c2b impl:android.net.LocalSocketImpl@453c888 fd:FileDescriptor[80]
08-26 15:42:51.296  7401  7401 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@34e29c2b impl:android.net.LocalSocketImpl@453c888 fd:FileDescriptor[80]
,08-26 15:42:51.296  7401  7523 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 15:42:51.296  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.296  1017  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:51.296  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.296  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.296  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:51.296  1017  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:51.296  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:51.306  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:51.306  1017  1140 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:42:51.306  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.306  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:51.306  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:51.306  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:51.316  7401  7401 V BluetoothOppManager: cleanUp...
,08-26 15:42:51.326  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:51.326  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:51.326  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.326  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 15:42:51.346  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:51.356  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:51.436  7401  7467 W bt-btif : ag scb idx 1 not allocated
08-26 15:42:51.436  7401  7467 W bt-btif : ag scb idx 2 not allocated
08-26 15:42:51.436  7401  7467 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 15:42:51.436  7401  7506 I bt_userial_mct: exiting userial_read_thread
08-26 15:42:51.436  7401  7506 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 15:42:51.436  7401  7419 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 15:42:51.436  7401  7470 I bt_vendor: hw_epilog_process
08-26 15:42:51.446  7401  7419 D bt_userial_mct: userial_close
08-26 15:42:51.446  7401  7419 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 15:42:52.416  1017  2754 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:42:52.426  1017  2754 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:42:52.426  1017  2754 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:42:52.426  1017  2754 D BatteryService: stay LED for fully charged
08-26 15:42:52.426  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:42:52.426  1017  1017 I MotionRecognitionService: Plugged
08-26 15:42:52.426  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:42:52.426  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:42:52.426  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:42:52.426  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:42:52.426  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:42:52.446  7401  7401 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:42:52.446  7401  7435 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:42:52.446  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:52.456  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:52.456  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:42:52.466  7401  7419 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 15:42:52.466  7401  7419 I bt_vendor: bluetooth satus is on
,08-26 15:42:52.466  7401  7419 I bt_vendor: bt-vendor : resetting BT status
08-26 15:42:52.466  7401  7419 I bt_vendor: Starting hciattach daemon
08-26 15:42:52.466  7401  7419 I bt_vendor: try to set false
,08-26 15:42:52.466  7401  7419 I bt_vendor: Starting hciattach daemon,
08-26 15:42:52.466  7401  7419 I bt_vendor: try to set false
,08-26 15:42:52.466  7401  7419 I bt_vendor: cleanup,
,08-26 15:42:52.466  7401  7467 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
,08-26 15:42:52.466  7401  7419 I GKI_LINUX: GKI_exit_task 0 done
08-26 15:42:52.466  7401  7419 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 15:42:52.476  7401  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
,08-26 15:42:52.476  7401  7416 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:42:52.476  7401  7416 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-26 15:42:52.476  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-26 15:42:52.476  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 15:42:52.476  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
,08-26 15:42:52.476  1017  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:52.476  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.476  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.476  1017  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 15:42:52.476  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-26 15:42:52.476  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:42:52.476  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 15:42:52.476  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 15:42:52.486  7401  7401 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:42:52.486  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.486  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.486  1017  1029 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:52.486  7401  7401 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 15:42:52.486  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-26 15:42:52.486  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:52.486  7401  7401 D BtGatt.GattService: stop()
08-26 15:42:52.486  1017  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.486  7401  7401 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 15:42:52.486  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:42:52.486  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:52.486  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:42:52.486  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 15:42:52.486  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
08-26 15:42:52.486  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.486  1017  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.486  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.486  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 15:42:52.486  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:52.486  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:42:52.486  1017  1140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.486  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.496  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.496  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.496  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.496  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 15:42:52.496  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 15:42:52.496  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:42:52.496  1017  1337 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:52.496  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.496  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.496  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.496  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.496  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-26 15:42:52.496  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 15:42:52.496  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:42:52.506  1017  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:52.506  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.506  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.506  1017  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:52.506  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.506  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.506  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.506  7401  7416 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.506  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:52.506  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0,
,08-26 15:42:52.516  1017  1488 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:52.516  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:52.516  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-26 15:42:52.516  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 15:42:52.516  1017  2754 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.516  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.516  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.516  1017  2754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:52.516  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:42:52.516  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:52.516  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:42:52.516  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:42:52.516  7401  7416 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:42:52.516  7401  7416 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:42:52.516  7401  7416 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 15:42:52.516  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 15:42:52.516  7401  7401 D HeadsetService: Received stop request...Stopping profile...
08-26 15:42:52.516  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:52.526  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 15:42:52.526  7401  7401 D A2dpService: Received stop request...Stopping profile...
,08-26 15:42:52.526  7401  7445 D A2dpStateMachine: Exit Disconnected: -1
,08-26 15:42:52.526  3066  3066 D HeadsetProfile: Bluetooth service disconnected
,08-26 15:42:52.526  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:52.526  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.526  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 15:42:52.526  3066  3066 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.526  3066  3066 D A2dpProfile: Bluetooth service disconnected
,08-26 15:42:52.526  7401  7401 D HidService: Received stop request...Stopping profile...
,08-26 15:42:52.526  7401  7401 D HidService: Stopping Bluetooth HidService
08-26 15:42:52.526  7401  7401 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 15:42:52.526  7401  7401 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 15:42:52.536  7401  7401 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:42:52.536  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:52.536  7401  7401 D HealthService: Received stop request...Stopping profile...
,08-26 15:42:52.536  3066  3066 D BluetoothInputDevice: Proxy object disconnected
08-26 15:42:52.536  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:52.536  3066  3066 D HidProfile: Bluetooth service disconnected
,08-26 15:42:52.536  7401  7401 D PanService: Received stop request...Stopping profile...
,08-26 15:42:52.536  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:52.536  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 15:42:52.536  7401  7401 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 15:42:52.536  3066  3066 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:52.536  3066  3066 D PanProfile: Bluetooth service disconnected
,08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:52.546  7401  7401 D SapService: Received stop request...Stopping profile...
08-26 15:42:52.546  7401  7401 D SapService: Stopping Bluetooth SapService
08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17187f2d
,08-26 15:42:52.546  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 15:42:52.546  7401  7401 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 15:42:52.546  7401  7401 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 15:42:52.546  7401  7401 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 15:42:52.546  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 15:42:52.546  7401  7401 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 15:42:52.546  7401  7401 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 15:42:52.546  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 15:42:52.546  7401  7401 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.546  7401  7446 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 15:42:52.546  7401  7401 I GKI_LINUX: GKI_exit_task 2 done
08-26 15:42:52.546  7401  7401 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 15:42:52.546  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 15:42:52.546  7401  7401 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.546  7401  7401 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:42:52.546  7401  7401 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:42:52.546  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 15:42:52.546  7401  7401 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.546  7401  7401 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.546  7401  7401 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:42:52.546  7401  7401 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 15:42:52.546  3066  3066 D BluetoothMap: Proxy object disconnected
08-26 15:42:52.546  3066  3066 D MapProfile: Bluetooth service disconnected
,08-26 15:42:52.546  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 15:42:52.546  3066  3066 D SapProfile: Bluetooth service disconnected
,08-26 15:42:52.556  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 15:42:52.556  7401  7401 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:52.556  7401  7401 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-26 15:42:52.556  7401  7401 E BluetoothAdapterService(387481389): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 15:42:52.556  7401  7401 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 15:42:52.556  7401  7401 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 15:42:52.556  7401  7416 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 15:42:52.556  7401  7416 D BluetoothAdapterProperties: Setting state to 10
08-26 15:42:52.556  7401  7416 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 15:42:52.556  7401  7416 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:52.556  7401  7416 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 15:42:52.556  7401  7416 D BluetoothAdapterService: Autoconnection is available 
08-26 15:42:52.556  7401  7416 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 15:42:52.556  7401  7416 I BluetoothAdapterState: Entering OffState
08-26 15:42:52.556  7401  7512 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.556  7401  7512 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.556  3066  7510 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:42:52.556  6792  6800 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:52.556  6792  6800 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:52.556  6792  6800 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-26 15:42:52.556  6792  6800 D BluetoothLeAdvertiser: Exit stop advertising
08-26 15:42:52.556  6792  6800 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 15:42:52.556  6792  6800 D BluetoothLeScanner: Exiting stopAllScan
,08-26 15:42:52.556  3066  3076 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 15:42:52.556  3066  3076 D Bluetoothsap: Unbinding service...
,08-26 15:42:52.566  3066  3074 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:52.566  3066  3074 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.566  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.566  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.566  1439  2457 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:52.566  1439  2457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.566  1416  1425 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.566  1416  1425 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.566  3066  7510 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 15:42:52.566  3066  3076 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 15:42:52.566  7401  7409 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:42:52.566  1178  2021 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:52.566  1178  2021 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.566  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:42:52.576  1987  2006 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:52.576  1987  2006 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:52.576  7451  7469 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.576  7451  7469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.576  3066  3076 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 15:42:52.576  1426  1802 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:52.576  1426  1802 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.576  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 15:42:52.576  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:42:52.586  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:52.586  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-26 15:42:52.586  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:42:52.586  7401  7419 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 15:42:52.586  1178  1178 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:52.586  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:42:52.586  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.586  1178  1178 D BluetoothTile:  getBluetoothState : 10
08-26 15:42:52.586  1178  1757 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:52.586  1178  1757 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:52.586  7401  7401 I GKI_LINUX: GKI_exit_task 1 done
08-26 15:42:52.586  7401  7401 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 15:42:52.586  7401  7401 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 15:42:52.586  1178  1178 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
,08-26 15:42:52.596  1178  1178 D BluetoothAdapter: 6349901: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:52.596  1017  2754 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:52.596  1017  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:52.596  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:42:52.596  1918  1918 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:52.596  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:52.596  7401  7401 I art     : System.exit called, status: 0
,08-26 15:42:52.596  7401  7401 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 15:42:52.596  1017  1140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:52.596  1987  2163 D BluetoothAdapter: 817837635: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:52.596  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 15:42:52.596  1987  2163 D BluetoothAdapter: 817837635: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:52.596  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.596  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.596  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:52.596  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.596  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.606  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:52.606  1017  1489 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:42:52.606  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.606  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.606  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.606  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:52.616  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:52.626  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:52.626  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.626  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 15:42:52.636  1017  1140 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:42:52.636  1017  1140 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:42:52.636  1017  1140 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-26 15:42:52.636  1017  1140 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 15:42:52.636  1017  1140 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 15:42:52.636  1017  1140 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 15:42:52.636  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.636  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.636  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.636  1017  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.646  7540  7540 E Zygote  : MountEmulatedStorage(),
08-26 15:42:52.646  7540  7540 E Zygote  : v2
08-26 15:42:52.646  7540  7540 I libpersona: KNOX_SDCARD checking this for 1002
,08-26 15:42:52.646  7540  7540 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:52.646  1017  1140 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7540 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 15:42:52.656  7540  7540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 15:42:52.656  7540  7540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:52.656  7540  7540 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:52.676  7540  7540 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:52.676  7540  7540 D ActivityThread: Added TimaKeyStore provider,
,08-26 15:42:52.686  7540  7540 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 15:42:52.686  7540  7540 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:52.706  7540  7540 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 15:42:52.736  7540  7540 D BtSettings.ProfileConfig: Adding GattService
,08-26 15:42:52.736  7540  7540 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 15:42:52.736  7540  7540 D BtSettings.ProfileConfig: Adding A2dpService
08-26 15:42:52.736  7540  7540 D BtSettings.ProfileConfig: Adding HidService
08-26 15:42:52.736  7540  7540 D BtSettings.ProfileConfig: Adding HealthService
,08-26 15:42:52.736  7540  7540 D BtSettings.ProfileConfig: Adding PanService
08-26 15:42:52.736  7540  7540 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-26 15:42:52.746  7540  7540 D BtSettings.ProfileConfig: Adding SapService
08-26 15:42:52.746  7540  7540 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 15:42:52.746  7540  7540 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 15:42:52.746  7540  7540 D BtSettings.ProfileConfig: Adding SapClientService
08-26 15:42:52.746  7540  7540 D BtSettings.ProfileConfig: Adding HidDevService
08-26 15:42:52.746  7540  7540 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 15:42:52.746  1017  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 15:42:52.746  1017  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.746  1017  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.746  1017  1475 D SettingsProvider: selectionArgs: false
08-26 15:42:52.746  1017  1475 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.746  1017  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.746  1017  1475 D SettingsProvider: ret = -1
,08-26 15:42:52.746  1017  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-26 15:42:52.746  1017  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.746  1017  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.746  1017  1476 D SettingsProvider: selectionArgs: false
,08-26 15:42:52.746  1017  1476 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.746  1017  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:42:52.746  1017  1476 D SettingsProvider: ret = -1
,08-26 15:42:52.746  1017  1347 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:52.746  1017  1347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.746  1017  1347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.746  1017  1347 D SettingsProvider: selectionArgs: false
08-26 15:42:52.746  1017  1347 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.746  1017  1347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.746  1017  1347 D SettingsProvider: ret = -1
,08-26 15:42:52.746  1017  4967 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 15:42:52.746  1017  4967 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.746  1017  4967 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.746  1017  4967 D SettingsProvider: selectionArgs: false
08-26 15:42:52.746  1017  4967 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.746  1017  4967 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.746  1017  4967 D SettingsProvider: ret = -1
,08-26 15:42:52.746  1017  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 15:42:52.746  1017  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:52.756  1017  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1477 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1477 D SettingsProvider: selectionArgs: 1002
,08-26 15:42:52.756  1017  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.756  1017  1477 D SettingsProvider: ret = -1
,08-26 15:42:52.756  1017  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-26 15:42:52.756  1017  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.756  1017  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1495 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1495 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.756  1017  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.756  1017  1495 D SettingsProvider: ret = -1
08-26 15:42:52.756  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.756  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:52.756  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1029 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1029 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.756  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:42:52.756  1017  1029 D SettingsProvider: ret = -1
,08-26 15:42:52.756  1017  1488 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 15:42:52.756  1017  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.756  1017  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1488 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1488 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.756  1017  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:42:52.756  1017  1488 D SettingsProvider: ret = -1
08-26 15:42:52.756  1017  1140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:52.756  1017  1140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.756  1017  1140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1140 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1140 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.756  1017  1140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:42:52.756  1017  1140 D SettingsProvider: ret = -1
08-26 15:42:52.756  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:52.756  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.756  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1030 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1030 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.756  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.756  1017  1030 D SettingsProvider: ret = -1
,08-26 15:42:52.756  1017  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 15:42:52.756  1017  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:52.756  1017  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1489 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1489 D SettingsProvider: selectionArgs: 1002,
08-26 15:42:52.756  1017  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.756  1017  1489 D SettingsProvider: ret = -1
08-26 15:42:52.756  1017  1337 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 15:42:52.756  1017  1337 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:52.756  1017  1337 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:52.756  1017  1337 D SettingsProvider: selectionArgs: false
08-26 15:42:52.756  1017  1337 D SettingsProvider: selectionArgs: 1002
08-26 15:42:52.756  1017  1337 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:52.756  1017  1337 D SettingsProvider: ret = -1
,08-26 15:42:52.766  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:52.766  1017  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:52.766  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.776  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.776  1017  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.776  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:52.786  1987  7557 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 15:42:52.786  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:52.936  1017  1347 I art     : Explicit concurrent mark sweep GC freed 70721(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.372ms total 157.955ms
,08-26 15:42:52.936  1017  2754 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:52.936  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.946  1017  2754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.946  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:52.946   288   288 E SMD     : DCD OFF
,08-26 15:42:52.956  1987  7557 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 15:42:53.406  1017  1049 I PowerManagerService: [PWL] Off : 75s ago,
,08-26 15:42:53.406  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-26 15:42:53.406  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-26 15:42:53.406  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=13386)
,08-26 15:42:54.216  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:54.216  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:54.346  1017  1302 E Watchdog: !@Sync 4
,08-26 15:42:54.966   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:55.956   288   288 E SMD     : DCD OFF
,08-26 15:42:55.966   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:56.966   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:57.216  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:42:57.216  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2394b6be added. We now have 6 listener(s)
,08-26 15:42:57.216  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 15:42:57.216  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:42:57.216  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af3e31f added. We now have 7 listener(s)
08-26 15:42:57.216  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:57.216  6792  6845 I System.out: IsBluetoothEnabled
08-26 15:42:57.216  6792  6845 D BluetoothAdapter: disable()
,08-26 15:42:57.226  1017  1475 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 15:42:57.226  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:57.226  6792  6845 D BluetoothAdapter: enable()
,08-26 15:42:57.226  1017  1489 W ActivityManager: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:42:57.226  1017  1489 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 15:42:57.226  1017  1489 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:57.226  1017  1489 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:42:57.226  1017  1489 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 15:42:57.226  1017  1489 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 15:42:57.226  1017  1489 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 15:42:57.226  1017  1489 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:57.226  1017  1489 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:57.226  1017  1489 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:57.246  1017  1489 D SettingsProvider: name = bluetooth_on
,08-26 15:42:57.246  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:42:57.246  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:42:57.256  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 15:42:57.256  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.276  7540  7540 D BluetoothAdapterState: make
,08-26 15:42:57.286  7540  7540 I bluedroid: init
,08-26 15:42:57.286  7540  7563 I BluetoothAdapterState: Entering OffState
,08-26 15:42:57.286  7540  7540 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 15:42:57.286  7540  7540 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 15:42:57.286  7540  7540 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 15:42:57.286  7540  7540 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 15:42:57.296  7540  7540 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-26 15:42:57.296  7540  7540 I bluedroid: get_profile_interface socket
,08-26 15:42:57.296  7540  7540 I bluedroid: get_profile_interface map_client
,08-26 15:42:57.296  7540  7540 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 15:42:57.296  7540  7566 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 15:42:57.306  7540  7540 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:57.306  1017  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:42:57.306  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.306  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.306  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.306  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.306  7540  7548 I bluedroid: config_hci_snoop_log
,08-26 15:42:57.306  7540  7566 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-26 15:42:57.306  7540  7566 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:42:57.306  7540  7566 I bluedroid: getModelRssiValues
08-26 15:42:57.306  7540  7566 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:42:57.306  7540  7566 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:42:57.306  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 15:42:57.316  7540  7566 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 15:42:57.316  1017  1017 D SettingsProvider: name = bluetooth_name
,08-26 15:42:57.316  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-26 15:42:57.316  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 15:42:57.316  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 15:42:57.316  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.326  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:57.326  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:42:57.326  7540  7540 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-26 15:42:57.326  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 15:42:57.336  7540  7563 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 15:42:57.336  7540  7563 D BluetoothAdapterProperties: Setting state to 11
,08-26 15:42:57.336  7540  7563 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:42:57.336  7540  7563 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:57.336  7540  7563 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 15:42:57.336  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:57.336  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-26 15:42:57.346  7540  7563 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:42:57.346  7540  7563 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 15:42:57.346  1918  1918 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:57.346  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:42:57.346  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:57.346  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-26 15:42:57.356  7540  7563 D BluetoothSecureManager: getInstant: null
08-26 15:42:57.356  7540  7563 D BluetoothSecureManager: calling getMethod for getService
08-26 15:42:57.356  7540  7563 D BluetoothSecureManager: calling getService
08-26 15:42:57.356  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:57.356  7540  7563 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2b2c8c61
,08-26 15:42:57.356  1017  1488 D BluetoothSecureManagerService: isSecureModeEnabled,
08-26 15:42:57.356  1017  1488 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-26 15:42:57.356  1017  1140 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:42:57.356  1017  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:57.356  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 15:42:57.356  1017  1140 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:57.356  7540  7563 D BtConfig.SecureMode: isSecureModeOn:false,
08-26 15:42:57.356  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 15:42:57.356  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:42:57.356  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:57.366  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:57.356  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 15:42:57.366  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-26 15:42:57.356  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:42:57.356  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 15:42:57.356  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService,
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService,
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:42:57.366  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 15:42:57.366  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:42:57.366  1017  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.366  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService,
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:57.366  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:42:57.366  7540  7563 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 15:42:57.366  7540  7563 D BluetoothBondStateMachine: make
,08-26 15:42:57.376  7540  7568 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 15:42:57.376  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 15:42:57.376  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 15:42:57.376  7540  7563 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 15:42:57.376  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:57.376  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.376  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 15:42:57.376  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.376  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.376  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.376  7540  7540 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 15:42:57.376  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:42:57.376  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:42:57.376  7540  7563 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 15:42:57.376  7540  7540 D BtGatt.GattService: Received start request. Starting profile...
08-26 15:42:57.376  7540  7540 D BtGatt.GattService: start()
08-26 15:42:57.386  7540  7540 D BtGatt.GattService: start()
08-26 15:42:57.386  7540  7540 I bluedroid: get_profile_interface gatt
,08-26 15:42:57.386  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
08-26 15:42:57.386  7540  7540 D BtGatt.AdvertiseManager: advertise manager created
,08-26 15:42:57.386  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-26 15:42:57.386  1017  2754 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.386  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 15:42:57.386  1017  2754 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 15:42:57.386  1017  2754 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.386  1017  2754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.386  1017  2754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.386  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 15:42:57.386  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:57.386  7540  7563 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:57.386  1017  4967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.386  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.396  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.396  1017  4967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.396  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.396  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-26 15:42:57.396  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:57.396  7540  7563 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:42:57.396  1017  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.396  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.396  7540  7540 D BtGatt.GattService: mStartError = false
,08-26 15:42:57.396  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
08-26 15:42:57.396  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.396  1017  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.396  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.406  7540  7540 D HeadsetService: Received start request. Starting profile...
08-26 15:42:57.406  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 15:42:57.406  7540  7540 D HeadsetService: start()
,08-26 15:42:57.406  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:42:57.406  7540  7563 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:42:57.406  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.406  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 15:42:57.406  7540  7540 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 15:42:57.406  7540  7540 D HeadsetStateMachine: make
,08-26 15:42:57.406  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.406  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.406  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.406  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-26 15:42:57.406  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:42:57.406  7540  7563 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:42:57.416  7540  7540 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 15:42:57.416  1017  4967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.416  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.416  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.416  1017  4967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.416  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.416  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:42:57.416  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:57.426  7540  7563 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:57.426  1017  1140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.426  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.426  1017  1140 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:57.426  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.426  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.426  1017  1476 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 15:42:57.426  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.426  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.426  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:42:57.426  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:57.426  7540  7563 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 15:42:57.426  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.426  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 15:42:57.426  1017  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:57.426  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.426  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.426  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.426  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:57.426  1017  4967 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 15:42:57.426  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:57.436  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.436  1017  4967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.436  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 15:42:57.436  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:57.436  7540  7540 I bluedroid: get_profile_interface handsfree
08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:57.436  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:42:57.436  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:42:57.436  7540  7563 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:42:57.436  7540  7563 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:42:57.436  7540  7563 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 15:42:57.446  7540  7540 I DualScoManager: Instantiating Dual Sco Manager
,08-26 15:42:57.446  7540  7540 I DualScoManager: Set HeadsetServiceHelper
,08-26 15:42:57.446  7540  7540 D BluetoothAtMessage: createCMTIContentObservers
,08-26 15:42:57.446  1017  1489 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 15:42:57.446  1017  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:57.446  1017  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:57.446  1017  1489 D SettingsProvider: selectionArgs: false
,08-26 15:42:57.446  1017  1489 D SettingsProvider: selectionArgs: 1002
08-26 15:42:57.446  1017  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:57.446  1017  1489 D SettingsProvider: ret = -1
,08-26 15:42:57.446  7540  7571 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 15:42:57.456  7540  7540 D HeadsetService: mStartError = false
08-26 15:42:57.456  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
,08-26 15:42:57.456  7540  7571 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 15:42:57.456  7540  7571 D HeadsetStateMachine: map size, before remove : 0
08-26 15:42:57.456  7540  7571 D HeadsetStateMachine: map size, after remove: 0
,08-26 15:42:57.456  7540  7540 D A2dpService: Received start request. Starting profile...
08-26 15:42:57.456  7540  7540 D A2dpService: start()
08-26 15:42:57.456  7540  7540 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 15:42:57.456  7540  7540 I bluedroid: get_profile_interface avrcp
,08-26 15:42:57.466  7540  7540 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:42:57.466  7540  7540 D Avrcp   : Initialize Media Controller
,08-26 15:42:57.466  7540  7540 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 15:42:57.466  7540  7540 E Avrcp   : getActiveSessions
,08-26 15:42:57.466  7540  7540 D Avrcp   : pick active media Controller
08-26 15:42:57.466  7540  7540 D Avrcp   : Get the active Media Controller 
,08-26 15:42:57.486  7540  7540 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 15:42:57.486  7540  7575 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-26 15:42:57.486  7540  7540 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 15:42:57.486  7540  7540 D A2dpStateMachine: make
,08-26 15:42:57.486  7540  7540 I bluedroid: get_profile_interface a2dp
,08-26 15:42:57.486  7540  7577 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 15:42:57.486  7540  7540 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 15:42:57.496  7540  7540 D A2dpService: mStartError = false
08-26 15:42:57.496  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
,08-26 15:42:57.496  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 15:42:57.496  7540  7540 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 15:42:57.496  7540  7540 D HidService: Received start request. Starting profile...
08-26 15:42:57.496  7540  7540 D HidService: start()
08-26 15:42:57.496  7540  7540 I bluedroid: get_profile_interface hidhost
08-26 15:42:57.496  7540  7540 D HidService: setHidService(): set to: null
08-26 15:42:57.496  7540  7540 D HidService: mStartError = false
08-26 15:42:57.496  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
,08-26 15:42:57.496  7540  7540 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 15:42:57.496  7540  7540 D HealthService: Received start request. Starting profile...
08-26 15:42:57.496  7540  7540 D HealthService: start()
,08-26 15:42:57.496  7540  7575 D BluetoothMediaBrowser: no now playing list
08-26 15:42:57.496  7540  7575 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-26 15:42:57.496  7540  7576 D A2dpStateMachine: Enter Disconnected: -2
,08-26 15:42:57.496  7540  7540 I bluedroid: get_profile_interface health
,08-26 15:42:57.496  7540  7540 D HealthService: mStartError = false
08-26 15:42:57.496  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
,08-26 15:42:57.506  7540  7540 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 15:42:57.506  7540  7540 D PanService: Received start request. Starting profile...
,08-26 15:42:57.506  7540  7540 D PanService: start()
08-26 15:42:57.506  7540  7540 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:42:57.506  7540  7540 I bluedroid: get_profile_interface pan
,08-26 15:42:57.506  7540  7540 D PanService: mStartError = false
,08-26 15:42:57.506  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
,08-26 15:42:57.516  7540  7540 D BluetoothMapService: Received start request. Starting profile...
08-26 15:42:57.516  7540  7540 D BluetoothMapService: start()
,08-26 15:42:57.516  7540  7540 D BluetoothMapService: mStartError = false
08-26 15:42:57.516  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
,08-26 15:42:57.516  7540  7540 D HeadsetStateMachine: Try to query the phonestate on bind
08-26 15:42:57.516  1416  1425 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 15:42:57.516  1416  1416 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 15:42:57.516  1416  1416 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:42:57.516  1416  1425 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 15:42:57.516  7540  7540 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 15:42:57.516  7540  7540 D SapService: Received start request. Starting profile...
08-26 15:42:57.516  7540  7540 D SapService: start()
08-26 15:42:57.516  7540  7540 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 15:42:57.516  7540  7540 I bluedroid: get_profile_interface sap
08-26 15:42:57.516  7540  7540 D SapService: mStartError = false
08-26 15:42:57.516  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
08-26 15:42:57.516  7540  7540 D HeadsetStateMachine: Proxy object connected
,08-26 15:42:57.526  7540  7540 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-26 15:42:57.526  7540  7540 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 15:42:57.526  7540  7571 D HeadsetStateMachine: Disconnected process message: 11
08-26 15:42:57.526  7540  7571 D HeadsetStateMachine: Disconnected process message: 18
08-26 15:42:57.526  7540  7540 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 15:42:57.526  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 15:42:57.526  7540  7540 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:42:57.526  7540  7540 D BluetoothA2dp: Proxy object connected
08-26 15:42:57.526  7540  7571 D HeadsetStateMachine: Disconnected process message: 10
08-26 15:42:57.526  7540  7540 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 15:42:57.526  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 15:42:57.526  7540  7571 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 15:42:57.526  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 15:42:57.526  7540  7571 D HeadsetStateMachine: Disconnected process message: 11
,08-26 15:42:57.526  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-26 15:42:57.526  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 15:42:57.526  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:57.526  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:57.546  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 15:42:57.546  7540  7540 E BluetoothAdapterService(501436915): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 15:42:57.556  7540  7563 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 15:42:57.556  7540  7563 I bluedroid: enable
,08-26 15:42:57.556  7540  7563 I bt_hci_bdroid: init
08-26 15:42:57.556  7540  7563 I bt_vendor: bt-vendor : init
08-26 15:42:57.556  7540  7563 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 15:42:57.556  7540  7563 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 15:42:57.556  7540  7563 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 15:42:57.556  7540  7563 D bt_userial_mct: userial_init
08-26 15:42:57.556  7540  7581 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 15:42:57.556  7540  7563 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 15:42:57.556  7540  7563 I bt_vendor: Starting hciattach daemon
08-26 15:42:57.556  7540  7563 I bt_vendor: try to set false
08-26 15:42:57.556  7540  7563 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-26 15:42:57.556  7540  7563 I bt_vendor: Starting hciattach daemon
08-26 15:42:57.556  7540  7563 I bt_vendor: try to set true
,08-26 15:42:57.576  7585  7585 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 15:42:57.616  7591  7591 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 15:42:57.626  7592  7592 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 15:42:57.636  7594  7594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:42:57.646  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 15:42:57.656  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:42:57.666  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 15:42:57.876  1017  3378 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:42:57.886  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-26 15:42:57.896  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 15:42:57.916  7540  7563 I bt_vendor: bluetooth satus is on,
08-26 15:42:57.916  7540  7583 D bt_userial_mct: userial_open(port:0)
08-26 15:42:57.916  7540  7583 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 15:42:57.916  7540  7583 I bt_vendor: Done intiailizing UART,
08-26 15:42:57.916  7540  7583 I bt_vendor: Done intiailizing UART
08-26 15:42:57.916  7540  7583 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 15:42:57.916  7540  7583 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 15:42:57.916  7540  7603 D bt_userial_mct: Entering userial_read_thread(),
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 15:42:57.926  7540  7581 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 15:42:57.966   320   320 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:58.016  7540  7581 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 15:42:58.016  7540  7581 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa416ded1 
,08-26 15:42:58.016  7540  7581 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa416ded1 
,08-26 15:42:58.036  7540  7566 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 15:42:58.036  7540  7566 E bt-btif : Calling BTA_HhEnable
,08-26 15:42:58.036  7540  7566 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 15:42:58.046  7540  7566 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 15:42:58.046  7540  7566 E BluetoothServiceJni: populateRssiValuesNative
,08-26 15:42:58.046  7540  7566 I bluedroid: getModelRssiValues
08-26 15:42:58.046  7540  7566 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:42:58.046  7540  7566 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:42:58.046  1017  1017 D SettingsProvider: name = bluetooth_name
,08-26 15:42:58.046  7540  7566 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 15:42:58.056  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:58.056  7540  7566 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:42:58.056  7540  7566 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:42:58.056  7540  7566 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:42:58.056  7540  7566 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-26 15:42:58.056  7540  7566 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 15:42:58.056  7540  7566 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-26 15:42:58.056  7540  7566 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 15:42:58.066  7540  7566 E bt-btif : btif_sock_init: !vhci_init
08-26 15:42:58.066  7540  7566 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 15:42:58.066  7540  7566 D IOP_DB_BT: db_open: db_open : handle 3027898384l, read 13894 bytes onto local cache
08-26 15:42:58.066  7540  7566 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-26 15:42:58.066  7540  7566 D IOP_DB_BT: db_query: result 1
,08-26 15:42:58.066  7540  7566 I         : iop_db_open: iop_db_open status 0
08-26 15:42:58.066  7540  7566 D bte_conf: Device ID record 1 : primary
08-26 15:42:58.066  7540  7566 D bte_conf:   vendorId            = 0075
08-26 15:42:58.066  7540  7566 D bte_conf:   vendorIdSource      = 0001
08-26 15:42:58.066  7540  7566 D bte_conf:   product             = 0100
08-26 15:42:58.066  7540  7566 D bte_conf:   version             = 0200
08-26 15:42:58.066  7540  7566 D bte_conf:   clientExecutableURL = 
08-26 15:42:58.066  7540  7566 D bte_conf:   serviceDescription  = 
08-26 15:42:58.066  7540  7566 D bte_conf:   documentationURL    = 
08-26 15:42:58.066  7540  7566 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 15:42:58.066  7540  7603 E bt_mct  : hci lib postload completed
,08-26 15:42:58.066  7540  7563 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 15:42:58.066  7540  7563 D BluetoothAdapterProperties: ScanMode =  20
,08-26 15:42:58.066  7540  7563 D BluetoothAdapterProperties: State =  11
,08-26 15:42:58.066  7540  7566 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 15:42:58.066  1017  2754 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:42:58.066  7540  7563 D BluetoothAdapterProperties: Setting state to 12
,08-26 15:42:58.076  7540  7563 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 15:42:58.076  7540  7566 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:42:58.076  7540  7566 D BluetoothAdapterProperties: Scan Mode:21
,08-26 15:42:58.076  7540  7566 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:42:58.076  1017  1347 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 15:42:58.076  1017  1347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:58.076  1017  1347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:58.076  1017  1347 D SettingsProvider: selectionArgs: false
08-26 15:42:58.076  1017  1347 D SettingsProvider: selectionArgs: 1002
08-26 15:42:58.076  1017  1347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:58.076  1017  1347 D SettingsProvider: ret = -1
,08-26 15:42:58.076  7540  7563 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:58.076  7540  7563 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 15:42:58.086  1017  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:58.086  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.086  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.086  1017  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.086  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:58.086  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:58.096  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:58.096  7540  7563 D BluetoothAdapterService: Autoconnection is available 
08-26 15:42:58.096  7540  7563 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 15:42:58.096  7540  7563 D BluetoothAdapterService: starting service from this receiver
,08-26 15:42:58.096  1017  1337 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:58.096  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.096  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.096  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:58.096  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.106  3066  7510 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:42:58.106  3066  7510 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:58.106  7540  7563 I BluetoothAdapterState: Entering On State from state = 11
,08-26 15:42:58.106  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 15:42:58.106  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.106  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.116  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.116  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.116  7540  7548 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:42:58.116  3066  3066 D BluetoothA2dp: Proxy object connected
,08-26 15:42:58.116  3066  3066 D A2dpProfile: Bluetooth service connected
,08-26 15:42:58.116  1416  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 15:42:58.116  7540  7540 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 15:42:58.116  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:42:58.116  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:58.116  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.116  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:58.116  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.126  1416  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:42:58.126  6792  6803 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:58.126  6792  6803 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:58.126  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:58.126  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:42:58.126  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:42:58.126  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:42:58.126  3066  3074 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 15:42:58.126  3066  3074 D Bluetoothsap: Binding service...
,08-26 15:42:58.126  3066  3074 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 15:42:58.126  7540  7540 I BluetoothPbapService: Handler(): got msg=1
,08-26 15:42:58.136  1017  1495 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:42:58.136  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 15:42:58.136  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.136  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.136  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.136  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.136  3066  3074 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 15:42:58.136  3066  3076 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:58.136  3066  3076 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:58.136  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:58.136  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:58.136  1017  1046 D BluetoothPan: Binding service...
,08-26 15:42:58.146  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:42:58.146  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 15:42:58.146  3066  3066 D SapProfile: Bluetooth service connected
08-26 15:42:58.146  3066  3066 D Bluetoothsap: getConnectedDevices()
,08-26 15:42:58.146  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.146  7540  7607 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 15:42:58.146  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:42:58.146  1416  1425 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:58.146  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:42:58.146  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:42:58.146  7540  7607 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:42:58.146  7540  7607 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:42:58.146  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.146  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:58.146  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.156  7540  7607 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-26 15:42:58.156  7540  7607 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:42:58.156  7540  7607 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:42:58.156  7540  7607 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2836a035
08-26 15:42:58.156  7540  7607 D BluetoothSocket: channel: 19
08-26 15:42:58.156  7540  7607 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 15:42:58.156  1416  1425 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:42:58.156  1439  1448 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:42:58.156  1439  1448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:58.156  1416  3290 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:42:58.156  1416  3290 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:58.156  3066  3074 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:42:58.156  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 15:42:58.156  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.156  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.156  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.156  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.166  3066  3066 D BluetoothMap: Proxy object connected
,08-26 15:42:58.166  3066  7510 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 15:42:58.166  3066  3066 D MapProfile: Bluetooth service connected
,08-26 15:42:58.166  3066  3066 D BluetoothMap: getConnectedDevices()
,08-26 15:42:58.166  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 15:42:58.166  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.166  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.166  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.166  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.166  7540  7550 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:42:58.166  7540  7550 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:58.166  1178  5011 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:58.166  3066  3066 D BluetoothInputDevice: Proxy object connected
08-26 15:42:58.166  3066  3066 D HidProfile: Bluetooth service connected
,08-26 15:42:58.166  1178  5011 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:42:58.166  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:42:58.166  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:58.166  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:42:58.166  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:42:58.166  1017  1017 D BluetoothA2dp: Proxy object connected
,08-26 15:42:58.176  1416  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:58.176  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
08-26 15:42:58.176  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:58.176  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.176  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.176  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.176  1416  1437 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:42:58.176  3066  3076 D BluetoothPan: Binding service...
,08-26 15:42:58.176  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:42:58.176  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.176  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.176  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.176  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.176  3066  3066 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:42:58.176  3066  3066 D PanProfile: Bluetooth service connected
08-26 15:42:58.176  3066  3074 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:58.176  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:42:58.176  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:58.176  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.176  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.176  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.176  3066  3074 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:42:58.176  1987  6762 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:58.176  1987  6762 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:58.186  7451  7460 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:58.186  7451  7460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:58.186  3066  3076 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 15:42:58.186  3066  3066 D HeadsetProfile: Bluetooth service connected
,08-26 15:42:58.186  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 15:42:58.186  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.186  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.186  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.186  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.186  1439  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:42:58.186  3066  3066 D BluetoothPbap: Proxy object connected
08-26 15:42:58.186  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:42:58.186  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:42:58.186  3066  3066 D PbapServerProfile: Bluetooth service connected
08-26 15:42:58.186  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.186  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.186  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.186  1439  1449 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:42:58.186  1426  1802 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:42:58.186  1426  1802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:42:58.186  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 15:42:58.186  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:42:58.196  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:58.196  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-26 15:42:58.196  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:42:58.196  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:42:58.196  1416  1416 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2a321628, true
,08-26 15:42:58.196  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:42:58.206  1416  1416 D BluetoothHeadset: registerMessageListener
08-26 15:42:58.206  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-26 15:42:58.206  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:58.206  1918  1918 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:58.206  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:58.206  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:58.206  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:58.206  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:58.206  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-26 15:42:58.206  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 15:42:58.206  7540  7550 D HeadsetService: registerMessageListener
08-26 15:42:58.216  7540  7550 D HeadsetService: registerMessageListener
,08-26 15:42:58.216  7540  7571 D HeadsetStateMachine: Disconnected process message: 70
08-26 15:42:58.216  7540  7571 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@22108cca
,08-26 15:42:58.216  1017  1347 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:42:58.216  1416  1416 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-26 15:42:58.216  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-26 15:42:58.216  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.216  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:58.216  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:58.216  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:42:58.216  1416  1416 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:42:58.216  7540  7610 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-26 15:42:58.216  3066  3066 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 15:42:58.216  3066  3066 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 15:42:58.216  3066  3066 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 15:42:58.216  3066  3066 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 15:42:58.226  1416  1416 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 15:42:58.226  1416  1416 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 15:42:58.226  1416  1416 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 15:42:58.226  1178  1757 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:58.226  7540  7610 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:42:58.226  7540  7610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:42:58.226  7540  7610 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-26 15:42:58.226  7540  7610 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:42:58.226  7540  7610 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:42:58.236  7540  7610 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a2dae3b
,08-26 15:42:58.236  7540  7610 D BluetoothSocket: channel: 5
,08-26 15:42:58.236  7540  7571 D HeadsetStateMachine: Disconnected process message: 9
,08-26 15:42:58.236  7540  7571 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 15:42:58.236  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:58.236  1017  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:42:58.236  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.246   283   702 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 15:42:58.246   283   702 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 15:42:58.246  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.246  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.246  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-26 15:42:58.246   283   702 V voice   : voice_set_parameters: exit with code(-2)
,08-26 15:42:58.246   283   702 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 15:42:58.246   283   702 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 15:42:58.246   283   702 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 15:42:58.246   283   702 V audio_hw_primary: adev_set_parameters: exit
08-26 15:42:58.246  7540  7571 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 15:42:58.256  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:58.256  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:58.256  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:58.256  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:58.256  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:58.266  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:58.266  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:42:58.266  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@205566c added. We now have 8 listener(s)
08-26 15:42:58.266  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:58.266  7540  7540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
08-26 15:42:58.266  7540  7540 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:42:58.266  1017  1140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:58.266  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.266  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.266  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.266  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:58.276  1017  1489 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:42:58.276  1017  1489 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:58.276  1017  1489 D SecContentProvider2: mCursor = null
,08-26 15:42:58.276  1017  1489 D WifiService: setWifiEnabled: false pid=6792, uid=10171
,08-26 15:42:58.276  1017  1489 D SettingsProvider: name = wifi_on
,08-26 15:42:58.276  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:58.276  1017  2754 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:42:58.276  1017  2754 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 15:42:58.286  1017  2754 D SecContentProvider2: mCursor = null
,08-26 15:42:58.286  1017  2754 D WifiService: setWifiEnabled: true pid=6792, uid=10171
,08-26 15:42:58.286  1017  2754 W ActivityManager: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:42:58.286  1017  2754 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:42:58.286  1017  2754 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6792, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:58.286  1017  2754 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:42:58.286  1017  2754 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:42:58.286  1017  2754 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:42:58.286  1017  2754 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:42:58.286  1017  2754 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:58.286  1017  2754 D SettingsProvider: name = wifi_on
,08-26 15:42:58.296  1987  1987 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:58.296  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
08-26 15:42:58.296  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:58.296  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 15:42:58.296  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.296  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:58.296  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:58.296  1017  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:42:58.316  1987  7622 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 15:42:58.316  1987  1987 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:58.316  7540  7623 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:42:58.316  7540  7623 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:42:58.316  1017  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:58.326  7540  7623 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-26 15:42:58.326  7540  7623 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:42:58.326  7540  7623 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:42:58.326  7540  7623 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c3ef317
08-26 15:42:58.326  7540  7623 D BluetoothSocket: channel: 12
08-26 15:42:58.326  7540  7623 I BtOppRfcommListener: Accept thread started.
,08-26 15:42:58.326  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.326  1017  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:58.326  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:58.336  1017  1337 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:58.336  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.336  1017  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:58.336  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:58.346  1987  7622 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 15:42:58.626  1017  1044 D Tethering: interfaceAdded wlan0
,08-26 15:42:58.626  1017  1131 E Tethering: No numeric data
,08-26 15:42:58.636  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 15:42:58.636  1017  1131 D Tethering: clearTetheredNotification()
,08-26 15:42:58.636  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:58.636  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:58.636  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 15:42:58.636  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 15:42:58.636  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:42:58.636  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:58.646  1017  1125 V NetworkStats: performPollLocked() took 9ms
,08-26 15:42:58.646  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:58.646  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.646  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.646  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.646  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.646  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:58.646  1017  1131 D Tethering: InitialState.processMessage what=4
08-26 15:42:58.656  1017  1131 E Tethering: No numeric data
08-26 15:42:58.656  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:58.656  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:42:58.656  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:58.656  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 15:42:58.656  1017  1044 D Tethering: interfaceAdded p2p0
08-26 15:42:58.666  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-26 15:42:58.666  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:58.666  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.666  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:58.666  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:58.666  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:58.666  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:58.666  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-26 15:42:58.676  1017  1125 V NetworkStats: performPollLocked() took 8ms
08-26 15:42:58.676  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.676   277   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 15:42:58.676   277   967 D SoftapController: Softap fwReload - Ok
08-26 15:42:58.676  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.676  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.676   277   967 D CommandListener: Setting iface cfg
08-26 15:42:58.676   277   967 D CommandListener: Trying to bring down wlan0
08-26 15:42:58.676   277   967 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:58.686  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant
08-26 15:42:58.696  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 15:42:58.696  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:58.706  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:58.706  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.706  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.706  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.706  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.706  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:58.706  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 15:42:58.706  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:58.706  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:58.706  1178  1178 D HotspotTile: onReceive : 2, 0
08-26 15:42:58.716  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:58.716  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:58.716  1017  3347 D SSRM:n  : SIOP:: AP = 340
,08-26 15:42:58.726  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:58.726  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:58.726  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.726  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.726  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:58.726  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:58.726  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:58.726  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:58.726  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:58.736  1654  1654 I Hs20UtilService: Starting #19
,08-26 15:42:58.736  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:58.746  7631  7631 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-26 15:42:58.746  7631  7631 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 15:42:58.746  7631  7631 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 15:42:58.756  7631  7631 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-26 15:42:58.756   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7631
08-26 15:42:58.756   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 15:42:58.756  7631  7631 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 15:42:58.756  7631  7631 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:58.756  7631  7631 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 15:42:58.756  7631  7631 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 15:42:58.756   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7631
08-26 15:42:58.756   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 15:42:58.826  1017  2062 V SAMP_SPCM_test: CSC File load.. 
,08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application,
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling,
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 15:42:58.836  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 15:42:58.866  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 15:42:58.876  1017  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-26 15:42:58.886  1017  2062 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-26 15:42:58.886  1017  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:58.886  1017  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:58.886  1017  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:58.886  1017  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:58.896  7633  7633 E Zygote  : MountEmulatedStorage()
08-26 15:42:58.896  7633  7633 E Zygote  : v2
08-26 15:42:58.896  7633  7633 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:58.896  7633  7633 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:58.906   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
08-26 15:42:58.906  7633  7633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:58.906  1017  2062 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7633 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:42:58.906  7633  7633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:58.906  7633  7633 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:58.906  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-26 15:42:58.926  7633  7633 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:58.926  7633  7633 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:58.946  7633  7633 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:58.946   288   288 E SMD     : DCD OFF
,08-26 15:42:58.956  7631  7631 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 15:42:58.956  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 15:42:58.966   320   320 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:58.966  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-26 15:42:58.966   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7631
08-26 15:42:58.966   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 15:42:58.966  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 15:42:58.966  7631  7631 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:58.966  7631  7631 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:58.966  7631  7631 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:58.966  7631  7631 E wpa_supplicant: SIM READ ERROR
08-26 15:42:58.966  7631  7631 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:58.966  7631  7631 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:58.966  7631  7631 E wpa_supplicant: SIM READ ERROR
08-26 15:42:58.966  7631  7631 I wpa_supplicant: Blacklist: Clear (all) 
08-26 15:42:58.976  7631  7631 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:42:58.976  7631  7631 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:58.976  7631  7631 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:58.976  7631  7631 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 15:42:58.976  7631  7631 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:58.976  7631  7631 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 15:42:58.976  7631  7631 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:42:58.976  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.976  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.976  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:58.986  1017  2062 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72,
,08-26 15:42:59.066  7631  7631 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 15:42:59.356  7631  7631 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 15:42:59.356  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 15:42:59.366  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-26 15:42:59.376   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7631
08-26 15:42:59.376   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-26 15:42:59.376  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-26 15:42:59.376  7631  7631 I wpa_supplicant: ssSupport state is = 1
,08-26 15:42:59.376  7631  7631 I wpa_supplicant: Ctrl_iface: loading cred from phone,
,08-26 15:42:59.376  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 15:42:59.386  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 15:42:59.386   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7631
08-26 15:42:59.386   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 15:42:59.386  7631  7631 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-26 15:42:59.386  7631  7631 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:59.386  7631  7631 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:59.386  7631  7631 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:59.386  7631  7631 E wpa_supplicant: SIM READ ERROR,
08-26 15:42:59.396  7631  7631 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:42:59.396  7631  7631 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:59.396  7631  7631 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 15:42:59.396  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:59.396  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:59.396  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:59.396  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:59.396  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:59.396  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:59.476  7631  7631 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 15:42:59.476  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 15:42:59.516  7631  7631 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 15:42:59.516  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-26 15:42:59.516  7631  7631 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:42:59.526  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-26 15:42:59.526  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:42:59.526  7631  7631 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-26 15:42:59.526  7631  7631 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 15:42:59.536  7631  7631 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:59.536  7631  7631 E wpa_supplicant: SIM READ ERROR
08-26 15:42:59.536  7631  7631 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:59.556  7631  7631 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 15:42:59.566  7631  7631 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-26 15:42:59.566  1017  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:42:59.566  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:42:59.566  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:59.566  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:59.566  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:59.566  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:59.566  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:59.566  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:59.566  1178  1757 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:59.566  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 15:42:59.566  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:59.576  1178  1178 D HotspotTile: onReceive : 3, 0
,08-26 15:42:59.576  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:59.576  6792  6792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:59.586  6792  6792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:59.586  1017  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:59.586  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:59.586  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:59.586  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:59.586  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:59.586  1017  1128 E WifiConfigStore: Not a HS20
,08-26 15:42:59.586  1017  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 15:42:59.586  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 15:42:59.586  1654  1654 I Hs20UtilService: Starting #20
,08-26 15:42:59.586  1654  1703 I Hs20UtilService: Message received 5011
,08-26 15:42:59.596  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:59.596  6607  6607 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:59.596  6607  6607 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:59.596  6607  6607 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:59.596  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 15:42:59.596  7631  7631 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 15:42:59.596  7631  7631 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 15:42:59.596  7631  7631 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:42:59.596  7631  7631 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 15:42:59.596  7631  7631 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 15:42:59.596  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 15:42:59.596  7631  7631 I wpa_supplicant: First Scan Start
08-26 15:42:59.596  7631  7631 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 15:42:59.596  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-26 15:42:59.606  7010  7010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:59.606  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:42:59.606  1017  1128 I WifiNative-HAL: startHal
08-26 15:42:59.606  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9d68688c
08-26 15:42:59.606  1017  1128 I WifiNative-HAL: Could not start hal
,08-26 15:42:59.606  1017  1128 E WifiNative-wlan0: do suspend true
,08-26 15:42:59.606  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 15:42:59.606  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 15:42:59.606  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 15:42:59.606  1017  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:59.606  1017  1150 I WifiNative-HAL: startHal
08-26 15:42:59.606  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9df149bc
08-26 15:42:59.606  1017  1150 I WifiNative-HAL: Could not start hal
08-26 15:42:59.606  1017  1150 E WifiScanningService: could not start HAL
,08-26 15:42:59.616   277   967 D CommandListener: Setting iface cfg
,08-26 15:42:59.616   277   967 D CommandListener: Trying to bring up p2p0
08-26 15:42:59.616  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-26 15:42:59.616  1017  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:59.616  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 15:42:59.616  1017  1127 D WifiP2pService: P2pEnablingState,
08-26 15:42:59.616  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 15:42:59.616  1017  1127 D WifiP2pService: P2p socket connection successful
08-26 15:42:59.616  1017  1127 D WifiP2pService: P2pEnabledState
,08-26 15:42:59.616  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:42:59.616  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:59.616  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-26 15:42:59.616  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:42:59.616  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:42:59.616  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:59.616  1017  1128 E WifiNative-wlan0: invaild command id : 215
08-26 15:42:59.616  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-26 15:42:59.616  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 15:42:59.616  7631  7631 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-26 15:42:59.616  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 15:42:59.616  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
,08-26 15:42:59.616  7631  7631 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:42:59.616  1017  1047 D WifiDisplayController: disconnect
08-26 15:42:59.616  7631  7631 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 15:42:59.616  1017  1047 D WifiDisplayController: updateConnection
08-26 15:42:59.616  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 15:42:59.616  1017  1128 E WifiStateMachine: Failed to set frequency band 0
08-26 15:42:59.616  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:59.616  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:59.616  1017  1128 D SecContentProvider2: mCursor = null
08-26 15:42:59.626  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 15:42:59.626  1017  4967 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:59.626  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:59.626  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress,
,08-26 15:42:59.626  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-26 15:42:59.636  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 15:42:59.636  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:59.636  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:59.636  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null,
,08-26 15:42:59.636  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:59.636  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:42:59.636  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:59.636  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:59.636  1017  1127 D WifiP2pService: DeviceAddress: 0a:76:28
,08-26 15:42:59.636  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  secondary type: null
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  wps: 0
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  grpcapab: 0
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  devcapab: 0
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  status: 3
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  wfdInfo: null
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-26 15:42:59.636  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-26 15:42:59.636  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:59.646  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:59.646  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 15:42:59.646  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:59.646  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:59.646  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:59.646  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:59.646  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:59.656  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 15:42:59.656  1017  1127 D WifiP2pService: InactiveState
,08-26 15:42:59.656  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-26 15:42:59.656  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:42:59.656  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 15:42:59.656  7631  7631 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:42:59.656  7033  7033 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:59.656  7033  7033 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:59.656  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-26 15:42:59.656  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:42:59.666  7048  7048 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:59.966   320   320 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:42:59.986  1017  1095 V AlarmManager: waitForAlarm result :8,
,08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:00.316  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:00.316  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:00.316  6792  6845 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 15:43:00.326  6792  6845 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 15:43:00.326  6792  6845 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a849de3 Bundle[{}]
,08-26 15:43:00.326  6792  6845 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 15:43:00.326  6792  6845 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 15:43:00.326  6792  6845 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 15:43:00.326  6792  6845 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 15:43:00.326  6792  6845 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 15:43:00.326  6792  6845 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:43:00.336  6792  6845 I System.out: Running OutgoingSocketThread
,08-26 15:43:00.336  6792  7655 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1359)
,08-26 15:43:00.346  6792  7655 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45481
,08-26 15:43:00.346  6792  7655 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 15:43:00.826  7631  7631 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
,08-26 15:43:00.826  7631  7631 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-26 15:43:00.826  7631  7631 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 15:43:00.826  7631  7631 I wpa_supplicant: Trying to associate with  'G700'
,08-26 15:43:00.826  7631  7631 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-26 15:43:00.826  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 15:43:00.836  1017  7652 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 15:43:00.846  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:00.846  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:43:00.936  7631  7631 E wpa_supplicant: Cmd 35605 not handled
,08-26 15:43:00.936  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:00.936  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:00.936  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:43:00.936  7631  7631 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-26 15:43:00.936  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:00.946  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:00.946  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:43:00.946  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-26 15:43:00.946  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 15:43:00.946  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:43:00.946  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-26 15:43:00.946  7631  7631 I wpa_supplicant: Associated with F4.99.3E,
,08-26 15:43:00.946  7631  7631 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 15:43:00.946  7631  7631 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-26 15:43:00.946  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-26 15:43:00.946  1017  1131 E Tethering: No numeric data,
,08-26 15:43:00.946  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 15:43:00.946  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:43:00.956  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:00.956  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:00.956  7631  7631 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 15:43:00.956  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:00.956  7631  7631 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 15:43:00.956  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 15:43:00.956  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:00.956  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:00.956  7631  7631 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-26 15:43:00.956  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 15:43:00.956  7631  7631 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:43:00.956  7631  7631 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
,08-26 15:43:00.956  7631  7631 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 15:43:00.966  1017  1125 V NetworkStats: performPollLocked() took 10ms
,08-26 15:43:00.956  7631  7631 I wpa_supplicant: Blacklist: Clear (temp) 
,08-26 15:43:00.966  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:43:00.956  7631  7631 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 15:43:00.966  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:00.966  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 15:43:00.966  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-26 15:43:00.966  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:00.966  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:00.966  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:43:00.966  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:00.976  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 15:43:00.976  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 15:43:00.986  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 15:43:00.986  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 15:43:00.986  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:43:00.986  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 15:43:00.986  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:43:00.986  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:43:00.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:00.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:00.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:00.986  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:00.996  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:43:00.996  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:00.996  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:43:00.996  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.996  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.996  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:00.996  1654  1654 I Hs20UtilService: Starting #21
08-26 15:43:00.996  1654  1703 I Hs20UtilService: Message received 5007
,08-26 15:43:01.006  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-26 15:43:01.006  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:43:01.006  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:43:01.006  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:43:01.006  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:43:01.006  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:43:01.006  3066  3910 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:43:01.016  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-26 15:43:01.026   277   967 D CommandListener: Setting iface cfg,
,08-26 15:43:01.026  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 15:43:01.026  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:01.026  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:43:01.036  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:01.036  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:43:01.046  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:43:01.046  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:01.046  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.046  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.046  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.046  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:01.046  1017  1128 E WifiNative-wlan0: do suspend false
,08-26 15:43:01.046  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-26 15:43:01.056  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:43:01.056  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:01.056  1017  1128 D SecContentProvider2: mCursor = null
,08-26 15:43:01.266  7658  7658 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 15:43:01.266  7658  7658 I dhcpcd  : version 5.5.6 starting
,08-26 15:43:01.276  7658  7658 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 15:43:01.316  7658  7658 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 15:43:01.316  7658  7658 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 15:43:01.316  7658  7658 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-26 15:43:01.316  7658  7658 I dhcpcd  : bssid match
08-26 15:43:01.316  7658  7658 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-26 15:43:01.336  6792  6845 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1360)
,08-26 15:43:01.336  6792  6845 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1360)
,08-26 15:43:01.336  6792  6845 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1365)
,08-26 15:43:01.336  6792  6845 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 15:43:01.336  6792  6845 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1366)
,08-26 15:43:01.346  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:01.346  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22e435 added. We now have 2 listener(s)
,08-26 15:43:01.346  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 15:43:01.346  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.346  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:01.346  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.346  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@266180ca added. We now have 9 listener(s)
,08-26 15:43:01.346  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:01.346  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:01.356  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.356  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.356  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:01.356  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:01.356  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.356  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:01.356  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d276d58 added. We now have 3 listener(s)
,08-26 15:43:01.356  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a8eb1 added. We now have 10 listener(s)
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:01.366  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:01.366  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:01.366  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:01.366  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22e435 removed from the list
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@266180ca removed from the list
08-26 15:43:01.366  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.366  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.366  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@266180ca not in the list
08-26 15:43:01.366  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72a8eb1 removed from the list
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:01.366  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d276d58 removed from the list
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127edf96 added. We now have 2 listener(s)
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.366  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c291717 added. We now have 9 listener(s)
08-26 15:43:01.366  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:43:01.366  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:01.376  7658  7658 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.376  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.376  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:01.376  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:01.376  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:01.376  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@132864ed added. We now have 3 listener(s)
,08-26 15:43:01.376  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 15:43:01.376  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 15:43:01.386  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.386  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.386  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:01.386  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.386  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33415f22 added. We now have 10 listener(s)
08-26 15:43:01.386  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:01.386  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:01.386  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:01.386  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:01.386  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:01.386  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:01.386  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:01.386  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:01.386  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:01.386  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:43:01.386  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:43:01.396  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:01.396  7540  7550 D BtGatt.GattService: registerClient() - UUID=a5d7d74c-54c2-45f9-a972-8cc6404651f0
,08-26 15:43:01.436  7540  7566 D BtGatt.GattService: onClientRegistered() - UUID=a5d7d74c-54c2-45f9-a972-8cc6404651f0, clientIf=6
,08-26 15:43:01.436  6792  6803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 15:43:01.436  7540  7548 D BtGatt.GattService: start scan with filters
08-26 15:43:01.436  7540  7570 D BtGatt.ScanManager: handling starting scan
08-26 15:43:01.436  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:43:01.436  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 15:43:01.436  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:01.436  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:43:01.446  7540  7570 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1de351f3
,08-26 15:43:01.446  7540  7566 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:43:01.446  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.446  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:01.446  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:43:01.446  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:01.446  7540  7570 D BtGatt.ScanManager: allow scan with filters
08-26 15:43:01.446  7540  7570 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:43:01.446  7540  7570 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 15:43:01.446  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:01.456  7540  7566 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:43:01.456  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.456  7540  7570 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:01.456  7540  7570 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:01.456  7540  7566 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:43:01.456  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.456  6792  6845 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 15:43:01.456  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:01.466  7540  7566 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 15:43:01.466  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:43:01.466  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.466  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:01.466  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:43:01.466  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:43:01.466  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:01.466  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:01.466  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:01.466  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 15:43:01.466  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.466  7540  7608 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:43:01.466  7540  7570 D BtGatt.ScanManager: filter size is 1
,08-26 15:43:01.476  7540  7550 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:43:01.476  7540  7570 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 15:43:01.476  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-26 15:43:01.476  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:01.476  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:01.476  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 15:43:01.476  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:01.476  7540  7566 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 15:43:01.476  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.476  7540  7570 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:43:01.476  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:01.476  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:01.476  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:01.486  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:43:01.486  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:01.486  7540  7566 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 15:43:01.486  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.486  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:01.486  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:01.486  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:01.486  7540  7570 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:43:01.486  7540  7566 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:43:01.486  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.496  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:01.496  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:01.496  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:01.496  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:01.496  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:01.496  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:01.496  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:01.496  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@127edf96 removed from the list
08-26 15:43:01.496  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:01.496  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c291717 removed from the list
,08-26 15:43:01.496  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:01.496  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:01.496  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:01.496  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:01.496  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:01.496  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:01.496  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:01.506  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c291717 not in the list
08-26 15:43:01.506  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.506  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:01.506  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:01.506  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:01.506  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.506  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33415f22 removed from the list
,08-26 15:43:01.506  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:01.506  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.506  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.506  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
,08-26 15:43:01.506  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@132864ed removed from the list
,08-26 15:43:01.506  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:01.506  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba4b6e added. We now have 2 listener(s)
,08-26 15:43:01.516  7658  7658 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-26 15:43:01.516  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.516  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.516  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:01.516  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.516  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3161d20f added. We now have 9 listener(s)
08-26 15:43:01.516  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:01.516  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:01.536  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.536  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.546  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:01.546  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:01.546  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:01.546  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38d644a5 added. We now have 3 listener(s)
,08-26 15:43:01.546  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:01.546  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:01.546  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.546  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-26 15:43:01.546  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:01.546  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.546  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c3b07a added. We now have 10 listener(s),
08-26 15:43:01.546  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:01.546  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:01.546  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-26 15:43:01.546  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:01.546  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:01.546  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-26 15:43:01.546  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:01.556  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-26 15:43:01.566  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:01.566  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:43:01.566  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:01.566  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:43:01.566  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:01.576  7540  7554 D BtGatt.GattService: registerClient() - UUID=0e60825f-fae4-4536-90bf-85d9a4ead6cc
,08-26 15:43:01.626  7540  7566 D BtGatt.GattService: onClientRegistered() - UUID=0e60825f-fae4-4536-90bf-85d9a4ead6cc, clientIf=6
,08-26 15:43:01.626  6792  6800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 15:43:01.626  7540  7609 D BtGatt.GattService: start scan with filters
,08-26 15:43:01.626  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:43:01.626  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:43:01.626  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:01.626  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:43:01.626  7540  7570 D BtGatt.ScanManager: handling starting scan,
,08-26 15:43:01.626  7540  7566 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-26 15:43:01.626  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.626  7540  7570 D BtGatt.ScanManager: allow scan with filters
08-26 15:43:01.626  7540  7570 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:43:01.626  7540  7570 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-26 15:43:01.626  7540  7566 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:43:01.626  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.626  7540  7570 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:01.626  7540  7570 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:01.626  7540  7566 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 15:43:01.626  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.636  7540  7566 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:43:01.636  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.646  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:01.646  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:01.646  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:43:01.646  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:01.656  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:01.656  6792  6845 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 15:43:01.656  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:01.656  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:01.656  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:01.656  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:01.656  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.656  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:01.656  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:01.656  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ba4b6e removed from the list
08-26 15:43:01.656  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.656  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3161d20f removed from the list
08-26 15:43:01.656  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:01.656  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:01.656  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.656  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 15:43:01.656  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.656  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:01.666  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3161d20f not in the list
08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:43:01.666  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:01.666  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:01.666  7540  7554 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:43:01.666  7540  7609 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 15:43:01.666  7540  7570 D BtGatt.ScanManager: filter size is 1
08-26 15:43:01.666  7540  7570 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 15:43:01.666  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:01.666  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:01.666  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:01.666  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:01.666  7540  7566 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:43:01.666  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.666  7540  7570 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:43:01.666  7540  7566 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:43:01.666  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.666  7540  7570 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:43:01.666  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:01.676  7540  7566 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:01.676  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:43:01.676  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:01.676  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:01.676  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:01.676  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.676  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c3b07a removed from the list
08-26 15:43:01.676  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:01.676  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.676  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:01.676  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:01.676  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38d644a5 removed from the list
08-26 15:43:01.676  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:01.676  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:01.676  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:01.676  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ecc5a46 added. We now have 2 listener(s),
,08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:01.676  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.676  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18a7f407 added. We now have 9 listener(s)
08-26 15:43:01.676  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:01.676  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:01.686  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.696  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.706  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:01.706  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-26 15:43:01.706  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:01.706  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f9635d added. We now have 3 listener(s)
,08-26 15:43:01.706  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:01.706  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.706  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1463d4d2 added. We now have 10 listener(s)
08-26 15:43:01.706  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:01.706  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:01.706  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 15:43:01.706  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:01.706  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:01.706  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:01.716  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.716  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:01.726  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:01.726  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:01.726  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:01.726  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:43:01.726  6792  6845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:01.736  7540  7608 D BtGatt.GattService: registerClient() - UUID=141b37ac-a6d1-40b8-8d6a-07ca33896309
,08-26 15:43:01.776  7540  7566 D BtGatt.GattService: onClientRegistered() - UUID=141b37ac-a6d1-40b8-8d6a-07ca33896309, clientIf=6
,08-26 15:43:01.776  6792  6803 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:43:01.776  7540  7609 D BtGatt.GattService: start scan with filters
,08-26 15:43:01.776  7540  7570 D BtGatt.ScanManager: handling starting scan
,08-26 15:43:01.776  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:43:01.776  7540  7566 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:43:01.776  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.776  7540  7570 D BtGatt.ScanManager: allow scan with filters
,08-26 15:43:01.786  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:43:01.786  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:01.786  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:43:01.786  7540  7570 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:43:01.786  7540  7570 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 15:43:01.786  7540  7566 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:43:01.786  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.786  7540  7570 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:01.786  7540  7570 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:01.786  7540  7566 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:43:01.786  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.786  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:01.786  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:43:01.786  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:01.786  7540  7566 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 15:43:01.796  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.796  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:01.806  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:01.806  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:01.806  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:01.806  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:01.806  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:01.806  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:01.806  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:01.806  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ecc5a46 removed from the list
08-26 15:43:01.806  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:01.806  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18a7f407 removed from the list
08-26 15:43:01.806  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:01.806  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:01.806  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
08-26 15:43:01.806  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 15:43:01.806  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:01.806  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.816  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18a7f407 not in the list
,08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 15:43:01.816  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:01.816  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:01.816  7540  7548 D BtGatt.GattService: stopScan() - queue size =1,
,08-26 15:43:01.816  7540  7554 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:43:01.816  7540  7570 D BtGatt.ScanManager: filter size is 1
08-26 15:43:01.816  7540  7570 D BtGatt.ScanManager: delete FilterIndex - 5
08-26 15:43:01.816  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:01.816  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 15:43:01.816  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 15:43:01.816  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:43:01.816  7540  7566 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:43:01.816  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.816  7540  7570 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:43:01.816  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 15:43:01.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:01.826  7540  7566 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:43:01.826  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:01.826  7540  7570 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
08-26 15:43:01.826  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-26 15:43:01.826  6792  6792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:01.826  7540  7566 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:43:01.826  7540  7566 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:01.826  6792  6792 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:01.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:01.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:01.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.826  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1463d4d2 removed from the list
,08-26 15:43:01.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:01.826  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:01.826  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f9635d removed from the list
08-26 15:43:01.826  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:01.826  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30866c1e added. We now have 2 listener(s)
,08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:01.826  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.826  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b615cff added. We now have 9 listener(s),
08-26 15:43:01.826  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:01.826  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:01.836  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.836  6792  6845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.836  6792  6845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:01.836  6792  6845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:01.836  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:01.836  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@381aa115 added. We now have 3 listener(s)
,08-26 15:43:01.836  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.846  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 15:43:01.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:01.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:01.846  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:01.846  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ba92c2a added. We now have 10 listener(s)
08-26 15:43:01.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:01.846  6792  6845 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:01.846  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:01.846  6792  6845 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:01.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:01.846  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:01.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:01.846  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30866c1e removed from the list
08-26 15:43:01.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:01.846  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b615cff removed from the list
08-26 15:43:01.846  6792  6845 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:01.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.846  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.846  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:01.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:01.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:01.846  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:01.846  6792  6845 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b615cff not in the list
08-26 15:43:01.856  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:01.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:01.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:01.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:01.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:01.856  6792  6845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ba92c2a removed from the list
08-26 15:43:01.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:01.856  6792  6845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:01.856  6792  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:01.856  6792  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:01.856  6792  6845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@381aa115 removed from the list
08-26 15:43:01.856  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 15:43:01.856  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 15:43:01.856  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 15:43:01.856  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:01.856  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 15:43:01.856  6792  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:01.866  1017  1128 E WifiNative-wlan0: do suspend true
08-26 15:43:01.866  6792  7689 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1373, name: My test thread name)
08-26 15:43:01.866  6792  7689 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1373, thread name: My test thread name)
08-26 15:43:01.866  6792  7689 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1373, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:01.866  6792  7690 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1375, name: My test thread name)
,08-26 15:43:01.866  6792  7690 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1375, thread name: My test thread name)
08-26 15:43:01.866  6792  7690 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1375, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:01.866  6792  6845 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-26 15:43:01.866  6792  6845 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 15:43:01.866  6792  6845 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 15:43:01.866  6792  6845 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 15:43:01.866  6792  6845 D com.test.thalitest.ThaliTestRunner: Total duration: 23326 ms
,08-26 15:43:01.876  6792  6845 I jxcore-log: *Native tests were executed*
08-26 15:43:01.876  6792  6845 I jxcore-log: 
,08-26 15:43:01.876  6792  6845 I jxcore-log: Total number of executed tests:  80
08-26 15:43:01.876  6792  6845 I jxcore-log: 
,08-26 15:43:01.876  6792  6845 I jxcore-log: Number of passed tests:  80
08-26 15:43:01.876  6792  6845 I jxcore-log: 
,08-26 15:43:01.876  6792  6845 I jxcore-log: Number of failed tests:  0
08-26 15:43:01.876  6792  6845 I jxcore-log: 
08-26 15:43:01.876  6792  6845 I jxcore-log: Number of ignored tests:  0
08-26 15:43:01.876  6792  6845 I jxcore-log: 
,08-26 15:43:01.876  6792  6845 I jxcore-log: Total duration:  23326
08-26 15:43:01.876  6792  6845 I jxcore-log: 
,08-26 15:43:01.876  6792  6845 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 15:43:01.876  6792  6845 I jxcore-log: 
,08-26 15:43:01.886  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:01.886  6792  6845 I jxcore-log: 
08-26 15:43:01.886  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:01.886  6792  6845 I jxcore-log: 
08-26 15:43:01.886  6792  6792 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 15:43:01.886  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:01.886  6792  6845 I jxcore-log: 
08-26 15:43:01.886  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
08-26 15:43:01.886  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:01.886  6792  6845 I jxcore-log: 
08-26 15:43:01.886  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 15:43:01.886  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:01.886  6792  6845 I jxcore-log: 
08-26 15:43:01.886  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:01.886  6792  6845 I jxcore-log: 
08-26 15:43:01.896  1017  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
08-26 15:43:01.896  1017  1128 E WifiStateMachine: VerifyingLinkState enter
,08-26 15:43:01.896  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:01.896  6792  6845 I jxcore-log: 
08-26 15:43:01.896  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:01.896  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:01.896  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.896  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.896  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.896  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.896  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,08-26 15:43:01.896  6792  6845 I jxcore-log: 
08-26 15:43:01.896  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-26 15:43:01.896  6792  6845 I jxcore-log: 
,08-26 15:43:01.896  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:01.896  6792  6845 I jxcore-log: 
,08-26 15:43:01.896  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:01.896  6792  6845 I jxcore-log: 
,08-26 15:43:01.896  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-26 15:43:01.896  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:01.896  6792  6845 I jxcore-log: 
,08-26 15:43:01.906  1017  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 15:43:01.906  1017  1130 D ConnectivityService: Adding iface wlan0 to network 504
08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
,08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
,08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-26 15:43:01.906  6792  6845 I jxcore-log: 
,08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
,08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
,08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-26 15:43:01.906  6792  6845 I jxcore-log: 
08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: ,
08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
,08-26 15:43:01.906  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:01.906  6792  6845 I jxcore-log: 
,08-26 15:43:01.916  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-26 15:43:01.916  6792  6845 I jxcore-log: 
,08-26 15:43:01.916  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:01.916  6792  6845 I jxcore-log: 
08-26 15:43:01.916  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
,08-26 15:43:01.916  6792  6845 I jxcore-log: 
08-26 15:43:01.916  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:01.916  6792  6845 I jxcore-log: 
08-26 15:43:01.916  1017  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-26 15:43:01.916  1017  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:01.916  1017  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:01.916  1017  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 15:43:01.916  1017  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 15:43:01.926  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:01.926  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:01.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.926  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:01.926  1017  1347 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:01.926  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:01.926  1017  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-26 15:43:01.936  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.936  1017  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.936  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:43:01.936  1017  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 15:43:01.936  1017  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-26 15:43:01.936  1654  1654 I Hs20UtilService: Starting #22
,08-26 15:43:01.936  1017  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-26 15:43:01.936  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:43:01.936  1654  1703 I Hs20UtilService: Message received 5007
,08-26 15:43:01.936  1017  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 15:43:01.936  1017  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-26 15:43:01.936  1017  1130 D ConnectivityService: LTETest block dns file not exists
,08-26 15:43:01.936  1017  1130 V NetworkStats: updateIfacesLocked()
08-26 15:43:01.936  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.936  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:01.936  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:01.936  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:01.946  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.946  1017  1130 V NetworkStats: performPollLocked() took 8ms
,08-26 15:43:01.946  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-26 15:43:01.946  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:43:01.946  3066  3066 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 15:43:01.946  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.946  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:01.956  1017  1130 E ConnectivityService: updateNetworkInfo()
08-26 15:43:01.956  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:01.956  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.956  1017  1130 V NetworkStats: updateIfacesLocked()
08-26 15:43:01.956  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:43:01.956  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:01.956   288   288 E SMD     : DCD OFF
08-26 15:43:01.956  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:01.956  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:01.956  1017  1130 V NetworkStats: performPollLocked() took 3ms
08-26 15:43:01.956  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:01.956  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:43:01.956  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:01.956  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.956  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.956  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.956  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:01.966  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:43:01.966  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 15:43:01.966  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
08-26 15:43:01.966  1017  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 15:43:01.966  1017  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 15:43:01.976  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.976  1017  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-26 15:43:01.976  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.976  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 15:43:01.976  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:01.976  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:43:01.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:01.976  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:01.976  1017  7656 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:01.976  1017  7656 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 15:43:01.976  1017  7656 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:01.976  1017  7656 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-26 15:43:01.976  1017  7656 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:43:01.976   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:43:01.976   277   961 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-26 15:43:01.986  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 15:43:01.986  1017  1130 D ConnectivityService:    accepting network in place of null
08-26 15:43:01.986  1017  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:01.986  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:01.986  1439  1439 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 15:43:01.986  1439  1439 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:43:01.986  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.986  1017  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.986  1017  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 15:43:01.986  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:43:01.986  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:43:01.986  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:43:01.986  1654  1654 I Hs20UtilService: Starting #23
08-26 15:43:01.986  6792  6792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 15:43:01.986  1654  1703 I Hs20UtilService: Message received 5007
08-26 15:43:01.986  1017  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-26 15:43:01.996  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:01.996  6792  6845 I jxcore-log: 
08-26 15:43:01.996  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:43:01.996  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:43:01.996  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 15:43:01.996  1017  1131 D Tethering: MasterInitialState.processMessage what=3
,08-26 15:43:01.996  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.996  1017  1125 V NetworkStats: updateIfacesLocked()
08-26 15:43:01.996  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:01.996  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:01.996  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:43:01.996  1017  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-26 15:43:01.996  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-26 15:43:01.996  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-26 15:43:01.996  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:01.996  1017  1125 V NetworkStats: performPollLocked() took 4ms
08-26 15:43:01.996  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:43:01.996  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false,
08-26 15:43:01.996  3066  3066 I NearbySettings: MountReceiver.onReceive - Keep current state
08-26 15:43:01.996  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 15:43:02.006  4746  6853 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:43:02.006  1178  1732 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:43:02.006  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-26 15:43:02.006  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:43:02.006  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:43:02.006  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 15:43:02.006  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 15:43:02.006  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 15:43:02.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:02.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:02.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:02.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:02.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:02.016  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 15:43:02.016  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:02.016  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:02.016  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:02.026  1017  1337 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:02.026  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:43:02.026  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:02.026  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:02.026  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:02.026  1654  1654 I Hs20UtilService: Starting #24
,08-26 15:43:02.026  1654  1703 I Hs20UtilService: Message received 5007
08-26 15:43:02.026  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:43:02.026  3066  3066 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 15:43:02.036  1017  1475 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 15:43:02.036  1017  2754 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 15:43:02.036  1017  2754 D SecContentProvider2: mCursor = null
,08-26 15:43:02.036  1017  1477 D SecContentProvider2: uri = 15 selection = getToastGravity
08-26 15:43:02.036  1017  1477 D SecContentProvider2: mCursor = null
,08-26 15:43:02.046  1017  1140 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
08-26 15:43:02.046  1017  1140 D SecContentProvider2: mCursor = null
08-26 15:43:02.046  1017  1337 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 15:43:02.046  1017  1337 D SecContentProvider2: mCursor = null
,08-26 15:43:02.046  1017  1029 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-26 15:43:02.046  1017  1029 D SecContentProvider2: mCursor = null
,08-26 15:43:02.046  1017  1347 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-26 15:43:02.046  1017  1347 D SecContentProvider2: mCursor = null
,08-26 15:43:02.076   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 15:43:02.076  1017  7656 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 15:43:02.076  1017  2754 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-26 15:43:02.086  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-26 15:43:02.146  1017  7656 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 13:43:02 GMT], X-Android-Received-Millis=[1472218982152], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472218982117]}
,08-26 15:43:02.146  1017  7656 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-26 15:43:02.146  1017  7656 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 15:43:02.146  1017  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-26 15:43:02.146  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 15:43:02.146  1017  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 15:43:02.146  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 15:43:02.146  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 15:43:02.146  4746  6853 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:43:02.146  1178  1732 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 15:43:02.146  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
,08-26 15:43:02.146  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:43:02.146  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:43:02.146  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 15:43:02.146  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 15:43:02.146  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:02.156  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:02.156  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:02.156  7693  7693 D AndroidRuntime: ,
08-26 15:43:02.156  7693  7693 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 15:43:02.166  7693  7693 D AndroidRuntime: CheckJNI is OFF,
08-26 15:43:02.166  7693  7693 D AndroidRuntime: readGMSProperty: start
08-26 15:43:02.166  7693  7693 D AndroidRuntime: readGMSProperty: already setted!!
08-26 15:43:02.166  7693  7693 D AndroidRuntime: propertySet: couldn't set property (it is from app),
08-26 15:43:02.166  7693  7693 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 15:43:02.166  7693  7693 D AndroidRuntime: readGMSProperty: end
08-26 15:43:02.166  7693  7693 D AndroidRuntime: addProductProperty: start
,08-26 15:43:02.176  6792  6792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-26 15:43:02.176  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:02.176  6792  6845 I jxcore-log: 
,08-26 15:43:02.286  7693  7693 E AffinityControl: AffinityControl: registerfunction enter,
,08-26 15:43:02.316  7693  7693 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-26 15:43:02.326  6792  6792 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 15:43:02.326  6792  6845 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:02.326  6792  6845 I jxcore-log: 
,08-26 15:43:02.336  1017  1495 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-26 15:43:02.336  1017  1495 D PackageManager: START PACKAGE DELETE: observer{748250760}
08-26 15:43:02.336  1017  1495 D PackageManager: pkg{<packageName>}
08-26 15:43:02.336  1017  1495 D PackageManager: user{0}
08-26 15:43:02.336  1017  1495 D PackageManager: caller{2000}
08-26 15:43:02.336  1017  1495 D PackageManager: flags{2}
08-26 15:43:02.336  1017  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-26 15:43:02.336  1017  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 15:43:02.336  1017  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 15:43:02.336  1017  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-26 15:43:02.336  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-26 15:43:02.336  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 15:43:02.336  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-26 15:43:02.346  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled,
08-26 15:43:02.346  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 15:43:02.346  1017  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-26 15:43:02.356  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-26 15:43:02.356  1017  1042 I ActivityManager: Killing 6792:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 15:43:02.356  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{1f87f6f8 u0 com.test.thalitest/.MainActivity t2}
,08-26 15:43:02.426  1017  1042 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:43:02.436  1017  1042 D InputDispatcher: Focus left window: 6792,
,08-26 15:43:02.446   258   439 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-26 15:43:02.446   258   437 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 15:43:02.456  1017  1042 D InputDispatcher: Focused application released
08-26 15:43:02.456  1017  1042 D FocusedStackFrame: Set to : 0
08-26 15:43:02.456  1017  1047 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-26 15:43:02.456  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:43:02.456  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:43:02.456  1017  1042 W ActivityManager: mDVFSHelper.acquire()
,08-26 15:43:02.476  1017  1057 W PackageSettings: Skipping PackageSetting{1d5c4c32 com.example.hello/10168} due to missing metadata
,08-26 15:43:02.476  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:43:02.476  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:43:02.476  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:43:02.476  1017  1030 D BatteryService: stay LED for fully charged
08-26 15:43:02.476  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:43:02.496  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:02.506  1017  1042 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-26 15:43:02.526  1017  1017 I MotionRecognitionService: Plugged,
08-26 15:43:02.526  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:43:02.536  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:43:02.536  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:43:02.536  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:43:02.536  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:43:02.546  1479  1479 D Launcher: onRestart, Launcher: 388686121
,08-26 15:43:02.546  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:43:02.556  7540  7540 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:43:02.556  7540  7571 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:43:02.566  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:43:02.566  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:43:02.566  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 15:43:02.576  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:02.576  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:02.576  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:02.576  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:02.586  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:02.586  7709  7709 E Zygote  : MountEmulatedStorage()
08-26 15:43:02.586  7709  7709 E Zygote  : v2
08-26 15:43:02.586  7709  7709 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:02.586  7709  7709 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:02.586  7709  7709 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:02.596  7709  7709 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:43:02.596  1017  1042 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7709 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:43:02.596  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-26 15:43:02.596  7709  7709 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:43:02.596  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-26 15:43:02.636  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 15:43:02.676  7709  7709 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:02.676  7709  7709 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:02.686  1017  2754 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-26 15:43:02.686  1017  2754 D SecContentProvider2: mCursor = null
,08-26 15:43:02.696  1479  1479 D Launcher: onStart, Launcher: 388686121
,08-26 15:43:02.696  1479  1479 D Launcher.HomeView: onStart
,08-26 15:43:02.696  1479  1479 D Launcher: onResume, Launcher: 388686121
,08-26 15:43:02.696  1017  1488 D SettingsProvider: name = kids_home_mode
08-26 15:43:02.696  1017  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:02.696  1017  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:02.696  1017  1488 D SettingsProvider: selectionArgs: false
08-26 15:43:02.696  1017  1488 D SettingsProvider: selectionArgs: 10006
08-26 15:43:02.696  1017  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:02.696  1017  1488 D SettingsProvider: ret = -1
,08-26 15:43:02.696  1479  1479 D Launcher.HomeView: onResume
,08-26 15:43:02.706  2641  2641 I art     : Explicit concurrent mark sweep GC freed 19541(1115KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.063ms total 56.894ms
,08-26 15:43:02.716  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 15:43:02.736  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 15:43:02.736  1918  1918 E SamsungIME: mOCRHelper is null
,08-26 15:43:02.736  1987  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
,08-26 15:43:02.746  4746  4746 I art     : Explicit concurrent mark sweep GC freed 22702(1371KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.290ms total 132.250ms
,08-26 15:43:02.756  1479  1479 D MenuAppsGridFragment: onResume
,08-26 15:43:02.756  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 15:43:02.766  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 15:43:02.766  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 15:43:02.766  1017  1041 W TextServicesManagerService: no available spell checker services found
,08-26 15:43:02.766  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 15:43:02.766  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:02.766  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:02.776  1426  1426 D PersonaManager: isKioskContainerExistOnDevice,
,08-26 15:43:02.786  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:02.796  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:02.796  1017  1125 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-26 15:43:02.796  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:02.796  1017  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-26 15:43:02.796  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:43:02.796  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:02.796  1017  4967 D ActivityManager: handle home activity for 0
08-26 15:43:02.796  1017  4967 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-26 15:43:02.796  1017  4967 D KnoxTimeoutHandler: post home show event for user 0
08-26 15:43:02.796  1017  4967 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 15:43:02.796  1017  4967 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:43:02.796  1017  4967 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 15:43:02.796  1479  1479 D Launcher.HomeView: onPause
,08-26 15:43:02.806  1426  1426 D RegisteredServicesCache: empty dynamic service
08-26 15:43:02.806  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 15:43:02.816  1017  1125 V NetworkStats: performPollLocked() took 17ms
08-26 15:43:02.816  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:02.816  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:02.816  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:02.826  1426  1426 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 15:43:02.826  1426  1426 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:43:02.836  7709  7709 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 15:43:02.836  7709  7709 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 15:43:02.836  7709  7709 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 15:43:02.846   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-26 15:43:02.846  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 15:43:02.856  7709  7709 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 15:43:02.856  7709  7709 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-26 15:43:02.856  7709  7709 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 15:43:02.856  7709  7709 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:02.856  1017  1477 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 1 receivers.size=28
08-26 15:43:02.856  1017  1477 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 15:43:02.856  1017  1477 I ActivityManager: Killing 7104:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-26 15:43:02.876  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 15:43:02.876  1017  1476 D InputDispatcher: Focus entered window: 1479
,08-26 15:43:02.886  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:43:02.886  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:43:02.886  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 15:43:02.896  1017  1475 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 15:43:02.896  1779  1779 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:43:02.896  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:02.896  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:02.896  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:02.896  1017  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:02.906  7728  7728 E Zygote  : MountEmulatedStorage(),
,08-26 15:43:02.906  7728  7728 I libpersona: KNOX_SDCARD checking this for 10031
08-26 15:43:02.906  7728  7728 E Zygote  : v2
08-26 15:43:02.906  7728  7728 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:02.906  7728  7728 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:43:02.916  1017  1475 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7728 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-26 15:43:02.916  1017  1017 I art     : Explicit concurrent mark sweep GC freed 86557(5MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/37MB, paused 11.703ms total 280.416ms
08-26 15:43:02.916  7728  7728 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:43:02.916  1017  1057 I art     : WaitForGcToComplete blocked for 164.845ms for cause Explicit
08-26 15:43:02.916  7728  7728 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:02.926  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{25fe3b2f token=android.os.BinderProxy@1f2c2da1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-26 15:43:02.926  1479  1479 D Launcher.HomeView: onStop
,08-26 15:43:02.936  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 15:43:02.936  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:02.936  1017  1476 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 15:43:02.936  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:02.946  2473  2482 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,08-26 15:43:02.946  7728  7728 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:43:02.946  1017  4967 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-26 15:43:02.946  1017  4967 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-26 15:43:02.946  7728  7728 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:02.946  1017  4967 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:02.946  1017  4967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:02.946  1017  4967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-26 15:43:02.956  1779  1779 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-26 15:43:02.956  1779  1779 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-26 15:43:02.956  1779  1779 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 15:43:02.956  1779  1779 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
08-26 15:43:02.956  1017  1476 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6792 uid 10171
,08-26 15:43:02.966  1017  7743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:43:02.976  1918  1918 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-26 15:43:02.976  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-26 15:43:02.986  1017  1477 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:43:02.986  1017  1476 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-26 15:43:02.996  1017  1476 D SecContentProvider2: mCursor = null
,08-26 15:43:02.996  1017  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 15:43:03.006  1779  1779 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:43:03.006  1779  1779 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 15:43:03.016  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-26 15:43:03.016  1017  1477 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:43:03.026  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30523eb6 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:146940
08-26 15:43:03.026  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 15:43:03.026  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 15:43:03.026  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 15:43:03.026  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-26 15:43:03.026  1017  1476 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:43:03.046  1017  1475 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-26 15:43:03.046  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.046  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:03.046  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.046  1017  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:03.046  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-26 15:43:03.046  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 15:43:03.056  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty,
08-26 15:43:03.056  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:43:03.056  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:03.056  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:43:03.056  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:43:03.066  7269  7269 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-26 15:43:03.106  1017  1477 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 15:43:03.106  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.106  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:03.106  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:03.106  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:43:03.136  7141  7141 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-26 15:43:03.136  2757  7751 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-26 15:43:03.136  2757  7751 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-26 15:43:03.136  2757  7751 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 15:43:03.146  7190  7190 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 15:43:03.146  7190  7190 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,08-26 15:43:03.146  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:03.146  7190  7190 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 15:43:03.146  7010  7750 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 15:43:03.146  7010  7750 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:43:03.146  7010  7750 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 15:43:03.146  7010  7750 I System.out: (HTTPLog)-Thread-1270-832990420: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 15:43:03.146  7010  7750 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:43:03.146   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:43:03.146   277   961 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-26 15:43:03.166  7190  7190 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 15:43:03.166  7190  7190 I SA      : [OR] == isSIMCardReady false ==
,08-26 15:43:03.166  2757  7751 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-26 15:43:03.166  2757  7751 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-26 15:43:03.176  2757  7751 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-26 15:43:03.176  2757  7751 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-26 15:43:03.176  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 15:43:03.176  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 15:43:03.176  7190  7190 I SA      : [SCU] == networkStateCheck == true
,08-26 15:43:03.176  2757  7751 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-26 15:43:03.176  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:03.176  2757  7751 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-26 15:43:03.176  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:03.176  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
08-26 15:43:03.176  2757  7751 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
08-26 15:43:03.186  7190  7190 I SA      : [DM] getCountryCodeFromCSC : PL
08-26 15:43:03.186  7190  7190 I SA      : isChinaCountryCode : false,
08-26 15:43:03.186  7190  7190 I SA      : [SCU] is ChinestModel Data Restricted   : false
,08-26 15:43:03.186  7190  7190 I SA      : [OR] == networkStateCheck true ==
08-26 15:43:03.186  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-26 15:43:03.186  2757  7751 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT,
,08-26 15:43:03.186  7010  7750 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:43:03.196  7190  7190 I SA      : [OR] GetMyCountryZoneTask
,08-26 15:43:03.196  7190  7190 I SA      : [OR] onReceive END
,08-26 15:43:03.206  1017  1057 W art     : Suspending all threads took: 19.073ms
,08-26 15:43:03.206  7339  7353 W art     : Suspending all threads took: 9.005ms
,08-26 15:43:03.206  7190  7754 I SA      : [SRS] prepareGetMyCountryZone
,08-26 15:43:03.216  7190  7754 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 15:43:03.216  7190  7754 I SA      : [SSP] query invoked
,08-26 15:43:03.226  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-26 15:43:03.226  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-26 15:43:03.226  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:43:03.226  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 15:43:03.236  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:43:03.236  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:43:03.236  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:43:03.236  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 15:43:03.236  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 15:43:03.236  2757  7751 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-26 15:43:03.246  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:03.246  7190  7754 I SA      : [TPMU] GetMccFromDB : null
08-26 15:43:03.246  7190  7754 I SA      : [SCU] getMccFromPreferece mcc = 260
08-26 15:43:03.246  7190  7754 I SA      : [LBE] isSupportCheckDomainRegion : false
08-26 15:43:03.246  7190  7754 I SA      : [TPM] isNoProxy(default) : true
,08-26 15:43:03.246  1017  1488 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-26 15:43:03.246  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.246  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:03.246  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.246  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-26 15:43:03.246  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 15:43:03.256  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-26 15:43:03.256  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:03.256  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 15:43:03.256  1017  3347 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 15:43:03.256  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-26 15:43:03.256  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:43:03.256  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 15:43:03.256  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-26 15:43:03.266  2757  7751 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-26 15:43:03.266  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-26 15:43:03.266  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:43:03.266  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:43:03.266  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 15:43:03.266  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 15:43:03.266  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-26 15:43:03.266  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 15:43:03.266  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 15:43:03.266  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 15:43:03.276  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-26 15:43:03.276  1017  1337 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-26 15:43:03.276  7010  7750 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 15:43:03.276  1017  1337 D SecContentProvider2: mCursor = null
,08-26 15:43:03.276  7190  7754 E File    : fail readDirectory() errno=2
,08-26 15:43:03.286  1178  1178 I StatusBar: Icon Only
,08-26 15:43:03.286  1178  1178 D PanelView: There is/are notification(s) 
,08-26 15:43:03.296  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:03.296  1017  1057 I art     : Explicit concurrent mark sweep GC freed 15241(908KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 44.588ms total 379.422ms
,08-26 15:43:03.296  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 15:43:03.296  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:03.326  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 15:43:03.346  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 15:43:03.356  1017  1489 I ActivityManager: Killing 7173:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-26 15:43:03.356  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 15:43:03.366  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.366  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.366  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.366  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:03.376  7758  7758 E Zygote  : MountEmulatedStorage()
08-26 15:43:03.376  7758  7758 I libpersona: KNOX_SDCARD checking this for 10001
08-26 15:43:03.376  7758  7758 E Zygote  : v2
08-26 15:43:03.376  7758  7758 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:03.376  7758  7758 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:03.386  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7758 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:43:03.396  7758  7758 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 15:43:03.396  7758  7758 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:03.416   303   303 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 27.589ms
,08-26 15:43:03.426  7758  7758 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:43:03.426  1017  1057 D PackageManager: delete codoeFile: 
,08-26 15:43:03.426  7758  7758 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:03.436   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.494ms
,08-26 15:43:03.436  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-26 15:43:03.456   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.770ms
,08-26 15:43:03.456  1017  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-26 15:43:03.456  1017  1057 D PackageManager: result of delete: 1{748250760}
,08-26 15:43:03.476  7693  7693 D AndroidRuntime: Shutting down VM
,08-26 15:43:03.486  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 15:43:03.486  1017  1057 D PackageManager: userId{-1}
08-26 15:43:03.486  1017  1057 D PackageManager: andCode{true}
08-26 15:43:03.486  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 15:43:03.496  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.496  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.496  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.496  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:03.506  7775  7775 E Zygote  : MountEmulatedStorage(),
08-26 15:43:03.506  7775  7775 E Zygote  : v2
,08-26 15:43:03.506  7775  7775 I libpersona: KNOX_SDCARD checking this for 10003
08-26 15:43:03.506  7775  7775 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:03.506  7775  7775 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:43:03.506  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7775 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 15:43:03.516  1017  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 15:43:03.516  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.516  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.516  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.516  1017  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:03.516  7775  7775 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:03.516  7775  7775 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:03.516  1479  1479 I Choreographer: Skipped 32 frames!  The application may be doing too much work on its main thread.
08-26 15:43:03.526  1479  1479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f2c2da1 time:147440
,08-26 15:43:03.536  7784  7784 E Zygote  : MountEmulatedStorage()
,08-26 15:43:03.536  7784  7784 E Zygote  : v2
08-26 15:43:03.536  7784  7784 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:03.536  7784  7784 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:03.536  7784  7784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:03.536  1017  1489 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7784 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:43:03.536  7784  7784 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:03.536  1017  1489 I ActivityManager: Killing 7212:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-26 15:43:03.536  1017  1475 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-26 15:43:03.536  1017  1475 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.536  1017  1475 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.536  1017  1475 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023,
08-26 15:43:03.536  1017  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-26 15:43:03.546  7784  7784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:43:03.546  7775  7775 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:03.546  7775  7775 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:03.556  1017  1347 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:43:03.556  1017  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.556  1017  1347 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.556  1017  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-26 15:43:03.556  1017  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:03.566  7269  7269 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-26 15:43:03.566  7269  7269 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-26 15:43:03.576   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:43:03.576   277   961 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: exit::IDLE
,08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-26 15:43:03.576  7269  7269 D InitializeManagerStateMachine: entry::SUCCESS
08-26 15:43:03.576  7269  7269 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-26 15:43:03.576  4746  4746 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 15:43:03.586  7784  7784 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:03.586  7269  7269 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-26 15:43:03.586  7269  7269 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-26 15:43:03.586  7784  7784 D ActivityThread: Added TimaKeyStore provider
08-26 15:43:03.586  4746  7288 I iu.UploadsManager: num queued entries: 0
,08-26 15:43:03.586  7269  7269 D InitializeManagerStateMachine: exit::SUCCESS
08-26 15:43:03.586  7269  7269 D InitializeManagerStateMachine: entry::IDLE
,08-26 15:43:03.596  4746  7288 I iu.UploadsManager: num updated entries: 0
,08-26 15:43:03.596  4746  7288 I iu.SyncManager: NEXT; no task
,08-26 15:43:03.616  1017  1489 I ActivityManager: Killing 6868:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-26 15:43:03.616  1017  1489 I ActivityManager: Killing 7253:com.sec.android.provider.badge/u0a68 (adj 15): empty #22
,08-26 15:43:03.646  7784  7784 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 15:43:03.686  7693  7693 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-26 15:43:03.706  1987  7800 I qtaguid : Tagging socket 47 with tag 1000040700000000{268436487,0} for uid -1, pid: 1987, getuid(): 10011
,08-26 15:43:03.776  7784  7784 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 15:43:03.796  7784  7784 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,08-26 15:43:03.796  7784  7784 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:03.796  7784  7784 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 15:43:03.796  7784  7784 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-26 15:43:03.796  7784  7784 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-26 15:43:03.866  7190  7754 I SA      : [RC New] Execute method=[GET] start
,08-26 15:43:03.896  7190  7754 I SA      : [RC New] Security=[true]
,08-26 15:43:03.896  7190  7754 I System.out: Thread-1321(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-26 15:43:03.896  7190  7754 I System.out: Thread-1321(ApacheHTTPLog):isSBSettingEnabled false
08-26 15:43:03.896  7190  7754 I System.out: Thread-1321(ApacheHTTPLog):isShipBuild true
08-26 15:43:03.896  7190  7754 I System.out: Thread-1321(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-26 15:43:03.896  7190  7754 I System.out: Thread-1321(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-26 15:43:03.906   277   961 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:43:03.906   277   961 D Netd    : getNetworkForDns: using netid 504 for uid 10036
,08-26 15:43:03.906  1017  1337 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-26 15:43:03.916  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:43:03.916  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.916  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:03.916  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
