#### Test 8291407379492e1_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system,
08-29 10:23:31.115  1018  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-29 10:23:31.115  1018  1321 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 10:23:31.115  1018  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 10:23:31.115  1018  1321 D BatteryService: stay LED for fully charged
08-29 10:23:31.115  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-29 10:23:31.125  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 10:23:31.135  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 10:23:31.135  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 10:23:31.135  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-29 10:23:31.135  1018  1018 I MotionRecognitionService: Plugged
08-29 10:23:31.135  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-29 10:23:31.145  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 10:23:31.145  3178  3283 D HeadsetStateMachine: Disconnected process message: 10
08-29 10:23:31.165  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 10:23:31.165  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 10:23:31.165  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 10:23:31.395  6767  6767 D AndroidRuntime: 
08-29 10:23:31.395  6767  6767 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 10:23:31.395  6767  6767 D AndroidRuntime: CheckJNI is OFF
08-29 10:23:31.395  6767  6767 D AndroidRuntime: readGMSProperty: start
08-29 10:23:31.395  6767  6767 D AndroidRuntime: readGMSProperty: already setted!!
08-29 10:23:31.395  6767  6767 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 10:23:31.395  6767  6767 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 10:23:31.395  6767  6767 D AndroidRuntime: readGMSProperty: end
08-29 10:23:31.395  6767  6767 D AndroidRuntime: addProductProperty: start
08-29 10:23:31.525  6767  6767 E AffinityControl: AffinityControl: registerfunction enter
08-29 10:23:31.545  6767  6767 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 10:23:31.565  1018  1500 E PersonaManagerService: inState():  stateMachine is null !!
08-29 10:23:31.565  1018  1500 I PersonaManagerService: PersonaId don't exist
08-29 10:23:31.565  1018  1500 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 10:23:31.565  1018  1500 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 10:23:31.585  1018  1500 W ActivityManager: mDVFSHelper.acquire()
08-29 10:23:31.585   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-29 10:23:31.585   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-29 10:23:31.595  1018  1500 D FocusedStackFrame: Set to : 0
08-29 10:23:31.595  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:31.595  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:31.595  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:31.595  1018  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:31.605  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 10:23:31.605  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 10:23:31.615  6778  6778 E Zygote  : MountEmulatedStorage()
08-29 10:23:31.615  6778  6778 E Zygote  : v2
08-29 10:23:31.615  6778  6778 I libpersona: KNOX_SDCARD checking this for 10171
08-29 10:23:31.615  6778  6778 I libpersona: KNOX_SDCARD not a persona
08-29 10:23:31.615  1018  1500 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6778 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 10:23:31.615  1018  1500 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 10:23:31.615  1018  1500 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 10:23:31.615  6778  6778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:23:31.615  1018  1500 D InputDispatcher: Focused application set to: xxxx
08-29 10:23:31.615  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 10:23:31.615  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 10:23:31.615  1018  1500 D InputDispatcher: Focus left window: 1501
08-29 10:23:31.615   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-29 10:23:31.615  6778  6778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:31.625  6767  6767 D AndroidRuntime: Shutting down VM
08-29 10:23:31.625  6778  6778 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 10:23:31.635  6778  6778 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 10:23:31.635  6778  6778 D ActivityThread: Added TimaKeyStore provider
08-29 10:23:31.645  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 10:23:31.645  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 10:23:31.645  1018  1319 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 10:23:31.645  1018  1018 V ActivityManager: Display changed displayId=0
08-29 10:23:31.655  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 10:23:31.665  1018  1319 D PersonaManager: isKioskContainerExistOnDevice
08-29 10:23:31.685  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 10:23:31.705   258   458 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-29 10:23:31.705   258  1113 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-29 10:23:31.715  1501  1501 V ActivityThread: updateVisibility : ActivityRecord{3d24f661 token=android.os.BinderProxy@3e80d443 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 10:23:31.715  1501  1501 D Launcher: onTrimMemory. Level: 20
08-29 10:23:31.805  6778  6778 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-29 10:23:31.825  6767  6767 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 10:23:31.845  6778  6778 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6885-6888)
,08-29 10:23:31.855  6778  6778 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 10:23:31.875  6778  6778 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21f3e505}
,08-29 10:23:31.875  6778  6778 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 10:23:31.885  6778  6778 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 10:23:31.915  6778  6778 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 10:23:31.925  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 10:23:31.925   293   293 E SMD     : DCD OFF,
,08-29 10:23:31.935  6778  6778 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-29 10:23:31.955  6778  6778 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 10:23:31.955  6778  6778 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 10:23:31.955  6778  6778 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 10:23:31.955  6778  6778 I Adreno-EGL: Local Branch: 
08-29 10:23:31.955  6778  6778 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 10:23:31.955  6778  6778 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 10:23:31.955  6778  6778 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 10:23:32.045  6778  6778 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 10:23:32.055  6778  6778 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 10:23:32.055  6778  6778 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 10:23:32.075  6778  6778 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 10:23:32.075  6778  6778 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 10:23:32.175  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{2547e50a u0 com.test.thalitest/.MainActivity t2}
,08-29 10:23:32.195  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 10:23:32.205  6778  6778 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 10:23:32.215  6778  6778 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-29 10:23:32.215  6778  6778 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-29 10:23:32.225  6778  6778 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-29 10:23:32.225  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 10:23:32.225  6778  6778 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 10:23:32.315  6778  6819 D OpenGLRenderer: Render dirty regions requested: true
,08-29 10:23:32.315  1018  1321 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 10:23:32.315  1018  1321 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 10:23:32.315  1018  1321 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 10:23:32.315  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 10:23:32.315  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 10:23:32.325  6778  6806 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-29 10:23:32.325  6778  6778 V ActivityThread: updateVisibility : ActivityRecord{2bdc49e5 token=android.os.BinderProxy@1094c3ae {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-29 10:23:32.335  6778  6778 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-29 10:23:32.335  6778  6778 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-29 10:23:32.345   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-29 10:23:32.365  1018  1454 D InputDispatcher: Focus entered window: 6778
,08-29 10:23:32.375  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 10:23:32.375  6778  6778 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 10:23:32.375  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 10:23:32.375  6778  6819 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 10:23:32.375  6778  6819 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-29 10:23:32.385  6778  6819 D OpenGLRenderer: Enabling debug mode 0
,08-29 10:23:32.395  1018  1319 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 10:23:32.405  1177  1177 I StatusBar: Icon Only
,08-29 10:23:32.405  1177  1177 D PanelView: There is/are notification(s) 
,08-29 10:23:32.405  1018  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 10:23:32.415  1018  1048 I ActivityManager: Displayed Component not be shown by security: +749ms (total +821ms)
,08-29 10:23:32.425  1018  1048 W ActivityManager: mDVFSHelper.release()
08-29 10:23:32.425  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2547e50a u0 com.test.thalitest/.MainActivity t2} time:107460
,08-29 10:23:32.425   258   458 I SurfaceFlinger: id=12 Removed uhalitest (7/9),
,08-29 10:23:32.425   258   456 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-29 10:23:32.435  6778  6778 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-29 10:23:32.435  6778  6778 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1094c3ae time:107473
,08-29 10:23:32.445  1884  1884 I SamsungIME: getCurrentCandidateView
,08-29 10:23:32.525  6778  6778 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6778
,08-29 10:23:32.545  1884  1884 D SamsungIME: Dismiss ExpandCandiate
,08-29 10:23:32.695  1884  1884 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 10:23:32.725  6778  6778 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 10:23:32.745  1884  1884 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 10:23:32.765  1884  1884 I SamsungIME: KeybaordView init() : load resources
,08-29 10:23:32.785  1884  1884 I SamsungIME: getCurrentKeyboard
,08-29 10:23:32.785  1884  1884 I SamsungIME: getTextKeyboard
,08-29 10:23:32.815  1884  1884 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-29 10:23:32.815  6778  6827 D jxcore_app_log: JniHelper::setJavaVM(0xb707f2b0), pthread_self() = -1218390848
,08-29 10:23:32.825  6778  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 10:23:32.825  6778  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 10:23:32.825  6778  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 10:23:32.825  6778  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 10:23:32.825  6778  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 10:23:32.825  6778  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cec18e3 added. We now have 1 listener(s)
,08-29 10:23:32.825  6778  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-29 10:23:32.825  6778  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 10:23:32.825  6778  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:23:32.825  6778  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 10:23:32.835  6778  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@230f745e added. We now have 1 listener(s)
08-29 10:23:32.835  6778  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:23:32.845  6778  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:23:32.845  6778  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 10:23:32.845  6778  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 10:23:32.845  6778  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 10:23:32.845  6778  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 10:23:32.845  6778  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:32.845  6778  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-29 10:23:32.855  6778  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:32.855  6778  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:23:32.855  6778  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 10:23:32.855  6778  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:23:32.865  6778  6827 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 10:23:32.865  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:32.865  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:32.895  6778  6778 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 10:23:33.075  1018  1327 E Watchdog: !@Sync 3
,08-29 10:23:33.365  6778  6834 W jxcore-log: Initializing JXcore engine
08-29 10:23:33.365  6778  6834 W jxcore-log: JXcore engine is ready
,08-29 10:23:33.415  2021  2021 E audit   : type=1400 msg=audit(1472459013.415:205): avc:  denied  { ioctl } for  pid=6834 comm="Thread-1266" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 10:23:33.415  2021  2021 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:33.415  2021  2021 E audit   : type=1300 msg=audit(1472459013.415:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9c7c28f8 items=0 ppid=324 ppcomm=main pid=6834 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1266" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 10:23:33.415  2021  2021 E audit   : type=1320 msg=audit(1472459013.415:205): 
,08-29 10:23:33.425  6778  6834 W jxcore-log: Starting JXcore engine
,08-29 10:23:33.535  6778  6834 W jxcore-log: Platform android
08-29 10:23:33.535  6778  6834 W jxcore-log: 
08-29 10:23:33.535  6778  6834 W jxcore-log: Process ARCH arm
08-29 10:23:33.535  6778  6834 W jxcore-log: 
,08-29 10:23:33.745  6778  6834 I jxcore-log: JXcore Cordova bridge is ready!
08-29 10:23:33.745  6778  6834 I jxcore-log: 
,08-29 10:23:33.745  6778  6834 W jxcore-log: JXcore engine is started
,08-29 10:23:33.755  6778  6827 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 10:23:33.765  6778  6778 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 10:23:33.975   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 10:23:33.975   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 10:23:34.925   293   293 E SMD     : DCD OFF
,08-29 10:23:36.675  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
,08-29 10:23:36.695  1018  3361 D SSRM:n  : SIOP:: AP = 340
,08-29 10:23:37.925   293   293 E SMD     : DCD OFF,
,08-29 10:23:38.575  5599  5599 D FactoryTest: Not factory mode
,08-29 10:23:38.585  5599  5599 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 10:23:38.585  5599  5599 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-29 10:23:38.585  5599  5599 D MTPRx   : still no open session command from host, so toast
,08-29 10:23:38.585  5599  5599 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-29 10:23:38.585  5599  5599 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 10:23:38.585  5599  5599 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113628
,08-29 10:23:38.585  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
,08-29 10:23:38.595  1018  1030 I PersonaManagerService: PersonaId don't exist
08-29 10:23:38.595  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 10:23:38.595  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 10:23:38.595  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:38.595  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:38.595  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 10:23:38.605  1018  1030 W ActivityManager: mDVFSHelper.acquire()
,08-29 10:23:38.615  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,08-29 10:23:38.625  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 10:23:38.625  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 10:23:38.625  1018  1030 D InputDispatcher: Focused application set to: xxxx
,08-29 10:23:38.625  1018  1030 D InputDispatcher: Focus left window: 6778
,08-29 10:23:38.625  5599  5599 E MTPRx   : started activity for popup
,08-29 10:23:38.625  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 10:23:38.625  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 10:23:38.645  5599  5599 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 10:23:38.645  5599  5599 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-29 10:23:38.655  5599  5599 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 10:23:38.655  5599  5599 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 10:23:38.655  5599  5599 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 10:23:38.655  5599  5599 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 10:23:38.675  5599  5599 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 10:23:38.685  1018  1499 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 10:23:38.685  1018  1499 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 10:23:38.685  1018  1499 D InputDispatcher: Focused application set to: xxxx
,08-29 10:23:38.685  1018  1499 D InputDispatcher: Focus entered window: 6778
,08-29 10:23:38.695  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 10:23:38.695  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 10:23:38.695  1018  1208 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 10:23:38.695  1018  1208 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@778b6c5 attribute=null, token = android.os.BinderProxy@26f68e55
,08-29 10:23:38.725  5599  5599 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 10:23:38.735  5599  5599 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-29 10:23:38.735  5599  5599 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 10:23:38.755  6778  6778 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 10:23:38.755  6778  6778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-29 10:23:38.755  6778  6778 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 10:23:38.755  6778  6778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 10:23:38.755  1018  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 10:23:38.755  1018  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-29 10:23:38.755  1018  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 10:23:38.765  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 10:23:38.765  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 10:23:38.775  6778  6778 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 10:23:38.775  6778  6778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 10:23:38.785  6778  6778 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c07ad0a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3c174103, 16908290=android.view.AbsSavedState$1@3c174103}, android:focusedViewId=100}]}]
,08-29 10:23:38.785  6778  6778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 10:23:38.785  6778  6778 V ActivityThread: updateVisibility : ActivityRecord{2bdc49e5 token=android.os.BinderProxy@1094c3ae {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 10:23:38.785  6778  6778 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 10:23:38.785  6778  6778 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 10:23:38.785  6778  6778 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1094c3ae time:113821
,08-29 10:23:38.785  1018  1208 D PersonaManager: isKioskContainerExistOnDevice
,08-29 10:23:38.975   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:23:39.975   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:40.925   293   293 E SMD     : DCD OFF,
,08-29 10:23:40.975   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:41.175  1018  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 10:23:41.175  1018  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 10:23:41.175  1018  1491 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 10:23:41.175  1018  1491 D BatteryService: stay LED for fully charged
,08-29 10:23:41.175  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 10:23:41.175  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 10:23:41.175  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 10:23:41.175  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 10:23:41.185  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 10:23:41.185  1018  1018 I MotionRecognitionService: Plugged
08-29 10:23:41.185  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 10:23:41.185  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 10:23:41.185  3178  3283 D HeadsetStateMachine: Disconnected process message: 10
,08-29 10:23:41.205  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:23:41.205  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:23:41.205  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:23:41.605  1018  1043 W ActivityManager: mDVFSHelper.release(),
,08-29 10:23:41.665  1018  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-29 10:23:41.975   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:42.975   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:23:43.925   293   293 E SMD     : DCD OFF
,08-29 10:23:43.975   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-29 10:23:44.965  1018  1096 V AlarmManager: waitForAlarm result :4,
,08-29 10:23:44.975  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,08-29 10:23:44.995  1946  1946 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-29 10:23:45.075  1946  1946 I art     : Explicit concurrent mark sweep GC freed 52449(3MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 10MB/17MB, paused 1.195ms total 66.776ms
,08-29 10:23:45.095  4663  4663 D ConnectivityManager: CallingUid : 10011, CallingPid : 4663
,08-29 10:23:45.105  1018  1454 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:23:45.105  1018  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-29 10:23:45.105  1018  1129 D ConnectivityService: apparently satisfied.  currentScore=60
08-29 10:23:45.105  1018  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-29 10:23:45.105  4663  6842 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:23:45.105  1018  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:23:45.105  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
08-29 10:23:45.105  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:45.105  1018  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:45.105  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:45.175  4663  6843 W DriveInitializer: Background init thread started
,08-29 10:23:45.205   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-29 10:23:45.205   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:45.205  4663  6843 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-29 10:23:45.255  1946  1946 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-29 10:23:45.295  1018  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:23:45.295  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.HeartbeatAlarm$ConnectionInfoPersistService; callingUser = 0; userId(target) = 0
,08-29 10:23:45.295  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:45.295  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:45.295  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:45.335  1018  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:45.335  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.container.ConfigService; callingUser = 0; userId(target) = 0
,08-29 10:23:45.335  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:45.335  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:45.335  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:45.395  1018  1208 I art     : Explicit concurrent mark sweep GC freed 35233(1946KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.532ms total 157.944ms
,08-29 10:23:45.415  1018  1208 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:45.415  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:45.415  1018  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:45.415  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:45.435  1018  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:45.435  4663  6843 W DriveInitializer: Background init thread ended
,08-29 10:23:45.435  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:45.435  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:45.435  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:45.495  1946  1946 D WearableService: callingUid 10011, callindPid: 1946
,08-29 10:23:45.565  1946  6854 I CheckinUtil: Classify the device as Phone.
,08-29 10:23:45.575  1018  1208 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 10:23:45.575  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-29 10:23:45.575  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:45.575  1018  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:45.575  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:45.605  1946  6854 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-29 10:23:45.605  1946  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:23:45.605  1946  6854 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 10:23:45.605  1946  6854 I System.out: (HTTPLog)-Thread-267-468690451: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-29 10:23:45.605  1946  6854 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:23:45.605   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 10:23:45.605   278   984 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 10:23:45.655  1946  6854 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 10:23:45.655  1946  6854 I qtaguid : Tagging socket 60 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1946, getuid(): 10011
,08-29 10:23:45.695  1946  6854 I qtaguid : Tagging socket 63 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1946, getuid(): 10011
,08-29 10:23:45.835  1946  6854 I qtaguid : Untagging socket 60
,08-29 10:23:45.865  4663  6845 D ChimeraConfigService: Fetched value, gms:chimera:dogfoods = null
,08-29 10:23:45.875  4663  6845 D ChimeraConfigService: Fetched value, gms:chimera:beta:module_sets = null
08-29 10:23:45.875  4663  6845 D ChimeraConfigService: Fetched value, gms:chimera:googlewide:module_sets = null
08-29 10:23:45.875  4663  6845 D ChimeraConfigService: Fetched value, gms:chimera:prod:module_sets = null
,08-29 10:23:45.875  4663  6845 D ChimeraConfigService: Fetched value, gms:chimera:module_set = null
,08-29 10:23:45.875  4663  6845 E ChimeraConfigService: gms:chimera:module_set is malformed, ignoring module set
,08-29 10:23:45.915  1018  3377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 10:23:45.955  1018  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:45.955  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-29 10:23:45.955  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:45.955  1018  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:45.955  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:45.975  1018  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-29 10:23:45.975  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-29 10:23:45.995  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 10:23:45.995  6778  6834 I jxcore-log: 
,08-29 10:23:45.995  1018  1454 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:45.995  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-29 10:23:46.005  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:46.005  1018  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.005  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 10:23:46.005  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 10:23:46.005  6778  6834 I jxcore-log: 
,08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:46.015  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:46.015  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:23:46.015  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 10:23:46.015  6778  6834 I jxcore-log: 
,08-29 10:23:46.015  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 10:23:46.015  6778  6834 I jxcore-log: 
,08-29 10:23:46.025  4663  6858 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-29 10:23:46.025  4663  6858 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-29 10:23:46.055  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 10:23:46.085  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:46.085  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.085  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.195  1018  1321 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:46.195  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-29 10:23:46.195  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:46.195  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.195  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.225  1018  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:46.225  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-29 10:23:46.225  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:46.225  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.225  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.285  1018  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:46.285  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:46.285  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.285  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.295  1018  1516 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:46.295  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:46.295  1018  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.295  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.365  1018  1321 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:46.375  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:46.375  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:23:46.375  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.375  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:46.385  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:46.385  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:46.385  1018  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:46.395  6864  6864 E Zygote  : MountEmulatedStorage(),
,08-29 10:23:46.395  6864  6864 E Zygote  : v2
,08-29 10:23:46.395  6864  6864 I libpersona: KNOX_SDCARD checking this for 10011
08-29 10:23:46.395  6864  6864 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:46.395  6864  6864 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 10:23:46.405  1018  1321 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6864 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-29 10:23:46.405  6864  6864 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:46.405  6864  6864 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 10:23:46.425  6864  6864 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:46.425  6864  6864 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:46.455  6864  6864 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-29 10:23:46.455  6864  6864 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 10:23:46.495  6864  6864 I MultiDex: VM with version 2.1.0 has multidex support
08-29 10:23:46.495  6864  6864 I MultiDex: install
08-29 10:23:46.495  6864  6864 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 10:23:46.525  6864  6864 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-29 10:23:46.585  6864  6864 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 10:23:46.585  6864  6864 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@322b22d1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-29 10:23:46.585  6864  6864 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 10:23:46.605  6864  6864 D ChimeraCfgMgr: Reading stored module config
,08-29 10:23:46.625  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-29 10:23:46.655  1018  1456 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:46.655  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:46.655  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.655  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.655  1018  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:46.665  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:46.665  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:23:46.665  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.675  6864  6879 I art     : Background sticky concurrent mark sweep GC freed 23841(1127KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 5.088ms total 56.684ms
,08-29 10:23:46.715  1018  3361 D SSRM:n  : SIOP:: AP = 350
,08-29 10:23:46.725  6864  6864 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-29 10:23:46.725  6864  6864 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-29 10:23:46.725  1946  1946 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=a2d35307-8f7e-4153-92ec-1d38004c5173
,08-29 10:23:46.745  6864  6879 W art     : Suspending all threads took: 13.991ms
,08-29 10:23:46.745  6864  6879 I art     : Background partial concurrent mark sweep GC freed 1595(201KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 18.058ms total 66.681ms
,08-29 10:23:46.755  1018  1319 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-29 10:23:46.755  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 10:23:46.755  6864  6882 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-29 10:23:46.755  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:46.755  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.755  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.755  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 10:23:46.765  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 10:23:46.775  4316  4327 I art     : Explicit concurrent mark sweep GC freed 1445(49KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 683us total 22.715ms
,08-29 10:23:46.815  1018  1321 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:46.815  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:46.815  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:46.815  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:46.825  6778  6834 D executeNativeTests: Running unit tests
,08-29 10:23:46.845   283   723 D WVCdm   : Instantiating CDM.
,08-29 10:23:46.855   283   693 I WVCdm   : CdmEngine::OpenSession
08-29 10:23:46.855   283   693 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-29 10:23:46.865   283   693 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-29 10:23:46.895   283   693 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-29 10:23:46.925  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:23:46.925  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 added. We now have 2 listener(s)
,08-29 10:23:46.935   293   293 E SMD     : DCD OFF
,08-29 10:23:46.935  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 10:23:46.935  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:23:46.935  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:23:46.935  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:23:46.935  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 added. We now have 2 listener(s)
08-29 10:23:46.935  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:23:46.935  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:23:46.935  6864  6873 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 10:23:46.935  6864  6873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 10:23:46.935  6864  6873 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 10:23:46.935  6864  6873 I System.out: (HTTPLog)-Thread-1244-104452122: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 10:23:46.935  6864  6873 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:23:46.935   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 10:23:46.935   278   984 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 10:23:46.945  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:46.945  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:46.945  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:23:46.945  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:46.955  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:46.955  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 10:23:46.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:23:46.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 10:23:46.955  6778  6834 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 10:23:46.955  6778  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:23:46.955  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:23:46.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:23:46.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:23:46.955  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:46.955  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:46.955  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:46.955  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:46.955  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.955  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:23:46.955  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:23:46.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 removed from the list,
08-29 10:23:46.955  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:23:46.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 removed from the list
08-29 10:23:46.955   283   693 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-29 10:23:46.955   283   723 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-29 10:23:46.955   283   723 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size,
08-29 10:23:46.955   283   723 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-29 10:23:46.965  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:46.965  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:46.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:46.965   283   723 D WVCdm   : PrepareKeyRequest: nonce=3393712657
08-29 10:23:46.965  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:46.965  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:46.965  6778  6834 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 10:23:46.965  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:46.965  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:46.965  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:46.965  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:46.965  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:46.965  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:46.965  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:46.965  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:46.965  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:46.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:46.965  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 10:23:46.975  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:46.975  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:46.975  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:46.975  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:46.975  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.975  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:46.975  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:46.975  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:46.975  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:46.975  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:46.975  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.975  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:46.975  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:46.975  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:46.975  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:46.975  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:46.975  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:46.975  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:46.985  6778  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 10:23:46.985  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:46.985  6864  6873 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 10:23:46.985  6864  6873 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6864, getuid(): 10011
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:46.985  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:23:46.995  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:46.995  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:23:46.995  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:23:46.995  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:23:46.995  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:23:46.995  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:46.995  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:23:46.995  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 10:23:46.995  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:46.995  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.005  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 10:23:47.015  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 10:23:47.015  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 10:23:47.025  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 10:23:47.025  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:23:47.025  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:23:47.025  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 10:23:47.035  3178  3199 D BtGatt.GattService: registerClient() - UUID=a42b7aaa-f07e-4234-a561-e8f2bac71cf8
,08-29 10:23:47.045  1946  2151 W GCoreFlp: No location to return for getLastLocation()
,08-29 10:23:47.075  3178  3274 D BtGatt.GattService: onClientRegistered() - UUID=a42b7aaa-f07e-4234-a561-e8f2bac71cf8, clientIf=6
,08-29 10:23:47.085  6778  6824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 10:23:47.085  3178  3277 D BtGatt.GattService: start scan with filters
,08-29 10:23:47.085  1018  1516 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 10:23:47.085  3178  3282 D BtGatt.ScanManager: handling starting scan
,08-29 10:23:47.085  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:23:47.085  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 10:23:47.085  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 10:23:47.085  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:23:47.085  3178  3282 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:47.085  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:47.095  1018  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:47.095  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:47.095  3178  3274 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 10:23:47.095  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:23:47.095  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.095  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:23:47.095  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:23:47.095  3178  3282 D BtGatt.ScanManager: allow scan with filters
08-29 10:23:47.095  3178  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 10:23:47.095  1018  1516 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:47.095  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:47.095  3178  3282 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-29 10:23:47.095  1018  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:23:47.095  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:47.095  3178  3274 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 10:23:47.095  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.095  3178  3282 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:23:47.095  3178  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 10:23:47.105  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 10:23:47.105  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:23:47.105  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:47.105  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:23:47.105  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:47.105  3178  3274 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 10:23:47.105  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.105  3178  3274 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 10:23:47.105  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.115  6778  6834 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:23:47.115  4663  6860 D UdcContextInitService: registered all accounts: true
,08-29 10:23:47.115  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:47.115  6778  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:23:47.115  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.115  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:23:47.115  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.115  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:23:47.115  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:23:47.115  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:23:47.115  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:23:47.115  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:47.115  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:23:47.115  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:23:47.115  3178  3199 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:23:47.115  3178  3282 D BtGatt.ScanManager: filter size is 1
,08-29 10:23:47.115  3178  3282 D BtGatt.ScanManager: delete FilterIndex - 3
08-29 10:23:47.115  1946  2155 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 10:23:47.125  3178  3277 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 10:23:47.125  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:23:47.125  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:23:47.125  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 10:23:47.125  1946  2170 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-29 10:23:47.125  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:23:47.125  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 10:23:47.135  3178  3274 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 10:23:47.135  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.135  3178  3282 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:23:47.135  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:47.135  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:23:47.135  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:23:47.135  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:23:47.135  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:23:47.135  3178  3274 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 10:23:47.135  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.135  3178  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 10:23:47.135  3178  3274 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 10:23:47.135  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.135  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.135  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.135  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:23:47.135  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.135  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.135  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.135  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.135  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.135  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.135  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.135  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:47.135  6778  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 10:23:47.145  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:47.145  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:47.155  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.155  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:47.155  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:23:47.155  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:23:47.155  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:23:47.155  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:47.155  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:23:47.155  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.155  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:23:47.165  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.165  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:23:47.165  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:23:47.165  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:23:47.165  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:23:47.165  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:23:47.175  3178  3277 D BtGatt.GattService: registerClient() - UUID=0ba4c181-c2c4-4a6c-acac-b75ef17394d4
,08-29 10:23:47.215  3178  3274 D BtGatt.GattService: onClientRegistered() - UUID=0ba4c181-c2c4-4a6c-acac-b75ef17394d4, clientIf=6
,08-29 10:23:47.215  6778  6824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 10:23:47.215  3178  3196 D BtGatt.GattService: start scan with filters
,08-29 10:23:47.215  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:23:47.215  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:23:47.215  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:23:47.215  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:23:47.215  3178  3282 D BtGatt.ScanManager: handling starting scan
,08-29 10:23:47.225  3178  3274 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 10:23:47.225  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.225  3178  3282 D BtGatt.ScanManager: allow scan with filters
08-29 10:23:47.225  3178  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 10:23:47.225  3178  3282 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 10:23:47.225  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:23:47.225  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:23:47.225  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:23:47.225  3178  3274 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 10:23:47.225  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.225  3178  3282 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:23:47.225  3178  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 10:23:47.225  3178  3274 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 10:23:47.225  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.225  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:23:47.225  3178  3274 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 10:23:47.225  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.235  6778  6834 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:23:47.245  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.245  6778  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:23:47.245  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.245  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:23:47.245  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.245  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:23:47.245  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:23:47.245  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:23:47.245  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:23:47.245  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:47.245  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:23:47.245  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:23:47.245  3178  3199 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:23:47.245  3178  3282 D BtGatt.ScanManager: filter size is 1
,08-29 10:23:47.245  3178  3282 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 10:23:47.245  3178  3274 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 10:23:47.245  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.255  3178  3282 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:23:47.255  3178  3277 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 10:23:47.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:23:47.255  3178  3274 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 10:23:47.255  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.255  3178  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 10:23:47.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 10:23:47.255  3178  3274 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 10:23:47.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:23:47.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:23:47.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 10:23:47.255  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:47.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 10:23:47.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:23:47.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:23:47.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:23:47.265  6864  6873 I qtaguid : Untagging socket 30
,08-29 10:23:47.265  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.265  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:23:47.265  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.265  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.265  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.265  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.265  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.265  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.265  6778  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 10:23:47.265  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:47.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:47.275  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:47.275  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.275  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:47.275  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:23:47.275  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:23:47.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:23:47.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:23:47.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:23:47.285  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.285  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:23:47.285  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.285  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:23:47.295  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:23:47.295  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:23:47.295  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 10:23:47.295  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:23:47.295  1946  2170 I art     : Explicit concurrent mark sweep GC freed 73175(3MB) AllocSpace objects, 8(320KB) LOS objects, 39% free, 11MB/18MB, paused 1.409ms total 83.264ms
,08-29 10:23:47.305  3178  3362 D BtGatt.GattService: registerClient() - UUID=749f6d96-f893-4777-adf4-cb38ea3c2543
,08-29 10:23:47.315  1946  1959 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c14a2e8)
,08-29 10:23:47.345  3178  3274 D BtGatt.GattService: onClientRegistered() - UUID=749f6d96-f893-4777-adf4-cb38ea3c2543, clientIf=6
,08-29 10:23:47.345  6778  6824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 10:23:47.345  3178  3196 D BtGatt.GattService: start scan with filters
,08-29 10:23:47.345  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:23:47.345  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:23:47.345  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:23:47.345  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:23:47.355  3178  3282 D BtGatt.ScanManager: handling starting scan
,08-29 10:23:47.365  3178  3274 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 10:23:47.365  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.365  3178  3282 D BtGatt.ScanManager: allow scan with filters
08-29 10:23:47.365  3178  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 10:23:47.365  3178  3282 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 10:23:47.365  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:23:47.365  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:23:47.365  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:23:47.365  3178  3274 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 10:23:47.365  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.365  3178  3282 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:23:47.365  3178  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 10:23:47.365  3178  3274 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 10:23:47.365  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.375  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:23:47.375  3178  3274 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 10:23:47.375  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.375  6778  6834 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 10:23:47.375  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:47.375  6778  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:23:47.375  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.375  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:23:47.375  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.375  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:23:47.375  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:23:47.375  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:23:47.375  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:23:47.375  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:47.375  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:23:47.375  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:23:47.375  3178  3362 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:23:47.375  3178  3282 D BtGatt.ScanManager: filter size is 1
,08-29 10:23:47.385  3178  3196 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 10:23:47.385  3178  3282 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:23:47.385  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:23:47.385  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 10:23:47.385  3178  3274 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 10:23:47.385  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.385  3178  3282 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:23:47.385  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:23:47.385  3178  3274 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 10:23:47.385  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.385  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.385  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:47.385  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.385  6778  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 10:23:47.385  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.385  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.385  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.385  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:23:47.385  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.385  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.385  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.385  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.385  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.385  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.395  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:23:47.395  3178  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.395  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.395  6778  6834 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 10:23:47.395  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:47.395  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.395  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.395  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.395  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.395  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.395  3178  3274 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.395  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.395  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.395  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.395  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.395  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.395  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.395  3178  3274 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.395  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.395  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 10:23:47.395  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.395  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.395  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.395  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.395  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.395  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.395  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.395  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.395  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.395  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:47.395  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.395  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.395  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.405  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.405  6778  6834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 10:23:47.405  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:23:47.405  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.405  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.405  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.405  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.405  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.405  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.405  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.405  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.405  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.405  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.405  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.405  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.405  6778  6834 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 10:23:47.405  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.405  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.405  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.405  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.405  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.405  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.405  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.405  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.405  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.405  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.405  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.405  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.405  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 10:23:47.405  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 10:23:47.405  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:23:47.405  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 10:23:47.405  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 10:23:47.405  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.415  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.415  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.415  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.415  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.415  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.415  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.415  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.415  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.415  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.415  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.415  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.415  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.415  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.415  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.415  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.415  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.415  6778  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:47.415  6778  6834 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 10:23:47.415  6778  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 10:23:47.415  6778  6834 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 10:23:47.415  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 10:23:47.415  6778  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 10:23:47.415  6778  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:23:47.415  6778  6834 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 10:23:47.415  6778  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:47.415  6778  6834 W i,o.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:23:47.415  6778  6834 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 10:23:47.415  6778  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:47.415  6778  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 10:23:47.415  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 10:23:47.425  1018  1456 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 10:23:47.425  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 10:23:47.425  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:47.425  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:47.425  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:47.425  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 10:23:47.425  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 10:23:47.425  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 10:23:47.435  6778  6834 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 10:23:47.435  6778  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 10:23:47.435  6778  6834 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 10:23:47.435  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.435  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.435  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.435  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 10:23:47.435  6778  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1330)
,08-29 10:23:47.435  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.435  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.435  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.435  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.435  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.435  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.435  6778  6834 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 10:23:47.435  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.435  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.435  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.435  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.435  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.435  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.435  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.435  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.435  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.435  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.435  6778  6895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1330
,08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.435  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.435  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.445  6778  6834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-29 10:23:47.445  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.445  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.445  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.445  6778  6894 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 10:23:47.445  6778  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:23:47.445  6778  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:23:47.445  6778  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55,
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:23:47.445  6778  6834 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 10:23:47.445  6778  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 10:23:47.445  6778  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-29 10:23:47.445  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.445  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.445  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
,08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
,08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.445  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.445  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.445  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.445  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.445  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:23:47.445  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.445  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.445  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.455  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.455  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.455  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.455  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.455  6778  6894 D BluetoothSocket: connect(): myUserId = 0
08-29 10:23:47.455  6778  6894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 10:23:47.455  3178  3362 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.455  6778  6894 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-29 10:23:47.455  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.455  6778  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 10:23:47.455  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.455  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:23:47.465  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.465  6778  6778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 10:23:47.465  6778  6778 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:23:47.465  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.465  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.465  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:23:47.465  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:23:47.465  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.465  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.465  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.465  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.465  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.465  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.465  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.465  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.465  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.465  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.465  6778  6896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 10:23:47.465  6778  6896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 10:23:47.465  6778  6834 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 10:23:47.465  6778  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 10:23:47.465  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 10:23:47.465  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.465  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.465  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.465  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.465  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.465  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.465  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.465  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.465  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.465  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.465  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.465  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.475  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.475  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.475  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:47.475  6778  6778 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:23:47.475  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.475  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.475  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.475  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.475  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.475  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.475  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.475  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.475  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.475  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.475  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:23:47.475  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:23:47.475  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:23:47.475  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.475  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.475  6778  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde51b0 not in the list
08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.475  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
08-29 10:23:47.475  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:23:47.475  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.475  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:23:47.475  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:23:47.475  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:23:47.475  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:23:47.475  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac9829 not in the list
,08-29 10:23:47.475  6778  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-29 10:23:47.475  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:23:47.475  6778  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 10:23:47.475  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 10:23:47.475  6778  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 10:23:47.475  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 10:23:47.485  6778  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:23:47.485  6778  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 10:23:47.485  6778  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing,
08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 10:23:47.485  6778  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 10:23:47.485  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:23:47.485  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c817ce3 added. We now have 2 listener(s)
08-29 10:23:47.485  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:23:47.485  6778  6834 D BluetoothAdapter: enable()
,08-29 10:23:47.485  6778  6834 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 10:23:47.495  1018  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 10:23:47.495  1018  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 10:23:47.495  1018  1491 D SecContentProvider2: mCursor = null
,08-29 10:23:47.495  1018  1491 D WifiService: setWifiEnabled: true pid=6778, uid=10171
,08-29 10:23:47.495  1018  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 10:23:47.495  1018  1491 W WifiService: Failed getting userId using ActivityManagerNative
08-29 10:23:47.495  1018  1491 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 10:23:47.495  1018  1491 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 10:23:47.495  1018  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 10:23:47.495  1018  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 10:23:47.495  1018  1491 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 10:23:47.495  1018  1491 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 10:23:47.495  1018  1491 D SettingsProvider: name = wifi_on
,08-29 10:23:47.495  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:23:47.495  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c186e0 added. We now have 3 listener(s)
08-29 10:23:47.495  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:23:47.505  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:23:47.505  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27bedd99 added. We now have 4 listener(s)
08-29 10:23:47.505  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:23:47.505  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:23:47.505  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@111f285e added. We now have 5 listener(s)
08-29 10:23:47.505  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:23:47.515  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 10:23:47.515  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 10:23:47.515  1018  1030 D SecContentProvider2: mCursor = null
,08-29 10:23:47.515  1018  1030 D WifiService: setWifiEnabled: false pid=6778, uid=10171
,08-29 10:23:47.515  1018  1030 D SettingsProvider: name = wifi_on
,08-29 10:23:47.515  6778  6834 D BluetoothAdapter: disable()
08-29 10:23:47.525  1018  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 10:23:47.525  1018  1319 D SettingsProvider: name = bluetooth_on
08-29 10:23:47.525  1357  1357 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 10:23:47.525  1357  1357 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-29 10:23:47.535  1357  1357 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-29 10:23:47.535  1357  1357 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 10:23:47.535  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:23:47.555  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:23:47.555  3178  3271 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-29 10:23:47.555  3178  3271 D BluetoothAdapterProperties: Setting state to 13
08-29 10:23:47.555  3178  3271 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 10:23:47.555  3178  3271 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 10:23:47.555  3178  3271 D BluetoothAdapterService: updateAdapterState state is 13
,08-29 10:23:47.555  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:47.555  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 10:23:47.565  1018  1127 E WifiNative-wlan0: do suspend true
,08-29 10:23:47.565  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:47.565  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:47.565  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:47.565  3178  3178 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-29 10:23:47.565  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:47.565  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:47.565  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:47.565  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.565  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:23:47.565  3178  3178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e94d72f, channel: 19, state: LISTENING
,08-29 10:23:47.565  3178  3178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e94d72f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4c11837, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c4a213cmSocket: android.net.LocalSocket@12189ec5 impl:android.net.LocalSocketImpl@639d01a fd:FileDescriptor[74]
08-29 10:23:47.565  3178  3178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@12189ec5 impl:android.net.LocalSocketImpl@639d01a fd:FileDescriptor[74]
,08-29 10:23:47.565  3178  3271 D BluetoothAdapterService: Autoconnection is available 
,08-29 10:23:47.565  3178  3271 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 10:23:47.565  3178  3271 D BluetoothAdapterService: terminating service from this receiver
,08-29 10:23:47.575  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:23:47.575  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:47.575  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-29 10:23:47.575  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:47.575  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:23:47.575  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.585  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 10:23:47.585  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 10:23:47.585  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:23:47.595  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:23:47.595  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:47.595  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-29 10:23:47.595  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 10:23:47.595  1884  1884 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 10:23:47.595  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:47.605  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 10:23:47.605  1018  1454 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 10:23:47.605  3178  3178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1221b74b, channel: 5, state: LISTENING
08-29 10:23:47.605  3178  3178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1221b74b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d2241a4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d361528mSocket: android.net.LocalSocket@1f696241 impl:android.net.LocalSocketImpl@3b14d3e6 fd:FileDescriptor[76]
08-29 10:23:47.605  3178  3178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f696241 impl:android.net.LocalSocketImpl@3b14d3e6 fd:FileDescriptor[76]
08-29 10:23:47.605  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:47.605  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:47.605  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:47.605  3178  3178 I BtOppRfcommListener: stopping Accept Thread
08-29 10:23:47.605  3178  3178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a527d27, channel: 12, state: LISTENING
08-29 10:23:47.605  3178  3178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a527d27, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1afb10e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a6b5bd4mSocket: android.net.LocalSocket@2fa8e17d impl:android.net.LocalSocketImpl@234a4872 fd:FileDescriptor[79]
08-29 10:23:47.605  3178  3178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2fa8e17d impl:android.net.LocalSocketImpl@234a4872 fd:FileDescriptor[79]
,08-29 10:23:47.605  3178  3271 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 10:23:47.605  3178  3271 D BluetoothAdapterProperties: mDiscovering is false
08-29 10:23:47.605  3178  5102 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 10:23:47.605  1018  1500 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:23:47.605  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 10:23:47.605  3178  3271 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 10:23:47.605  3178  5102 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 10:23:47.605  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 10:23:47.605  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:23:47.605  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:47.605  1018  1208 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 10:23:47.615  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 10:23:47.615  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:47.615  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:23:47.615  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:47.615  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:47.615  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:47.615  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.625  3178  3274 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 10:23:47.625  3178  3274 D BluetoothAdapterProperties: Scan Mode:20
,08-29 10:23:47.625  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.625  3178  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 10:23:47.625  3178  3271 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 10:23:47.625  3178  3271 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-29 10:23:47.625  3178  3271 E bt-btif : cmd socket is not created
,08-29 10:23:47.625  6778  6894 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f68310c, channel: -1, state: INIT
08-29 10:23:47.625  6778  6894 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1f68310c, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1996ba55, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4b16c6amSocket: android.net.LocalSocket@128fa55b impl:android.net.LocalSocketImpl@2aed51f8 fd:FileDescriptor[105]
08-29 10:23:47.625  6778  6894 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@128fa55b impl:android.net.LocalSocketImpl@2aed51f8 fd:FileDescriptor[105]
08-29 10:23:47.625  6778  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1330)
,08-29 10:23:47.635  3178  3295 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-29 10:23:47.635  3178  3295 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 10:23:47.635  3178  3271 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 10:23:47.635  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:23:47.635  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:47.635  3178  3178 V BluetoothOppManager: cleanUp...
08-29 10:23:47.635  1018  1500 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 10:23:47.635  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 10:23:47.635  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:47.635  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:47.635  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 10:23:47.645  3178  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 10:23:47.645  3178  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:47.645  3178  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 10:23:47.645  3066  3066 D BluetoothPbap: Proxy object disconnected
,08-29 10:23:47.645  3066  3066 D PbapServerProfile: Bluetooth service disconnected
,08-29 10:23:47.655  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:23:47.655  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 10:23:47.665  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:47.665  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 10:23:47.665  1018  1319 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 10:23:47.665  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:47.665  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:47.665  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:47.665  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:47.675  6904  6904 E Zygote  : MountEmulatedStorage()
08-29 10:23:47.675  6904  6904 I libpersona: KNOX_SDCARD checking this for 10055
08-29 10:23:47.675  6904  6904 E Zygote  : v2
08-29 10:23:47.675  6904  6904 I libpersona: KNOX_SDCARD not a persona
08-29 10:23:47.675  6904  6904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:23:47.675  1018  1319 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6904 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 10:23:47.685  6904  6904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:47.685  6904  6904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:47.715  6904  6904 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:47.715  6904  6904 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:47.745  6913  6913 I dex2oat : ----------------------------------------------------
08-29 10:23:47.745  6913  6913 I dex2oat : <SS>: S T A R T I N G . . .
08-29 10:23:47.745  6913  6913 I dex2oat : <SS>: Zip is absent. Canceled.
,08-29 10:23:47.745  6913  6913 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 10:23:47.765  6904  6904 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 10:23:47.795  6913  6913 I dex2oat : dex2oat took 47.721ms (threads: 4)
,08-29 10:23:47.805  6904  6904 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-29 10:23:47.805  6904  6904 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
08-29 10:23:47.805  6904  6904 D UserAnalysis: Create SecureDbHelper
,08-29 10:23:47.805  6864  6873 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-29 10:23:47.805  6864  6873 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 10:23:47.805  6864  6873 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 10:23:47.805  6864  6873 I Adreno-EGL: Local Branch: 
08-29 10:23:47.805  6864  6873 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 10:23:47.805  6864  6873 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 10:23:47.805  6864  6873 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 10:23:47.815  6904  6904 D IntelligenceServiceApplication: onCreate()
,08-29 10:23:47.815  1018  1208 I ActivityManager: Killing 6481:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-29 10:23:47.825  1018  1208 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 10:23:47.825  6904  6904 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 10:23:47.825  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:47.825  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:47.825  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:47.825  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:47.835  3178  3295 W bt-l2cap: HC lib lpm enable=0 return 0
,08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:47.835  3178  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:23:47.835  3178  3352 I bt_userial_mct: exiting userial_read_thread
08-29 10:23:47.835  3178  3295 W bt-btif : ag scb idx 1 not allocated
08-29 10:23:47.835  3178  3352 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 10:23:47.835  3178  3295 W bt-btif : ag scb idx 2 not allocated
,08-29 10:23:47.835  3178  3295 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 10:23:47.835  3178  3274 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 10:23:47.835  3178  3298 I bt_vendor: hw_epilog_process
08-29 10:23:47.835  3178  3274 D bt_userial_mct: userial_close
,08-29 10:23:47.835  3178  3274 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 10:23:47.845  6927  6927 E Zygote  : MountEmulatedStorage()
08-29 10:23:47.845  6927  6927 E Zygote  : v2
08-29 10:23:47.845  6927  6927 I libpersona: KNOX_SDCARD checking this for 10105
08-29 10:23:47.845  6927  6927 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:47.845  6927  6927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:47.845  6927  6927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:47.845  1018  1208 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6927 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 10:23:47.845  6927  6927 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 10:23:47.845  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-29 10:23:47.845  6904  6904 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 10:23:47.855  6904  6904 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 10:23:47.865  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:47.865  6927  6927 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:47.905  6864  6873 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 10:23:47.905  6864  6873 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 10:23:47.905  6864  6873 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 10:23:47.905  6864  6873 I Adreno-EGL: Local Branch: 
08-29 10:23:47.905  6864  6873 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 10:23:47.905  6864  6873 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 10:23:47.905  6864  6873 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 10:23:47.945  6864  6873 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 10:23:47.945  6864  6873 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 10:23:47.945  6864  6873 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 10:23:47.945  6864  6873 I Adreno-EGL: Local Branch: 
08-29 10:23:47.945  6864  6873 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 10:23:47.945  6864  6873 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 10:23:47.945  6864  6873 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 10:23:47.965  6778  6778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 10:23:47.975   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 10:23:47.975   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:47.985  6927  6948 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 10:23:47.995   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 10:23:47.995   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:47.995  6927  6948 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 10:23:48.095  3178  3274 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 10:23:48.095  3178  3274 I bt_vendor: bluetooth satus is on
08-29 10:23:48.095  3178  3274 I bt_vendor: bt-vendor : resetting BT status
08-29 10:23:48.095  3178  3274 I bt_vendor: Starting hciattach daemon
08-29 10:23:48.095  3178  3274 I bt_vendor: try to set false
,08-29 10:23:48.095  3178  3274 I bt_vendor: Starting hciattach daemon
08-29 10:23:48.095  3178  3274 I bt_vendor: try to set false
,08-29 10:23:48.095  3178  3274 I bt_vendor: cleanup
,08-29 10:23:48.095  3178  3295 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-29 10:23:48.095  3178  3274 I GKI_LINUX: GKI_exit_task 0 done
,08-29 10:23:48.095  3178  3274 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-29 10:23:48.095  3178  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 10:23:48.095  3178  3271 D BtConfig.SecureMode: isSecureModeOn:false
08-29 10:23:48.095  3178  3271 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-29 10:23:48.095  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 10:23:48.095  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 10:23:48.095  3178  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 10:23:48.095  1018  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:48.095  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.105  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.105  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.105  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.105  3178  3178 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 10:23:48.105  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 10:23:48.105  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 10:23:48.105  3178  3178 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:23:48.105  3178  3178 D BtGatt.GattService: stop()
08-29 10:23:48.105  3178  3178 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 10:23:48.105  3178  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 10:23:48.105  1018  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:48.105  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.105  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.105  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.105  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.105  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:48.105  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
08-29 10:23:48.105  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:48.105  3178  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:48.105  1018  1454 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:48.105  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.105  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.105  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.105  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.105  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 10:23:48.105  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 10:23:48.115  3178  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 10:23:48.115  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:48.115  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.115  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:48.115  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.115  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.115  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 10:23:48.115  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 10:23:48.115  3178  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 10:23:48.115  1018  1208 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:48.115  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.115  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.115  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:23:48.115  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.115  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 10:23:48.115  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 10:23:48.115  3178  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 10:23:48.115  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:48.115  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.115  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.115  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:23:48.125  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.125  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 10:23:48.125  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 10:23:48.125  3178  3271 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 10:23:48.125  1018  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:48.125  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.125  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:48.125  1018  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.125  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.125  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-29 10:23:48.125  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 10:23:48.125  3178  3271 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 10:23:48.125  1018  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:48.125  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.125  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.125  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.125  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:48.125  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 10:23:48.125  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 10:23:48.135  3178  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:23:48.135  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-29 10:23:48.135  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:48.135  3178  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-29 10:23:48.135  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 10:23:48.135  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 10:23:48.135  3178  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 10:23:48.135  3178  3271 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 10:23:48.135  3178  3271 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 10:23:48.135  3178  3271 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-29 10:23:48.135  3178  3271 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 10:23:48.135  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-29 10:23:48.135  3178  3178 D HeadsetService: Received stop request...Stopping profile...
,08-29 10:23:48.135  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:48.135  3178  3178 D A2dpService: Received stop request...Stopping profile...
,08-29 10:23:48.135  3066  3066 D HeadsetProfile: Bluetooth service disconnected
08-29 10:23:48.135  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 10:23:48.135  3178  3286 D A2dpStateMachine: Exit Disconnected: -1
,08-29 10:23:48.145  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:48.145  3066  3066 D BluetoothA2dp: Proxy object disconnected
08-29 10:23:48.145  3066  3066 D A2dpProfile: Bluetooth service disconnected
,08-29 10:23:48.145  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-29 10:23:48.145  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 10:23:48.145  3178  3178 D HidService: Received stop request...Stopping profile...
,08-29 10:23:48.145  3178  3178 D HidService: Stopping Bluetooth HidService
08-29 10:23:48.145  3178  3178 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 10:23:48.145  3178  3178 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 10:23:48.145  3178  3178 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 10:23:48.145  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:48.145  3178  3178 D HealthService: Received stop request...Stopping profile...
,08-29 10:23:48.145  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:48.145  3066  3066 D BluetoothInputDevice: Proxy object disconnected
08-29 10:23:48.145  3066  3066 D HidProfile: Bluetooth service disconnected
,08-29 10:23:48.145  3178  3178 D PanService: Received stop request...Stopping profile...
,08-29 10:23:48.145  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:48.145  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 10:23:48.155  3178  3178 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 10:23:48.155  3066  3066 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:23:48.155  3066  3066 D PanProfile: Bluetooth service disconnected
,08-29 10:23:48.155  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:48.155  3178  3178 D SapService: Received stop request...Stopping profile...
08-29 10:23:48.155  3178  3178 D SapService: Stopping Bluetooth SapService
08-29 10:23:48.155  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:48.155  3066  3066 D BluetoothMap: Proxy object disconnected
08-29 10:23:48.155  3066  3066 D MapProfile: Bluetooth service disconnected
,08-29 10:23:48.155  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 10:23:48.155  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 10:23:48.155  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 10:23:48.165  3178  3178 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 10:23:48.165  3178  3178 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 10:23:48.165  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-29 10:23:48.165  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 10:23:48.165  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 10:23:48.165  3178  3178 D BluetoothA2dp: Proxy object disconnected
08-29 10:23:48.165  3178  3178 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-29 10:23:48.165  3178  3288 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-29 10:23:48.165  3178  3178 I GKI_LINUX: GKI_exit_task 2 done
08-29 10:23:48.165  3178  3178 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 10:23:48.165  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 10:23:48.165  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 10:23:48.165  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 10:23:48.165  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 10:23:48.165  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 10:23:48.165  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 10:23:48.165  3178  3178 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 10:23:48.165  3178  3178 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 10:23:48.165  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 10:23:48.165  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 10:23:48.165  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 10:23:48.165  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 10:23:48.165  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 10:23:48.165  3178  3178 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-29 10:23:48.165  3178  3178 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:23:48.165  3178  3178 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 10:23:48.165  3178  3178 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-29 10:23:48.165  3178  3178 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 10:23:48.165  3178  3178 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-29 10:23:48.165  3178  3271 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 10:23:48.165  3178  3271 D BluetoothAdapterProperties: Setting state to 10
08-29 10:23:48.165  3178  3271 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 10:23:48.165  3178  3271 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 10:23:48.165  3178  3271 D BluetoothAdapterService: updateAdapterState state is 10
08-29 10:23:48.165  3178  3271 D BluetoothAdapterService: Autoconnection is available 
08-29 10:23:48.165  3178  3271 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 10:23:48.165  3178  3271 I BluetoothAdapterState: Entering OffState
08-29 10:23:48.165  1946  2159 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.165  1946  2159 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.175  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 10:23:48.175  3066  3066 D SapProfile: Bluetooth service disconnected
08-29 10:23:48.175  3178  3196 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:23:48.175  3066  3075 D BluetoothMap: onBluetoothStateChange: up=false
08-29 10:23:48.175  1177  1204 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.175  1177  1204 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.175  3066  6900 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.175  3066  6900 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.175  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:23:48.185  3066  3074 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 10:23:48.185  6778  6788 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.185  6778  6788 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.185  6778  6788 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 10:23:48.185  6778  6788 D BluetoothLeAdvertiser: Exit stop advertising
08-29 10:23:48.185  6778  6788 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 10:23:48.185  6778  6788 D BluetoothLeScanner: Exiting stopAllScan
08-29 10:23:48.185  1444  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.185  1444  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.185  3066  3075 D Bluetoothsap: onBluetoothStateChange: up=false
08-29 10:23:48.185  3066  3075 D Bluetoothsap: Unbinding service...
08-29 10:23:48.185  1460  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.185  1460  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.185  1478  1492 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.185  1478  1492 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.185  3066  3074 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:23:48.185  3178  3277 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.195  3178  3277 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.195  3066  3075 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:23:48.195  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:23:48.195  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:23:48.195  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 10:23:48.195  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 10:23:48.205  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:48.205  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-29 10:23:48.205  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-29 10:23:48.205  1177  1177 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
08-29 10:23:48.205  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 10:23:48.205  1177  1778 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
08-29 10:23:48.205  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:48.205  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-29 10:23:48.205  1177  1778 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
08-29 10:23:48.205  1177  1177 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
08-29 10:23:48.205  1177  1177 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
08-29 10:23:48.205  1884  1884 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 10:23:48.205  1018  1319 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 10:23:48.205  1018  1319 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 10:23:48.215  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 10:23:48.215  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 10:23:48.215  1946  2161 D BluetoothAdapter: 1035973801: getState() :  mService = null. Returning STATE_OFF
08-29 10:23:48.215  1946  2161 D BluetoothAdapter: 1035973801: getState() :  mService = null. Returning STATE_OFF
08-29 10:23:48.215  1018  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:23:48.215  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-29 10:23:48.215  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.215  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:48.215  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 10:23:48.215  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:48.215  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:48.215  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:48.235  3178  3274 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 10:23:48.235  3178  3178 I GKI_LINUX: GKI_exit_task 1 done
08-29 10:23:48.235  3178  3178 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 10:23:48.235  3178  3178 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 10:23:48.235  3178  3178 I art     : System.exit called, status: 0
08-29 10:23:48.235  3178  3178 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 10:23:48.265  1357  1357 I wpa_supplicant: nl80211: Received scan results (5 BSSes)
,08-29 10:23:48.265  1018  1126 D WifiP2pService: InactiveState{ what=147461 }
,08-29 10:23:48.265  1018  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
08-29 10:23:48.265  1018  1126 D WifiP2pService: DefaultState{ what=147461 }
,08-29 10:23:48.265  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-29 10:23:48.265  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 10:23:48.265   278   990 D CommandListener: Clearing all IP addresses on wlan0,
,08-29 10:23:48.275  1946  3020 V NativeCrypto: Read error: ssl=0xb75766b8: I/O error during system call, Connection timed out
,08-29 10:23:48.275  1946  3020 V NativeCrypto: SSL shutdown failed: ssl=0xb75766b8: I/O error during system call, Broken pipe,
,08-29 10:23:48.275  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-29 10:23:48.275  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:23:48.275  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-29 10:23:48.275  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-29 10:23:48.285  1946  3020 E GCM     : Wifi connection closed with errorCode 20
08-29 10:23:48.285  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
,08-29 10:23:48.285  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:48.285  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 10:23:48.285  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
08-29 10:23:48.285  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 10:23:48.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:48.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:48.285  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 10:23:48.295  1018  1500 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011,
,08-29 10:23:48.305  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,08-29 10:23:48.305  1018  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:23:48.315  1018  1018 D RttService: SCAN_AVAILABLE : 1
,08-29 10:23:48.315  1018  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:23:48.315  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:23:48.315  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:23:48.315  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-29 10:23:48.315  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:23:48.315  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:48.315  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:48.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:48.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.315  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 10:23:48.315  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-29 10:23:48.315  1018  1757 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:23:48.315  1018  1757 I qtaguid : Tagging socket 322 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=328 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=311 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=310 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=309 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=307 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=286 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=286 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:23:48.325  6927  6927 D StrictMode: StrictMode policy violation; ~duration=285 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:48.325  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:48.325  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-29 10:23:48.335  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 10:23:48.335  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 10:23:48.335  1018  1454 I ActivityManager: Process com.android.bluetooth (pid 3178)(adj 0) has died(27,713)
08-29 10:23:48.345  1018  1516 I ActivityManager: Killing 6381:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-29 10:23:48.345  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 10:23:48.345  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 10:23:48.345  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 10:23:48.345  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 10:23:48.345  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:23:48.345  1018  1048 D WifiDisplayController: disconnect
08-29 10:23:48.345  1018  1048 D WifiDisplayController: updateConnection
08-29 10:23:48.345  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:23:48.345  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 10:23:48.355  1018  1757 I qtaguid : Untagging socket 322
08-29 10:23:48.355  1018  1757 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:23:48.365  1018  1126 D WifiP2pService: P2pDisablingState
08-29 10:23:48.365  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-29 10:23:48.365  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 10:23:48.365  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-29 10:23:48.365  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 10:23:48.365  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 10:23:48.365  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 10:23:48.365  1018  1126 D WifiP2pService: p2p socket connection lost
08-29 10:23:48.375  1018  1127 E WifiNative-wlan0: do suspend true
08-29 10:23:48.375  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 10:23:48.375  1018  1126 D WifiP2pService: P2pDisabledState
08-29 10:23:48.375  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-29 10:23:48.375  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
08-29 10:23:48.385   278   990 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:23:48.385  1018  1456 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 10:23:48.385   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 10:23:48.385  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 10:23:48.385   278   984 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-29 10:23:48.385  1018  1129 V NetworkStats: updateIfacesLocked()
08-29 10:23:48.385  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:48.385  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:23:48.385  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:23:48.385  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 10:23:48.385  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 10:23:48.385  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-29 10:23:48.385  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 10:23:48.385  1018  1129 V NetworkStats: performPollLocked() took 4ms
08-29 10:23:48.385  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:48.385  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:48.385  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:48.385  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.385  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.385  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.385  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.395  1357  1357 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-29 10:23:48.395  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 10:23:48.395  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:23:48.395  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:48.395  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:48.395  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.395  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.395  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.395  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:48.405  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-29 10:23:48.405  1018  1500 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 10:23:48.405  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-29 10:23:48.405  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:48.405  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:48.405  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.405  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.405  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 10:23:48.405  1177  1766 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 10:23:48.405  1018  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 10:23:48.405  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 10:23:48.405  1018  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 10:23:48.405  1478  1478 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 10:23:48.405  1478  1478 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 10:23:48.405  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 10:23:48.415  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,08-29 10:23:48.415  1018  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-29 10:23:48.415  4663  6842 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-29 10:23:48.415  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 10:23:48.415  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 10:23:48.415  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:48.415  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:23:48.425  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 10:23:48.425  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-29 10:23:48.425  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.425  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.425  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.425  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:48.425  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:48.425  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-29 10:23:48.425  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:48.425  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 10:23:48.435  1177  1177 D HotspotTile: onReceive : 0, 0
,08-29 10:23:48.435  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:23:48.435  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:48.435  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:23:48.435  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:48.435  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:23:48.435  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-29 10:23:48.435  1018  1131 D Tethering: MasterInitialState.processMessage what=3
08-29 10:23:48.445  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:48.445  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:23:48.445  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:48.445  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:23:48.445  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
08-29 10:23:48.445  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:48.445  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit(),
08-29 10:23:48.445  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 10:23:48.445  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:23:48.445  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:23:48.445  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-29 10:23:48.445  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:48.445  1018  1124 V NetworkStats: updateIfacesLocked()
08-29 10:23:48.445  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-29 10:23:48.445  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 10:23:48.445  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:23:48.445  1018  1124 V NetworkStats: performPollLocked() took 3ms
08-29 10:23:48.445  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:48.445  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-29 10:23:48.445  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 10:23:48.445  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 10:23:48.445  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-29 10:23:48.445  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 10:23:48.445  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 10:23:48.445  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 10:23:48.455  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:48.455  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:48.455  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:48.455  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 10:23:48.455  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 10:23:48.455  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.455  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:48.465  6927  6949 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 10:23:48.465  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:48.465  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 10:23:48.475  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 10:23:48.475  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-29 10:23:48.485  1018  1208 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-29 10:23:48.485  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:48.495  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:48.495  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:48.495  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:48.495  1946  6862 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:23:48.495   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-29 10:23:48.495   278   984 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-29 10:23:48.495  1946  6862 W GLSUser : [AppCertManager] IOException while requesting key: 
,08-29 10:23:48.505  6973  6973 E Zygote  : MountEmulatedStorage()
08-29 10:23:48.505  6973  6973 E Zygote  : v2
,08-29 10:23:48.505  6973  6973 I libpersona: KNOX_SDCARD checking this for 1002
08-29 10:23:48.505  6973  6973 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:48.505  1018  1208 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6973 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-29 10:23:48.505  6973  6973 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:48.505  6973  6973 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:48.505  6973  6973 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 10:23:48.515  1018  1516 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:48.515  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.515  1018  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:48.515  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-29 10:23:48.525  1357  1357 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 10:23:48.545  6973  6973 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:48.545  6973  6973 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:48.565  1357  1357 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 10:23:48.565  6973  6973 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-29 10:23:48.565  6973  6973 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 10:23:48.565  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 10:23:48.565  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:23:48.565  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-29 10:23:48.575  1946  2170 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 10:23:48.575  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.575  1946  2170 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-29 10:23:48.575  1946  2170 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-29 10:23:47.209+0200, stopTime=2016-08-29 10:23:48.588+0200, duration=1379ms
,08-29 10:23:48.575  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.585  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.585  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.585  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.585  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.585  1357  1357 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-29 10:23:48.585  1357  1357 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 10:23:48.585  1357  1357 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 10:23:48.585  1357  1357 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 10:23:48.585  1357  1357 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 10:23:48.585  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.585  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.585  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:48.585  1018  1131 D Tethering: InitialState.processMessage what=4
,08-29 10:23:48.595  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.595  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.595  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:48.595  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.595  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.595  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:48.595  6973  6973 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 10:23:48.595  1018  1131 E Tethering: No numeric data
,08-29 10:23:48.595  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 10:23:48.595  1018  1131 D Tethering: clearTetheredNotification()
,08-29 10:23:48.595  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:23:48.595  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:48.605  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:23:48.605  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 10:23:48.605  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 10:23:48.605  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:23:48.605  1018  1124 V NetworkStats: performPollLocked() took 5ms
08-29 10:23:48.605  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:48.605  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.605  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:48.605  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:48.605  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.605  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.615  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.615  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.615  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.615  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.615  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.615  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.615  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.615  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.625  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.625  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.625  1946  6992 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:23:48.635  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.635  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.635   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 10:23:48.635   278   984 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding GattService
,08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding HeadsetService
08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding A2dpService
08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding HidService
,08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding HealthService
08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding PanService
08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding SapService
,08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-29 10:23:48.635  1946  1946 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding SapClientService
08-29 10:23:48.635  6973  6973 D BtSettings.ProfileConfig: Adding HidDevService,
08-29 10:23:48.635  6973  6973 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 10:23:48.635  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 10:23:48.635  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.635  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.635  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 10:23:48.645  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 10:23:48.645  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 10:23:48.645   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7bf87c8
08-29 10:23:48.645   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-29 10:23:48.645   273   273 I rmt_storage: wakelock acquired: 1, error no: 42,
08-29 10:23:48.645   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1212184440)
,08-29 10:23:48.645  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 10:23:48.645  1478  1478 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 10:23:48.645  1018  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-29 10:23:48.645  1018  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.645  1018  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.645  1018  1499 D SettingsProvider: selectionArgs: false
08-29 10:23:48.645  1018  1499 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.645  1018  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.655  1018  1499 D SettingsProvider: ret = -1
,08-29 10:23:48.655  1018  1208 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 10:23:48.655  1478  1478 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 10:23:48.655  1018  1208 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.655  1018  1208 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.655  1018  1208 D SettingsProvider: selectionArgs: false
,08-29 10:23:48.655  1018  1208 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.655  1018  1208 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.655  1018  1208 D SettingsProvider: ret = -1
08-29 10:23:48.655  1018  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-29 10:23:48.655  1018  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.655  1018  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-29 10:23:48.655  1018  1491 D SettingsProvider: selectionArgs: false
08-29 10:23:48.655  1018  1491 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.655  1018  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.655  1018  1491 D SettingsProvider: ret = -1
08-29 10:23:48.655  1018  1208 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 10:23:48.655  1018  1208 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.655  1018  1208 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.655  1018  1208 D SettingsProvider: selectionArgs: false
08-29 10:23:48.655  1018  1208 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.655  1018  1208 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.655  1018  1208 D SettingsProvider: ret = -1
,08-29 10:23:48.665  1018  1321 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 10:23:48.665  1018  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.665  1018  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.665  1018  1321 D SettingsProvider: selectionArgs: false
08-29 10:23:48.665  1018  1321 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.665  1018  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.665  1018  1321 D SettingsProvider: ret = -1
,08-29 10:23:48.665  1018  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 10:23:48.665  1018  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.665  1018  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.665  1018  1500 D SettingsProvider: selectionArgs: false
08-29 10:23:48.665  1018  1500 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.665  1018  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.665  1018  1500 D SettingsProvider: ret = -1
08-29 10:23:48.665  1018  1456 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-29 10:23:48.665  1018  1456 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.665  1018  1456 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.665  1018  1456 D SettingsProvider: selectionArgs: false
08-29 10:23:48.665  1018  1456 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.665  1018  1456 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.665  1018  1456 D SettingsProvider: ret = -1
08-29 10:23:48.665  1018  1491 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 10:23:48.665  1018  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.665  1018  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.665  1018  1491 D SettingsProvider: selectionArgs: false
08-29 10:23:48.665  1018  1491 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.665  1018  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.665  1018  1491 D SettingsProvider: ret = -1
08-29 10:23:48.665  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:23:48.665  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.665  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.665  1018  1031 D SettingsProvider: selectionArgs: false
08-29 10:23:48.665  1018  1031 D SettingsProvider: selectionArgs: 1002
,08-29 10:23:48.665  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.675  1018  1031 D SettingsProvider: ret = -1
,08-29 10:23:48.675  1018  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:48.675  1018  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.675  1018  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.675  1018  1499 D SettingsProvider: selectionArgs: false
08-29 10:23:48.675  1018  1499 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.675  1018  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.675  1018  1499 D SettingsProvider: ret = -1
08-29 10:23:48.675   283   693 I WVCdm   : CdmEngine::CloseSession
,08-29 10:23:48.675  1018  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-29 10:23:48.675  1018  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.675  1018  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 10:23:48.675  1018  1319 D SettingsProvider: selectionArgs: false
08-29 10:23:48.675  1018  1319 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.675  1018  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.675  1018  1319 D SettingsProvider: ret = -1
08-29 10:23:48.675   283   693 I WVCdm   : L3 Terminate.
,08-29 10:23:48.675  1018  1208 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-29 10:23:48.675  1018  1208 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:48.675  1018  1208 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:48.675  1018  1208 D SettingsProvider: selectionArgs: false
08-29 10:23:48.675  1018  1208 D SettingsProvider: selectionArgs: 1002
08-29 10:23:48.675  1018  1208 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:48.675  1018  1208 D SettingsProvider: ret = -1
,08-29 10:23:48.695  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 10:23:48.695  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:23:48.695  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.695  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.695  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:48.695  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:48.695  1946  7014 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 10:23:48.705  1018  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:48.705  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 10:23:48.705  1018  1500 W ActivityManager: userId = 0, bbcId = -10000,
08-29 10:23:48.705  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:48.705  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:48.705   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-29 10:23:48.705   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-29 10:23:48.705   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1212184440) wakelock released: 1, error no: 0
08-29 10:23:48.705   273   312 I rmt_storage: 
,08-29 10:23:48.705   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7bf87c8
,08-29 10:23:48.715  1018  1208 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:48.715  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:23:48.725  1357  1357 I wpa_supplicant: Blacklist: Clear (all) 
08-29 10:23:48.725  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.725  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:48.725  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:48.725  1602  1602 I Hs20UtilService: Starting #8
08-29 10:23:48.725  1018  1456 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 10:23:48.725  1602  1639 I Hs20UtilService: Message received 5007
,08-29 10:23:48.725  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:48.725  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:48.725  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:48.735  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 10:23:48.735  1946  7014 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-29 10:23:48.735  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 10:23:48.735  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 10:23:48.735  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:23:48.745  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:23:48.745  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 10:23:48.745  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:48.745  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 10:23:48.755  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 10:23:48.755  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 10:23:48.755  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 10:23:48.755  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:23:48.755  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 10:23:48.755  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:48.755  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 10:23:48.755  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:48.755  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:48.755  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:48.755  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:48.765  7015  7015 E Zygote  : MountEmulatedStorage(),
08-29 10:23:48.765  7015  7015 E Zygote  : v2
,08-29 10:23:48.765  7015  7015 I libpersona: KNOX_SDCARD checking this for 10064
08-29 10:23:48.765  7015  7015 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:48.775  1018  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7015 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 10:23:48.775  7015  7015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:48.775  7015  7015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 10:23:48.775  7015  7015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:48.785  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.785  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:48.785  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:48.785  1357  1357 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 10:23:48.795  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 10:23:48.795  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 10:23:48.805  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 10:23:48.805  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 10:23:48.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:48.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 10:23:48.805  7015  7015 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 10:23:48.805  7015  7015 D ActivityThread: Added TimaKeyStore provider
08-29 10:23:48.805  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:48.805  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-29 10:23:48.805  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 10:23:48.805  1018  1030 I art     : Explicit concurrent mark sweep GC freed 47172(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 8.304ms total 168.610ms
,08-29 10:23:48.805  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:48.815  1946  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:23:48.815  1177  1177 D HotspotTile: onReceive : 1, 0
,08-29 10:23:48.815  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:48.815  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:23:48.815  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:48.815  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:23:48.825  7015  7015 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 10:23:48.845  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 10:23:48.845  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 10:23:48.855  1946  2170 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-29 10:23:48.865  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-29 10:23:48.885  7015  7015 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 10:23:48.885  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 10:23:48.885  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:48.885  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:48.885  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:48.885  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:48.895  7030  7030 E Zygote  : MountEmulatedStorage(),
08-29 10:23:48.895  7030  7030 E Zygote  : v2
08-29 10:23:48.895  7030  7030 I libpersona: KNOX_SDCARD checking this for 10065
08-29 10:23:48.895  7030  7030 I libpersona: KNOX_SDCARD not a persona
08-29 10:23:48.895  1018  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7030 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 10:23:48.895  7030  7030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:23:48.895  1018  1031 I ActivityManager: Killing 6512:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-29 10:23:48.905  7030  7030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:48.905  7030  7030 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:48.915  7030  7030 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:48.925  7030  7030 D ActivityThread: Added TimaKeyStore provider,
,08-29 10:23:48.925   324   324 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 30.092ms
,08-29 10:23:48.935  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:23:48.945  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-29 10:23:48.945   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 16.869ms
,08-29 10:23:48.965  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 10:23:48.965   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 654us total 18.305ms
08-29 10:23:48.965  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:48.965  7030  7030 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 10:23:48.975   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:23:48.985  1018  1491 I ActivityManager: Killing 6538:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 10:23:49.005  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.005  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:49.005  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-29 10:23:49.005  1018  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-29 10:23:49.005  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.005  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.005  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.005  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.015  7045  7045 E Zygote  : MountEmulatedStorage(),
08-29 10:23:49.015  7045  7045 E Zygote  : v2
08-29 10:23:49.015  7045  7045 I libpersona: KNOX_SDCARD checking this for 10102
08-29 10:23:49.015  7045  7045 I libpersona: KNOX_SDCARD not a persona,
08-29 10:23:49.015  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-29 10:23:49.015  1018  1491 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7045 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-29 10:23:49.015  7045  7045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.025  7045  7045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:49.025  7045  7045 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 10:23:49.035  7045  7045 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.035  7045  7045 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.065  7045  7045 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 10:23:49.225  7045  7066 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-29 10:23:49.225  7045  7066 I Babel_SMS: MmsConfig.loadMmsSettings
08-29 10:23:49.225  7045  7066 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-29 10:23:49.225  7045  7066 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 10:23:49.275  7045  7066 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-29 10:23:49.275  7045  7066 I Babel_SMS: MmsConfig.loadFromResources
,08-29 10:23:49.275  7045  7066 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 10:23:49.275  7045  7066 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 10:23:49.295  1018  1031 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 10:23:49.295  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-29 10:23:49.295  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.295  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:49.295  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 10:23:49.325  7045  7045 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:23:49.325  1018  1045 D Tethering: interfaceRemoved wlan0
,08-29 10:23:49.325  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 10:23:49.335  7045  7045 I Babel_Crash: startup - clean
,08-29 10:23:49.355  1018  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:49.355  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:23:49.355  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.355  1018  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.355  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:49.355  1602  1602 I Hs20UtilService: Starting #9
,08-29 10:23:49.355  1602  1639 I Hs20UtilService: Message received 5007
,08-29 10:23:49.365  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 10:23:49.365  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 10:23:49.365  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 10:23:49.375  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 10:23:49.375  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:23:49.375  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 10:23:49.375  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:49.375  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 10:23:49.385  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:23:49.385  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.385  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.385  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:49.385  1602  1602 I Hs20UtilService: Starting #10
,08-29 10:23:49.385  1602  1639 I Hs20UtilService: Message received 5011
,08-29 10:23:49.385  7045  7045 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:49.385  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 10:23:49.385  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 10:23:49.385  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
08-29 10:23:49.385  7045  7045 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 10:23:49.385  7045  7045 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 10:23:49.395  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 10:23:49.395  7045  7045 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-29 10:23:49.395  7045  7045 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-29 10:23:49.405  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.405  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.405  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.405  7045  7045 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 10:23:49.405  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.405  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.405  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.405  7045  7045 W AudioCapabilities: Unsupported mime audio/x-ima
,08-29 10:23:49.405  7045  7045 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 10:23:49.405  7045  7045 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 10:23:49.405  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.405  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.405  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.415  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.415  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.415  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.415  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.415  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.415  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.425  7045  7045 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 10:23:49.425  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.425  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:23:49.425  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-29 10:23:49.425  7045  7045 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 10:23:49.425  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.425  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.425  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.435  7045  7045 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 10:23:49.435  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:49.435  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:23:49.435  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.435  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.435  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.435  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.435  7045  7045 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 10:23:49.435  7045  7045 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 10:23:49.445  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.445  7045  7045 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
08-29 10:23:49.445  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.445  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.445  7045  7045 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-29 10:23:49.445  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.445  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.455  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.455  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.455  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.455  7045  7045 W VideoCapabilities: Unsupported mime video/mp43
,08-29 10:23:49.455  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.455  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.455  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 10:23:49.455  1018  1208 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:49.455  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:23:49.455  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.455  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:49.455  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:49.465  7045  7045 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 10:23:49.465  1602  1602 I Hs20UtilService: Starting #11
,08-29 10:23:49.465  1602  1639 I Hs20UtilService: Message received 5011
,08-29 10:23:49.465  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 10:23:49.465  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 10:23:49.465  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
08-29 10:23:49.465  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 10:23:49.465  7045  7045 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 10:23:49.475  1018  1319 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 10:23:49.475  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.475  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.475  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.475  1018  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.485  7069  7069 E Zygote  : MountEmulatedStorage(),
08-29 10:23:49.485  7069  7069 E Zygote  : v2
08-29 10:23:49.485  7069  7069 I libpersona: KNOX_SDCARD checking this for 1000,
08-29 10:23:49.485  7069  7069 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:49.485  7069  7069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:23:49.485  1018  1319 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7069 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 10:23:49.495  7045  7045 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
08-29 10:23:49.495  7069  7069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:49.495  7069  7069 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:49.515  7069  7069 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.515  7069  7069 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.525  7045  7045 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:49.525  7045  7045 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:49.525  1018  1045 D Tethering: interfaceRemoved p2p0
08-29 10:23:49.525  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 10:23:49.525  7045  7045 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:49.535  7045  7045 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 10:23:49.535  1018  1516 I ActivityManager: Killing 6562:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 10:23:49.535  7045  7045 I vclib   : onServiceConnected
,08-29 10:23:49.545  7069  7069 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-29 10:23:49.545  7069  7069 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 10:23:49.545  7069  7069 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 10:23:49.565  7069  7069 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 10:23:49.565  7069  7069 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 10:23:49.565  7069  7069 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-29 10:23:49.565  7069  7069 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:23:49.565  1018  1031 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-29 10:23:49.565  1018  1031 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 10:23:49.565  7069  7084 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 10:23:49.565  1018  1031 I ActivityManager: Killing 6609:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-29 10:23:49.575  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 10:23:49.575  1789  1789 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-29 10:23:49.575  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.575  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.575  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.575  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.585  7086  7086 E Zygote  : MountEmulatedStorage()
,08-29 10:23:49.585  7086  7086 E Zygote  : v2
08-29 10:23:49.585  7086  7086 I libpersona: KNOX_SDCARD checking this for 10121
08-29 10:23:49.585  7086  7086 I libpersona: KNOX_SDCARD not a persona
08-29 10:23:49.585  1018  1043 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7086 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 10:23:49.595  7086  7086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.595  7086  7086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 10:23:49.595  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-29 10:23:49.595  7086  7086 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 10:23:49.595  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.595  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.595  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.595  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.605  7086  7086 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.605  7086  7086 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.615  7098  7098 E Zygote  : MountEmulatedStorage()
08-29 10:23:49.615  7098  7098 E Zygote  : v2
,08-29 10:23:49.615  7098  7098 I libpersona: KNOX_SDCARD checking this for 10031
08-29 10:23:49.615  7098  7098 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:49.615  1018  1031 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7098 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-29 10:23:49.615  7098  7098 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.615  7098  7098 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:49.625  7098  7098 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 10:23:49.625  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 10:23:49.625  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.625  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.625  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.625  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.625  2470  2481 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6,
,08-29 10:23:49.635  7114  7114 E Zygote  : MountEmulatedStorage()
,08-29 10:23:49.635  7114  7114 E Zygote  : v2
08-29 10:23:49.635  7114  7114 I libpersona: KNOX_SDCARD checking this for 10001
08-29 10:23:49.635  7114  7114 I libpersona: KNOX_SDCARD not a persona,
08-29 10:23:49.645  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7114 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 10:23:49.645  7114  7114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.645  7098  7098 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 10:23:49.645  7098  7098 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.645  7114  7114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:49.645  7114  7114 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:49.655  1789  1789 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 10:23:49.655  1789  1789 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 10:23:49.655  1789  1789 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 10:23:49.665  1789  1789 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 10:23:49.665  1789  1789 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 10:23:49.675  1789  1789 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 10:23:49.675  1018  1454 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 10:23:49.675  7086  7086 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 10:23:49.675  7086  7086 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 10:23:49.675  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.675  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.675  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.675  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.675  7086  7086 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 10:23:49.675  7114  7114 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.675  7114  7114 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.695  7131  7131 E Zygote  : MountEmulatedStorage()
,08-29 10:23:49.695  7131  7131 E Zygote  : v2
08-29 10:23:49.695  7131  7131 I libpersona: KNOX_SDCARD checking this for 10077
08-29 10:23:49.695  7131  7131 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:49.695  1018  1454 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7131 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 10:23:49.695  7131  7131 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.695  7086  7086 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:23:49.695  7131  7131 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:49.695  7131  7131 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-29 10:23:49.705  7086  7086 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 10:23:49.705  7086  7086 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 10:23:49.705  1018  1499 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-29 10:23:49.705  7098  7098 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-29 10:23:49.715  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.715  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.715  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.715  1018  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.725  7131  7131 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.725  7131  7131 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.725  7146  7146 E Zygote  : MountEmulatedStorage(),
,08-29 10:23:49.725  7146  7146 E Zygote  : v2
08-29 10:23:49.725  7146  7146 I libpersona: KNOX_SDCARD checking this for 10141
08-29 10:23:49.725  7146  7146 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:49.725  7146  7146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.725  1018  1499 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7146 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
08-29 10:23:49.725  7146  7146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:49.725  7146  7146 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:49.725  1018  1499 I ActivityManager: Killing 6629:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-29 10:23:49.735  1018  1499 I ActivityManager: Killing 6646:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-29 10:23:49.755  7146  7146 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.755  7146  7146 D ActivityThread: Added TimaKeyStore provider
08-29 10:23:49.755  1018  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 10:23:49.755  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.755  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.755  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.755  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.765  2762  7161 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-29 10:23:49.765  2762  7161 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 10:23:49.765  2762  7161 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-29 10:23:49.775  2762  7161 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0,
,08-29 10:23:49.775  2762  7161 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 10:23:49.775  7162  7162 E Zygote  : MountEmulatedStorage()
08-29 10:23:49.775  7162  7162 E Zygote  : v2
08-29 10:23:49.775  7162  7162 I libpersona: KNOX_SDCARD checking this for 10032
08-29 10:23:49.775  7162  7162 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:49.775  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.775  7162  7162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:49.775  1018  1491 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7162 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 10:23:49.775  7162  7162 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 10:23:49.795  7146  7146 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-29 10:23:49.795  7146  7146 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 10:23:49.795  7146  7146 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 10:23:49.795  7146  7146 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 10:23:49.805  7162  7162 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.805  7162  7162 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.855  1018  1319 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:49.865  7162  7177 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-29 10:23:49.865  7162  7177 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 10:23:49.875  1018  1454 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:49.875  7162  7177 D SPPClientService: PushLog.txt file is not deleted.
,08-29 10:23:49.875  7162  7177 D SPPClientService: PushLog.txt file is not deleted.
08-29 10:23:49.875  7162  7177 D SPPClientService: ============PushLog. stop!
,08-29 10:23:49.905  7162  7162 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-29 10:23:49.905  1018  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:49.905  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 10:23:49.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.905  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.915  7185  7185 E Zygote  : MountEmulatedStorage(),
08-29 10:23:49.915  7185  7185 I libpersona: KNOX_SDCARD checking this for 10036
08-29 10:23:49.915  7185  7185 E Zygote  : v2
08-29 10:23:49.915  7185  7185 I libpersona: KNOX_SDCARD not a persona
08-29 10:23:49.915  7185  7185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.925  1018  1030 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7185 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 10:23:49.925  1018  1030 I ActivityManager: Killing 6582:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-29 10:23:49.925  7185  7185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:49.925  1018  1500 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-29 10:23:49.925  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:49.925  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-29 10:23:49.925  1018  1500 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 10:23:49.925  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-29 10:23:49.925  7185  7185 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-29 10:23:49.925  1018  1208 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:49.935   293   293 E SMD     : DCD OFF
,08-29 10:23:49.945  7185  7185 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:49.945  7185  7185 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:49.965  1018  1208 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 10:23:49.965  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.965  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:49.965  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.965  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:49.975  7204  7204 E Zygote  : MountEmulatedStorage(),
08-29 10:23:49.975  7204  7204 E Zygote  : v2
08-29 10:23:49.985  7204  7204 I libpersona: KNOX_SDCARD checking this for 1000,
08-29 10:23:49.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:23:49.985  1018  1208 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7204 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 10:23:49.985  7204  7204 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:49.985  7204  7204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:49.995  7162  7192 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 10:23:50.005  7204  7204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:50.005  7204  7204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:50.005  7185  7185 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1117d94d
,08-29 10:23:50.015  1018  1499 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:50.025  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:50.035  7204  7204 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:50.035  7204  7204 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:50.055  1018  1030 I ActivityManager: Killing 6091:com.android.mms/u0a41 (adj 15): empty #21
,08-29 10:23:50.065  7185  7185 I SA      : [SSP] onCreated
,08-29 10:23:50.075  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:50.085  1018  1516 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 10:23:50.085  1018  1499 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:23:50.085  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.095  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.095  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.095  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.095  7185  7185 I SA      : [TPM] There is no property file
,08-29 10:23:50.095  7204  7204 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 10:23:50.105  7185  7185 I SA      : [SCU] isHaveSA() - false,
08-29 10:23:50.105  7185  7185 I SA      : [TPM] getModelProperty : null
08-29 10:23:50.105  7185  7185 I SA      : [TPM] getCSCProperty : null
08-29 10:23:50.105  7185  7185 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-29 10:23:50.105  7185  7185 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 10:23:50.105  7185  7185 I SA      : [DM] TFT FEATURE: false
,08-29 10:23:50.105  7224  7224 E Zygote  : MountEmulatedStorage()
,08-29 10:23:50.105  7224  7224 E Zygote  : v2
08-29 10:23:50.105  7224  7224 I libpersona: KNOX_SDCARD checking this for 10068
08-29 10:23:50.105  7224  7224 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:50.115  7224  7224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 10:23:50.115  7185  7185 I SA      : [DM] init START
,08-29 10:23:50.115  7224  7224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:50.115  1018  1516 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7224 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-29 10:23:50.115  1018  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-29 10:23:50.115  7224  7224 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 10:23:50.115  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:50.115  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:50.115  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:50.115  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.125  7224  7224 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:50.135  7224  7224 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:50.135  1018  1499 D CountryDetector: No listener is left
,08-29 10:23:50.135   324   324 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.190ms total 22.212ms,
,08-29 10:23:50.145  7185  7185 I SA      : [DM] This device is not a Vodafone,
,08-29 10:23:50.155   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.444ms,
,08-29 10:23:50.175   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.542ms
,08-29 10:23:50.185  7240  7240 E Zygote  : MountEmulatedStorage(),
08-29 10:23:50.185  7240  7240 E Zygote  : v2
08-29 10:23:50.185  7240  7240 I libpersona: KNOX_SDCARD checking this for 10009
,08-29 10:23:50.185  7240  7240 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:50.185  7240  7240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:23:50.185  1018  1491 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7240 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-29 10:23:50.185  7240  7240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:50.185  1018  1491 I ActivityManager: Killing 6669:com.qualcomm.timeservice/1000 (adj 15): empty #21,
08-29 10:23:50.185  7240  7240 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 10:23:50.195  1018  1208 I ActivityManager: Killing 6689:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-29 10:23:50.205  7185  7185 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 10:23:50.205  7185  7185 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-29 10:23:50.215  7185  7185 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 10:23:50.215  7185  7185 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-29 10:23:50.225  7240  7240 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:50.225  7240  7240 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-29 10:23:50.235  7185  7185 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-29 10:23:50.235  7224  7224 D BadgeProvider: onCreate
,08-29 10:23:50.245  7224  7224 D BadgeProvider: DatabaseHelper
,08-29 10:23:50.245  7185  7185 I SA      : [SCU] isHaveSA() - false
,08-29 10:23:50.245  7185  7185 I SA      : support phone number id : false
08-29 10:23:50.245  7185  7185 I SA      : [DM] Supports Ref Jpn : true
,08-29 10:23:50.245  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 10:23:50.255  7185  7185 I SA      : [DM] init END
,08-29 10:23:50.255  7224  7233 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-29 10:23:50.255  7185  7185 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 10:23:50.265  7185  7185 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-29 10:23:50.265  7185  7185 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 10:23:50.275  1018  1208 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-29 10:23:50.275  7204  7204 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 10:23:50.275  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 10:23:50.275  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:50.275  1018  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:23:50.275  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 10:23:50.285  7185  7185 I SA      : [SLFUCHKMGR] constructor called
,08-29 10:23:50.285  7204  7204 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-29 10:23:50.285  7204  7204 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:23:50.285  7224  7233 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 10:23:50.285  7224  7233 D BadgeProvider: sendNotify, [notify] : null
08-29 10:23:50.285  7224  7233 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 10:23:50.285  7224  7233 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 10:23:50.285  7224  7233 D BadgeProvider: update, [UpdateCount] : 1
08-29 10:23:50.285  7204  7204 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 10:23:50.285  7204  7204 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 10:23:50.285  7204  7204 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-29 10:23:50.285  1501  1501 D Launcher.Model: reloadBadges entered.
,08-29 10:23:50.285  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-29 10:23:50.295  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.295  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.295  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:50.295  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.315  7185  7185 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
08-29 10:23:50.315  7185  7185 I SA      : [OR] == isSIMCardReady false ==
08-29 10:23:50.315  7185  7185 I SA      : [SCU] == networkStateCheck == false
08-29 10:23:50.315  7185  7185 I SA      : [OR] onReceive END,
,08-29 10:23:50.315  7261  7261 E Zygote  : MountEmulatedStorage()
,08-29 10:23:50.315  7261  7261 E Zygote  : v2
08-29 10:23:50.315  7261  7261 I libpersona: KNOX_SDCARD checking this for 10110
08-29 10:23:50.315  7261  7261 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:50.315  7261  7261 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:50.315  1018  1031 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7261 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-29 10:23:50.315  7261  7261 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:50.325  7261  7261 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 10:23:50.325  1018  1500 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 10:23:50.325  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 10:23:50.325  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:50.325  1018  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:50.325  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-29 10:23:50.325  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-29 10:23:50.335  7045  7258 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-29 10:23:50.335  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:50.335  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:50.335  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:50.335  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:50.345  7276  7276 E Zygote  : MountEmulatedStorage()
,08-29 10:23:50.345  7276  7276 E Zygote  : v2
08-29 10:23:50.345  7276  7276 I libpersona: KNOX_SDCARD checking this for 10008
08-29 10:23:50.345  7276  7276 I libpersona: KNOX_SDCARD not a persona,
08-29 10:23:50.345  7261  7261 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 10:23:50.345  7276  7276 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:50.345  7261  7261 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:50.355  7276  7276 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:50.355  7276  7276 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 10:23:50.355  1018  1031 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7276 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 10:23:50.365  1018  1031 I ActivityManager: Killing 6707:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-29 10:23:50.365  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:23:50.365  7276  7276 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 10:23:50.365  1018  1031 I ActivityManager: Killing 6524:com.android.calendar/u0a131 (adj 15): empty #21
,08-29 10:23:50.365  7276  7276 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:50.375  1018  1208 I ActivityManager: Killing 6722:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-29 10:23:50.375  1018  1031 I ActivityManager: Killing 6040:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-29 10:23:50.385  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:50.385  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 10:23:50.385  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:50.385  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:50.385  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:50.395  4663  7290 I iu.SyncManager: SYNC; picasa accounts
08-29 10:23:50.395  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-29 10:23:50.395  1018  1208 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-29 10:23:50.395  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 10:23:50.395  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 10:23:50.405  4663  4663 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-29 10:23:50.465  1018  1491 I ActivityManager: Killing 5841:com.android.vending/u0a26 (adj 15): empty #21
,08-29 10:23:50.465  2880  2880 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 10:23:50 GMT+02:00 2016
,08-29 10:23:50.475  1018  1208 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-29 10:23:50.475  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 10:23:50.475  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:50.475  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:50.475  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 10:23:50.475  2880  2880 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 10:23:50.485  2880  2880 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 10:23:50.485  2880  2880 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 10:23:50.485  2880  2880 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 10:23:50.485  2880  7292 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 10:23:50.495  2880  7292 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 10:23:50.495  2880  7292 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-29 10:23:50.495  2880  7292 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 10:23:50.495  2880  2880 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 10:23:50.555  1018  1321 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 10:23:50.565  1018  1456 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 10:23:50.565  1018  1456 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 10:23:50.565  1018  1456 D SecContentProvider2: mCursor = null
,08-29 10:23:50.565  1018  1456 D WifiService: setWifiEnabled: true pid=6778, uid=10171
,08-29 10:23:50.565  1018  1456 W ActivityManager: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 10:23:50.575  1018  1456 W WifiService: Failed getting userId using ActivityManagerNative
08-29 10:23:50.575  1018  1456 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 10:23:50.575  1018  1456 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 10:23:50.575  1018  1456 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 10:23:50.575  1018  1456 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 10:23:50.575  1018  1456 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 10:23:50.575  1018  1456 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 10:23:50.575  1018  1456 D SettingsProvider: name = wifi_on
,08-29 10:23:50.575  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################,
,08-29 10:23:50.675   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 10:23:50.675   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:50.675  7261  7297 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 10:23:50.685   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 10:23:50.685   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:50.685  7261  7297 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 10:23:50.695   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 10:23:50.695   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:50.695  7261  7298 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 10:23:50.695   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 10:23:50.695   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:50.695  7261  7298 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 10:23:50.735  7261  7261 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 10:23:50.735  7261  7261 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 10:23:50.735  7261  7261 I GAv4    :   adb logcat -s GAv4
,08-29 10:23:50.755  7261  7261 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:23:50.755  1018  1208 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 10:23:50.765  7261  7261 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:23:50.775  7261  7300 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 10:23:50.865  1946  2170 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-29 10:23:50.865  1946  2170 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-29 10:23:50.955  1018  1045 D Tethering: interfaceAdded wlan0
,08-29 10:23:50.955  1018  1131 E Tethering: No numeric data
,08-29 10:23:50.965  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 10:23:50.965  1018  1131 D Tethering: clearTetheredNotification()
,08-29 10:23:50.965  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 10:23:50.965  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:50.965  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:50.965  1018  1131 D Tethering: InitialState.processMessage what=4
,08-29 10:23:50.965  1018  1131 E Tethering: No numeric data
,08-29 10:23:50.965  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 10:23:50.965  1018  1131 D Tethering: clearTetheredNotification()
,08-29 10:23:50.965  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-29 10:23:50.975  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:50.975  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:23:50.975  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:23:50.975  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 10:23:50.975  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 10:23:50.975  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 10:23:50.975  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:23:50.975  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-29 10:23:50.975  1018  1124 V NetworkStats: performPollLocked() took 7ms
08-29 10:23:50.975  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:50.975  1018  1045 D Tethering: interfaceAdded p2p0
,08-29 10:23:50.975  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-29 10:23:50.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:23:50.985   278   990 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 10:23:50.985   278   990 D SoftapController: Softap fwReload - Ok,
,08-29 10:23:50.985  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:50.985  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:50.985   278   990 D CommandListener: Setting iface cfg
08-29 10:23:50.985   278   990 D CommandListener: Trying to bring down wlan0
08-29 10:23:50.985   278   990 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:23:50.995  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 10:23:51.025  1018  1321 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:51.025  1018  1321 W ActivityManager: userId = 0, bbcId = -10000,
08-29 10:23:51.025  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:51.025  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 10:23:51.045  7322  7322 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 10:23:51.045  7322  7322 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 10:23:51.045  7322  7322 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 10:23:51.085  7322  7322 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-29 10:23:51.085   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7322
08-29 10:23:51.085   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-29 10:23:51.085  7322  7322 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 10:23:51.085  7322  7322 I wpa_supplicant: ssSupport state is = 1
,08-29 10:23:51.085  7322  7322 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 10:23:51.085  7322  7322 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-29 10:23:51.085   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7322
08-29 10:23:51.085   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106,
,08-29 10:23:51.095  7261  7261 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500),
,08-29 10:23:51.095  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 10:23:51.105  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-29 10:23:51.105  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 10:23:51.105  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:51.105  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:51.105  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:51.105  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:51.105  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 10:23:51.105  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:51.105  1177  1177 D HotspotTile: onReceive : 2, 0
08-29 10:23:51.105  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:51.105  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-29 10:23:51.105  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:51.105  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:51.115  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:51.115  7261  7261 I cr.library_loader: Time to load native libraries: 6 ms (timestamps 6146-6152)
,08-29 10:23:51.115  7261  7261 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 10:23:51.125  7261  7261 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c4a213c}
,08-29 10:23:51.125  7261  7261 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 10:23:51.125  7261  7261 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 10:23:51.145  7261  7261 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 10:23:51.145  7261  7261 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 10:23:51.145  7261  7261 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 10:23:51.165  7261  7261 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-29 10:23:51.165  7261  7261 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 10:23:51.165  7261  7261 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 10:23:51.165  7261  7261 I Adreno-EGL: Local Branch: 
08-29 10:23:51.165  7261  7261 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 10:23:51.165  7261  7261 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 10:23:51.165  7261  7261 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 10:23:51.225  1018  1516 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 10:23:51.225  1018  1516 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 10:23:51.225  1018  1516 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 10:23:51.235  1018  1516 D BatteryService: stay LED for fully charged
,08-29 10:23:51.235  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 10:23:51.235  1018  1018 I MotionRecognitionService: Plugged
,08-29 10:23:51.235  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 10:23:51.235  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 10:23:51.235  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 10:23:51.235  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 10:23:51.235  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 10:23:51.265  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:23:51.265  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 10:23:51.265  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:23:51.275   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-29 10:23:51.275  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-29 10:23:51.285  7261  7338 W cr.media: Requires BLUETOOTH permission
,08-29 10:23:51.295  7261  7261 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 10:23:51.305  7261  7261 I NSApplication: Starting up...
,08-29 10:23:51.305  1018  1208 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 10:23:51.305  1018  1499 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 10:23:51.315  1018  1454 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-29 10:23:51.315  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:51.315  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:51.315  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:51.315  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:51.325  7322  7322 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-29 10:23:51.325  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 10:23:51.325  7343  7343 E Zygote  : MountEmulatedStorage()
,08-29 10:23:51.325  7343  7343 E Zygote  : v2
08-29 10:23:51.325  7343  7343 I libpersona: KNOX_SDCARD checking this for 10117
08-29 10:23:51.325  7343  7343 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:51.325  7343  7343 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 10:23:51.325  1018  1454 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7343 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 10:23:51.325  1018  1454 I ActivityManager: Killing 6904:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-29 10:23:51.335  7343  7343 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:23:51.335  7343  7343 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 10:23:51.335  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-29 10:23:51.335   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7322
08-29 10:23:51.335   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 10:23:51.335  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 10:23:51.335  7322  7322 I wpa_supplicant: ssSupport state is = 1
,08-29 10:23:51.345  7322  7322 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 10:23:51.345  7322  7322 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 10:23:51.345  7322  7322 E wpa_supplicant: SIM READ ERROR
08-29 10:23:51.345  7322  7322 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:23:51.345  7322  7322 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 10:23:51.345  7322  7322 E wpa_supplicant: SIM READ ERROR
08-29 10:23:51.345  7322  7322 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 10:23:51.345  7322  7322 I wpa_supplicant: wpa_default_ap_write_once
08-29 10:23:51.345  7322  7322 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 10:23:51.345  7322  7322 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:23:51.345  7322  7322 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 10:23:51.345  7322  7322 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:23:51.345  7322  7322 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 10:23:51.345  7322  7322 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 10:23:51.345  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:51.345  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:51.345  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:51.355  7343  7343 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:51.355  7343  7343 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:51.375  7343  7343 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 10:23:51.435  7322  7322 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-29 10:23:51.635  7322  7322 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-29 10:23:51.635  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 10:23:51.655  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-29 10:23:51.655   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7322,
08-29 10:23:51.655   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 10:23:51.655  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 10:23:51.655  7322  7322 I wpa_supplicant: ssSupport state is = 1
,08-29 10:23:51.675  7322  7322 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-29 10:23:51.675  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 10:23:51.695  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-29 10:23:51.695   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7322,
08-29 10:23:51.695  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:23:51.695   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 10:23:51.695  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:23:51.695  7322  7322 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-29 10:23:51.695  7322  7322 I wpa_supplicant: ssSupport state is = 1
08-29 10:23:51.695  7322  7322 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 10:23:51.695  7322  7322 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 10:23:51.695  7322  7322 E wpa_supplicant: SIM READ ERROR
08-29 10:23:51.695  7322  7322 I wpa_supplicant: wpa_default_ap_write_once
08-29 10:23:51.695  7322  7322 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-29 10:23:51.695  7322  7322 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 10:23:51.695  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 10:23:51.695  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-29 10:23:51.695  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 10:23:51.695  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
,08-29 10:23:51.725  1018  1321 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-29 10:23:51.725  1018  1321 I ActivityManager: Killing 6973:com.android.bluetooth/1002 (adj 15): empty #21
,08-29 10:23:51.735  1018  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:51.735  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:51.735  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 10:23:51.735  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:51.735  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:51.735  1602  1602 I Hs20UtilService: Starting #12
08-29 10:23:51.735  1602  1639 I Hs20UtilService: Message received 5011
,08-29 10:23:51.735  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 10:23:51.735  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 10:23:51.735  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
08-29 10:23:51.735  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 10:23:51.745  7322  7322 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-29 10:23:51.745  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 10:23:51.805  7322  7322 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-29 10:23:51.805  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 10:23:51.805  7322  7322 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 10:23:51.805  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-29 10:23:51.805  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 10:23:51.805  7322  7322 I wpa_supplicant: HOTSPOT20_ENABLE called
08-29 10:23:51.805  7322  7322 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:23:51.805  7322  7322 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 10:23:51.805  7322  7322 E wpa_supplicant: SIM READ ERROR
08-29 10:23:51.805  7322  7322 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 10:23:51.835  7322  7322 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-29 10:23:51.845  7322  7322 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-29 10:23:51.845  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 10:23:51.845  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 10:23:51.845  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:51.845  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:51.845  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:51.855  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-29 10:23:51.855  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:51.855  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-29 10:23:51.855  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 10:23:51.855  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:51.855  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:23:51.855  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:51.855  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:51.855  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:23:51.855  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:51.855  1177  1177 D HotspotTile: onReceive : 3, 0,
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:51.855  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:51.855  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:51.855  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:23:51.855  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:51.865  1018  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:51.865  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-29 10:23:51.865  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:51.865  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:51.865  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:51.865  1018  1127 E WifiConfigStore: Not a HS20
,08-29 10:23:51.865  1602  1602 I Hs20UtilService: Starting #13
08-29 10:23:51.865  1602  1639 I Hs20UtilService: Message received 5011
08-29 10:23:51.865  1018  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 10:23:51.865  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 10:23:51.865  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 10:23:51.865  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 10:23:51.865  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
08-29 10:23:51.865  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 10:23:51.875  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-29 10:23:51.875  7322  7322 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 10:23:51.875  7322  7322 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 10:23:51.875  7322  7322 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 10:23:51.875  7322  7322 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 10:23:51.875  7322  7322 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 10:23:51.875  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 10:23:51.875  7322  7322 I wpa_supplicant: First Scan Start
08-29 10:23:51.875  7322  7322 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 10:23:51.875  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-29 10:23:51.875  7045  7045 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:23:51.875  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:23:51.875  1018  1127 I WifiNative-HAL: startHal
08-29 10:23:51.875  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d6c488c
08-29 10:23:51.875  1018  1127 I WifiNative-HAL: Could not start hal
,08-29 10:23:51.875  1018  1127 E WifiNative-wlan0: do suspend true
,08-29 10:23:51.875  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 10:23:51.885  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,08-29 10:23:51.885  1018  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:23:51.885  1018  1150 I WifiNative-HAL: startHal
08-29 10:23:51.885  1018  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9ec809bc
08-29 10:23:51.885  1018  1150 I WifiNative-HAL: Could not start hal
08-29 10:23:51.885  1018  1150 E WifiScanningService: could not start HAL
08-29 10:23:51.885  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-29 10:23:51.885  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 },
08-29 10:23:51.885  1018  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:23:51.885  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 10:23:51.885  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-29 10:23:51.885  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-29 10:23:51.885   278   990 D CommandListener: Setting iface cfg
08-29 10:23:51.885   278   990 D CommandListener: Trying to bring up p2p0
08-29 10:23:51.885  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 10:23:51.885  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 10:23:51.885  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-29 10:23:51.885  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 10:23:51.885  1018  1126 D WifiP2pService: P2pEnablingState
08-29 10:23:51.885  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 10:23:51.885  1018  1126 D WifiP2pService: P2p socket connection successful
08-29 10:23:51.885  1018  1126 D WifiP2pService: P2pEnabledState
,08-29 10:23:51.885  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:23:51.885  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 10:23:51.885  7322  7322 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 10:23:51.885  7322  7322 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 10:23:51.885  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 10:23:51.885  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-29 10:23:51.885  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:23:51.885  1018  1048 D WifiDisplayController: disconnect
08-29 10:23:51.885  1018  1048 D WifiDisplayController: updateConnection
08-29 10:23:51.885  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:23:51.885  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 10:23:51.885  7322  7322 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-29 10:23:51.885  1018  1127 E WifiStateMachine: Failed to set frequency band 0
,08-29 10:23:51.895  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:51.895  1018  1127 D SecContentProvider2: mCursor = null
08-29 10:23:51.895  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 10:23:51.895  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 10:23:51.895  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 10:23:51.895  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-29 10:23:51.895  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 10:23:51.895  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-29 10:23:51.895  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:51.895  1018  1127 D SecContentProvider2: mCursor = null,
08-29 10:23:51.895  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-29 10:23:51.895  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 10:23:51.895  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-29 10:23:51.895  1018  1516 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 10:23:51.895  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-29 10:23:51.895  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 10:23:51.895  1018  1126 D WifiP2pService: DeviceAddress: 0a:76:28
08-29 10:23:51.895  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  secondary type: null
,08-29 10:23:51.895  1018  1048 D WifiDisplayController:  wps: 0
,08-29 10:23:51.895  1018  1048 D WifiDisplayController:  grpcapab: 0
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  devcapab: 0
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  status: 3
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  wfdInfo: null
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-29 10:23:51.895  1018  1048 D WifiDisplayController:  SConnectInfo : null
08-29 10:23:51.895  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:23:51.895  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 10:23:51.895  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 10:23:51.895  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:51.905  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 10:23:51.905  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 10:23:51.905  7015  7015 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 10:23:51.905  7030  7030 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 10:23:51.915  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 10:23:51.915  1018  1126 D WifiP2pService: InactiveState
08-29 10:23:51.915  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-29 10:23:51.915  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 10:23:51.915  7322  7322 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 10:23:51.915  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
08-29 10:23:51.915  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 10:23:51.965  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 10:23:51.965  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 10:23:51.965  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-29 10:23:51.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:23:52.935   293   293 E SMD     : DCD OFF
,08-29 10:23:52.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:23:53.065  7322  7322 I wpa_supplicant: nl80211: Received scan results (31 BSSes),
08-29 10:23:53.065  7322  7322 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 10:23:53.065  7322  7322 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 10:23:53.065  7322  7322 I wpa_supplicant: Trying to associate with  'G700'
,08-29 10:23:53.065  7322  7322 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-29 10:23:53.065  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 10:23:53.065  1018  7369 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 10:23:53.085  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:53.085  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:23:53.175  7322  7322 E wpa_supplicant: Cmd 35605 not handled
,08-29 10:23:53.175  7322  7322 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-29 10:23:53.175  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 10:23:53.175  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 10:23:53.175  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 10:23:53.175  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-29 10:23:53.175  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 10:23:53.175  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-29 10:23:53.175  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:53.185  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 10:23:53.185  7322  7322 I wpa_supplicant: Associated with F4.99.3E
,08-29 10:23:53.185  7322  7322 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 10:23:53.185  7322  7322 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-29 10:23:53.185  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-29 10:23:53.185  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 10:23:53.185  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-29 10:23:53.185  1018  1131 E Tethering: No numeric data
,08-29 10:23:53.185  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 10:23:53.185  1018  1131 D Tethering: clearTetheredNotification()
08-29 10:23:53.185  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:23:53.185  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:53.185  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 10:23:53.185  7322  7322 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 10:23:53.185  1177  1177 D HotspotTile: updateTetherState():false, false
08-29 10:23:53.185  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:23:53.185  7322  7322 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-29 10:23:53.185  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 10:23:53.195  7322  7322 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 10:23:53.195  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 10:23:53.195  7322  7322 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:23:53.195  7322  7322 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 10:23:53.195  7322  7322 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-29 10:23:53.195  7322  7322 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 10:23:53.195  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 10:23:53.195  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 10:23:53.195  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 10:23:53.195  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-29 10:23:53.195  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:53.195  1018  1127 D SecContentProvider2: mCursor = null
08-29 10:23:53.195  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:53.195  1018  1124 V NetworkStats: performPollLocked() took 7ms
08-29 10:23:53.195  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:53.195  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:53.195  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-29 10:23:53.205  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
08-29 10:23:53.205  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 10:23:53.205  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 10:23:53.205  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:23:53.205  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:23:53.205  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:53.205  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:53.215  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:23:53.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.215  1018  1516 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:53.215  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 10:23:53.215  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:53.215  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:53.215  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 10:23:53.225  1602  1602 I Hs20UtilService: Starting #14
08-29 10:23:53.225  1602  1639 I Hs20UtilService: Message received 5007
08-29 10:23:53.225  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 10:23:53.225  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 10:23:53.225  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 10:23:53.225  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 10:23:53.225  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:23:53.225  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:23:53.225  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 10:23:53.225  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:53.235   278   990 D CommandListener: Setting iface cfg
08-29 10:23:53.235  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 10:23:53.235  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:53.235  1018  1127 D SecContentProvider2: mCursor = null
08-29 10:23:53.245  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:53.245  1018  1127 D SecContentProvider2: mCursor = null
08-29 10:23:53.255  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:53.255  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:53.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.265  1018  1127 E WifiNative-wlan0: do suspend false
08-29 10:23:53.265  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-29 10:23:53.265  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 10:23:53.265  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:53.265  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:23:53.405  1018  1456 I ActivityManager: Killing 6927:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-29 10:23:53.485  7376  7376 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 10:23:53.485  7376  7376 I dhcpcd  : version 5.5.6 starting,
,08-29 10:23:53.495  7376  7376 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 10:23:53.555  7376  7376 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 10:23:53.555  7376  7376 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 10:23:53.555  7376  7376 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-29 10:23:53.555  7376  7376 I dhcpcd  : bssid match
,08-29 10:23:53.555  7376  7376 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 10:23:53.575  1018  1499 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 10:23:53.575  1018  1499 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 10:23:53.575  1018  1499 D SecContentProvider2: mCursor = null
,08-29 10:23:53.575  1018  1499 D WifiService: setWifiEnabled: false pid=6778, uid=10171
,08-29 10:23:53.585  1018  1499 D SettingsProvider: name = wifi_on
,08-29 10:23:53.585  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-29 10:23:53.605  1018  1127 E WifiNative-wlan0: do suspend true,
,08-29 10:23:53.625  7376  7376 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-29 10:23:53.625  7376  7376 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-29 10:23:53.625  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:53.625  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-29 10:23:53.625  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:53.625  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 10:23:53.635  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.635  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.635  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.635  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.635   278   990 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:23:53.645  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-29 10:23:53.645  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:23:53.645  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:23:53.645  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-29 10:23:53.645   278   990 E Netd    : no such netId 503
08-29 10:23:53.645  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,08-29 10:23:53.655  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:53.655  1018  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
08-29 10:23:53.655  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:23:53.655  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 10:23:53.655  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 10:23:53.655  1018  1129 V NetworkStats: updateIfacesLocked()
08-29 10:23:53.655  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-29 10:23:53.655  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:53.655  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:53.665  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.665  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.665  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.665  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:53.665  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:53.665  1018  1129 V NetworkStats: performPollLocked() took 11ms
,08-29 10:23:53.665  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
08-29 10:23:53.665  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 10:23:53.665  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-29 10:23:53.665  1018  7374 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:23:53.665  1018  7374 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 10:23:53.665  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 10:23:53.665  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 10:23:53.665  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-29 10:23:53.675  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-29 10:23:53.675  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1,
08-29 10:23:53.675  1018  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:23:53.675  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-29 10:23:53.675  1018  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:23:53.675  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 10:23:53.675  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:53.685  1018  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:53.685  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 10:23:53.685  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
08-29 10:23:53.685  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:53.685  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:53.685  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 10:23:53.685  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 10:23:53.685  1602  1602 I Hs20UtilService: Starting #15
08-29 10:23:53.685  1018  1126 D WifiP2pService: P2pDisablingState
08-29 10:23:53.685  1602  1639 I Hs20UtilService: Message received 5007
08-29 10:23:53.685  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 10:23:53.685  1018  1126 D WifiP2pService: p2p socket connection lost
08-29 10:23:53.695  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 10:23:53.695  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 10:23:53.695  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-29 10:23:53.695  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 10:23:53.695  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 10:23:53.695  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 10:23:53.695  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:23:53.695  1018  1048 D WifiDisplayController: disconnect
08-29 10:23:53.695  1018  1048 D WifiDisplayController: updateConnection
08-29 10:23:53.695  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:23:53.695  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 10:23:53.695  1018  1126 D WifiP2pService: P2pDisabledState
,08-29 10:23:53.695  1018  1127 E WifiNative-wlan0: do suspend true
,08-29 10:23:53.695  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 10:23:53.695  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 10:23:53.705  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 10:23:53.705  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 10:23:53.705  1018  1129 W MessageQueue: Handler (com.android.internal.util.StateMachine$SmHandler) {17009fdc} sending message to a Handler on a dead thread
08-29 10:23:53.705  1018  1129 W MessageQueue: java.lang.IllegalStateException: Handler (com.android.internal.util.StateMachine$SmHandler) {17009fdc} sending message to a Handler on a dead thread
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at android.os.Handler.sendMessageAtFrontOfQueue(Handler.java:623)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at com.android.internal.util.StateMachine$SmHandler.quitNow(StateMachine.java:1216)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at com.android.internal.util.StateMachine$SmHandler.access$2400(StateMachine.java:673)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at com.android.internal.util.StateMachine.quitNow(StateMachine.java:1914)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at com.android.server.connectivity.NetworkMonitor.doQuit(NetworkMonitor.java:300)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at com.android.server.ConnectivityService.handleAsyncChannelDisconnected(ConnectivityService.java:3030)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at com.android.server.ConnectivityService.access$2200(ConnectivityService.java:250)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2636)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:53.705  1018  1129 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 10:23:53.705  1018  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 10:23:53.705  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:23:53.705  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 10:23:53.705  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:23:53.705  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:23:53.705  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:23:53.705  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 10:23:53.705  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:53.715  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 10:23:53.715  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 10:23:53.725  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 10:23:53.725  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:23:53.725  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:23:53.725  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 10:23:53.725  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:53.725  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 10:23:53.725  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 10:23:53.725  7015  7015 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 10:23:53.735  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-29 10:23:53.735  7030  7030 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 10:23:53.735  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
08-29 10:23:53.735   278   990 D CommandListener: Clearing all IP addresses on wlan0
,08-29 10:23:53.735  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:53.735  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:53.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:53.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:23:53.745  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 10:23:53.745  7322  7322 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 10:23:53.755  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:53.755  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:23:53.755  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.755  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.755  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.755  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.755  1018  1208 I ActivityManager: Killing 7069:com.sec.pcw.device/1000 (adj 15): empty #21,
,08-29 10:23:53.765  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:23:53.765  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:23:53.765  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:23:53.765  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 10:23:53.765  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.765  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.765  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.765  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:53.765  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:53.765  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:53.765  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 10:23:53.775  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 10:23:53.775  1177  1177 D HotspotTile: onReceive : 0, 0
,08-29 10:23:53.775  1018  1454 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:53.775  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:23:53.775  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:53.775  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:53.775  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:53.775  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:53.775  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:53.775  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:53.775  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:53.775  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:23:53.775  1602  1602 I Hs20UtilService: Starting #16
08-29 10:23:53.775  1602  1639 I Hs20UtilService: Message received 5007
,08-29 10:23:53.785  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:53.785  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:53.785  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 10:23:53.785  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:23:53.785  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 10:23:53.785  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 10:23:53.785  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 10:23:53.795  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:23:53.795  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:23:53.795  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 10:23:53.795  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:23:53.805  1018  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:23:53.805  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:23:53.805  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:53.805  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:53.805  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:53.815  1602  1602 I Hs20UtilService: Starting #17
,08-29 10:23:53.815  1602  1639 I Hs20UtilService: Message received 5011
08-29 10:23:53.815  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-29 10:23:53.815  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 10:23:53.815  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
08-29 10:23:53.815  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 10:23:53.985  7322  7322 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 10:23:53.985   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 10:23:54.045  7322  7322 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-29 10:23:54.045  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 10:23:54.045  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:23:54.045  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-29 10:23:54.065  7322  7322 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-29 10:23:54.065  7322  7322 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 10:23:54.065  7322  7322 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 10:23:54.075  7322  7322 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030,
08-29 10:23:54.075  7322  7322 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 10:23:54.075  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:54.075  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 10:23:54.075  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:54.075  1018  1131 D Tethering: InitialState.processMessage what=4
,08-29 10:23:54.075  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 10:23:54.075  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:54.075  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:54.085  1018  1131 E Tethering: No numeric data
08-29 10:23:54.085  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 10:23:54.085  1018  1131 D Tethering: clearTetheredNotification()
08-29 10:23:54.085  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:54.085  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:54.085  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:54.085  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 10:23:54.085  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-29 10:23:54.095  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:23:54.095  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-29 10:23:54.095  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 10:23:54.095  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 10:23:54.095  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:54.095  1018  1124 V NetworkStats: performPollLocked() took 6ms
,08-29 10:23:54.095  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:23:54.095  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:23:54.175  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 10:23:54.175  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:54.175  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:54.395  7322  7322 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 10:23:54.475  7322  7322 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-29 10:23:54.475  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:23:54.475  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:23:54.475  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:23:54.585  7045  7045 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 10:23:54.585  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-29 10:23:54.585  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 10:23:54.595  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 10:23:54.595  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 10:23:54.595  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 10:23:54.595  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:54.595  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:54.595  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:54.595  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:54.595  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:23:54.595  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:23:54.595  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 10:23:54.595  1946  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:23:54.595  1177  1177 D HotspotTile: onReceive : 1, 0
,08-29 10:23:54.595  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:23:54.605  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:54.605  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:54.605  1018  1208 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 10:23:54.605  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:23:54.605  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:54.605  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:54.605  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:23:54.605  1602  1602 I Hs20UtilService: Starting #18
,08-29 10:23:54.605  1602  1639 I Hs20UtilService: Message received 5011
08-29 10:23:54.615  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 10:23:54.615  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 10:23:54.615  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
08-29 10:23:54.615  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 10:23:55.405  1018  1045 D Tethering: interfaceRemoved wlan0
08-29 10:23:55.405  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 10:23:55.555  1018  1045 D Tethering: interfaceRemoved p2p0
,08-29 10:23:55.555  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 10:23:55.935   293   293 E SMD     : DCD OFF
,08-29 10:23:56.335  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 10:23:56.595  6778  6834 D BluetoothAdapter: enable()
,08-29 10:23:56.595  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 10:23:56.595  1018  1031 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 10:23:56.595  1018  1031 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 10:23:56.595  1018  1031 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 10:23:56.595  1018  1031 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 10:23:56.595  1018  1031 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 10:23:56.595  1018  1031 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 10:23:56.595  1018  1031 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 10:23:56.595  1018  1031 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:23:56.595  1018  1031 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:23:56.605  1018  1031 D SettingsProvider: name = bluetooth_on
,08-29 10:23:56.605  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-29 10:23:56.605  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 10:23:56.615  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-29 10:23:56.615  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 10:23:56.615  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:56.615  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:56.615  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:56.615  1018  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:56.635  1018  1047 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7406 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-29 10:23:56.635  7406  7406 E Zygote  : MountEmulatedStorage()
,08-29 10:23:56.635  7406  7406 E Zygote  : v2
08-29 10:23:56.635  7406  7406 I libpersona: KNOX_SDCARD checking this for 1002
08-29 10:23:56.635  7406  7406 I libpersona: KNOX_SDCARD not a persona
,08-29 10:23:56.645  7406  7406 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:56.645  7406  7406 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 10:23:56.645  7406  7406 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:56.675  7406  7406 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:56.675  7406  7406 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:56.695  7406  7406 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 10:23:56.695  7406  7406 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 10:23:56.735  1018  3361 D SSRM:n  : SIOP:: AP = 360
,08-29 10:23:56.735  7406  7406 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 10:23:56.775  7406  7406 D BtSettings.ProfileConfig: Adding GattService
,08-29 10:23:56.775  7406  7406 D BtSettings.ProfileConfig: Adding HeadsetService
,08-29 10:23:56.775  7406  7406 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 10:23:56.775  7406  7406 D BtSettings.ProfileConfig: Adding HidService
,08-29 10:23:56.775  7406  7406 D BtSettings.ProfileConfig: Adding HealthService
,08-29 10:23:56.785  7406  7406 D BtSettings.ProfileConfig: Adding PanService
,08-29 10:23:56.785  7406  7406 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-29 10:23:56.785  7406  7406 D BtSettings.ProfileConfig: Adding SapService
08-29 10:23:56.785  7406  7406 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-29 10:23:56.785  7406  7406 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-29 10:23:56.785  7406  7406 D BtSettings.ProfileConfig: Adding SapClientService
,08-29 10:23:56.785  7406  7406 D BtSettings.ProfileConfig: Adding HidDevService
,08-29 10:23:56.785  7406  7406 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 10:23:56.785  1018  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-29 10:23:56.785  1018  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.785  1018  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.785  1018  1500 D SettingsProvider: selectionArgs: false
08-29 10:23:56.785  1018  1500 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.785  1018  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.785  1018  1500 D SettingsProvider: ret = -1
,08-29 10:23:56.785  1018  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-29 10:23:56.785  1018  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.785  1018  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.785  1018  1319 D SettingsProvider: selectionArgs: false
,08-29 10:23:56.785  1018  1319 D SettingsProvider: selectionArgs: 1002
,08-29 10:23:56.795  1018  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 10:23:56.795  1018  1319 D SettingsProvider: ret = -1
,08-29 10:23:56.795  1018  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:56.795  1018  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.795  1018  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.795  1018  1499 D SettingsProvider: selectionArgs: false
,08-29 10:23:56.795  1018  1499 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.795  1018  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.795  1018  1499 D SettingsProvider: ret = -1
,08-29 10:23:56.795  1018  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 10:23:56.795  1018  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.795  1018  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.795  1018  1491 D SettingsProvider: selectionArgs: false
,08-29 10:23:56.795  1018  1491 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.795  1018  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.795  1018  1491 D SettingsProvider: ret = -1
,08-29 10:23:56.795  1018  1516 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 10:23:56.795  1018  1516 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 10:23:56.795  1018  1516 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.795  1018  1516 D SettingsProvider: selectionArgs: false
08-29 10:23:56.795  1018  1516 D SettingsProvider: selectionArgs: 1002
,08-29 10:23:56.795  1018  1516 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.795  1018  1516 D SettingsProvider: ret = -1
,08-29 10:23:56.795  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-29 10:23:56.795  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.795  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.795  1018  1031 D SettingsProvider: selectionArgs: false
08-29 10:23:56.795  1018  1031 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.795  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.795  1018  1031 D SettingsProvider: ret = -1
08-29 10:23:56.795  1018  1454 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-29 10:23:56.795  1018  1454 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.795  1018  1454 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.795  1018  1454 D SettingsProvider: selectionArgs: false
08-29 10:23:56.795  1018  1454 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.795  1018  1454 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.795  1018  1454 D SettingsProvider: ret = -1
,08-29 10:23:56.795  1018  1321 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 10:23:56.805  1018  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.805  1018  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.805  1018  1321 D SettingsProvider: selectionArgs: false
08-29 10:23:56.805  1018  1321 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.805  1018  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.805  1018  1321 D SettingsProvider: ret = -1
,08-29 10:23:56.805  1018  1208 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:23:56.805  1018  1208 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.805  1018  1208 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.805  1018  1208 D SettingsProvider: selectionArgs: false
08-29 10:23:56.805  1018  1208 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.805  1018  1208 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 10:23:56.805  1018  1208 D SettingsProvider: ret = -1
08-29 10:23:56.805  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:56.805  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.805  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.805  1018  1030 D SettingsProvider: selectionArgs: false
08-29 10:23:56.805  1018  1030 D SettingsProvider: selectionArgs: 1002
,08-29 10:23:56.805  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.805  1018  1030 D SettingsProvider: ret = -1
08-29 10:23:56.805  1018  1456 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 10:23:56.805  1018  1456 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.805  1018  1456 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.805  1018  1456 D SettingsProvider: selectionArgs: false
08-29 10:23:56.805  1018  1456 D SettingsProvider: selectionArgs: 1002
,08-29 10:23:56.805  1018  1456 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.805  1018  1456 D SettingsProvider: ret = -1
08-29 10:23:56.805  1018  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-29 10:23:56.805  1018  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:56.805  1018  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:56.805  1018  1500 D SettingsProvider: selectionArgs: false
,08-29 10:23:56.805  1018  1500 D SettingsProvider: selectionArgs: 1002
08-29 10:23:56.805  1018  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:56.805  1018  1500 D SettingsProvider: ret = -1
,08-29 10:23:56.825  7406  7406 D BluetoothAdapterState: make
,08-29 10:23:56.825  7406  7406 I bluedroid: init
,08-29 10:23:56.825  7406  7421 I BluetoothAdapterState: Entering OffState
,08-29 10:23:56.835  7406  7406 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 10:23:56.835  7406  7406 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf,
08-29 10:23:56.835  7406  7406 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:23:56.835  7406  7406 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 10:23:56.835  7406  7406 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-29 10:23:56.835  7406  7406 I bluedroid: get_profile_interface socket
,08-29 10:23:56.835  7406  7406 I bluedroid: get_profile_interface map_client
,08-29 10:23:56.835  7406  7406 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-29 10:23:56.845  7406  7424 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-29 10:23:56.845  7406  7406 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:56.845  1018  1456 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 10:23:56.845  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:23:56.845  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:56.845  1018  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:56.845  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:56.845  7406  7414 I bluedroid: config_hci_snoop_log
,08-29 10:23:56.845  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
08-29 10:23:56.845  7406  7424 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-29 10:23:56.845  7406  7424 E BluetoothServiceJni: populateRssiValuesNative
08-29 10:23:56.845  7406  7424 I bluedroid: getModelRssiValues
08-29 10:23:56.845  7406  7424 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 10:23:56.845  7406  7424 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 10:23:56.845  7406  7424 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 10:23:56.855  1018  1018 D SettingsProvider: name = bluetooth_name
,08-29 10:23:56.855  1018  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-29 10:23:56.855  1018  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-29 10:23:56.855  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 10:23:56.855  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 10:23:56.865  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:23:56.865  7406  7406 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-29 10:23:56.865  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:23:56.875  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 10:23:56.875  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 10:23:56.875  7406  7421 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 10:23:56.875  7406  7421 D BluetoothAdapterProperties: Setting state to 11
,08-29 10:23:56.875  7406  7421 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 10:23:56.875  7406  7421 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 10:23:56.875  7406  7421 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 10:23:56.875  7406  7421 D BluetoothAdapterService: Autoconnection is available 
,08-29 10:23:56.875  7406  7421 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 10:23:56.875  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:56.875  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-29 10:23:56.885  7406  7421 D BluetoothSecureManager: getInstant: null
08-29 10:23:56.885  7406  7421 D BluetoothSecureManager: calling getMethod for getService
,08-29 10:23:56.885  7406  7421 D BluetoothSecureManager: calling getService
,08-29 10:23:56.885  7406  7421 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@225eafbd
08-29 10:23:56.885  1018  1321 D BluetoothSecureManagerService: isSecureModeEnabled
08-29 10:23:56.885  1018  1321 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-29 10:23:56.885  7406  7421 D BtConfig.SecureMode: isSecureModeOn:false
08-29 10:23:56.885  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 10:23:56.885  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 10:23:56.885  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 10:23:56.885  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-29 10:23:56.885  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:56.885  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService,
08-29 10:23:56.885  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 10:23:56.885  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 10:23:56.885  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:56.885  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-29 10:23:56.885  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-29 10:23:56.885  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 10:23:56.895  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 10:23:56.895  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-29 10:23:56.895  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 10:23:56.895  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:23:56.895  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:56.895  1884  1884 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:56.895  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 10:23:56.895  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 10:23:56.895  7406  7421 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-29 10:23:56.905  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:56.905  1018  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 10:23:56.905  1018  1499 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 10:23:56.905  1018  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:23:56.905  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 10:23:56.905  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 10:23:56.905  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:56.905  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:23:56.905  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:56.915  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:56.915  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 10:23:56.915  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
08-29 10:23:56.915  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 10:23:56.925  7406  7421 D BluetoothBondStateMachine: make
,08-29 10:23:56.925  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 10:23:56.925  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 10:23:56.925  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 10:23:56.925  7406  7427 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 10:23:56.925  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 10:23:57.055  1018  1319 I art     : Explicit concurrent mark sweep GC freed 71808(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.419ms total 159.336ms
,08-29 10:23:57.065  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 10:23:57.065  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:57.065  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.065  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.065  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:23:57.065  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.075  7406  7406 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 10:23:57.075  7406  7406 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:23:57.075  7406  7406 D BtGatt.GattService: start()
08-29 10:23:57.075  7406  7406 D BtGatt.GattService: start()
08-29 10:23:57.075  7406  7406 I bluedroid: get_profile_interface gatt
08-29 10:23:57.075  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
08-29 10:23:57.075  7406  7406 D BtGatt.AdvertiseManager: advertise manager created
08-29 10:23:57.075  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-29 10:23:57.075  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 10:23:57.075  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 10:23:57.085  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:57.085  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 10:23:57.085  1018  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:57.085  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.085  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.085  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:23:57.085  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.095  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:57.095  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:57.095  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 10:23:57.095  1018  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:57.095  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.095  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.095  1018  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.095  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.095  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-29 10:23:57.095  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 10:23:57.095  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 10:23:57.105  7406  7406 D BtGatt.GattService: mStartError = false
08-29 10:23:57.105  1018  1516 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 10:23:57.105  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:57.105  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:57.105  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:57.105  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:57.105  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:57.115  7406  7406 D HeadsetService: Received start request. Starting profile...
08-29 10:23:57.115  7406  7406 D HeadsetService: start()
08-29 10:23:57.115  7406  7406 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 10:23:57.115  7406  7406 D HeadsetStateMachine: make
,08-29 10:23:57.115  7406  7406 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 10:23:57.125  7432  7432 E Zygote  : MountEmulatedStorage()
,08-29 10:23:57.125  7432  7432 E Zygote  : v2
08-29 10:23:57.125  7432  7432 I libpersona: KNOX_SDCARD checking this for 10055
08-29 10:23:57.125  7432  7432 I libpersona: KNOX_SDCARD not a persona,
,08-29 10:23:57.135  7432  7432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:23:57.135  1018  1516 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7432 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 10:23:57.135  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:57.135  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 10:23:57.135  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.135  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.135  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 10:23:57.135  7432  7432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:23:57.135  7432  7432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:23:57.145  1018  1456 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 10:23:57.145  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.145  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.145  1018  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.145  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 10:23:57.145  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 10:23:57.145  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 10:23:57.145  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 10:23:57.145  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:57.145  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.145  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.145  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.145  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.155  1018  1454 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-29 10:23:57.155  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 10:23:57.155  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-29 10:23:57.155  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 10:23:57.155  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 10:23:57.155  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.155  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.155  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-29 10:23:57.155  7406  7406 I bluedroid: get_profile_interface handsfree
08-29 10:23:57.155  1018  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:57.155  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.155  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.155  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.155  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.165  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-29 10:23:57.165  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 10:23:57.165  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 10:23:57.165  1018  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:57.165  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.175  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.175  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.175  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.175  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 10:23:57.175  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 10:23:57.175  7406  7421 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 10:23:57.175  1018  1516 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:57.175  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.175  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.175  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.175  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.185  7432  7432 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:23:57.185  7432  7432 D ActivityThread: Added TimaKeyStore provider
,08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:23:57.185  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:57.185  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 10:23:57.185  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 10:23:57.185  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 10:23:57.185  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 10:23:57.185  7406  7421 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 10:23:57.195  7406  7406 I DualScoManager: Instantiating Dual Sco Manager
08-29 10:23:57.195  7406  7406 I DualScoManager: Set HeadsetServiceHelper
,08-29 10:23:57.195  7406  7406 D BluetoothAtMessage: createCMTIContentObservers
,08-29 10:23:57.195  1018  1031 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-29 10:23:57.195  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:57.195  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:57.195  1018  1031 D SettingsProvider: selectionArgs: false
08-29 10:23:57.195  1018  1031 D SettingsProvider: selectionArgs: 1002
08-29 10:23:57.195  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:57.195  1018  1031 D SettingsProvider: ret = -1
,08-29 10:23:57.195  7406  7431 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 10:23:57.205  7406  7406 D HeadsetService: mStartError = false
08-29 10:23:57.205  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:57.205  7406  7431 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 10:23:57.205  7406  7431 D HeadsetStateMachine: map size, before remove : 0
08-29 10:23:57.205  7406  7431 D HeadsetStateMachine: map size, after remove: 0
,08-29 10:23:57.205  7406  7406 D A2dpService: Received start request. Starting profile...
08-29 10:23:57.205  7406  7406 D A2dpService: start()
,08-29 10:23:57.205  7406  7406 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 10:23:57.205  7406  7406 I bluedroid: get_profile_interface avrcp
,08-29 10:23:57.215  7406  7406 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 10:23:57.215  7406  7406 D Avrcp   : Initialize Media Controller
08-29 10:23:57.215  7406  7406 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 10:23:57.215  7406  7406 E Avrcp   : getActiveSessions
08-29 10:23:57.215  7406  7406 D Avrcp   : pick active media Controller
08-29 10:23:57.215  7406  7406 D Avrcp   : Get the active Media Controller 
,08-29 10:23:57.225  7432  7432 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 10:23:57.235  7406  7406 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 10:23:57.235  7406  7450 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 10:23:57.245  7406  7406 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 10:23:57.245  7406  7406 D A2dpStateMachine: make
08-29 10:23:57.245  7406  7406 I bluedroid: get_profile_interface a2dp
08-29 10:23:57.245  7406  7452 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 10:23:57.245  7406  7406 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 10:23:57.245  7406  7406 D A2dpService: mStartError = false
08-29 10:23:57.245  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
08-29 10:23:57.245  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-29 10:23:57.255  7406  7406 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 10:23:57.255  7406  7451 D A2dpStateMachine: Enter Disconnected: -2
,08-29 10:23:57.255  7406  7406 D HidService: Received start request. Starting profile...
08-29 10:23:57.255  7406  7406 D HidService: start()
08-29 10:23:57.255  7406  7406 I bluedroid: get_profile_interface hidhost
08-29 10:23:57.255  7406  7406 D HidService: setHidService(): set to: null
08-29 10:23:57.255  7406  7406 D HidService: mStartError = false
08-29 10:23:57.255  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:57.255  7406  7406 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 10:23:57.255  1444  1459 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 10:23:57.255  1444  1444 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 10:23:57.255  1444  1444 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 10:23:57.255  1444  1459 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 10:23:57.255  7406  7406 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 10:23:57.265  7406  7406 D HealthService: Received start request. Starting profile...
,08-29 10:23:57.265  7406  7406 D HealthService: start()
,08-29 10:23:57.265  7432  7432 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-29 10:23:57.265  7432  7432 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 10:23:57.265  7432  7432 D UserAnalysis: Create SecureDbHelper
,08-29 10:23:57.265  7406  7450 D BluetoothMediaBrowser: no now playing list
08-29 10:23:57.265  7406  7450 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 10:23:57.265  7406  7406 I bluedroid: get_profile_interface health
,08-29 10:23:57.265  7406  7406 D HealthService: mStartError = false
08-29 10:23:57.265  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:57.265  7406  7406 D HeadsetStateMachine: Proxy object connected
,08-29 10:23:57.265  7406  7406 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 10:23:57.265  7406  7406 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 10:23:57.265  7406  7431 D HeadsetStateMachine: Disconnected process message: 11
,08-29 10:23:57.265  7406  7406 D PanService: Received start request. Starting profile...
08-29 10:23:57.265  7406  7406 D PanService: start()
,08-29 10:23:57.265  7406  7406 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 10:23:57.275  7406  7406 I bluedroid: get_profile_interface pan
,08-29 10:23:57.275  7432  7432 D IntelligenceServiceApplication: onCreate()
,08-29 10:23:57.275  7406  7406 D PanService: mStartError = false
08-29 10:23:57.275  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:57.275  7406  7406 D BluetoothMapService: Received start request. Starting profile...
08-29 10:23:57.275  7406  7406 D BluetoothMapService: start()
,08-29 10:23:57.275  1018  1031 I ActivityManager: Killing 7086:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-29 10:23:57.285  7432  7432 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 10:23:57.285  7406  7406 D BluetoothMapService: mStartError = false
08-29 10:23:57.285  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:23:57.285  7406  7406 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 10:23:57.285  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 10:23:57.285  7432  7432 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 10:23:57.285  7406  7406 D SapService: Received start request. Starting profile...
08-29 10:23:57.285  7406  7406 D SapService: start()
08-29 10:23:57.285  7406  7406 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 10:23:57.285  7406  7406 I bluedroid: get_profile_interface sap
08-29 10:23:57.285  7406  7406 D SapService: mStartError = false
08-29 10:23:57.285  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
08-29 10:23:57.285  7406  7406 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-29 10:23:57.285  7406  7406 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-29 10:23:57.285  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 10:23:57.285  7406  7431 D HeadsetStateMachine: Disconnected process message: 18
08-29 10:23:57.285  7406  7406 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 10:23:57.285  7406  7406 D BluetoothA2dp: Proxy object connected
08-29 10:23:57.285  7406  7406 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 10:23:57.285  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 10:23:57.285  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-29 10:23:57.285  7406  7431 D HeadsetStateMachine: Disconnected process message: 10
08-29 10:23:57.285  7406  7431 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:23:57.285  7406  7431 D HeadsetStateMachine: Disconnected process message: 11
,08-29 10:23:57.295  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 10:23:57.295  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 10:23:57.295  1018  1208 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 10:23:57.295  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:57.295  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:23:57.295  7432  7432 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-29 10:23:57.295  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:57.295  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:23:57.315  1018  1208 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7457 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 10:23:57.315  7457  7457 E Zygote  : MountEmulatedStorage()
08-29 10:23:57.315  7457  7457 I libpersona: KNOX_SDCARD checking this for 10105
08-29 10:23:57.315  7457  7457 E Zygote  : v2
08-29 10:23:57.315  7457  7457 I libpersona: KNOX_SDCARD not a persona
08-29 10:23:57.315  7457  7457 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:23:57.315  7457  7457 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 10:23:57.315  7457  7457 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 10:23:57.335  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 10:23:57.335  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 10:23:57.335  7406  7421 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-29 10:23:57.335  7406  7421 I bluedroid: enable
,08-29 10:23:57.345  7406  7470 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-29 10:23:57.345  7406  7421 I bt_hci_bdroid: init
,08-29 10:23:57.345  7406  7421 I bt_vendor: bt-vendor : init
08-29 10:23:57.345  7406  7421 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 10:23:57.345  7406  7421 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 10:23:57.345  7406  7421 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 10:23:57.345  7406  7421 D bt_userial_mct: userial_init
,08-29 10:23:57.345  7406  7421 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 10:23:57.345  7406  7421 I bt_vendor: Starting hciattach daemon
08-29 10:23:57.345  7406  7421 I bt_vendor: try to set false
,08-29 10:23:57.355  7406  7421 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 10:23:57.355  7406  7421 I bt_vendor: Starting hciattach daemon
08-29 10:23:57.355  7406  7421 I bt_vendor: try to set true
,08-29 10:23:57.375  7457  7457 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 10:23:57.375  7457  7457 D ActivityThread: Added TimaKeyStore provider,
,08-29 10:23:57.375  7478  7478 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 10:23:57.425  7484  7484 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-29 10:23:57.435  7485  7485 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 10:23:57.445  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 10:23:57.455  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 10:23:57.465  7491  7491 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 10:23:57.475  7492  7492 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-29 10:23:57.495   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 10:23:57.495   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:57.495  7457  7496 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 10:23:57.505   257   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 10:23:57.505   257   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 10:23:57.505  7457  7496 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 10:23:57.675  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-29 10:23:57.675  7508  7508 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 10:23:57.705  7406  7421 I bt_vendor: bluetooth satus is on
,08-29 10:23:57.705  7406  7474 D bt_userial_mct: userial_open(port:0)
08-29 10:23:57.705  7406  7474 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 10:23:57.715  7406  7474 I bt_vendor: Done intiailizing UART
,08-29 10:23:57.715  7406  7474 I bt_vendor: Done intiailizing UART
,08-29 10:23:57.715  7406  7474 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.File.exists(File.java:363)
,08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityT,hread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194),
08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.715  7457  7457 D StrictMode: ,	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:57.725  1018  1208 I ActivityManager: Killing 7098:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 10:23:57.715  7457  7457 D StrictMode: ,	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
,08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.v.a(PG:1161),
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=200 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.androi,d.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:57.715  7457  7457 D Str,ictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399),
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 10:23:57.715  7457  7457 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
,08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 10:23:57.715  7457  7457 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 10:23:57.725  7406  7474 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 10:23:57.725  7406  7510 D bt_userial_mct: Entering userial_read_thread()
08-29 10:23:57.725  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_SAP
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 10:23:57.735  7406  7470 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
08-29 10:23:57.735  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 10:23:57.795  7457  7506 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 10:23:57.825  1018  1454 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:57.835  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.835  1018  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:57.835  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 10:23:57.835  7406  7470 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 10:23:57.835  7406  7470 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4219ed1 
08-29 10:23:57.835  7406  7470 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4219ed1 
,08-29 10:23:57.855  7406  7424 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 10:23:57.855  7406  7424 E bt-btif : Calling BTA_HhEnable
,08-29 10:23:57.865  7406  7424 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 10:23:57.865  7406  7424 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 10:23:57.865  7406  7424 E BluetoothServiceJni: populateRssiValuesNative
08-29 10:23:57.865  7406  7424 I bluedroid: getModelRssiValues
,08-29 10:23:57.865  7406  7424 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-29 10:23:57.865  7406  7424 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 10:23:57.865  1018  1018 D SettingsProvider: name = bluetooth_name
,08-29 10:23:57.865  7406  7424 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 10:23:57.875  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.875  7406  7424 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 10:23:57.875  7406  7424 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:23:57.875  7406  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:23:57.875  7406  7424 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-29 10:23:57.875  7406  7424 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-29 10:23:57.875  7406  7424 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-29 10:23:57.875  7406  7424 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 10:23:57.875  7406  7424 E bt-btif : btif_sock_init: !vhci_init
08-29 10:23:57.875  7406  7424 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-29 10:23:57.875  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:23:57.875  7406  7424 D IOP_DB_BT: db_open: db_open : handle 3028733968l, read 13894 bytes onto local cache,
,08-29 10:23:57.875  7406  7424 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-29 10:23:57.875  7406  7510 E bt_mct  : hci lib postload completed
08-29 10:23:57.875  7406  7424 D IOP_DB_BT: db_query: result 1
08-29 10:23:57.875  7406  7424 I         : iop_db_open: iop_db_open status 0,
08-29 10:23:57.875  7406  7424 D bte_conf: Device ID record 1 : primary
08-29 10:23:57.875  7406  7424 D bte_conf:   vendorId            = 0075
,08-29 10:23:57.875  7406  7424 D bte_conf:   vendorIdSource      = 0001,
08-29 10:23:57.875  7406  7424 D bte_conf:   product             = 0100
08-29 10:23:57.875  7406  7424 D bte_conf:   version             = 0200
08-29 10:23:57.875  7406  7424 D bte_conf:   clientExecutableURL = 
08-29 10:23:57.875  7406  7424 D bte_conf:   serviceDescription  = 
08-29 10:23:57.875  7406  7424 D bte_conf:   documentationURL    = 
08-29 10:23:57.875  7406  7424 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 10:23:57.875  7406  7424 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 10:23:57.875  7406  7421 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 10:23:57.875  7406  7421 D BluetoothAdapterProperties: ScanMode =  20
08-29 10:23:57.875  7406  7421 D BluetoothAdapterProperties: State =  11
08-29 10:23:57.885  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 10:23:57.885  7406  7421 D BluetoothAdapterProperties: Setting state to 12
08-29 10:23:57.885  7406  7421 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 10:23:57.885  7406  7424 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 10:23:57.885  7406  7424 D BluetoothAdapterProperties: Scan Mode:21
,08-29 10:23:57.895  1018  1208 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 10:23:57.895  1018  1208 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:23:57.895  1018  1208 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:23:57.895  1018  1208 D SettingsProvider: selectionArgs: false
08-29 10:23:57.895  1018  1208 D SettingsProvider: selectionArgs: 1002
08-29 10:23:57.895  1018  1208 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:23:57.895  1018  1208 D SettingsProvider: ret = -1
,08-29 10:23:57.895  7406  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:23:57.895  7406  7421 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 10:23:57.895  7406  7421 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 10:23:57.895  1018  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:57.895  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:57.895  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:23:57.895  1018  1500 W ActivityManager: userId = 0, bbcId = -10000,
08-29 10:23:57.895  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.895  1018  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:57.895  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 10:23:57.895  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-29 10:23:57.895  7406  7421 D BluetoothAdapterService: Autoconnection is available 
08-29 10:23:57.895  7406  7421 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-29 10:23:57.895  7406  7421 D BluetoothAdapterService: starting service from this receiver
08-29 10:23:57.895  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.895  1018  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.895  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.905  1946  2159 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.905  1946  2159 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:23:57.905  7406  7421 I BluetoothAdapterState: Entering On State from state = 11
,08-29 10:23:57.905  1444  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:57.905  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:23:57.905  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:23:57.905  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.905  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.905  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.905  1444  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:23:57.905  3066  3074 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 10:23:57.915  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:23:57.915  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 10:23:57.915  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.915  7406  7406 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 10:23:57.915  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.915  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.915  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:57.915  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:23:57.915  1177  3886 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 10:23:57.925  1177  3886 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:23:57.925  3066  6900 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.925  3066  6900 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:23:57.925  7406  7415 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.925  7406  7415 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:23:57.925  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:23:57.925  1444  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:57.925  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:23:57.925  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 10:23:57.925  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.925  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.925  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.925  1444  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:23:57.925  7406  7406 I BluetoothPbapService: Handler(): got msg=1
,08-29 10:23:57.925  1018  1456 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 10:23:57.925  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 10:23:57.925  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:23:57.925  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:23:57.925  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 10:23:57.925  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:23:57.925  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:57.935  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 10:23:57.935  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.935  3066  3075 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 10:23:57.935  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 10:23:57.935  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.935  3066  3066 D BluetoothMap: Proxy object connected
08-29 10:23:57.935  3066  3066 D MapProfile: Bluetooth service connected
08-29 10:23:57.935  3066  3066 D BluetoothMap: getConnectedDevices()
08-29 10:23:57.935  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.935  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.935  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.935  7406  7517 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 10:23:57.935  1018  1018 D BluetoothA2dp: Proxy object connected
,08-29 10:23:57.935  6778  6824 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.935  6778  6824 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:23:57.935  1444  1463 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.935  1444  1463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:23:57.935  7406  7415 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:23:57.935  3066  3066 D BluetoothInputDevice: Proxy object connected
08-29 10:23:57.935  7406  7517 D BluetoothSocket: bindListen(): myUserId = 0
08-29 10:23:57.935  3066  6900 D Bluetoothsap: onBluetoothStateChange: up=true
08-29 10:23:57.935  3066  6900 D Bluetoothsap: Binding service...
08-29 10:23:57.935  7406  7517 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:23:57.935  3066  3066 D HidProfile: Bluetooth service connected
,08-29 10:23:57.945  7406  7517 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-29 10:23:57.945  7406  7517 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 10:23:57.945  7406  7517 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 10:23:57.945  7406  7517 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f9fb136
08-29 10:23:57.945  7406  7517 D BluetoothSocket: channel: 19
08-29 10:23:57.945  7406  7517 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 10:23:57.945  3066  6900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 10:23:57.945  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-29 10:23:57.945  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.945  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.945  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.945  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.945  3066  6900 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 10:23:57.945  3066  6900 D BluetoothPan: Binding service...
08-29 10:23:57.945  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 10:23:57.945  3066  3066 D SapProfile: Bluetooth service connected
08-29 10:23:57.945  3066  3066 D Bluetoothsap: getConnectedDevices()
,08-29 10:23:57.955  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 10:23:57.955  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.955  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.955  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.955  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.955  1460  1475 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 10:23:57.955  1460  1475 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:23:57.955  3066  3066 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:23:57.955  3066  3066 D PanProfile: Bluetooth service connected
08-29 10:23:57.955  1478  1492 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.955  1478  1492 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:23:57.955  7457  7468 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.955  7457  7468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:23:57.955  3066  3075 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:23:57.955  3066  3075 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:57.955  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 10:23:57.955  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.955  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.955  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.955  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.955  3066  3066 D BluetoothA2dp: Proxy object connected
,08-29 10:23:57.955  3066  3066 D A2dpProfile: Bluetooth service connected
08-29 10:23:57.955  1444  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:57.955  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 10:23:57.965  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:23:57.965  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.965  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.965  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.965  1444  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:23:57.965  3066  6900 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 10:23:57.965  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-29 10:23:57.965  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.965  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.965  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.965  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.965  3066  3066 D BluetoothPbap: Proxy object connected
,08-29 10:23:57.965  3066  3066 D PbapServerProfile: Bluetooth service connected
,08-29 10:23:57.975  3066  3074 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:57.975  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 10:23:57.975  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:23:57.975  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:57.975  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.975  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.975  3066  3074 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:23:57.975  3066  3066 D HeadsetProfile: Bluetooth service connected
,08-29 10:23:57.975  1478  1668 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:23:57.975  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:23:57.975  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:23:57.975  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:57.975  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:57.975  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:57.975  1478  1668 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 10:23:57.975  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:23:57.975  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:23:57.975  1018  1047 D BluetoothPan: Binding service...
,08-29 10:23:57.975  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 10:23:57.975  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 10:23:57.975  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:23:57.975  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 10:23:57.975  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 10:23:57.985  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:57.985  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-29 10:23:57.985  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 10:23:57.985  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 10:23:57.985  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 10:23:57.995  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:57.995  1177  1177 D BluetoothTile:  getBluetoothState : 12
08-29 10:23:57.995  1444  1444 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2680d912, true
,08-29 10:23:57.995  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:23:57.995  1444  1444 D BluetoothHeadset: registerMessageListener
,08-29 10:23:57.995  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:23:57.995  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:57.995  1884  1884 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 10:23:58.005  1018  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 10:23:58.005  1018  1321 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 10:23:58.005  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:58.005  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 10:23:58.005  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:23:58.005  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:58.005  7406  7425 D HeadsetService: registerMessageListener
08-29 10:23:58.005  1018  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:58.005  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 10:23:58.005  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:58.005  7406  7425 D HeadsetService: registerMessageListener
08-29 10:23:58.005  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:23:58.005  7406  7431 D HeadsetStateMachine: Disconnected process message: 70
08-29 10:23:58.005  7406  7431 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4c11837
08-29 10:23:58.005  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 10:23:58.005  1444  1444 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-29 10:23:58.005  1444  1444 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 10:23:58.015  7406  7519 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 10:23:58.015  1444  1444 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 10:23:58.015  1444  1444 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-29 10:23:58.015  1444  1444 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 10:23:58.015  3066  3066 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-29 10:23:58.015  3066  3066 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-29 10:23:58.015  3066  3066 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 10:23:58.015  3066  3066 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 10:23:58.015  7406  7431 D HeadsetStateMachine: Disconnected process message: 9
08-29 10:23:58.015  7406  7431 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 10:23:58.015  7406  7519 D BluetoothSocket: bindListen(): myUserId = 0
08-29 10:23:58.015  7406  7519 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:23:58.025  7406  7519 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-29 10:23:58.025  7406  7519 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 10:23:58.025  7406  7519 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 10:23:58.025  7406  7519 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d2241a4
08-29 10:23:58.025  7406  7519 D BluetoothSocket: channel: 5
,08-29 10:23:58.035  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:23:58.035  1018  1208 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 10:23:58.035   283   693 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 10:23:58.035   283   693 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 10:23:58.035   283   693 V voice   : voice_set_parameters: exit with code(-2)
08-29 10:23:58.035   283   693 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 10:23:58.035   283   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 10:23:58.035   283   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 10:23:58.035   283   693 V audio_hw_primary: adev_set_parameters: exit
08-29 10:23:58.035  7406  7431 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-29 10:23:58.035  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 10:23:58.035  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:58.035  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:58.035  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 10:23:58.045  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:23:58.045  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 10:23:58.045  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:58.045  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 10:23:58.055  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
08-29 10:23:58.055  7406  7406 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 10:23:58.055  1018  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:23:58.055  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 10:23:58.055  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:58.055  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:58.055  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:58.075  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 10:23:58.075  1018  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:23:58.075  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 10:23:58.075  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:58.075  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:58.075  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:58.085  1946  7526 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 10:23:58.085  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 10:23:58.085  1018  1321 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:58.085  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:58.085  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:58.085  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:58.095  1018  1500 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 10:23:58.105  1018  1454 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:23:58.105  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:58.105  1018  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:58.105  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:58.115  7406  7530 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 10:23:58.115  7406  7530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:23:58.115  7406  7530 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 10:23:58.115  7406  7530 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 10:23:58.115  7406  7530 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 10:23:58.115  7406  7530 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1afb10e
08-29 10:23:58.115  7406  7530 D BluetoothSocket: channel: 12
08-29 10:23:58.115  7406  7530 I BtOppRfcommListener: Accept thread started.
,08-29 10:23:58.125  1946  7526 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 10:23:58.945   293   293 E SMD     : DCD OFF
,08-29 10:23:59.615  6778  6834 D BluetoothAdapter: disable()
,08-29 10:23:59.615  1018  1500 D SettingsProvider: name = bluetooth_on
,08-29 10:23:59.625  7406  7421 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-29 10:23:59.625  7406  7421 D BluetoothAdapterProperties: Setting state to 13
08-29 10:23:59.625  7406  7421 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 10:23:59.625  7406  7421 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 10:23:59.625  7406  7421 D BluetoothAdapterService: updateAdapterState state is 13
08-29 10:23:59.625  1018  1516 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:23:59.625  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 10:23:59.625  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:23:59.625  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-29 10:23:59.625  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:59.625  7406  7406 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-29 10:23:59.625  7406  7421 D BluetoothAdapterService: Autoconnection is available 
08-29 10:23:59.625  7406  7421 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 10:23:59.625  7406  7421 D BluetoothAdapterService: terminating service from this receiver
,08-29 10:23:59.625  7406  7406 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3e94d72f, channel: 19, state: LISTENING
08-29 10:23:59.625  7406  7406 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3e94d72f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f9fb136, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c4a213cmSocket: android.net.LocalSocket@12189ec5 impl:android.net.LocalSocketImpl@639d01a fd:FileDescriptor[75]
08-29 10:23:59.625  7406  7406 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@12189ec5 impl:android.net.LocalSocketImpl@639d01a fd:FileDescriptor[75]
,08-29 10:23:59.625  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 10:23:59.635  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:59.635  1018  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:59.635  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:23:59.635  7406  7421 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 10:23:59.635  7406  7421 D BluetoothAdapterProperties: mDiscovering is false
,08-29 10:23:59.635  1018  1500 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 10:23:59.635  7406  7421 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 10:23:59.635  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:59.635  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-29 10:23:59.645  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 10:23:59.645  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 10:23:59.645  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:59.645  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:23:59.645  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-29 10:23:59.645  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:23:59.655  1884  1884 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 10:23:59.655  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 10:23:59.655  1018  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 10:23:59.655  1018  1516 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 10:23:59.655  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 10:23:59.665  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:59.665  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:23:59.665  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:23:59.665  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:59.665  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:23:59.675  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:23:59.675  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:23:59.675  6778  6778 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 10:23:59.675  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:23:59.675  1018  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:23:59.675  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 10:23:59.675  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:59.675  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:23:59.675  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:23:59.685  7406  7406 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1221b74b, channel: 5, state: LISTENING
,08-29 10:23:59.685  7406  7406 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1221b74b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d2241a4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d361528mSocket: android.net.LocalSocket@1f696241 impl:android.net.LocalSocketImpl@3b14d3e6 fd:FileDescriptor[76]
,08-29 10:23:59.685  7406  7406 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f696241 impl:android.net.LocalSocketImpl@3b14d3e6 fd:FileDescriptor[76]
,08-29 10:23:59.685  7406  7406 I BtOppRfcommListener: stopping Accept Thread
08-29 10:23:59.685  7406  7406 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a527d27, channel: 12, state: LISTENING
08-29 10:23:59.685  7406  7406 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a527d27, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1afb10e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a6b5bd4mSocket: android.net.LocalSocket@2fa8e17d impl:android.net.LocalSocketImpl@234a4872 fd:FileDescriptor[80]
08-29 10:23:59.685  7406  7406 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2fa8e17d impl:android.net.LocalSocketImpl@234a4872 fd:FileDescriptor[80]
,08-29 10:23:59.685  7406  7530 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 10:23:59.685  7406  7530 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 10:23:59.685  7406  7424 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 10:23:59.695  7406  7424 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:23:59.695  7406  7406 V BluetoothOppManager: cleanUp...
,08-29 10:23:59.695  7406  7421 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 10:23:59.695  7406  7421 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 10:23:59.695  7406  7421 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-29 10:23:59.695  7406  7421 E bt-btif : cmd socket is not created
08-29 10:23:59.695  7406  7421 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 10:23:59.695  7406  7470 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-29 10:23:59.695  7406  7470 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 10:23:59.695  7406  7470 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:23:59.695  7406  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:59.695  7406  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 10:23:59.695  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:23:59.695  1018  1499 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 10:23:59.695  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 10:23:59.695  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:59.705  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:23:59.705  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:23:59.705  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 10:23:59.705  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:23:59.705  3066  3066 D BluetoothPbap: Proxy object disconnected
08-29 10:23:59.705  3066  3066 D PbapServerProfile: Bluetooth service disconnected
,08-29 10:23:59.715  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:23:59.715  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 10:23:59.715  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:23:59.715  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 10:23:59.735  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 10:23:59.735  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:23:59.895  7406  7510 I bt_userial_mct: exiting userial_read_thread
08-29 10:23:59.895  7406  7510 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-29 10:23:59.895  7406  7470 W bt-l2cap: HC lib lpm enable=0 return 0
08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 10:23:59.895  7406  7470 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 10:23:59.895  7406  7470 W bt-btif : ag scb idx 1 not allocated
08-29 10:23:59.895  7406  7470 W bt-btif : ag scb idx 2 not allocated
08-29 10:23:59.895  7406  7470 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 10:23:59.895  7406  7424 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 10:23:59.895  7406  7474 I bt_vendor: hw_epilog_process
08-29 10:23:59.895  7406  7424 D bt_userial_mct: userial_close
08-29 10:23:59.895  7406  7424 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 10:23:59.985  1018  1096 V AlarmManager: waitForAlarm result :8
,08-29 10:24:01.115  7406  7424 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-29 10:24:01.115  7406  7424 I bt_vendor: bluetooth satus is on
08-29 10:24:01.115  7406  7424 I bt_vendor: bt-vendor : resetting BT status
,08-29 10:24:01.115  7406  7424 I bt_vendor: Starting hciattach daemon
08-29 10:24:01.115  7406  7424 I bt_vendor: try to set false
,08-29 10:24:01.125  7406  7424 I bt_vendor: Starting hciattach daemon,
,08-29 10:24:01.125  7406  7424 I bt_vendor: try to set false
08-29 10:24:01.125  1018  1454 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:24:01.125  7406  7424 I bt_vendor: cleanup
08-29 10:24:01.125  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-29 10:24:01.125  7406  7470 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 10:24:01.125  1018  1516 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:24:01.125  7406  7424 I GKI_LINUX: GKI_exit_task 0 done
08-29 10:24:01.125  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 10:24:01.125  7406  7424 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 10:24:01.125  7406  7421 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 10:24:01.125  7406  7421 D BtConfig.SecureMode: isSecureModeOn:false
08-29 10:24:01.125  7406  7421 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 10:24:01.125  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 10:24:01.125  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 10:24:01.125  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-29 10:24:01.125  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.125  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:01.125  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 10:24:01.125  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 10:24:01.125  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 10:24:01.125  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 10:24:01.125  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.135  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:01.135  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:01.135  7406  7406 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 10:24:01.135  7406  7406 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 10:24:01.135  7406  7406 D BtGatt.GattService: stop()
08-29 10:24:01.135  7406  7406 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 10:24:01.135  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 10:24:01.135  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 10:24:01.135  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 10:24:01.135  1018  1516 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:01.135  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:24:01.135  1018  1516 W ActivityManager: userId = 0, bbcId = -10000,
08-29 10:24:01.135  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:01.135  1018  1208 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:01.135  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 10:24:01.135  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 10:24:01.135  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 10:24:01.135  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 10:24:01.135  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 10:24:01.135  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
08-29 10:24:01.135  7406  7406 D HeadsetService: Received stop request...Stopping profile...
08-29 10:24:01.135  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.135  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:01.135  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:01.145  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService,
08-29 10:24:01.145  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 10:24:01.145  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 10:24:01.145  1018  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:01.145  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 10:24:01.145  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.145  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:01.145  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:01.145  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:24:01.145  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 10:24:01.145  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 10:24:01.145  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 10:24:01.145  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 10:24:01.145  1018  1454 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:01.145  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 10:24:01.155  3066  3066 D HeadsetProfile: Bluetooth service disconnected
,08-29 10:24:01.155  7406  7406 D A2dpService: Received stop request...Stopping profile...
,08-29 10:24:01.155  7406  7451 D A2dpStateMachine: Exit Disconnected: -1,
,08-29 10:24:01.155  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.155  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:24:01.155  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:01.155  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService,
08-29 10:24:01.155  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 10:24:01.155  7406  7421 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 10:24:01.155  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
08-29 10:24:01.155  1018  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:01.155  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 10:24:01.155  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.155  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:24:01.155  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:01.165  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:01.165  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 10:24:01.165  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 10:24:01.165  1018  1208 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:01.165  3066  3066 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:01.165  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 10:24:01.165  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:01.165  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:01.165  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 10:24:01.165  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:01.165  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 10:24:01.165  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 10:24:01.165  7406  7421 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 10:24:01.165  7406  7421 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 10:24:01.165  7406  7421 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 10:24:01.165  3066  3066 D A2dpProfile: Bluetooth service disconnected
,08-29 10:24:01.165  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-29 10:24:01.165  7406  7406 D HidService: Received stop request...Stopping profile...
,08-29 10:24:01.165  7406  7406 D HidService: Stopping Bluetooth HidService
08-29 10:24:01.175  7406  7406 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 10:24:01.175  7406  7406 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 10:24:01.175  7406  7406 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 10:24:01.175  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:24:01.175  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-29 10:24:01.175  7406  7406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 10:24:01.175  7406  7406 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 10:24:01.175  7406  7406 D HealthService: Received stop request...Stopping profile...
,08-29 10:24:01.175  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:24:01.175  3066  3066 D BluetoothInputDevice: Proxy object disconnected,
08-29 10:24:01.175  3066  3066 D HidProfile: Bluetooth service disconnected
,08-29 10:24:01.175  7406  7406 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 10:24:01.175  7406  7406 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 10:24:01.175  7406  7406 D PanService: Received stop request...Stopping profile...
08-29 10:24:01.185  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:24:01.185  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 10:24:01.185  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 10:24:01.185  7406  7406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 10:24:01.185  7406  7406 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 10:24:01.185  3066  3066 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 10:24:01.185  3066  3066 D PanProfile: Bluetooth service disconnected
,08-29 10:24:01.185  7406  7406 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 10:24:01.185  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:24:01.185  7406  7406 D BluetoothA2dp: Proxy object disconnected
08-29 10:24:01.185  7406  7406 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-29 10:24:01.185  7406  7452 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 10:24:01.195  7406  7406 I GKI_LINUX: GKI_exit_task 2 done
08-29 10:24:01.195  7406  7406 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 10:24:01.195  3066  3066 D BluetoothMap: Proxy object disconnected
08-29 10:24:01.195  3066  3066 D MapProfile: Bluetooth service disconnected
,08-29 10:24:01.195  7406  7406 D SapService: Received stop request...Stopping profile...
08-29 10:24:01.195  7406  7406 D SapService: Stopping Bluetooth SapService
08-29 10:24:01.195  7406  7406 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b89987c
,08-29 10:24:01.195  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 10:24:01.195  3066  3066 D SapProfile: Bluetooth service disconnected
,08-29 10:24:01.195  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-29 10:24:01.195  7406  7406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 10:24:01.195  7406  7406 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 10:24:01.195  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-29 10:24:01.195  7406  7406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 10:24:01.195  7406  7406 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 10:24:01.195  7406  7406 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 10:24:01.195  7406  7406 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 10:24:01.195  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 10:24:01.195  7406  7406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 10:24:01.195  7406  7406 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 10:24:01.195  7406  7406 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 10:24:01.195  7406  7406 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 10:24:01.195  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-29 10:24:01.195  7406  7406 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 10:24:01.195  7406  7406 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 10:24:01.205  7406  7406 E BluetoothAdapterService(730437756): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-29 10:24:01.205  7406  7406 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-29 10:24:01.205  7406  7406 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 10:24:01.205  7406  7421 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-29 10:24:01.205  7406  7421 D BluetoothAdapterProperties: Setting state to 10
08-29 10:24:01.205  7406  7421 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-29 10:24:01.205  7406  7421 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 10:24:01.205  7406  7421 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 10:24:01.205  7406  7421 D BluetoothAdapterService: Autoconnection is available 
,08-29 10:24:01.205  7406  7421 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 10:24:01.205  7406  7421 I BluetoothAdapterState: Entering OffState
,08-29 10:24:01.205  1946  1956 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 10:24:01.205  1946  1956 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 10:24:01.205  3066  6900 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 10:24:01.215  1177  1609 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 10:24:01.215  1177  1609 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 10:24:01.215  3066  3075 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:24:01.215  3066  3075 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 10:24:01.215  7406  7518 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 10:24:01.215  7406  7518 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 10:24:01.215  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 10:24:01.215  3066  3074 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 10:24:01.215  6778  6788 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 10:24:01.215  6778  6788 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:24:01.215  6778  6788 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-29 10:24:01.215  6778  6788 D BluetoothLeAdvertiser: Exit stop advertising
08-29 10:24:01.215  6778  6788 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 10:24:01.215  6778  6788 D BluetoothLeScanner: Exiting stopAllScan
,08-29 10:24:01.215  1444  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 10:24:01.215  1444  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 10:24:01.215  7406  7414 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 10:24:01.225  3066  6900 D Bluetoothsap: onBluetoothStateChange: up=false
,08-29 10:24:01.225  3066  6900 D Bluetoothsap: Unbinding service...
,08-29 10:24:01.225  1460  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 10:24:01.225  1460  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 10:24:01.225  1478  1490 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:24:01.225  1478  1490 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 10:24:01.225  7457  7473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:24:01.225  7457  7473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:24:01.225  3066  3074 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 10:24:01.225  3066  6900 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 10:24:01.225  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 10:24:01.225  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 10:24:01.225  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-29 10:24:01.235  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 10:24:01.235  7406  7424 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 10:24:01.235  7406  7406 I GKI_LINUX: GKI_exit_task 1 done
08-29 10:24:01.235  7406  7406 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 10:24:01.235  7406  7406 I BluetoothServiceJni: cleanupNative: return from cleanup,
08-29 10:24:01.235  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:01.235  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-29 10:24:01.235  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 10:24:01.245  7406  7406 I art     : System.exit called, status: 0
08-29 10:24:01.245  7406  7406 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 10:24:01.245  1177  1177 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
08-29 10:24:01.245  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 10:24:01.245  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:01.245  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-29 10:24:01.245  1177  1177 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
,08-29 10:24:01.245  1177  1778 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
08-29 10:24:01.245  1177  1778 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
,08-29 10:24:01.245  1884  1884 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 10:24:01.245  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:01.245  1177  1177 D BluetoothAdapter: 805781029: getState() :  mService = null. Returning STATE_OFF
,08-29 10:24:01.255  1018  1208 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 10:24:01.255  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:01.255  1018  1516 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 10:24:01.255  1946  2161 D BluetoothAdapter: 1035973801: getState() :  mService = null. Returning STATE_OFF
08-29 10:24:01.255  1946  2161 D BluetoothAdapter: 1035973801: getState() :  mService = null. Returning STATE_OFF
,08-29 10:24:01.255  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 10:24:01.255  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:24:01.255  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-29 10:24:01.255  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:01.255  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.255  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:01.255  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:01.255  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:24:01.255  1018  1319 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 10:24:01.255  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 10:24:01.265  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.265  1018  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:01.265  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 10:24:01.275  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:01.275  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 10:24:01.295  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:01.295  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 10:24:01.295  1018  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 10:24:01.305  1018  1499 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 10:24:01.305  1018  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 10:24:01.305  1018  1031 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 10:24:01.305  1018  1499 D BatteryService: stay LED for fully charged
,08-29 10:24:01.305  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 10:24:01.305  1018  1031 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 10:24:01.305  1018  1031 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-29 10:24:01.305  1018  1031 W BroadcastQueue: android.os.TransactionTooLargeException
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method),
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-29 10:24:01.305  1018  1031 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-29 10:24:01.305  1018  1031 W BroadcastQueue: ,	at android.os.Binder.execTransact(Binder.java:446)
08-29 10:24:01.305  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-29 10:24:01.305  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:01.305  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:01.305  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:01.305  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:01.325  7546  7546 E Zygote  : MountEmulatedStorage()
08-29 10:24:01.325  7546  7546 E Zygote  : v2
08-29 10:24:01.325  7546  7546 I libpersona: KNOX_SDCARD checking this for 1002
08-29 10:24:01.325  7546  7546 I libpersona: KNOX_SDCARD not a persona
,08-29 10:24:01.325  7546  7546 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:24:01.325  7546  7546 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:24:01.325  7546  7546 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:24:01.325  1018  1031 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7546 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-29 10:24:01.335  1018  1018 I MotionRecognitionService: Plugged
08-29 10:24:01.335  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 10:24:01.335  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 10:24:01.335  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 10:24:01.345  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 10:24:01.345  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-29 10:24:01.355  7546  7546 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:24:01.355  7546  7546 D ActivityThread: Added TimaKeyStore provider
,08-29 10:24:01.365  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:24:01.365  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 10:24:01.365  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:24:01.365  7546  7546 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 10:24:01.375  7546  7546 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 10:24:01.395  7546  7546 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding GattService
,08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding HeadsetService
,08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding A2dpService
08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding HidService
,08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding HealthService
08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding PanService
,08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding SapService
08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding SapClientService
08-29 10:24:01.425  7546  7546 D BtSettings.ProfileConfig: Adding HidDevService
08-29 10:24:01.425  7546  7546 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 10:24:01.425  1018  1456 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-29 10:24:01.425  1018  1456 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.425  1018  1456 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.425  1018  1456 D SettingsProvider: selectionArgs: false
,08-29 10:24:01.425  1018  1456 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.425  1018  1456 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 10:24:01.425  1018  1456 D SettingsProvider: ret = -1
,08-29 10:24:01.435  1018  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-29 10:24:01.435  1018  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.435  1018  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.435  1018  1491 D SettingsProvider: selectionArgs: false
08-29 10:24:01.435  1018  1491 D SettingsProvider: selectionArgs: 1002
,08-29 10:24:01.435  1018  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.435  1018  1491 D SettingsProvider: ret = -1
,08-29 10:24:01.435  1018  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-29 10:24:01.435  1018  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.435  1018  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.435  1018  1499 D SettingsProvider: selectionArgs: false
,08-29 10:24:01.435  1018  1499 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.435  1018  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.435  1018  1499 D SettingsProvider: ret = -1
,08-29 10:24:01.435  1018  1321 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-29 10:24:01.435  1018  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.435  1018  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.435  1018  1321 D SettingsProvider: selectionArgs: false
,08-29 10:24:01.435  1018  1321 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.435  1018  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.435  1018  1321 D SettingsProvider: ret = -1
,08-29 10:24:01.435  1018  1208 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 10:24:01.435  1018  1208 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.435  1018  1208 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.435  1018  1208 D SettingsProvider: selectionArgs: false
08-29 10:24:01.435  1018  1208 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.435  1018  1208 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.435  1018  1208 D SettingsProvider: ret = -1
,08-29 10:24:01.435  1018  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 10:24:01.435  1018  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 10:24:01.435  1018  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.435  1018  1319 D SettingsProvider: selectionArgs: false
08-29 10:24:01.435  1018  1319 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.435  1018  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.435  1018  1319 D SettingsProvider: ret = -1
,08-29 10:24:01.435  1018  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-29 10:24:01.435  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.435  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.435  1018  1030 D SettingsProvider: selectionArgs: false
08-29 10:24:01.435  1018  1030 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.435  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.445  1018  1030 D SettingsProvider: ret = -1
,08-29 10:24:01.445  1018  1454 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 10:24:01.445  1018  1454 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.445  1018  1454 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.445  1018  1454 D SettingsProvider: selectionArgs: false
08-29 10:24:01.445  1018  1454 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.445  1018  1454 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.445  1018  1454 D SettingsProvider: ret = -1
,08-29 10:24:01.445  1018  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:24:01.445  1018  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.445  1018  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.445  1018  1500 D SettingsProvider: selectionArgs: false
08-29 10:24:01.445  1018  1500 D SettingsProvider: selectionArgs: 1002
,08-29 10:24:01.445  1018  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.445  1018  1500 D SettingsProvider: ret = -1
,08-29 10:24:01.445  1018  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:01.445  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.445  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.445  1018  1031 D SettingsProvider: selectionArgs: false
08-29 10:24:01.445  1018  1031 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.445  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 10:24:01.445  1018  1031 D SettingsProvider: ret = -1
08-29 10:24:01.445  1018  1516 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 10:24:01.445  1018  1516 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.445  1018  1516 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.445  1018  1516 D SettingsProvider: selectionArgs: false
08-29 10:24:01.445  1018  1516 D SettingsProvider: selectionArgs: 1002
,08-29 10:24:01.445  1018  1516 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.445  1018  1516 D SettingsProvider: ret = -1
,08-29 10:24:01.445  1018  1456 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-29 10:24:01.445  1018  1456 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:01.445  1018  1456 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:01.445  1018  1456 D SettingsProvider: selectionArgs: false
,08-29 10:24:01.445  1018  1456 D SettingsProvider: selectionArgs: 1002
08-29 10:24:01.445  1018  1456 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:01.445  1018  1456 D SettingsProvider: ret = -1
,08-29 10:24:01.455  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:01.455  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:24:01.455  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 10:24:01.455  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:01.455  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 10:24:01.455  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:01.465  1946  7562 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 10:24:01.465  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 10:24:01.475  1018  1456 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:24:01.475  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:01.475  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:01.475  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:01.485  1946  7562 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-29 10:24:01.675  1018  1050 I PowerManagerService: [PWL] Off : 75s ago
,08-29 10:24:01.675  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-29 10:24:01.675  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 10:24:01.675  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=13229)
,08-29 10:24:01.945   293   293 E SMD     : DCD OFF,
,08-29 10:24:02.625  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:02.625  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:03.075  1018  1327 E Watchdog: !@Sync 4
,08-29 10:24:03.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:24:04.945   293   293 E SMD     : DCD OFF
,08-29 10:24:04.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:24:05.625  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 10:24:05.625  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33d5a6d1 added. We now have 6 listener(s)
,08-29 10:24:05.625  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:05.625  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:05.625  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@171e536 added. We now have 7 listener(s)
,08-29 10:24:05.625  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:05.635  6778  6834 I System.out: IsBluetoothEnabled,
,08-29 10:24:05.635  6778  6834 D BluetoothAdapter: disable()
,08-29 10:24:05.635  1018  1030 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-29 10:24:05.635  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:05.635  6778  6834 D BluetoothAdapter: enable()
,08-29 10:24:05.645  1018  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 10:24:05.645  1018  1491 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 10:24:05.645  1018  1491 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 10:24:05.645  1018  1491 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 10:24:05.645  1018  1491 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 10:24:05.645  1018  1491 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 10:24:05.645  1018  1491 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 10:24:05.645  1018  1491 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 10:24:05.645  1018  1491 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 10:24:05.645  1018  1491 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:24:05.645  1018  1491 D SettingsProvider: name = bluetooth_on
,08-29 10:24:05.655  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:24:05.655  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:24:05.655  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-29 10:24:05.655  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 10:24:05.685  7546  7546 D BluetoothAdapterState: make
,08-29 10:24:05.695  7546  7546 I bluedroid: init
08-29 10:24:05.695  7546  7567 I BluetoothAdapterState: Entering OffState
,08-29 10:24:05.695  7546  7546 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 10:24:05.695  7546  7546 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 10:24:05.695  7546  7546 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 10:24:05.695  7546  7546 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 10:24:05.695  7546  7546 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-29 10:24:05.695  7546  7546 I bluedroid: get_profile_interface socket
08-29 10:24:05.695  7546  7546 I bluedroid: get_profile_interface map_client
,08-29 10:24:05.695  7546  7570 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-29 10:24:05.705  7546  7546 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-29 10:24:05.705  7546  7570 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 10:24:05.705  7546  7570 E BluetoothServiceJni: populateRssiValuesNative
08-29 10:24:05.705  7546  7570 I bluedroid: getModelRssiValues
08-29 10:24:05.705  7546  7570 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 10:24:05.705  7546  7570 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 10:24:05.705  7546  7570 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 10:24:05.705  7546  7546 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:24:05.715  1018  1018 D SettingsProvider: name = bluetooth_name
,08-29 10:24:05.715  1018  1454 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 10:24:05.715  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.715  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:05.715  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.715  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.715  7546  7554 I bluedroid: config_hci_snoop_log
,08-29 10:24:05.715  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 10:24:05.725  1018  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-29 10:24:05.725  1018  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-29 10:24:05.725  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 10:24:05.725  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 10:24:05.725  7546  7546 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-29 10:24:05.735  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:24:05.735  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 10:24:05.745  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 10:24:05.745  7546  7567 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 10:24:05.745  7546  7567 D BluetoothAdapterProperties: Setting state to 11
,08-29 10:24:05.745  7546  7567 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 10:24:05.745  7546  7567 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 10:24:05.745  7546  7567 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 10:24:05.745  7546  7567 D BluetoothAdapterService: Autoconnection is available 
08-29 10:24:05.745  7546  7567 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 10:24:05.755  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:05.755  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-29 10:24:05.755  7546  7567 D BluetoothSecureManager: getInstant: null
08-29 10:24:05.755  7546  7567 D BluetoothSecureManager: calling getMethod for getService
08-29 10:24:05.755  7546  7567 D BluetoothSecureManager: calling getService
,08-29 10:24:05.755  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 10:24:05.755  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:05.755  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-29 10:24:05.755  1884  1884 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 10:24:05.755  7546  7567 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@c4e3480
,08-29 10:24:05.755  1018  1319 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 10:24:05.755  1018  1208 D BluetoothSecureManagerService: isSecureModeEnabled
,08-29 10:24:05.765  1018  1208 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-29 10:24:05.765  1018  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 10:24:05.765  7546  7567 D BtConfig.SecureMode: isSecureModeOn:false
08-29 10:24:05.765  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 10:24:05.765  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:05.765  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 10:24:05.765  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 10:24:05.765  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 10:24:05.765  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-29 10:24:05.765  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 10:24:05.765  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:05.765  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:24:05.765  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-29 10:24:05.765  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-29 10:24:05.765  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 10:24:05.765  1018  1516 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:24:05.765  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.765  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-29 10:24:05.765  1018  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 10:24:05.765  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 10:24:05.765  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:05.765  1018  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:05.765  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:05.765  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 10:24:05.765  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 10:24:05.775  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-29 10:24:05.775  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 10:24:05.775  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:24:05.775  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:05.775  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 10:24:05.775  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-29 10:24:05.775  7546  7567 D BluetoothBondStateMachine: make
,08-29 10:24:05.775  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 10:24:05.775  7546  7573 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 10:24:05.775  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 10:24:05.775  7546  7567 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 10:24:05.785  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:05.785  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 10:24:05.785  1018  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:24:05.785  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-29 10:24:05.785  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:05.785  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.785  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.785  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 10:24:05.785  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 10:24:05.785  7546  7567 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 10:24:05.785  7546  7546 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 10:24:05.785  7546  7546 D BtGatt.GattService: Received start request. Starting profile...
08-29 10:24:05.785  7546  7546 D BtGatt.GattService: start()
08-29 10:24:05.785  7546  7546 D BtGatt.GattService: start()
08-29 10:24:05.785  7546  7546 I bluedroid: get_profile_interface gatt
,08-29 10:24:05.785  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
08-29 10:24:05.785  7546  7546 D BtGatt.AdvertiseManager: advertise manager created
,08-29 10:24:05.795  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:24:05.795  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 10:24:05.795  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:05.795  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.795  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.795  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 10:24:05.795  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 10:24:05.795  7546  7546 D BtGatt.GattService: mStartError = false
08-29 10:24:05.795  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
08-29 10:24:05.805  7546  7567 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 10:24:05.805  7546  7546 D HeadsetService: Received start request. Starting profile...
,08-29 10:24:05.805  7546  7546 D HeadsetService: start()
,08-29 10:24:05.805  7546  7546 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 10:24:05.805  7546  7546 D HeadsetStateMachine: make
,08-29 10:24:05.805  1018  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:05.805  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.805  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:05.805  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.805  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.805  7546  7546 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 10:24:05.815  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 10:24:05.815  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 10:24:05.815  7546  7567 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 10:24:05.815  1018  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:05.815  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.815  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:05.815  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:24:05.815  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.815  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 10:24:05.815  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 10:24:05.815  7546  7567 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 10:24:05.825  1018  1499 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-29 10:24:05.825  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.825  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:05.825  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.825  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 10:24:05.825  1018  1454 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:05.825  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.825  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:05.825  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.825  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.825  1018  1321 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 10:24:05.825  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.825  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:05.825  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.825  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 10:24:05.825  7546  7546 I bluedroid: get_profile_interface handsfree
08-29 10:24:05.825  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 10:24:05.825  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 10:24:05.825  7546  7567 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 10:24:05.825  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:24:05.835  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.835  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:05.835  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.835  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.835  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-29 10:24:05.835  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 10:24:05.835  7546  7567 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 10:24:05.845  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:05.845  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 10:24:05.845  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:05.845  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.845  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.845  7546  7546 I DualScoManager: Instantiating Dual Sco Manager
,08-29 10:24:05.845  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService,
08-29 10:24:05.845  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 10:24:05.845  7546  7567 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-29 10:24:05.845  7546  7546 I DualScoManager: Set HeadsetServiceHelper
08-29 10:24:05.845  1018  1516 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:05.845  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 10:24:05.845  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:05.855  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:05.855  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:24:05.855  7546  7546 D BluetoothAtMessage: createCMTIContentObservers
,08-29 10:24:05.855  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:05.855  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 10:24:05.855  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 10:24:05.855  7546  7567 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 10:24:05.855  7546  7567 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 10:24:05.855  7546  7567 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 10:24:05.855  1018  1500 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-29 10:24:05.855  1018  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:05.855  1018  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:05.855  1018  1500 D SettingsProvider: selectionArgs: false
08-29 10:24:05.855  1018  1500 D SettingsProvider: selectionArgs: 1002
08-29 10:24:05.855  1018  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:05.855  1018  1500 D SettingsProvider: ret = -1
,08-29 10:24:05.855  7546  7576 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 10:24:05.855  7546  7546 D HeadsetService: mStartError = false
08-29 10:24:05.855  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
,08-29 10:24:05.855  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-29 10:24:05.865  7546  7576 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-29 10:24:05.865  7546  7576 D HeadsetStateMachine: map size, before remove : 0
,08-29 10:24:05.865  7546  7576 D HeadsetStateMachine: map size, after remove: 0
,08-29 10:24:05.865  7546  7546 D A2dpService: Received start request. Starting profile...
08-29 10:24:05.865  7546  7546 D A2dpService: start()
,08-29 10:24:05.865  7546  7546 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 10:24:05.865  7546  7546 I bluedroid: get_profile_interface avrcp
,08-29 10:24:05.875  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:05.875  7546  7546 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 10:24:05.875  7546  7546 D Avrcp   : Initialize Media Controller
08-29 10:24:05.875  7546  7546 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 10:24:05.875  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 10:24:05.875  7546  7546 E Avrcp   : getActiveSessions
08-29 10:24:05.875  7546  7546 D Avrcp   : pick active media Controller
08-29 10:24:05.875  7546  7546 D Avrcp   : Get the active Media Controller 
,08-29 10:24:05.895  7546  7546 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 10:24:05.895  7546  7580 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 10:24:05.895  7546  7546 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 10:24:05.895  7546  7546 D A2dpStateMachine: make
,08-29 10:24:05.895  7546  7546 I bluedroid: get_profile_interface a2dp
,08-29 10:24:05.895  7546  7582 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 10:24:05.895  7546  7546 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 10:24:05.905  7546  7546 D A2dpService: mStartError = false
08-29 10:24:05.905  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
,08-29 10:24:05.905  7546  7546 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 10:24:05.905  7546  7546 D HidService: Received start request. Starting profile...
08-29 10:24:05.905  7546  7546 D HidService: start()
08-29 10:24:05.905  7546  7546 I bluedroid: get_profile_interface hidhost
08-29 10:24:05.905  7546  7546 D HidService: setHidService(): set to: null
08-29 10:24:05.905  7546  7546 D HidService: mStartError = false
08-29 10:24:05.905  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
,08-29 10:24:05.905  7546  7546 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 10:24:05.905  1444  7516 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 10:24:05.905  7546  7581 D A2dpStateMachine: Enter Disconnected: -2
,08-29 10:24:05.905  1444  1444 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 10:24:05.905  1444  1444 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 10:24:05.905  1444  7516 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 10:24:05.905  7546  7546 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 10:24:05.915  7546  7580 D BluetoothMediaBrowser: no now playing list
08-29 10:24:05.915  7546  7580 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 10:24:05.915  7546  7546 D HealthService: Received start request. Starting profile...
08-29 10:24:05.915  7546  7546 D HealthService: start()
,08-29 10:24:05.915  7546  7546 I bluedroid: get_profile_interface health
,08-29 10:24:05.915  7546  7546 D HealthService: mStartError = false
08-29 10:24:05.915  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
08-29 10:24:05.915  7546  7546 D HeadsetStateMachine: Proxy object connected
,08-29 10:24:05.915  7546  7546 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 10:24:05.915  7546  7546 D PanService: Received start request. Starting profile...
08-29 10:24:05.915  7546  7546 D PanService: start()
08-29 10:24:05.915  7546  7546 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 10:24:05.915  7546  7546 I bluedroid: get_profile_interface pan
,08-29 10:24:05.915  7546  7546 D PanService: mStartError = false
,08-29 10:24:05.915  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
,08-29 10:24:05.915  7546  7546 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-29 10:24:05.915  7546  7546 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 10:24:05.915  7546  7546 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-29 10:24:05.915  1018  3377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 10:24:05.915  7546  7576 D HeadsetStateMachine: Disconnected process message: 11
,08-29 10:24:05.925  7546  7576 D HeadsetStateMachine: Disconnected process message: 18
,08-29 10:24:05.925  7546  7546 D BluetoothMapService: Received start request. Starting profile...
08-29 10:24:05.925  7546  7546 D BluetoothMapService: start()
,08-29 10:24:05.925  7546  7546 D BluetoothMapService: mStartError = false
08-29 10:24:05.925  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
,08-29 10:24:05.925  7546  7546 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 10:24:05.925  7546  7546 D SapService: Received start request. Starting profile...
,08-29 10:24:05.925  7546  7546 D SapService: start()
08-29 10:24:05.925  7546  7546 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 10:24:05.925  7546  7546 I bluedroid: get_profile_interface sap
08-29 10:24:05.925  7546  7546 D SapService: mStartError = false
08-29 10:24:05.925  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
08-29 10:24:05.925  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 10:24:05.925  7546  7546 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 10:24:05.925  7546  7546 D BluetoothA2dp: Proxy object connected
08-29 10:24:05.925  7546  7546 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 10:24:05.925  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 10:24:05.925  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-29 10:24:05.925  7546  7576 D HeadsetStateMachine: Disconnected process message: 10
,08-29 10:24:05.925  7546  7576 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 10:24:05.925  7546  7576 D HeadsetStateMachine: Disconnected process message: 11
,08-29 10:24:05.925  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 10:24:05.925  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 10:24:05.945  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 10:24:05.945  7546  7546 E BluetoothAdapterService(729692506): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 10:24:05.945  7546  7567 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 10:24:05.955  7546  7567 I bluedroid: enable
08-29 10:24:05.955  7546  7567 I bt_hci_bdroid: init
,08-29 10:24:05.955  7546  7586 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-29 10:24:05.955  7546  7567 I bt_vendor: bt-vendor : init,
08-29 10:24:05.955  7546  7567 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 10:24:05.955  7546  7567 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 10:24:05.955  7546  7567 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 10:24:05.955  7546  7567 D bt_userial_mct: userial_init
,08-29 10:24:05.955  7546  7567 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 10:24:05.955  7546  7567 I bt_vendor: Starting hciattach daemon
08-29 10:24:05.955  7546  7567 I bt_vendor: try to set false
,08-29 10:24:05.955  7546  7567 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 10:24:05.955  7546  7567 I bt_vendor: Starting hciattach daemon
,08-29 10:24:05.955  7546  7567 I bt_vendor: try to set true
,08-29 10:24:05.975  7590  7590 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-29 10:24:05.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 10:24:06.015  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-29 10:24:06.025  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 10:24:06.035  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 10:24:06.045  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-29 10:24:06.055  7602  7602 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 10:24:06.065  7603  7603 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-29 10:24:06.365  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-29 10:24:06.375  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 10:24:06.415  7546  7567 I bt_vendor: bluetooth satus is on,
,08-29 10:24:06.415  7546  7588 D bt_userial_mct: userial_open(port:0)
08-29 10:24:06.415  7546  7588 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-29 10:24:06.415  7546  7588 I bt_vendor: Done intiailizing UART
08-29 10:24:06.415  7546  7588 I bt_vendor: Done intiailizing UART
08-29 10:24:06.415  7546  7588 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-29 10:24:06.415  7546  7588 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 10:24:06.425  7546  7609 D bt_userial_mct: Entering userial_read_thread()
,08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_SAP
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 10:24:06.425  7546  7586 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-29 10:24:06.515  7546  7586 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 10:24:06.525  7546  7586 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4219ed1 
,08-29 10:24:06.525  7546  7586 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4219ed1 
,08-29 10:24:06.535  7546  7570 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 10:24:06.545  7546  7570 E bt-btif : Calling BTA_HhEnable
,08-29 10:24:06.545  7546  7570 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 10:24:06.545  7546  7570 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 10:24:06.545  7546  7570 E BluetoothServiceJni: populateRssiValuesNative
,08-29 10:24:06.545  7546  7570 I bluedroid: getModelRssiValues
08-29 10:24:06.545  7546  7570 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-29 10:24:06.545  7546  7570 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 10:24:06.555  1018  1018 D SettingsProvider: name = bluetooth_name
,08-29 10:24:06.555  7546  7570 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 10:24:06.565  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:06.565  7546  7570 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 10:24:06.565  7546  7570 D BluetoothAdapterProperties: Scan Mode:20
08-29 10:24:06.565  7546  7570 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 10:24:06.565  7546  7570 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-29 10:24:06.565  7546  7570 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-29 10:24:06.565  7546  7570 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-29 10:24:06.565  7546  7570 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 10:24:06.565  7546  7570 E bt-btif : btif_sock_init: !vhci_init
,08-29 10:24:06.565  7546  7570 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-29 10:24:06.565  7546  7570 D IOP_DB_BT: db_open: db_open : handle 3028623376l, read 13894 bytes onto local cache
08-29 10:24:06.565  7546  7570 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-29 10:24:06.565  7546  7570 D IOP_DB_BT: db_query: result 1
08-29 10:24:06.565  7546  7570 I         : iop_db_open: iop_db_open status 0
08-29 10:24:06.565  7546  7570 D bte_conf: Device ID record 1 : primary
,08-29 10:24:06.565  7546  7570 D bte_conf:   vendorId            = 0075
08-29 10:24:06.565  7546  7570 D bte_conf:   vendorIdSource      = 0001
08-29 10:24:06.565  7546  7570 D bte_conf:   product             = 0100
,08-29 10:24:06.565  7546  7570 D bte_conf:   version             = 0200
08-29 10:24:06.565  7546  7570 D bte_conf:   clientExecutableURL = 
08-29 10:24:06.565  7546  7570 D bte_conf:   serviceDescription  = 
,08-29 10:24:06.565  7546  7570 D bte_conf:   documentationURL    = 
08-29 10:24:06.565  7546  7570 D bte_conf: bte_load_did_conf no section named DID2.
08-29 10:24:06.565  7546  7570 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 10:24:06.565  7546  7567 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 10:24:06.575  7546  7567 D BluetoothAdapterProperties: ScanMode =  20
,08-29 10:24:06.575  7546  7567 D BluetoothAdapterProperties: State =  11
,08-29 10:24:06.575  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 10:24:06.575  7546  7567 D BluetoothAdapterProperties: Setting state to 12
,08-29 10:24:06.575  7546  7567 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 10:24:06.575  7546  7609 E bt_mct  : hci lib postload completed
,08-29 10:24:06.575  7546  7570 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 10:24:06.575  7546  7570 D BluetoothAdapterProperties: Scan Mode:21
,08-29 10:24:06.575  7546  7570 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 10:24:06.575  1018  1031 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-29 10:24:06.585  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 10:24:06.585  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:06.585  1018  1031 D SettingsProvider: selectionArgs: false
,08-29 10:24:06.585  1018  1031 D SettingsProvider: selectionArgs: 1002
,08-29 10:24:06.585  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 10:24:06.585  1018  1031 D SettingsProvider: ret = -1
,08-29 10:24:06.585  7546  7567 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 10:24:06.585  7546  7567 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 10:24:06.585  1018  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:06.585  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.595  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:06.595  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:06.595  1018  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:24:06.595  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.595  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:06.595  7546  7567 D BluetoothAdapterService: Autoconnection is available 
08-29 10:24:06.595  7546  7567 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 10:24:06.595  7546  7567 D BluetoothAdapterService: starting service from this receiver
,08-29 10:24:06.595  1946  1956 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.595  1946  1956 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:24:06.595  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 10:24:06.595  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.595  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.595  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.595  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.595  7546  7567 I BluetoothAdapterState: Entering On State from state = 11
,08-29 10:24:06.605  1444  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:24:06.605  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 10:24:06.605  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:24:06.605  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:06.605  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:24:06.605  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.605  1444  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:24:06.605  7546  7554 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 10:24:06.605  7546  7554 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.605  3066  6900 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 10:24:06.625  7546  7546 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:06.665  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:06.665  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:06.665  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:06.665  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f193c37 added. We now have 8 listener(s)
08-29 10:24:06.665  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:06.675  1018  1456 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 10:24:06.675  1018  1456 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 10:24:06.675  1018  1456 D SecContentProvider2: mCursor = null
,08-29 10:24:06.675  1018  1456 D WifiService: setWifiEnabled: false pid=6778, uid=10171
,08-29 10:24:06.675  1018  1456 D SettingsProvider: name = wifi_on
,08-29 10:24:06.675  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:06.675  1018  1319 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 10:24:06.675  1018  1319 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 10:24:06.675  1018  1319 D SecContentProvider2: mCursor = null
,08-29 10:24:06.685  1018  1319 D WifiService: setWifiEnabled: true pid=6778, uid=10171
,08-29 10:24:06.685  1018  1319 W ActivityManager: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 10:24:06.685  1018  1319 W WifiService: Failed getting userId using ActivityManagerNative
08-29 10:24:06.685  1018  1319 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6778, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 10:24:06.685  1018  1319 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 10:24:06.685  1018  1319 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 10:24:06.685  1018  1319 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 10:24:06.685  1018  1319 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 10:24:06.685  1018  1319 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 10:24:06.685  1018  1319 D SettingsProvider: name = wifi_on
,08-29 10:24:06.685  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 10:24:06.765  1018  3361 D SSRM:n  : SIOP:: AP = 340
,08-29 10:24:06.775  1018  1047 I art     : Explicit concurrent mark sweep GC freed 22157(1258KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.784ms total 161.848ms
08-29 10:24:06.775  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 10:24:06.775  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.775  1018  1047 W ActivityManager: userId = 0, bbcId = -10000,
08-29 10:24:06.775  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:24:06.775  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth,
,08-29 10:24:06.775  1177  3886 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.775  1177  3886 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.775  3066  3074 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.775  3066  3074 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.775  1444  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:24:06.775  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:24:06.775  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:24:06.775  1018  1047 W ActivityManager: userId = 0, bbcId = -10000,
08-29 10:24:06.775  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-29 10:24:06.775  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:24:06.775  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 10:24:06.775  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 10:24:06.775  1444  1463 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 10:24:06.775  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 10:24:06.775  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 10:24:06.775  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 10:24:06.775  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 10:24:06.775  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 10:24:06.775  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 10:24:06.785  1018  1018 D BluetoothA2dp: Proxy object connected
,08-29 10:24:06.785  3066  6900 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 10:24:06.785  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 10:24:06.785  7546  7546 I BluetoothPbapService: Handler(): got msg=1
08-29 10:24:06.785  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.785  1018  1500 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 10:24:06.785  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.785  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.785  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.785  6778  6786 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.785  6778  6786 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.785  1444  1463 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.785  1444  1463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.785  3066  3075 D Bluetoothsap: onBluetoothStateChange: up=true
,08-29 10:24:06.785  3066  3075 D Bluetoothsap: Binding service...
,08-29 10:24:06.785  3066  3066 D BluetoothMap: Proxy object connected
08-29 10:24:06.785  3066  3066 D MapProfile: Bluetooth service connected
08-29 10:24:06.785  3066  3066 D BluetoothMap: getConnectedDevices()
,08-29 10:24:06.795  7546  7616 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 10:24:06.795  3066  3075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 10:24:06.795  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 10:24:06.795  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.795  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.795  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.795  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.795  3066  3075 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 10:24:06.795  3066  3074 D BluetoothPan: Binding service...
,08-29 10:24:06.795  3066  3066 D BluetoothInputDevice: Proxy object connected,
08-29 10:24:06.795  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 10:24:06.795  3066  3066 D HidProfile: Bluetooth service connected
08-29 10:24:06.795  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 10:24:06.795  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.795  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.795  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 10:24:06.795  7546  7616 D BluetoothSocket: bindListen(): myUserId = 0,
08-29 10:24:06.795  7546  7616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:06.805  1460  1485 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 10:24:06.805  1460  1485 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.805  7546  7616 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-29 10:24:06.805  7546  7616 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 10:24:06.805  7546  7616 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 10:24:06.805  7546  7616 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d2241a4
08-29 10:24:06.805  1478  1849 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.805  1478  1849 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.805  7457  7468 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.805  7457  7468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 10:24:06.805  7546  7616 D BluetoothSocket: channel: 19
08-29 10:24:06.805  7546  7616 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-29 10:24:06.805  3066  6900 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:24:06.805  3066  3066 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 10:24:06.805  3066  3066 D SapProfile: Bluetooth service connected
,08-29 10:24:06.805  3066  3066 D Bluetoothsap: getConnectedDevices()
,08-29 10:24:06.805  3066  6900 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:24:06.805  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 10:24:06.805  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.805  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.805  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.805  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.805  7546  7554 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 10:24:06.805  3066  3066 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 10:24:06.805  1444  7516 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:24:06.805  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:24:06.805  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 10:24:06.805  3066  3066 D PanProfile: Bluetooth service connected
,08-29 10:24:06.815  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.815  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.815  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.815  1444  7516 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:24:06.815  3066  3074 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 10:24:06.815  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 10:24:06.815  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.815  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.815  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.815  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.815  3066  3066 D BluetoothA2dp: Proxy object connected
08-29 10:24:06.815  3066  3066 D A2dpProfile: Bluetooth service connected
,08-29 10:24:06.815  3066  3075 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:24:06.815  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:24:06.815  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:24:06.815  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.815  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 10:24:06.815  3066  3066 D BluetoothPbap: Proxy object connected
08-29 10:24:06.815  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 10:24:06.815  3066  3066 D PbapServerProfile: Bluetooth service connected
,08-29 10:24:06.815  3066  3075 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:24:06.825  1478  1668 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 10:24:06.825  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 10:24:06.825  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 10:24:06.825  3066  3066 D HeadsetProfile: Bluetooth service connected
08-29 10:24:06.825  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.825  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.825  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.825  1478  1668 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 10:24:06.825  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 10:24:06.825  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 10:24:06.825  1018  1047 D BluetoothPan: Binding service...
,08-29 10:24:06.825  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 10:24:06.825  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.825  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 10:24:06.825  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 10:24:06.825  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 10:24:06.825  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:06.825  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-29 10:24:06.825  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 10:24:06.835  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 10:24:06.835  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 10:24:06.835  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:24:06.835  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:24:06.835  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 10:24:06.845  1177  1177 D BluetoothTile:  getBluetoothState : 12
08-29 10:24:06.845  1444  1444 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1cec18e3, true
,08-29 10:24:06.845  1444  1444 D BluetoothHeadset: registerMessageListener
,08-29 10:24:06.845  1177  1778 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 10:24:06.845  1884  1884 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 10:24:06.845  1018  1516 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 10:24:06.845  1018  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 10:24:06.845  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 10:24:06.855  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:06.855  7546  7617 D HeadsetService: registerMessageListener
08-29 10:24:06.855  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:24:06.855  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.855  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.855  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:06.855  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:06.865  7546  7617 D HeadsetService: registerMessageListener
,08-29 10:24:06.865  1444  1444 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 10:24:06.865  7546  7576 D HeadsetStateMachine: Disconnected process message: 70
08-29 10:24:06.865  1444  1444 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 10:24:06.865  7546  7576 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@306e1b0d
,08-29 10:24:06.865  3066  3066 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:06.865  1444  1444 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 10:24:06.865  1444  1444 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 10:24:06.865  1444  1444 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 10:24:06.875  7546  7619 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-29 10:24:06.875  3066  3066 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-29 10:24:06.875  3066  3066 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-29 10:24:06.875  3066  3066 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-29 10:24:06.875  3066  3066 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-29 10:24:06.875  7546  7576 D HeadsetStateMachine: Disconnected process message: 9
,08-29 10:24:06.875  7546  7576 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 10:24:06.875   283   693 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-29 10:24:06.875   283   693 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-29 10:24:06.875   283   693 V voice   : voice_set_parameters: exit with code(-2)
08-29 10:24:06.875   283   693 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 10:24:06.875   283   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 10:24:06.875   283   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 10:24:06.875   283   693 V audio_hw_primary: adev_set_parameters: exit
,08-29 10:24:06.885  7546  7576 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 10:24:06.885  7546  7619 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 10:24:06.885  7546  7619 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:06.885  7546  7619 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-29 10:24:06.885  7546  7619 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 10:24:06.885  7546  7619 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 10:24:06.885  7546  7619 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@242daac2
,08-29 10:24:06.885  7546  7619 D BluetoothSocket: channel: 5
,08-29 10:24:06.895  3066  3066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 10:24:06.895  1018  1516 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 10:24:06.895  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.895  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:06.895  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.895  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 10:24:06.905  3066  3066 D DockEventReceiver: finishStartingService: stopping service
,08-29 10:24:06.905  3066  3066 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 10:24:06.905  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 10:24:06.905  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 10:24:06.915  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
,08-29 10:24:06.915  7546  7546 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 10:24:06.925  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 10:24:06.925  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.925  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.925  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:06.925  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 10:24:06.935  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 10:24:06.935  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:24:06.935  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 10:24:06.945  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.945  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:06.945  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:06.945  1946  7632 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 10:24:06.945  1018  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 10:24:06.945  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 10:24:06.955  1018  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:24:06.955  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:06.955  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:06.955  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:06.965  7546  7635 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 10:24:06.965  7546  7635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 10:24:06.965  7546  7635 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-29 10:24:06.965  7546  7635 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 10:24:06.965  7546  7635 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 10:24:06.965  7546  7635 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1afb10e
08-29 10:24:06.965  7546  7635 D BluetoothSocket: channel: 12
08-29 10:24:06.965  7546  7635 I BtOppRfcommListener: Accept thread started.
,08-29 10:24:06.975  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 10:24:06.975  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:06.975  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:06.975  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:06.975  1946  7632 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 10:24:06.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:07.035  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-29 10:24:07.035  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 10:24:07.035  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-29 10:24:07.035  1018  1045 D Tethering: interfaceAdded wlan0
08-29 10:24:07.035  1018  1131 E Tethering: No numeric data
,08-29 10:24:07.035  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 10:24:07.035  1018  1131 D Tethering: clearTetheredNotification()
,08-29 10:24:07.035  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:07.035  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:24:07.035  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:24:07.035  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:24:07.045  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 10:24:07.045  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-29 10:24:07.045  1177  1177 D HotspotTile: updateTetherState():false, false,
08-29 10:24:07.045  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:07.045  1018  1124 V NetworkStats: performPollLocked() took 6ms
,08-29 10:24:07.045  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:07.045  1018  1045 D Tethering: interfaceAdded p2p0
08-29 10:24:07.045  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring,
,08-29 10:24:07.055  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 10:24:07.055  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:24:07.055  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
,08-29 10:24:07.055   278   990 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-29 10:24:07.055   278   990 D SoftapController: Softap fwReload - Ok
,08-29 10:24:07.065   278   990 D CommandListener: Setting iface cfg
08-29 10:24:07.065   278   990 D CommandListener: Trying to bring down wlan0
,08-29 10:24:07.065   278   990 D CommandListener: Clearing all IP addresses on wlan0
08-29 10:24:07.065  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
08-29 10:24:07.075  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 10:24:07.075  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:24:07.075  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 10:24:07.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:07.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:07.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:07.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:07.075  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:07.075  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-29 10:24:07.075  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 10:24:07.075  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:24:07.075  1177  1177 D HotspotTile: onReceive : 2, 0
,08-29 10:24:07.085  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:24:07.085  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:07.085  1018  1456 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 10:24:07.085  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:24:07.085  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:07.085  1018  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:07.085  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:24:07.095  1602  1602 I Hs20UtilService: Starting #19
,08-29 10:24:07.095  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 10:24:07.095  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 10:24:07.095  1602  1639 I Hs20UtilService: Message received 5011
,08-29 10:24:07.095  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 10:24:07.095  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 10:24:07.115  7638  7638 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 10:24:07.115  7638  7638 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 10:24:07.115  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 10:24:07.125  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-29 10:24:07.135   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7638,
08-29 10:24:07.135   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 10:24:07.135  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-29 10:24:07.135  7638  7638 I wpa_supplicant: ssSupport state is = 1
08-29 10:24:07.135  7638  7638 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 10:24:07.135  7638  7638 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-29 10:24:07.135   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7638
08-29 10:24:07.135   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-29 10:24:07.285   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-29 10:24:07.285  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-29 10:24:07.335  7638  7638 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-29 10:24:07.335  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 10:24:07.345  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-29 10:24:07.345   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7638
08-29 10:24:07.345   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 10:24:07.345  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 10:24:07.345  7638  7638 I wpa_supplicant: ssSupport state is = 1
08-29 10:24:07.345  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:24:07.345  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 10:24:07.345  7638  7638 E wpa_supplicant: SIM READ ERROR
08-29 10:24:07.345  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:24:07.345  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 10:24:07.345  7638  7638 E wpa_supplicant: SIM READ ERROR
08-29 10:24:07.345  7638  7638 I wpa_supplicant: Blacklist: Clear (all) 
08-29 10:24:07.355  7638  7638 I wpa_supplicant: wpa_default_ap_write_once
08-29 10:24:07.355  7638  7638 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-29 10:24:07.355  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:24:07.355  7638  7638 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 10:24:07.355  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:24:07.355  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 10:24:07.355  7638  7638 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-29 10:24:07.355  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 10:24:07.355  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:24:07.355  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-29 10:24:07.355  1018  1131 D Tethering: InitialState.processMessage what=4
,08-29 10:24:07.365  1018  1131 E Tethering: No numeric data
08-29 10:24:07.365  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-29 10:24:07.365  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 10:24:07.365  1177  1177 D HotspotTile: updateTetherState():false, false,
08-29 10:24:07.365  1018  1131 D Tethering: clearTetheredNotification(),
08-29 10:24:07.365  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:24:07.365  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 10:24:07.375  1018  1124 V NetworkStats: performPollLocked() took 5ms
,08-29 10:24:07.365  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:24:07.365  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 10:24:07.375  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:07.375  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 10:24:07.375  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:07.405  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 10:24:07.515  7638  7638 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-29 10:24:07.515  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-29 10:24:07.525  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 10:24:07.535   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7638
08-29 10:24:07.535   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 10:24:07.535  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-29 10:24:07.535  7638  7638 I wpa_supplicant: ssSupport state is = 1
08-29 10:24:07.535  7638  7638 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-29 10:24:07.535  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 10:24:07.545  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 10:24:07.545   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7638
08-29 10:24:07.545   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-29 10:24:07.545  7638  7638 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 10:24:07.545  7638  7638 I wpa_supplicant: ssSupport state is = 1
08-29 10:24:07.545  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:24:07.545  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:24:07.545  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 10:24:07.545  7638  7638 E wpa_supplicant: SIM READ ERROR
08-29 10:24:07.545  7638  7638 I wpa_supplicant: wpa_default_ap_write_once
08-29 10:24:07.545  7638  7638 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 10:24:07.545  7638  7638 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 10:24:07.545  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 10:24:07.545  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-29 10:24:07.555  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 10:24:07.555  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 10:24:07.555  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-29 10:24:07.635  7638  7638 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 10:24:07.635  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 10:24:07.675  7638  7638 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-29 10:24:07.675  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-29 10:24:07.675  7638  7638 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 10:24:07.685  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-29 10:24:07.685  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 10:24:07.685  7638  7638 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-29 10:24:07.685  7638  7638 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 10:24:07.685  7638  7638 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 10:24:07.685  7638  7638 E wpa_supplicant: SIM READ ERROR
08-29 10:24:07.685  7638  7638 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 10:24:07.715  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-29 10:24:07.725  7638  7638 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 10:24:07.725  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-29 10:24:07.725  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 10:24:07.735  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 10:24:07.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:07.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:07.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:07.735  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:07.735  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 10:24:07.735  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 10:24:07.735  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:24:07.735  1177  1778 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 10:24:07.735  1177  1177 D HotspotTile: onReceive : 3, 0
,08-29 10:24:07.745  3066  3066 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 10:24:07.745  1018  2068 V SAMP_SPCM_test: CSC File load.. 
,08-29 10:24:07.755  1018  1127 E WifiConfigStore: Not a HS20
,08-29 10:24:07.755  1018  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:07.755  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:07.755  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn,
08-29 10:24:07.765  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 10:24:07.805  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize,
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time,
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi,
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-29 10:24:07.815  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,08-29 10:24:07.815  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 10:24:07.815  1018  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-29 10:24:07.815  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:07.815  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:07.815  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:24:07.815  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 10:24:07.825  1602  1602 I Hs20UtilService: Starting #20,
08-29 10:24:07.825  1602  1639 I Hs20UtilService: Message received 5011
,08-29 10:24:07.825  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-29 10:24:07.825  7638  7638 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 10:24:07.825  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 10:24:07.825  7638  7638 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 10:24:07.825  7638  7638 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 10:24:07.825  7638  7638 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 10:24:07.825  1018  2068 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-29 10:24:07.825  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 10:24:07.825  7638  7638 I wpa_supplicant: First Scan Start
,08-29 10:24:07.825  7638  7638 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 10:24:07.825  1018  2068 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:07.825  1018  2068 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:07.825  1018  2068 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:07.825  1018  2068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:07.825  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 10:24:07.825  6592  6592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 10:24:07.825  6592  6592 D SecurityLogAgent: StateMachine : Current State = 1
08-29 10:24:07.825  6592  6592 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 10:24:07.835  7645  7645 E Zygote  : MountEmulatedStorage()
08-29 10:24:07.835  7645  7645 E Zygote  : v2
08-29 10:24:07.835  7645  7645 I libpersona: KNOX_SDCARD checking this for 1000
08-29 10:24:07.835  7645  7645 I libpersona: KNOX_SDCARD not a persona
08-29 10:24:07.835  1018  2068 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7645 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 10:24:07.835  7645  7645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:24:07.845  7645  7645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:24:07.845  7645  7645 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 10:24:07.845  7045  7045 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 10:24:07.855  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
08-29 10:24:07.855  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 10:24:07.855  1018  1127 I WifiNative-HAL: startHal
08-29 10:24:07.855  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d6c488c
08-29 10:24:07.855  1018  1127 I WifiNative-HAL: Could not start hal
08-29 10:24:07.855  1018  1127 E WifiNative-wlan0: do suspend true
08-29 10:24:07.855  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-29 10:24:07.865  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 10:24:07.865  1018  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.865  1018  1150 I WifiNative-HAL: startHal
08-29 10:24:07.865  1018  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9ec809bc
08-29 10:24:07.865  1018  1150 I WifiNative-HAL: Could not start hal
08-29 10:24:07.865  1018  1150 E WifiScanningService: could not start HAL
08-29 10:24:07.865  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-29 10:24:07.865  1018  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:07.865  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 10:24:07.865  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 10:24:07.865  1018  1127 E WifiNative-wlan0: invaild command id : 215
08-29 10:24:07.865  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 10:24:07.865  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 10:24:07.865  1018  1127 E WifiNative-wlan0: invaild command id : 215
08-29 10:24:07.865  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
08-29 10:24:07.865   278   990 D CommandListener: Setting iface cfg
08-29 10:24:07.865   278   990 D CommandListener: Trying to bring up p2p0
08-29 10:24:07.865  1018  1126 D WifiP2pService: P2pEnablingState
08-29 10:24:07.865  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 10:24:07.865  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 10:24:07.865  1018  1126 D WifiP2pService: P2p socket connection successful
08-29 10:24:07.865  1018  1126 D WifiP2pService: P2pEnabledState
08-29 10:24:07.865  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 10:24:07.875  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:24:07.875  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 10:24:07.875  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 10:24:07.875  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:24:07.875  1018  1048 D WifiDisplayController: disconnect
08-29 10:24:07.875  1018  1048 D WifiDisplayController: updateConnection
08-29 10:24:07.875  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 10:24:07.875  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 10:24:07.875  7638  7638 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 10:24:07.875  7638  7638 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 10:24:07.875  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 10:24:07.875  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-29 10:24:07.875  7638  7638 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 10:24:07.875  1018  1127 E WifiStateMachine: Failed to set frequency band 0
08-29 10:24:07.885  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:24:07.885  1018  1127 D SecContentProvider2: mCursor = null
08-29 10:24:07.885  7645  7645 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 10:24:07.885  7645  7645 D ActivityThread: Added TimaKeyStore provider
08-29 10:24:07.885  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 10:24:07.885  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 10:24:07.885  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-29 10:24:07.885  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 10:24:07.885  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 10:24:07.885  1018  1126 D WifiP2pService: DeviceAddress: 0a:76:28
08-29 10:24:07.885  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 10:24:07.885  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:24:07.885  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:24:07.885  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 10:24:07.885  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:24:07.885  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 10:24:07.885  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 10:24:07.885  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 10:24:07.885  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 10:24:07.885  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 10:24:07.885  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  secondary type: null
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  wps: 0
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  grpcapab: 0
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  devcapab: 0
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  status: 3
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  wfdInfo: null
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-29 10:24:07.885  1018  1048 D WifiDisplayController:  SConnectInfo : null
,08-29 10:24:07.885  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:24:07.895  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 10:24:07.895  7015  7015 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 10:24:07.895  7015  7015 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 10:24:07.905  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 10:24:07.905  1018  1126 D WifiP2pService: InactiveState
,08-29 10:24:07.905  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
08-29 10:24:07.905  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 10:24:07.905  7638  7638 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 10:24:07.905  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
08-29 10:24:07.905  7645  7645 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 10:24:07.905  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 10:24:07.915  7030  7030 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 10:24:07.945  1018  2068 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-29 10:24:07.945   293   293 E SMD     : DCD OFF
,08-29 10:24:07.985   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 10:24:08.025  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 10:24:08.025  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 10:24:08.025  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:08.695  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:08.705  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:08.705  6778  6834 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 10:24:08.705  6778  6834 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 10:24:08.715  6778  6834 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c07ad0a Bundle[{}]
,08-29 10:24:08.715  6778  6834 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 10:24:08.715  6778  6834 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 10:24:08.715  6778  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 10:24:08.715  6778  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 10:24:08.715  6778  6834 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 10:24:08.715  6778  6834 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 10:24:08.725  6778  6834 I System.out: Running OutgoingSocketThread
,08-29 10:24:08.725  6778  7662 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1360)
,08-29 10:24:08.725  6778  7662 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55382
,08-29 10:24:08.725  6778  7662 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 10:24:08.985   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-29 10:24:09.125  7638  7638 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
08-29 10:24:09.125  7638  7638 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-29 10:24:09.125  7638  7638 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 10:24:09.125  7638  7638 I wpa_supplicant: Trying to associate with  'G700'
08-29 10:24:09.125  7638  7638 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 10:24:09.125  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 10:24:09.125  1018  7643 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 10:24:09.145  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:24:09.145  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:24:09.245  7638  7638 E wpa_supplicant: Cmd 35605 not handled
,08-29 10:24:09.245  7638  7638 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 10:24:09.245  7638  7638 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-29 10:24:09.245  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 10:24:09.245  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:24:09.245  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-29 10:24:09.245  7638  7638 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
,08-29 10:24:09.245  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 10:24:09.245  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-29 10:24:09.245  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 10:24:09.245  7638  7638 I wpa_supplicant: Associated with F4.99.3E,
08-29 10:24:09.255  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 10:24:09.245  7638  7638 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 10:24:09.245  7638  7638 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-29 10:24:09.245  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-29 10:24:09.245  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:24:09.245  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-29 10:24:09.245  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 10:24:09.245  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-29 10:24:09.255  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 10:24:09.255  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-29 10:24:09.255  7638  7638 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 10:24:09.255  1018  1131 E Tethering: No numeric data
08-29 10:24:09.255  7638  7638 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 10:24:09.255  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 10:24:09.255  1018  1131 D Tethering: clearTetheredNotification()
08-29 10:24:09.255  7638  7638 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 10:24:09.255  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 10:24:09.255  7638  7638 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 10:24:09.255  7638  7638 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 10:24:09.255  7638  7638 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 10:24:09.255  7638  7638 I wpa_supplicant: Blacklist: Clear (temp) 
,08-29 10:24:09.265  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 10:24:09.255  7638  7638 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 10:24:09.265  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 10:24:09.265  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-29 10:24:09.265  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:24:09.265  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:09.265  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 10:24:09.265  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:24:09.265  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:24:09.265  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:24:09.265  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 10:24:09.265  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 10:24:09.275  1018  1124 V NetworkStats: performPollLocked() took 9ms
,08-29 10:24:09.275  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:09.275  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 10:24:09.275  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:09.275  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:09.285  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 10:24:09.285  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:24:09.285  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:24:09.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:09.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:09.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:09.285  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:09.295  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-29 10:24:09.295  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 10:24:09.295  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:09.295  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-29 10:24:09.295  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 10:24:09.295  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 10:24:09.295  1018  1208 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:24:09.295  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:24:09.305  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:09.305  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:09.305  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:24:09.305  1602  1602 I Hs20UtilService: Starting #21
,08-29 10:24:09.305  1602  1639 I Hs20UtilService: Message received 5007
,08-29 10:24:09.305  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 10:24:09.305  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 10:24:09.305  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 10:24:09.305  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:24:09.305  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 10:24:09.305  3066  3066 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 10:24:09.305  3066  3881 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 10:24:09.315   278   990 D CommandListener: Setting iface cfg
,08-29 10:24:09.315  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-29 10:24:09.325  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 10:24:09.325  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:24:09.325  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 10:24:09.325  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:24:09.335  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 10:24:09.335  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 10:24:09.335  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:09.335  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:09.335  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:09.335  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:09.345  1018  1127 E WifiNative-wlan0: do suspend false
,08-29 10:24:09.345  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-29 10:24:09.345  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 10:24:09.345  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 10:24:09.345  1018  1127 D SecContentProvider2: mCursor = null
,08-29 10:24:09.565  7665  7665 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 10:24:09.565  7665  7665 I dhcpcd  : version 5.5.6 starting,
,08-29 10:24:09.565  7665  7665 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 10:24:09.625  7665  7665 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-29 10:24:09.625  7665  7665 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 10:24:09.625  7665  7665 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 10:24:09.625  7665  7665 I dhcpcd  : bssid match
08-29 10:24:09.625  7665  7665 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 10:24:09.715  7665  7665 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-29 10:24:09.725  6778  6834 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1361)
08-29 10:24:09.725  6778  6834 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1361)
,08-29 10:24:09.725  6778  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1366)
08-29 10:24:09.725  6778  6834 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-29 10:24:09.725  6778  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1367)
,08-29 10:24:09.735  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:09.735  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27a195a4 added. We now have 2 listener(s)
,08-29 10:24:09.735  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 10:24:09.735  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:24:09.735  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:09.735  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:09.735  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3cdf0d added. We now have 9 listener(s)
08-29 10:24:09.735  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:09.735  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:24:09.745  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:09.745  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:09.745  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:09.745  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:09.745  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:09.745  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@273b64d3 added. We now have 3 listener(s)
,08-29 10:24:09.755  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b346810 added. We now have 10 listener(s)
08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:09.755  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:09.755  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:09.755  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:09.755  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:09.755  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27a195a4 removed from the list
,08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3cdf0d removed from the list
08-29 10:24:09.755  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:09.755  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:09.755  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3cdf0d not in the list
08-29 10:24:09.755  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b346810 removed from the list
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:09.755  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:09.755  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:09.755  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@273b64d3 removed from the list
,08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:09.755  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19655f09 added. We now have 2 listener(s)
,08-29 10:24:09.765  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 10:24:09.765  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:09.765  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:09.765  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:09.765  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d14650e added. We now have 9 listener(s)
08-29 10:24:09.765  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-29 10:24:09.765  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:09.765  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:09.775  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:09.775  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:09.775  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:09.775  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:09.775  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:09.775  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34dff53c added. We now have 3 listener(s)
,08-29 10:24:09.775  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:09.785  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 10:24:09.785  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:24:09.785  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:09.785  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:09.785  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@287be2c5 added. We now have 10 listener(s)
,08-29 10:24:09.785  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:09.785  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 10:24:09.785  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:09.785  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 10:24:09.785  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:09.785  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:24:09.795  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:24:09.795  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:24:09.795  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:24:09.805  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:24:09.805  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 10:24:09.805  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:24:09.805  7546  7618 D BtGatt.GattService: registerClient() - UUID=c387de81-2355-42aa-b59e-14c0dbce58c5
,08-29 10:24:09.825  7665  7665 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-29 10:24:09.845  7546  7570 D BtGatt.GattService: onClientRegistered() - UUID=c387de81-2355-42aa-b59e-14c0dbce58c5, clientIf=6,
,08-29 10:24:09.855  6778  6788 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 10:24:09.855  7546  7618 D BtGatt.GattService: start scan with filters
,08-29 10:24:09.855  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:24:09.855  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 10:24:09.855  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:24:09.855  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:24:09.855  7546  7575 D BtGatt.ScanManager: handling starting scan
,08-29 10:24:09.865  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-29 10:24:09.865  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 10:24:09.865  7546  7575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7e395a
08-29 10:24:09.865  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:24:09.865  7546  7570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,08-29 10:24:09.865  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:09.865  7546  7575 D BtGatt.ScanManager: allow scan with filters
08-29 10:24:09.865  7546  7575 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 10:24:09.865  7546  7575 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 10:24:09.875  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-29 10:24:09.875  7546  7570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 10:24:09.875  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:09.875  7546  7575 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:24:09.875  7546  7575 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 10:24:09.875  7546  7570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 10:24:09.875  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:09.885  7546  7570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 10:24:09.885  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:09.885  6778  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-29 10:24:09.885  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:09.885  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 10:24:09.885  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:09.885  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:24:09.885  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 10:24:09.885  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:24:09.885  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:24:09.885  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:24:09.885  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:24:09.885  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:24:09.895  7546  7571 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:24:09.905  7546  7575 D BtGatt.ScanManager: filter size is 1,
08-29 10:24:09.905  7546  7575 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 10:24:09.905  7546  7618 D BtGatt.GattService: unregisterClient() - clientIf=6,
,08-29 10:24:09.915  7546  7570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 10:24:09.915  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:09.915  7546  7575 D BtGatt.ScanManager: stopping BLe Batch
08-29 10:24:09.915  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:09.915  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:24:09.915  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:24:09.915  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:24:09.915  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 10:24:09.915  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:24:09.915  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:24:09.915  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:24:09.915  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,08-29 10:24:09.915  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:09.915  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 10:24:09.915  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:09.915  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:09.915  7546  7570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-29 10:24:09.915  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:09.925  7546  7575 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 10:24:09.925  7546  7570 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 10:24:09.925  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:09.925  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 10:24:09.925  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:09.925  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:09.925  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 10:24:09.925  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:09.925  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:09.925  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:09.925  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19655f09 removed from the list
,08-29 10:24:09.925  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:09.925  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d14650e removed from the list
08-29 10:24:09.925  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 10:24:09.925  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:09.925  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 10:24:09.925  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:09.925  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:09.925  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:09.925  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:09.935  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d14650e not in the list
08-29 10:24:09.935  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:09.935  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:09.935  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 10:24:09.935  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:09.935  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:09.935  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@287be2c5 removed from the list
,08-29 10:24:09.935  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:09.935  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:09.935  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:09.935  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:09.935  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34dff53c removed from the list
,08-29 10:24:09.935  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-29 10:24:09.935  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32bce641 added. We now have 2 listener(s)
,08-29 10:24:09.945  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 10:24:09.945  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:24:09.945  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:09.945  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:09.945  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fdc07e6 added. We now have 9 listener(s)
08-29 10:24:09.945  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:09.945  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:24:09.945  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:09.955  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:09.955  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:09.955  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:09.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:09.955  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d67afd4 added. We now have 3 listener(s)
,08-29 10:24:09.965  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:09.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 10:24:09.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:09.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:09.965  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 10:24:09.965  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb0a57d added. We now have 10 listener(s)
08-29 10:24:09.965  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:09.965  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:09.965  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:09.965  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:09.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:09.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 10:24:09.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 10:24:09.965  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:09.965  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:24:09.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:24:09.965  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:24:09.975  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 10:24:09.975  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 10:24:09.975  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:24:09.975  7546  7554 D BtGatt.GattService: registerClient() - UUID=068aec9c-4fb7-4c10-82c9-217059c4dda9
,08-29 10:24:10.015  7546  7570 D BtGatt.GattService: onClientRegistered() - UUID=068aec9c-4fb7-4c10-82c9-217059c4dda9, clientIf=6
,08-29 10:24:10.015  6778  6786 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 10:24:10.025  7546  7555 D BtGatt.GattService: start scan with filters
08-29 10:24:10.025  7546  7575 D BtGatt.ScanManager: handling starting scan
08-29 10:24:10.025  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 10:24:10.025  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 10:24:10.025  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 10:24:10.025  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 10:24:10.035  7546  7570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 10:24:10.035  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:10.035  7546  7575 D BtGatt.ScanManager: allow scan with filters
08-29 10:24:10.035  7546  7575 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 10:24:10.035  7546  7575 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 10:24:10.035  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:24:10.035  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:24:10.035  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:24:10.035  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 10:24:10.035  7546  7570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 10:24:10.035  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:10.035  7546  7575 D BtGatt.ScanManager: Starting BLE batch scan
08-29 10:24:10.035  7546  7575 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 10:24:10.035  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:10.035  6778  6834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 10:24:10.035  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:10.035  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:10.035  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:10.035  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:10.035  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.035  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:24:10.035  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:10.035  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32bce641 removed from the list
08-29 10:24:10.045  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:10.045  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fdc07e6 removed from the list
08-29 10:24:10.045  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:10.045  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:10.045  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.045  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
08-29 10:24:10.045  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.045  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:10.045  7546  7570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 10:24:10.045  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:10.045  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 10:24:10.045  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:10.045  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:10.045  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fdc07e6 not in the list
,08-29 10:24:10.045  7546  7570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 10:24:10.045  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:10.045  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 10:24:10.055  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 10:24:10.055  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 10:24:10.055  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 10:24:10.055  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:24:10.055  7546  7618 D BtGatt.GattService: stopScan() - queue size =1,
,08-29 10:24:10.055  7546  7554 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 10:24:10.055  7546  7575 D BtGatt.ScanManager: filter size is 1
,08-29 10:24:10.055  7546  7575 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 10:24:10.055  7546  7570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 10:24:10.055  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:10.065  7546  7575 D BtGatt.ScanManager: stopping BLe Batch
,08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:24:10.065  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:24:10.065  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 10:24:10.065  7546  7570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:24:10.065  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:24:10.065  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:10.065  7546  7575 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 10:24:10.065  7546  7570 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 10:24:10.065  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 10:24:10.065  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:10.065  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:10.065  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 10:24:10.065  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb0a57d removed from the list
08-29 10:24:10.065  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:10.065  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.065  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:10.075  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 10:24:10.075  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d67afd4 removed from the list
08-29 10:24:10.075  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:10.075  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:10.075  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:10.075  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 10:24:10.075  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39271c79 added. We now have 2 listener(s)
,08-29 10:24:10.075  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 10:24:10.075  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:24:10.075  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:10.075  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:10.075  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eea2dbe added. We now have 9 listener(s)
,08-29 10:24:10.075  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:10.075  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 10:24:10.085  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-29 10:24:10.085  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 10:24:10.085  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 10:24:10.085  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 10:24:10.095  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:10.095  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fa9256c added. We now have 3 listener(s)
,08-29 10:24:10.095  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:10.095  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 10:24:10.095  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 10:24:10.095  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 10:24:10.095  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 10:24:10.095  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:10.095  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31f40735 added. We now have 10 listener(s)
,08-29 10:24:10.095  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 10:24:10.095  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 10:24:10.095  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 10:24:10.095  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 10:24:10.095  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-29 10:24:10.105  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 10:24:10.105  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 10:24:10.105  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 10:24:10.115  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 10:24:10.115  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 10:24:10.115  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 10:24:10.115  6778  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 10:24:10.115  7546  7555 D BtGatt.GattService: registerClient() - UUID=8a98ab4f-629a-428f-93f0-69ec63b3b629
,08-29 10:24:10.155  1018  1127 E WifiNative-wlan0: do suspend true
,08-29 10:24:10.155  7546  7570 D BtGatt.GattService: onClientRegistered() - UUID=8a98ab4f-629a-428f-93f0-69ec63b3b629, clientIf=6
,08-29 10:24:10.155  6778  6824 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 10:24:10.165  7546  7571 D BtGatt.GattService: start scan with filters
,08-29 10:24:10.165  7546  7575 D BtGatt.ScanManager: handling starting scan
,08-29 10:24:10.165  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 10:24:10.165  7546  7570 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 10:24:10.165  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:10.165  7546  7575 D BtGatt.ScanManager: allow scan with filters
,08-29 10:24:10.165  7546  7575 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 10:24:10.165  7546  7575 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 10:24:10.165  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 10:24:10.165  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 10:24:10.165  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 10:24:10.175  7546  7570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 10:24:10.175  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:10.175  7546  7575 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 10:24:10.175  7546  7575 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 10:24:10.175  7546  7570 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 10:24:10.175  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:10.185  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:24:10.185  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 10:24:10.185  7546  7570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 10:24:10.185  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-29 10:24:10.185  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 10:24:10.185  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 10:24:10.195  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 10:24:10.195  1018  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 10:24:10.195  1018  1127 E WifiStateMachine: VerifyingLinkState enter
,08-29 10:24:10.195  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 10:24:10.195  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 10:24:10.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:10.195  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-29 10:24:10.195  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 10:24:10.205  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-29 10:24:10.205  1018  1129 D ConnectivityService: Adding iface wlan0 to network 504
,08-29 10:24:10.205  1018  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-29 10:24:10.205  1018  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 10:24:10.205  1018  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 10:24:10.205  1018  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 10:24:10.205  1018  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 10:24:10.215  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:24:10.215  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:24:10.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 10:24:10.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:10.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.215  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:10.225  1018  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-29 10:24:10.235  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:10.235  1018  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:24:10.235  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:10.235  1018  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 10:24:10.235  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:10.235  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:10.235  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.235  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 10:24:10.235  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:10.235  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39271c79 removed from the list
08-29 10:24:10.235  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:10.235  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eea2dbe removed from the list
08-29 10:24:10.235  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:10.235  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 10:24:10.235  1018  1500 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:10.235  1018  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:10.235  1018  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 10:24:10.235  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 10:24:10.235  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
08-29 10:24:10.235  1602  1602 I Hs20UtilService: Starting #22
,08-29 10:24:10.235  1018  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-29 10:24:10.235  1602  1639 I Hs20UtilService: Message received 5007
08-29 10:24:10.245  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 10:24:10.245  1018  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-29 10:24:10.245  1018  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-29 10:24:10.245  1018  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 10:24:10.245  1018  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-29 10:24:10.245  1018  1129 D ConnectivityService: LTETest block dns file not exists
08-29 10:24:10.245  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 10:24:10.255  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.255  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-29 10:24:10.255  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-29 10:24:10.255  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,08-29 10:24:10.255  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 10:24:10.255  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:24:10.255  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.255  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:10.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:10.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:10.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:10.255  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eea2dbe not in the list
08-29 10:24:10.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 10:24:10.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 10:24:10.255  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 10:24:10.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 10:24:10.255  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 10:24:10.265  7546  7618 D BtGatt.GattService: stopScan() - queue size =1
,08-29 10:24:10.265  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 10:24:10.265  7546  7575 D BtGatt.ScanManager: filter size is 1
08-29 10:24:10.265  7546  7554 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 10:24:10.265  7546  7575 D BtGatt.ScanManager: delete FilterIndex - 5
08-29 10:24:10.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 10:24:10.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 10:24:10.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 10:24:10.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 10:24:10.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 10:24:10.265  7546  7570 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-29 10:24:10.265  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:10.265  1018  1129 V NetworkStats: updateIfacesLocked()
08-29 10:24:10.265  7546  7575 D BtGatt.ScanManager: stopping BLe Batch
08-29 10:24:10.265  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:24:10.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 10:24:10.265  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.265  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:24:10.265  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:24:10.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 10:24:10.265  6778  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 10:24:10.265  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 10:24:10.275  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:10.275  3066  3066 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 10:24:10.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:10.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:10.275  1018  1129 V NetworkStats: performPollLocked() took 9ms
08-29 10:24:10.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:10.275  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31f40735 removed from the list
08-29 10:24:10.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:10.275  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.275  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:10.275  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:10.275  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fa9256c removed from the list
08-29 10:24:10.275  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:10.275  6778  6778 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 10:24:10.275  6778  6778 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 10:24:10.275  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.275  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:10.275  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286ae1b1 added. We now have 2 listener(s)
,08-29 10:24:10.275  7546  7570 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 10:24:10.275  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.275  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:10.275  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:10.275  7546  7575 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 10:24:10.275  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 10:24:10.275  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 10:24:10.275  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:10.275  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:10.275  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c3696 added. We now have 9 listener(s)
08-29 10:24:10.275  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:10.285  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 10:24:10.285  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-29 10:24:10.285  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:24:10.285  1018  1129 E ConnectivityService: updateNetworkInfo()
08-29 10:24:10.285  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 10:24:10.285  1018  1129 V NetworkStats: updateIfacesLocked()
08-29 10:24:10.285  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.285  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-29 10:24:10.285  7546  7570 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 10:24:10.285  7546  7570 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 10:24:10.285  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:24:10.285  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:24:10.285  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.285  1018  1129 V NetworkStats: performPollLocked() took 3ms
,08-29 10:24:10.285  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 10:24:10.295  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.295  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.295  1018  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-29 10:24:10.295  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 10:24:10.295  1018  7663 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:10.295  1018  7663 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
,08-29 10:24:10.295  1018  7663 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 10:24:10.295  1018  7663 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-29 10:24:10.295  1018  1208 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:24:10.295  1018  1208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 10:24:10.295  1018  7663 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
08-29 10:24:10.295  1018  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:10.295  1018  1208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:10.295  1018  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 10:24:10.295   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-29 10:24:10.295   278   984 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-29 10:24:10.295  1602  1602 I Hs20UtilService: Starting #23
,08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 10:24:10.295  6778  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 10:24:10.295  1602  1639 I Hs20UtilService: Message received 5007
08-29 10:24:10.295  1018  1129 D ConnectivityService:    accepting network in place of null,
,08-29 10:24:10.295  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 10:24:10.295  1018  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-29 10:24:10.295  1478  1478 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 10:24:10.295  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 10:24:10.295  1478  1478 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 10:24:10.295  1018  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-29 10:24:10.295  1018  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 10:24:10.295  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 10:24:10.295  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 10:24:10.305  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-29 10:24:10.295  3066  3066 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 10:24:10.305  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 10:24:10.305  1018  1131 D Tethering: MasterInitialState.processMessage what=3
08-29 10:24:10.305  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-29 10:24:10.305  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 10:24:10.305  1018  1124 V NetworkStats: updateIfacesLocked()
08-29 10:24:10.305  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 10:24:10.305  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:10.305  1177  1766 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:24:10.305  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 10:24:10.305  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 10:24:10.305  4663  6842 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:24:10.305  6778  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 10:24:10.305  6778  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 10:24:10.305  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 10:24:10.305  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc0b604 added. We now have 3 listener(s)
08-29 10:24:10.305  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 10:24:10.305  3066  3066 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-29 10:24:10.305  3066  3066 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 10:24:10.305  1018  1124 V NetworkStats: performPollLocked() took 4ms
08-29 10:24:10.305  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:10.305  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-29 10:24:10.305  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 10:24:10.305  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 10:24:10.305  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-29 10:24:10.305  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 10:24:10.305  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 10:24:10.315  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.315  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 10:24:10.315  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.315  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.315  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.315  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:10.315  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:10.315  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 10:24:10.315  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-29 10:24:10.315  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 10:24:10.315  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 10:24:10.315  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@239ae7ed added. We now have 10 listener(s)
08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 10:24:10.315  6778  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 10:24:10.315  6778  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 10:24:10.315  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 10:24:10.315  6778  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 10:24:10.315  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:10.315  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.315  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:10.315  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 10:24:10.315  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:10.315  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286ae1b1 removed from the list
08-29 10:24:10.315  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:10.315  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c3696 removed from the list
,08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:24:10.315  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.325  6778  6778 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 10:24:10.325  1018  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 10:24:10.325  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 10:24:10.325  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 10:24:10.325  6778  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-29 10:24:10.325  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:10.325  1018  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:10.325  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 10:24:10.325  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:10.325  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.325  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 10:24:10.325  1602  1602 I Hs20UtilService: Starting #24
08-29 10:24:10.325  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:10.325  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:10.325  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:10.325  6778  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62c3696 not in the list
08-29 10:24:10.325  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.325  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:10.325  1602  1639 I Hs20UtilService: Message received 5007
,08-29 10:24:10.325  3066  3066 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 10:24:10.325  3066  3066 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 10:24:10.335  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 10:24:10.335  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 10:24:10.335  6778  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 10:24:10.335  6778  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@239ae7ed removed from the list
08-29 10:24:10.335  6778  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 10:24:10.335  6778  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 10:24:10.335  6778  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 10:24:10.335  6778  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 10:24:10.335  6778  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc0b604 removed from the list
,08-29 10:24:10.335  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 10:24:10.335  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 10:24:10.335  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 10:24:10.335  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 10:24:10.335  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 10:24:10.335  6778  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 10:24:10.335  1018  1319 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-29 10:24:10.335  1018  1500 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-29 10:24:10.335  1018  1500 D SecContentProvider2: mCursor = null
,08-29 10:24:10.345  6778  7701 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1374, name: My test thread name)
08-29 10:24:10.345  1018  1491 D SecContentProvider2: uri = 15 selection = getToastGravity
08-29 10:24:10.345  1018  1491 D SecContentProvider2: mCursor = null
08-29 10:24:10.345  6778  7701 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1374, thread name: My test thread name)
08-29 10:24:10.345  6778  7701 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1374, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 10:24:10.345  1018  1499 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-29 10:24:10.345  1018  1499 D SecContentProvider2: mCursor = null
08-29 10:24:10.345  6778  7702 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1376, name: My test thread name)
08-29 10:24:10.345  6778  7702 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1376, thread name: My test thread name)
08-29 10:24:10.345  6778  7702 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1376, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 10:24:10.345  1018  1030 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-29 10:24:10.345  1018  1030 D SecContentProvider2: mCursor = null
,08-29 10:24:10.345  1018  1454 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-29 10:24:10.345  1018  1454 D SecContentProvider2: mCursor = null
08-29 10:24:10.345  6778  6834 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
08-29 10:24:10.345  1018  1516 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-29 10:24:10.345  1018  1516 D SecContentProvider2: mCursor = null
08-29 10:24:10.345  6778  6834 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 10:24:10.345  6778  6834 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 10:24:10.345  6778  6834 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 10:24:10.345  6778  6834 D com.test.thalitest.ThaliTestRunner: Total duration: 23425 ms
08-29 10:24:10.355  6778  6834 I jxcore-log: *Native tests were executed*
08-29 10:24:10.355  6778  6834 I jxcore-log: 
08-29 10:24:10.355  6778  6834 I jxcore-log: Total number of executed tests:  80
08-29 10:24:10.355  6778  6834 I jxcore-log: 
08-29 10:24:10.355  6778  6834 I jxcore-log: Number of passed tests:  80
08-29 10:24:10.355  6778  6834 I jxcore-log: 
08-29 10:24:10.355  6778  6834 I jxcore-log: Number of failed tests:  0
08-29 10:24:10.355  6778  6834 I jxcore-log: 
08-29 10:24:10.355  6778  6834 I jxcore-log: Number of ignored tests:  0
08-29 10:24:10.355  6778  6834 I jxcore-log: 
,08-29 10:24:10.355  6778  6834 I jxcore-log: Total duration:  23425
08-29 10:24:10.355  6778  6834 I jxcore-log: 
08-29 10:24:10.355  6778  6834 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 10:24:10.355  6778  6834 I jxcore-log: 
,08-29 10:24:10.355  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.355  6778  6834 I jxcore-log: 
08-29 10:24:10.355  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.355  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6778 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.365  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.365  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
,08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
,08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
,08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
,08-29 10:24:10.375  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.375  6778  6834 I jxcore-log: 
08-29 10:24:10.385  1018  7663 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 10:24:10.385  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 10:24:10.385  6778  6834 I jxcore-log: 
,08-29 10:24:10.385  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 10:24:10.385  6778  6834 I jxcore-log: 
,08-29 10:24:10.385  1018  1499 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018,
,08-29 10:24:10.395  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 10:24:10.415  6778  6778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 10:24:10.425  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:10.425  6778  6834 I jxcore-log: 
,08-29 10:24:10.445  1018  7663 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 08:24:10 GMT], X-Android-Received-Millis=[1472459050456], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472459050423]},
,08-29 10:24:10.445  1018  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-29 10:24:10.445  1018  7663 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-29 10:24:10.445  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 10:24:10.445  1018  7663 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 10:24:10.445  1018  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.,
08-29 10:24:10.445  1177  1766 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 10:24:10.445  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
08-29 10:24:10.445  4663  6842 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
08-29 10:24:10.445  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 10:24:10.455  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 10:24:10.455  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 10:24:10.455  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 10:24:10.465  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.465  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.465  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 10:24:10.465  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 10:24:10.575  6778  6778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-29 10:24:10.575  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:10.575  6778  6834 I jxcore-log: 
,08-29 10:24:10.635  7704  7704 D AndroidRuntime: ,
08-29 10:24:10.635  7704  7704 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 10:24:10.645  7704  7704 D AndroidRuntime: CheckJNI is OFF,
08-29 10:24:10.645  7704  7704 D AndroidRuntime: readGMSProperty: start
08-29 10:24:10.645  7704  7704 D AndroidRuntime: readGMSProperty: already setted!!
,08-29 10:24:10.645  7704  7704 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 10:24:10.645  7704  7704 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 10:24:10.645  7704  7704 D AndroidRuntime: readGMSProperty: end
08-29 10:24:10.645  7704  7704 D AndroidRuntime: addProductProperty: start
,08-29 10:24:10.775  6778  6778 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-29 10:24:10.775  6778  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 10:24:10.775  6778  6834 I jxcore-log: 
,08-29 10:24:10.785  7704  7704 E AffinityControl: AffinityControl: registerfunction enter
,08-29 10:24:10.795  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-29 10:24:10.815  7704  7704 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-29 10:24:10.835  1018  1454 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-29 10:24:10.835  1018  1454 D PackageManager: START PACKAGE DELETE: observer{641207627}
08-29 10:24:10.835  1018  1454 D PackageManager: pkg{<packageName>}
08-29 10:24:10.835  1018  1454 D PackageManager: user{0}
08-29 10:24:10.835  1018  1454 D PackageManager: caller{2000}
08-29 10:24:10.835  1018  1454 D PackageManager: flags{2}
08-29 10:24:10.835  1018  1454 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 10:24:10.835  1018  1454 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-29 10:24:10.835  1018  1454 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 10:24:10.835  1018  1454 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-29 10:24:10.845  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:10.845  1018  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-29 10:24:10.845  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 10:24:10.845  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-29 10:24:10.845  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-29 10:24:10.845  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-29 10:24:10.845  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 10:24:10.855  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:10.855  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:10.855  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:10.855  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:10.855  1018  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 10:24:10.865  6778  6778 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 10:24:10.865  7714  7714 E Zygote  : MountEmulatedStorage()
08-29 10:24:10.865  7714  7714 E Zygote  : v2
08-29 10:24:10.865  7714  7714 I libpersona: KNOX_SDCARD checking this for 1000
08-29 10:24:10.865  7714  7714 I libpersona: KNOX_SDCARD not a persona
,08-29 10:24:10.865  7714  7714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 10:24:10.875  7714  7714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:24:10.875  7714  7714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 10:24:10.875  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7714 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 10:24:10.895  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-29 10:24:10.895  1018  1043 I ActivityManager: Killing 6778:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-29 10:24:10.895  7714  7714 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:24:10.895  7714  7714 D ActivityThread: Added TimaKeyStore provider
,08-29 10:24:10.945   293   293 E SMD     : DCD OFF,
,08-29 10:24:10.945  1018  1057 W PackageSettings: Skipping PackageSetting{27ee9359 com.example.hello/10168} due to missing metadata
,08-29 10:24:10.975  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{2547e50a u0 com.test.thalitest/.MainActivity t2}
,08-29 10:24:10.985  1018  1043 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 10:24:10.995  1018  1098 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
08-29 10:24:11.005  1018  1098 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,08-29 10:24:11.015  7714  7714 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-29 10:24:11.015  7714  7714 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 10:24:11.015  7714  7714 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 10:24:11.015  1018  1043 D InputDispatcher: Focus left window: 6778
,08-29 10:24:11.015  1018  1043 W InputDispatcher: Attempted to unregister already unregistered input channel
08-29 10:24:11.015   258   456 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-29 10:24:11.015   258   458 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-29 10:24:11.035  1018  1499 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-29 10:24:11.035  1018  1499 D SecContentProvider2: mCursor = null
,08-29 10:24:11.035  1018  1043 D InputDispatcher: Focused application released
,08-29 10:24:11.035  1018  1043 D FocusedStackFrame: Set to : 0
,08-29 10:24:11.045  1018  1319 W WindowManager: Failed looking up window
08-29 10:24:11.045  1018  1319 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@26f68e55 does not exist
08-29 10:24:11.045  1018  1319 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
08-29 10:24:11.045  1018  1319 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
08-29 10:24:11.045  1018  1319 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
08-29 10:24:11.045  1018  1319 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,08-29 10:24:11.045  1018  1319 I WindowState: WIN DEATH: null
,08-29 10:24:11.045  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 10:24:11.045  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 10:24:11.045  1018  1043 W ActivityManager: mDVFSHelper.acquire()
,08-29 10:24:11.055  1018  1043 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-29 10:24:11.055  1018  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-29 10:24:11.065  7714  7714 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-29 10:24:11.065  7714  7714 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 10:24:11.065  7714  7714 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 10:24:11.065  7714  7714 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:11.085  1501  1501 D Launcher: onRestart, Launcher: 404078696
,08-29 10:24:11.085  1018  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-29 10:24:11.125  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-29 10:24:11.125  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-29 10:24:11.125  2638  2638 I art     : Explicit concurrent mark sweep GC freed 19547(1115KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 904us total 37.255ms
,08-29 10:24:11.135  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 10:24:11.135  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-29 10:24:11.135  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-29 10:24:11.135  1884  1884 E SamsungIME: mOCRHelper is null
,08-29 10:24:11.135  1946  2155 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 10:24:11.145  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 10:24:11.145  4663  4663 I art     : Explicit concurrent mark sweep GC freed 24406(1479KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 12MB/21MB, paused 1.400ms total 80.379ms
,08-29 10:24:11.155  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-29 10:24:11.155  1018  1516 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-29 10:24:11.155  1018  1516 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 10:24:11.155  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-29 10:24:11.155  1018  1516 I ActivityManager: Killing 7114:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 10:24:11.165  1501  1501 D Launcher: onStart, Launcher: 404078696
,08-29 10:24:11.165  1501  1501 D Launcher.HomeView: onStart
,08-29 10:24:11.165  1501  1501 D Launcher: onResume, Launcher: 404078696
,08-29 10:24:11.165  1018  1321 D SettingsProvider: name = kids_home_mode
08-29 10:24:11.165  1018  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 10:24:11.165  1018  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 10:24:11.165  1018  1321 D SettingsProvider: selectionArgs: false
08-29 10:24:11.165  1018  1321 D SettingsProvider: selectionArgs: 10006
08-29 10:24:11.165  1018  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 10:24:11.165  1018  1321 D SettingsProvider: ret = -1
,08-29 10:24:11.165  1501  1501 D Launcher.HomeView: onResume
,08-29 10:24:11.175  1501  1501 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 10:24:11.175  1460  1460 D PersonaManager: isKioskContainerExistOnDevice
,08-29 10:24:11.185  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 10:24:11.185  1789  1789 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 10:24:11.185  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.185  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.185  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.185  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.195  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0,
08-29 10:24:11.195  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms,
08-29 10:24:11.195  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-29 10:24:11.205  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-29 10:24:11.205  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-29 10:24:11.215  7734  7734 E Zygote  : MountEmulatedStorage()
,08-29 10:24:11.215  7734  7734 E Zygote  : v2
08-29 10:24:11.215  7734  7734 I libpersona: KNOX_SDCARD checking this for 10121
08-29 10:24:11.215  7734  7734 I libpersona: KNOX_SDCARD not a persona
08-29 10:24:11.215  7734  7734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:24:11.215  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-29 10:24:11.215  7734  7734 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:24:11.215  7734  7734 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 10:24:11.215  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-29 10:24:11.225  1018  1043 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7734 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 10:24:11.225  1018  1516 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-29 10:24:11.225  1018  1516 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-29 10:24:11.225  1460  1460 D RegisteredServicesCache: empty dynamic service
,08-29 10:24:11.225  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:11.225  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:11.225  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-29 10:24:11.245  1018  1454 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast,
08-29 10:24:11.245   324   324 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 21.013ms
,08-29 10:24:11.245  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.245  2470  3278 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
08-29 10:24:11.245  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.245  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.245  1018  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.245  7734  7734 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:24:11.245  7734  7734 D ActivityThread: Added TimaKeyStore provider
,08-29 10:24:11.255   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.512ms
,08-29 10:24:11.275   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 16.073ms
,08-29 10:24:11.285  7749  7749 E Zygote  : MountEmulatedStorage(),
08-29 10:24:11.285  7749  7749 E Zygote  : v2,
,08-29 10:24:11.285  7749  7749 I libpersona: KNOX_SDCARD checking this for 10031
08-29 10:24:11.285  7749  7749 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:24:11.285  7749  7749 I libpersona: KNOX_SDCARD not a persona
08-29 10:24:11.295  7749  7749 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:24:11.295  7749  7749 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:24:11.305  1018  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-29 10:24:11.305  1018  1454 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7749 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 10:24:11.315  1501  1501 D MenuAppsGridFragment: onResume
,08-29 10:24:11.325  1501  1501 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-29 10:24:11.325  1501  1501 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-29 10:24:11.335  1018  1208 D ActivityManager: handle home activity for 0
,08-29 10:24:11.335  1018  1208 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-29 10:24:11.335  1018  1208 D KnoxTimeoutHandler: post home show event for user 0
08-29 10:24:11.335  1018  1208 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 10:24:11.335  1018  1208 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 10:24:11.335  1018  1208 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 10:24:11.335  1501  1501 D Launcher.HomeView: onPause
08-29 10:24:11.335  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 10:24:11.335  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 10:24:11.335  1501  1501 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 10:24:11.335  7749  7749 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 10:24:11.335  7749  7749 D ActivityThread: Added TimaKeyStore provider
,08-29 10:24:11.335  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-29 10:24:11.335  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-29 10:24:11.335  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 10:24:11.335  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 10:24:11.345  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-29 10:24:11.345  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 10:24:11.345  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 10:24:11.345  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-29 10:24:11.345  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 10:24:11.345  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 10:24:11.355  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.355  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 10:24:11.355  1018  1018 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-29 10:24:11.355  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:11.355  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-29 10:24:11.355  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 10:24:11.355  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
08-29 10:24:11.355  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 10:24:11.365  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.365  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:11.365  1018  1124 V NetworkStats: performPollLocked() took 6ms
,08-29 10:24:11.365  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 10:24:11.365  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 10:24:11.365  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 10:24:11.365  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 10:24:11.365  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 10:24:11.365  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 10:24:11.365  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 10:24:11.365  1018  1031 D BatteryService: stay LED for fully charged
,08-29 10:24:11.365  1789  1789 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 10:24:11.375  1789  1789 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-29 10:24:11.375  1789  1789 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 10:24:11.375  1789  1789 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 10:24:11.375  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 10:24:11.375  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 10:24:11.385  1789  1789 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-29 10:24:11.385  1789  1789 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 10:24:11.395  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.395  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.395  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 10:24:11.395  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 10:24:11.415  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.415  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 10:24:11.415  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-29 10:24:11.415  7734  7734 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 10:24:11.415  7734  7734 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 10:24:11.415  7734  7734 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 10:24:11.415  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-29 10:24:11.415  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-29 10:24:11.425  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 10:24:11.425  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 10:24:11.425  1018  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-29 10:24:11.425  1018  3361 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-29 10:24:11.435  1460  1460 D RegisteredComponentCache: Collect Tech packages for Knox
,08-29 10:24:11.435  7734  7734 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:11.435  1460  1460 D PersonaManager: isKioskContainerExistOnDevice
08-29 10:24:11.435   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-29 10:24:11.435  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 10:24:11.435  7734  7734 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 10:24:11.445  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.445  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 10:24:11.445  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 10:24:11.445  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 10:24:11.455  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.455  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 10:24:11.455  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 10:24:11.465  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 10:24:11.465  1018  1208 D InputDispatcher: Focus entered window: 1501
,08-29 10:24:11.465  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 10:24:11.465  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 10:24:11.465  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 10:24:11.465  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 10:24:11.465  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 10:24:11.465  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 10:24:11.465  1501  1501 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 10:24:11.485  1501  1501 V ActivityThread: updateVisibility : ActivityRecord{3d24f661 token=android.os.BinderProxy@3e80d443 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-29 10:24:11.485  1501  1501 D Launcher.HomeView: onStop
,08-29 10:24:11.485  1018  1454 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 10:24:11.485  7546  7546 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 10:24:11.485  7546  7576 D HeadsetStateMachine: Disconnected process message: 10
,08-29 10:24:11.495  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 10:24:11.495  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.495  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.495  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.495  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.495  1018  1454 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6778 uid 10171
,08-29 10:24:11.505  1018  7765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-29 10:24:11.505  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:24:11.505  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:24:11.505  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 10:24:11.515  7766  7766 E Zygote  : MountEmulatedStorage()
08-29 10:24:11.515  7766  7766 E Zygote  : v2
08-29 10:24:11.515  7766  7766 I libpersona: KNOX_SDCARD checking this for 10001
08-29 10:24:11.515  7766  7766 I libpersona: KNOX_SDCARD not a persona
,08-29 10:24:11.515  7766  7766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:24:11.515  7766  7766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 10:24:11.515  1884  1884 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-29 10:24:11.525  7766  7766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:24:11.525  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7766 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 10:24:11.525  1018  1018 I MotionRecognitionService: Plugged
08-29 10:24:11.525  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-29 10:24:11.525  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-29 10:24:11.525  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-29 10:24:11.525  1018  1321 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-29 10:24:11.525  1018  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-29 10:24:11.525  1018  1321 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:11.525  1018  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:11.525  1018  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-29 10:24:11.535  1177  1177 I StatusBar: Icon Only
08-29 10:24:11.535  1177  1177 D PanelView: There is/are notification(s) 
,08-29 10:24:11.555  7734  7734 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 10:24:11.555  1018  1043 W ActivityManager: mDVFSHelper.release()
,08-29 10:24:11.555  7766  7766 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:24:11.555  7766  7766 D ActivityThread: Added TimaKeyStore provider
,08-29 10:24:11.555  1018  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 10:24:11.555  1018  1030 D SecContentProvider2: mCursor = null
,08-29 10:24:11.575  1018  1319 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 10:24:11.575  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 10:24:11.585  1018  1057 I art     : Explicit concurrent mark sweep GC freed 90843(5MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 6.698ms total 272.538ms
,08-29 10:24:11.585  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:11.585  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:11.585  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 10:24:11.585  1018  1499 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:24:11.595  1018  1208 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 10:24:11.595  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11318418 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:146633
,08-29 10:24:11.605  1018  1057 D PackageManager: delete codoeFile: 
,08-29 10:24:11.615  1018  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-29 10:24:11.615  1018  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-29 10:24:11.615  1018  1057 D PackageManager: result of delete: 1{641207627}
,08-29 10:24:11.645  7240  7240 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-29 10:24:11.645  7045  7785 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 10:24:11.645  7045  7785 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 10:24:11.645  7045  7785 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 10:24:11.645  7045  7785 I System.out: (HTTPLog)-Thread-1286-29188159: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 10:24:11.645  7045  7785 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 10:24:11.645   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 10:24:11.645   278   984 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-29 10:24:11.645  7704  7704 D AndroidRuntime: Shutting down VM
,08-29 10:24:11.655  2762  7786 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-29 10:24:11.655  2762  7786 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-29 10:24:11.665  7162  7162 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
08-29 10:24:11.665  2762  7786 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 10:24:11.665  1018  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 10:24:11.665  1018  1057 D PackageManager: userId{-1}
08-29 10:24:11.665  1018  1057 D PackageManager: andCode{true}
,08-29 10:24:11.665  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 10:24:11.675  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.675  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.675  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.675  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.675  7185  7185 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 10:24:11.675  7185  7185 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,08-29 10:24:11.675  7185  7185 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 10:24:11.685  7793  7793 E Zygote  : MountEmulatedStorage()
08-29 10:24:11.685  7793  7793 E Zygote  : v2
08-29 10:24:11.685  7793  7793 I libpersona: KNOX_SDCARD checking this for 10003
08-29 10:24:11.685  7793  7793 I libpersona: KNOX_SDCARD not a persona
,08-29 10:24:11.685  7793  7793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 10:24:11.685  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7793 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 10:24:11.685  7793  7793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 10:24:11.695  7793  7793 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 10:24:11.695  7185  7185 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 10:24:11.695  7045  7785 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 10:24:11.695  7185  7185 I SA      : [OR] == isSIMCardReady false ==
,08-29 10:24:11.695  7185  7185 I SA      : [SCU] == networkStateCheck == true
08-29 10:24:11.695  7185  7185 I SA      : [DM] getCountryCodeFromCSC : PL
08-29 10:24:11.695  7185  7185 I SA      : isChinaCountryCode : false
08-29 10:24:11.695  7185  7185 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-29 10:24:11.695  7185  7185 I SA      : [OR] == networkStateCheck true ==
,08-29 10:24:11.705  7204  7204 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
08-29 10:24:11.705  7204  7204 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 10:24:11.705  7204  7204 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-29 10:24:11.705  7204  7204 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-29 10:24:11.715  7185  7185 I SA      : [OR] GetMyCountryZoneTask
,08-29 10:24:11.715  7185  7185 I SA      : [OR] onReceive END
,08-29 10:24:11.715  2762  7786 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-29 10:24:11.725  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 10:24:11.725  7793  7793 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:24:11.725  1018  1454 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-29 10:24:11.725  1018  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-29 10:24:11.725  7793  7793 D ActivityThread: Added TimaKeyStore provider
,08-29 10:24:11.725  2762  7786 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-29 10:24:11.725  1018  1454 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:11.725  1018  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 10:24:11.725  1018  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
08-29 10:24:11.725  2762  7786 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-29 10:24:11.735  2762  7786 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-29 10:24:11.735  7185  7804 I SA      : [SRS] prepareGetMyCountryZone
,08-29 10:24:11.745  2762  7786 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-29 10:24:11.745  2762  7786 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-29 10:24:11.745  2762  7786 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-29 10:24:11.745  2762  7786 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-29 10:24:11.755  7185  7804 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 10:24:11.755  7185  7804 I SA      : [SSP] query invoked
,08-29 10:24:11.755  1018  1456 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-29 10:24:11.755  1018  1456 D SecContentProvider2: mCursor = null
,08-29 10:24:11.765  2762  7786 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-29 10:24:11.765  7185  7804 I SA      : [TPMU] GetMccFromDB : null
,08-29 10:24:11.775  7045  7785 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 10:24:11.775  1018  1499 I ActivityManager: Killing 7224:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-29 10:24:11.785  1018  1030 I ActivityManager: Killing 7276:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 10:24:11.785  2762  7786 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-29 10:24:11.815  7185  7804 I SA      : [SCU] getMccFromPreferece mcc = 260
08-29 10:24:11.815  7185  7804 I SA      : [LBE] isSupportCheckDomainRegion : false
08-29 10:24:11.815  7185  7804 I SA      : [TPM] isNoProxy(default) : true
,08-29 10:24:11.825  7185  7804 E File    : fail readDirectory() errno=2
,08-29 10:24:11.855  1018  1319 D PersonaManager: isKioskContainerExistOnDevice
,08-29 10:24:11.855  7704  7704 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 10:24:11.875  1018  1208 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-29 10:24:11.875  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.875  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.875  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:11.875  1018  1208 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:11.885  7814  7814 E Zygote  : MountEmulatedStorage()
08-29 10:24:11.885  7814  7814 E Zygote  : v2
08-29 10:24:11.885  7814  7814 I libpersona: KNOX_SDCARD checking this for 10008
08-29 10:24:11.885  7814  7814 I libpersona: KNOX_SDCARD not a persona
,08-29 10:24:11.885  7814  7814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 10:24:11.895  7814  7814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 10:24:11.895  7814  7814 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 10:24:11.895  1018  1208 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7814 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 10:24:11.915  7814  7814 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 10:24:11.925  7814  7814 D ActivityThread: Added TimaKeyStore provider,
,08-29 10:24:11.965  1501  1501 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3e80d443 time:147002
,08-29 10:24:11.995  1018  1030 I ActivityManager: Killing 6864:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-29 10:24:12.005  1018  1491 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-29 10:24:12.005  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-29 10:24:12.005  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:12.005  1018  1491 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 10:24:12.005  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 10:24:12.015  1018  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 10:24:12.015  1018  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 10:24:12.015  1018  1456 W ActivityManager: userId = 0, bbcId = -10000
08-29 10:24:12.015  1018  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:12.015  1018  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:12.025  7240  7240 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-29 10:24:12.025   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 10:24:12.025   278   984 D Netd    : getNetworkForDns: using netid 504 for uid 10011
08-29 10:24:12.025  7240  7240 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
08-29 10:24:12.025  7240  7240 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-29 10:24:12.025  7240  7240 D InitializeManagerStateMachine: exit::IDLE
08-29 10:24:12.025  7240  7240 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: entry::SUCCESS
08-29 10:24:12.035  7240  7240 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-29 10:24:12.035  7240  7240 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-29 10:24:12.035  7240  7240 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: exit::SUCCESS
08-29 10:24:12.035  7240  7240 D InitializeManagerStateMachine: entry::IDLE
,08-29 10:24:12.045  4663  4663 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 10:24:12.045  4663  7290 I iu.UploadsManager: num queued entries: 0
08-29 10:24:12.045  4663  7290 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-29 10:24:12.045  4663  7290 E SQLiteLog: (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
,08-29 10:24:12.055  1018  1454 I ActivityManager: Killing 4316:com.google.process.gapps/u0a11 (adj 15): empty #21
,08-29 10:24:12.055  7814  7814 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-29 10:24:12.065  7814  7814 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-29 10:24:12.065  7814  7814 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-29 10:24:12.075  1018  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 10:24:12.075  1018  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.AnalyticsService; callingUser = 0; userId(target) = 0
,08-29 10:24:12.075  1018  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-29 10:24:12.075  1018  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 10:24:12.075  1018  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 10:24:12.075  7814  7814 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-29 10:24:12.075  1018  1491 W ActivityManager: ProcessRecord{f8f1642 4316:com.google.process.gapps/u0a11} is already killed
,08-29 10:24:12.075  1018  1491 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-29 10:24:12.075   255   255 E lowmemorykiller: Error writing /proc/4316/oom_score_adj; errno=22
,08-29 10:24:12.075  1018  1491 I ActivityManager: Existing provider com.google.android.gsf/.gservices.GservicesProvider is crashing; detaching ProcessRecord{21adc2c7 4663:com.google.android.gms/u0a11}
,08-29 10:24:12.085  4663  5126 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-29 10:24:12.085  4663  5126 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-29 10:24:12.085  4663  5126 E GAv4-SVC: Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,08-29 10:24:12.085  4663  5126 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-29 10:24:12.085  4663  5126 E GAv4-SVC: Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-29 10:24:12.085  4663  4926 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
08-29 10:24:12.085  4663  4926 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,08-29 10:24:12.085  1018  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gsf
,08-29 10:24:12.085  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:12.085  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 10:24:12.085  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 10:24:12.085  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
