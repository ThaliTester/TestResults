#### Test 82203060198550b_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-24 14:03:33.080   291   291 E SMD     : DCD OFF
,08-24 14:03:33.950  6712  6712 D AndroidRuntime: 
08-24 14:03:33.950  6712  6712 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:03:33.960  6712  6712 D AndroidRuntime: CheckJNI is OFF
08-24 14:03:33.960  6712  6712 D AndroidRuntime: readGMSProperty: start
08-24 14:03:33.960  6712  6712 D AndroidRuntime: readGMSProperty: already setted!!
08-24 14:03:33.960  6712  6712 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 14:03:33.960  6712  6712 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:03:33.960  6712  6712 D AndroidRuntime: readGMSProperty: end
08-24 14:03:33.960  6712  6712 D AndroidRuntime: addProductProperty: start
08-24 14:03:34.090  6712  6712 E AffinityControl: AffinityControl: registerfunction enter
08-24 14:03:34.120  6712  6712 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 14:03:34.130  1016  1449 E PersonaManagerService: inState():  stateMachine is null !!
08-24 14:03:34.130  1016  1449 I PersonaManagerService: PersonaId don't exist
08-24 14:03:34.130  1016  1449 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-24 14:03:34.130  1016  1449 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-24 14:03:34.160  1016  1449 W ActivityManager: mDVFSHelper.acquire()
08-24 14:03:34.160   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-24 14:03:34.170   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-24 14:03:34.170  1016  1449 D FocusedStackFrame: Set to : 0
08-24 14:03:34.180  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:34.180  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:34.180  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:34.180  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:34.180  1016  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 14:03:34.180  1016  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-24 14:03:34.200  6723  6723 E Zygote  : MountEmulatedStorage()
08-24 14:03:34.200  6723  6723 E Zygote  : v2
08-24 14:03:34.200  6723  6723 I libpersona: KNOX_SDCARD checking this for 10171
08-24 14:03:34.200  6723  6723 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:34.200  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 14:03:34.200  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 14:03:34.200  6723  6723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:34.200  1016  1449 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6723 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:03:34.200  1016  1449 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 14:03:34.200  1016  1449 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:03:34.200  6723  6723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:34.200   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-24 14:03:34.200  6723  6723 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 14:03:34.200  1016  1449 D InputDispatcher: Focused application set to: xxxx
08-24 14:03:34.210  1016  1449 D InputDispatcher: Focus left window: 1483
08-24 14:03:34.210  6712  6712 D AndroidRuntime: Shutting down VM
08-24 14:03:34.210  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:03:34.210  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:34.230  6723  6723 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:34.230  6723  6723 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:34.230  1016  1722 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-24 14:03:34.240  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 14:03:34.250  1016  1016 V ActivityManager: Display changed displayId=0
08-24 14:03:34.260  1016  1722 D PersonaManager: isKioskContainerExistOnDevice
08-24 14:03:34.270  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-24 14:03:34.290   258  1097 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-24 14:03:34.290   258  1038 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-24 14:03:34.290  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{3ae31c5a token=android.os.BinderProxy@85dd063 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 14:03:34.290  1483  1483 D Launcher: onTrimMemory. Level: 20
08-24 14:03:34.380  6723  6723 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-24 14:03:34.400  6723  6723 I cr.library_loader: Time to load native libraries: 8 ms (timestamps 5387-5395)
08-24 14:03:34.400  6723  6723 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-24 14:03:34.410  6712  6712 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 14:03:34.430  6723  6723 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28c77e69}
,08-24 14:03:34.430  6723  6723 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 14:03:34.440  6723  6723 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 14:03:34.470  6723  6723 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 14:03:34.480  6723  6723 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:03:34.480  6723  6723 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 14:03:34.520  6723  6723 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 14:03:34.520  6723  6723 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 14:03:34.520  6723  6723 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 14:03:34.520  6723  6723 I Adreno-EGL: Local Branch: 
08-24 14:03:34.520  6723  6723 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 14:03:34.520  6723  6723 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 14:03:34.520  6723  6723 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 14:03:34.590  6723  6723 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 14:03:34.610  6723  6723 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 14:03:34.610  6723  6723 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 14:03:34.620  6723  6723 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 14:03:34.620  6723  6723 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 14:03:34.720  6723  6723 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:03:34.740  6723  6723 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 14:03:34.750  6723  6723 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-24 14:03:34.750  6723  6723 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-24 14:03:34.750  6723  6723 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-24 14:03:34.760  6723  6723 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:03:34.760  6723  6723 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:03:34.760  1016  1042 W ActivityManager: Activity pause timeout for ActivityRecord{37bf6fb5 u0 com.test.thalitest/.MainActivity t2}
,08-24 14:03:34.810  6723  6762 D OpenGLRenderer: Render dirty regions requested: true
,08-24 14:03:34.810  1016  1449 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-24 14:03:34.810  1016  1449 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 14:03:34.810  1016  1449 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-24 14:03:34.810  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 14:03:34.810  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 14:03:34.820  6723  6750 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-24 14:03:34.830  6723  6723 V ActivityThread: updateVisibility : ActivityRecord{706549 token=android.os.BinderProxy@32c3402 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-24 14:03:34.830  6723  6723 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 14:03:34.830  6723  6723 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-24 14:03:34.840   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-24 14:03:34.860  1016  1499 D InputDispatcher: Focus entered window: 6723
,08-24 14:03:34.860  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 14:03:34.860  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:03:34.870  6723  6723 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 14:03:34.870  6723  6762 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 14:03:34.870  6723  6762 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-24 14:03:34.870  6723  6762 D OpenGLRenderer: Enabling debug mode 0
,08-24 14:03:34.890  1016  1498 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 14:03:34.900  1175  1175 I StatusBar: Icon Only
,08-24 14:03:34.900  1175  1175 D PanelView: There is/are notification(s) 
,08-24 14:03:34.900  1016  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:03:34.910  1016  1047 I ActivityManager: Displayed Component not be shown by security: +652ms (total +734ms)
,08-24 14:03:34.910  1016  1047 W ActivityManager: mDVFSHelper.release()
08-24 14:03:34.910  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37bf6fb5 u0 com.test.thalitest/.MainActivity t2} time:105907
,08-24 14:03:34.920  6723  6723 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 14:03:34.920   258   454 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-24 14:03:34.920   258   456 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-24 14:03:34.920  6723  6723 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@32c3402 time:105912
,08-24 14:03:34.950  1879  1879 I SamsungIME: getCurrentCandidateView
,08-24 14:03:35.060  6723  6723 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6723
,08-24 14:03:35.080  1879  1879 D SamsungIME: Dismiss ExpandCandiate
,08-24 14:03:35.150  1016  1443 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 14:03:35.150  1016  1443 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:03:35.150  1016  1443 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 14:03:35.150  1016  1443 D BatteryService: stay LED for fully charged
08-24 14:03:35.150  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 14:03:35.160  1016  1016 I MotionRecognitionService: Plugged
,08-24 14:03:35.160  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:03:35.160  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 14:03:35.160  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:03:35.160  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 14:03:35.170  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:03:35.170  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:03:35.170  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:03:35.190  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 14:03:35.190  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-24 14:03:35.190  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 14:03:35.190  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-24 14:03:35.190  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 14:03:35.260  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 14:03:35.290  6723  6723 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 14:03:35.300  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 14:03:35.310  1879  1879 I SamsungIME: KeybaordView init() : load resources
,08-24 14:03:35.340  1879  1879 I SamsungIME: getCurrentKeyboard
,08-24 14:03:35.340  1879  1879 I SamsungIME: getTextKeyboard
,08-24 14:03:35.360  1879  1879 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-24 14:03:35.380  6723  6769 D jxcore_app_log: JniHelper::setJavaVM(0xb74bf2b0), pthread_self() = -1213941912
,08-24 14:03:35.390  6723  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:03:35.390  6723  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:03:35.390  6723  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:03:35.390  6723  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:03:35.390  6723  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 14:03:35.390  6723  6769 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d2d7967 added. We now have 1 listener(s)
,08-24 14:03:35.390  6723  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-24 14:03:35.400  6723  6769 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-24 14:03:35.400  6723  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:03:35.400  6723  6769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:03:35.410  6723  6769 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@349da1b2 added. We now have 1 listener(s)
,08-24 14:03:35.410  6723  6769 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:03:35.410  6723  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:03:35.410  6723  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:03:35.410  6723  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:03:35.410  6723  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:03:35.410  6723  6769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 14:03:35.420  6723  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:03:35.420  6723  6769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-24 14:03:35.420  6723  6769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:03:35.420  6723  6769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:03:35.420  6723  6769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:03:35.420  6723  6769 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:03:35.420  6723  6769 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 14:03:35.430  6723  6723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:03:35.430  6723  6723 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:03:35.460  6723  6723 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:03:36.020  6723  6776 W jxcore-log: Initializing JXcore engine
08-24 14:03:36.020  6723  6776 W jxcore-log: JXcore engine is ready
,08-24 14:03:36.080  2018  2018 E audit   : type=1400 msg=audit(1472040216.080:205): avc:  denied  { ioctl } for  pid=6776 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 14:03:36.080  2018  2018 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:36.080  2018  2018 E audit   : type=1300 msg=audit(1472040216.080:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9e6ff8f8 items=0 ppid=310 ppcomm=main pid=6776 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-24 14:03:36.080  2018  2018 E audit   : type=1320 msg=audit(1472040216.080:205): 
,08-24 14:03:36.080   291   291 E SMD     : DCD OFF
,08-24 14:03:36.090  6723  6776 W jxcore-log: Starting JXcore engine,
,08-24 14:03:36.200  6723  6776 W jxcore-log: Platform android
08-24 14:03:36.200  6723  6776 W jxcore-log: 
08-24 14:03:36.200  6723  6776 W jxcore-log: Process ARCH arm
08-24 14:03:36.200  6723  6776 W jxcore-log: 
,08-24 14:03:36.410  6723  6776 I jxcore-log: JXcore Cordova bridge is ready!,
08-24 14:03:36.410  6723  6776 I jxcore-log: 
08-24 14:03:36.410  6723  6776 W jxcore-log: JXcore engine is started
,08-24 14:03:36.410  6723  6769 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:03:36.420  6723  6723 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 14:03:37.080  1016  1321 E Watchdog: !@Sync 3,
,08-24 14:03:38.140   330   330 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-24 14:03:38.140   330   330 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 14:03:39.080   291   291 E SMD     : DCD OFF,
,08-24 14:03:40.610  1016  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-24 14:03:41.040  1016  3369 D SSRM:n  : SIOP:: AP = 330,
,08-24 14:03:42.080   291   291 E SMD     : DCD OFF
,08-24 14:03:43.140   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:03:43.810  5615  5615 D FactoryTest: Not factory mode
,08-24 14:03:43.810  5615  5615 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-24 14:03:43.810  5615  5615 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-24 14:03:43.810  5615  5615 D MTPRx   : still no open session command from host, so toast
,08-24 14:03:43.820  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-24 14:03:43.820  5615  5615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-24 14:03:43.820  5615  5615 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114815
08-24 14:03:43.820  1016  1482 E PersonaManagerService: inState():  stateMachine is null !!
08-24 14:03:43.820  1016  1482 I PersonaManagerService: PersonaId don't exist
08-24 14:03:43.820  1016  1482 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false,
,08-24 14:03:43.830  1016  1482 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-24 14:03:43.830  1016  1482 W ActivityManager: userId = 0, bbcId = -10000,
08-24 14:03:43.830  1016  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:43.830  1016  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-24 14:03:43.830  1016  1482 W ActivityManager: mDVFSHelper.acquire()
,08-24 14:03:43.850  1016  1482 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:43.850  1016  1482 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:03:43.850  1016  1482 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 14:03:43.850  1016  1482 D InputDispatcher: Focused application set to: xxxx
08-24 14:03:43.850  1016  1482 D InputDispatcher: Focus left window: 6723
,08-24 14:03:43.860  5615  5615 E MTPRx   : started activity for popup
,08-24 14:03:43.870  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 14:03:43.870  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:03:43.880  5615  5615 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-24 14:03:43.880  5615  5615 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-24 14:03:43.880  5615  5615 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 14:03:43.880  5615  5615 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:43.880  5615  5615 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:43.880  5615  5615 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 14:03:43.910  5615  5615 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-24 14:03:43.910  1016  1482 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 14:03:43.910  1016  1482 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-24 14:03:43.910  1016  1482 D InputDispatcher: Focused application set to: xxxx
,08-24 14:03:43.910  1016  1482 D InputDispatcher: Focus entered window: 6723
,08-24 14:03:43.920  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 14:03:43.920  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:03:43.920  1016  1498 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 14:03:43.920  1016  1498 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@53bd87c attribute=null, token = android.os.BinderProxy@2fd8c44c
,08-24 14:03:43.960  5615  5615 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-24 14:03:43.970  5615  5615 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-24 14:03:43.970  5615  5615 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-24 14:03:43.990  6723  6723 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 14:03:43.990  6723  6723 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-24 14:03:43.990  6723  6723 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 14:03:43.990  6723  6723 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-24 14:03:44.000  1016  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-24 14:03:44.000  1016  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 14:03:44.000  1016  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-24 14:03:44.000  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 14:03:44.000  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 14:03:44.010  6723  6723 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 14:03:44.010  6723  6723 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED,
,08-24 14:03:44.010  6723  6723 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@37cf819e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3e86cf87, 16908290=android.view.AbsSavedState$1@3e86cf87}, android:focusedViewId=100}]}],
08-24 14:03:44.010  6723  6723 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-24 14:03:44.010  6723  6723 V ActivityThread: updateVisibility : ActivityRecord{706549 token=android.os.BinderProxy@32c3402 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-24 14:03:44.010  6723  6723 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
08-24 14:03:44.010  6723  6723 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED,
08-24 14:03:44.010  6723  6723 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@32c3402 time:115009
,08-24 14:03:44.030  1016  1498 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:44.140   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:03:44.230  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 14:03:44.390  6723  6776 E jxcore  : Error!: syntax error
08-24 14:03:44.390  6723  6776 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"14","_columnNumber":"19","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"}]
,08-24 14:03:44.400  6723  6723 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-24 14:03:44.400  6723  6723 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-24 14:03:44.400  1016  1729 D FocusedStackFrame: Set to : 0
08-24 14:03:44.400  1016  1729 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:03:44.400  1016  1729 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 14:03:44.400  1016  1729 D InputDispatcher: Focused application set to: xxxx
08-24 14:03:44.410  1016  1729 D InputDispatcher: Focus left window: 6723
08-24 14:03:44.410  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:03:44.410  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:03:44.410  1016  1729 I ActivityManager: Killing 6428:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-24 14:03:44.420  6723  6769 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,08-24 14:03:44.420  6723  6723 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 14:03:44.420  6723  6723 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-24 14:03:44.420  6723  6723 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:03:44.420  6723  6723 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:03:44.420  6723  6723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:03:44.420  6723  6723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:03:44.420  6723  6723 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d2d7967 removed from the list
08-24 14:03:44.420  6723  6723 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:03:44.420  6723  6723 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@349da1b2 removed from the list
08-24 14:03:44.420  6723  6723 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:03:44.420  6723  6723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-24 14:03:44.420  6723  6723 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 14:03:44.430   258   456 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-24 14:03:44.430   258  1097 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-24 14:03:44.450  1016  1029 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-24 14:03:44.470  1483  1483 D Launcher: onRestart, Launcher: 908764188
,08-24 14:03:44.470  1483  1483 D Launcher: onStart, Launcher: 908764188
08-24 14:03:44.470  1483  1483 D Launcher.HomeView: onStart
,08-24 14:03:44.470  1483  1483 D Launcher: onResume, Launcher: 908764188
,08-24 14:03:44.470  1016  1722 D SettingsProvider: name = kids_home_mode
,08-24 14:03:44.470  1016  1722 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 14:03:44.470  1016  1722 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 14:03:44.470  1016  1722 D SettingsProvider: selectionArgs: false
,08-24 14:03:44.470  1016  1722 D SettingsProvider: selectionArgs: 10006
,08-24 14:03:44.470  1016  1722 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 14:03:44.470  1016  1722 D SettingsProvider: ret = -1
08-24 14:03:44.470  1483  1483 D Launcher.HomeView: onResume
,08-24 14:03:44.480  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-24 14:03:44.480  1483  1483 D MenuAppsGridFragment: onResume
08-24 14:03:44.480  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-24 14:03:44.490  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.490  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.490  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-24 14:03:44.490  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-24 14:03:44.490  1016  1223 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-24 14:03:44.490  1016  1223 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-24 14:03:44.490  1016  1223 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.490  1016  1223 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-24 14:03:44.490  1016  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.490  1016  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-24 14:03:44.500  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.500  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.500  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.500  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.510  6786  6786 E Zygote  : MountEmulatedStorage()
08-24 14:03:44.510  6786  6786 E Zygote  : v2
08-24 14:03:44.510  6786  6786 I libpersona: KNOX_SDCARD checking this for 10039
,08-24 14:03:44.510  6786  6786 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:44.510  1016  1223 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6786 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-24 14:03:44.520  6786  6786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:44.520  1016  1029 D ActivityManager: handle home activity for 0
08-24 14:03:44.520  1016  1029 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-24 14:03:44.520  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-24 14:03:44.520  1016  1029 D KnoxTimeoutHandler: post home show event for user 0
08-24 14:03:44.520  1016  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 14:03:44.520  1016  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 14:03:44.520  1016  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 14:03:44.520  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-24 14:03:44.520  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,08-24 14:03:44.520  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 14:03:44.520  1483  1483 D Launcher.HomeView: onPause
08-24 14:03:44.520  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-24 14:03:44.520  6786  6786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:44.520  6786  6786 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:44.520  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.520  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.520  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-24 14:03:44.530  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.530  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-24 14:03:44.530  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.530  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-24 14:03:44.530  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.530  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.530  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.530  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.550  6800  6800 E Zygote  : MountEmulatedStorage(),
08-24 14:03:44.550  6800  6800 E Zygote  : v2
,08-24 14:03:44.550  6800  6800 I libpersona: KNOX_SDCARD checking this for 10089
08-24 14:03:44.550  6800  6800 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:44.550  6800  6800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:44.550  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6800 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-24 14:03:44.550  6800  6800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:44.550  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.550  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
08-24 14:03:44.550  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.550  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-24 14:03:44.560  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.560  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.560  6800  6800 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-24 14:03:44.560  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.560  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.560  6786  6786 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:44.560  6786  6786 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.580  6816  6816 E Zygote  : MountEmulatedStorage()
,08-24 14:03:44.580  6816  6816 E Zygote  : v2
08-24 14:03:44.580  6816  6816 I libpersona: KNOX_SDCARD checking this for 10139
08-24 14:03:44.580  6816  6816 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:44.580  6816  6816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:44.580  6800  6800 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-24 14:03:44.580  6800  6800 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.590  6816  6816 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:44.590  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6816 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,08-24 14:03:44.590  6816  6816 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:44.610  6816  6816 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:44.610  6816  6816 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.610   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-24 14:03:44.610  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-24 14:03:44.620  1016  1722 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.620  1016  1722 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1483, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-24 14:03:44.620  1016  1722 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.620  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 14:03:44.620  1016  1722 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-24 14:03:44.620  6800  6800 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:44.620  6800  6800 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-24 14:03:44.620  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.620  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.620  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-24 14:03:44.620  1016  1482 D InputDispatcher: Focus entered window: 1483
08-24 14:03:44.630  2552  2552 D Recents_RecreateReceiver: onReceive by home
,08-24 14:03:44.630  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:03:44.630  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:03:44.630  1016  1499 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.630  1016  1499 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-24 14:03:44.630  1016  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.630  1016  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
08-24 14:03:44.630  1483  1483 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 14:03:44.630  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.630  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.630  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.630  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.630  6786  6786 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 14:03:44.630  6786  6786 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:44.630  6786  6786 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:44.630  6786  6786 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-24 14:03:44.630  6786  6786 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 14:03:44.630  6786  6786 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-24 14:03:44.630  6786  6786 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 14:03:44.640  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{3ae31c5a token=android.os.BinderProxy@85dd063 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-24 14:03:44.640  1483  1483 D Launcher.HomeView: onStop
,08-24 14:03:44.650  1016  1223 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 14:03:44.650  1016  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:03:44.650  6833  6833 E Zygote  : MountEmulatedStorage()
08-24 14:03:44.650  6833  6833 I libpersona: KNOX_SDCARD checking this for 10084
08-24 14:03:44.650  6833  6833 E Zygote  : v2
08-24 14:03:44.650  6833  6833 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:44.650  6833  6833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:44.650  6723  6723 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-24 14:03:44.660  6833  6833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:44.660  1879  1879 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-24 14:03:44.660  1016  1499 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6833 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-24 14:03:44.660  1175  1175 I StatusBar: Icon Only
08-24 14:03:44.660  1175  1175 D PanelView: There is/are notification(s) 
,08-24 14:03:44.670  6833  6833 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-24 14:03:44.670  6816  6816 V TaskCloserActivity: TaskCloserActivity enter()
,08-24 14:03:44.680  1483  1483 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@85dd063 time:115678
,08-24 14:03:44.690  6816  6816 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME,
08-24 14:03:44.690  1016  1223 I ActivityManager: Killing 6322:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-24 14:03:44.690  1016  1223 W ActivityManager: userId = 0, bbcId = -10000,
08-24 14:03:44.690  1016  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.690  1016  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
08-24 14:03:44.700  6784  6784 D AndroidRuntime: 
08-24 14:03:44.700  6784  6784 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:03:44.700  6784  6784 D AndroidRuntime: CheckJNI is OFF
08-24 14:03:44.700  6784  6784 D AndroidRuntime: readGMSProperty: start
08-24 14:03:44.700  6784  6784 D AndroidRuntime: readGMSProperty: already setted!!
,08-24 14:03:44.700  6784  6784 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 14:03:44.700  6784  6784 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:03:44.700  6784  6784 D AndroidRuntime: readGMSProperty: end
08-24 14:03:44.700  6784  6784 D AndroidRuntime: addProductProperty: start
,08-24 14:03:44.710  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:44.710  1016  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-24 14:03:44.710  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:44.710  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,08-24 14:03:44.710  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.710  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.710  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:44.710  1016  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:44.720  6833  6833 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:44.730  6833  6833 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.730  6851  6851 E Zygote  : MountEmulatedStorage(),
08-24 14:03:44.730  6851  6851 E Zygote  : v2
08-24 14:03:44.730  6851  6851 I libpersona: KNOX_SDCARD checking this for 10135
08-24 14:03:44.730  6851  6851 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:44.740  6851  6851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:44.740  6851  6851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:44.740  1016  1498 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6851 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,08-24 14:03:44.740  6851  6851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:44.740  1016  1498 I ActivityManager: Killing 6460:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-24 14:03:44.750  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{299a63e7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:115748
08-24 14:03:44.750  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-24 14:03:44.750  1016  1047 W ActivityManager: mDVFSHelper.release()
,08-24 14:03:44.760  6851  6851 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:44.770  6851  6851 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:44.770  6833  6833 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:44.780  1016  1443 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:44.790  6851  6851 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,08-24 14:03:44.790  6851  6851 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 14:03:44.790  6851  6851 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-24 14:03:44.790  6851  6851 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-24 14:03:44.790  6851  6851 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 14:03:44.800  1016  1440 I ActivityManager: Killing 6510:com.samsung.android.sm/1000 (adj 15): empty #21
,08-24 14:03:44.840  1016  1729 I ActivityManager: Killing 6474:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-24 14:03:44.850  6786  6786 D NearbySource: Nearby Source Create!
,08-24 14:03:44.850  6786  6786 D NearbyContext: Nearby Context Create!
,08-24 14:03:44.850  6784  6784 E AffinityControl: AffinityControl: registerfunction enter
,08-24 14:03:44.880  6784  6784 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:03:44.890   257   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/,
08-24 14:03:44.890  6786  6786 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-24 14:03:44.890   257   517 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 14:03:44.890  6786  6786 D SLinkSource: Samsung link source created,
,08-24 14:03:44.890  1016  1482 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-24 14:03:44.890  1016  1482 D PackageManager: START PACKAGE DELETE: observer{41204500}
08-24 14:03:44.890  1016  1482 D PackageManager: pkg{<packageName>}
08-24 14:03:44.890  1016  1482 D PackageManager: user{0}
08-24 14:03:44.890  1016  1482 D PackageManager: caller{2000}
08-24 14:03:44.890  1016  1482 D PackageManager: flags{2}
08-24 14:03:44.890  1016  1482 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-24 14:03:44.890  1016  1482 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-24 14:03:44.890  1016  1482 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 14:03:44.890  1016  1482 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-24 14:03:44.900  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-24 14:03:44.900  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-24 14:03:44.900  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-24 14:03:44.900  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-24 14:03:44.900  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-24 14:03:44.900  1016  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-24 14:03:44.920  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-24 14:03:44.930  1016  1042 I ActivityManager: Killing 6723:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-24 14:03:45.020  1016  1056 W PackageSettings: Skipping PackageSetting{30b60c79 com.example.hello/10168} due to missing metadata
,08-24 14:03:45.050  1016  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,08-24 14:03:45.060  1016  1722 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:03:45.060  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
08-24 14:03:45.060  6786  6786 D GalleryCacheReady: Receive : home resume
,08-24 14:03:45.080  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-24 14:03:45.090   291   291 E SMD     : DCD OFF
,08-24 14:03:45.100  6786  6876 D ContactProvider: getAllContactInfoList Start
,08-24 14:03:45.100  2638  2638 I art     : Explicit concurrent mark sweep GC freed 19457(1111KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 791us total 31.179ms
,08-24 14:03:45.120  1016  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:03:45.130  4792  4792 I art     : Explicit concurrent mark sweep GC freed 2325(95KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/16MB, paused 1.135ms total 62.751ms
,08-24 14:03:45.140  1879  1879 E SamsungIME: mOCRHelper is null
,08-24 14:03:45.150   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:03:45.150  2045  2215 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 14:03:45.170  1456  1456 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 14:03:45.170  1016  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-24 14:03:45.170  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:03:45.170  1016  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-24 14:03:45.170  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-24 14:03:45.170  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:03:45.180  1016  1440 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.180  1016  1440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:03:45.180  1016  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-24 14:03:45.180  1016  1123 V NetworkStats: performPollLocked() took 11ms
08-24 14:03:45.180  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:03:45.200  6057  6057 D Mms/UIEventReceiver: ui event
,08-24 14:03:45.210  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:03:45.210  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:03:45.210  1016  1223 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-24 14:03:45.220  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:45.220  1016  1223 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.220  1016  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:45.220  1016  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-24 14:03:45.220  1016  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 14:03:45.220  1016  1223 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4316, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:03:45.220  1016  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 14:03:45.220  1016  1223 D BatteryService: stay LED for fully charged
,08-24 14:03:45.220  1441  1441 D RegisteredServicesCache: empty dynamic service
,08-24 14:03:45.230  6816  6816 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-24 14:03:45.250  2873  2873 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 24 14:03:45 GMT+02:00 2016
,08-24 14:03:45.250  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-24 14:03:45.250  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:03:45.250  1016  1449 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-24 14:03:45.250  1016  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-24 14:03:45.250  1016  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.250  1016  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:45.250  1016  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-24 14:03:45.270  1016  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-24 14:03:45.270  1016  1029 D SecContentProvider2: mCursor = null
,08-24 14:03:45.270  2873  2873 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-24 14:03:45.270  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-24 14:03:45.270  1016  1482 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-24 14:03:45.270  1016  1482 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-24 14:03:45.270  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-24 14:03:45.280  1016  1041 W TextServicesManagerService: no available spell checker services found
,08-24 14:03:45.290  6636  6636 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-24 14:03:45.290  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-24 14:03:45.290  2873  2873 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-24 14:03:45.290  1016  1016 I art     : Explicit concurrent mark sweep GC freed 49517(3MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/37MB, paused 6.669ms total 214.046ms
08-24 14:03:45.290  1016  1722 I TactileAssist: enable value -1
08-24 14:03:45.290  1016  1722 I TactileAssist: internal enable value -1
08-24 14:03:45.290  1016  1722 I TactileAssist: intensity value -1
,08-24 14:03:45.290  1016  1722 I TactileAssist: saveAppList value true
,08-24 14:03:45.290  1016  1056 I art     : WaitForGcToComplete blocked for 148.938ms for cause Explicit
,08-24 14:03:45.300  1016  1722 I TactileAssist: List of disabled apps :
,08-24 14:03:45.300  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.300  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.300  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.300  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.310  6879  6879 E Zygote  : MountEmulatedStorage()
08-24 14:03:45.310  6879  6879 E Zygote  : v2
08-24 14:03:45.310  6879  6879 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:45.310  6879  6879 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.310  6879  6879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:45.310  6879  6879 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:45.320  6879  6879 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-24 14:03:45.320  1016  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6879 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 14:03:45.320  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.320  2873  2873 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 14:03:45.320  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-24 14:03:45.320  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.320  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.320  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.320  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.330  2873  2873 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 14:03:45.330  2873  6878 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-24 14:03:45.340  6891  6891 E Zygote  : MountEmulatedStorage()
08-24 14:03:45.340  6891  6891 E Zygote  : v2
08-24 14:03:45.340  6891  6891 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:45.340  6891  6891 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:45.340  6891  6891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:45.340  1016  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6891 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 14:03:45.340  1016  1440 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-24 14:03:45.340  1016  1440 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-24 14:03:45.350  1016  1440 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.350  1016  1440 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:03:45.350  1016  1440 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-24 14:03:45.350  6891  6891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:45.350  6891  6891 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:45.350  2873  6878 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-24 14:03:45.350  2873  6878 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-24 14:03:45.360  6636  6636 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-24 14:03:45.360  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.360  2873  6878 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-24 14:03:45.360  6636  6636 D elm:15121: ElmAgentService : onCreate()
,08-24 14:03:45.360  6636  6901 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-24 14:03:45.360  6636  6901 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-24 14:03:45.360  6636  6901 D elm:15121: MDMBridge.getInstance()
08-24 14:03:45.360  6636  6901 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-24 14:03:45.370  6636  6901 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-24 14:03:45.370  6879  6879 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.380  6879  6879 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.380  6891  6891 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.380  6891  6891 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.390  6636  6636 D elm:15121: ElmAgentService : onDestroy().
,08-24 14:03:45.400  1016  1499 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-24 14:03:45.400  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.400  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.400  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.400  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.420  6911  6911 E Zygote  : MountEmulatedStorage()
08-24 14:03:45.420  6911  6911 I libpersona: KNOX_SDCARD checking this for 10048
08-24 14:03:45.420  6911  6911 E Zygote  : v2
08-24 14:03:45.420  6911  6911 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:45.420  6911  6911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:45.420  6911  6911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:03:45.420  6911  6911 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-24 14:03:45.430  1016  1499 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6911 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-24 14:03:45.440  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-24 14:03:45.440  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-24 14:03:45.440  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-24 14:03:45.440  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-24 14:03:45.440  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-24 14:03:45.440  6786  6876 D ContactProvider: getAllContactInfoList End
,08-24 14:03:45.440  6911  6911 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.440  6911  6911 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.450  6786  6876 I syncContacts: thread: 1228, sync time = 518
,08-24 14:03:45.450  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-24 14:03:45.460  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-24 14:03:45.460  6891  6891 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-24 14:03:45.460  1016  1499 D SecContentProvider2: uri = -1 selection = getSealedState
08-24 14:03:45.460  1016  1499 D SecContentProvider2: mCursor = null
,08-24 14:03:45.470  6891  6891 I PopupuiReceiver_KNOX: getSealedState : true
,08-24 14:03:45.470  1016  1482 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-24 14:03:45.470  1016  1482 D SecContentProvider2: mCursor = null
,08-24 14:03:45.470  6891  6891 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-24 14:03:45.470  1016  1135 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-24 14:03:45.470  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-24 14:03:45.470  1016  1135 D SecContentProvider2: mCursor = null
,08-24 14:03:45.470  1016  1223 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-24 14:03:45.480  6891  6891 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-24 14:03:45.480  6891  6891 D PopupuiReceiver: Action package removed
08-24 14:03:45.480  1016  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-24 14:03:45.480  1016  1223 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.480  1016  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:45.480  1016  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-24 14:03:45.480  2873  6878 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-24 14:03:45.480  1016  1482 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-24 14:03:45.480  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.480  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.480  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.480  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.500  6927  6927 E Zygote  : MountEmulatedStorage(),
08-24 14:03:45.500  6927  6927 E Zygote  : v2
08-24 14:03:45.500  6927  6927 I libpersona: KNOX_SDCARD checking this for 10145
08-24 14:03:45.500  6927  6927 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.500  6927  6927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 14:03:45.500  2873  6878 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-24 14:03:45.500  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.500  6927  6927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:45.500  1016  1482 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6927 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:03:45.500  6927  6927 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:45.500  1016  1482 I ActivityManager: Killing 6547:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-24 14:03:45.510  1016  1482 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-24 14:03:45.510  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.510  6911  6911 D Compatibility: onReceive() it will make start service
,08-24 14:03:45.510  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.510  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.510  1016  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.530  6941  6941 E Zygote  : MountEmulatedStorage()
,08-24 14:03:45.530  2873  6878 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-24 14:03:45.530  6941  6941 E Zygote  : v2
08-24 14:03:45.530  6941  6941 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:45.530  6941  6941 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.530  6941  6941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:03:45.530  1016  1482 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 14:03:45.540  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-24 14:03:45.540  6927  6927 D ActivityThread: Added TimaKeyStore provider,
08-24 14:03:45.540  1016  1499 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-24 14:03:45.540  1016  1499 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-24 14:03:45.540  6941  6941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:45.540  6941  6941 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-24 14:03:45.540  1016  1499 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.540  1016  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:45.540  1016  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-24 14:03:45.550  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:03:45.550  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 14:03:45.560  2873  2873 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-24 14:03:45.560  1016  1481 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-24 14:03:45.560   310   310 I art     : Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 632us total 25.507ms
,08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 14:03:45.560  6911  6957 D Compatibility: onHandleIntent()
08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-24 14:03:45.560  6911  6957 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-24 14:03:45.560  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 14:03:45.570  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.570  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.570  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.570  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.570  6911  6957 D Compatibility: found: 2
,08-24 14:03:45.580  6911  6957 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-24 14:03:45.580   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 18.742ms
,08-24 14:03:45.580  6911  6957 D Compatibility: skipping ResolveInfo{14dfee97 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-24 14:03:45.580  6941  6941 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:45.580  6911  6957 D Compatibility: considering ResolveInfo{3dd4c884 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-24 14:03:45.580  6911  6957 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-24 14:03:45.580  6941  6941 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.590  6911  6957 D Compatibility: enabling receiver ResolveInfo{2c9c86d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-24 14:03:45.590  1016  1041 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,08-24 14:03:45.590  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.590  6911  6957 D Compatibility: enabling receiver ResolveInfo{1c49bca2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-24 14:03:45.600   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.878ms
,08-24 14:03:45.600  1016  1056 I art     : Explicit concurrent mark sweep GC freed 17403(1108KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 6.343ms total 305.701ms
,08-24 14:03:45.600  6911  6957 D Compatibility: enabling receiver ResolveInfo{a2add33 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-24 14:03:45.610  6960  6960 E Zygote  : MountEmulatedStorage()
08-24 14:03:45.610  6960  6960 I libpersona: KNOX_SDCARD checking this for 10052
08-24 14:03:45.610  6960  6960 E Zygote  : v2
08-24 14:03:45.610  6960  6960 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.610  6960  6960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:45.610  6960  6960 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:45.610  1016  1481 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6960 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-24 14:03:45.610  6960  6960 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:03:45.620  6911  6957 D Compatibility: enabling receiver ResolveInfo{2c17e8f0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-24 14:03:45.630  6911  6957 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-24 14:03:45.630  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:03:45.630  1016  3369 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 14:03:45.630  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-24 14:03:45.640  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-24 14:03:45.640  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 14:03:45.640  6960  6960 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.640  6960  6960 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.650  6927  6927 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-24 14:03:45.650  6927  6927 D ThemeInfoUtil: isCurrentFestival = false
,08-24 14:03:45.650  1016  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-24 14:03:45.660  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 14:03:45.660  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:03:45.660  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 14:03:45.660  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:03:45.670  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 14:03:45.670  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-24 14:03:45.670  6941  6941 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:45.670  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 14:03:45.670  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:03:45.670  3178  3280 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:03:45.680  1016  1499 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-24 14:03:45.680  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.680  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.680  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.680  1016  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.690  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 14:03:45.690  6975  6975 E Zygote  : MountEmulatedStorage()
08-24 14:03:45.690  6975  6975 E Zygote  : v2
08-24 14:03:45.690  6975  6975 I libpersona: KNOX_SDCARD checking this for 10148
08-24 14:03:45.690  6975  6975 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.690  6975  6975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 14:03:45.690  1016  1499 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6975 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
08-24 14:03:45.690  1016  1499 I ActivityManager: Killing 6561:com.osp.app.signin/u0a36 (adj 15): empty #21
08-24 14:03:45.700  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-24 14:03:45.700  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-24 14:03:45.700  6975  6975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:45.700  6975  6975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:45.700  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.700  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.700  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.700  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.710  6941  6941 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-24 14:03:45.720  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6984 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-24 14:03:45.720  1016  1028 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-24 14:03:45.720  6984  6984 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:45.720  1016  1028 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-24 14:03:45.720  6984  6984 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.720  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-24 14:03:45.720  6984  6984 E Zygote  : MountEmulatedStorage()
08-24 14:03:45.720  6984  6984 E Zygote  : v2
08-24 14:03:45.720  6984  6984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:45.730  6984  6984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:45.730  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-24 14:03:45.730  6984  6984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:45.730  6975  6975 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:45.730  6975  6975 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.740  1016  1029 I ActivityManager: Killing 6575:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-24 14:03:45.740  1016  1029 I ActivityManager: Killing 6594:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-24 14:03:45.750  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-24 14:03:45.760  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:03:45.760  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.760  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.760  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.780  7001  7001 E Zygote  : MountEmulatedStorage(),
08-24 14:03:45.780  7001  7001 I libpersona: KNOX_SDCARD checking this for 10087
08-24 14:03:45.780  7001  7001 E Zygote  : v2,
08-24 14:03:45.780  7001  7001 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.780  7001  7001 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:03:45.780  7001  7001 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:45.780  7001  7001 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:03:45.780  1016  1029 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7001 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-24 14:03:45.780  1016  1029 I ActivityManager: Killing 6529:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-24 14:03:45.800  6984  6984 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.810  6984  6984 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.810  1016  1056 D PackageManager: delete codoeFile: 
08-24 14:03:45.810  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.810  1016  1482 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-24 14:03:45.810  1016  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-24 14:03:45.810  1016  1482 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.810  1016  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:45.810  1016  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-24 14:03:45.820  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.820  6975  6975 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-24 14:03:45.830  7001  7001 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:03:45.830  1016  1135 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-24 14:03:45.830  1016  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-24 14:03:45.830  1016  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-24 14:03:45.830  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-24 14:03:45.830  7001  7001 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:45.830  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.830  1016  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:45.830  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-24 14:03:45.830  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:45.830  1016  1056 D PackageManager: result of delete: 1{41204500}
,08-24 14:03:45.840  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-24 14:03:45.840  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:45.840  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:45.840  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:45.840  6784  6784 D AndroidRuntime: Shutting down VM
,08-24 14:03:45.850  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 14:03:45.850  1016  1056 D PackageManager: userId{-1}
08-24 14:03:45.850  1016  1056 D PackageManager: andCode{true}
,08-24 14:03:45.860  1016  1016 I MotionRecognitionService: Plugged
08-24 14:03:45.860  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:03:45.870  1016  1223 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-24 14:03:45.870  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.870  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.870  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.870  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.870  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.880  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.880  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:45.880  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-24 14:03:45.880  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:45.880  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 14:03:45.880  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-24 14:03:45.880  7022  7022 E Zygote  : MountEmulatedStorage()
,08-24 14:03:45.880  7022  7022 I libpersona: KNOX_SDCARD checking this for 10055
08-24 14:03:45.880  7022  7022 E Zygote  : v2
,08-24 14:03:45.880  7022  7022 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:45.890  7022  7022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:45.890  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.890  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 14:03:45.890  7022  7022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:03:45.890  7022  7022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:03:45.890  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:03:45.890  6984  6984 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-24 14:03:45.890  6984  6984 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 14:03:45.890  6984  6984 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-24 14:03:45.890  1016  1223 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7022 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-24 14:03:45.900  1016  1481 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-24 14:03:45.900  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-24 14:03:45.900  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:45.900  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:03:45.900  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-24 14:03:45.900  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-24 14:03:45.910  1016  1135 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-24 14:03:45.920  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-24 14:03:45.920  1016  1722 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-24 14:03:45.920  7022  7022 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.920  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-24 14:03:45.920  7022  7022 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:45.920  1016  1722 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.920  1016  1722 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.930  6984  6984 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-24 14:03:45.930  6984  6984 I PCWCLIENTTRACE_PushUtil: sales region : global
08-24 14:03:45.930  1016  1722 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.930  6984  6984 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 14:03:45.930  1016  1722 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.930  6984  6984 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-24 14:03:45.940  7039  7039 E Zygote  : MountEmulatedStorage()
,08-24 14:03:45.940  7039  7039 E Zygote  : v2
08-24 14:03:45.940  7039  7039 I libpersona: KNOX_SDCARD checking this for 10152
08-24 14:03:45.940  7039  7039 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:45.940  7039  7039 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 14:03:45.940  1016  1722 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7039 uid=10152 gids={50152, 9997} abi=armeabi-v7a,
,08-24 14:03:45.950  7039  7039 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:45.950  1016  1440 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-24 14:03:45.950  7039  7039 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-24 14:03:45.950  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-24 14:03:45.950  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.950  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.950  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:45.950  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:45.980  7022  7022 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
08-24 14:03:45.980  1016  1028 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7055 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-24 14:03:45.980  7039  7039 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:45.980  7039  7039 D ActivityThread: Added TimaKeyStore provider,
,08-24 14:03:45.980  1016  1028 I ActivityManager: Killing 6613:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-24 14:03:45.980  7055  7055 E Zygote  : MountEmulatedStorage()
08-24 14:03:45.980  7055  7055 E Zygote  : v2
08-24 14:03:45.980  7055  7055 I libpersona: KNOX_SDCARD checking this for 10029
,08-24 14:03:45.980  7055  7055 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:45.990  7055  7055 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:45.990  1016  1028 I ActivityManager: Killing 6654:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-24 14:03:45.990  7055  7055 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:45.990  7055  7055 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:46.010  7055  7055 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:46.010  7055  7055 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:46.020  7022  7022 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-24 14:03:46.020  7039  7039 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-24 14:03:46.020  7039  7039 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
08-24 14:03:46.020  7022  7022 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-24 14:03:46.020  7022  7022 D UserAnalysis: Create SecureDbHelper
,08-24 14:03:46.030  7039  7039 I TapandpayWidget:Utils: Clear T&P info.
,08-24 14:03:46.030  7022  7022 D IntelligenceServiceApplication: onCreate()
,08-24 14:03:46.030  7022  7022 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-24 14:03:46.040  1016  1223 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-24 14:03:46.040  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:46.040  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:46.040  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:46.040  1016  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:46.040  7022  7022 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-24 14:03:46.050  7039  7039 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.,
,08-24 14:03:46.050  7073  7073 E Zygote  : MountEmulatedStorage()
08-24 14:03:46.050  7073  7073 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:03:46.050  7073  7073 E Zygote  : v2
08-24 14:03:46.050  7073  7073 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:46.050  7073  7073 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:46.060  7073  7073 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:46.060  6784  6784 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 14:03:46.060  7073  7073 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:03:46.060  1016  1223 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:03:46.070  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-24 14:03:46.060  1016  1223 I ActivityManager: Killing 6491:com.android.calendar/u0a131 (adj 15): empty #21
08-24 14:03:46.070  1016  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-24 14:03:46.070  1016  1729 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,08-24 14:03:46.080  5818  5818 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(302): Wear auto uninstall disabled for package com.test.thalitest
08-24 14:03:46.080  7073  7073 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:46.080  7073  7073 D ActivityThread: Added TimaKeyStore provider
08-24 14:03:46.080  1016  1135 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-24 14:03:46.080  1016  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,08-24 14:03:46.090  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:46.090  1016  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:46.090  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-24 14:03:46.090  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-24 14:03:46.100  1016  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-24 14:03:46.100  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:46.100  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:46.100  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:46.100  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:46.110  7073  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:03:46.110  7055  7090 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-24 14:03:46.120  7093  7093 E Zygote  : MountEmulatedStorage()
08-24 14:03:46.120  7093  7093 E Zygote  : v2
08-24 14:03:46.120  7093  7093 I libpersona: KNOX_SDCARD checking this for 10032
08-24 14:03:46.120  7093  7093 I libpersona: KNOX_SDCARD not a persona
,08-24 14:03:46.120  7093  7093 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:03:46.130  1016  1481 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7093 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:03:46.130  1016  1481 I ActivityManager: Killing 6669:com.google.android.gms:car/u0a11 (adj 15): empty #21
08-24 14:03:46.130  7093  7093 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:03:46.130  7093  7093 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 14:03:46.130  1016  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:03:46.130  1016  1135 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:03:46.130  1016  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:03:46.130  1016  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-24 14:03:46.140  2045  2045 D WearableService: callingUid 10011, callindPid: 2045
,08-24 14:03:46.150   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:03:46.160  1016  1498 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:03:46.160  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,08-24 14:03:46.160  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:03:46.160  1016  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-24 14:03:46.160  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:03:46.170  5818  5818 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 14:03:46.180  5818  5818 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-24 14:03:46.180  1016  1029 D LocationManagerService: getProviders()=[passive]
,08-24 14:03:46.190  7093  7093 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:03:46.200  7093  7093 D ActivityThread: Added TimaKeyStore provider
,08-24 14:03:46.200  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-24 14:03:46.200  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-24 14:03:46.200  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-24 14:03:46.210  2045  2045 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-24 14:03:46.210  2045  2045 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false,
08-24 14:03:46.210  2045  2045 D AndroidRuntime: Shutting down VM
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-24 14:03:46.210  7055  7090 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false,
08-24 14:03:46.210  7055  7090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-24 14:03:46.210  7055  7090 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.,
08-24 14:03:46.210  7055  7090 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-24 14:03:46.210  7055  7090 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-24 14:03:46.210  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-24 14:03:46.220  4792  7112 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-24 14:03:46.220  4792  7112 D AccountUtils: Clearing selected account for com.test.thalitest
,08-24 14:03:46.220  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-24 14:03:46.220  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-24 14:03:46.220  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,08-24 14:03:46.230  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-24 14:03:46.230  1016  1449 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
08-24 14:03:46.230  7022  7022 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-24 14:03:46.230  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:46.230  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:46.230  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:03:46.230  1016  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:03:46.240  7073  7073 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,08-24 14:03:46.240  7073  7073 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:03:46.240  7073  7073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:03:46.240  7055  7090 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-24 14:03:46.240  7073  7073 D AndroidRuntime: Shutting down VM
08-24 14:03:46.240  7055  7090 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-24 14:03:46.240  7073  7073 E AndroidRuntime: FATAL EXCEPTION: main
08-24 14,:03:46.240  7073  7073 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7073
08-24 14:03:46.240  7073  7073 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:159)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:66)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-24 14:03:46.240  7073  7073 E AndroidRuntime: 	... 9 more
08-24 14:03:46.240  7055  7090 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 14:03:46.240  7055  7090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:03:46.240  7055  7090 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:03:46.240  7055  7090 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-24 14:03:46.250  7115  7115 E Zygote  : MountEmulatedStorage()
08-24 14:03:46.250  7115  7115 E Zygote  : v2
08-24 14:03:46.250  7115  7115 I libpersona: KNOX_SDCARD checking this for 10014
08-24 14:03:46.250  7115  7115 I libpersona: KNOX_SDCARD not a persona
08-24 14:03:46.250  1016  1449 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7115 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
08-24 14:03:46.250  7115  7115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:03:46.260  7115  7115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:03:46.260  7115  7115 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:03:46.260  7022  7022 D BluetoothAdapter: cancelDiscovery
08-24 14:03:46.270  4792  7112 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-24 14:03:46.270  1016  1729 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
08-24 14:03:46.280  1016  1482 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: com.google.android.location.util.PreferenceService
08-24 14:03:46.280  1016  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0

```
